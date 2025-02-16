# 🚀 Real-Time Data Streaming Pipeline: Kafka + Spark + Snowflake + Power BI  

## 📌 Project Overview  
Excited to share that I have successfully built a **real-time data streaming pipeline** that integrates:  
✅ **Kafka (Confluent Cloud)** for real-time data ingestion  
✅ **Spark Streaming** for transformation  
✅ **Snowflake** for data storage  
✅ **Power BI** for real-time analytics  

This project **produces streaming data**, processes it via **Apache Spark**, stores it in **Snowflake**, and visualizes insights in **Power BI**.  

---

## 🔧 **Tech Stack & Tools**  
- **Programming Language**: Python  
- **Message Broker**: Confluent Kafka  
- **Big Data Processing**: Apache Spark  
- **Database**: Snowflake  
- **Visualization**: Power BI  

---

---

## 🚀 **How It Works**  
1️⃣ **Kafka Producer (`producer.py`)**  
   - Generates **streaming data** using **Faker**.  
   - Publishes messages to a **Kafka topic** in Confluent Cloud.  

2️⃣ **Kafka Consumer with Spark (`spark_consumer.py`)**  
   - Reads messages from Kafka **in real-time**.  
   - Converts raw messages into a **structured Spark DataFrame**.  
   - Applies **transformations** (e.g., filtering, data enrichment).  

3️⃣ **Store Data in Snowflake (`snowflake_connector.py`)**  
   - Inserts processed data into **Snowflake** using **Spark Snowflake Connector**.  

4️⃣ **Power BI Dashboard (`powerbi_dashboard.pbix`)**  
   - Connects to **Snowflake** for live data visualization.  
   - Displays **real-time insights** on an interactive dashboard.  

---


