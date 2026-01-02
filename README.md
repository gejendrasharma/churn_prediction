📉 Customer Churn Prediction

Predicting customer churn using Machine Learning to help businesses retain customers before they leave.

🔍 Project Overview

Customer churn happens when users stop using a product or service. Reducing churn is cheaper than acquiring new customers, which makes churn prediction a high impact business problem.

In this project, we:

Analyze customer behavior

Identify churn drivers

Build ML models to predict churn

Provide actionable business insights

🧠 Problem Statement

Can we predict whether a customer is likely to churn based on their past behavior, usage patterns, and demographic information?

This is treated as a binary classification problem:

1 → Churned

0 → Retained

📊 Dataset Information

Source: Telco Customer Churn Dataset
Target Variable: Churn

Key Features

Customer demographics (Gender, Senior Citizen)

Account information (Tenure, Contract type)

Services used (Internet, Streaming, Phone)

Billing details (Monthly charges, Total charges)

⚙️ Tech Stack

Programming Language: Python

Libraries:

pandas, numpy

matplotlib, seaborn

scikit-learn

Modeling Techniques:

Logistic Regression

Decision Tree

Random Forest

XGBoost (optional)

🧪 Project Workflow
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Business Insights

📈 Exploratory Data Analysis

Some key insights discovered:

Customers with month-to-month contracts churn more

High monthly charges increase churn probability

Longer tenure customers are more loyal

Fiber optic users show higher churn

🧬 Feature Engineering

Converted categorical variables using encoding

Handled missing values

Scaled numerical features

Balanced dataset when required

🤖 Model Building

We trained multiple models and compared performance:

Model	Accuracy	Precision	Recall
Logistic Regression	✅ Good	⭐⭐⭐	⭐⭐⭐
Decision Tree	⚠️ Medium	⭐⭐	⭐⭐
Random Forest	🚀 Best	⭐⭐⭐⭐	⭐⭐⭐⭐
📊 Model Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

ROC-AUC Curve

🏆 Best Model

Random Forest Classifier performed best with:

High recall (important to catch churners)

Strong overall generalization

💡 Business Impact

Using this model, businesses can:

Identify high risk customers

Offer personalized discounts

Improve customer retention

Reduce revenue loss

🚀 How to Run the Project
# Clone the repository
git clone https://github.com/your-username/customer-churn-prediction.git

# Navigate to project folder
cd customer-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook

📁 Project Structure
customer-churn-prediction/
│
├── data/
│   └── churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── models/
│   └── churn_model.pkl
├── README.md
└── requirements.txt

🔮 Future Improvements

Deploy using Flask or FastAPI

Add real-time predictions

Hyperparameter tuning

SHAP values for explainability

Dashboard using Power BI or Streamlit

👤 Author

Gajendra Sharma
Aspiring Data Scientist
📌 Focused on ML, SQL, Python, and Real-World Projects

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork or contribute.

<h1 align="left">Hey 👋 What's up?</h1>

###

<p align="left">My name is ... and I'm a ..., from ....</p>

###

<h2 align="left">About me</h2>

###

<p align="left">✨ Creating bugs since ...<br>📚 I'm currently learning ...<br>🎯 Goals: ...<br>🎲 Fun fact: ...</p>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="nextjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="40" alt="storybook logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="40" alt="nestjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" height="40" alt="jest logo"  />
</div>

###

