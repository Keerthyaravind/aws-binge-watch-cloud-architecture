# Binge Watch Online – AWS Cloud Architecture

## Project Overview

This Cloud Architect Capstone project demonstrates the deployment of an online entertainment website on AWS.

The scenario is based on Binge Watch Online, an entertainment provider receiving traffic from users around the world. The existing website experienced slow page-loading performance because static content was being served from a single location.

The solution was designed using AWS cloud services to improve global content delivery, manage DNS traffic, store static website content, support file sharing, and provide appropriate governance and cost management.

## Objectives

The main objectives of the project were to:

- Deploy website resources on AWS
- Improve delivery of static content to global users
- Store static website files in Amazon S3
- Use Amazon CloudFront for content delivery
- Use Amazon Route 53 for DNS management
- Work with Amazon EC2 compute resources
- Support storage and file-sharing requirements
- Connect compute resources with storage services
- Organise development, testing, and production resources
- Consider billing and cost management for cloud resources

## Technologies and Tools Used

- Amazon Web Services (AWS)
- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- Amazon EC2
- AWS Identity and Access Management (IAM)
- AWS Management Console
- AWS resource tagging
- AWS cost management and budgeting features

## Architecture

The solution uses AWS services to provide storage, compute, DNS management, and global content delivery.

A simplified request flow is:

User
↓
Route 53
↓
CloudFront
↓
Amazon S3
↓
Static Website Content

Amazon EC2 provides compute capability where required as part of the wider cloud environment.

## Key Features and Functionalities

### Amazon S3 – Static Content Storage

Amazon S3 was used to store static website content such as HTML files and other static assets.

Using cloud object storage provides scalable storage for website content.

### Amazon CloudFront – Content Delivery

Amazon CloudFront was used as the Content Delivery Network (CDN).

CloudFront can cache content closer to users through edge locations, helping improve the delivery of static website content to geographically distributed users.

### Amazon Route 53 – DNS

Amazon Route 53 was included in the architecture for DNS management.

It provides the DNS layer that directs users towards the appropriate website endpoint.

### Amazon EC2 – Compute

Amazon EC2 was used as the compute service within the cloud architecture.

The project also provided practical experience with connecting compute resources to cloud storage services.

### Resource Governance

The solution considered separation and governance of resources used for:

- Development
- Testing
- Production

Resource tagging can be used to identify and organise resources according to their environment and purpose.

### Cost Management

Cost management was considered so that resources and services associated with the website could be tracked.

Environment-specific tagging and AWS billing/cost-management capabilities can help identify resource usage and understand cloud expenditure.

## My Role and Contributions

I worked on the design, configuration, and testing of the AWS cloud solution.

My responsibilities included:

- Reviewing the business requirements
- Designing an appropriate AWS architecture
- Working with Amazon S3 for static content
- Configuring CloudFront for content delivery
- Working with Route 53 for DNS
- Working with Amazon EC2
- Uploading website content to cloud storage
- Considering resource governance across environments
- Applying resource tagging
- Considering cloud billing and cost management
- Testing the implemented cloud solution
- Documenting the architecture and implementation

## Implementation Steps

1. Reviewed the website and global traffic requirements.
2. Selected AWS as the cloud platform.
3. Created/configured Amazon S3 storage.
4. Uploaded static website content to S3.
5. Configured Amazon CloudFront for content delivery.
6. Configured the required DNS components using Route 53.
7. Worked with an Amazon EC2 instance for compute requirements.
8. Connected compute and storage resources where required.
9. Organised resources for development, testing, and production.
10. Applied resource-management and tagging practices.
11. Considered billing and cost-management requirements.
12. Tested the website and cloud configuration.

## How to Reproduce the Project

A similar architecture can be created by:

1. Creating an AWS account and signing in to the AWS Management Console.
2. Creating an Amazon S3 bucket.
3. Uploading the required static website files.
4. Configuring the required S3 access settings.
5. Creating an Amazon CloudFront distribution with the appropriate origin.
6. Configuring DNS using Amazon Route 53.
7. Deploying an EC2 instance if compute resources are required.
8. Configure the required permissions between AWS resources.
9. Apply tags to identify development, testing, and production resources.
10. Configure appropriate AWS cost-monitoring and budgeting controls.
11. Test website accessibility and content delivery.

## Project Outcome

The project demonstrated a cloud architecture for an online entertainment provider using AWS services.

The solution addressed global static-content delivery using Amazon CloudFront, cloud storage using Amazon S3, DNS management using Route 53, and compute requirements using Amazon EC2.

The project also considered resource governance, environment separation, and cloud cost management.

## Key Learnings

Through this capstone project, I gained practical experience with:

- AWS cloud architecture
- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- Amazon EC2
- Content Delivery Networks (CDN)
- DNS concepts
- Static website hosting
- Cloud storage
- Resource tagging
- Development, testing, and production environments
- Cloud governance
- AWS cost management
- Designing solutions for global users
