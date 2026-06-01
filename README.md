# Awesome Data Engineering [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1123974508.svg)](https://doi.org/10.5281/zenodo.19673251)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

> A curated list of tools, frameworks, platforms, architectures, and learning resources for **data engineering**, covering data ingestion, transformation, storage, orchestration, and reliable data infrastructure at scale.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Foundations & Concepts](#foundations--concepts)
- [Data Ingestion & Integration](#data-ingestion--integration)
- [Streaming & Event Processing](#streaming--event-processing)
- [Data Transformation & Modeling](#data-transformation--modeling)
- [Workflow Orchestration](#workflow-orchestration)
- [Storage, Warehousing & Lakehouses](#storage-warehousing--lakehouses)
- [Query Engines & Analytics](#query-engines--analytics)
- [NoSQL & Specialized Datastores](#nosql--specialized-datastores)
- [Data Quality, Governance & Lineage](#data-quality-governance--lineage)
- [Observability & Reliability](#observability--reliability)
- [Infrastructure & Platforms](#infrastructure--platforms)
- [Data Engineering on the Cloud](#data-engineering-on-the-cloud)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Foundations & Concepts

- [Data Engineering Explained](https://www.ibm.com/topics/data-engineering) – Overview of data engineering roles, responsibilities, and workflows.
- [Modern Data Stack](https://www.getdbt.com/what-is-the-modern-data-stack/) – Overview of modern analytics and data engineering tooling.
- [Data Lake vs Data Warehouse](https://www.databricks.com/glossary/data-lakehouse) – Comparison of storage architectures for analytics.
- [CAP Theorem](https://www.ibm.com/topics/cap-theorem) – Fundamental trade-offs in distributed data systems.
- [Event-Driven Architecture](https://martinfowler.com/articles/201701-event-driven.html) – Architectural style for real-time data systems.

## Data Ingestion & Integration

- [Apache Kafka Connect](https://kafka.apache.org/documentation/#connect) – Framework for moving data between Kafka and external systems.
- [Apache NiFi](https://nifi.apache.org/) – Visual data ingestion and flow automation platform.
- [Airbyte](https://airbyte.com/) – Open-source data integration platform for ELT pipelines.
- [Fivetran](https://www.fivetran.com/) – Managed data connectors for analytics and warehousing.
- [Singer](https://www.singer.io/) – Open-source standard for data extraction and loading.
- [Debezium](https://debezium.io/) – Change data capture (CDC) platform for databases.

## Streaming & Event Processing

- [Apache Kafka](https://kafka.apache.org/) – Distributed event streaming platform.
- [Apache Pulsar](https://pulsar.apache.org/) – Cloud-native pub/sub and streaming platform.
- [Apache Flink](https://flink.apache.org/) – Stream-first processing framework with low latency.
- [Kafka Streams](https://kafka.apache.org/documentation/streams/) – Stream processing library built on Kafka.
- [Apache Storm](https://storm.apache.org/) – Real-time computation system for stream processing.

## Data Transformation & Modeling

- [dbt](https://www.getdbt.com/) – SQL-based transformation and analytics engineering tool.
- [Apache Spark](https://spark.apache.org/) – Distributed engine for large-scale data processing.
- [Apache Beam](https://beam.apache.org/) – Unified programming model for batch and streaming pipelines.
- [Dask](https://www.dask.org/) – Parallel computing library for scalable Python data processing.
- [SQLMesh](https://sqlmesh.com/) – Versioned, testable SQL transformations.

## Workflow Orchestration

- [Apache Airflow](https://airflow.apache.org/) – Platform for scheduling and monitoring data workflows.
- [Dagster](https://dagster.io/) – Data orchestration platform with strong observability and testing.
- [Prefect](https://www.prefect.io/) – Workflow orchestration system for data pipelines.
- [Luigi](https://github.com/spotify/luigi) – Python package for building complex pipelines.
- [Argo Workflows](https://argo-workflows.readthedocs.io/) – Kubernetes-native workflow engine.

## Storage, Warehousing & Lakehouses

- [Amazon S3](https://aws.amazon.com/s3/) – Object storage widely used as a data lake.
- [Google Cloud Storage](https://cloud.google.com/storage) – Scalable object storage for analytics workloads.
- [Azure Data Lake Storage](https://azure.microsoft.com/products/storage/data-lake-storage/) – Optimized storage for analytics on Azure.
- [Snowflake](https://www.snowflake.com/) – Cloud-native data warehouse.
- [BigQuery](https://cloud.google.com/bigquery) – Serverless analytics data warehouse.
- [Delta Lake](https://delta.io/) – Open-source storage layer enabling lakehouse architecture.
- [Apache Iceberg](https://iceberg.apache.org/) – Table format for large-scale analytic datasets.
- [Apache Hudi](https://hudi.apache.org/) – Incremental data processing and lakehouse framework.

## Query Engines & Analytics

- [Trino](https://trino.io/) – Distributed SQL query engine for large datasets.
- [Presto](https://prestodb.io/) – High-performance distributed SQL engine.
- [Spark SQL](https://spark.apache.org/sql/) – SQL analytics module built on Apache Spark.
- [DuckDB](https://duckdb.org/) – In-process analytical SQL engine.
- [ClickHouse](https://clickhouse.com/) – Column-oriented OLAP database.

## NoSQL & Specialized Datastores

- [Apache Cassandra](https://cassandra.apache.org/) – Distributed wide-column NoSQL database.
- [MongoDB](https://www.mongodb.com/) – Document-oriented NoSQL database.
- [Apache HBase](https://hbase.apache.org/) – NoSQL database built on HDFS.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) – Managed NoSQL key-value store.
- [Redis](https://redis.io/) – In-memory data store for caching and streaming use cases.

## Data Quality, Governance & Lineage

- [Great Expectations](https://greatexpectations.io/) – Data quality validation framework.
- [Apache Atlas](https://atlas.apache.org/) – Metadata management and data governance platform.
- [OpenLineage](https://openlineage.io/) – Open standard for capturing data lineage.
- [DataHub](https://datahubproject.io/) – Open-source metadata and data catalog.
- [Amundsen](https://www.amundsen.io/) – Data discovery and metadata engine.
- [OneQuery](https://github.com/wordbricks/onequery) – Self-hosted data access gateway for databases, analytics tools, and APIs, with centralized credentials, read-only query validation, query limits, and audit logs.

## Observability & Reliability

- [Monte Carlo](https://www.montecarlodata.com/) – Data observability platform for pipelines.
- [Bigeye](https://www.bigeye.com/) – Data quality monitoring and alerting.
- [Prometheus](https://prometheus.io/) – Metrics and monitoring system.
- [Grafana](https://grafana.com/) – Visualization platform for observability.
- [OpenTelemetry](https://opentelemetry.io/) – Observability framework for distributed systems.

## Infrastructure & Platforms

- [Kubernetes](https://kubernetes.io/) – Container orchestration for data workloads.
- [Ray](https://www.ray.io/) – Distributed computing framework for scalable data processing.
- [Terraform](https://www.terraform.io/) – Infrastructure as code for data platforms.
- [Apache Mesos](https://mesos.apache.org/) – Distributed systems kernel for resource management.

## Data Engineering on the Cloud

- [Databricks](https://www.databricks.com/) – Unified analytics platform built on Apache Spark.
- [AWS EMR](https://aws.amazon.com/emr/) – Managed big data platform on AWS.
- [Google Dataproc](https://cloud.google.com/dataproc) – Managed Spark and Hadoop service.
- [Azure Synapse Analytics](https://azure.microsoft.com/products/synapse-analytics/) – Integrated analytics service.
- [Snowflake Data Cloud](https://www.snowflake.com/) – Platform for data sharing and analytics.

## Learning Resources

### Tutorials
- [Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) – Free hands-on data engineering course.
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/) – Official Spark guides and examples.
- [Kafka Documentation](https://kafka.apache.org/documentation/) – Official Kafka tutorials.

### Guides
- [Designing Data-Intensive Applications](https://dataintensive.net/) – Foundational book on scalable data systems.
- [Streaming Systems](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) – Concepts and architectures for stream processing.
- [Data Engineering Best Practices](https://www.getdbt.com/blog/) – Modern data engineering workflows.

### Courses
- *Data Engineering Fundamentals* – Core data pipeline concepts.
- *Streaming Data Engineering* – Real-time data processing architectures.
- *Cloud Data Engineering* – Building scalable pipelines in the cloud.

## Related Awesome Lists

- [Awesome Big Data](https://github.com/awesomelistsio/awesome-big-data)
- [Awesome Data Analytics](https://github.com/awesomelistsio/awesome-data-analytics)
- [Awesome SQL](https://github.com/awesomelistsio/awesome-sql)
- [Awesome Cloud](https://github.com/awesomelistsio/awesome-cloud)
- [Awesome MLOps](https://github.com/awesomelistsio/awesome-mlops)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
