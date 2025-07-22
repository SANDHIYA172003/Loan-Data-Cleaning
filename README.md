## ✨PROJECT TITLE Loan Default Prediction using Python, EDA & Machine Learning
![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/SCKIT%20LEARN-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)
![Seaborn](https://img.shields.io/badge/SEABORN-3772A3?style=for-the-badge&logo=seaborn&logoColor=white)
        
        This project aims to predict the likelihood of a loan applicant defaulting using machine learning models. It involves data cleaning, exploratory data analysis (EDA), model building, and final model deployment.

## 📁 Project Structure

loan-default-prediction
│
├── dataset
│   └── "test1.csv"
│   └── "train1.csv"
│   
├── notebooks
│   ├── 1_"datacleaning1.ipynb"
│   ├── 2_"EDA process.ipynb"
│   └── 3_"ML.ipynb"
│   └── 4_"submission.ipynb"
│
│
├── models
│   └── "final_model.pkl"
│
│
├── PPT
│   └── Final_Presentation.pptx
│
├── README.md
└── requirements.txt


## 📊 Dataset

- **Source**: Provided by instructor
- **Description**: Includes loan applicant details such as income, credit history, education, etc.


## 🧹 1. Data Cleaning

- Removed duplicates and handled missing values
- Converted categorical variables to numerical using label encoding and one-hot encoding
- Dropped irrelevant columns

## 📈 2. Exploratory Data Analysis (EDA)

- Visualized distributions of loan amount, applicant income, and credit history
- Explored correlations between variables and default status

## 🤖 3. Model Building

- Used **Logistic Regression** and **Decision Tree** classifiers
- Evaluated models using accuracy, confusion matrix, classification report
- Final model exported as 'final_model.pkl

## 🧪 Model Performance

- Accuracy (Logistic Regression): ~81%
- Accuracy (Decision Tree): ~79%

## 💾 Final Output

- 'final_model.pkl': Trained ML model for deployment
- 'Final_Presentation.pptx': Summary presentation
- '3_model.ipynb': Full training notebook
