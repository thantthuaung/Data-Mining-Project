# Data-Mining-Project
# Identifying Economic Growth Hubs in Singapore  
**Group 34 – CP3403 Data Mining Project (JCU Singapore)**

This repository contains the final report and codebase for a data mining project focused on identifying potential economic and innovation hubs in Singapore using geospatial business registration data. The project was completed as part of the CP3403 (Data Mining) subject at James Cook University.

---

## 📁 Contents

- `group-34-data-mining-assignment.ipynb`  
  Python notebook with preprocessing, classification, and clustering analysis.

- `Group_34_Project_Report.pdf`  
  Full documentation of the project, including methodology, results, and insights.

---

## 🎯 Objective

This project explores how data mining techniques can be used to uncover emerging clusters of business activity in Singapore. Using registration records with spatial attributes (e.g., postal code, street name), we aimed to:

- Detect regions with high growth potential.
- Analyze business density and distribution over time.
- Provide a data-driven foundation for planning and investment decisions.

---

## 🧪 Methods

### 🔧 Preprocessing
- Reduced dataset size (~280,000 ➝ 28,000 records).
- Cleaned and formatted datetime, numeric, and text fields.
- Applied feature scaling for model readiness.

### 📊 Classification
- **Support Vector Machine (SVM)**: Classified regions as "hub" or "non-hub" based on business registration density.
- **Random Forest**: Achieved ~91% accuracy using spatial and categorical features with probability-based region scoring.

### 🧩 Clustering
- **K-Prototypes algorithm**: Grouped regions into clusters based on both numerical and categorical features.
- Identified three regional types: established hubs, developing zones, and low-activity areas.
- Visualized clusters using PCA-reduced 2D plots.

---

## 📈 Results Summary

- **Top predicted hubs**:  
  - Paya Lebar Road  
  - Anson Road  
  - Robinson Road  

- **Cluster categories**:  
  - Cluster 0: Mature business districts (e.g., CBD)
  - Cluster 1: Transitional growth zones
  - Cluster 2: Dormant or underdeveloped areas

---

## 🛠 Tools & Libraries

- Python (Pandas, Scikit-learn, Matplotlib, kmodes)
- Jupyter Notebook
- PDF report with figures and analysis

---

## 🧭 Applications

This analysis supports:
- Urban development planning
- Investment opportunity targeting
- Policy and zoning strategy for economic development

---

## 👥 Team

**Group 34**  
CP3403 – Data Mining  
James Cook University Singapore  
Trimester 1, 2025

---

Feel free to explore the notebook and report for full details on methodology and insights.
