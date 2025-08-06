# Open and Connected Data with Open Table Formats in Teradata

Modern enterprises face the challenge of unifying data access across fragmented environments—multiple clouds, table formats, catalogs, and teams. Open Table Formats (OTFs) like Apache Iceberg and Delta Lake offer a better way. Teradata VantageCloud natively supports these formats, enabling teams to query and govern data where it lives—across AWS, Azure, GCP, or on-prem—while maintaining enterprise-grade performance, security, and governance.

## Project Overview

This repository contains Jupyter notebooks that demonstrate Teradata’s OTF capabilities on VantageCloud Lake including:
- Cross-catalog and cross-format querying
- Metadata exploration
- Schema evolution without rewriting existing data
- Time travel via snapshots

Whether you're dealing with siloed data, evolving schemas, or multi-format pipelines, these notebooks show how Teradata makes open, scalable analytics easy.

## Key Concepts

- **Open Table Formats Architecture:** Combines a distributed storage layer (e.g., S3, ADLS Gen2, GCS) with a data catalog for metadata management, schema evolution, partitioning, and versioning.
- **Database-like Features:** Schema enforcement, ACID transactions, and time travel for data lakes.
- **Multi-catalog Scenarios:** Demonstrates interoperability across Hive and Unity Catalogs, and between Iceberg and Delta Lake formats.
- **Metadata Exploration:** Use native Teradata commands to introspect data lakes, databases, and tables.
- **Schema Evolution:** Modify table schemas without rewriting historical data.
- **Time Travel:** Query historical snapshots for reproducibility and auditability.

## Getting Started

1. **Set up your Jupyter workspace**  
   Use the [Vantage Modules for Jupyter](https://downloads.teradata.com/download/tools/vantage-modules-for-jupyter).  
   Contact your Teradata system administrator for system access.
   Create a connection to your Teradata system.

2. **Connect to VantageCloud Lake**  
   Use the `%connect` magic command in your notebook to connect to your environment.

3. **Run the notebooks**  
   - Explore cross-catalog and cross-format querying.
   - Perform metadata exploration, schema evolution, and time travel.

## Example Workflow

- Drop previous data lakes and credentials for a clean environment.
- Create authorization objects and data lakes for Hive and Unity Catalogs.
- Define and load tables with sample data across catalogs and formats.
- Query and aggregate data, including cross-catalog and cross-format joins.
- Explore metadata and perform schema evolution.
- Use snapshot queries for time travel.

## Comments and Questions

Are you navigating multi-cloud data challenges or exploring open table formats?  
We’d love to hear about your experiences with data lakehouse modernization, cross-cloud analytics, or schema governance.  
For questions or guidance [feel free to contact us!](https://www.teradata.com/platform/open-table-formats).

---