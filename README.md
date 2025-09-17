# 🚢 Titanic Survival Data Analysis

This mini-project explores the **Titanic: Machine Learning from Disaster** dataset using Python.  
by analyzing survival patterns with data cleaning, feature engineering, and visualizations.


## 📊 Features of the Project
- Clean missing values (Age, Fare, Embarked).
- Engineer new features:
  - **FamilySize** → `SibSp + Parch + 1`
  - **IsAlone** → binary feature for passengers traveling alone
  - **Title** → extracted from names (Mr, Mrs, Miss, Rare titles)
  - **Cabin_known** → whether cabin info is available
- Group-based insights (survival by gender, class, embarkation, title, family size).
- Visualization with **Seaborn & Matplotlib**.


## Dataset
The dataset used is the **Titanic dataset from Kaggle**:  
 [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)


## 🛠️ Technologies Used 
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
