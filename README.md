# Comparative Need State Analysis for Ride-Hailing Platforms: A Case Study on PickMe and Uber

## 🚖 Project Overview
This project is a **Comparative Need State Analysis** of **ride-hailing customers** in Colombo, Sri Lanka, focusing on **PickMe and Uber**.  
The primary goal is to segment customers based on their behaviour and **help ride-hailing companies**:
- Identify different customer segments.
- Optimize marketing strategies.
- Improve customer retention and engagement.

This project is part of my **Final Year Project (FYP)** for the **BSc (Hons) in Data Science and Analytics** at the **University of Westminster**.

---

## 🎯 Objectives
- **Understand customer needs** for using PickMe and Uber.
- **Preprocess survey data** (collected in both **English & Sinhala**).
- **Perform clustering (K-Modes)** to group similar users.
- **Evaluate clusters** using multiple techniques.
- **Generate insights** to help ride-hailing businesses optimize their services.

---

## 📊 Dataset Overview
- The dataset was collected via **two surveys**: **English & Sinhala**.
- **Data Cleaning Steps:**
  - **Removed duplicates & missing values** using exact/partial match imputation.
  - **Translated Sinhala responses manually** for accuracy.
  - **Filtered data** to focus on **Colombo-based users**.

- **Final Processed Data**:
  - 📌 **384 total responses**
  - 📌 **Categorical variables only** (suitable for K-Modes clustering)

---

## 🔧 Installation & Dependencies
To run the Jupyter Notebook, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn kmodes scikit-learn
