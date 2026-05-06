# fabric-retail-analytics-platform
End-to-end data engineering solution using Microsoft Fabric with medallion architecture

# Fabric Retail Analytics Platform

![Architecture](docs/architecture.png)
 
 
 
## Overview
Production-ready data engineering solution built on Microsoft Fabric, implementing medallion architecture (Bronze-Silver-Gold) for retail analytics.
 
## Architecture
[We'll add this later]
 
## Technologies
- Microsoft Fabric Data Factory
- Fabric Lakehouse
- PySpark (Fabric Notebooks)
- Delta Lake
- Power BI
- Python

  flowchart LR
    A[Source Data] --> B[Notebook or Dataflow Gen2]
    B --> C[Bronze Lakehouse]
    C --> D[Silver Cleansing]
    D --> E[Gold Aggregations]
    E --> F[Power BI Dashboard]
    D --> G[GitHub Portfolio]
