# Loan Default Prediction Project  

## 1. Introduction  
This project focuses on predicting loan defaults based on various borrower and loan-related features. A loan default refers to a borrower's inability to fulfill payment obligations, which poses significant risks to financial institutions. By leveraging machine learning, we aim to enhance lending decisions and risk mitigation.  

## 2. Dataset Overview  
The dataset includes both numerical and categorical features:  
- **Numerical Features**: Age, Income, Loan Amount, Credit Score, Months Employed, Number of Credit Lines, Interest Rate, Loan Term, Debt-to-Income Ratio (DTIRatio).  
- **Categorical Features**: Education, Employment Type, Marital Status, Has Mortgage, Has Dependents, Loan Purpose, Has Co-Signer.  
The target variable, `Default`, indicates loan default status (binary classification).  

## 3. Problem Statement  
The project goals include:  
1. Accurately predicting loan defaults using machine learning.  
2. Identifying key factors that contribute to loan defaults.  

## 4. Data Preprocessing  
Data preprocessing steps included:  
- **Exploratory Analysis**: Investigated dataset structure, descriptive statistics, and data types.  
- **Missing Values**: Detected and addressed missing values.  
- **Feature Engineering**: Encoded categorical features (One-Hot Encoding) and analyzed numerical feature correlations, removing redundant features.  
- **Feature Selection**: Used Random Forest feature importance analysis to retain only the most significant variables.  

## 5. Data Transformation  
- **Scaling**: Standardized numerical features using `StandardScaler`.  
- **Encoding**: Applied One-Hot Encoding for categorical variables.  
- **Data Splitting**: Divided data into training (70%) and testing (30%) sets using `train_test_split`.  

## 6. Model Building  
- Trained multiple models, including Logistic Regression, Random Forest, and Decision Tree.  
- Evaluated model performance using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.  
- Conducted feature significance analysis to identify influential predictors.  

## 7. Conclusion  
This project aims to:  
1. Build a robust loan default prediction model.  
2. Highlight key features driving default risks.  
3. Deliver actionable insights for financial institutions to improve lending strategies and mitigate risk.  


