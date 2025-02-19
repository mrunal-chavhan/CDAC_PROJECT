# T20-Cricket-Match-Score-Prediction

## 📌 Aim of The Project
To build a model that predicts the inning score of a match based on match conditions.

## 📅 Project Timeline

- Collected data from Cricbuzz & ESPN Cricinfo.
- Performed Exploratory Data Analysis.
- Trained an XGBoost Regressor model.
- Created API using Flask.
- Developed a Tableau Dashboard.

## 🛠️ Technology Stack

- Data Collection: Selenium
- Processing & ML: Pandas, NumPy, XGBoost
- Deployment: Flask, AWS
- Visualization: Tableau

## 🚀 Model Deployment

- Flask Web App: Predicts match scores.
- AWS Hosting: Ensures availability.
- Tableau Dashboard: [View Here](https://public.tableau.com/views/Cricket_Score_Prediction_visualization/Dashboard2?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

  ![image](https://github.com/user-attachments/assets/32de0c47-32df-4331-8937-fb80012a7c96)
  

# 🚦 Traffic Crashes Streaming & Analysis

## 📌 Project Overview  
This project processes real-time **traffic crashes data** using **Kafka, Spark, and Cassandra** and visualizes it in **Power BI**.

## 🔗 Dataset  
- **Source**: [Traffic Crashes Data](https://catalog.data.gov/dataset/traffic-crashes-crashes)  
- **Sample File**: [Download Here](data/sample_data.csv)

## ⚙️ Project Workflow  
1️⃣ Kafka Producer reads traffic crash data from a local server and streams it.
2️⃣ Spark Consumer processes transformations on the streamed data.
3️⃣ Processed data is stored in Cassandra for efficient querying.
4️⃣ Power BI connects to Cassandra (via ODBC) for visualization and analysis.

---

## 🛠️ Technology Stack  
- **Streaming**: Kafka  
- **Processing**: Spark  
- **Storage**: Cassandra  
- **Visualization**: Power BI  
- **Connection**: ODBC Driver  

---

## 🚀 Setup Instructions  

### 1️⃣ Kafka Producer & Consumer  
- **Producer Code**: [producer.py](kafka/producer.py)  
- **Consumer Code**: [consumer_spark.py](kafka/consumer_spark.py)  

### 2️⃣ Cassandra Table Schema  
- **Schema File**: [schema.txt](cassandra/schema.txt)  
- **Stored Data Preview**:  
  ![Cassandra Screenshot](cassandra/cassandra_screenshots/cassandra_table.png)

### 3️⃣ Power BI Connection  
- **ODBC Driver Download**: [ODBC Driver Link](powerbi/odbc_driver_link.txt)  
- **Cassandra to Power BI Connection**:  
  ![Power BI Connection](powerbi/connectivity_screenshots/powerbi_odbc.png)  
- **Power BI Dashboard Preview**:  
  ![Power BI Dashboard](powerbi/powerbi_screenshots/dashboard.png)

---

## 📈 Results & Insights  
- Power BI provides **real-time analysis** of crash patterns.  
- Data can be **filtered & visualized** based on different crash parameters.

---




