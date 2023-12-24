# Realtime Data Streaming and End-to-End Data Engineering Project

## Table of Contents

1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Learning Outcome](#learning-outcome)
4. [Technologies](#technologies)
5. [Getting Started](#getting-started)

---

## Introduction

Welcome to a comprehensive guide on building an end-to-end data engineering pipeline. This project takes you through the entire process, starting from data ingestion, moving through processing, and finally, storing the data. The robust technology stack includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. To ensure ease of deployment and scalability, the entire setup is containerized using Docker.

## System Architecture

### Components:

1. **Data Source:**
   - Utilizing the randomuser.me API to generate random user data for the pipeline.

2. **Apache Airflow:**
   - Orchestrating the pipeline and storing fetched data in a PostgreSQL database.

3. **Apache Kafka and Zookeeper:**
   - Streaming data from PostgreSQL to the processing engine.

4. **Control Center and Schema Registry:**
   - Aiding in monitoring and schema management of Kafka streams.

5. **Apache Spark:**
   - Employed for data processing with master and worker nodes.

6. **Cassandra:**
   - The storage solution for the processed data.

## Learning Outcome

- Setting up a data pipeline with Apache Airflow.
- Real-time data streaming using Apache Kafka.
- Distributed synchronization with Apache Zookeeper.
- Data processing techniques with Apache Spark.
- Data storage solutions with Cassandra and PostgreSQL.
- Containerizing your entire data engineering setup with Docker.

## Technologies

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yash-chauhan-dev/Realtime-Data-Streaming.git
1. **Navigate to the project directory:**
   ```bash
   cd your-repo
1. **Run Docker Compose to spin up the services:**
   ```bash
   docker-compose up