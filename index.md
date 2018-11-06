# Brion Stone

Objectives:
- Principal-level technical positions
- Complex distributed cloud/dedicated services
- Creating systems to optimize cloud operations

Expertise:
DevOps, Capacity Planning & Performance, Cloud Infrastructure Design & Architecture, Project/Program Management, Disaster Recovery, Analysis & Forecasting, Agile Development, Billing
 
Blog Entries:

- [Building a DevOps Team](./blog/building_devops.md)
- [Measuring cost](./blog/dubweb.md)
- [Capacity Phases](./blog/cap_phases.md) 
- [Managing Software Capacity](./blog/capacity.md) 

## Projects
Current projects:

- EKS Vault IAM credential provider: (python/bash script) run Hashicorp Vault-Operator, Vault, etcd, to provide dynamic AWS IAM credentials to Kubernetes pods based on their Service Account.
- [Google G-Scout fork:  Scripts (python) running periodically to track security regressions in Google cloud, adding slack and email integration](https://github.com/zulily/G-Scout).
- [AWS TrustRunner:  AWS Lambda function (python) running periodically to track regressions in AWS Trusted Advisor checks](https://github.com/zulily/aws_trustrunner).
- [AWS CowCatcher: AWS Lambda function (python) finding instances and reporting/stopping/deleting them based on given criteria](https://github.com/zulily/cow_catcher).
- [AWS Monitor: AWS Lambda function (python)  creates/refreshes instance-based Cloudwatch monitors and dashboards](https://github.com/zulily/aws_monitor).
- [Dubweb: python/flask/javascript/mysql application to budget/track cloud spend](https://github.com/zulily/dubweb).
- Lemur/cfssl integration: (golang) - self-service certificate management.
- Klar/Clair/Docker/Gitlab integration: (gitlab script) build-time container scanning. 

## Employment

### Zulily
(2013 - Current)
Optimize DevOps resources by migrating business applications to a Kubernetes cluster (Docker container hosting using the Google Compute Engine), managing the project while creating:

-  Custom farm logging using ELK (elasticsearch/logstash/kibana on CoreOS).
-	Backup/restore pods which backup/restore encrypted Mysql and Mongo dumps to cloud storage (Docker, Bash shell)
-	Namespace-based scaling and costing tools (Python, Kubernetes API).

Understand and reduce costs for datacenter and cloud through creation of an open source cost / usage analysis application for cloud, datacenter and SAAS footprint including:

- 	Automated Extract/Transform/Load tool to import cloud usage metrics (Python/MySQL).
-  Web application for creation/tracking/reporting datacenter budgets/actuals (Flask/Python/AngularJS/Bootstrap).

Streamline service capacity by analyzing historical traffic, creating capacity models, and developing automated tools including:

-  Alerts when actual traffic diverges from predicted traffic (Nagios).
-  Clickstream analysis of regressions in Mongo, Redis, and MySQL (Google BigQuery).

Increase resilience by leading business continuity and disaster recovery efforts including:

- 	System outage tracking and availability reporting (Python, JIRA, Excel).
-	Monitoring systems planning and provisioning (SaltStack, Python, Zabbix).
- 	Automated backup tools with client-side encryption and Google Cloud storage (PHP).

### Microsoft
Enterprise Search Group, SharePoint Search (2007-2013)
(Individual Contributor role)

- Co-invented multiple technology innovations resulting in 2 new patents for Microsoft and 1 pending including patent in search health monitoring.
- Designed and led implementation of on-premises and Office365 cloud-base search functions (SharePoint) handling performance monitoring and development of:

	- Topology management, object model, PowerShell, faceted search, and monitoring features.
	- Performance, reliability, capacity planning, and security (threat modeling).
	- Led development of features for Office365 V1 launch including: 
	- Disaster recovery, high availability, and customer site restoration

Windows Live Member Experience Group, Live Favorites (2004-2007) (Lead role)

- Incubated idea, developed architecture, recruited and led small team in implementation of Windows Live Favorites, allowing users to access, share, and synchronize IE bookmarks across all major MSN applications.

MSN Core Services, Special Forces Team (2001-2004)
(Lead role)

- Drove development of new features and critical services for MSN including installation, authorization, and signup (MSN7.x, 8.x & 9).
- Facilitated partner integration with Charter, Dell, Verizon, and Major League Baseball for releases.

Internet Explorer Sustained Engineering, IE for Unix (2000-2001) (Lead role)

- Met corporate customer needs by leading IE for Unix 5.0 SP1 project and QFE releases (4) while managing remote development and testing groups in Israel and Redmond.
- Improved functionality by writing and managing specifications throughout software development lifecycle. 
- Integrated Windows IE fixes into Unix IE source code (C++).
