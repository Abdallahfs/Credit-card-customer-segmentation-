# Credit Card Customer Segmentation

## Overview
This project focuses on developing a **customer segmentation model** using **K-Means clustering**. By analyzing the behavioral data of over 9,000 active credit card holders across 18 variables, this model identifies distinct customer segments to enable targeted marketing strategies.

## Objectives
- **Segment** customers based on their credit card usage behavior.
- **Provide actionable insights** to support personalized marketing campaigns.

## Methodology
1. **Data Preprocessing**:
   - Cleaned and handled missing data.
   - Standardized features using **StandardScaler** for uniform scaling.

2. **Feature Reduction (PCA)**:
   - Reduced dimensionality for visualization while retaining maximum variance.

3. **Clustering with K-Means**:
   - Used the **Elbow Method** to determine the optimal number of clusters.
   - Applied **K-Means clustering** to group customers into distinct segments.

4. **Evaluation and Insights**:
   - Visualized clusters in a **2D PCA-reduced space**.
   - Analyzed cluster-specific characteristics to derive marketing insights.

## Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **K-Means Clustering**
- **Principal Component Analysis (PCA)**

## Outcomes
- Identified **3 unique customer segments** with distinct spending and usage patterns.
- Derived **insights** for better customer engagement and optimized marketing strategies.
- Demonstrated the power of **data-driven decision-making** in customer management.
