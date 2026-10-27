# ☁️ Azure Data Fundamentals (DP-900) Project

## 📖 Project Overview

This project was completed as part of the **Microsoft Azure Data Fundamentals (DP-900)** training course and demonstrates foundational knowledge of cloud computing, data storage, data processing, and analytics within the Microsoft Azure ecosystem.

The project explored how different Azure data services can be used to store, manage, process, and analyse data across relational, non-relational, and analytical workloads. Practical exercises included working with **Azure SQL Database**, **Azure Storage Accounts**, **Azure Cosmos DB**, and **Microsoft Fabric Lakehouse**, alongside data ingestion and SQL-based analysis techniques.

---

## 🎯 Project Objectives

- Understand core cloud computing concepts and Azure architecture.
- Work with relational and non-relational data services.
- Explore modern analytical workloads using Microsoft Fabric.
- Learn data ingestion and streaming techniques.
- Apply SQL querying skills to analyse business datasets.
- Understand how Azure services integrate within a modern data platform.

---

## 🛠️ Azure Services & Technologies Used

### ☁️ Cloud Computing Foundations
- Cloud Service Models (IaaS, PaaS, SaaS)
- Public, Private, and Hybrid Cloud
- Azure Resource Management
- Scalability, Availability, and Security Concepts
- Cost Management Fundamentals

### 🗄️ Relational Data
- Azure SQL Database
- Database Tables and Relationships
- Structured Data Storage
- SQL Querying & Analysis

### 📦 Non-Relational Data
- Azure Storage Account
  - Blob Storage
  - Data Lake Storage
  - File Storage
- Azure Cosmos DB
  - NoSQL Document Storage
  - JSON-based Data Structures
  - Globally Distributed Databases

### 📊 Analytics & Data Engineering
- Microsoft Fabric
- Fabric Lakehouse
- Real-Time Analytics
- Data Warehousing Concepts
- Power BI Integration

### 🔄 Data Ingestion & Streaming
- Eventstreams
- Batch Data Ingestion
- File-Based Imports
- Database Imports
- Data Integration Pipelines

---

## 🏗️ Solution Architecture

```text
Data Sources
     │
     ▼
 Eventstreams / Data Ingestion
     │
 ┌─────────────┬─────────────┐
 ▼             ▼             ▼
Azure SQL   Azure Storage   Cosmos DB
Database     Account        (NoSQL)
     │             │             │
     └──────┬──────┴──────┬──────┘
            ▼
    Microsoft Fabric
        Lakehouse
            │
            ▼
      Analytics & BI
         Power BI
```

---

## 📊 Relational Data Analysis with Azure SQL Database

Using Azure SQL Database, relational datasets were queried and analysed using industry-standard SQL techniques.

### Skills Demonstrated

✅ **SELECT Statements**

```sql
SELECT *
FROM Sales;
```

✅ **Filtering with WHERE**

```sql
SELECT *
FROM Sales
WHERE SalesAmount > 1000;
```

✅ **Sorting Results with ORDER BY**

```sql
SELECT ProductName, SalesAmount
FROM Sales
ORDER BY SalesAmount DESC;
```

✅ **Aggregations using GROUP BY**

```sql
SELECT ProductCategory,
       SUM(SalesAmount) AS TotalSales
FROM Sales
GROUP BY ProductCategory;
```

✅ **Joining Related Tables**

```sql
SELECT c.CustomerName,
       s.SalesAmount
FROM Customers c
INNER JOIN Sales s
    ON c.CustomerID = s.CustomerID;
```

### Key Learning Outcomes

- Working with structured relational data
- Writing efficient SQL queries
- Data filtering and sorting
- Aggregating business metrics
- Combining data across multiple tables
- Extracting actionable insights from sales data

---

## 📦 Non-Relational Data with Azure Storage & Cosmos DB

The project explored Azure services designed for handling large volumes of semi-structured and unstructured data.

### Azure Storage Account

Used to store:

- CSV files
- Images
- Documents
- Backup data
- Raw analytics datasets

### Azure Cosmos DB

Used to understand:

- NoSQL database concepts
- JSON document storage
- Flexible schema design
- High availability architecture
- Globally distributed applications

### Skills Demonstrated

- Creating storage resources
- Managing containers and blobs
- Understanding partitioning concepts
- Working with document-based data
- Comparing relational and non-relational database models

---

## 📈 Analytics with Microsoft Fabric Lakehouse

A key component of the project was exploring analytical workloads using **Microsoft Fabric Lakehouse**.

### Lakehouse Capabilities

- Centralised data storage
- Structured and unstructured data support
- Analytics-ready architecture
- Power BI integration
- Scalable data processing

### Fabric Skills Demonstrated

✅ Loading data into a Lakehouse

✅ Querying analytical datasets

✅ Understanding Real-Time Analytics concepts

✅ Data visualisation integration

✅ Exploring modern analytics architectures

### Benefits of the Lakehouse Approach

- Single source of truth
- Reduced data duplication
- Improved reporting performance
- Simplified data engineering workflows
- Support for both BI and advanced analytics

---

## 🔄 Data Ingestion & Event Streaming

Data ingestion methods were explored to understand how information moves from source systems into analytical environments.

### Techniques Covered

- Eventstreams
- Batch processing
- File-based ingestion
- Database imports
- Automated integration pipelines

### Eventstream Use Cases

- Retail transactions
- Website activity
- Customer interactions
- IoT device telemetry
- Real-time monitoring

### Skills Demonstrated

- Understanding streaming architectures
- Data movement and transformation
- Real-time data processing concepts
- End-to-end analytics workflows

---

## 📊 Business Insights Example

Using retail and sales datasets, SQL queries were applied to uncover business insights such as:

- Which products generate the highest revenue?
- Which product categories perform best?
- Which customers make the most purchases?
- What are the monthly sales trends?
- Where are opportunities for stock optimisation?

These exercises demonstrated how Azure data services can transform raw data into meaningful business intelligence that supports data-driven decision making.

---

## 🚀 Key Skills Developed

### ☁️ Cloud Fundamentals
- Cloud Computing Concepts
- Azure Architecture
- Service Models (IaaS, PaaS, SaaS)
- Security & Compliance Fundamentals
- High Availability & Scalability Concepts

### 🗄️ Data Storage
- Azure SQL Database
- Azure Storage Accounts
- Azure Cosmos DB
- Relational vs NoSQL Databases

### ⚙️ Data Engineering
- Data Ingestion
- Eventstreams
- Data Pipelines
- Data Integration Concepts
- Data Transformation Fundamentals

### 📈 Analytics
- Microsoft Fabric
- Lakehouse Architecture
- Real-Time Analytics
- Business Intelligence Concepts
- Power BI Integration

### 💻 SQL
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- SUM & COUNT Aggregations
- INNER JOIN
- Data Analysis Techniques

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience working across multiple Azure data services and developed a strong understanding of:

- Relational and non-relational data concepts
- Cloud-based database solutions
- Data ingestion and streaming technologies
- Analytical workloads in Microsoft Fabric
- SQL-based data exploration and reporting
- End-to-end data platform architecture within Azure

This project strengthened my foundation in modern cloud data technologies and provided hands-on experience with services commonly used within enterprise data environments.

---

## 📌 Skills Showcase

`Azure` • `DP-900` • `Azure SQL Database` • `Azure Storage Account` • `Azure Cosmos DB` • `Microsoft Fabric` • `Lakehouse` • `Eventstreams` • `Data Ingestion` • `Cloud Computing` • `Data Analytics` • `SQL` • `SELECT` • `WHERE` • `ORDER BY` • `GROUP BY` • `JOINs` • `Business Intelligence`

---

### 🎯 Project Outcome

By completing this project, I developed a strong understanding of how modern cloud-based data solutions work together, from data ingestion and storage through to transformation, analysis, and reporting. The project provided valuable hands-on experience with Microsoft's Azure data platform and strengthened my ability to work with both operational and analytical data workloads in a cloud environment.
