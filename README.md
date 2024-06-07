# AWS Cloud Project: Hosting a High-Availability Web Application
This project demonstrates how to design, build, and deploy a highly available, scalable, and secure web application on AWS. The application will be hosted on a combination of AWS services to ensure optimal performance and cost-efficiency.
## Table of Contents
+ Introduction
+ Architecture
+ Prerequisites
+ Project Phases
    1. Phase : Planning the Design and Estimating Cost
    2. Phase : Creating a Basic Functional Web Application
    3. Phase : Decoupling the Application Components
    4. Phase : Implementing High Availability and Scalability
+ Lab Environment and Budget Monitoring
+ Assumptions
+ Approach
+ Solution Requirements
+ Testing

# Introduction
In this project, I will create a proof of concept (POC) to host a web application for student records on AWS. The goal of this project is to improve user experience during peak periods by ensuring the application is highly available, scalable, load balanced, secure, and high-performing.

# Architecture
The architecture includes:

+ **Amazon S3**: For static website hosting.
+ **Amazon Route 53**: For domain management.
+ **Amazon EC2**: For hosting the web application.
+ **Amazon RDS**: For hosting the relational database.
+ **AWS Secrets Manager**: For managing database credentials securely.
+ **Amazon VPC**: For networking.
+ **Elastic Load Balancing**: For distributing traffic across multiple instances.
+ **Auto Scaling**: For scaling instances based on demand.
