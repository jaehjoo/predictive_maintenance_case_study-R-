## 🏭 Predictive Maintenance Case Study (R)
## 📌 Overview
This project presents an end-to-end predictive maintenance case study
using manufacturing sensor data.
The goal is to identify key operational factors driving machine failure
and to support data-driven, condition-based maintenance decisions.

## 🎯 Business Problem
Unexpected machine failures in manufacturing environments cause
production downtime and increased maintenance costs.

### Key question:
**Which operational and sensor variables most strongly contribute to machine failure?**

## 📊 Dataset

### Source
AI4I 2020 Predictive Maintenance Dataset (Kaggle)

### Description
Simulated manufacturing sensor data reflecting realistic industrial conditions

### Target Variable
machine_failure (0 = No failure, 1 = Failure)

### Key Features
Air temperature, Process temperature, Rotational speed, Torque, Tool wear, Product type

## 🛠️ Methodology
Data cleaning and preprocessing using tidyverse

Exploratory Data Analysis (EDA) to identify failure patterns

Logistic Regression for interpretable failure modeling

Evaluation using:

Confusion Matrix

ROC Curve & AUC

Threshold trade-off (Recall vs Precision)

## 📈 Key Findings
Tool wear and torque are the strongest drivers of machine failure.
Failure events are highly imbalanced, making accuracy alone misleading.
Lowering the classification threshold significantly improves failure recall,
which is critical in predictive maintenance.

## 🔧 Business Recommendations
Implement condition-based maintenance using tool wear thresholds.
Monitor torque spikes as early indicators of mechanical stress.
Prioritize recall over accuracy to reduce the risk of unexpected downtime.

## 📄 Report
📘 Full analysis report (HTML):
👉 analysis.html
(Generated using R Markdown for reproducibility)

## 🧰 Tools & Technologies
R, tidyverse, ggplot2, pROC, R Markdown

### ✅ Key Takeaway
This case study demonstrates how manufacturing sensor data can be
leveraged to identify key drivers of machine failure and support
data-driven, condition-based maintenance strategies.
Interpretable statistical models enable actionable insights for
operational decision-making.

## 🔗 Author
JaeHo Joo, Aspiring Manufacturing Data Analyst
