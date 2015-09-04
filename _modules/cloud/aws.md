---
layout: default
title: Amazon Web Services (AWS) 
index: 0
---

Amazon Web Services
===================

Amazon Web Services is the most widely used Infrastructure as a Service (IaaS) platform there is. It is used for many different kinds of use cases and workloads from big data storage, processing and analytics to serving streaming video. The most common usage is for serving web applications in production and organizations across the public and private sectors from giant multi-nationals to startups to local governments use it to deploy and run their applications in the cloud. There are other cloud providers, but you will almost certainly work with Amazon Web Services on your projects and so its important to become familiar with the different services it provides and how they are used to deploy production applications on the web. 

The sections below cover the most commonly used AWS services, but there are many more that may be applicable for use in your application. Consult with your mentor to determine what services are required to deploy your application and how to architect your production setup for maximum performance, durability and scalability.

Elastic Compute Cloud (EC2)
---------------------------

Elastic Compute Cloud (EC2) is a web service that provides the ability to provision virtual machines of varying sizes and configurations for use in deploying your application. It allows you to scale up your application by easily provisioning more machines when demand warrants and deprovision those machines when not required. Using multiple virtual machines provides the developers the tools to build failure resilient applications.

You should become familiar with how to provision machines using EC2, how to configure their networks and attach storage to them. Depending on the type of application you are developing, you should learn how to architect your deployment for fault tolerance.

Simple Storage Service (S3)
---------------------------

Simple Storage Service (S3) provides developers and IT teams with secure, durable and scalable storage in the cloud. It can be used with various tools to store and retrieve large amounts of data via the web. S3 can be used with other AWS Services to perform backup and archivin, to provide content distribution or to do big data analytics. 

You should learn how to store and retrieve objects (data) on S3 using command line tools, desktop or browser based tools and with scripts or other automated methods. You should plan for disaster recovery early on in your application development lifecycle and incorporate a backup and archive plan using S3 or similar technology. 

Relational Database Service (RDS)
---------------------------------

Amazon Relational Database Service (RDS) allows you run the relational database(s) for your application in the cloud without having to worry about the configuration, management and administration of the relational database system itself. It frees the developer to focus on the application itself and rely on a well configured and scaleable database platform. 

If you are deploying your application on Amazon Web Services and it involves a relational database, you should be using RDS in production. You should learn how to provision an RDS database instance and configure it for use in your application.  


Goals/Objectives/Outcomes
-------------------------

* Understand the different AWS Services available and how they are used together to deploy an application in production
* Understand how to use EC2 Virtual Machines (instances) for development and production compute requirements
* Understand how to configure the networking and security of EC2 instances 
* Understand how to attach and configure EBS storage with EC2 instances
* Understand how to work with S3 for data object storage and retrieval and how to do archiving and backup using this service
* Understand how to use RDS for application databases
* Understand the range of other services available on AWS.
* Begin the process of architecting a durable, scalable and performant production setup for the prticipants application.

Reference Material
------------------

* http://aws.amazon.com/documentation/
* http://aws.amazon.com/documentation/gettingstarted/
* http://aws.amazon.com/documentation/ec2/
* http://aws.amazon.com/documentation/s3/
* http://aws.amazon.com/documentation/rds/


Measures of Success
-------------------

* Participant has demonstrated the ability to provision and work with EC2 instances for their project
* Participant has demonstrated the ability to work with S3 for backup and archiving using GUI, CLI and script based tools.
* Participant has demonstrated the ability to use RDS databases in their application
* Participant has begun the process of developing a production architecture for their application with their Mentor
