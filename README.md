# 👋 Hi, I'm Prashantha D

## 🚀 About Me

I'm **Prashantha D**, a **Bachelor of Engineering student in Information Science & Engineering** at **Sri Sairam College of Engineering, Bengaluru** (CGPA: **7.8/10**, 2022–2026).

I'm a passionate and results-driven aspiring software engineer who enjoys building **scalable, secure, and high-performance applications** using modern backend technologies, cloud platforms, data engineering pipelines, and AI-powered solutions.

I'm particularly interested in:

- 🏗️ Data Engineering & Lakehouse Architecture
- ⚙️ ETL/ELT Pipeline Development
- ☁️ Cloud Computing & Deployment
- 🤖 Artificial Intelligence & GenAI
- 🔒 Cybersecurity
- 📊 Data Analytics & Visualization
- 🧩 Backend Development & System Design

📍 Bengaluru, India
📧 **Email:** [dpsomasamudra@gmail.com](mailto:dpsomasamudra@gmail.com)
🔗 **GitHub:** [github.com/dpsomasamudra](https://github.com/dpsomasamudra)
🔗 **LinkedIn:** [linkedin.com/in/prashantha-d6366](https://linkedin.com/in/prashantha-d6366)

---

# 🛠️ Technical Skills

## 💻 Programming Languages
- Python
- Java
- JavaScript
- C
- SQL

---

## 🏗️ Data Engineering *(Core Expertise)*

### ⚙️ ETL / ELT & Pipeline Development
- Apache Spark / PySpark
- Apache Kafka (streaming ingestion)
- Apache Airflow (workflow orchestration)
- dbt (data build tool — transformations & testing)
- Medallion Architecture (Bronze → Silver → Gold)
- Batch & Incremental Data Loading
- Watermark-based Change Data Capture (CDC)
- MERGE / Upsert patterns

### 🏛️ Lakehouse & Data Warehouse
- Delta Lake (ACID transactions, time travel, schema evolution)
- Azure Databricks
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- Azure Data Factory (ADF)
- Star Schema & Dimensional Modeling
- Slowly Changing Dimensions (SCD Type 1 & Type 2)
- Z-Ordering & query optimization

### 🔍 Data Quality & Governance
- Schema Validation & Enforcement
- Duplicate Detection (MD5 / SHA256 hashing)
- Data Reconciliation (row counts, checksums)
- Great Expectations (data quality framework)
- Data Lineage & Audit Logging
- Unity Catalog (Azure Databricks governance)
- PII masking & column-level encryption

### 📦 Data Formats & Storage
- Parquet
- Delta
- JSON / CSV / Avro
- ADLS Gen2 / Blob Storage
- Partitioning & bucketing strategies

### 📊 Analytics & BI
- SQL (advanced — window functions, CTEs, subqueries)
- Pandas / NumPy
- Plotly / Matplotlib / Seaborn
- Power BI (integration-ready pipelines)

---

## 🤖 AI / Generative AI
- Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- NLP
- GPT Integration
- Agentic AI
- LangChain
- CrewAI
- MCP Development
- Ollama
- Hugging Face Transformers
- Vector Databases
- Embeddings
- AI Workflow Automation

## 🧠 Machine Learning / Deep Learning
- Scikit-learn
- XGBoost
- PyTorch
- Predictive Modeling
- Feature Engineering
- Data Preprocessing
- Model Optimization
- Supervised Learning

## 🌐 Backend & APIs
- FastAPI
- Flask
- Django
- REST APIs
- Spring Boot
- Microservices
- JWT Authentication

## 🎨 Frontend
- HTML
- CSS
- JavaScript
- React

## 🗄️ Databases
- MySQL
- Firebase
- Delta Lake

## ☁️ Cloud & DevOps
- Microsoft Azure (ADF, Databricks, ADLS Gen2, Azure Monitor)
- AWS
- Docker
- GitHub Actions
- CI/CD Pipelines

## 🛠️ Tools & Platforms
- Git / GitHub
- Docker
- Pinecone
- n8n
- Postman
- VS Code
- Linux
- Replit / Cursor
- Apache Airflow
- dbt

---

# 💼 Experience

## 🚀 Intern – Dyashin Technosoft Pvt Ltd
📅 June 2025

- Worked on real-world datasets using **Python** and **Data Analytics**
- Performed data preprocessing, analysis, and visualization tasks
- Improved analytical thinking and practical problem-solving skills
- Collaborated on industry-oriented case studies and technical tasks
- Gained exposure to professional software development workflows

---

# 🔥 Projects

---

## 🏗️ Azure Lakehouse Migration Platform *(Data Engineering)*
*PySpark · Azure Databricks · Azure Data Factory · ADLS Gen2 · Delta Lake · SQL*

An enterprise-grade **Medallion Architecture** data lakehouse built to migrate and process large-scale organizational data with full pipeline automation, data quality enforcement, and real-time orchestration.

- Developed scalable **ETL pipelines using PySpark and SQL** to ingest enterprise data into **Bronze, Silver, and Gold layers**, following the Medallion Architecture pattern
- Implemented a **data quality framework** including schema validation, duplicate detection via composite key hashing, and row-count reconciliation between layers
- Built **Azure Data Factory** workflows for full orchestration: scheduling, dependency chaining, retry logic, and SLA monitoring across pipeline stages
- Utilized **Delta Lake** features including ACID transactions, time travel for version rollback, schema evolution, and incremental MERGE-based upserts
- Designed **SCD Type 2** handling for historical tracking and dimensional modeling for Gold layer business marts
- Added **audit logging** and pipeline observability: rows processed, run duration, failure alerting via webhook

**Tech Stack:** `PySpark` `Azure Databricks` `Azure Data Factory` `ADLS Gen2` `Delta Lake` `SQL` `Python`

---

## 📡 Real-Time Telecom Data Lakehouse Platform *(Data Engineering)*
*Kafka · Spark Structured Streaming · Delta Lake · Azure · SQL*

A **real-time streaming data platform** built for telecom data ingestion, processing, and analytics at scale, handling millions of CDR (Call Detail Records) per day.

- Designed and implemented **Kafka-based streaming ingestion** for high-throughput telecom event data (CDRs, network events, subscriber activity)
- Built **Spark Structured Streaming** pipelines with watermarking and windowing for late-arriving data handling
- Stored processed streams in **Delta Lake** with ACID guarantees, enabling both real-time queries and batch analytics
- Implemented **data quality checks** and anomaly detection on streaming data (null rates, schema drift, duplicate events)
- Built Gold layer **aggregation tables** for churn prediction, network KPI monitoring, and revenue analytics
- Deployed on **Azure Databricks** with auto-scaling cluster configurations and cost monitoring

**Tech Stack:** `Apache Kafka` `Spark Structured Streaming` `Delta Lake` `Azure Databricks` `ADLS Gen2` `SQL` `Python`

---

## 📊 AI-Powered Financial Analysis & Predictor Dashboard

- Developed a **Flask-based web application** for stock market analysis and prediction
- Integrated **Yahoo Finance API** for real-time stock data
- Implemented sentiment analysis using **VADER** and **NewsAPI**
- Added technical indicators: SMA, RSI, MACD
- Calculated financial risk metrics: Sharpe Ratio, Beta, Value at Risk (VaR)
- Built interactive candlestick charts with buy/sell signals using **Plotly**
- Developed a **5-day stock price prediction model** using Linear Regression

**Tech Stack:** `Python` `Flask` `Plotly` `Yahoo Finance API` `Machine Learning`

---

## 🏥 Patient Management System (Microservices Architecture)

- Designed and developed a scalable **patient management platform** using **Spring Boot microservices**
- Implemented secure **RESTful APIs**, **JWT authentication**, and role-based access control
- Integrated **MySQL** for secure and optimized database handling
- Deployed services on **AWS** for scalability and high availability
- Added centralized logging and robust error handling mechanisms

**Tech Stack:** `Java` `Spring Boot` `REST APIs` `JWT` `MySQL` `AWS`

---

## 🔐 Honeypot Security System

- Built a **Python-based honeypot system** to detect unauthorized access attempts
- Captured attacker information: IP addresses, ports, payloads
- Logged suspicious activities for attack pattern analysis
- Simulated vulnerable services to identify intrusion attempts

**Tech Stack:** `Python` `Network Security` `Socket Programming`

---

## 🔭 Image Acquisition Control Panel – ISRO LEOS

- Developed a **PyQt5-based desktop application** for controlling satellite camera operations
- Implemented configurable gain, integration time, telemetry monitoring, and file management
- Built dual-mode image capture pipelines: Simulation Mode & Real Hardware Execution
- Designed an efficient operational interface for aerospace image acquisition systems

**Tech Stack:** `Python` `PyQt5` `Shell Scripting`

---

## 🚓 AI-Based Crime Pattern Prediction

- Developed an ML-powered crime prediction system using **Bengaluru crime datasets**
- Performed preprocessing, feature engineering, and predictive modeling using **XGBoost**
- Achieved **87% prediction accuracy** through optimized machine learning workflows
- Built scalable **FastAPI inference APIs** for real-time prediction and analytics integration

**Tech Stack:** `Python` `XGBoost` `FastAPI` `Machine Learning`

---

## 🐛 Smart Sericulture Management System

- Developed an AI-powered agriculture monitoring system for silkworm environment management
- Implemented real-time monitoring for temperature and humidity conditions
- Built intelligent advisory workflows using **Firebase** backend integration
- Added AI-assisted recommendations for improving silkworm health and productivity

**Tech Stack:** `Python` `GenAI` `Firebase` `FastAPI`

---

# 🏆 Certifications

- ☁️ Microsoft Azure Fundamentals (AZ-900)
- 🔐 Google Cybersecurity Certificate
- 🎨 Meta Front-End Developer Certificate
- ⚙️ Meta Back-End Developer Certificate
- 🗄️ Meta Database Engineer Certificate
- 🤖 Anthropic Claude 101
- 💻 Claude Code in Action
- 🔗 Build with Claude API
- 🧩 Introduction to MCP

---

# 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dpsomasamudra&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dpsomasamudra&layout=compact&theme=tokyonight)

---

# 🌱 Currently Learning

- ⚙️ Advanced Data Engineering (dbt, Apache Iceberg, Flink)
- 🏗️ Real-Time Streaming Architectures (Kafka + Spark)
- 🤖 Generative AI Applications & Agentic Workflows
- ☁️ Cloud Deployment & DevOps (Azure, AWS)
- 🧩 System Design & Scalability Patterns

---

# 🤝 Let's Connect

I'm actively learning, building, and preparing for opportunities in:

- 🏗️ **Data Engineering** (Pipelines, Lakehouses, ETL/ELT)
- ⚙️ **Backend Development**
- ☁️ **Cloud Computing**
- 🤖 **AI-Powered Applications**

If you'd like to collaborate, discuss technology, or explore opportunities — feel free to connect!

⭐ **Thanks for visiting my profile!**
