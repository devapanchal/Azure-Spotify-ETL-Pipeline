# Azure Spotify ETL Pipeline

<p align="center">
End-to-End Azure Data Engineering Pipeline using Azure Data Factory, Azure Databricks, Azure Data Lake Storage Gen2, and Azure SQL Database
</p>

---

## Overview

This project demonstrates a scalable end-to-end Azure Data Engineering solution designed to process and transform Spotify datasets using modern cloud-based ETL workflows and distributed data processing techniques.

The pipeline leverages Microsoft Azure services including Azure Data Factory, Azure Databricks, Azure Data Lake Storage Gen2, and Azure SQL Database to implement automated data ingestion, transformation, storage, and analytics-ready processing following Medallion Architecture principles.

---

## Solution Architecture

### Data Flow

```text
Spotify Dataset / API
        ↓
Azure Data Factory
        ↓
Azure Data Lake Storage Gen2
        ↓
Azure Databricks (PySpark Transformations)
        ↓
Azure SQL Database
        ↓
Power BI / Analytics
```

---

## Architecture Diagram

> Add architecture diagram screenshot here

```md
![Architecture](screenshots/architecture.png)
```

---

## Key Features

- End-to-end Azure Data Engineering workflow
- Automated ETL pipeline orchestration
- Incremental data ingestion and processing
- Distributed data transformations using PySpark
- Medallion Architecture implementation (Bronze, Silver, Gold)
- Cloud-native scalable data storage
- Analytics-ready curated datasets
- Azure SQL Database integration
- Modular and scalable pipeline design

---

## Azure Services Used

| Service | Purpose |
|---|---|
| Azure Data Factory | Pipeline orchestration and workflow automation |
| Azure Databricks | Distributed data transformation using PySpark |
| Azure Data Lake Storage Gen2 | Cloud-based scalable storage |
| Azure SQL Database | Structured analytics-ready storage |
| Azure Key Vault | Secure credential management |
| Power BI | Reporting and visualization |

---

## Technologies & Tools

- Python
- PySpark
- SQL
- Azure Data Factory
- Azure Databricks
- Azure SQL Database
- Azure Data Lake Storage Gen2
- REST APIs
- ETL Pipelines
- Incremental Data Loading
- Medallion Architecture
- Git & GitHub

---

## Medallion Architecture

### Bronze Layer
Stores raw ingested data directly from source systems with minimal transformation.

### Silver Layer
Performs cleansing, normalization, transformation, and validation processes.

### Gold Layer
Contains business-ready curated datasets optimized for analytics and reporting.

---

## Project Structure

```bash
Azure-Spotify-ETL-Pipeline/
│
├── Databricks Code/
├── source_code/
├── SQL Scripts/
├── README.md
```

---

## ETL Workflow

1. Extract Spotify datasets and source files.
2. Load raw datasets into Azure Data Lake Storage Gen2.
3. Orchestrate ingestion pipelines using Azure Data Factory.
4. Transform and process datasets using PySpark in Azure Databricks.
5. Store transformed datasets across Bronze, Silver, and Gold layers.
6. Load curated datasets into Azure SQL Database.
7. Generate analytics and reporting outputs using Power BI.

---



---

## Learning Outcomes

This project provided hands-on exposure to:

- Azure Data Engineering workflows
- Cloud-native ETL pipeline design
- Incremental data processing
- Distributed data transformation using PySpark
- Azure cloud ecosystem integration
- Data Lake architecture and storage patterns
- Pipeline orchestration using Azure Data Factory
- Scalable analytics-ready data processing

---

## Author

### Dev Panchal

- GitHub: https://github.com/devapanchal
- LinkedIn: https://www.linkedin.com/in/devpanchal108/


---
