Azure Cloud Computing & Data Analytics Project

Project Overview

This project demonstrates an end-to-end cloud computing and data analytics solution built using Microsoft Azure services and Power BI. The objective was to design, deploy, and integrate cloud infrastructure, IoT data ingestion, database management, and business intelligence reporting into a unified cloud-based architecture.

The project uses the AdventureWorksLT dataset to simulate real-world business scenarios and implements IoT sensor data simulation to demonstrate real-time data ingestion and storage in Azure.

 Architecture Components
1. Azure Virtual Machine (Ubuntu)

Deployed and configured Ubuntu VM

Enabled remote access via RDP

Verified system provisioning and secure authentication

2️. Azure Storage & Blob Services

Created Storage Account (StorageV2)

Configured Blob containers

Enabled public blob access

Implemented Static Website Hosting

Configured Lifecycle Management Policy (Move blobs to Cool tier after 100 days)

3️. Azure IoT Hub Integration

Created IoT Hub instance

Registered IoT device (Raspberry Pi simulator)

Simulated temperature & humidity telemetry

Configured message routing from IoT Hub to Blob Storage

Verified .avro telemetry file storage

4️. Azure SQL Database

Deployed Azure SQL Database

Executed SQL queries (AdventureWorksLT dataset)

Validated database connectivity and data retrieval

5️. Power BI Integration

Connected Azure SQL Database to Power BI

Created DAX measure:

Total Sales Amount = SUM(SalesLT_SalesOrderDetail[LineTotal])

Built interactive dashboards:

Total Sales Overview

Sales by Product

Sales by Year

Product Distribution

Order Analytics


Technologies Used

Microsoft Azure (VM, Storage, IoT Hub, SQL Database)

Azure Monitor & Message Routing

SQL (AdventureWorksLT)

Power BI (DAX & Dashboarding)

Raspberry Pi IoT Simulator


 Key Outcomes

Designed and deployed scalable cloud infrastructure

Implemented real-time IoT telemetry ingestion

Built automated cloud data storage pipelines

Performed SQL-based data validation

Developed interactive business intelligence dashboards

Demonstrated practical application of cloud analytics for data-driven decision-making


Project Significance

This project showcases hands-on experience in:

Cloud Infrastructure Deployment

IoT Data Engineering

Database Management

Business Intelligence & Data Visualization

End-to-End Cloud Data Pipeline Design

It reflects practical understanding of how modern cloud ecosystems integrate infrastructure, data ingestion, storage, analytics, and visualization to support enterprise-level decision-making.
