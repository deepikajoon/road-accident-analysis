# 🚗 Road Accident Analysis using Data Mining Techniques

### 📘 Course:
**B.Sc. (Hons.) Computer Science – Data Mining II Project**
Road Traffic Accident Analysis

DBSCAN, Anomaly Detection & Ensemble Classification

Project Overview

This project analyzes road traffic accident data to identify accident hotspots, detect anomalous accident records, and predict accident severity using data mining techniques. The work is carried out as part of the Data Mining-II curriculum for B.Sc. (Hons) Computer Science (2024–26) at Shyama Prasad Mukherji College for Women, University of Delhi.

Aim

To analyze road accident patterns by:

Identifying spatial and temporal accident hotspots

Detecting unusual or rare accident cases

Predicting accident severity using ensemble classification models

Dataset

Dataset Name: US Accidents (2016–2023)

Source: Kaggle

Subset Used: US_Accidents_Sample_100k.csv (100,000 records)

The dataset contains real accident reports with geographic, environmental, and temporal features collected from traffic sensors, government agencies, and other sources.

Features Used

Some key features used in this project include:

Accident Severity (1–4)

Latitude and Longitude

Distance affected

Temperature, Humidity, Pressure

Visibility and Wind Speed

Weather Conditions

Extracted Time Features (Hour, Day, Month)

These features are suitable for clustering, anomaly detection, and classification.

Techniques Implemented
1. Data Preprocessing

Feature selection

Datetime feature extraction (hour, day, month)

Missing value handling (median/mode)

Label encoding for categorical features

Standard scaling for numerical features

2. DBSCAN Clustering

Identifies accident hotspots without predefining number of clusters

Detects noise points representing rare or unusual accidents

Suitable for spatial (latitude–longitude) data

Evaluation using Silhouette Score and Davies–Bouldin Index

3. Anomaly Detection

Z-Score Method

IQR Method

Isolation Forest

These methods help identify extreme or rare accident cases caused by unusual weather or conditions.

4. Ensemble Classification

Models used to predict accident severity:

Decision Tree

Bagging

AdaBoost

Random Forest

Evaluation metrics:

Accuracy

Confusion Matrix

Classification Report

Key Insights

DBSCAN successfully identified spatial–temporal accident hotspots

Noise points often aligned with anomalous weather or rare events

Isolation Forest captured multivariate anomalies effectively

Random Forest achieved the highest classification accuracy

Accident severity is influenced by weather, visibility, humidity, and time of day

Files in This Repository

RTA_Project.ipynb (or Colab notebook file)

Project_Report.docx / Project_Report.pdf

data/US_Accidents_Sample_100k.csv

README.md

Colab Notebook

Notebook implementation (preprocessing, clustering, anomaly detection, and classification):
👉 https://colab.research.google.com/drive/1x-ujxPbInW9yTjV62UxI7v648wJrWAcj

Conclusion

This project demonstrates how combining clustering, anomaly detection, and ensemble learning provides deep insights into road accident patterns. The findings can support accident hotspot monitoring, risk analysis, and informed decision-making for traffic management authorities.

Limitations & Future Scope

Using the full dataset may improve robustness

Additional features like road type and traffic volume can enhance accuracy

Future work may include real-time models and geospatial heatmap visualization

Disclaimer

This project is for academic and educational purposes only and is not intended for real-world traffic or safety decision-making.
### 👩‍💻 Student:
**Deepika**

---

## 🎯 Project Aim
The aim of this project is to analyze and predict **road accident patterns** using multiple **data mining techniques**, helping the community and authorities identify **high-risk accident conditions** and **improve road safety**.

---

## 🧩 Dataset
**Source:** [Traffic Accidents Dataset - Kaggle](https://www.kaggle.com/datasets/oktayrdeki/traffic-accidents)

**File Used:** `traffic_accidents.csv`

**Total Records:** ~370,000  
**Columns Include:** Date, Weather Condition, Lighting Condition, Road Surface, Injury Type, etc.

---

## ⚙️ Techniques Applied

| Unit | Concept | Techniques Used |
|------|----------|----------------|
| Unit 1 | **Clustering** | K-Means, DBSCAN, Hierarchical Clustering |
| Unit 2 | **Ensemble Methods** | Decision Tree, Bagging, AdaBoost, Random Forest |
| Unit 3 | **Anomaly Detection** | Z-Score, Isolation Forest, Cluster-based Outlier Detection |
| Unit 4 | **Text Mining (N/A)** | — |
| Unit 5 | **Stream Mining** | MiniBatchKMeans (CluStream Simulation), Decay Function, Moving Window Analysis |

---

## 🧠 Tools & Libraries
- **Language:** Python  
- **Environment:** Google Colab  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, scipy  

---

## 📊 Summary of Findings

### 🔹 Clustering:
- K-Means formed meaningful groups of accidents based on severity and time.
- Hierarchical clusters confirmed K-Means findings.
- DBSCAN identified rare, isolated accident cases.

### 🔹 Anomaly Detection:
- Statistical (Z-Score) and Isolation Forest methods revealed outliers — potential rare, high-severity accidents.

### 🔹 Stream Mining:
- Time series trend analysis showed temporal accident patterns.
- MiniBatchKMeans simulated streaming data clustering.
- Decay function emphasized recent accident influence.

### 🔹 Ensemble Learning:
| Model | Accuracy (approx.) |
|--------|--------------------|
| Decision Tree | ~75% |
| Bagging | ~80% |
| AdaBoost | ~82% |
| Random Forest | **~85% (Best)** |

---

## 📁 Repository Structure
📂 Road_Accident_Analysis
│
├── traffic_accidents.csv # Original Dataset
├── traffic_accidents_processed.csv # Cleaned & Preprocessed Data
├── traffic_accidents_final.csv # Final dataset with results
├── Traffic_Accident_Analysis.ipynb # Complete Colab Notebook (All in One)
└── README.md # Project Documentation

---

## 🚀 How to Run

1. Open **Google Colab**
2. Upload the notebook: `Traffic_Accident_Analysis.ipynb`
3. Upload the dataset: `traffic_accidents.csv`
4. Run all cells sequentially.
5. View results and exported processed files at the end.

---

## 💡 Project Outcome

> This project successfully demonstrates how multiple data mining methods can be integrated to extract insights from real-world data.
> The approach helps in **predicting accident severity**, **detecting anomalies**, and **tracking time-based trends**, all of which contribute toward **enhancing road safety awareness and prevention systems.**

---

## 👩‍💻 Author
**Deepika**  
B.Sc. (Hons.) Computer Science  
University of Delhi


