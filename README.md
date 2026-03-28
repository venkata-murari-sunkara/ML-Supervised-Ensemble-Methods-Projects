# Supervised Machine Learning & Ensemble Methods

This repository contains end-to-end predictive machine learning projects focusing on exploratory data analysis (EDA), feature engineering, hyperparameter tuning, and business-driven model deployment.

## Tech Stack
* **Languages:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Techniques:** Classification, Ensemble Methods, Oversampling/Undersampling (SMOTE), Hyperparameter Tuning

---

## Projects

### 1. Predicting Hotel Booking Cancellations (INN Hotels Group)
* **Dataset:** 36,275 booking records
* **Objective:** Built predictive classification models to determine cancellation likelihood based on customer demographics, pricing behavior, and booking patterns.
* **Techniques:** EDA, Feature Engineering, Logistic Regression, Decision Trees.
* **Key Results:** Achieved **87% model accuracy**. Optimized ROC thresholds and feature selection, generating actionable business recommendations projected to reduce cancellations by 15% and increase revenue by 10%.

### 2. Visa Approval Prediction (EasyVisa)
* **Dataset:** 25,480 visa applications
* **Objective:** Architected machine learning models to predict whether a visa application will be 'Certified' or 'Denied' based on employer characteristics, wages, and applicant demographics.
* **Techniques:** Data Preprocessing, Class Imbalance Handling (Oversampling/Undersampling), Ensemble Modeling, Hyperparameter Tuning.
* **Key Results:** Evaluated multiple supervised learning and ensemble models, selecting a tuned AdaBoost classifier trained on oversampled data (SMOTE), which achieved a 79.1% F1-score and 82.4% recall. Feature importance analysis revealed that prevailing_wage, company establishment year, and company size were the strongest positive predictors of visa certification. Delivered strategic recommendations to integrate the model into the application review pipeline as a decision support tool to prioritize high-certainty approvals.

---

## How to Run
1. Clone this repository.
2. The datasets (`INNHotelsGroup.csv`, `EasyVisa.csv`) are included in the root directory.
3. Open the `.ipynb` files in Jupyter Notebook or Google Colab to view the code and execution states.
4. Refer to the included PDF Business Reports for comprehensive stakeholder presentations and strategic recommendations.
