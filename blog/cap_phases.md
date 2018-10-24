# Capacity Measurement

I've been part of the creation and evolution of many different commercial software systems. After you've seen the same patterns occur over and over again, you begin to recognize the signs...

## Evolution

I believe there are basically four phases of software system evolution.  There is a hidden phase 0 (of course) when the software is being created, but it has to launch in order to make it to level one.  The phases are:

1. "V1.0: It is alive!"  This phase is characterized by the delivery of initial functionality.  Pioneering users interact with the software, perhaps even as the designers intended. Software teams are delighted that all the hard work has paid off. The teams are dismayed to find that they have no way to determine how many users are interacting with their system, and why the system is breaking down so often. Initial capacity estimates were just a (SWA) guess, so capacity issues are encountered as well.
2. "V1.1: It is stable!"  Software teams have (quickly?) added monitoring and alerting to determine how the software is performing, fixing the common issues encountered on most of the paths. More established users recognize the stability of the point release (.1) and become customers. With monitoring comes awareness, and teams over-provision their systems (e.g., 2x) to avoid capacity issues.
3. "V1.5:  Starting capacity management"  After costs from being over-provisioned increase, capacity management becomes important. Teams implement capacity-related metrics collection, and use those metrics to ensure they avoid capacity issues (as well as 2x over-provisioning).
4. "V2.0:  Capacity and Efficiency" Teams design for efficient use of capacity, and the software system adjusts automagically to increased demand.  Platforms like Kubernetes may be used to share capacity across many different workloads, if necessary.