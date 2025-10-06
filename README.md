# Real-Time Weather Monitoring Pipeline using Microsoft Azure

This repository contains the documentation and interactive showcase for a fully automated, serverless ETL pipeline built with Microsoft Azure.

## Project Overview

This project demonstrates a complete ETL (Extract, Transform, Load) process. The pipeline automatically fetches live weather data from a public API, transforms the raw JSON into a structured format, and loads it into an Azure SQL Database. The entire process is orchestrated by Azure Data Factory and runs on a schedule every 3 minutes.

The file `interactive_pipeline_documentation.html` is a single-page web application that provides an interactive deep-dive into the project's architecture, implementation, and execution flow.

### Key Features
- **Automated Extraction:** A Copy Data activity fetches live weather data from the Open-Meteo API.
- **Visual Transformation:** A Data Flow in ADF cleans, enriches, and validates the data, handling data type conversions and schema adjustments.
- **Structured Loading:** The final, clean data is stored in an Azure SQL Database, ready for analytics.
- **Serverless & Scheduled:** The entire pipeline is serverless and runs automatically on a high-frequency schedule.

### Technology Stack
- **Orchestration:** Azure Data Factory
- **Staging:** Azure Blob Storage
- **Data Warehouse:** Azure SQL Database
- **Data Format:** JSON, SQL
- **Documentation:** HTML, Tailwind CSS, JavaScript

## Live Demo

You can view the interactive project showcase for this pipeline live at the following URL:
[**[Click here to view the live interactive ]**](https://shiva13016.github.io/Azure-Real-Time-Weather-Pipeline/interactive_pipeline_documentation.html)
