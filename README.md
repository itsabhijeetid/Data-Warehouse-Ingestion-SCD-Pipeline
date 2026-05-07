# 🏗️ Data Warehouse Ingestion & SCD Pipeline

An end-to-end Data Engineering project built using Microsoft Fabric to design scalable, fault-tolerant, and incremental data ingestion pipelines with Slowly Changing Dimension (SCD) Type 1 and Type 2 implementations.

## 📌 Project Overview

This project demonstrates the design and implementation of a modern Data Warehouse ingestion architecture using Microsoft Fabric with Azure Data Lake Storage Gen2 (ADLS Gen2) as the source layer.

The pipeline handles:
- scalable data ingestion
- incremental loading
- Slowly Changing Dimensions (SCD)
- fault-tolerant workflows
- idempotent processing
- analytical warehouse integration

The architecture integrates:
- ADLS Gen2
- Microsoft Fabric Pipelines
- Fabric Notebooks
- OneLake
- Lakehouse
- Data Warehouse

to create a production-style Data Engineering workflow. Microsoft OneLake itself is built on top of ADLS Gen2 and integrates natively with Fabric workloads. 

## 🚀 Key Features

- ⚡ End-to-end ingestion pipeline design
- 🔄 Incremental data loading strategy
- 🧠 SCD Type 1 & Type 2 implementation
- 🛡️ Fault-tolerant ingestion workflows
- 🚫 Duplicate data prevention
- 📂 Idempotent file processing
- 🏗️ Lakehouse + Warehouse architecture
- ☁️ ADLS Gen2 integration with Microsoft Fabric
- 📊 Analytics-ready warehouse design

## 🛠️ Technologies Used

- Microsoft Fabric
- Fabric Pipelines
- Fabric Notebooks
- OneLake
- Lakehouse
- Data Warehouse
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- SQL
- PySpark

## 🏛️ Architecture Overview

```bash
ADLS Gen2 (Source Layer)
            │
            ▼
     Fabric Pipeline
            │
            ▼
    Fabric Notebooks
            │
            ▼
          OneLake
            │
     ┌──────┴──────┐
     │             │
     ▼             ▼
 Lakehouse     Data Warehouse
     │             │
     └──────┬──────┘
            ▼
   Reporting & Analytics
