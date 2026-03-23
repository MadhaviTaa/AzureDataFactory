# 🚀 Azure Data Factory ETL Project

## 📌 Overview
This project demonstrates the implementation of a scalable ETL (Extract, Transform, Load) pipeline using Azure Data Factory (ADF). The pipeline processes CSV files stored in Azure Storage, performs multiple transformations using Data Flow, and loads the cleaned data into an Azure SQL Database.

---

## 🏗️ Architecture
- Source: CSV files in Azure Storage Account  
- Processing: Azure Data Factory (Pipelines + Data Flow)  
- Destination: Azure SQL Database  

---

## ⚙️ Technologies Used
- Azure Data Factory  
- Azure Storage Account  
- Azure SQL Database  
- Data Flow Transformations  
- Git Integration  

---

## 🔄 Pipeline Workflow

### Data Ingestion
- Used Copy Activity to load CSV data from Azure Storage.

### Metadata Handling
- Used Get Metadata Activity to dynamically fetch file details.

### Iteration Logic
- Implemented ForEach Activity to process multiple files.

### Conditional Processing
- Used If Condition Activity to filter and process selected files.

---

## 🔧 Data Transformations (ADF Data Flow)

### Column-Level
- Select (rename, reorder columns)
- Derived Column (create new columns)

### Row-Level
- Filter
- Conditional Split

### Data Structuring
- Sort
- Aggregate (SUM, COUNT, AVG)

### Data Integration
- Join
- Lookup
- Union

### Data Cleaning
- Coalesce (null handling)
- Surrogate Key
- Flatten
- Column Patterns

### Optimization
- Removed redundant data
- Applied collation
- Used schema drift
- Debug mode testing

---

## 📂 Pipelines Implemented
- onlySelected_files  
- prodPipeline  
- pipeline_git  
- pipelineManager  
- VarPipeline  

---

## 🗄️ Database Setup
- Created Azure SQL Server and Database  
- Loaded transformed data  

---

## 📸 Screenshots
<img width="940" height="533" alt="image" src="https://github.com/user-attachments/assets/e44f5ebd-30fd-4af3-b8d0-f79d06b56783" />

<img width="940" height="531" alt="image" src="https://github.com/user-attachments/assets/3dfca6ba-cb6c-406d-aeef-e6392d3be3fb" />

<img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/aa917b5d-6da1-4ca6-ad18-55826c3126bd" />

<img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/4d4c095a-9a29-4f29-8040-aae60af15a15" />

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/80673b3c-9976-472c-9dfa-83a0731f6f88" />

<img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/c7ab9f41-a64a-4ad2-b8de-86e7cbb37a6c" />

<img width="940" height="539" alt="image" src="https://github.com/user-attachments/assets/4b2e99f2-0896-4a97-8452-1a1aa198dcc4" />

<img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/1b8cdae8-097d-4e92-abaf-e084b3ea5375" />








---

## 📊 Key Learnings
- Built ETL pipelines using Azure Data Factory  
- Implemented dynamic workflows  
- Performed data transformations  
- Learned data cleaning techniques  
- Used Git integration  

---

## 🚀 Future Enhancements
- Real-time processing  
- Monitoring & alerting  
- Performance optimization  
- Power BI integration  

---

## 📁 Setup Instructions
1. Clone the repository  
2. Import pipelines in Azure Data Factory  
3. Configure services  
4. Run pipelines  

---

## 🙌 Author
Madhavi Prabhakar Thakare

---

## ⭐ Support
Give this repo a ⭐ if you like it!
