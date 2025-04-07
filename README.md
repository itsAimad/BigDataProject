# 🏥 Real-time Breast Cancer Monitoring System

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Streamlit-1.0+-green.svg" alt="Streamlit Version">
  <img src="https://img.shields.io/badge/Apache%20Kafka-2.8+-orange.svg" alt="Kafka Version">
  <img src="https://img.shields.io/badge/Apache%20Spark-3.0+-red.svg" alt="Spark Version">
  <img src="https://img.shields.io/badge/Apache%20Hadoop-3.3+-yellow.svg" alt="Hadoop Version">
</div>

## 🎥 Demo

<div align="center">
  <h3>📹 Application Demo</h3>
  <video width="800" controls loop autoplay>
    <source src="images/breast-cancer.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  
  <h3>🔄 Real-time Data Flow</h3>
  <img src="images/kafka_producer.png" alt="Data Flow" width="800">
</div>

## 🌟 Overview

A cutting-edge real-time breast cancer prediction system that combines machine learning, data streaming, and interactive visualization to assist healthcare professionals in early detection and diagnosis. This application provides real-time predictions, comprehensive data analysis, and intuitive visualizations.

## 🚀 Features

### 📊 Interactive Dashboard
- Real-time prediction monitoring
- Dynamic data visualization
- Interactive feature analysis
- Comprehensive statistics and metrics

### 🔄 Real-time Monitoring
- Live prediction updates
- Automatic data refresh
- Manual refresh option
- Prediction history tracking

### 📈 Advanced Visualizations
- Distribution analysis
- Timeline evolution
- Feature correlation heatmaps
- 3D scatter plots
- Customizable graph generation

### 🔍 Data Insights
- Prediction accuracy analysis
- Pattern recognition
- Feature importance visualization
- Historical data analysis

### 🧪 Test Cases
- Interactive feature input
- Real-time prediction testing
- Visual feature representation
- Confidence scoring

## 🛠️ Technologies Used

<div align="center">
  <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="50" height="50">
  <img src="/root/myproject/kafka_to_streamlit/images/image.png" width="66" height="50">
  <img src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-ar21.svg" width="100" height="50">
  <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-ar21.svg" width="100" height="50" style="background-color:white;">
  <img src="https://www.vectorlogo.zone/logos/plotly/plotly-ar21.svg" width="100" height="50">
  <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" width="50" height="50">
  <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" width="50" height="50">
  <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" width="50" height="50">
</div>

## 📋 System Architecture

<div align="center">
  <img src="images/bigDataArchitecture.png" alt="System Architecture" width="800">
</div>

## 📊 Data Flow

<div align="center">
  <h3>🔄 Real-time Data Processing Pipeline</h3>
  <img src="images/kafka_producer.png" alt="Kafka Producer Interface" width="800">
  <p><em>Kafka Producer sending real-time breast cancer data</em></p>
  
  <h3>⚡ Spark Processing</h3>
  <img src="images/spark_processing.png" alt="Spark Processing" width="800">
  <p><em>Spark processing the streaming data and preparing for predictions</em></p>
  
  <h3>🎯 Prediction Results</h3>
  <img src="images/predictions.png" alt="Prediction Results" width="800">
  <p><em>Real-time prediction results with confidence scores</em></p>
</div>

1. **Data Ingestion**
   - Data collection from medical sources
   - Real-time streaming through Kafka
   - Data preprocessing in Spark
   - Feature extraction and validation

2. **Processing Pipeline**
   - Spark processing of streaming data
   - Model inference for predictions
   - Probability calculations
   - Result validation and storage

3. **Visualization & Monitoring**
   - Real-time dashboard updates
   - Interactive data visualization
   - Statistical analysis
   - Prediction monitoring

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Apache Hadoop 3.3+
- Apache Kafka 2.8+
- Apache Spark 3.0+
- Streamlit 1.0+
- Docker
- PostgreSQL
- Grafana

### Installation
1. Clone the repository
```bash
git clone [repository-url]
```

2. Install Python dependencies
```bash
pip install -r requirements.txt
```

3. Start Docker containers and setup environment
```bash
# Start Hadoop containers
docker start hadoop-master hadoop-slave1

# Access hadoop-master container
docker exec -it hadoop-master bash

# Start Hadoop services
./start-hadoop.sh

# Start Kafka and Zookeeper
./start-kafka-zookeeper.sh
```

4. Start Spark Streaming
```bash
# Navigate to project directory
cd /root/myproject/kafka_to_streamlit

# Submit Spark Streaming job
spark-submit --jars /root/myproject/postgresql-42.6.0.jar \
             --packages org.apache.spark:spark-sql-kafka-0-10_2.12:3.5.1 \
             SparkStreaming.py
```

5. Run the Streamlit application
```bash
# In the same directory
streamlit run App.py
```

## 📊 Data Storage & Visualization

### PostgreSQL Database
<div align="center">
  <h3>📊 Database Schema</h3>
  <img src="/root/myproject/kafka_to_streamlit/images/postgres_schema.png" alt="PostgreSQL Schema" width="800">
  <p><em>Database structure for storing prediction results and patient data</em></p>
</div>

### Grafana Dashboards
<div align="center">
  <h3>📈 Real-time Monitoring Dashboard</h3>
  <img src="/root/myproject/kafka_to_streamlit/images/grafana_dashboard.png" alt="Grafana Dashboard" width="800">
  <p><em>Real-time monitoring of predictions and system metrics</em></p>
</div>

## 📸 Screenshots

<div align="center">
  <h3>📊 Dashboard Overview</h3>
  <img src="/root/myproject/kafka_to_streamlit/images/dashboard.png" alt="Dashboard Overview" width="800">
  
  <h3>📈 Real-time Monitoring</h3>
  <img src="/root/myproject/kafka_to_streamlit/images/monitoring.png" alt="Real-time Monitoring" width="800">
  
  <h3>🔍 Data Analysis</h3>
  <img src="/root/myproject/kafka_to_streamlit/images/analysis.png" alt="Data Analysis" width="800">
</div>

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

### **Aimad Bouya**

## 🙏 Acknowledgments

- University of Wisconsin for the breast cancer dataset
- Open-source community for the amazing tools and libraries
- Healthcare professionals for their valuable insights

---

<div align="center">
  <p>Made with ❤️ for better healthcare</p>
</div> 