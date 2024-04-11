---
title : "1.2. Problems"
date : "`r Sys.Date()`"
weight : 3
chapter : false
---
## Which problems does AWS Glue solve?
### Provisions and manages the lifecycle of resources
AWS Glue provisions the requested resources like servers, storage, and runtime environment that ETL jobs need. It also manages the lifecycle of these resources and removes them when they are not being used. AWS Glue maintains the resource pool from where requested capacity is allocated.

### Provides interactive tools
AWS Glue has tools for each persona for performing development activities that include no-code, low-code, and interactive tools, so it reduces development time.

### Auto-generates code
AWS Glue auto-generates code when built-in transformation are used, which is optimized for runtime and cost effectiveness. It also provides features to upload the scripts to make migration more straightforward.

### Connects to hundreds of data stores
AWS Glue connects to hundreds of data stores, including Amazon Redshift, relational databases, MongoDB, and software as a service (SaaS) providers like Salesforce. it also exposes APIs to conveniently build your own connectors.

### Creates a data catalog for various data sources
AWS Glue provides the opportunity to create a data catalog for various data sources that could help search metadata and classify data. AWS Glue Data Catalog is used by multiple analytics services to work on the data.

### Identifies sensitive data using ML recognition patterns for PII
AWS Glue helps in identifying sensitive data using ML recognition patterns for personally identifiable information (PII). After identification, you can remediate them by redacting through string or cryptographic hashing.

### Manage and enforce schemas on data-streaming applications
Using AWS Glue, you can also manage and enforce schemas on data-streaming applications. Integrations with Apache Kafka and Amazon Kinesis help ensure that downstream systems are not affected by semantic changes in upstream systems.

### Offers data quality and automatic data scaling
AWS Glue offers data quality for creating and applying built-in rule types or custom rule types to clean and normalize your data. AWS Glue automatically scales as the volume of data increases, and it is integrated with Amazon CloudWatch for monitoring.
