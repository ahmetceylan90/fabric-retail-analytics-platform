# End-to-End Retail Analytics Platform
 
End-to-end data engineering solution built on Microsoft Fabric, implementing a medallion architecture for retail analytics.
 
## Project Overview
 
This project demonstrates an end-to-end retail analytics pipeline using Microsoft Fabric.  
It ingests anonymized source data, transforms it through Bronze, Silver, and Gold layers, and prepares the data for reporting in Power BI.
 
## Architecture
 
```mermaid
flowchart TB
    A[Anonymized Source Data] --> B[Ingestion Layer]
    B --> C[Bronze Lakehouse]
    C --> D[Silver Transformation]
    D --> E[Gold Aggregation]
    E --> F[Power BI Dashboard]
    D --> G[GitHub Portfolio]
