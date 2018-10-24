I wrote this guide for a friend building out a DevOps pillar of a consulting company.  You may find it useful as well.

## Team Buildout Strategy:
   While I'd start with the Principal/Manager and 2-3 Senior DevOps, you should build out a pipeline of folks at all 3 levels, as DevOps is one of the harder S/W disciplines to hire and you will probably have more luck growing newer system engineers into DevOps.  Also, a lot of the build/deployment/automation work is fairly simple once you've got the templates built. Linkedin + Glassdoor + Hacker news + perhaps even StackOverflow are places where I've seen interesting opportunities.

Remember to look for open source contributions from the potential DevOps engineers; most engineers keep the code they write handy. Generalizing this concept should be a core strength of your company... I believe it's important to keep the (sanitized) general purpose scripts/templates from DevOps engagements in a central repository for reuse. 


## DevOps levels, with qualifications:

### Principal DevOps Engineer/Manager

Look for 10+ years experience as an Engineer (S/W Dev, Test, and Program Management roles), as well as consulting experience.
Required skills in:

  - multiple Cloud toolsets (AWS CLI + Google/Azure/?)
  - multiple CI/CD pipelines (Jenkins or gitlab or ?)
  - various scripting languages (BASH, Python, JS, perhaps PowerShell if you're going after MSFT customers).  
  - at least one high-level Object Oriented language (customers will be using Java, C++, C#)
  - automation (SaltStack, Puppet).
  - monitoring implementation (AWS CloudWatch, Prometheus, ?)
  - Container development (Docker, Docker Swarm, Kubernetes, AWS ECS)
  - API development, if you want them to create services around the automation.
  - Architecture skills to understand the customer needs and scope the engagement

Manager title adds:

  - Leadership skills to build/grow the team 
  - Management/presentation/change management/process skills; some of the principal DevOps folks want to sit in a dark room and hack on automation.  ;-)

#### Example Job Description:
Seeking a highly motivated, seasoned Principal DevOps Engineer to help build out the Company Cloud Platform applications. 
This Principal Engineer will be a crucial member of the Cloud Infrastructure Team as they design, deploy and operate a secure, scalable, reliable and fast platform for both our infrastructure and application services.
A successful candidate will have extensive experience building platform based infrastructure services leveraging automation and resilient design and support models to provide performance, scalability, availability and security. Technical vision, flawless execution and a commitment to delivery is critical to this role. The role will also require strong partnership with engineering teams, product owners security teams and vendors.
Company's Cloud Infrastructure team is a fun, innovate, collaborative and respectful place to work where we value every employees input. This is the place where you can make a large impact to many industries including architecture, engineering, construction, civil engineering, biotechnology, media & entertainment and beyond.
Job Title: Principal Software Engineer, Infrastructure and Tools

Responsibilities:

- Install, configure, and maintain cloud platformed applications.
- Share, configure and maintain cloud platformed applications
- Make infrastructure/engineering recommendations to optimize reliability, availability and scalability
- Work closely with the product team, product owner and technical program manager to support and deliver solutions.
- Collaborate with product teams to architect, develop and optimize cloud performance
- Maintain documentation and troubleshooting runbooks.
- Respond to and resolve access and performance issues.
- Adopt and evangelize best uses for NewRelic, EC2, CloudWatch and other monitoring systems
- Maintain change control and testing processes for all modifications and deployments.
- Conduct research and make recommendations on products, services, and standards.

Requirements:

- 8-10 years of experience in systems administration/development/engineering in large scale environments in support of global services.
- Experience working with and performance tuning cloud platformed applications.
- Strong understanding of security best practices to protect systems and customer data.
- Desire to containerize all possible services and to automate their delivery.
- Advanced knowledge of Cloud platforms.
- Continuous Integration/Delivery Know it. Love it. Live it..
- Deep understanding of web infrastructure operations and delivery.
- Experience with Configuration management tools (Chef)
- Experience in Paas
- Automated, software based infrastructure management. - Infrastructure as code
- Solid understanding of highly available, secure services and a proven ability to deliver them against a roadmap.
- Strong leadership to drive technical development through our cloud transformation.
- Strong verbal and written communication, to interface with engineers, product owners and technical project managers.

Plus:

- Experience with monitoring and log analytics tools (NewRelic, Grafana, Graphite, collectd, Splunk, Sensu, kafka)
- Knowledge and experience with Agile development methodologies.



### Senior DevOps Engineer
Look for 5 years as an engineer, with at least 3 of it on DevOps/builds, with demonstrated skills in:

- at least one cloud toolset (likely AWS)
- at least one CI/CD pipeline, end to end.
- multiple scripting languages (BASH, Python, JS)
- automation
- system monitoring (e.g., AWS Cloudwatch)
- container development (Docker)
- documentation (code comments + process documentation) 

#### Example Job Description ([link](https://www.linkedin.com/jobs/view/921603477)):
Seeking a Senior DevOps engineer with strong Amazon Web Services experience and expert knowledge of containerization, specifically Docker. You will work to support our custom Python and Go applications. You will be expected to deliver on integrated solutions that meet customer and business objectives as well as coordinate and drive software/automation projects. You will have technical ownership, ownership over the infrastructure and make recommendations to leadership on future implementations.


On a regular day, you would work towards building and maintaining high-performance, fault-tolerant, scalable distributed software systems and write code that is performant, maintainable, clear, and concise. You will guide other developers through design, review and implementation. You will be helping us maintain current knowledge on data privacy and information security topics and their applicable program requirements. You will design, build, implement and support CI/CD framework; develop and support processes to maintain uptime, SLAs and availability of critical platform components. You will drive automation and reliability at all levels.


You’ll help automate and streamline our operations and processes. Build and maintain tools for deployment, monitoring and operations and troubleshoot and resolve issues in our dev, test and production environments. You would work closely with the backend team to meet the objectives and build tools to meet any gap.


What we look for:

- Ability to use a wide variety of open source technologies and cloud services (experience with AWS is required)
- Experience with designing, implementing and operating fault-tolerant, highly-available distributed systems
- Expertise knowledge in containerization, specifically Docker and its ecosystem including Docker hub, Docker private registry and Docker-compose
- A working experience of code and script (Python, Go preferable)
- Experience with open-source tools including Consul, Vault, Terraform, and Nomad and CI/CD platforms
- Strong experience with large-scale data-tier building blocks, specifically MongoDB, Redis, RabbitMQ and Kafka
- Knowledge of best practices and IT operations in an always-up, always-available service
- Commitment to providing software engineering best practices (e.g. unit testing, code reviews, design documentation, and continuous integration)
 

Other preferred qualifications include:

- You will have a strong understanding of client server development in a mobile environment, working knowledge of RESTful API design, firm understanding of DevOps concepts as they relate to “The Three Ways” - quality, feedback loops, and continuous learning/improvement.
- It is a plus if you have worked on previous projects using Python and Golang to develop DevOps tooling, have a background in big data design and technologies (e.g Spark, Nifi, Redshift, Airflow, or similar).


### DevOps Engineer
Look for 2-4 years as an engineer, with at least 1 of it on DevOps/builds. Check for demonstrated skills:

- scripting languages
- automation
- system monitoring
- CI/CD
- cloud toolset/API usage

#### Example Job Description:

The DevOps Engineer will be part of a team that builds lots of tools and services to pull, make sense of, and serve the results of that data.   To run those services and process that data, we require lots of cloud infrastructure. We’re part operations, part development and part support.

Qualifications:

- BS in Computer Science / Engineering or related field
- 3+ years software development or operations background understanding concepts such as distributed systems, alerting, monitoring, logging, and incident management
- Understanding of one or more programming languages: Python, Java, Ruby, Go, C++, C#
- Understanding of one or more scripting languages: Python, Bash, PowerShell, JavaScript, Ruby
- Solid understanding of Linux core fundamentals, command-line operations, scripting, and service monitoring
- Solid understanding of version control systems, i.e. git
- Solid understanding of agile methodologies, working in small teams, Continuous Integration and Continuous Delivery
- Firm understanding of networking concepts and technologies
- Excellent oral and written communication skills

Desired:

- Experience with cloud infrastructure services a plus; specifically, in AWS
- 3+ years implementing, troubleshooting, and supporting Linux and/or Windows environments in a large-scale public-facing website capacity
- Deployed a production application in a containerized environment (e.g. Docker) while using container management and service registry tools
- Experience with Redis, ElasticSearch, MongoDB, NGINX, Spark, and any RDBMS (preferably PostgreSQL)

Responsibilities:

- Work directly with development teams to understand engineering requirements and help engineer scalable, reliable, performant, and resilient software  
- Design and build infrastructure to support organization’s services and infrastructure
- Create, use, and enhance tools to monitor our applications and services in the cloud, including system health indicators, trend identification, log analysis, and anomaly detection
- Automate repeatable and deterministic system and infrastructure build outs using Infrastructure-as-Code tools such as Chef, Ansible, and Terraform
- Build on our automated process pipelines for alerting and CI/CD
- Provide and improve incident management coverage, support, and reporting, including on call rotations
- Help further our DevOps culture of cross-collaboration
