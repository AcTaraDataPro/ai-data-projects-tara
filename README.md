# ai-data-projects-tara
Personal portfolio of data engineering and AI/ML projects by Tara A.C.
Welcome! This repository showcases a portfolio of real-world data engineering and AI/ML projects, designed and implemented by **Tara A.C.**, a Principal Data Engineer with 15+ years of experience across healthcare, insurance, and finance domains.

Each project is built to demonstrate:
- Data ingestion, transformation, and automation
- Cloud-native architectures (Azure, Snowflake)
- AI/ML pipelines for real-world use cases
- Compliance with healthcare standards (HIPAA, PHI)

---
## 📁 Projects

### 1. 🔍 Claims Fraud Detection
Use machine learning to detect suspicious healthcare claims based on patterns in provider behavior and claim amounts.

- Tech: `Python`, `Pandas`, `PySpark`, `Azure ML`, `Power BI`
- Concepts: Feature engineering, model training, fraud flagging
- Notebook: `01_claims_fraud_detection/notebooks/claims_fraud_detection_demo.ipynb`

### 2. 🏥 Healthcare Data Lakehouse (Medallion Architecture)
Design an end-to-end data pipeline using medallion architecture for healthcare datasets.

- Tech: `Azure Data Factory`, `Azure Synapse`, `Snowflake`, `SQL`
- Concepts: Bronze-Silver-Gold data layers, scheduling, modular design
- Pipeline Scripts: `02_healthcare_datalakehouse/synapse_pipeline/`

### 3. 🔐 PHI Masking & HIPAA Audit Trail
Build a secure ETL pipeline that masks PHI and logs access for auditing, ensuring HIPAA compliance.

- Tech: `Informatica`, `Python`, `SQL`, `Azure Blob`
- Concepts: Data masking, field-level encryption, audit logs
- Scripts: `03_phi_masking_hipaa_audit/etl_jobs/`

---

## ⚙️ Tech Stack

| Category             | Tools / Languages                            |
|----------------------|----------------------------------------------|
| **Cloud**            | Azure Synapse, ADF, Snowflake, Azure ML      |
| **ETL / Orchestration** | Informatica, Python, SQL, PySpark          |
| **ML & Analytics**   | Pandas, Scikit-learn, Power BI               |
| **Compliance**       | HIPAA, PHI Handling, Audit Logging           |
| **DevOps**           | GitHub Actions, CI/CD, Azure DevOps          |

---
