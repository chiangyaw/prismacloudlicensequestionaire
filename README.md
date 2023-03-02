# Prisma Cloud License Questionaire
## Introduction
This is a general guideline to help partners & customers to estimate their requirements for Prisma Cloud licensse credit count & consumption.

## Basics
Prisma Cloud supports 2 different deployment options, Enterprise Edition & Compute Edition. For more details, refer to [Prisma Cloud Enterprise Edition vs Compute Edition](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute/welcome/pcee_vs_pcce). The license required for both deployment options are in the form of credits. The amount of credits will be determined by the number of resources & features to be enabled. Despite having the same credit system, both deployment options are required to be calculated separately, as the license SKUs are different for both deployment options.

## Prisma Cloud Enterprise Edition
Prisma Cloud Enterprise Edition covers the full functionality of Prisma Cloud, which covers 4 major modules:
- Cloud Security Posture Management (CSPM)
- Cloud Workload Protection (CWP)
- Cloud Identity Security (CIS)
- Cloud Code Security (CCS)
It is important to understand the differences and features provided in each module. The information will be used to determine the credits required.
The Enterprise Edition is offered in different pricing plan:
1. Cloud Security Foundations
2. Cloud Security Advanced
3. Standard (A-la-carte)
The major differences between these pricing plans is the feature bundled. As a general guideline, for deployment in AWS, Azure & GCP, it is highly recommended to look into Cloud Security Foundations or Cloud Security Advanced, as Prisma Cloud supports Agentless Vulnerability Management & Cloud Identity Security for these Public Cloud Service Providers (CSP).

## Questions to ask for Prisma Cloud Enterprise Edition
Here are some general questions to ask to determine the Prisma Cloud license credits required:
1. What is the preferred deployment options? (Enterprise / Compute)
2. For Enterprise Edition, what are the features required? (CSPM, CWP, CIS, CCS)
3. For Enterprise Edition, how many virtual machines in all your cloud deployment? (including all types of VMs, AWS EC2, AWS EKS/ECS Worker Nodes, 

## Prisma Cloud Compute Edition
Prisma Cloud Compute Edition covers only the Cloud Workload Protection module.
