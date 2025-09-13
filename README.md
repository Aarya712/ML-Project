# ML-Project
#Reducing Credit Default Rate at a Bank
🎯# Goal
To identify risky customers by analyzing their data, understand their defining characteristics, and recommend suitable actions to help the bank reduce its overall credit default rate.

🏦# Background
ABC Bank is facing the challenge of high credit default rates. One of the bank's key strategies is to proactively identify customers who are likely to default and take targeted measures before a default occurs.

⚙️ # Methodology & Solution Approach
A machine learning model was built following these steps:

Step 1: Loading the Dataset
The dataset is loaded using Python.

The data is checked for missing values and to get information about each feature.

Step 2: Preprocessing and Feature Engineering
The class distribution is checked, revealing that the dataset is imbalanced.

Numerical and categorical features are selected from the dataset.

Exploratory Data Analysis (EDA) is performed on both numerical and categorical data.

Important numerical features are selected using an Extra Trees Regressor and a correlation matrix.

Feature scaling is performed on numerical features using StandardScaler.

Categorical features are selected based on domain knowledge.

Step 3: Performing One-Hot Encoding
One-hot encoding is performed on categorical features, and the dummy variable trap is handled.

Step 4: Handling Imbalanced Dataset
The SMOTE (Synthetic Minority Over-sampling Technique) method is used to balance the dataset.

Step 5: Model Creation
The processed numerical and encoded categorical features are combined.

The data is split into training and testing sets.

Models are created using Logistic Regression, Decision Tree, Random Forest, and XGBoost algorithms.

Step 6: Model Evaluation
The performance of each model is evaluated and compared using accuracy, precision, recall, and F1-score.

🤖# Modeling Techniques Used
Logistic Regression

Decision Tree

Random Forest

XGBoost

More details regarding the models and their implementation can be found in the provided PowerPoint presentation and Jupyter Notebook.

▶️ #Code Execution Steps
Download the dataset (data.xlsx) and the notebook (code.ipynb).

Execute the code.ipynb file to see the results directly in the notebook.

For a summary of the analysis and model results, please refer to the presentation: Analysis_Result_Sakil.pptx.
