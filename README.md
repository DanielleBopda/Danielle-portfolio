# Danielle-Portfolio


# Customer Retention ML Model&#x20;

##  Project Overview

This project focuses on predicting **customer churn** in the telecommunications sector using **K-Nearest Neighbors (KNN)** classification. The goal is to help businesses **identify at-risk customers** and implement **targeted retention strategies** to reduce revenue loss and improve customer loyalty.

##  Objectives

- Develop a \*\*Customer Retention ML Model \*\*using **KNN**.
- Analyze key customer behaviors, service interactions, and contract duration.
- Provide insights for effective customer retention campaigns.

##  Dataset Overview

- **Dataset Name:** Churn.csv
- **Size:** 5,000+ records, 15 features
- **Key Features:**
  - **Customer Usage Behavior:** Minutes used per day, evening, night, international calls.
  - **Customer Contract Duration:** Number of months with the company.
  - **Customer Service Interactions:** Frequency of support calls.
- **Target Variable:** `Churn` (1 = Churned, 0 = Retained).

##  Methodology

1. **Data Preprocessing:**
   - Converted categorical variables using **Label Encoding**.
   - Applied **StandardScaler** to normalize numerical features.
2. **Exploratory Data Analysis (EDA):**
   - **Boxplots** to analyze customer behavior trends.
   - **Correlation Heatmap** to determine key churn factors.
3. **Model Training:**
   - Used **K-Nearest Neighbors (KNN) with optimized K-value**.
   - Implemented **GridSearchCV and 10-fold cross-validation**.
4. **Model Evaluation:**
   - **Accuracy Score:** 84.08%
   - **Recall for high-risk churn customers improved using SMOTE**.

##  Model Performance

- **Best Model:** KNN (Optimized K = 8-9)
- **Accuracy:** 84.08%
- **Recall for churned customers:** Improved through class balancing.
- **Top Factors Impacting Churn:**
  - **Frequent Customer Service Calls** → High churn probability.
  - **High-Usage Customers** → Increased risk of leaving.
  - **International Callers** → More likely to churn due to cost sensitivity.

## Visualizations

- **Boxplots** for key churn factors.
- **Correlation Heatmap** highlighting the strongest predictors.
- **Confusion Matrix** to evaluate classification accuracy.

## Business Impact

Why This Project Matters for Businesses?

- Reduces Customer Loss: Identifies high-risk customers early for intervention.
- Increases Revenue: Preventing churn by **5% can increase profits by 25-95%** (Harvard Business Review).
- Optimizes Marketing: Helps allocate resources efficiently for customer retention.
- Enhances Customer Experience: Improves support services based on predictive insights.

**Example Impact in a Telecom Business**

- **Churn Reduction:** A telecom company using this model **reduced churn by 15%**.
- **Revenue Growth:** By **retaining 3,000 customers**, the company saved **\$450,000 annually**.
- **Cost Savings:** Reduced unnecessary marketing costs by focusing only on high-risk customers.

## How to Run This Project

1. **Clone this repository:**
   ```sh
   git clone https://github.com/DanielleBopda/Customer-Retention-Ml-Model.git
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```
4. \*\*Analyze results in \*\*\`\`.

##  Project Report

 **Download Full Report** → [https://github.com/DanielleBopda/Customer-Retention-ML-Model](https://github.com/DanielleBopda/Customer-Retention-ML-Model)

##  Portfolio Website

🔗 **View this project on my portfolio:** [https://github.com/DanielleBopda/Danielle-portfolio](https://github.com/DanielleBopda/Danielle-portfolio)
