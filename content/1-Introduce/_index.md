---
title : "Introduction"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
### Introduction
Table of Contents:
- Cloud Computing
- Amazon Web Services
- Cost Optimization
- AWS Management Console

### Cloud Computing
Cloud computing (Cloud Computing) is the on-demand delivery of information technology resources over the Internet with a pay-as-you-go policy.

### Amazon Web Services
Amazon Web Services (AWS) is the most widely used cloud computing service provider, offering over 200 full-featured services from data centers around the world.

What differentiates AWS from other service providers:

- Vision & Culture;
- AWS pricing philosophy: use more, pay less;
- Leadership Principles: [https://www.amazon.jobs/content/en/our-workplace/leadership-principles](https://www.amazon.jobs/content/en/our-workplace/leadership-principles)

### Cost Optimization
To optimize costs when using cloud computing services, it is necessary to:
- Choose the appropriate computing resource configuration and data storage location;
- Use discount payment methods such as reserve, savings plan, spot;
- Delete unused resources, automatically turn off resources that do not need to run 24/7;
- Use serverless service;
- Optimize architectural design requirements;
- Install and use AWS Budget;
- Manage costs by department/application with cost allocation tags;
- Continue to monitor and prioritize.

Use the cost calculation work: https://computer.aws/
- Allows to create estimated service information;
- Can share estimates with others;
- Costs will be thirsty by region.

### AWS Management Console
AWS Mangement Console is the AWS display console. Includes digital components:

| Components | Functions |
| ---------------------------------- | -----------------------------------------------|
| Root Login | - The root account, created first;<br>- Has full, unlimited access to all resources.|
| IAM User Login | - Child account that manages AWS resources;<br>- When logging in with IAM, the User needs to provide an Account ID (a 12-digit string) to identify the AWS Account.|
| Search for services | - Service search bar.|
| Support Center | - Create support cases to request support from the AWS sleep team;|
| AWS Command Line Interface (CLI) | - Open source tool for interacting with AWS services using commands (commands).|
| AWS Software Development Kit (SDK) | - A set of software tools provided by AWS to help programmers easily interact with AWS services from their application code; <br>- Provides lifecycle management of APIs to AWS services such as:<br>+ Credential management (credential management);<br>+ Retries (retries);<br>+ Data marshaling (data marshaling - data preparation);<br>+ Serialization (serialization converts objects to byte streams);<br>+ Deserialization (deserialization converts byte streams back to objects).|