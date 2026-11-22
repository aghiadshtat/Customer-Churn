Customer Churn Prediction

A machine learning project focused on predicting customer churn using two different customer churn datasets.

The project explores data preprocessing, feature engineering, and model comparison to understand how different machine learning algorithms perform on customer retention prediction.

📊 Datasets

This project uses two datasets:

1. Iranian Customer Churn Dataset

- File: "Customer Churn.csv"
- Dataset containing customer information and churn labels.
- Used to explore and compare machine learning models on a numerical dataset.

2. IBM Telco Customer Churn

- File: "WA_Fn-UseC_-Telco-Customer-Churn.csv"
- Contains customer demographics, subscribed services, account information, and churn labels.
- Includes both numerical and categorical features.

Dataset source links:

- Iranian Customer Churn: [Add original dataset source]
- IBM Telco Customer Churn: [Add original dataset source]

🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

🔍 Project Workflow

1. Load and inspect the datasets.
2. Explore the data and examine feature distributions.
3. Split the data into training and validation sets.
4. Handle missing values.
5. Apply preprocessing:
   - "StandardScaler" for numerical features.
   - "OneHotEncoder" for categorical features.
6. Build machine learning pipelines.
7. Train and compare multiple models.
8. Evaluate model performance on validation data.

🤖 Models

The following models are evaluated:

- Logistic Regression
- Random Forest Classifier
- HistGradientBoosting Classifier

📈 Evaluation

Models are compared using validation accuracy.

Additional evaluation metrics may be used to investigate performance on imbalanced classes, including:

- Precision
- Recall
- F1-score
- ROC-AUC

📁 Project Structure

Customer-Churn-Prediction/
│
├── datasets/
│   ├── Customer Churn.csv
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn.ipynb
│
├── README.md
└── requirements.txt

🎯 Objective

The goal of this project is to develop a practical understanding of machine learning workflows for customer churn prediction, with particular emphasis on preprocessing pipelines, categorical encoding, and model evaluation.

🚧 Project Status

Currently in development.