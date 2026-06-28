# MediCare Health Network | Hospital Readmission Risk Intelligence

## Project Overview
This project is based on the pre-submission document for the IITM Group 21 CPS Project 1, Domain 1: Healthcare Analytics. The objective is to build a data-driven solution for predicting and managing hospital readmissions in the MediCare Health Network.

## Problem Statement
Hospital readmission rates are increasing and creating financial, operational, and patient-care challenges. Readmissions lead to higher treatment costs, increased pressure on hospital resources, lower patient satisfaction, and possible regulatory penalties. The project aims to identify patients at high risk of readmission before discharge so that timely interventions can be applied.

## Business and Analytical Objectives
- Identify patients at high risk of readmission at the point of discharge.
- Segment patients into risk groups such as High, Medium, and Low risk.
- Predict individual readmission risk using machine learning models.
- Provide actionable business recommendations based on data-driven insights.

## Proposed Solution Approach
The project follows an analytical workflow that combines both unsupervised and supervised learning methods:

1. Data Understanding and Exploratory Data Analysis (EDA)
2. Dimensionality Reduction using PCA and LDA
3. Unsupervised Clustering using K-Means
4. Classification using Logistic Regression, Decision Tree, KNN, and Naive Bayes
5. Model Evaluation and Selection
6. Business Recommendations and Visualization

## Expected Deliverables
- Data analysis report
- Dimensionality reduction analysis
- K-Means cluster profiles
- Machine learning classification models
- Model evaluation report with confusion matrices, ROC curves, and AUC scores
- Business recommendations for targeted interventions
- Dashboard or visualization summary
- Deployment proposal for clinical workflow integration
- Technical documentation and reproducible notebooks
- Final presentation

## Team Information
- Team: Group 21
- Domain: Healthcare Analytics
- Date: June 2026

## Software and Tools Required
The following software and tools are recommended for this project:

### Core Software
- Python 3.10 or higher
- Jupyter Notebook or JupyterLab
- Visual Studio Code (recommended IDE)
- Git for version control

### Python Libraries
Install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy plotly jupyterlab
```

### Optional Tools
- Microsoft Excel or LibreOffice for data review and reporting
- Power BI or Tableau for dashboard creation (if needed)

## Setup Instructions
1. Install Python and ensure pip is available.
2. Open the project folder in Visual Studio Code.
3. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

4. Install the required libraries using the command above.
5. Launch Jupyter Notebook or JupyterLab to begin analysis.

## Notes
This README is prepared from the pre-submission document and can be expanded as the project progresses with notebooks, reports, and implementation files.
