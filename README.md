# 🚗 Road Accident Analysis using Data Mining Techniques

### 📘 Course:
**B.Sc. (Hons.) Computer Science – Data Mining II Project**

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


