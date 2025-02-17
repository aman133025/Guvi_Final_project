Loan Default Prediction 📊

🚀 This project predicts the likelihood of a borrower defaulting on a loan using machine learning models.

📌 Project Overview

Problem Statement: Financial institutions face high risks when borrowers default on loans. This leads to financial losses and inefficient credit allocation.

Solution: Develop a machine learning model to predict loan defaults based on borrower information, enabling lenders to make informed decisions.

🔍 Dataset

Source: [Dataset Link if available]

Number of records: 10,000

Features:

Age 🏆

Income 💰

Credit Score ✅

Loan Amount 💵

Interest Rate 📈

Loan Duration ⏳

Employment Status 💼

Debt-to-Income Ratio 🔢

Existing Loan Balance 💳

Target Variable: default (1 = Default, 0 = No Default)

🛠️ Preprocessing Steps

✅ Handled missing values in Gender and Employment Status✅ Encoded categorical variables using One-Hot Encoding✅ Scaled numerical features using StandardScaler✅ Addressed class imbalance using SMOTE & Class Weights

🤖 Model Selection & Performance

Model

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Logistic Regression

85%

78%

82%

80%

89%

Random Forest (Best)

92%

89%

98%

93%

98%

📊 Key Findings

Higher Loan Amount & Longer Duration increase default risk.

Low Credit Scores (<600) are strong indicators of default.

Higher Interest Rates show a moderate correlation with default.

Income levels impact repayment capacity, with lower-income borrowers defaulting more often.

🔧 How to Run

1️⃣ Clone this repository

git clone https://github.com/your-username/machine-learning-projects.git
cd machine-learning-projects/Project_1_Loan_Default

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook

🚀 Deployment

Model saved as loan_default_model.pkl

Flask API built for real-time predictions

Can be integrated into a banking risk management system

📄 License

This project is open-source under the MIT License.

💡 Future Enhancements

Improve feature selection for better model performance

Integrate external economic indicators (e.g., inflation rates)

Deploy the model on cloud platforms (AWS, GCP) for real-time use

