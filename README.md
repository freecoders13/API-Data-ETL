# API-Data-ETL

🛠️ Reddit Data Pipeline with Delta Lake and PySpark

End-to-end Reddit Data Pipeline: Extracted data using PRAW, stored as CSV, ingested into Delta Lake (Bronze → Silver → Gold) using PySpark. Applied transformations, built a semantic layer, and implemented Delta Lake time travel &amp; rollback.

🔍 Data Extraction: Fetched data from the Reddit API using PRAW (Python Reddit API Wrapper).

🧱 Bronze Layer: Raw Reddit data saved as .csv files and ingested into Delta Lake for historical retention.

🧹 Silver Layer: Data cleansing, normalization, and schema enforcement using PySpark.

📊 Gold Layer (Semantic Layer): Aggregated and modeled data ready for analytics and reporting.

⏳ Delta Time Travel & Rollback: Enabled versioned access and rollback on the semantic layer to support auditability and debugging.

📌 Key Concepts Demonstrated
1. Lakehouse architecture (Delta Lake)

2. Time travel and rollback

3. Medallion architecture (Bronze → Silver → Gold)

4. ETL best practices using PySpark

5. Data versioning and audit support
