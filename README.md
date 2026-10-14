# Kubernetes Practical Labs

Hands-on labs exploring container orchestration, configuration management, batch processing, and data streaming.

## Labs

### Lab 01 — ConfigMaps and Secrets
**Topics:** Kubernetes configuration, environment variables, mounted configuration files, and secret management.

- Store application configuration using ConfigMaps.
- Manage sensitive configuration using Kubernetes Secrets.
- Inject configuration into pods through environment variables and mounted files.

*Status: Lab results documented; files to be added.*

### Lab 02 — Jobs and CronJobs
**Topics:** Kubernetes batch workloads, retries, deadlines, parallel execution, and scheduled tasks.

- Run one-off tasks using Jobs.
- Configure retries and execution deadlines.
- Execute parallel batch workloads.
- Schedule recurring tasks with CronJobs.
- Suspend and resume scheduled workloads.

**Technologies:** Kubernetes, YAML.

### Lab 03 — Kafka and Spark
**Topics:** Event streaming, distributed data processing, and containerized data engineering environments.

- Run Kafka and PySpark services with Docker Compose.
- Explore Kafka producer code.
- Work with PySpark notebooks for stream processing.
- Configure services, ports, volumes, and networking.

**Technologies:** Apache Kafka, Apache Spark, PySpark, Docker Compose, Python, Jupyter Notebook.

## Repository Structure

```text
kubernetes-practical-labs/
├── 01-configmaps-secrets/
├── 02-jobs-cronjobs/
├── 03-kafka-spark/
└── README.md
```

## Goals

- Practice container and workload orchestration.
- Understand configuration and secret management.
- Explore batch processing and scheduled jobs.
- Learn the fundamentals of streaming data pipelines.
- Document practical exercises and technical results.

## Notes

This repository is a learning portfolio. Review configuration files before running them, and never commit passwords, API keys, tokens, or other sensitive credentials.