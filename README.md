# BFSI Data & AI Platform

**Platform**: AWS S3 → Databricks Lakehouse → Snowflake (regulated consumption)

**Week 1 Day 1**: AWS lakehouse positioning

TODO:
- [ ] S3 buckets
- [ ] Glue Studio demo
- [ ] Databricks notebook


### Key Learnings
- **IAM + S3 policies** debugged [file:138]
- **Spark partitioning**: 5 rows → 4 parquet parts (production behavior)
- **coalesce(1)** for single file control

[Bucket Policy.pdf](https://github.com/user-attachments/files/24339710/Bucket.Policy.pdf)
[s3bucket.pdf](https://github.com/user-attachments/files/24339709/s3bucket.pdf)
[Job Run Status.pdf](https://github.com/user-attachments/files/24339708/Job.Run.Status.pdf)
[glue ETL output tranform.pdf](https://github.com/user-attachments/files/24339707/glue.ETL.output.tranform.pdf)
