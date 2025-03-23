# AWS 

What is AWS (Amazon Web Services)?
AWS (Amazon Web Services) is a cloud computing platform provided by Amazon, offering a wide range of cloud services like computing power, storage, databases, networking, AI/ML, security, and analytics. AWS allows businesses and developers to build, deploy, and scale applications efficiently without managing physical infrastructure.

 Key Features of AWS:
Pay-as-you-go pricing – No upfront cost, pay only for what you use.
 Highly scalable – Automatically adjusts to traffic demand.
Secure and compliant – Provides advanced security and compliance standards.
Global infrastructure – Data centers across multiple regions worldwide.
Flexible and reliable – Offers services for startups, enterprises, and governments.

 AWS Service Categories & Examples:
Category	Service Name	Purpose
Compute	EC2 (Elastic Compute Cloud)	Virtual servers in the cloud
	Lambda	Serverless computing (FaaS)
Storage	S3 (Simple Storage Service)	Scalable object storage
	EBS (Elastic Block Store)	Block storage for EC2
Databases	RDS (Relational Database Service)	Managed SQL databases
	DynamoDB	NoSQL database service
Networking	VPC (Virtual Private Cloud)	Private network for AWS resources
	Route 53	Domain Name System (DNS) service
Security	IAM (Identity and Access Management)	Access control for AWS services
	AWS Shield	DDoS protection
AI & ML	SageMaker	Machine learning model development
	Rekognition	Image and video analysis
DevOps & Monitoring	CloudWatch	Monitoring and logging
	CodePipeline	CI/CD automation
Analytics	Redshift	Data warehousing and analytics
	Athena	Query data in S3 using SQL

 AWS Deployment Models
Public Cloud – AWS owns and manages the cloud resources shared across multiple customers.
Private Cloud – AWS provides isolated cloud environments for enterprises.
Hybrid Cloud – A mix of AWS cloud and on-premise infrastructure.

 Popular Use Cases of AWS
Hosting Websites & Applications – Netflix, Airbnb, and LinkedIn run on AWS.
Big Data & Analytics – AWS Redshift, Athena for data processing.
Machine Learning & AI – AWS SageMaker for building AI models.
IoT (Internet of Things) – AWS IoT Core connects and manages IoT devices.
Disaster Recovery & Backup – AWS provides reliable and secure data backups.

Why Choose AWS?
 Most widely used cloud provider – Market leader with the largest customer base.
 Comprehensive services – Offers over 200+ cloud services for different needs.
 Global reach – Data centers in multiple regions for low-latency performance.
Strong security – Complies with major security and regulatory standards.




Cloud Computing Service Models: IaaS, PaaS, SaaS, DaaS, FaaS, and Serverless
Cloud computing is categorized into different service models, each offering various levels of control, flexibility, and ease of use. Below is a detailed explanation of IaaS, PaaS, SaaS, DaaS, FaaS, and Serverless Computing.

1. Infrastructure as a Service (IaaS)
 Definition:
IaaS provides virtualized computing resources (such as servers, storage, networking) over the internet, allowing businesses to manage their infrastructure without purchasing physical hardware.
 Examples:
•	Compute: AWS EC2, Google Compute Engine, Azure Virtual Machines
•	Storage: Amazon S3, Google Cloud Storage, Azure Blob Storage
•	Networking: AWS VPC, Azure Virtual Network
 Use Cases:
 Hosting websites, applications, or databases
 Disaster recovery and backup solutions
 Scalable and flexible infrastructure
 Benefits:
Full control over infrastructure
Scalable and cost-efficient
Pay-as-you-go pricing

2. Platform as a Service (PaaS)
Definition:
PaaS provides a complete development and deployment environment in the cloud, where developers can build, test, and manage applications without handling the underlying infrastructure.
 Examples:
•	Application Hosting: Google App Engine, AWS Elastic Beanstalk, Azure App Services
•	Database Services: AWS RDS, Google Cloud SQL, Azure SQL Database
•	Container Management: AWS Fargate, Google Kubernetes Engine (GKE), Azure Kubernetes Service
 Use Cases:
 Web & mobile app development
 Automated deployment & scaling
 CI/CD (Continuous Integration & Continuous Deployment)
 Benefits:
 Developers focus on coding, not infrastructure
 Automatic scaling and updates
 Faster development and deployment

3. Software as a Service (SaaS)
Definition:
SaaS provides ready-to-use software applications over the internet, eliminating the need for installation and maintenance on local devices.
 Examples:
•	Email & Collaboration: Gmail, Microsoft 365, Google Workspace
•	CRM & ERP: Salesforce, SAP, Oracle Cloud Applications
•	Cloud Storage: Google Drive, Dropbox, OneDrive
 Use Cases:
 Business applications (CRM, ERP, HR software)
 Cloud storage and file sharing
 Email & communication services
 Benefits:
 No need to install or maintain software
 Accessible from anywhere via the internet
 Automatic updates and security patches

4. Desktop as a Service (DaaS)
 Definition:
DaaS delivers virtual desktops to users over the cloud, allowing them to access a remote operating system without depending on a local machine.
 Examples:
•	Amazon WorkSpaces
•	Azure Virtual Desktop
•	Citrix Virtual Apps and Desktops
 Use Cases:
 Remote work and virtual desktop environments
 Secure desktop access from any device
 Reduces IT hardware and management costs
 Benefits:
 No need for powerful local hardware
 Secure, cloud-hosted desktop experience
 Centralized management and updates

5. Function as a Service (FaaS)
 Definition:
FaaS is a serverless computing model where developers run small code functions only when triggered, without managing infrastructure.
 Examples:
•	AWS Lambda
•	Google Cloud Functions
•	Azure Functions
 Use Cases:
 Processing events (e.g., file uploads, HTTP requests)
 Automating tasks & scheduled jobs
 Running microservices-based applications
 Benefits:
 No infrastructure management
 Cost-effective (pay-per-execution)
 Highly scalable and event-driven

6. Serverless Computing
Definition:
Serverless computing is a cloud execution model where cloud providers manage all infrastructure, scaling, and maintenance, allowing developers to focus only on writing code.
 Examples:
•	Compute: AWS Lambda, Google Cloud Functions
•	Storage: AWS S3, Google Cloud Storage
•	Databases: Firebase Firestore, AWS DynamoDB
 Use Cases:
 Real-time data processing
 Internet of Things (IoT) applications
 API backend development
 Benefits:
 No server management
 Automatic scaling
 Cost-efficient (pay-per-use)

Comparison Table: IaaS vs PaaS vs SaaS vs DaaS vs FaaS vs Serverless
Service Model	Definition	User Responsibility	Examples	Best For
IaaS	Cloud-based infrastructure (VMs, storage, networking)	User manages OS, applications	AWS EC2, Google Compute Engine	Hosting applications, disaster recovery
PaaS	Platform for developers to build and deploy applications	User manages code and data	AWS Elastic Beanstalk, Google App Engine	App development, CI/CD
SaaS	Fully managed software applications	No management needed	Gmail, Dropbox, Salesforce	Productivity tools, cloud storage
DaaS	Virtual desktops delivered over the cloud	User manages applications on virtual desktop	Amazon WorkSpaces, Azure Virtual Desktop	Remote work, virtual desktop access
FaaS	Event-driven execution of code functions	User writes function code	AWS Lambda, Azure Functions	Running microservices, event-based tasks
Serverless	Fully managed cloud services, including FaaS & storage	User writes code, provider handles infra	AWS Lambda, Firebase, AWS S3	API backends, IoT, data processing

Summary
 IaaS → Virtual machines & infrastructure
 PaaS → Development platform (deploy apps)
 SaaS → Ready-to-use software (Google Docs, Gmail)
 DaaS → Virtual desktops over the cloud
 FaaS → Serverless function execution (Lambda, Cloud Functions)
 Serverless → Fully managed cloud execution model (includes FaaS, databases, storage) 


Difference Between Hypervisor and Cloud Computing
Feature	Hypervisor	Cloud Computing
Definition	Software that enables virtualization by running multiple VMs on a single physical machine	Delivery of computing services (servers, storage, networking, databases) over the internet
Purpose	Creates and manages virtual machines	Provides scalable and on-demand computing resources
Types	Type 1 (Bare Metal), Type 2 (Hosted)	IaaS, PaaS, SaaS
Examples	VMware ESXi, Hyper-V, VirtualBox	AWS, Microsoft Azure, Google Cloud
Resource Management	Limited to the physical server	Uses multiple data centers across regions
Scalability	Limited to local hardware capacity	Highly scalable with unlimited resources
Usage	Used for virtualization in data centers, testing environments	Used for hosting websites, applications, AI, storage, and more

 Key Differences:
 Hypervisor → Manages VMs on a single physical machine (local virtualization)
 Cloud Computing → Provides computing resources over the internet (remote access)
 Conclusion:
•	If you need to run multiple virtual machines on a local server, use a Hypervisor.
•	If you need on-demand scalable resources (without managing physical infrastructure), use Cloud Computing. 

 



Regions, Availability Zones, and Edge Locations

AWS Regions
Definition: A Region is a geographical area that contains multiple Availability Zones (AZs)..

AWS has 36 Regions worldwide 
 Each Region operates independently to ensure high availability.
 Regions are selected based on proximity, compliance, and cost.
 Example: us-east-1 (N. Virginia), ap-south-1 (Mumbai).

AWS Availability Zones (AZs)
 Definition: Availability Zones are physically separated data centers within a Region, designed to ensure fault tolerance and high availability.
 Key Points for an Interview:
 AWS has 114  AZs globally (.
 Each Region has multiple AZs (usually 3 to 6).
 AZs have independent power, cooling, and networking to prevent failures.
 They are connected via low-latency, high-speed networks.
 Example: us-east-1a, us-east-1b, us-east-1c (Availability Zones within the us-east-1 Region).

AWS Edge Locations
 Definition: Edge Locations are global data centers that cache content closer to users to reduce latency and improve performance. They are mainly used for AWS CloudFront (CDN), Route 53 (DNS), and other edge services.
 Key Points for an Interview:
 AWS has 700 Edge Locations globally 
 These help in faster content delivery and lower latency.
They work with services like Amazon CloudFront (CDN).
 Example: An Edge Location in New York, London, or Tokyo improves content delivery speed for nearby users.


A Data Center is a physical facility that organizations use to house their critical applications, data, and IT infrastructure. It contains servers, storage systems, networking devices, and other computing resources.
Key Features of a Data Center
•	Infrastructure: Includes servers, storage devices, networking equipment, and power management systems.
•	Cooling and Power: Requires robust cooling systems and uninterrupted power supplies (UPS) to ensure continuous operations.
•	Security: Physical security measures like surveillance, biometric access, and fire suppression systems.
•	Network Connectivity: Provides high-speed network connections for efficient data transmission.
•	Redundancy and Backup: Often designed with redundancy for failover support and disaster recovery.
Types of Data Centers
1.	Enterprise Data Centers: Built and managed by organizations for private use.
2.	Colocation Data Centers: Third-party facilities where companies rent space and resources.
3.	Cloud Data Centers: Managed by cloud providers like AWS, Azure, and Google Cloud.
4.	Edge Data Centers: Smaller facilities located closer to users for low-latency applications.



Amazon VPC (Virtual Private Cloud) 
What is VPC?
Amazon VPC (Virtual Private Cloud) is a logically isolated network within AWS where you can launch AWS resources securely. It allows users to control IP addressing, subnets, route tables, security groups, and network ACLs.

 Key Features of VPC
 Complete Control Over Network – Define your IP ranges, subnets, and routing rules.
 Security & Isolation – Uses Security Groups and Network ACLs to control inbound/outbound traffic.
 Connectivity Options – Supports Internet Gateway, VPN, Direct Connect, and VPC Peering.
 Scalability – Can host multiple EC2 instances, databases, and load balancers.

Components of VPC (Important for Interviews)
Component	Definition
VPC	A logically isolated network within AWS.
Subnets	Smaller networks within a VPC. Can be Public (internet-facing) or Private (internal).
Internet Gateway (IGW)	Allows public internet access for resources in a VPC.
NAT Gateway (NGW)	Allows outbound internet access for private subnets.
Route Tables	Direct traffic between subnets, IGW, and VPNs.
Security Groups (SGs)	Acts as a virtual firewall for controlling inbound/outbound traffic at the instance level.
Network ACLs (NACLs)	Another firewall that controls traffic at the subnet level (stateless).
VPC Peering	Connects two VPCs to communicate privately.
AWS PrivateLink	Securely connects AWS services and VPCs without exposing traffic to the internet.
Transit Gateway	Connects multiple VPCs and on-premises networks.

 

Types of Subnets in VPC
Public Subnet – Connected to an Internet Gateway (IGW) → Used for web servers.
Private Subnet – No direct internet access → Used for databases and internal services.
NAT Gateway (NGW) – Allows private subnet instances to access the internet outbound only.

Connectivity Options in VPC
 Internet Gateway (IGW) – Public internet access.
 NAT Gateway (NGW) – Private subnet to internet (outbound only).
 VPN Connection – Secure connection to on-premises data centers.
 AWS Direct Connect – Dedicated network connection from on-premises to AWS.
 VPC Peering – Connects two VPCs (same or different regions).
 Transit Gateway – Centralized hub for connecting multiple VPCs and networks.  

Amazon EC2 (Elastic Compute Cloud) 
What is EC2?
Amazon EC2 (Elastic Compute Cloud) is a web service that provides resizable compute capacity (virtual servers) in the cloud. It allows users to deploy, manage, and scale virtual machines on demand.

Key Features of EC2 (Important for Interviews)
 Scalability – Can scale up/down based on demand.
 Flexibility – Choose from different instance types (CPU, memory, storage).
 Security – Secure access via Key Pairs, Security Groups, IAM Roles.
 Networking – Can be placed inside VPCs, Subnets, Elastic IPs.
 Cost-Effectiveness – Multiple pricing models (On-Demand, Reserved, Spot).
 Automation – Can be managed using Auto Scaling Groups and Elastic Load Balancers.

EC2 Components
Component	Definition
Instance Type	Determines the CPU, RAM, storage, and network capacity of an EC2 instance.
AMI (Amazon Machine Image)	A pre-configured template containing the OS, applications, and settings needed to launch an EC2 instance.
EBS (Elastic Block Store)	Persistent storage that remains even if the instance is stopped.
Elastic IP	A static public IP assigned to an EC2 instance.
Security Groups	Firewall rules that control inbound/outbound traffic to instances.
Key Pair	SSH keys for securely logging into instances.
Auto Scaling	Automatically increases/decreases instances based on demand.
Elastic Load Balancer (ELB)	Distributes incoming traffic across multiple EC2 instances for fault tolerance.
IAM Role	Grants EC2 instances permissions to interact with AWS services securely.

EC2 Pricing Models (Interview Question)
Pricing Model	Description	Use Case
On-Demand	Pay for compute capacity per second/minute.	Short-term, unpredictable workloads.
Reserved Instances (RI)	Commit for 1 to 3 years to get discounts up to 72%.	Steady-state, predictable workloads.
Spot Instances	Unused EC2 capacity at a discount of up to 90%.	Batch processing, big data, ML workloads.
Dedicated Hosts	Physical servers dedicated to one customer.	Regulatory and licensing requirements.
Savings Plans	Flexible pricing based on usage commitment.	Cost-effective alternative to Reserved Instances.

 EC2 Instance Lifecycle
Launch – Choose AMI, Instance Type, Storage, Security Group, Key Pair.
Running – The instance is active and in use.
Stopped – The instance is off but EBS volume persists.
Terminated – The instance is permanently deleted.

 EC2 Storage Options
 Amazon EBS (Elastic Block Store) → Persistent block storage (like a hard disk).
 Instance Store → Temporary storage (deleted on instance stop/terminate).
 Amazon S3 → Object storage for backups.
 EFS (Elastic File System) → Shared file storage for multiple instances.

 Networking in EC2
 VPC (Virtual Private Cloud) – Each EC2 runs inside a VPC.
 Subnet – Defines which instances are publicly or privately accessible.
 Elastic IP – Assigns a static public IP to instances.
 Security Groups – Acts as a firewall to control network traffic.
 Load Balancer – Distributes traffic across multiple EC2s.
   
Amazon AMI (Amazon Machine Image) 
What is an AMI?
An Amazon Machine Image (AMI) is a pre-configured virtual machine template that contains the operating system, application software, libraries, and configurations required to launch an EC2 instance.

Key Features of AMI
 Customizable – You can create custom AMIs with specific configurations.
 Prebuilt & Marketplace AMIs – AWS provides prebuilt AMIs, and third-party vendors offer AMIs via AWS Marketplace.
 Scalability – AMIs allow you to launch multiple EC2 instances with the same configuration.
 Encryption – AMIs can be encrypted for security and compliance.
 Region-Specific – AMIs are tied to a specific AWS region but can be copied across regions.

 AMI Components (Interview-Relevant Details)
Component	Description
Root Volume	The main boot volume, usually an EBS volume or an Instance Store.
Launch Permissions	Defines which AWS accounts can use the AMI to launch EC2 instances.
Block Device Mapping	Specifies the additional storage (EBS volumes) attached when launching an EC2 instance.
Virtualization Type	Either HVM (Hardware Virtual Machine) or PV (Paravirtualization). HVM is recommended for most workloads.

 



Types of AMIs
Type	Description	Example Use Case
Public AMI	Available to all AWS users, typically provided by AWS or third-party vendors.	Quickly launching EC2 instances without custom configuration.
Private AMI	Restricted to a specific AWS account and not publicly shared.	Secure, custom-built AMIs for enterprise workloads.
AWS Marketplace AMI	Paid or free AMIs provided by third-party vendors for specific use cases.	Deploying commercial software like antivirus, databases, or monitoring tools.
Custom AMI	AMIs created from an existing EC2 instance with specific configurations.	Scaling applications with pre-configured software stacks.

 How to Create an AMI?
Launch an EC2 instance and configure it (install software, update settings).
Create an AMI from the running instance via EC2 Management Console or AWS CLI.
Choose Storage Options (EBS-backed or Instance Store-backed).
Set Permissions (Public or Private).
Use AMI to launch multiple identical EC2 instances.

Commands to Manage AMIs (AWS CLI)
Command	Description
aws ec2 describe-images	Lists available AMIs.
aws ec2 create-image --instance-id i-12345678 --name "MyCustomAMI"	Creates an AMI from an existing EC2 instance.
aws ec2 deregister-image --image-id ami-12345678	Deletes an AMI.
aws ec2 copy-image --source-image-id ami-12345678 --source-region us-east-1 --destination-region us-west-1 --name "CopiedAMI"	Copies an AMI to another region.




