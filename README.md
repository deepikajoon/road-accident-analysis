# 🚗 Road Traffic Accident Analysis using Data Mining Techniques

## 📘 Course
**B.Sc. (Hons.) Computer Science – Data Mining II**  
Shyama Prasad Mukherji College for Women  
University of Delhi (2024–26)

---

## 📌 Project Overview
This project analyzes road traffic accident data to identify accident hotspots, detect anomalous accident records, and predict accident severity using data mining techniques. The project integrates clustering, anomaly detection, and ensemble classification methods to extract meaningful insights from real-world accident data.

---

## 🎯 Aim
The aim of this project is to analyze road accident patterns by:
- Identifying spatial and temporal accident hotspots  
- Detecting unusual or rare accident cases  
- Predicting accident severity using ensemble classification models  

---

## 🧩 Dataset
- **Dataset Name:** US Accidents (2016–2023)  
- **Source:** Kaggle  
- **Subset Used:** US_Accidents_Sample_100k.csv (100,000 records)

The dataset contains real accident reports collected from traffic sensors, government agencies, and news feeds. It includes geographic, environmental, and temporal features suitable for data mining tasks.

---

## 🧠 Features Used
- Accident Severity (1–4)
- Latitude and Longitude
- Distance affected
- Temperature, Humidity, Pressure
- Visibility and Wind Speed
- Weather Conditions
- Extracted Time Features (Hour, Day, Month)

These features were selected because they influence accident severity and are suitable for clustering, anomaly detection, and classification.

---

## ⚙️ Techniques Implemented

### Data Preprocessing
- Feature selection
- Datetime feature extraction (hour, day, month)
- Missing value handling using median and mode
- Label encoding for categorical variables
- Standard scaling for numerical features

### DBSCAN Clustering
DBSCAN is used to identify dense regions of accidents without specifying the number of clusters. It detects spatial–temporal accident hotspots and marks rare or unusual accident records as noise. Model evaluation is performed using Silhouette Score and Davies–Bouldin Index.

### Anomaly Detection
Multiple methods are used to detect unusual accident cases:
- Z-Score Method
- IQR Method
- Isolation Forest

These techniques help identify extreme values and multivariate anomalies often associated with rare weather or environmental conditions.

### Ensemble Classification
Accident severity prediction is performed using:
- Decision Tree
- Bagging
- AdaBoost
- Random Forest

Models are evaluated using accuracy, confusion matrix, and classification report. Random Forest achieves the highest overall performance.

---

## 📊 Key Insights
- DBSCAN successfully identified spatial–temporal accident hotspots
- Noise points often aligned with extreme weather or rare accident conditions
- Isolation Forest captured multivariate anomalies effectively
- Random Forest achieved the highest classification accuracy
- Accident severity is strongly influenced by weather conditions, visibility, humidity, and time of day

---

## 🔗 Colab Notebook
The complete implementation covering preprocessing, clustering, anomaly detection, and classification is available here:  
👉 https://colab.research.google.com/drive/1x-ujxPbInW9yTjV62UxI7v648wJrWAcj

---

## 🧾 Conclusion
This project demonstrates how clustering, anomaly detection, and ensemble learning techniques can be combined to gain deep insights into road accident patterns. The analysis supports accident hotspot identification, severity prediction, and risk assessment for improved road safety awareness.

---

## 🔮 Limitations & Future Scope
- Using the full dataset may improve result robustness
- Including additional features such as road type and traffic volume can enhance prediction accuracy
- Future work may include real-time models and geospatial heatmap visualization

---

## ⚠️ Disclaimer
This project is for academic and educational purposes only and is not intended for real-world traffic or safety decision-making.

---

## 👩‍💻 Author
**Deepika**  
B.Sc. (Hons.) Computer Science  
University of Delhi
