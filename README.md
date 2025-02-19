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

- **Live Prediction App**: [Try Here](http://13.60.202.76:5000/)  

  ![image](https://github.com/mrunal-chavhan/CDAC_PROJECT/blob/main/UI/ui_image.png)
  

# 🚦 Traffic Crashes Streaming & Analysis

## 📌 Project Overview  
This project processes real-time **traffic crashes data** using **Kafka, Spark, and Cassandra** and visualizes it in **Power BI**.

## 🔗 Dataset  
- **Source**: [Traffic Crashes Data](https://catalog.data.gov/dataset/traffic-crashes-crashes)  
- **Sample File**: [Download Here]()

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
  ![Cassandra Screenshot](https://github.com/mrunal-chavhan/CDAC_PROJECT/commit/105f8423e20fb0b4c69a2b3c5fc09faebb0cefbe#diff-cb50ead9aaa4137746202fdc9b0b2b0bc3cf626be681c530cb109348ae1761ff)

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




