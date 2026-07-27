<h1 align="center">Hi 👋, I'm Vaishnavi Manne</h1>
<h3 align="center">Analytics Engineer | dbt · SQL · Snowflake · BigQuery · Airflow | GenAI/Text-to-SQL</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2DD4BF&center=true&vCenter=true&width=650&lines=Building+analytics-ready+data+models;dbt+%7C+Snowflake+%7C+BigQuery+%7C+Airflow;Extending+dbt+schemas+with+GenAI+Text-to-SQL;M.Eng+CS+%40+University+of+Cincinnati" alt="Typing SVG" />
</p>

---

## 👩‍💻 About Me

I notice when numbers don't add up, and I don't stop until I know why. That's what pulled me into analytics engineering — a role where accuracy isn't extra effort, it's the actual work.

- 🎓 **M.Eng. Computer Science** @ University of Cincinnati — GPA 3.8
- 🧱 I build **dimensional data models and dbt-based transformation layers** on top of cloud warehouses (Snowflake, BigQuery)
- 🤖 Currently focused on where analytics engineering meets AI — grounding **GenAI text-to-SQL** systems in dbt schemas, with guardrails
- 💼 Learned data discipline at **ADP**, validating payroll and benefits data across 50+ national accounts — where a wrong query didn't just break a report, it broke someone's paycheck
- 💬 Ask me about **dbt, data modeling, Airflow orchestration, or GenAI-in-analytics**
- 📍 Cincinnati, OH | Open to Analytics Engineer roles across the US

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

### 🔐 PinIT — Image Forensics Platform
> PostgreSQL · FastAPI · Supabase · Cloudinary · Vercel

- Designed **PostgreSQL** schemas with role-based access controls in Supabase for a multi-tenant platform
- Built **FastAPI** REST workflows capturing metadata, ownership signals, and tamper-detection results with automated validation
- Deployed an end-to-end image authentication pipeline (Cloudinary, Render, Vercel) with automated data validation

---

## 💼 Experience

**Data Engineering Intern** — Career Solutions *(Dec 2025 – Apr 2026)*
Remote, United States

**Configuration Analyst — Benefits, National Account Services** — ADP India *(Aug 2023 – Aug 2024)*
Hyderabad, India

**Data Analyst** — OM Systems and Services Private Limited *(Jan 2022 – Aug 2023)*
Hyderabad, India

---

## 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Analytics Engineering**

<p>
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
</p>

**GenAI / LLM**

<p>
  <img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-2DD4BF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Text--to--SQL-2DD4BF?style=for-the-badge" />
</p>

**Cloud & Storage**

<p>
  <img src="https://img.shields.io/badge/AWS%20S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Cloud%20Storage-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
</p>

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,sqlite" />
</p>

**Tools & Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,github,linux" />
</p>

**BI & Visualization**

<p>
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

---

<p align="center">
  <i>Always learning. Always modeling.</i>
</p>
