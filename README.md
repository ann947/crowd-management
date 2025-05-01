# 👥 Crowd Engagement Analysis with UCF_CC_50 Dataset

This project implements a comprehensive analysis and modeling framework for understanding **crowd behavior and engagement** using the challenging UCF_CC_50 dataset. The work supports intelligent crowd management for large-scale events like **Bradford 2025 UK City of Culture**.

---

## 📂 Dataset Overview

- **Name**: UCF_CC_50
- **Source**: [Kaggle - UCF Crowd Counting](https://www.kaggle.com/datasets/tthien/ucfcc50)
- **Images**: 50 ultra-dense crowd scenes
- **Annotations**: Over 63,000 human-labeled coordinates
- **Use Case**: Crowd counting and engagement analysis in diverse indoor/outdoor settings

---

## 🔬 Project Objectives

- Estimate crowd **density and engagement**
- Visualize spatial distribution of people
- Compare advanced crowd counting architectures
- Support real-world cultural event planning

---

## 🧪 Key Features

### 📊 Exploratory Data Analysis (EDA)
- Crowd count and density histograms
- Distribution by density levels (low, medium, high)
- Relationships between image size and crowd count
- Visual sample images with annotations and generated density maps

### 📍 Spatial Metrics & Engagement
- Calculated:
  - **Dispersion**
  - **Clustering**
  - **Central tendency**
  - **Edge density**
- Computed a **normalized engagement score**
- Visualized spatial behavior vs. crowd count

### 🧠 Modeling Approaches
- **Density map generation using Gaussian kernels**
- Multiple deep learning architectures:
  - Baseline CNN
  - Multi-Column CNN (MCNN)
  - CSRNet-inspired dilated CNN
  - VGG16-based transfer learning model

### 📈 Results & Analysis
- Evaluation metrics: MAE, RMSE, R²
- 5-fold cross-validation
- Cluster analysis for discovering behavior patterns
- Correlation heatmaps of engagement and spatial features

---

## 📌 Summary of Findings

- **Engagement** was more correlated with spatial metrics than raw crowd count
- Identified 4 distinct crowd types using KMeans clustering
- Found ideal crowd patterns for cultural events: high clustering, central focus, low edge density
- Proposed experiment design for real-time crowd assessment tools

---

## 🚀 How to Use

1. Open the notebook in **Kaggle** or **JupyterLab** with access to the UCF_CC_50 dataset.
2. Run all cells in order.
3. Review output charts, metrics, and model predictions.
4. Modify parameters for your own experimentation.

---

## 📁 File Structure

📦 crowd-engagement/ 
┣ 📜 crowd-engagement.ipynb # Main notebook 
┣ 📄 Readme.md # Project overview 
┣ 📊 output_plots/ # Saved figures (EDA, clusters, heatmaps) 
  ┗ 📁 ucfcc-dataset/ # Images and annotations (Kaggle input)


---

## 📚 References

- Idrees et al. (2013) — *Multi-source Multi-scale Counting*
- Zhang et al. (2016) — *MCNN for Crowd Counting*
- Li et al. (2018) — *CSRNet: Dilated CNNs*
- Sindagi & Patel (2022) — *Survey on Crowd Analysis*
- Liu et al. (2023) — *Crowd Engagement Metrics*

---

## 🛠️ Future Improvements

- Incorporate real-time video stream analysis
- Expand dataset with modern surveillance footage
- Deploy models in an edge-compatible pipeline for live crowd estimation

---

## ✍️ Author

This work was created as part of the **COS7045-B Advanced Machine Learning** assessment project on **crowd analysis and engagement modeling**.
