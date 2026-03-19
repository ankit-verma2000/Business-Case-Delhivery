# 🚚 Delhivery Logistics Data Analysis & Feature Engineering

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![Dataset](https://img.shields.io/badge/Dataset-Delhivery_Logistics-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📘 About Delhivery

**Delhivery** is one of India’s largest and fastest-growing logistics companies.  
It aims to build the **operating system for commerce** by combining:
- Advanced logistics infrastructure 🚚  
- High-quality operations ⚙️  
- Cutting-edge technology & data intelligence 💡  

The data team plays a crucial role in improving **efficiency, scalability, and profitability** by leveraging large-scale operational data.

---

## 🌍 Project Context

This project focuses on analyzing **logistics and delivery trip data** generated from Delhivery’s data pipelines.

The dataset contains detailed information about:
- Trip creation and scheduling  
- Source and destination hubs  
- Delivery timelines and distances  
- OSRM-based route estimations  
- Segment-level delivery performance  

The goal is to transform raw operational data into **clean, structured, and meaningful features** for downstream analytics and modeling.

---

## 🎯 Objective

The primary objectives of this project are to:

- Clean and preprocess raw logistics data  
- Perform **feature engineering** for better analysis  
- Understand relationships between key variables  
- Handle missing values and outliers  
- Prepare the dataset for **data science and forecasting use cases**

---

## ❓ Key Business Questions Answered

- 🚚 How does **actual delivery time compare with estimated (OSRM) time**?  
- 📍 What factors influence **delivery delays and efficiency**?  
- ⏱️ How do **segment-level times contribute to total trip duration**?  
- 📊 Are there inconsistencies or anomalies in logistics data?  
- 🔍 Which features are most useful for future **prediction models**?  

---

## 📊 Dataset Overview

🔗 Dataset Link:  
https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/551/original/delhivery_data.csv?1642751181  

| Feature Type | Description |
|-------------|------------|
| Time-based | Trip creation, start/end timestamps |
| Location-based | Source and destination centers |
| Distance metrics | Actual vs OSRM distances |
| Time metrics | Actual vs estimated delivery times |
| Segment-level | Granular trip performance data |

---

## 🧾 Key Features

### ⏱️ Time Features
- `trip_creation_time`
- `od_start_time`, `od_end_time`
- `start_scan_to_end_scan`
- `actual_time`, `osrm_time`

---

### 📍 Location Features
- `source_center`, `source_name`
- `destination_center`, `destination_name`
- `route_type` (FTL / Carting)

---

### 📏 Distance Metrics
- `actual_distance_to_destination`
- `osrm_distance`
- `segment_osrm_distance`

---

### 🔗 Segment-Level Features
- `segment_actual_time`
- `segment_osrm_time`
- `segment_factor`

---

## 🧹 Data Cleaning & Preprocessing

Key steps performed:

- Handling **missing values**
- Treating **outliers**
- Converting timestamps into usable formats
- Standardizing column formats
- Cleaning inconsistent or noisy data

---

## 🧠 Feature Engineering

- Created new features from **time and distance fields**
- Derived insights from **actual vs estimated metrics**
- Built relationships between **trip-level and segment-level data**
- Normalized and standardized numerical columns

---

## 🔍 Analysis Scope

### 📊 Delivery Performance Analysis
- Compared **actual vs OSRM time**
- Identified delays and inefficiencies

### 🚚 Route Optimization Insights
- Analyzed differences in **estimated vs actual routes**
- Evaluated logistics accuracy

### ⏱️ Segment-Level Analysis
- Studied contribution of segments to total trip time
- Identified bottlenecks in delivery flow

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|--------|
| **Python** | Data analysis & preprocessing |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical computations |
| **Jupyter Notebook** | Analysis environment |

---

## 💡 Key Insights

✅ Identified gaps between **actual and estimated delivery times**  
✅ Highlighted **data inconsistencies and anomalies**  
✅ Improved dataset quality through preprocessing  
✅ Extracted meaningful features for **future modeling**  

---

## 🚀 Business Impact

This analysis helps:
- Improve **delivery time predictions**
- Optimize **route planning and logistics**
- Enhance **data quality for ML models**
- Support better **operational decision-making**

---

## 👨‍💻 Author

**Ankit Verma**  
_Data Analyst | Python • Feature Engineering • Data Analysis_

🔗 [LinkedIn](https://www.linkedin.com/in/ankit-verma)  
🔗 [GitHub](https://github.com/ankitverma)

---

⭐ **If you found this project useful, consider starring the repository!** ⭐
