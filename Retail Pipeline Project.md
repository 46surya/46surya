# Real-Time Retail Data Pipeline on AWS

## Overview
Built an enterprise-grade retail data pipeline on AWS for a Fortune 500 client, enabling real-time insights from 30+ data sources (POS, CRM, web, app).

## Tech Stack
- AWS Glue, Lambda, S3, Kinesis, Redshift Spectrum
- Glue Crawlers, Data Catalog, IAM, CloudWatch
- Python, PySpark, Terraform

## Architecture
[Insert Diagram.png]

## Key Features
- Event-driven ingestion from multiple systems
- Automated schema discovery & partitioning
- Cost-efficient querying via Redshift Spectrum

## Business Outcomes
- Analytics latency cut from 6h → 10 min
- Enabled real-time campaign optimization → +20% ROI
- Saved $250K/year via infra re-architecture

## How to Replicate (Demo Version)
- Sample CSVs in `data/`
- Glue scripts in `glue_jobs/`
- Terraform setup in `infra/`
