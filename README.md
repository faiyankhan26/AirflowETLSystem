# AirflowETLSystem

**AirflowETLSystem** is a fully automated ETL pipeline built with **Apache Airflow** that extracts weather data from APIs, transforms it for analytics, and loads it into a **PostgreSQL** database. This project demonstrates real-world ETL workflows, task orchestration, and pipeline monitoring.

---

## 🔹 Key Features

- **Automated ETL:** Periodically fetches weather data from APIs.  
- **Data Transformation:** Cleans, formats, and prepares data for analysis.  
- **Database Integration:** Stores processed data in PostgreSQL for querying.  
- **Pipeline Monitoring:** Airflow DAGs provide logs, retry mechanisms, and task status.  
- **Dockerized Environment:** Easy setup with Docker for Airflow and PostgreSQL.

---

## 🔹 Tech Stack

- **Python** – Core programming and data processing  
- **Apache Airflow** – Workflow orchestration  
- **PostgreSQL** – Data storage  
- **Pandas & SQLAlchemy** – Data transformation  
- **Docker** – Containerized deployment  
- **HTTP Requests** – Fetching data from APIs  

---

## 🔹 Project Structure

```bash
AirflowETLSystem/
├── dags/                   # Airflow DAG definitions
│   └── etlweather.py       # Main ETL DAG
├── plugins/                # Custom operators/hooks (if any)
├── docker/                 # Docker setup for Airflow & PostgreSQL
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
