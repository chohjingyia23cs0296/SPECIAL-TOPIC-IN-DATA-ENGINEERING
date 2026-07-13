# Scalable Data Architecture for Traffic Safety Analytics
### Implementing a Medallion Lakehouse and Predictive AI using Apache Spark

## Project Overview

This repository contains my individual project for **SECP3843 – Special Topic in Data Engineering** at Universiti Teknologi Malaysia (UTM).

The project develops an end-to-end traffic accident analytics pipeline using **Apache Spark** and the **Medallion Data Lakehouse Architecture**. Three heterogeneous data sources are integrated, including the US Accidents dataset, the Nager.Date Public Holiday API, and the U.S. Census State Population dataset. The pipeline performs data ingestion, cleaning, transformation, feature engineering, data storage, machine learning, and business intelligence reporting.

A **Random Forest Classifier** implemented with **Apache Spark MLlib** is integrated into the pipeline to predict accident severity, while **Power BI** is used to visualize analytical insights through an interactive dashboard.

---

# Project Objectives

- Build a scalable ETL pipeline using Apache Spark.
- Integrate multiple heterogeneous data sources.
- Implement the Medallion Data Lakehouse architecture.
- Apply feature engineering for traffic accident analytics.
- Train a Random Forest model for accident severity prediction.
- Develop an interactive Power BI dashboard for visualization.

---

# Technology Stack

| Component | Technology |
|------------|------------|
| Programming Language | Python |
| Big Data Framework | Apache Spark (PySpark) |
| Data Storage | Delta Lake |
| Architecture | Medallion Data Lakehouse |
| Machine Learning | Spark MLlib Random Forest |
| Dashboard | Microsoft Power BI |
| Development Environment | Google Colab |

---

# Data Sources

| Source | Format | Purpose |
|---------|--------|---------|
| US Accidents Dataset (Kaggle) | CSV | Main accident dataset |
| Nager.Date Public Holiday API | JSON | Holiday information |
| U.S. Census Bureau Population Dataset | CSV | State population data |

---

# Data Pipeline

```
Data Sources
      │
      ▼
Bronze Layer
(Raw Data Ingestion)
      │
      ▼
Silver Layer
(Data Cleaning & Transformation)
      │
      ▼
Gold Layer
(Feature Engineering & Star Schema)
      │
      ├────────► Random Forest Model
      │
      ▼
Power BI Dashboard
```

## 💡 Key Learnings & Reflection

Working on this project taught me a lot about data engineering in a practical way. At first, I thought data work was only about coding, but I learned that understanding the data flow is just as important. I practiced collecting, cleaning, and organizing data so it can be used correctly. I also learned how small mistakes in one step can affect the whole pipeline.

Another thing I improved was problem solving. When errors happened, I had to read logs, check each process, and test again. This made me more patient and careful. I also became more confident using tools and writing clearer steps.

Overall, this project helped me connect theory with real tasks. I now understand data engineering better and feel more ready for future projects and teamwork.

---

# Appendix A — Project Timeline

| Task | Duration |
|------|----------|
| Project Instruction Review | 18 Jun |
| Dataset Identification | 18 Jun |
| Introduction | 19 Jun |
| Literature Review | 20–24 Jun |
| Proposal Submission | 23–24 Jun |
| Proposal Presentation | 24 Jun |
| Bronze Layer Development | 22–23 Jun |
| Silver Layer Development | 22–23 Jun |
| Gold Layer Development | 22–23 Jun |
| Exploratory Data Analysis | 22–23 Jun |
| Random Forest Model Training | 22–23 Jun |
| Model Evaluation | 22–23 Jun |
| Power BI Dashboard Development | 22–23 Jun |
| Methodology Writing | 25–26 Jun |
| System Design | 27–28 Jun |
| Conclusion | 28 Jun |
| Final Report Writing | 29 Jun – 6 Jul |

---

# Appendix B — Generative AI (GAI) Activity Log

| Date | Task | GAI Usage | Example Prompt |
|------|------|-----------|----------------|
| 18 Jun | Project Planning | Planned project methodology | Suggest a Spark-based data engineering methodology. |
| 18 Jun | Dataset Selection | Compared suitable datasets | Recommend datasets for traffic accident analytics. |
| 19 Jun | Literature Review | Summarised research papers | Summarise Medallion Architecture with references. |
| 20 Jun | Bronze Layer | Reviewed ingestion workflow | Explain my Spark Bronze Layer implementation. |
| 21 Jun | Silver Layer | Improved data processing explanation | Write data cleaning methodology based on PySpark code. |
| 22 Jun | Gold Layer | Explained feature engineering | Describe feature engineering activities. |
| 22 Jun | EDA | Explained analytical findings | Summarise accident analysis results. |
| 23 Jun | Machine Learning | Reviewed Random Forest implementation | Explain Random Forest using Spark MLlib. |
| 24 Jun | Power BI | Improved dashboard description | Describe Power BI dashboard academically. |
| 25 Jun | Methodology | Proofreading and rewriting | Rewrite methodology using academic English. |
| 26 Jun | UML Design | Generated PlantUML diagrams | Generate a simplified use case diagram. |
| 27 Jun | Architecture | Created architecture explanation | Draw a Medallion architecture workflow. |
| 28 Jun | Database Design | Reviewed star schema and ERD | Explain star schema design. |
| 29 Jun | Testing | Drafted Alpha Testing documentation | Write Alpha Testing section. |
| 30 Jun – 6 Jul | Final Report | Grammar checking and proofreading | Improve writing while maintaining academic style. |

---

# Appendix C — External References

| Resource | Purpose |
|----------|---------|
| Kaggle US Accidents Dataset | Primary accident dataset |
| Nager.Date Public Holiday API | Holiday information |
| U.S. Census Bureau | State population dataset |
| Apache Spark Documentation | Spark implementation reference |
| Apache Spark MLlib Documentation | Machine learning reference |
| Delta Lake Documentation | Data Lakehouse reference |
| Microsoft Power BI | Dashboard development |

---

# Author

**Jing Yi Choh**

Faculty of Computing  
Universiti Teknologi Malaysia (UTM)

Course: **SECP3843 – Special Topic in Data Engineering**
