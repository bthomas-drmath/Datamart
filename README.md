# 📊 DataMart: Unified Data Warehouse with GenAI Interface
 
## 🚀 Overview
 
**DataMart** is a modern, centralized data warehouse integrating legacy iSeries data with Microsoft Dynamics F&O to provide a 360-degree view of our outbound, return, and POS transactions. It powers insights through **Power BI dashboards** and includes a **Generative AI assistant** to translate natural language queries into actionable SQL.
 
This portfolio version presents a simplified mock-up of the actual implementation for educational and demonstration purposes.
 
---
 
## 🛠️ Tech Stack
 
- **Azure Data Factory** – Data ingestion pipelines  

- **Databricks** – ETL & transformation logic  

- **SQL & Delta Lake** – Curated tables for reporting  

- **Power BI** – Interactive dashboards and KPIs  

- **OpenAI / LangChain** – Natural language to SQL assistant  

- **iSeries / Legacy Data** – Extracted and unified with modern ERP data  
 
---
 
## 🗂️ Project Structure
 
| Folder         | Description |

|----------------|-------------|

| `/sql`         | Example SQL views and curated layer logic |

| `/src`         | Scripts for AI assistant / backend APIs |

| `/data`        | Sample datasets (mocked) |

| `/images`      | Power BI screenshots, architecture diagrams |

| `/docs`        | High-level design, metadata mapping, user flows |
 
---
 
## 🧠 Key Features
 
### 📦 Unified Data Model

Combines legacy iSeries + F&O datasets to serve:

- Sales

- Returns

- Inventory

- POS transaction history
 
### 📊 Power BI Reporting

- Real-time dashboards with drill-through

- Security via RLS (Row Level Security)

- Business metrics aligned across teams
 
### 🤖 Generative AI Assistant

- Ask questions like _“Show me return rates by category last quarter”_

- Returns either SQL code or direct result

- Accelerates self-service analytics and removes SQL barriers
 
---
 
 
## 🛠️ How It Works (Simplified Flow)
 
1. **Data Ingestion:** ADF loads legacy + ERP data to Bronze tables

2. **ETL in Databricks:** Transform to curated views (Silver/Gold layers)

3. **AI Assistant:** Natural language → SQL using LangChain + OpenAI

4. **Power BI:** Visualizes unified datasets for decision-making
 
---
 
## ⚙️ How to Run (Example)
 
```bash

# Clone repo

git clone https://github.com/yourusername/datamart-portfolio.git

cd datamart-portfolio
 
 
