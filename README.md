# Amazon Web Services Certified Cloud Practitioner

## MODULE 1

#### INTRODUCTION TO THE AWS CLOUD
	- On-demand delivery
	- No large upfront  investments
	- Provisioning of computing resources as needed
	- Pay only for what you use

#### CLOUD COMPUTING COMPONENTS
	- Servers
	- Storage
	- Databases
	- Applications

#### CLOUD COMPUTING DEPLOYMENT MODELS
	- Cloud
	- Hybrid
	- On-premises

#### BENEFITS OF AWS
	- Agility
	- Elasticity
	- Cost Savings
	- Rapid deployment

	AGILITY
		- Faster innovation
		- No wait for additional resources
		- Ability to experiment and innovate

	ELASTICITY
		- Adapt to meet varying workloads
		- Distribute workloads across multiple resources
		- Deploy fault tolerant applications and resources

	COST SAVINGS
		- Trade capital expense(capEx) for variable expense
		- Reduce facility maintenance costs
		- Pay as you go

	RAPID DEPLOYMENT
		- Highly scalabre platform around the world
		- Quick release for new features in applications
		- Automated deployment

#### GLOBAL INFRASTRUCTURE
	- 27 regions

#### REGIONS
	- A region is a separate geographical location with multiple locations that are isolated from each other.
	- Supports AWS's global footprint
	- Serves customers across the world
	- Faast-paced expansion with long-term commitment to sustainability
 
#### AVAILABILITY ZONES
	- Fully isolated portions of the AWS global infrastructure
	- All Availabity Zones are interconnected with high-bandwidth, low-latency networking over fully redundant, dedicated fiber
	- Help customers to build highly available applications

#### POINTS OF PRESENCE
	- Consist of edge locations and regional edge cache servers
	- Deliver content to customers through a worldwide network of points of presence locations
	- Low latency and high transfer speed

#### WHO USES AWS?
	- Enterprises
	- Startups
	- Public Sector

#### KEY TAKEAWAYS
	- Benefits of AWS
		- Agility
		- Elasticity
		- Cost savings
		- Rapid deployment

------------------------------------------------------------------------------------------------------------------------------------------

## MODULE 2

#### OVERVIEW OF AWS SERVICES

- AWS service domains:
	- Compute
	- Storage
	- Database
	- Networking and Content Delivery

- How to access AWS services

#### AWS SERVICE DOMAINS

	- AWS COMPUTE SERVICES
		- Amazon Elastic Compute Cloud(Amazon EC2)
		- Amazon EC2 Auto Scaling
		- Elastic Load Balancing
		- Amazon Elastic Container Service(Amazon ECS)
		- Amazon Lambda

	- AMAZON EC2
		- Secure, sizable compute capacity
		- Enables you to:
			- Boot server instances in minutes
			- Scale capacity up and down as computing requirements change
		- Multiple pricing options to minimize cost
		- On-demand instances (only when necessary)
		- Spot instances (pay by hour)
		- Reserved instances (agreement with AWS)

	- AMAZON EC2 AUTO SCALING 
		- Automatically add or remove EC2 instances according to conditions you define (horizontal scalability)
		- Maintain application availability
		- Benefit from dynamic and predictive scaling
		- Add new instances only when necessary
		- Remove unneeded instances when traffic is low
		- Pay only for what you use

	- ELASTIC LOAD BALANCING
		- Automatically distributes traffic across multiple resources
		- Acts as a single point of contact for your Auto Scaling group
		- Distributes traffic across multiple Availability Zones

		- APPLICATION LOAD BALANCERS
			- Used for load balancing HTTP and HTTPS traffic
			- Operate at the individual request level(Layer 7)
			- Route traffic based on the content of a request

		- NETWORK LOAD BALANCERS
			- Used for load balancing TCP, UDP, and TLS traffic
			- Optimized to handle sudden and volatile traffic patterns
			- Operate at the connection level(Layer 4)

		- CLASSIC LOAD BALANCERS
			- Used for load balancing across multiple EC2 instances
			- Operate at both the request level and connection level
			- Used with applications that were built within the EC2-Classic network

	- AMAZON ELASTIC CONTAINER SERVICE
		- Amazon EC2 is a highly scalable, high-performance container orchestration service
			- Run and scale containerized applications on AWS
			- Use simple API calls to lauch and stop Docker-enabled applications

	- AMAZON LAMBDA (serverless)
		- Run code without provisioning or managing servers
		- Pay only for compute time while code is running
		- Use other AWS services to automatically trigger code
		- AWS Lambda functions cannot run continuously for more than 15 minutes
		- Trigger em sua tradução literal é acionar. Um trigger no lambda seria alguma ação que foi feita que acionou a nossa função lambda

		- Steps to use Lambda:
			- Upload code to Lambda
			- Set code to trigger from an event source
			- Code runs only when triggered
			- Pay only for the compute time you use

	- AWS STORAGE SERVICES
		- Amazon Simple Storage Service (Amazon S3)
		- Amazon Elastic Block Store (Amazon EBS)
		- Amazon Elastic File System (Amazon EFS)

		- AMAZON SIMPLES STORAGE SERVICE (S3)
			- You can store and access any type of data over the Internet
			- It is 99.999999999% durable
			- It included a wide range of cost-effective storage classes
			- Store files in buckets
			- Support a variety of use cases
			- Keep track of multiple variants of an object through versioning
			- Prevent accidental object deletions

		- AMAZON ELASTIC BLOCK STORE (EBS)
			- High performance block storage
			- Replicated within an Availability Zone for 99.999% availability
			- Scale up or down in minutes
			- Four volume types to optimize price and performance
			- Volume Types:
				- General Purpose SSD
				- Provisioned IOPS SSD
				- Throughput Optimized HDD
				- Cold HDD

		- AMAZON ELASTIC FILE SYSTEM (EFS)
			- Simple, scalable, fully managed file system
			- Scales on demand to petabytes without disrupting applications
			- Stores data within and across multiple Availability Zones

	- AWS DATABASES SERVICES
		- Amazon Relational Database Service (Amazon RDS)
		- Amazon DynamoDB
		- AWS Database Migration Service (AWS DMS)

		- AMAZON RELATION DATABASE SERVICE (RDS)
			- Amazon RDS is a fully managed relational database service
			- Automates time-consuming administration tasks
			- Secure and compatible
			- Easy to administer

			- AMAZON RDS: ENGINE TYPES
				- Engine types are optimized for memory, performance, or I/O:
					- Amazon Aurora
					- PostgreSQL
					- MySQL
					- MariaDB
					- Oracle Database
					- SQL Server

			- AMAZON RDS: PROVISIONING
				- Multi-AZ deployment for built-in automated fail-over
				- High availability and reliability
				- Use Read Replicas for read-heavy database workloads

		- AMAZON DYNAMODB
			- Fast and flexible NoSQL key-value and document database
			- No servers to manage
			- Single-digit millisecond performance at any scale

			- AMAZON DYNAMODB: USE CASES
				- Serverless web applications
				- Mobile backends
				- Gaming
				- Internet of Things (IoT)

		- AWS DATABASE MIGRATION SERVICE (AWS DMS)
			- Migrate databases to AWS quickly and securely
			- Migrate data to and from most widely-used databases
			- Maintain full operation of source databases during the migration

	- AWS NETWORKING AND CONTENT DELIVERY
		- Amazon Virtual Private Cloud (VPC)
		- Amazon Route 53
		- AWS Direct Connect
		- Amazon CloudFront

		- AMAZON VIRTUAL PRIVATE CLOUD (VPC)
			- Launch AWS resources in a virtual network that you define
			- Have complete control over your virtual networking environment
			- Create subnets and leverage multiple layers of security

		- AMAZON ROUTE 53
			- Amazon Route 53 is a highly available and scalabre DNS web service
			- Translates domain names to numeric IP addresses
			- Connects user requests to infrastructures within and outside of AWS
			- Routers traffic to healthy endpoints
			- Transfer DNS records for existing domain names
			- Register new domain names
			- Ensure a high level of availability with multiple name servers

		- AWS DIRECT CONNECT
			- AWS Direct Connect is a dedicated network connection from your premises to AWS
			- Reduce network costs and increase bandwidth throughput
			- Partition the connection into multiple virtual interfaces

		- AMAZON CLOUDFRONT
			- Quickly delivers content to customers globally
			- Seamlessly integrates with AWS services
			- Incurs no charges for data transferred between AWS origins and CloudFront
			- No minimum commitments
			- Pay only for what you use
			- Wide variety of use cases:
				- Static asset caching
				- Video streaming
				- Software distribution

#### HOW TO ACCESS AWS SERVICES
	- AWS Management Console
		- A simple, intuitive user interface
		- Access to simple wizards and automated workflows
		- AWS Console mobile application

	- Command Line Interface
		- Unified tool to manage your AWS services
		- Available on Windows, MacOS, and Linux
		- Automate services through scripts

	- AWS Tools and SDKs
		- Tools for developing and managing applications on AWS
		- Easily develop applications on AWS in the programming language of your choice

#### KEY TAKEAWAYS
	- Broad selection of services and deep functionality
	- Pay only for the services you use
	- Trusted by millions of customers worldwide

------------------------------------------------------------------------------------------------------------------------------------------

## MODULE 3

#### SECURITY AND COMPLIANCE OVERVIEW
	- Overview of security
	- Shared responsability model
	- AWS security services
	- AWS compliance

	- WHAT IS SECURITY?
		- Visibility
		- Controllability
		- Auditability
		- Agility

	- CIA TRIAD
		- Confidentiality
		- Integrity
		- Availability

		- CONFIDENTIALITY
			- Controlling access to data in order to prevent unauthorized disclosure
			- AWS examples:
				- S3 bucket permissions
				- Database permissions
				- Restricting access to EC2 instances

		- INTEGRITY
			- Ensuring that data has not been tampered with and, therefore, can be trusted
			- AWS examples:
				- Server-Side Encryption (SSE) Keys
				- AWS Certificate Manager

		- AVAILABILITY
			- Networks, systems, and applications are up and running when needed
			- AWS Examples:
				- Availability Zones
				- Backups

	- WHAT AWS OFFERS FOR SECURITY
		- Better monitoring and efficiency
		- More automated processes
		- Comprehensive security and compliance controls

	- SHARED RESPONSABILITY MODEL
		- AWS
			- Foundation services
				- Compute
				- Storage
				- Database
				- Network
			- AWS global infrastructure
				- Regions
				- Availability Zones
				- Edge Locations
		CUSTOMER
			- Customer data
			- Platform, applications, identity & access management
			- Operating system, network & firewall configuration
			- Client-side data encryption & Data integrity authentication
			- Server-side encryption (File system and/or data)
			- Network traffic protection (Ecryption/integrity/identity)

	- CUSTOMERS: SECURITY 'IN' THE CLOUD
		- Instance operating system
		- Application
		- Security groups
		- Operating system/host-based firewalls
		- Network configuration
		- Account management

	- AWS: SECURITY 'OF' THE CLOUD
		- Physical security of data centers
		- Hardware and software infrastructure
		- Network infrastructure
		- Virtualization infrastructure

	- AWS SECURITY SERVICES
		- Identity and access management
		- Detective controls
		- Infrastructure protection
		- Data protection
		- Compliance

	- IDENTITY AND ACCESS MANAGEMENT
		- Amazon Cognito
		- AWS Directory Service
		- AWS Identity and Access Management (IAM)
		- AWS Secrets Manager
		- AWS Single Sign-On (SSO)

	- DETECTIVE CONTROLS
		- AWS Security Hub
		- Amazon GuardDuty
		- Amazon Inspector
		- Amazon Macie

	- INFRASTRUCTURE PROTECTION
		- AWS Shield
		- AWS Web Application Firewall (WAF)
		- AWS Firewall Manager

	- DATA PROTECTION
		- AWS Key Management Service (KMS)
		- AWS CloudHSM
		- AWS Certificate Manager

	- COMPLIANCE
		- AWS Artifact

	- AWS IDENTITY AND ACCESS MANAGEMENT (IAM)
		- Control access to AWS resources and services
		- Create and manage users and groups
		- Enable multi-factor authentication (MFA) for event greater security
		- IAM USERS
			- A user is an entity to represent a person or application that interacts with AWS
			- New users have no permissions by default
		- IAM GROUPS
			- A group is a collection of IAM users
			- You can easily manage permissions for multiple users at once
			- A user can be in multiple groups
		- IAM POLICIES
			- A policy is a documents that defines permissions within AWS
			- A policy is used for allowing and denying specific actions
			- Best practice: Follow the principle of least privilege
	
	- MULTI-FACTOR AUTHENTICATION (MFA)
		- Provides an extra layer of protection for your AWS account
		- Is available at no extra cost
		- Included options for MFA hardware and virtual devices

	- AWS KEY MANAGEMENT SERVICE (AWS KMS)
		- Create and manage crypptographic keys
		- Choose the level of access control that you need
		- Integrate with AWS CloudTrail

		- AWS KMS: ADDITIONAL BENEFITS
			- Centralized key management
			- Encrypts data in your applications
			- Is low cost

	- AWS ARTIFACT
		- Self-service portal for on-demand access to AWS compliance reports
		- Review, accept, and manage agreements with AWS
		- Access compliance reports from third-party auditors

#### KEY TAKEAWAYS
	- Comprehensive and flexible security services
	- Security is a shared responsability
	- On-demand access to compliance reports
------------------------------------------------------------------------------------------------------------------------------------------

## MODULE 4

#### OVERVIEW OF AWS MANAGEMENT AND GOVERNANCE
	
	- Managing and governing with AWS:
		- Enable
		- Provision
		- Operate

	- AWS MANAGEMENT AND GOVERNANCE
		- Question: Do you want faster innovation or control over costs, compliance and security?
		- With AWS, you can have both:
			- Enable, provision and operate your environment for business agility
			- Secure your envinroments and improve operational efficiency

	- ENABLE STAGE
		- Resources grow
		- Create the environments
		- Enable governance controls
		- Manage accounts and policies
		- Improve architecture

		- AWS ORGANIZATIONS
			- Centrally govern your AWS environment as you grow and scale
			- Control access, compliance and security
			- Consolidate billing across all of your company's AWS accounts

		- AWS CONTROL TOWER
			- Automate the setup of a multi-account AWS environment
			- Quickly and easily provision new AWS accounts
			- Maintain continuous oversight of your multi-account AWS environment

	- PROVISION STAGE
		- Users need resources
		- On-demand provisioning
		- Map pre-approved services to users
		- Improve efficiency and compliance

		- AWS CLOUDFORMATION
			- Model and provision your cloud environment
			- Provision resources based on the specified configurations
			- Automatically roll back changes if errors are detected

		- AWS MARKETPLACE
			- A place to find software and services that run on AWS
			- Includes thousands of listings
			- Enables you to explore solutions by industry and use case

	- OPERATE STAGE
		- Monitor
		- Audit
		- Act
		- Analyze

		- AMAZON CLOUDWATCH
			- Monitor your applications
			- Respond to system-wide performance changes
			- Benefit from real-time monitoring
			- Optimize resource utilization
			-  Access log files for different services from a single location
			- Perform queries on log data to more efficiently resolve issues
			- Retain log files indefinitely

		- AWS SIMPLE NOTIFICATION SERVICE (AMAZON SNS)
			- Decouple microservices, distributed systems and serverless applications
			- Automatically scale your workload
			- Keep messaged private and secure

		- AWS TRUSTED ADVISOR
			- Real-time guidance for your AWS environment
			- Helpful at all stages of deployment
			- Provides best practices for five categories

####  KEY TAKEWAYS
	- MANAGING AND GOVERNING WITH AWS INCLUDES THREE STAGED:
		- ENABLE
		- PROVISION
		- OPERATE
	- OPTIMITZE ENVIRONMENTS FOR BUSINESS AGILITY AND GOVERNANCE CONTROL
