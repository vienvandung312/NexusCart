# NexusCart

Focus: Real-time analytics and reporting for an e-commerce platform
Technologies Used:
Primary Database: MongoDB (product catalog, user data)
Cache Layer: Redis (session management, cart)
Analytics Store: ClickHouse (for analytics)
Event Processing: Kafka + Debezium (CDC from MongoDB) + Flink
Data Quality: Great Expectations
Orchestration: Kubernetes + ArgoCD
Transformation: dbt
Query Engine: Trino
Metadata Management: Hive Metastore
Learning Flow:
Set up basic e-commerce data in MongoDB
Implement Redis for caching
Use Debezium to capture changes from MongoDB
Process events with Kafka + Flink
Load data into ClickHouse for analytics
Build dbt models
Implement data quality checks
Set up Kubernetes deployment
