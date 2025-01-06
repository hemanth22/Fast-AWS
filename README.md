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
- [Common AWS Services In-Short]
  - [Compute Services]
  - [Container Services]
  - [Database Services]  
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

## Common AWS Services In-Short <a name="services-in-short"></a>
### Compute Services
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
  
### Container Services
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

### Databases

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
  
