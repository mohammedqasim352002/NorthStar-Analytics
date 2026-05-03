# NorthStar Urban Mobility and Logistics – Data Analytics Project

## 📌 Overview

This project presents a complete data analytics solution for the NorthStar Urban Mobility and Logistics case study. The main objective is to identify operational inefficiencies, customer issues, and system-level problems using an integrated approach combining SQL, R, Python, and MongoDB.

The analysis is performed using Google Colab notebooks, where all tools are connected in a single workflow.

---

## 📂 Dataset Description

The dataset consists of 9 CSV files (total 4,208 records):

* `customers.csv` – Customer profiles, loyalty and engagement scores
* `orders.csv` – Service order details
* `deliveries.csv` – Delivery outcomes and timings
* `drivers.csv` – Driver performance data
* `vehicles.csv` – Fleet information and maintenance status
* `hubs.csv` – Hub locations and capacity
* `incidents.csv` – Operational incidents
* `complaints.csv` – Customer complaints and compensation
* `app_events.csv` – Mobile app interaction data

---

## 🛠️ Tools & Technologies

* **R (sqldf, dplyr, ggplot2)** – SQL queries + statistical analysis
* **Python (pandas, numpy, matplotlib)** – Data processing and visualisation
* **MongoDB Atlas (PyMongo)** – NoSQL database design and implementation
* **Google Colab** – Unified development environment

---

## 🔍 Key Tasks Performed

### 1. Data Preprocessing

* Zone normalization across datasets
* Missing value handling (median imputation / logical NA)
* Timestamp anomaly detection and handling

---

### 2. SQL Analysis in R

* Order revenue by zone
* Complaint rates by service type
* Hub performance and failure rates
* Driver performance analysis
* Complaint resolution statistics
* Incident clustering
* Customer segmentation
* Route override impact on delivery outcomes

---

### 3. R Analytics & Visualisation

* Delivery status distribution
* Driver rating vs training analysis
* Order value distribution
* Complaint trends over time
* Incident frequency analysis
* Correlation heatmap

---

### 4. Python Analysis

* Feature engineering (failure flag, override rate)
* Descriptive statistics
* Hub performance charts
* API latency analysis
* Complaint trend validation
* Override vs rating relationship
* Vehicle maintenance analysis

---

### 5. MongoDB Implementation

* Document-based schema design
* Two collections:

  * `customer_sessions`
  * `delivery_incidents`
* CRUD operations using PyMongo
* Aggregation pipelines for analytics
* Indexing strategy for performance optimisation

---

## 📊 Key Findings

* Low-capacity hubs are overloaded → high failure rates
* Route overrides strongly linked to delivery failure
* Riverside Hub shows major fleet reliability issues
* High-value customers becoming inactive unnoticed
* Mobile app latency causing continuous complaints

---

## 💡 Recommendations

* Upgrade capacity of critical hubs
* Monitor and control route overrides
* Improve preventive maintenance (especially EV vehicles)
* Implement customer health monitoring system
* Fix mobile platform latency issues

---

## 🚀 How to Run

1. Open the Colab notebooks from this repository
2. Upload dataset CSV files (if not included)
3. Run cells sequentially
4. MongoDB connection requires valid Atlas credentials

---

## 📁 Repository Structure

* `R_SQL_Notebook.ipynb`
* `Python_Analytics_Notebook.ipynb`
* `MongoDB_Implementation.ipynb`
* `dataset/` (CSV files)
* `report/` (final report document)

---

## 📎 Notes

* All analysis is based on cleaned and validated data
* Results are cross-verified using multiple tools
* Designed for academic and practical analytics demonstration

---

## 👨‍💻 Author

Student Project – Databases and Analytics Coursework

---
