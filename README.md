# Exploring the Relationship between Risk Factors and Heart Disease: A Data Mining Approach

## Project Overview
This project analyzes heart disease risk factors using **data mining techniques**, specifically **association rule mining** with the **FP-growth algorithm**. The goal is to uncover patterns in a **heart disease dataset** and identify relationships between different attributes to aid in early diagnosis and prevention.

## Scope
- Utilize the **Orange** data mining platform for association rule mining.
- Analyze a **heart disease dataset** to extract meaningful patterns.
- Identify significant relationships between attributes contributing to heart disease risk.

## Dataset
- **Source:** Kaggle
- **Format:** CSV
- **Size:** 540 patient records
- **Attributes:**
  - Age
  - Gender
  - Chest pain type
  - Resting blood pressure
  - Serum cholesterol
  - Fasting blood sugar
  - Heart disease diagnosis (target variable)

## Methodology
1. **Data Preprocessing**
   - Import CSV into Orange.
   - Remove **ID column**.
   - Convert **numeric attributes** (age, blood pressure, cholesterol) into **categorical** values using binning.
   
2. **Descriptive Analysis & Visualization**
   - Use **box plots and feature statistics** to analyze distribution.
   - Detect **outliers**.

3. **Association Rule Mining**
   - Apply **FP-growth** algorithm.
   - Experiment with different **support & confidence** thresholds.
   - Extract association rules to uncover patterns.

## Workflow
Below is the workflow used in **Orange** for data preprocessing, visualization, and association rule mining:
![Workflow](https://github.com/Rehab-Alsaidi/DataMining/blob/main/workflow.png)

## Experiments & Results
- Conducted multiple experiments with varying **support (Min Supp) and confidence (Min Conf)** levels.
- **Key Findings:**
  - Strong **association rules** linking certain factors to **heart disease occurrence**.
  - Insights into risk factors that can aid **prevention & diagnosis**.

## Conclusion
This study demonstrates how **data mining** can identify **hidden relationships** in heart disease risk factors. The **FP-growth algorithm** successfully extracted significant **association rules**, providing insights for **healthcare professionals**. Future work could include:
- **Larger datasets** for improved accuracy.
- **Additional risk factors** for deeper analysis.
- **Alternative algorithms** for comparison.


