<h1 align="center">Hi 👋, I'm Vaishnavi Manne</h1>
<h3 align="center">Data Engineer | Azure · Databricks · PySpark · Snowflake · dbt · Airflow</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2DD4BF&center=true&vCenter=true&width=650&lines=Building+reliable+supply+chain+data+pipelines;Azure+%7C+Databricks+%7C+PySpark+%7C+Snowflake;Data+quality+%26+governance+at+scale;MS+CS+%40+University+of+Cincinnati" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaishnavimanne">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/mannevi">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:mannevaishnavi19@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## 👩‍💻 About Me

I'm a **Data Engineer with 5+ years of experience** building and optimizing supply chain data pipelines and visibility solutions. I specialize in structured data, analytics, and governance frameworks, using **Azure Data Factory, PySpark, and SQL** to improve supplier inventory management, risk mitigation, and operational decision-making across complex supply networks.

- 💼 **Data Engineer at Microsoft**, with previous experience at **Cognizant** and **Infosys**
- ☁️ Build centralized datasets and ingestion pipelines on **Azure Data Lake, Databricks, Synapse, and Data Factory**
- 🧱 Design **standardized data models** (Star Schema, 3NF, SCD) for supplier inventory and master data
- 🔍 Focus on **data governance, data quality, lineage, and reconciliation** across disparate source systems
- 📊 Deliver **Power BI and Tableau dashboards** that turn supply chain data into actionable insights
- 🎓 **Master's in Computer Science**, University of Cincinnati — **3.8/4.0 GPA**
- 🌎 Open to **Data Engineer roles** across the US; open to relocation

---

## 🛠️ Professional Skills

| Area | Skills |
| :--- | :--- |
| **Cloud & Data Platforms** | Azure Data Lake, Azure Databricks, Azure Synapse, AWS S3, AWS Redshift, Snowflake |
| **Languages & Core** | Python, PySpark, SQL (T-SQL, PL/SQL), Pandas |
| **Orchestration & ETL** | Azure Data Factory, dbt, Airflow, SSIS, Informatica |
| **Data Modeling & Governance** | Star Schema, 3NF, SCD, Data Quality, Master Data Governance, Data Lineage |
| **Visualization & Reporting** | Tableau, Power BI, Excel |

---

## 💼 Professional Experience

### Data Engineer · Microsoft
*Nov 2025 – Oct 2026 | USA*

- Developed and maintained a centralized dataset for supplier-held inventory (finished goods and raw materials) using **Azure Data Lake and Databricks**, ensuring data accuracy for supply chain risk management.
- Rationalized diverse supplier inventory sources (APIs, manual reports) with standardized **Azure Data Factory** ingestion pipelines, improving consistency and **reducing manual effort by 30%**.
- Designed and implemented data governance frameworks for supplier inventory reporting on **Azure Synapse**, establishing clear data ownership and quality rules.
- Built analytics and **Power BI dashboards** to monitor supplier inventory attainment and coverage, helping **reduce potential stock-outs by 25%** for critical components.
- Collaborated with Supply Chain and IT teams to integrate supplier data into master data structures, improving visibility into part-site mapping and country of origin for compliance and risk assessment.

### Data Engineer · Cognizant
*Oct 2022 – Jun 2024 | Hyderabad, India*

- Delivered end-to-end data solutions for a healthcare payer client, integrating diverse supplier data feeds into a unified **AWS Redshift** data warehouse.
- Designed standardized data models for supplier inventory and master data, supporting inventory optimization and **reducing reconciliation effort by 35%**.
- Partnered with client stakeholders to assess data quality and close gaps in supplier management platforms (iValua), improving governance for critical supply chain attributes.
- Developed **Python scripts and AWS Lambda functions** to automate ingestion of supplier data (APIs, EDI), enabling near real-time visibility for risk mitigation.
- Facilitated cross-functional workshops with Supply Chain and Planning teams to translate business requirements into technical specifications for supplier network mapping.

### Data Engineer · Infosys
*Mar 2020 – Sep 2022 | Pune, India*

- Developed and maintained ETL processes using **SSIS and SQL Server** for a large manufacturing client, delivering timely and accurate supply chain data.
- Optimized complex **T-SQL stored procedures** and queries, **improving load performance by 20%** and reducing reporting latency.
- Reconciled inventory data across legacy systems during a data warehouse migration, identifying a **2% discrepancy** in raw material counts and adding validation scripts before go-live.
- Provided production support, performing root cause analysis on data anomalies and implementing corrective actions to maintain data quality.

---

## 🚀 Projects

### 🏥 Healthcare Claims Analytics Pipeline + GenAI SQL Layer
> Python · dbt · BigQuery · GCS · Airflow · Docker · Gemini API · Looker Studio

- Built a **medallion-architecture pipeline** (Bronze → Silver → Gold) ingesting **58,066 real CMS Medicare inpatient claims** (197 raw columns) into a GCS bronze layer and BigQuery warehouse
- Developed **6 dbt models** across staging, intermediate, and mart layers — deduplicated **35,268 duplicate claims** and enriched records with **71,704 ICD-10 diagnosis codes**
- Authored **11 automated data quality tests** to guard the transformation layer
- Orchestrated a **6-task Airflow DAG** (`@daily`), containerized with Docker, running `dbt build` / `dbt test`
- Built a **Looker Studio dashboard** surfacing **$119.58M in Medicare spend** and top diagnosis trends
- Extended the pipeline with a **GenAI natural-language-to-SQL layer** via the Gemini API — grounding query generation in the dbt schema itself, with guardrails against destructive commands and prompt-injection attempts

🔗 [View Project](https://github.com/mannevi/healthcare-claims-pipeline)

---

### 🚕 NYC Rideshare + Weather Pipeline
> Python · PySpark · Snowflake · dbt · Airflow · AWS S3 · Docker · GitHub Actions · Tableau

- Ingestion: processed **19.8M real NYC TLC trip records** (~400MB Parquet) with **PySpark**, loaded **1.98M rows** into Snowflake via S3 external staging
- Analytics engineering layer: built **3 dbt mart models** with **5 automated data quality tests** and advanced SQL analytics (CTEs, `RANK()`, window functions)
- Orchestrated an **8-task Airflow DAG** (~8 min runtime) with quality gates and structured logging; CI/CD via **GitHub Actions**
- Built a **Tableau dashboard** visualizing weather impact and a **$2.3M peak-revenue day**

🔗 [View Project](https://github.com/mannevi/nyc-rideshare-pipeline)

---

### 🛒 E-Commerce Data Pipeline
> Python · Pandas · SQL · Apache Airflow · AWS S3

- Engineered a **5-task Airflow ETL pipeline** (~12s throughput) with deduplication, join transforms, and 5 automated data quality checks
- Advanced SQL analytics — CTEs, window functions (`ROW_NUMBER()`, `SUM() OVER`) for customer segmentation and revenue trend reporting
- Reports auto-uploaded to **AWS S3** after every run

🔗 [View Project](https://github.com/mannevi/ecommerce-etl-pipeline)

---

### 🛒 E-commerce Customer Lifetime Value & RFM Segmentation Pipeline
> dbt · Snowflake · SQL · Python · Dimensional Modeling

- Designed an analytics pipeline with staging, intermediate, fact, dimension, and analytical mart models to transform transactional data into business-ready datasets.
- Implemented SCD Type 2 customer modeling and payment transformations to calculate customer lifetime value, RFM metrics, and retention segments, identifying high-value and at-risk customers.

---

### 🔐 PinIT — Image Forensics Platform
> PostgreSQL · FastAPI · Supabase · Cloudinary · Vercel

- Designed **PostgreSQL** schemas with role-based access controls in Supabase for a multi-tenant platform
- Built **FastAPI** REST workflows capturing metadata, ownership signals, and tamper-detection results with automated validation
- Deployed an end-to-end image authentication pipeline (Cloudinary, Render, Vercel) with automated data validation

---

## 🧰 Tech Stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
</p>

**Cloud & Data Platforms**

<p>
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white" />
</p>

**Orchestration & ETL**

<p>
  <img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/SSIS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

**GenAI / LLM**

<p>
  <img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-2DD4BF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Text--to--SQL-2DD4BF?style=for-the-badge" />
</p>

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,sqlite" />
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

**Tools & Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,github,linux" />
</p>

**BI & Visualization**

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" />
</p>

---

## 📊 What I Have Built

```
✅ Medallion-architecture pipelines (Bronze → Silver → Gold) on BigQuery & Snowflake
✅ dbt models across staging, intermediate, and mart layers
✅ Dimensional data modeling — star/snowflake schema, fact & dimension tables
✅ GenAI text-to-SQL layer grounded in a dbt schema, with prompt-injection guardrails
✅ Distributed pipelines with PySpark — 19.8M+ rows
✅ Apache Airflow DAGs with scheduling, XCom, and error handling
✅ Automated data quality testing (dbt tests, custom checks)
✅ CI/CD for data pipelines via GitHub Actions
✅ BI dashboards in Looker Studio & Tableau
```

---

## 🎓 Education

### Master of Engineering in Computer Science
**University of Cincinnati** · Cincinnati, OH  
Aug 2024 – May 2026 | **GPA: 3.8/4.0**

---

## 📜 Certifications

- **Microsoft Certified: Fabric Data Engineer Associate (DP-700)**
- **dbt Fundamentals** — dbt Labs
- **AI Fluency: Framework & Foundations** — Anthropic

---

## 📫 Connect with Me

<p>
  <a href="https://linkedin.com/in/vaishnavimanne">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/mannevi">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:mannevaishnavi19@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Always learning. Always building.</i>
  <br />
  <strong>Reliable data. Clear insights. Better decisions.</strong>
</p>
