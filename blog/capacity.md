# Managing Software Capacity
What does it mean to "manage" it?  Basically, for the various components, it is a cycle of:

- Characterize ::= Diagram 
- Measure ::= Instrument
- Analyze ::=   Understand key metrics 
- Forecast ::=  Build models for estimation 
- Adjust ::= Optimize for efficiency

Note: Symbol ::= means "may be replaced with" in Backus-Naur Form (BNF)

## Characterize
Diagram the system architecture (date your diagrams as change is constant).  Focus on the key component flows of the system, with

- description
- downstream dependencies 
- upstream triggers (& SLA, if known)
- external scale drivers for this flow
- peak periods

## Measure
Lord Kelvin said "To measure is to know".   Some tips to consider:

- Ensure you have a durable storage location for trend metrics. Based on your needs, you many consider high availability in your storage (and collection).
- Start simple, with key metrics.
- Use common metrics collection platforms, if possible.
- Also collect metrics from upstream systems, critical for forecasting your system capacity.

## Analyze
Metrics are only numbers.  The hard part is understanding which ones to collect, and what they mean:

- Start with basic metrics, and understand how they change over time. CPU, Disk IO waits, Storage Capacity, Available Memory, Network bandwidth can usually be collected for any monitored system.
- For the key component flows, compare the throughput to the upstream trend metrics. Look for user-driven traffic, as well as batch job-driven traffic, in order to understand usage patterns and impact.
- Simplify upstream metrics to a few basic metrics that given rough approximations of downstream impact, as complete characterization of upstream load is unlikely.
- Analyze the limitations of your resources, as well, given your specific load examples and patterns. For example, RabbitMQ may benchmark at 1500 150KB msgs/sec on a specific system, however, a typical use at your company could include 1MB messages that invalidate the benchmark.

## Forecast
Forecasting is not a black art. First, answer your basic capacity question: do I have adequate capacity to keep my system running? Specifically:

- What traffic should my key component flows be experiencing at this time?
- What limitations will my key component flows hit (and when)?

Simple forecasting can be done with models in spreadsheets. After you tire of updating spreadsheets, consider automation:

- Provide a user experience that shows your model's forecasts in a way that can be easily consumed by the owners of the system (e.g., charts).
- Provide the current actuals, on the same chart, to understand when your forecast assumptions are incorrect.
- (Stretch goal) Provide APIs surfacing capacity for a given timeframe, allowing automated scale up/down the given system.

## Adjust

Capacity management is about efficient use of resources (and since resources aren't free, it's all about optimizing cost).  I suggest the following crawl/walk/run phases:

- Crawl: Perform basic analysis/provisioning to ensure that the given system has adequate capacity based on predicted demand, for the appropriate forecast cycle. Excess capacity is very likely for many periods within the forecast cycle.
- Walk: Perform periodic manual adjustments based on capacity models, to accommodate peak demand in the shorter forecast cycle.  Example: I scale up capacity manually for the big event, only during that event.
- Run: Perform automated capacity adjustments based on capacity models, based on the periodic demand throughout the day. 

Over time, you will determine that your capacity model's accuracy drifts from the actuals.   It is important to periodically re-analyze the inputs, as well as their effect on the key component flows, as: 

- A change in upstream behavior may impact your flow (e.g., calling your flow 2x instead of 1x).
- A regression in your key component flow impacts the capacity limits (self-inflicted). 
- A change in a downstream flow impacts resources required by your key component flow (collateral damage). 
