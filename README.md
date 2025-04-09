<div align="center">
  <img src="images/project-banner.png" alt="Project Banner" width="100%"/>
  <h1>🏥 Real-time Breast Cancer Monitoring System</h1>
  <p>A cutting-edge ML-powered system for early cancer detection and real-time monitoring</p>

  <!-- Badges with modern design -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python Version"/>
    <img src="https://img.shields.io/badge/Streamlit-1.0+-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit Version"/>
    <img src="https://img.shields.io/badge/Apache_Kafka-2.8+-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" alt="Kafka Version"/>
    <img src="https://img.shields.io/badge/Apache_Spark-3.0+-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" alt="Spark Version"/>
    <img src="https://img.shields.io/badge/Hadoop-3.3+-66CCFF?style=for-the-badge&logo=apache-hadoop&logoColor=black" alt="Hadoop Version"/>
  </p>
</div>

## 🎬 Project Overview

<div align="center">
  <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID">
    <img src="kafka_to_streamlit/images/thumbnail.png" alt="Project Overview Video" width="600"/>
  </a>
  <p><em>Click to watch the project overview video</em></p>
</div>

## ✨ Interactive Demo

<div align="center">
  <h3>Live System Demo For a Test Case's Tab</h3>
  <video width="800" controls loop autoplay>
    <source src="kafka_to_streamlit/images/breast-cancer.mp4" type="video/mp4">
  </video>
  <p><em>Real-time prediction and monitoring in action</em></p>
</div>

## 💫 Key Features

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/dashboard-layout.png"/>
        <br /><strong>Interactive Dashboard</strong>
        <br />Real-time monitoring & visualization
        <br /><img src="https://raw.githubusercontent.com/itsAimad/BigDataProject/main/kafka_to_streamlit/images/real-time.png" width="200"/>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/statistics.png"/>
        <br /><strong>Feature Importance</strong>
        <br />Key feature analysis & impact
        <br /><img src="kafka_to_streamlit/images/importance.png" width="200"/>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/visual-game-boy.png"/>
        <br /><strong>Advanced Visualizations</strong>
        <br />3D plots & heatmaps
        <br /><img src="https://raw.githubusercontent.com/itsAimad/BigDataProject/main/kafka_to_streamlit/images/heatmap.png" width="200"/>
      </td>
    </tr>
  </table>
</div>

## 🏗 System Architecture

<div align="center">
  <img src="kafka_to_streamlit/images/bigDataArchitecture.png" alt="System Architecture" width="800"/>
  <p><em>Comprehensive system architecture showing data flow and component interaction</em></p>
  
  <details>
    <summary>📝 Detailed Architecture Explanation</summary>
    <p>Detailed breakdown of each component and their interactions</p>
  </details>
</div>

## 📊 Data Flow

<div align="center">
  <h3>🔄 Real-time Data Processing Pipeline</h3>
  <img src="kafka_to_streamlit/images/dashboard.png" alt="Real-time Processing" width="800">
  <p><em>Real-time data processing and prediction pipeline</em></p>
  
  <h3>⚡ System Features</h3>
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/itsAimad/BigDataProject/main/kafka_to_streamlit/images/real-time.png" width="200"/>
        <br /><strong>Real-time Monitoring</strong>
        <br />Live predictions & updates
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/itsAimad/BigDataProject/main/kafka_to_streamlit/images/latest.png" width="200"/>
        <br /><strong>Latest Predictions</strong>
        <br />Instant results visualization
      </td>
      <td align="center">
      <img src="kafka_to_streamlit/images/prediction_confidence.png" width="200"/>
        <br /><strong>Advanced Analytics</strong>
        <br />Detailed data insights
      </td>
    </tr>
  </table>
  
</div>

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="40"/><br />Python</td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" width="40"/><br />Hadoop</td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-ar21.svg" width="70"/><br />Spark</td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" width="40"/><br />Kafka</td>
    </tr>
    <tr>
      <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Streamlit-logo-primary-colormark-darktext.png" width="80"/><br />Streamlit</td>
      <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Plotly-logo.png" width="90"/><br />Plotly</td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" width="40"/><br />PostgreSQL</td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" width="40"/><br />Grafana</td>
    </tr>
  </table>
</div>

## 🚀 Installation & Setup Guide

<div align="center">
  <img src="images/setup-guide.gif" alt="Setup Process" width="100%"/>
</div>

### Prerequisites
```bash
Python 3.10+  |  Apache Hadoop 3.3+  |  Apache Kafka 2.8+  |  Apache Spark 3.0+
Streamlit 1.0+  |  Docker  |  PostgreSQL  |  Grafana
```

### Step-by-Step Setup

1. **Start Docker Containers**
```bash
# Start Hadoop containers
docker start hadoop-master hadoop-slave1

# Start Grafana container
docker start grafana
```

2. **Access Hadoop Master Container**
```bash
docker exec -it hadoop-master bash
```

3. **Start Hadoop and Kafka Services**
```bash
# Start Hadoop services
./start-hadoop.sh

# Start Kafka and Zookeeper
./start-kafka-zookeeper.sh
```

4. **Create Kafka Topics**
```bash
# Create prediction-topic
kafka-topics.sh --create --topic prediction-topic \
                --partitions 3 \
                --replication-factor 3 \
                --bootstrap-server localhost:9092

# Create prediction-results-topic
kafka-topics.sh --create --topic prediction-results-topic \
                --partitions 3 \
                --replication-factor 3 \
                --bootstrap-server localhost:9092

# Verify topics creation
kafka-topics.sh --list --bootstrap-server localhost:9092
```

5. **Install Python Dependencies**
```bash
pip install -r requirements.txt
```

6. **Start Spark Streaming**
```bash
# Navigate to project directory
cd /root/myproject/kafka_to_streamlit

# Submit Spark Streaming job
spark-submit --jars /root/myproject/postgresql-42.6.0.jar \
             --packages org.apache.spark:spark-sql-kafka-0-10_2.12:3.5.1 \
             SparkStreaming.py
```

7. **Launch Streamlit Application**
```bash
# In a new terminal
streamlit run App.py
```

### 🔍 Verification Steps

1. Check Hadoop services:
```bash
jps
```
Expected output should show: NameNode, DataNode, ResourceManager, etc.

2. Verify Kafka topics:
```bash
kafka-topics.sh --describe --bootstrap-server localhost:9092
```

3. Monitor Kafka topics:
```bash
# For prediction-topic
kafka-console-consumer.sh --bootstrap-server localhost:9092 \
                         --topic prediction-topic \
                         --from-beginning

# For prediction-results-topic
kafka-console-consumer.sh --bootstrap-server localhost:9092 \
                         --topic prediction-results-topic \
                         --from-beginning
```

### 📊 Accessing Services

- **Hadoop NameNode**: http://localhost:9870
- **YARN ResourceManager**: http://localhost:8088
- **Grafana Dashboard**: http://localhost:3000
- **Streamlit App**: http://localhost:8501

### ⚠️ Troubleshooting

If you encounter issues:

1. Check if all containers are running:
```bash
docker ps
```

2. Verify Kafka broker status:
```bash
kafka-broker-api-versions.sh --bootstrap-server localhost:9092
```

3. Check Kafka logs:
```bash
cat /var/log/kafka/server.log
```

4. Ensure proper permissions:
```bash
chmod +x start-hadoop.sh
chmod +x start-kafka-zookeeper.sh
```

## 📈 Performance Metrics

<div align="center">
  <img src="kafka_to_streamlit/images/roc.png" alt="Performance Metrics" width="460px"/>
  <p><em>System performance and accuracy metrics</em></p>
</div>

## 👨‍💻 Author

<div align="center">

  <h3>Aimad Bouya</h3>
  <p>AI & Data Enginnering Student</p>
</div>

## 📄 License
MIT License - See [LICENSE](LICENSE) for details

<div align="center">
  <br />
  <p>Made with ❤️ for better healthcare</p>
  <p>
    <a href="">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://github.com/itsAimad">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a href="[your-twitter]">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
    </a>
  </p>
  
  <!-- Repository Stats -->
  <p>
    <img src="https://img.shields.io/github/watchers/itsAimad/BigDataProject?style=social" alt="Watchers"/>
    <img src="https://img.shields.io/github/stars/itsAimad/BigDataProject?style=social" alt="Stars"/>
    <img src="https://img.shields.io/github/forks/itsAimad/BigDataProject?style=social" alt="Forks"/>
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FitsAimad%2FBigDataProject&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/>
  </p>

  <!-- Profile Views -->
  <p>
    <img src="https://komarev.com/ghpvc/?username=itsAimad&color=brightgreen" alt="Profile Views"/>
  </p>
</div> 



