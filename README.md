# Senior-Project
**CREDIT CARD FRAUD DETECTION USING MACHINE LEARNING**

## Project Overview
This repository contains a Machine Learning (ML) pipeline designed to detect fraudulent credit card transactions in real-time. The project addresses the critical challenge of highly imbalanced datasets—where fraudulent transactions account for less than 0.2% of all data —to deliver a solution that is accurate, interpretable, and scalable.
The primary goal is to minimize financial losses, which are projected to reach $49 billion by 2027 globally , by efficiently spotting rare fraud cases that traditional systems often miss.

**Objectives**
The project focuses on building a robust, production-ready prototype by achieving the following specific objectives:
1.	Data Preprocessing & Imbalance Handling: To collect, clean, and analyze historical credit card data, specifically applying techniques to handle the severe class imbalance.
2.	Model Building & Evaluation: To build and evaluate multiple machine learning models (including Logistic Regression, Random Forest, XGBoost, and Isolation Forest) and compare their performance using metrics suited for imbalanced data.
3.	Automated Pipeline Implementation: To implement an automated fraud detection pipeline that integrates the best-performing model for simulated real-time prediction, visualization, and interpretability.

**Research Questions**
- How do data preprocessing and resampling techniques improve fraud detection performance on imbalanced datasets?
- Which machine learning model best balances precision, recall, F1-score, and ROC-AUC?
- Can an automated pipeline achieve real-time fraud detection with interpretable results suitable for financial decision-making?

## Methodology

The project follows a quantitative experimental design using the publicly available Kaggle Credit Card Fraud Detection Dataset containing 284,807 transactions, of which only 0.17% are fraudulent.

**Workflow:**
- Data Loading and Cleaning: Using pandas to import and process anonymized transaction data.
- Feature Engineering: Creating time-based and frequency-based features to improve model performance.
- Resampling: Applying SMOTE, under-sampling, and hybrid methods to balance the dataset.
- Model Training: Logistic Regression, Random Forest, XGBoost and Isolation Forest.
- Evaluation Metrics: Precision, Recall, F1-score, and ROC-AUC.
- Visualization: Confusion matrices, ROC curves, and feature importance plots using matplotlib and seaborn.
- Pipeline Automation: Implementing scalable batch prediction and visualization with Apache Spark for near real-time fraud detection.

**Tools & Technologies**
- Programming Language: Python
- Libraries: Scikit-learn, Imbalanced-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- Data Source: Kaggle Credit Card Fraud Detection Dataset for a real-world imbalanced scenario (284,807 anonymized transactions).
- Environment:	Jupyter Notebook / Google Colab

## Expected Contributions

This project is expected to deliver valuable contributions to both data science research and industry practice:
- End-to-End Template: Providing a reusable automated pipeline template for financial institutions to integrate ML effectively into their fraud detection workflows.-
- Practical Model Benchmarks: Offering a practical comparison of model performance (Logistic Regression, Random Forest, XGBoost) using different resampling strategies on skewed financial data.
- Actionable Insights: Generating detailed feature importance reports to make the fraud detection system easier to explain and justify.
- Focus on Cost-Effectiveness: Emphasizing interpretable and affordable methods using open-source tools, providing an accessible solution for institutions of all sizes.

## Ethical Considerations

- Data Privacy: The dataset is fully anonymized and GDPR-compliant.
- No Human Subjects: The research uses pre-labeled, publicly available data.

## Research Contribution

This project contributes to both academia and industry by:
- Demonstrating effective handling of class imbalance in financial data.
- Providing a transparent and interpretable alternative to deep learning systems.
- Offering a low-cost, open-source prototype for institutions seeking scalable fraud detection.


## Dataset Access

Due to GitHub’s 100 MB file size limit, the dataset used in this project is available on Kaggle.

[Download Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
