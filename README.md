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
  - [1.Compute Services](#compute)
  - [2.Container Services](#container)
  - [3.Storage Services](#storage)
  - [4.Database Services](#database)
  - [5.Data Analytics Services](#dataanalytics)
  - [6.Integration Services ](#integration)
  - [7.Cloud Financial Management Services](#cloudfinancial)
  - [8.Management & Governance Services](#managementgovernance)
  - [9.Security, Identity, & Compliance Services](#securityidentity)
  - [10.Networking Services](#networking)
  - [11.Migration Services](#migration)
  - [12.Internet of Things Services](#internetofthings)
  - [13.Artificial Intelligence Services](#artificialintelligence)
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

## Common AWS Services In-Short <a name="servicesshort"></a>
### 1.Compute Services <a name="compute"></a>
#### Amazon EC2 
- Virtual servers in the cloud
- Document: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html 

#### Amazon EC2 Auto Scaling 
- Scale compute capacity to meet demand
- Document: https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html

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
  
### 2.Container Services  <a name="container"></a>
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
  
### 3.Storage Services <a name="storage"></a>
#### Amazon Simple Storage Service (S3)
- Scalable storage in the cloud

#### Amazon S3 Glacier storage classes
- Low-cost archive storage in the cloud

#### Amazon Elastic Block Store (EBS)
- EC2 block storage volumes

#### Amazon Elastic File System (EFS)
- Fully managed file system for EC2

#### Amazon FSx for Lustre
- High-performance file system integrated with S3

#### Amazon FSx for NetApp ONTAP
- Fully managed storage built on NetApp’s popular ONTAP file system

#### Amazon FSx for OpenZFS
- Fully managed storage built on the popular OpenZFS file system

#### Amazon FSx for Windows File Server
- Fully managed Windows native file system

#### Amazon File Cache
- High-speed cache for datasets stored anywhere

#### AWS Backup
- Centralized backup across AWS services

#### AWS Elastic Disaster Recovery (DRS)
- Scalable, cost-effective application recovery

#### AWS Snowball
- Accelerate moving offline data or remote storage to the cloud

#### AWS Storage Gateway
- Hybrid storage integration

### 4.Database Services <a name="database"></a>
#### Amazon Aurora
- High performance managed relational database with full MySQL and PostgreSQL compatibility

#### Amazon Aurora DSQL
- Fastest serverless distributed SQL database with active-active high availability

#### Amazon Aurora Serverless V2
- Instantly scale to >100,000 transactions per second

#### Amazon DocumentDB (with MongoDB compatibility)
- Fully managed document database

#### Amazon DynamoDB
- Managed NoSQL database

#### Amazon ElastiCache
- In-memory caching service for Valkey, Memcached, and Redis OSS

#### Amazon Keyspaces (for Apache Cassandra)
- Managed Cassandra-compatible database

#### Amazon MemoryDB
- Valkey- and Redis OSS-compatible, durable, in-memory database with ultra-fast performance

#### Amazon Neptune
- Fully managed graph database service

#### Amazon RDS
- Managed relational database service for PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, and Db2

#### Amazon Timestream
- Fully managed time series database

#### AWS Database Migration Service
- Migrate databases with minimal downtime

### 5.Data Analytics Services <a name="dataanalytics"></a>
#### Amazon Athena
- Query data in S3 using SQL

#### Amazon OpenSearch Service
- Search, visualize, and analyze up to petabytes of text and unstructured data

#### Amazon EMR
- Easily run big data frameworks

#### Amazon FinSpace
- Analytics for the financial services industry

#### Amazon Kinesis
- Analyze real-time video and data streams

#### Amazon Data Firehose
- Real-time streaming delivery for any data, at any scale, at low-cost

#### Amazon Managed Service for Apache Flink
- Fully managed Apache Flink service

#### Amazon Managed Streaming for Apache Kafka
- Fully managed Apache Kafka service

#### Amazon Redshift
- Fast, simple, cost-effective data warehousing

#### Amazon QuickSight
- Fast business analytics service

#### AWS Data Exchange
- Find, subscribe to, and use third-party data in the cloud

#### AWS Glue
- Simple, scalable, and serverless data integration

#### AWS Lake Formation
- Build, manage, and secure your data lake

### 6.Integration Services <a name="integration"></a>
#### AWS Step Functions
- Coordination for distributed applications

#### Amazon API Gateway
- Build, deploy, and manage APIs

#### Amazon AppFlow
- No-code integration for SaaS apps & AWS services

#### Amazon EventBridge
- Serverless event bus for SaaS apps & AWS services

#### Amazon Managed Workflows for Apache Airflow
- Highly available, secure, and managed workflow orchestration

#### Amazon MQ
- Managed message broker service

#### Amazon Simple Notification Service (SNS)
- Pub/sub, SMS, email, and mobile push notifications

#### Amazon Simple Queue Service (SQS)
- Managed message queues

#### AWS AppSync
- Fully-managed, scalable GraphQL APIs

### 7.Cloud Financial Management Services <a name="cloudfinancial"></a>
#### AWS Cost Explorer
- Analyze your AWS cost and usage

#### AWS Billing Conductor
- Simplify billing and reporting with customizable pricing and cost visibility

#### AWS Budgets
- Set custom cost and usage budgets

#### AWS Cost and Usage Report
- Access comprehensive cost and usage information

### 8.Management & Governance Services <a name="managementgovernance"></a>
#### Amazon CloudWatch
- Monitor resources and applications

#### Amazon Managed Grafana
- Powerful interactive data visualizations

#### Amazon Managed Service for Prometheus
- Highly available, secure monitoring for containers

#### AWS CloudFormation
- Create and manage resources with templates

#### AWS CloudTrail
- Track user activity and API usage

#### AWS Command Line Interface
- Unified tool to manage AWS services

#### AWS Compute Optimizer
- Identify optimal AWS Compute resources

#### AWS Config
- Track resources inventory and changes

#### AWS Control Tower
- Set up and govern a secure, compliant multi-account environment

#### AWS Health Dashboard
- View important events and changes affecting your AWS environment

#### AWS License Manager
- Track, manage, and control licenses

#### AWS Management Console
- Web-based user interface

#### AWS Managed Services
- Infrastructure operations management for AWS

#### AWS Organizations
- Central governance and management across AWS accounts

#### AWS Proton
- Automated management for container and serverless deployment

#### AWS Service Catalog
- Create and use standardized products

#### AWS Systems Manager
- Gain operational insights and take action

#### AWS Trusted Advisor
- Optimize performance and security

#### AWS User Notifications
- Configure and view notifications from AWS services

#### AWS Well-Architected Tool
- Review and improve your workloads

### 9.Security, Identity, & Compliance Services <a name="securityidentity"></a>
#### AWS Identity and Access Management (IAM)
- Securely manage access to services and resources

#### Amazon Cognito
- Identity management for your apps

#### Amazon Detective
- Investigate potential security issues

#### Amazon GuardDuty
- Managed threat detection service

#### Amazon Inspector
- Automate vulnerability management

#### Amazon Macie
- Discover and protect your sensitive data at scale

#### Amazon Security Lake
- Automatically centralize your security data with a few clicks

#### Amazon Verified Permissions
- Fine-grained permissions and authorization for your applications

#### AWS Artifact
- On-demand access to AWS’ compliance reports

#### AWS Audit Manager
- Continuously audit your AWS usage

#### AWS Certificate Manager
- Provision, manage, and deploy SSL/TLS certificates

#### AWS CloudHSM
- Hardware-based key storage for regulatory compliance

#### AWS Directory Service
- Host and manage active directory

#### AWS Firewall Manager
- Central management of firewall rules

#### AWS Key Management Service
- Managed creation and control of encryption keys

#### AWS Network Firewall
- Network security to protect your VPCs

#### AWS Resource Access Manager
- Simple, secure service to share AWS resources

#### AWS Secrets Manager
- Rotate, manage, and retrieve secrets

#### AWS Security Hub
- Unified security and compliance center

#### AWS Shield
- DDoS protection

#### AWS IAM Identity Center
- Manage single sign-on access to AWS accounts and apps

#### AWS WAF
- Filter malicious web traffic

### 10.Networking Services <a name="networking"></a>
#### Amazon VPC
- Isolated cloud resources

#### Amazon VPC Lattice
- Simplify service-to-service connectivity, security, and monitoring

#### Amazon API Gateway
- Build, deploy, and manage APIs

#### Amazon CloudFront
- Global content delivery network

#### Amazon Route 53
- Scalable domain name system (DNS)

#### AWS App Mesh
- Monitor and control microservices

#### AWS Cloud Map
- Service discovery for cloud resources

#### AWS Cloud WAN
- Easily build, manage, and monitor global wide area networks

#### AWS Direct Connect
- Dedicated network connection to AWS

#### AWS Global Accelerator
- Improve application availability and performance

#### AWS Private 5G
- Easily deploy, manage, and scale a private cellular network

#### AWS PrivateLink
- Securely access services hosted on AWS

#### AWS Transit Gateway
- Easily scale VPC and account connections

#### AWS Verified Access
- Provide secure access to corporate applications without a VPN

#### AWS VPN
- Securely access your network resources

#### Elastic Load Balancing (ELB)
- Distribute incoming traffic across multiple targets

### 11.Migration Services <a name="migration"></a>
#### AWS Migration Hub
- Track migrations from a single place

#### AWS Application Discovery Service
- Discover on-premises applications to streamline migration

#### AWS Application Migration Service (MGN)
- Move and improve your on-premises and cloud-based applications

#### AWS Database Migration Service
- Migrate databases with minimal downtime

#### AWS DataSync
- Simple, fast, online data transfer

#### AWS Migration Acceleration Program
- Comprehensive and proven cloud migration program

#### AWS Optimization and Licensing Assessment
- Optimize your license and compute costs before and after migration

#### AWS Transfer Family
- Fully managed SFTP, FTPS, FTP, and AS2 service

#### Migration Evaluator (Formerly TSO Logic)
- Create a business case for cloud migration

#### AWS for VMware
- Migrate and modernize VMware-based workloads

### 12.Internet of Things Services <a name="internetofthings"></a>
#### AWS IoT Button
- Cloud programmable dash button

#### AWS IoT Core
- Connect devices to the cloud

#### AWS IoT Device Defender
- Security management for IoT devices

#### AWS IoT Device Management
- Onboard, organize, and remotely manage IoT devices

#### AWS IoT Events
- IoT event detection and response

#### AWS IoT FleetWise
- Easily collect, transform, and transfer vehicle data to the cloud in near-real time

#### AWS IoT Greengrass
- Local compute, messaging, and sync for devices

#### Amazon Kinesis Video Streams
- Capture, process, and analyze real-time video streams

#### FreeRTOS
- Real-time operating system for microcontrollers

#### Amazon Location Service
- Securely and easily add location data to applications

#### AWS Device Farm
- Test Android, iOS, and web apps on real devices in the AWS cloud

### 13.Artificial Intelligence Services <a name="artificialintelligence"></a>
#### Amazon Q
- Generative AI-powered assistant for work

#### Amazon Bedrock
- Build with foundation models

#### Amazon SageMaker AI
- Build, train, and deploy machine learning models at scale

#### AWS App Studio 
- Fastest and easiest way to build enterprise-grade applications

#### Amazon Augmented AI
- Easily implement human review of ML predictions

#### Amazon CodeGuru
- Find your most expensive lines of code

#### Amazon Comprehend
- Discover insights and relationships in text

#### Amazon Comprehend Medical
- Extract health data

#### Amazon Elastic Inference
- Deep learning inference acceleration

#### Amazon Fraud Detector
- Detect more online fraud faster

#### Amazon Kendra
- Reinvent enterprise search with ML

#### Amazon Lex
- Build voice and text chatbots

#### Amazon Lookout for Metrics
- Detect anomalies in metrics

#### Amazon Monitron
- End-to-end system for equipment monitoring

#### AWS HealthLake
- Make sense of health data

#### Amazon Personalize
- Build real-time recommendations into your applications

#### Amazon Polly
- Turn text into life-like speech

#### Amazon Rekognition
- Analyze image and video

#### Amazon Textract
- Extract text and data from documents

#### Amazon Translate
- Natural and fluent language translation

#### Amazon Transcribe
- Automatic speech recognition
