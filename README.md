# 🧬 Breast Cancer Diagnostic Data – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> 🔬 A comprehensive exploratory data analysis (EDA) on the Breast Cancer Wisconsin (Diagnostic) dataset to uncover patterns and prepare the ground for future machine learning models. This project aims to visualize the hidden structure, clean the data, and extract meaningful insights from medical attributes.

---

## 📚 Table of Contents

- [📌 Project Motivation](#project-motivation)
- [📁 Dataset Summary](#dataset-summary)
- [📊 Key Visualizations](#key-visualizations)
- [🧠 EDA Breakdown](#eda-breakdown)
- [🚀 How to Run](#how-to-run)
- [🛠️ Tech Stack](#tech-stack)
- [🖼️ Visual Preview](#visual-preview)


---

## 📌 Project Motivation

Breast cancer is one of the most common cancers in women globally. Early detection through data-driven diagnostics is crucial in improving outcomes. This project explores:
- What features differentiate malignant and benign tumors?
- Are there any features strongly correlated that could aid classification?
- How can we clean and visualize the data to assist future ML models?

---

## 📁 Dataset Summary

| Attribute        | Details                                  |
|------------------|-------------------------------------------|
| Source           | UCI Machine Learning Repository           |
| Samples          | 569 entries (diagnosed tumors)            |
| Features         | 30 numerical features derived from images |
| Target Variable  | `Diagnosis` - M (Malignant) / B (Benign)  |

Each sample includes computed metrics like:
- Mean radius, perimeter, area, smoothness
- Texture, compactness, symmetry, fractal dimension

---

## 📊 Key Visualizations

| Type                        | Insight |
|-----------------------------|---------|
| 📈 **Count Plot**            | Distribution of benign vs malignant |
| 🔥 **Correlation Heatmap**   | Strength of relationships between features |
| 🧬 **Pairplot**              | Visualize pairwise feature relationships |
| 📦 **Boxplots**              | Spot outliers and compare spread |
| 📉 **Distribution Plots**    | Understand shape, skewness, and spread of data |
| 📤 **Feature Reduction**     | Identify redundant or highly correlated features |

---

## 🧠 EDA Breakdown

1. **Data Inspection**
   - Checked nulls, data types, statistical summaries
   - Cleaned `Unnamed: 32` column and ID field

2. **Target Analysis**
   - Diagnosis imbalance checked using count plots

3. **Correlation Matrix**
   - Identified strong correlations between radius, perimeter, and area
  
     ![Sightings Overview](https://github.com/AMMAR1122-LG/Sightings_PowerBI_Dashboard/blob/main/images/Sightigs%20Dashboad.png)

4. **Boxplots & Distributions**
   - Spotted outliers in radius and texture
   - Observed skewness in symmetry and fractal dimensions

5. **Feature Engineering Ideas**
   - Highlighted potential redundant features for ML pruning
   - Proposed normalization and scaling for future modeling

---

🔗 **GitHub**: [(https://github.com/AMMAR1122-LG)]
🔗 **LinkedIn**: [(https://www.linkedin.com/in/muhammad-ammar-zahid-b91124268/] 
