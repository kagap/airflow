# 🔧 Data Engineering Starter Pack

9 interactive Jupyter Notebook modules covering data engineering fundamentals: orchestration with **Apache Airflow**, transformation with **dbt**, data warehouse modeling, and streaming with **Kafka** and **Spark Structured Streaming**. Written in **Polish**. The fifth course in the series, following [python-starter-pack](https://github.com/kagap/python-starter-pack) → [sql-](https://github.com/kagap/sql-) → [statistic](https://github.com/kagap/statistic) → [pyspark](https://github.com/kagap/pyspark). Each notebook is built with a clean layout and locked theory cells to keep the focus entirely on coding practice.

## 📌 What's Inside

| # | Notebook | Topic |
|---|----------|-------|
| 1 | `DE_Modul1_Wprowadzenie.ipynb` | Introduction to Data Engineering |
| 2 | `DE_Modul2_Airflow_Podstawy.ipynb` | Apache Airflow — basics |
| 3 | `DE_Modul3_Airflow_Zaawansowany.ipynb` | Apache Airflow — advanced patterns |
| 4 | `DE_Modul4_dbt_Podstawy.ipynb` | dbt — basics |
| 5 | `DE_Modul5_dbt_Zaawansowany.ipynb` | dbt — tests, documentation & advanced patterns |
| 6 | `DE_Modul6_Modelowanie_Danych.ipynb` | Data modeling & data warehouse architecture |
| 7 | `DE_Modul7_SCD.ipynb` | Slowly Changing Dimensions (SCD) |
| 8 | `DE_Modul8_Streaming_Kafka.ipynb` | Streaming fundamentals & Apache Kafka |
| 9 | `DE_Modul9_Spark_Structured_Streaming.ipynb` | Spark Structured Streaming |

* **Core Theory & Examples:** Clear explanations paired with runnable Airflow DAGs, dbt models, and PySpark code for each topic.
* **Interactive Exercises:** Hands-on tasks with expandable spoiler solutions.
* **Protected Content:** Theory and description cells are configured as non-editable (`"editable": false`, `"deletable": false`) to prevent accidental changes while working through the material.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/kagap/airflow.git
   ```
2. Install the core Python dependencies:
   ```bash
   pip install jupyter pandas numpy duckdb dbt-duckdb
   ```
3. Apache Airflow needs its own constraints-pinned install — follow the [official installation guide](https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html) for Modules 2–3.
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Work through the modules in order — later ones (dbt, SCD) build on the warehouse schema set up in earlier modules.
