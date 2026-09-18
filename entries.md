# 2026-08-18
- Finished the EIA STEO analysis project: refactored the pipeline into functions (extract, clean, reshape, compute_metrics, compute_correlation, generate_graph, export_results)
- Started this learning log
- Start dbt Fundamentals (dbt Studio)

# 2026-08-19
- dbt and SnowFlake set up, working on dbt models

# 2026-08-20
- learn dbt concepts on models, modularity, the ref Macro, naming conventions (src, stg, int, fct, dim), and dbt cmds

# 2026-08-21
- learn dbt Understanding Sources and Data Testing (unique, not_null, accepted_values, relationships)

# 2026-08-22
- learn dbt Generic and Singular tests, use dbt AI for data test generation
- test sources for data integrity, test models for transformation integrity
- Finish documentation and deployment sections
- Finished dbt Fundamentals (dbt Studio) course

# 2026-08-23
- start data engineering market analysis project to build in dbt and gain insight

# 2026-09-07
- finish de-market-analysis project, push to github
- learn AWS Core Services: basics of AWS IAM, S3, and VPC

# 2026-09-09
- setting up AWS Redshift, learning about setting policies through root user / IAM user
- migrated de-market-analysis to AWS: S3, IAM roles, Redshift Serverless, dbt (new `redshift` target alongside local DuckDB).

# 2026-09-10
- store raw data in s3 and query it directly with Athena

# 2026-09-11
- set up local Airflow via Docker Compose (WSL2, Docker Desktop). Make sure to use UTF-8/ASCII for AIRFLOW_UID in .env

# 2026-09-15
- researching ideas for capstone project

# 2026-09-16
- decided on a project analyzing the US Federal Spending
- deciding the agency scope, award type scope, and other angles this project will take

# 2026-09-17
- write out data plan, at least 2 questions per category