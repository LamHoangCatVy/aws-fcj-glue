---
title : "1.3. Benefits"
date : "`r Sys.Date()`"
weight : 4
chapter : false
---
## What are the benefits of AWS Glue?
### Faster data integration
With AWS Glue, developers have the flexibility to choose their preferred tool for data preparation and processing. This makes it possible to quickly deliver data for analytics, ML, and application development. By creating repeatable and reusable workflows, developers can streamline data integration and ETL processes, making collaboration on these tasks more efficient.

Data engineers can develop and test your AWS Glue job scripts thorugh multiple options
#### AWS Glue Studio console
- Visual editor
- Script editor
- AWS Glue Studio notebook

#### Interactive sessions
- Jupyter Notebook


#### Docker image
- Local development
- Remote development

#### AWS Glue Studio ETL library
- Local development

### Automate data integration at scale
AWS Glue uses crawlers to scan data sources, identify data format and metadata, register the data's schema, and generate code for transformations. It also provide workflows that developers can use to create streamlined and advanced pipelines for ETL tasks.

### No infrastructure to manage
AWS Glue helps you prepare and work on data without users needing to provision and maintain any infrastructure. This makes AWS Glue serverless, because AWS will manage and provision servers from a warm pool. It automatically scales resources up and down as required by AWS Glue jobs. By doing this, data engineers and developers can focus on writing business logic and creating complex workflows. AWS Glue works with contiunous integration and continuous delivery (CI/CD) and also with alerting or monitoring services to make their workload self-service.

### Create, run, and monitor ETL jobs without coding
AWS Glue Studio provides straightforward creation, running and monitoring of ETL tasks for data transformation through a user-friendly drag-and-drop interface. It automatically generates code and offers built-in transformations from AWS Glue DataBrew that can assist with data cleaning and standardization. The processed data can then be used for analytical and ML purpsoes

### Pay only for what you use
With AWS Glue, users pay only for the resources they consume. There's no upfront cost, and users are not charged for a start-up or shutdown time
