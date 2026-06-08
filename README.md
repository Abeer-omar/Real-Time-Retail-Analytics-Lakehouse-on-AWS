# Real-Time Retail Analytics Lakehouse on AWS

## Overview

A cloud-native end-to-end Data Engineering project that processes retail transactions in real time using Kafka, Spark Structured Streaming, and AWS.

The platform implements a Medallion (Bronze / Silver / Gold) Lakehouse architecture to ingest, transform, validate, and aggregate retail transaction data for business analytics and reporting.

## Architecture

Kafka → Spark Structured Streaming → S3 Bronze → Data Quality Layer → S3 Silver → Business Aggregations → S3 Gold → Athena → Power BI

## Features

* Real-time transaction ingestion using Apache Kafka
* Spark Structured Streaming processing
* Bronze, Silver, and Gold Lakehouse architecture
* Data quality validation framework
* Customer spending analytics
* Merchant performance analytics
* Geospatial transaction distance analysis
* Athena querying layer
* Power BI dashboards
* Airflow orchestration

## Technology Stack

* AWS EC2
* AWS S3
* AWS Athena
* Apache Kafka
* Apache Spark
* Apache Airflow
* Python
* Power BI

## Project Structure

```text
kafka/
spark/
airflow/
athena/
data_quality/
powerbi/
infrastructure/
```

## Dataset

Synthetic retail transaction data containing customer, merchant, geographic, and transaction attributes.

## Status

Project in development.
