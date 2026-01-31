customer-segmentation
Overview
This project implements a data-driven customer classification system for the wholesale and retail distribution domain. The objective is to automatically segment customers into HORECA (Hotels, Restaurants, Cafés) and Retail Stores based on historical purchase data across product categories such as fresh food, dairy, groceries, frozen items, detergents, and delicatessen products.

Manual segmentation becomes challenging as transaction volumes grow. This system aims to improve marketing targeting, inventory planning, and overall business efficiency.

Dataset
Dataset Name: Wholesale Customers Dataset

Source: UCI Machine Learning Repository

Data Type: Structured, continuous numerical data

Features:
Fresh

Milk

Grocery

Frozen

Detergents_Paper

Delicatessen

Channel (HORECA vs Retail)

Region

Steps Performed
1) Data Cleaning
Checked for missing values and duplicates

Validated feature types

Handled outliers

2) Exploratory Data Analysis (EDA)
Visualized distributions using histograms, boxplots, and pairplots

Studied feature correlations and patterns across customer segments

EDA was performed using my custom data analysis web application, which allows interactive exploration and visualization of datasets

3) Modeling
Built a Gaussian Naive Bayes classifier using pipeline
4) Evaluation
Metrics: Accuracy, Precision, Recall, F1-score

Confusion Matrix to identify misclassifications

Achieved ~91% accuracy

Business Impact
Automated segmentation of customers improves scalability

Enables targeted marketing campaigns

Helps optimize inventory and reduce misclassification risk

Provides insights to enhance customer engagement and ROI

This project was completed under the guidance of @Mohit Payasi, whose mentorship was invaluable in shaping both the technical and business aspects of this work.

To run this project, install the required packages:

pandas

numpy

matplotlib

seaborn

scikit-learn
