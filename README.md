# customer-churn-ml
A machine learning project for predicting customer churn using sentiment analysis

README for GitHub Repository


---

Churn Prediction with Sentiment Analysis

Project Overview

This project combines sentiment analysis of customer reviews and churn prediction to create an integrated system that evaluates customer feedback and predicts churn risk. It serves as a demonstration of my skills in data analysis, machine learning, text processing, and visualization.


---

Features

1. Sentiment Analysis:

Analyzes customer reviews to identify sentiment (positive or negative).

Uses text-processing models such as TF-IDF, Doc2Vec, and VADER.



2. Churn Prediction:

Builds predictive models to determine customer churn risk.

Includes various machine learning models: Random Forest, Gradient Boosting, XGBoost, Neural Networks, and an ensemble model.

Balances imbalanced datasets using SMOTE.



3. Visualization:

Creates an interactive Power BI dashboard.

Visualizes the impact of different factors on churn risk.





---

Repository Structure

churn_prediction_project/
│
├── data/  
│   ├── raw/                  # Raw datasets  
│   ├── processed/            # Preprocessed 
│
├── models/                   # Saved machine learning models  
│   ├── random_forest.pkl  
│   ├── xgboost.pkl  
│   ├── gradient_boosting.pkl  
│
├── notebooks/  
│   ├── sentiment_analysis.ipynb   # Sentiment analysis  
│   ├── churn_prediction.ipynb     # Churn   
├── README.md                # Project documentation  
└── requirements.txt         # Dependency list


---

Technologies Used

1. Python: Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, Matplotlib, Seaborn, NLTK.


2. Power BI: For interactive dashboard visualization.


3. GitHub: For version control.




---

How to Run the Project

1. Clone the Repository:

git clone https://github.com/<your-username>/customer-churn-ml.git
cd churn_prediction_project


2. Install required packages:

pip install -r requirements.txt

3. Run Sentiment Analysis:

Launch the notebooks/sentiment_analysis.ipynb notebook to train and test the sentiment analysis model.

4. Run Churn Prediction:

Open the notebooks/churn_prediction.ipynb notebook to train and evaluate churn prediction models.

5. Visualize in Power BI:

Open notebooks/churn_dashboard.pbix in Power BI to explore the interactive dashboard.


---

Results and Insights

The models achieved high accuracy in predicting customer churn risk.

Sentiment analysis significantly improved prediction quality.

The Power BI dashboard provides an interactive way to analyze the results, offering valuable insights for business decisions.



---

Contact Information

Author: Serhii Bondarenko
Email: 
LinkedIn: 
GitHub: 


---
