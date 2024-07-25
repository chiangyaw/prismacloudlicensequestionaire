# Prisma Cloud License Questionaire
## Introduction
This is a general guideline to help partners & customers to estimate their requirements for Prisma Cloud license credit count & consumption.

## Basics
Prisma Cloud supports 2 different deployment options, Enterprise Edition & Compute Edition. For more details, refer to [Prisma Cloud Enterprise Edition vs Compute Edition](https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin-compute/welcome/pcee_vs_pcce). The license required for both deployment options are in the form of credits. The amount of credits will be determined by the number of resources & features to be enabled. Despite having the same credit system, both deployment options are required to be calculated separately, as the license SKUs are different for both deployment options.

## Prisma Cloud Enterprise Edition
Prisma Cloud Enterprise Edition covers the full functionality of Prisma Cloud, which covers the following major modules:
- Cloud Security Posture Management (CSPM)
- Data Security Posture Management (DSPM)
- Cloud Workload Protection (CWP)
- Cloud Identity Security (CIS) / Cloud Infrastructure Entitlement Management (CIEM)
- Cloud Application Security (CAS)
It is important to understand the differences and features provided in each module. The information will be used to determine the credits required.
The Enterprise Edition is offered in different pricing plan:
1. Cloud Security Foundations
2. Cloud Security Advanced
3. Standard (A-la-carte)
The major differences between these pricing plans is the feature bundled. As a general guideline, for deployment in AWS, Azure & GCP, it is highly recommended to look into Cloud Security Foundations or Cloud Security Advanced, as Prisma Cloud supports Agentless Vulnerability Management & Cloud Identity Security for these Public Cloud Service Providers (CSP). For more details on the licensing, refer to the [Prisma Cloud Enterprise Edition Pricing Guide](https://www.paloaltonetworks.com/resources/guides/prisma-cloud-enterprise-edition-licensing-guide).

## Questions to ask for Prisma Cloud Enterprise Edition (Simplified Edition)
Here are some general questions to ask to determine the Prisma Cloud license credits required:
1. What is the preferred deployment options? (Enterprise / Compute)
2. For Enterprise Edition, what are the features required? (CSPM, DSPM, CWP, CIS, CAS)
3. For Enterprise Edition, how many virtual machines in all your cloud deployment? (including all types of VMs, AWS EC2, AWS EKS/ECS Worker Nodes)
4. For Enterprise Edition, if you need CAS, how many active developers or cloud infrastructure engineers that are actively committing to your code repository?
5. If DSPM is required, can you list down the quantity of the following assets in your environment?
    - AWS::S3::Bucket
    - AWS::ElastiCache::CacheCluster
    - AWS::DynamoDB::Table
    - AWS::RDS::DBCluster
    - AWS::RDS::DBInstance
    - AWS::EFS::FileSystem
    - AWS::EMR::Cluster
    - AWS::EMRContainers::VirtualCluster 
    - AWS::ElasticSearch::Domain
    - AWS::OpenSearchService::Domain
    - AWS::Fsx::FileSystem
    - AWS::Redshift::Cluster
    - microsoft.storage/storageaccounts
    - microsoft.documentdb/databaseaccounts
    - microsoft.synapse/workspaces
    - microsoft.sql/servers
    - microsoft.cache/redis
    - microsoft.dbformysql/servers
    - microsoft.dbformysql/flexibleservers
    - microsoft.dbforpostgresql/servergroupsv2
    - microsoft.dbforpostgresql/flexibleservers
    - microsoft.dbforpostgresql/servers
    - microsoft.dbformariadb/servers
    - storage.Bucket
    - sqladmin.Instance
    - file.Instance
    - bigquery.Dataset
    - bigtableadmin.Table
    - spanner.Database
    - redis.Instance
    - memcache.Instance
    - firestore.Database

## Prisma Cloud Compute Edition
Prisma Cloud Compute Edition covers only the Cloud Workload Protection module. For more details on Compute Edition, refer to the [Prisma Cloud Compute Edition Pricing Guide](https://www.paloaltonetworks.com/resources/guides/prisma-cloud-compute-edition-licensing-guide).
