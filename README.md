# Hi, I'm Marcos 👋

### Junior Data Engineer · Python · SQL · Generative AI

Multiplatform developer (DAM) currently doing a **Master's in Big Data, Applied AI and Generative AI at U-tad**. I build end-to-end data and AI projects, from streaming ingestion and lakehouses to explainable ML and RAG, always with automated tests, CI and a live demo, on top of a full-stack background with Java/Spring Boot and Angular.

📍 Madrid, Spain · 🇬🇧 English C2 (LanguageCert) · 🇪🇸 Native Spanish  
🟢 **Available immediately for an internship or a junior role, full-time.**

🌐 **Portfolio:** [mmartinezvaras.github.io](https://mmartinezvaras.github.io/inicio/) · 📄 CV in the portfolio

---

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[Card fraud detection on a lakehouse](https://github.com/mmartinezvaras/banking-lakehouse-pyspark)** · [▶ live demo](https://fraude-lakehouse-marcos.streamlit.app/) | Bronze → Silver → Gold pipeline over 50,109 bank transactions, with a quarantine for bad rows, incremental `MERGE` and time travel. Fraud rules built with window functions catch **13 of 13 attacks and stop 99.9% of the stolen money**, versus 4 of 13 for a naive rule. Tested on real Spark in CI. | PySpark · Delta Lake · Streamlit · pytest · GitHub Actions |
| **[Explainable credit scoring](https://github.com/mmartinezvaras/credit-scoring)** · [▶ live demo](https://scoring-credito-marcos.streamlit.app/) | Probability of default for 30,000 customers: monotonic LightGBM (Gini 0.546 vs 0.478 for logistic regression), explained with SHAP, calibrated and banded A–E. Reviewing 47% of customers would avoid **77% of defaults**. | Python · LightGBM · SHAP · scikit-learn · Streamlit |
| **[RAG assistant for the Spanish Workers' Statute](https://github.com/mmartinezvaras/Python-RAG-AI-para-los-PDFs)** · [▶ live demo](https://estatuto-rag.streamlit.app/) | Hybrid search (vectors + BM25) that cites the article and page, and refuses questions the law does not cover. Evaluated in CI on 35 questions: **right article 87%** of the time, correct answer 77%. Runs locally on Ollama or online on Gemini. | LangChain · ChromaDB · BM25 · Ollama · Gemini · Streamlit · pytest |
| **[Real-time card payments](https://github.com/mmartinezvaras/bigdata-pagos-tarjeta)** | Simulator → Kafka → HDFS → Hive with at-least-once delivery and a quarantine per rule. **0 payments lost out of 102,000 messages**, even when the consumer is killed; every result is checked against expected values. | Kafka · Hadoop HDFS · Hive · Parquet · Docker Compose |
| **[LaLiga match prediction](https://github.com/mmartinezvaras/laliga-match-prediction)** | Random Forest with a time-based split and leakage-free recent-form features: 51.5% win-prediction precision vs a 38% base rate. | Python · pandas · scikit-learn · Jupyter |

More: [resale management dashboard](https://github.com/mmartinezvaras/consolaAdminProductos) (Spring Boot API with 64 endpoints) · [NoSQL banking database](https://github.com/mmartinezvaras/nosql-financial-engine) · [face-recognition attendance](https://github.com/mmartinezvaras/Reconocimiento_Facial) · [restaurant ordering app, final DAM project](https://github.com/mmartinezvaras/TFGangular) · [machine learning coursework](https://github.com/mmartinezvaras/s_aprendizaje)

---

## 💼 Experience

**Minsait (Indra Group)** · Development intern · Mar – Jun 2026 (4 months)
- Front-end development with **Angular, Tailwind CSS and JavaScript** in a professional development team.
- Back-end tasks with **Java and Spring Boot**.

## 🎓 Education

- **Master's in Big Data, Applied AI & Generative AI** · U-tad · 2026 – 2027 (in progress)
- **Higher Technician in Multiplatform Application Development (DAM)** · IES Gonzalo Chacón · 2024 – 2026

---

## 🛠️ Tech stack

**Data**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Big Data**  
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Hadoop HDFS](https://img.shields.io/badge/Hadoop_HDFS-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Apache Hive](https://img.shields.io/badge/Apache_Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)

**Generative AI & ML**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Development**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Quality & DevOps**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)

---

## 📚 Currently learning

- **Apache Airflow** for orchestration and **dbt** for SQL data modelling
- **Azure data fundamentals (DP-900)**
- **COBOL and z/OS mainframe basics** (IBM Z Xplore), to connect legacy systems with modern data platforms

## 🏅 Certifications

- **Python Essentials 1** and **Python Essentials 2** · Cisco Networking Academy & OpenEDG Python Institute · Oct 2026 · [verify](https://www.credly.com/badges/d5f2e3d3-7c41-4ec8-8fdd-0be91d3ac1a8/public_url) · [verify](https://www.credly.com/badges/50a0a413-61d9-47c9-be51-33c1361e98e5/public_url)
- **Data Science Essentials with Python** · Cisco · Oct 2026 · [verify](https://www.credly.com/badges/3eb09829-dfb1-4eed-ada0-a2b9ffe9e77b/public_url)
- **English C2** · LanguageCert

*Next: Databricks Fundamentals · Microsoft Azure Data Fundamentals (DP-900) · IBM Z Xplore*

---

## 📫 Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://mmartinezvaras.github.io/inicio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-mar%C3%ADa-mart%C3%ADnez-varas-b5156b3a3/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mmartinezvaras@icloud.com)
