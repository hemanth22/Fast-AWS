# Fast-AWS
This repo covers AWS Hands-on Labs for different AWS services.

## Why was this repo created?
- **Shows AWS details in short with simple **
- **Shows AWS Hands-on LABs, and clean demos **

# Quick Look (How-To): AWS Hands-on Labs
These hands-on labs focus on how to create and use AWS components:
- [HANDS-ON-01: Provisioning EC2s (Windows 2019 Server, Ubuntu 20.04) on VPC (Subnet), Creating Key-Pair, Connecting Ubuntu using SSH, and Connecting Windows Using RDP](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE01-EC2-VPC-Ubuntu-Win-SSH-RDP.md)
- [HANDS-ON-02: Provisioning Lambda Function, API Gateway and Reaching HTML Page in Python Code From Browser](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE02-Lambda-API-Gateway-Python.md)
- [HANDS-ON-03: EBS (Elastic Block Storage: HDD, SDD) and EFS (Elastic File System: NFS) Configuration with EC2s (Ubuntu and Windows Instances)](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE03-EC2-EBS-EFS.md)
- [HANDS-ON-04: Provisioning ECR (Elastic Container Repository), Pushing Image to ECR, Provisioning ECS (Elastic Container Service), VPC (Virtual Private Cloud), ELB (Elastic Load Balancer), ECS Tasks and Service on Fargate Cluster](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE04-ECR-ECS-ELB-VPC-ECS-Service.md)
- [HANDS-ON-05: Provisioning ECR, Lambda Function and API Gateway to run Flask App Container on Lambda](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE05-Lambda-Container-ApiGateway-FlaskApp.md)
- [HANDS-ON-06: Provisioning EKS (Elastic Kubernetes Service) with Managed Nodes using Blueprint and Modules](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE06-EKS-ManagedNodes-Blueprint.md)
- [HANDS-ON-07: CI/CD on AWS => Provisioning CodeCommit and CodePipeline, Triggering CodeBuild and CodeDeploy, Running on Lambda Container](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE07-CodeCommit-Pipeline-Build-Deploy-Lambda.md)
- [HANDS-ON-08: Provisioning S3 and CloudFront to serve Static Web Site](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE08-S3-CloudFront-Static-WebSite.md)
- [HANDS-ON-09: Running Gitlab Server using Docker on Local Machine and Making Connection to Provisioned Gitlab Runner on EC2 in Home Internet without Using VPN](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE09-GitlabServer-on-Premise-GitlabRunner-on-EC2.md)
- [HANDS-ON-10: Implementing MLOps Pipeline using GitHub, AWS CodePipeline, AWS CodeBuild, AWS CodeDeploy, and AWS Sagemaker (Endpoint)](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE10-MLOps-SageMaker-GitHub-Codepipeline-CodeBuild-CodeDeploy.md)

# Table of Contents
- [Motivation](#motivation)
- [Common AWS Services In-Short](#servicesshort)
  - [1. Compute Services](#compute)
  - [2. Container Services](#container)
  - [3. Storage Services](#storage)
  - [4. Database Services](#database)
  - [5. Data Analytics Services](#dataanalytics)
  - [6. Integration Services ](#integration)
  - [7. Cloud Financial Management Services](#cloudfinancial)
  - [8. Management & Governance Services](#managementgovernance)
  - [9. Security, Identity, & Compliance Services](#securityidentity)
  - [10. Networking Services](#networking)
  - [11. Migration Services](#migration)
  - [12. Internet of Things Services](#internetofthings)
  - [13. Artificial Intelligence Services](#artificialintelligence)
- [AWS Hands-on Labs](#samples)
  - [HANDS-ON-01: EC2s (Windows 2019 Server, Ubuntu 20.04), VPC, Key-Pairs for SSH, RDP connections](#ec2_vpc_key_pair_ssh_rdp)
  - [HANDS-ON-02: Provisioning Lambda Function, API Gateway and Reaching HTML Page in Python Code From Browsers](#lambda_apigateway_python)
  - [HANDS-ON-03: EBS (Elastic Block Storage: HDD, SDD) and EFS (Elastic File System: NFS) Configuration with EC2s (Ubuntu and Windows Instances)](#ebs_efs_ec2)
  - [HANDS-ON-04: Provisioning ECR (Elastic Container Repository), Pushing Image to ECR, Provisioning ECS (Elastic Container Service), VPC (Virtual Private Cloud), ELB (Elastic Load Balancer), ECS Tasks and Service on Fargate Cluster](#ecr_ecs_elb_vpc_ecs_service_fargate)
  - [HANDS-ON-05: Provisioning ECR, Lambda Function and API Gateway to run Flask App Container on Lambda](#ecr_lambda_apigateway_container)
  - [HANDS-ON-06: Provisioning EKS (Elastic Kubernetes Service) with Managed Nodes using Blueprint and Modules](#eks_managednodes_blueprint)
  - [HANDS-ON-07: CI/CD on AWS => Provisioning CodeCommit and CodePipeline, Triggering CodeBuild and CodeDeploy, Running on Lambda Container](#ci_cd)
  - [HANDS-ON-08: Provisioning S3 and CloudFront to serve Static Web Site](#s3_cloudfront)
  - [HANDS-ON-09: Running Gitlab Server using Docker on Local Machine and Making Connection to Provisioned Gitlab Runner on EC2 in Home Internet without Using VPN](#gitlabrunner)
  - [HANDS-ON-10: Implementing MLOps Pipeline using GitHub, AWS CodePipeline, AWS CodeBuild, AWS CodeDeploy, and AWS Sagemaker (Endpoint)](#sagemaker)
- [References](#references)

## Motivation <a name="motivation"></a>
Why should we use / learn cloud?
- cloud

Why should we use / learn AWS?
- aws

## AWS Services In-Short <a name="servicesshort"></a>
There are more than 200 AWS services. Popular services are listed in short.

### 1. Compute Services <a name="compute"></a>
#### Amazon EC2 
- Virtual servers in the cloud
- Document: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
- ![image](https://github.com/user-attachments/assets/fdd66a3a-f740-43ed-b8f9-ac34a4cf743e)

#### Amazon EC2 Auto Scaling 
- Scale compute capacity to meet demand
- Document: https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html
- ![image](https://github.com/user-attachments/assets/3dc3ba14-cf8c-43a7-805d-c31f42a46c4b)

#### Amazon Lightsail 
- Launch and manage virtual private servers
- Document: https://docs.aws.amazon.com/lightsail/latest/userguide/what-is-amazon-lightsail.html
  
#### AWS App Runner
- Build and run containerized web apps at scale
- Document: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html

#### AWS Batch
- Run batch jobs at any scale
- Document:
  
#### AWS Elastic Beanstalk
- Run and manage web apps
- Document:

#### AWS Amplify
- Build, deploy, and host scalable web and mobile apps
- Document:

#### AWS Lambda
- Run code without thinking about servers
- Document:
  
#### AWS Outposts
- Run AWS infrastructure on-premises
- Document:
  
#### AWS Parallel Computing Service
- Easily run HPC workloads at virtually any scale
- Document:
  
#### AWS Serverless Application Repository
- Discover, deploy, and publish serverless applications
- Document:
  
#### AWS Snowball
- Accelerate moving offline data or remote storage to the cloud
- Document:
  
#### AWS Wavelength
- Deliver ultra-low latency applications for 5G devices
- Document:
  
### 2. Container Services  <a name="container"></a>
#### Amazon Elastic Container Registry
- Easily store, manage, and deploy container images
- Document:
  
#### Amazon Elastic Container Service (ECS)
- Highly secure, reliable, and scalable way to run containers
- Document:
  
#### Amazon ECS Anywhere
- Run containers on customer-managed infrastructure
- Document:
  
#### Amazon Elastic Kubernetes Service (EKS)
- The most trusted way to run Kubernetes
- Document:
  
#### Amazon EKS Anywhere
- Kubernetes on your infrastructure
- Document:
  
#### Amazon EKS Distro
- Run consistent Kubernetes clusters
- Document:
  
#### AWS App2Container
- Containerize and migrate existing applications
- Document:
  
#### AWS App Runner 
- Build and run containerized web apps at scale
- Document:
  
#### AWS Copilot
- Easily deploy and operate containerized applications
- Document:
  
#### AWS Fargate
- Serverless compute for containers
- Document:
  
### 3. Storage Services <a name="storage"></a>
#### Amazon Simple Storage Service (S3)
- Scalable storage in the cloud
- Document: 

#### Amazon S3 Glacier storage classes
- Low-cost archive storage in the cloud
- Document:

#### Amazon Elastic Block Store (EBS)
- EC2 block storage volumes
- Document:

#### Amazon Elastic File System (EFS)
- Fully managed file system for EC2
- Document:

#### Amazon FSx for Lustre
- High-performance file system integrated with S3
- Document:

#### Amazon FSx for NetApp ONTAP
- Fully managed storage built on NetApp’s popular ONTAP file system
- Document:

#### Amazon FSx for OpenZFS
- Fully managed storage built on the popular OpenZFS file system
- Document:

#### Amazon FSx for Windows File Server
- Fully managed Windows native file system
- Document:

#### Amazon File Cache
- High-speed cache for datasets stored anywhere
- Document:

#### AWS Backup
- Centralized backup across AWS services
- Document:

#### AWS Elastic Disaster Recovery (DRS)
- Scalable, cost-effective application recovery
- Document:

#### AWS Snowball
- Accelerate moving offline data or remote storage to the cloud
- Document:

#### AWS Storage Gateway
- Hybrid storage integration
- Document:

### 4. Database Services <a name="database"></a>
#### Amazon Aurora
- High performance managed relational database with full MySQL and PostgreSQL compatibility
- Document:

#### Amazon Aurora DSQL
- Fastest serverless distributed SQL database with active-active high availability
- Document:

#### Amazon Aurora Serverless V2
- Instantly scale to >100,000 transactions per second
- Document:

#### Amazon DocumentDB (with MongoDB compatibility)
- Fully managed document database
- Document:

#### Amazon DynamoDB
- Managed NoSQL database
- Document:

#### Amazon ElastiCache
- In-memory caching service for Valkey, Memcached, and Redis OSS
- Document:

#### Amazon Keyspaces (for Apache Cassandra)
- Managed Cassandra-compatible database
- Document:

#### Amazon MemoryDB
- Valkey- and Redis OSS-compatible, durable, in-memory database with ultra-fast performance
- Document:

#### Amazon Neptune
- Fully managed graph database service
- Document:

#### Amazon RDS
- Managed relational database service for PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, and Db2
- Document:

#### Amazon Timestream
- Fully managed time series database
- Document:

#### AWS Database Migration Service
- Migrate databases with minimal downtime
- Document:

### 5. Data Analytics Services <a name="dataanalytics"></a>
#### Amazon Athena
- Query data in S3 using SQL
- Document:

#### Amazon OpenSearch Service
- Search, visualize, and analyze up to petabytes of text and unstructured data
- Document:

#### Amazon EMR
- Easily run big data frameworks
- Document:

#### Amazon FinSpace
- Analytics for the financial services industry
- Document:

#### Amazon Kinesis
- Analyze real-time video and data streams
- Document:

#### Amazon Data Firehose
- Real-time streaming delivery for any data, at any scale, at low-cost
- Document:

#### Amazon Managed Service for Apache Flink
- Fully managed Apache Flink service
- Document:

#### Amazon Managed Streaming for Apache Kafka
- Fully managed Apache Kafka service
- Document:

#### Amazon Redshift
- Fast, simple, cost-effective data warehousing
- Document:

#### Amazon QuickSight
- Fast business analytics service
- Document:

#### AWS Data Exchange
- Find, subscribe to, and use third-party data in the cloud
- Document:

#### AWS Glue
- Simple, scalable, and serverless data integration
- Document:

#### AWS Lake Formation
- Build, manage, and secure your data lake
- Document:

### 6. Integration Services <a name="integration"></a>
#### AWS Step Functions
- Coordination for distributed applications
- Document:

#### Amazon API Gateway
- Build, deploy, and manage APIs
- Document:

#### Amazon AppFlow
- No-code integration for SaaS apps & AWS services
- Document:

#### Amazon EventBridge
- Serverless event bus for SaaS apps & AWS services
- Document:

#### Amazon Managed Workflows for Apache Airflow
- Highly available, secure, and managed workflow orchestration
- Document:

#### Amazon MQ
- Managed message broker service
- Document:

#### Amazon Simple Notification Service (SNS)
- Pub/sub, SMS, email, and mobile push notifications
- Document:

#### Amazon Simple Queue Service (SQS)
- Managed message queues
- Document:

#### AWS AppSync
- Fully-managed, scalable GraphQL APIs
- Document:

### 7. Cloud Financial Management Services <a name="cloudfinancial"></a>
#### AWS Cost Explorer
- Analyze your AWS cost and usage
- Document:

#### AWS Billing Conductor
- Simplify billing and reporting with customizable pricing and cost visibility
- Document:

#### AWS Budgets
- Set custom cost and usage budgets
- Document:

#### AWS Cost and Usage Report
- Access comprehensive cost and usage information
- Document:

### 8. Management & Governance Services <a name="managementgovernance"></a>
#### Amazon CloudWatch
- Monitor resources and applications
- Document:

#### Amazon Managed Grafana
- Powerful interactive data visualizations
- Document:

#### Amazon Managed Service for Prometheus
- Highly available, secure monitoring for containers
- Document:

#### AWS CloudFormation
- Create and manage resources with templates
- Document:

#### AWS CloudTrail
- Track user activity and API usage
- Document:

#### AWS Command Line Interface
- Unified tool to manage AWS services
- Document:

#### AWS Compute Optimizer
- Identify optimal AWS Compute resources
- Document:

#### AWS Config
- Track resources inventory and changes
- Document:

#### AWS Control Tower
- Set up and govern a secure, compliant multi-account environment
- Document:

#### AWS Health Dashboard
- View important events and changes affecting your AWS environment
- Document:

#### AWS License Manager
- Track, manage, and control licenses
- Document:

#### AWS Management Console
- Web-based user interface
- Document:

#### AWS Managed Services
- Infrastructure operations management for AWS
- Document:

#### AWS Organizations
- Central governance and management across AWS accounts
- Document:

#### AWS Proton
- Automated management for container and serverless deployment
- Document:

#### AWS Service Catalog
- Create and use standardized products
- Document:

#### AWS Systems Manager
- Gain operational insights and take action
- Document:

#### AWS Trusted Advisor
- Optimize performance and security
- Document:

#### AWS User Notifications
- Configure and view notifications from AWS services
- Document:

#### AWS Well-Architected Tool
- Review and improve your workloads
- Document:

### 9. Security, Identity, & Compliance Services <a name="securityidentity"></a>
#### AWS Identity and Access Management (IAM)
- Securely manage access to services and resources
- Document:

#### Amazon Cognito
- Identity management for your apps
- Document:

#### Amazon Detective
- Investigate potential security issues
- Document:

#### Amazon GuardDuty
- Managed threat detection service
- Document:

#### Amazon Inspector
- Automate vulnerability management
- Document:

#### Amazon Macie
- Discover and protect your sensitive data at scale
- Document:

#### Amazon Security Lake
- Automatically centralize your security data with a few clicks
- Document:

#### Amazon Verified Permissions
- Fine-grained permissions and authorization for your applications
- Document:

#### AWS Artifact
- On-demand access to AWS’ compliance reports
- Document:

#### AWS Audit Manager
- Continuously audit your AWS usage
- Document:

#### AWS Certificate Manager
- Provision, manage, and deploy SSL/TLS certificates
- Document:

#### AWS CloudHSM
- Hardware-based key storage for regulatory compliance
- Document:

#### AWS Directory Service
- Host and manage active directory
- Document:

#### AWS Firewall Manager
- Central management of firewall rules
- Document:

#### AWS Key Management Service
- Managed creation and control of encryption keys
- Document:

#### AWS Network Firewall
- Network security to protect your VPCs
- Document:

#### AWS Resource Access Manager
- Simple, secure service to share AWS resources
- Document:

#### AWS Secrets Manager
- Rotate, manage, and retrieve secrets
- Document:

#### AWS Security Hub
- Unified security and compliance center
- Document:

#### AWS Shield
- DDoS protection
- Document:

#### AWS IAM Identity Center
- Manage single sign-on access to AWS accounts and apps
- Document:

#### AWS WAF
- Filter malicious web traffic
- Document:

### 10. Networking Services <a name="networking"></a>
#### Amazon VPC
- Isolated cloud resources
- Document:

#### Amazon VPC Lattice
- Simplify service-to-service connectivity, security, and monitoring
- Document:

#### Amazon API Gateway
- Build, deploy, and manage APIs
- Document:

#### Amazon CloudFront
- Global content delivery network
- Document:

#### Amazon Route 53
- Scalable domain name system (DNS)
- Document:

#### AWS App Mesh
- Monitor and control microservices
- Document:

#### AWS Cloud Map
- Service discovery for cloud resources
- Document:

#### AWS Cloud WAN
- Easily build, manage, and monitor global wide area networks
- Document:

#### AWS Direct Connect
- Dedicated network connection to AWS
- Document:

#### AWS Global Accelerator
- Improve application availability and performance
- Document:

#### AWS Private 5G
- Easily deploy, manage, and scale a private cellular network
- Document:

#### AWS PrivateLink
- Securely access services hosted on AWS
- Document:

#### AWS Transit Gateway
- Easily scale VPC and account connections
- Document:

#### AWS Verified Access
- Provide secure access to corporate applications without a VPN
- Document:

#### AWS VPN
- Securely access your network resources
- Document:

#### Elastic Load Balancing (ELB)
- Distribute incoming traffic across multiple targets
- Document:

### 11. Migration Services <a name="migration"></a>
#### AWS Migration Hub
- Track migrations from a single place
- Document:

#### AWS Application Discovery Service
- Discover on-premises applications to streamline migration
- Document:

#### AWS Application Migration Service (MGN)
- Move and improve your on-premises and cloud-based applications
- Document:

#### AWS Database Migration Service
- Migrate databases with minimal downtime
- Document:

#### AWS DataSync
- Simple, fast, online data transfer
- Document:

#### AWS Migration Acceleration Program
- Comprehensive and proven cloud migration program
- Document:

#### AWS Optimization and Licensing Assessment
- Optimize your license and compute costs before and after migration
- Document:

#### AWS Transfer Family
- Fully managed SFTP, FTPS, FTP, and AS2 service
- Document:

#### Migration Evaluator (Formerly TSO Logic)
- Create a business case for cloud migration
- Document:

#### AWS for VMware
- Migrate and modernize VMware-based workloads
- Document:

### 12. Internet of Things Services <a name="internetofthings"></a>
#### AWS IoT Button
- Cloud programmable dash button
- Document:

#### AWS IoT Core
- Connect devices to the cloud
- Document:

#### AWS IoT Device Defender
- Security management for IoT devices
- Document:

#### AWS IoT Device Management
- Onboard, organize, and remotely manage IoT devices
- Document:

#### AWS IoT Events
- IoT event detection and response
- Document:

#### AWS IoT FleetWise
- Easily collect, transform, and transfer vehicle data to the cloud in near-real time
- Document:

#### AWS IoT Greengrass
- Local compute, messaging, and sync for devices
- Document:

#### Amazon Kinesis Video Streams
- Capture, process, and analyze real-time video streams
- Document:

#### FreeRTOS
- Real-time operating system for microcontrollers
- Document:

#### Amazon Location Service
- Securely and easily add location data to applications
- Document:

#### AWS Device Farm
- Test Android, iOS, and web apps on real devices in the AWS cloud
- Document:

### 13. Artificial Intelligence Services <a name="artificialintelligence"></a>
#### Amazon Q
- Generative AI-powered assistant for work
- Document:

#### Amazon Bedrock
- Build with foundation models
- Document:

#### Amazon SageMaker AI
- Build, train, and deploy machine learning models at scale
- Document:

#### AWS App Studio 
- Fastest and easiest way to build enterprise-grade applications
- Document:

#### Amazon Augmented AI
- Easily implement human review of ML predictions
- Document:

#### Amazon CodeGuru
- Find your most expensive lines of code
- Document:

#### Amazon Comprehend
- Discover insights and relationships in text
- Document:

#### Amazon Comprehend Medical
- Extract health data
- Document:

#### Amazon Elastic Inference
- Deep learning inference acceleration
- Document:

#### Amazon Fraud Detector
- Detect more online fraud faster
- Document:

#### Amazon Kendra
- Reinvent enterprise search with ML
- Document:

#### Amazon Lex
- Build voice and text chatbots
- Document:

#### Amazon Lookout for Metrics
- Detect anomalies in metrics
- Document:

#### Amazon Monitron
- End-to-end system for equipment monitoring
- Document:

#### AWS HealthLake
- Make sense of health data
- Document:

#### Amazon Personalize
- Build real-time recommendations into your applications
- Document:

#### Amazon Polly
- Turn text into life-like speech
- Document:

#### Amazon Rekognition
- Analyze image and video
- Document:

#### Amazon Textract
- Extract text and data from documents
- Document:

#### Amazon Translate
- Natural and fluent language translation
- Document:

#### Amazon Transcribe
- Automatic speech recognition
- Document:
