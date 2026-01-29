# People Analytics for Employee Behavior Profiling

## Project Overview
This project applies **People Analytics** to profile employee work behavior using **clustering methods** and to identify key behavioral determinants affecting performance.  
The analysis combines **unsupervised learning** (K-Means and Hierarchical Clustering) for behavior profiling and **supervised learning** (Random Forest and Lasso Regression) to determine the most influential behavioral dimensions.

The dataset originates from internship activities as a **Data Analyst**.

## Objectives
- Profile dominant employee work behavior patterns using clustering techniques
- Determine the optimal number of employee behavior clusters
- Compare K-Means and Hierarchical Clustering results
- Identify key behavioral dimensions influencing final work behavior performance
- Provide data-driven insights to support human resource evaluation in the public sector

## Data Description
The dataset consists of employee behavior assessment records with variables including:
- Behavioral performance indicators (integrity, commitment, teamwork, leadership, service orientation, communication, self-development, decision-making, and national cohesion)
- Final work behavior score
- Monthly observation period (January–July) 2025

> Raw and confidential data are **not included** in this repository.

## Installation
Install required libraries using:
```bash
pip install -r requirements.txt
```

## Methodology
- Data cleaning and preprocessing
- Feature selection and aggregation of behavioral indicators
- Data standardization and outlier handling using IQR-based winsorization
- Dimensionality reduction using Principal Component Analysis (PCA)
- Determination of optimal number of clusters using Elbow Method and Silhouette Score
- Employee behavior profiling using:
  - K-Means Clustering
  - Hierarchical Clustering
- Cluster evaluation using Silhouette Score
- Identification of key behavioral determinants using:
  - Random Forest Regression
  - Lasso Regression
- Statistical assumption testing:
  - Normality
  - Homoskedasticity
  - Multicollinearity

## Results Summary
- Optimal number of clusters identified: **k = 3**
- Silhouette Score for both K-Means and Hierarchical Clustering: **0.8290**
- Employee behavior profiles identified:
  - **Excellent Work Behavior**
  - **Stable Work Behavior**
  - **Needs Development**
- Random Forest model achieved strong predictive performance:
  - **R² Test: 0.967**
- Most influential behavioral dimensions include:
  - Integrity
  - Decision-making
  - Service orientation
  - National cohesion
- Lasso Regression confirmed consistent feature importance with minimal prediction error

## Policy Implications
The findings support:
- Evidence-based employee performance evaluation
- Targeted behavioral development programs for employees
- Strengthening integrity- and decision-making-oriented human resource policies
- Adoption of people analytics approaches in public sector workforce management

## Disclaimer
This project was developed as part of a **Data Analyst internship in the public sector**.  
All data used in this repository has been **anonymized or modified** for educational and portfolio purposes.  
No confidential, sensitive, or personally identifiable information is disclosed.

## Author
Bunga Aprilian
