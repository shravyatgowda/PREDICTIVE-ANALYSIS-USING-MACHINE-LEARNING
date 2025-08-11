# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHRAVYA T

*INTERN ID*: CT04DZ1893

*DOMAIN*: DATA ANALYSIS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

Task Description

The objective of this Task was to perform predictive analysis using machine learning to forecast outcomes based on historical data. Predictive analysis is a crucial branch of data science that uses statistical and machine learning techniques to make informed predictions about future events. For this task, the goal was to build a supervised learning model — specifically a classification model — to predict whether a customer would churn (leave the company) based on their attributes such as demographics, account details, and usage patterns. The deliverable required the complete workflow: dataset preparation, feature selection, model training, evaluation, and summarizing insights in a Jupyter Notebook.

Task Performed

The project began by preparing a dataset of approximately 10,000 records with realistic features relevant to customer churn prediction. The data contained numerical variables (e.g., credit score, age, account balance, monthly spend, transactions) and categorical variables (e.g., geography, gender), along with a binary target variable (churn).

Exploratory Data Analysis (EDA) was performed to check for missing values, understand the target distribution, and visualize patterns using histograms for key variables such as age and balance.

Preprocessing involved scaling numeric features to standardize their range and encoding categorical features using One-Hot Encoding to make them machine-readable. A feature selection step was applied using SelectKBest (ANOVA F-test) to identify the top predictors influencing churn.

Two models were built and compared:

1. Logistic Regression – a baseline statistical model suitable for binary classification.

2. Random Forest Classifier – an ensemble model that often delivers higher accuracy and robustness.

The Random Forest model underwent a small Grid Search to tune hyperparameters (number of trees and maximum depth). Both models were evaluated using Accuracy, ROC-AUC score, classification report, confusion matrix, and ROC curves.

Results showed that the tuned Random Forest model achieved a higher ROC-AUC score than Logistic Regression, making it the better choice for this dataset.

Tools Used

1. Python – programming language for data analysis and modeling.

2. Pandas – for data manipulation and cleaning.

3. NumPy – for numerical computations.

4. Matplotlib – for visualizations.

5. Scikit-learn – for preprocessing, feature selection, model training, evaluation, and hyperparameter tuning.

6. Joblib – for saving trained machine learning models.

Editor/Platform Used

1. Jupyter Notebook – provided an interactive environment to combine code, explanations, and results in a single document. This setup allowed for clear documentation of each step, making the workflow transparent and reproducible.

Application Areas

The predictive analysis approach demonstrated in this task is widely applicable in real-world scenarios across industries, such as:

1. Banking & Finance – predicting loan defaults, fraud detection, and credit risk scoring.

2. Telecommunications – customer churn prediction to improve retention strategies.

3. Retail & E-commerce – predicting purchase likelihood, customer segmentation, and recommendation systems.

4. Healthcare – predicting disease outcomes or hospital readmission rates.

5. Marketing – forecasting campaign success and lead conversion probability.

This task showcases how machine learning can be applied to structured datasets to make data-driven predictions, ultimately supporting decision-making and improving business performance.

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4793c984-26d9-4146-8e1e-06b53d5aa903" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/258c99cb-344b-4787-85f7-525a6eb6bdfb" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d61139b9-29a5-491b-a4d6-e021647e8faa" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/37ec0454-d1ae-4b6b-b28c-9d8fd9e8a969" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3b826d50-47c2-40d4-abf8-edcc1f922dfe" />


