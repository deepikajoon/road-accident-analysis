# road-accident-analysis
🚗 Road Accident Analysis using Data Mining Techniques
📘 Project Overview

This project focuses on analyzing road accident data using various data mining techniques to uncover patterns, detect anomalies, and predict accident severity.
The study is based on the US Accidents (2016–2023) dataset, which contains detailed information about road accidents across the United States, including time, location, weather, and severity.

The main goal is to help authorities, policy makers, and the community understand accident trends and improve road safety through data-driven insights.

🎯 Aim

To apply multiple data mining techniques — including clustering, anomaly detection, ensemble classification, and stream mining — on the US Accidents dataset to identify accident hotspots, unusual patterns, and predict accident severity.

📊 Dataset Information

Dataset Name: US Accidents (2016–2023)

Source: Kaggle
Size: ~3 million records
Features:

Start_Time, End_Time → Timestamp of accident

Severity → Level of accident severity (1–4)

Latitude, Longitude → Accident location

Weather_Condition, Temperature(F), Humidity(%) → Environmental conditions

Distance(mi) → Distance affected by the accident

and more...

🧠 Techniques Applied

Clustering

Algorithms: K-Means, Hierarchical Clustering, DBSCAN

Purpose: Identify accident-prone zones (hotspots) based on location and conditions.

Anomaly Detection

Algorithms: Z-Score, IQR, Isolation Forest, Local Outlier Factor (LOF)

Purpose: Detect rare or unusual accident cases with abnormal conditions.

Ensemble Classification

Algorithms: Random Forest, Gradient Boosting, XGBoost

Purpose: Predict accident severity using road, weather, and time features.

Stream Mining (Incremental Learning)

Algorithms: Hoeffding Tree, Online Naïve Bayes

Purpose: Simulate real-time accident data flow and model adaptation.

(Optional) Text Mining

Analyze accident descriptions for insights using TF-IDF and NLP preprocessing.

🛠️ Tools and Libraries

Python 3.10+

Google Colab / Jupyter Notebook

Libraries:
pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, folium, scikit-multiflow

🧩 Project Workflow

Data Preprocessing → Cleaning, handling missing values, feature encoding.

Exploratory Data Analysis (EDA) → Visualizations of time, weather, and location trends.

Clustering → Identify hotspots using geospatial clustering.

Anomaly Detection → Detect rare or severe accident conditions.

Classification → Predict severity using ensemble models.

Stream Mining Simulation → Incrementally learn from accident data streams.

Evaluation & Visualization → Metrics, confusion matrix, cluster maps, charts.

📈 Expected Outcomes

Identification of high-risk accident zones.

Discovery of abnormal accident patterns.

Predictive model to estimate accident severity.

Real-time analysis potential for traffic monitoring systems.

✍️ Author

Name: Deepika
Course: B.Sc. (Hons) Computer Science
Subject: Data Mining - II
Institution: Delhi University
Semester: V
