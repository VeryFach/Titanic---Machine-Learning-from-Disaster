# Titanic - Machine Learning from Disaster

## 📌 Overview  
This project is my participation in the **Titanic - Machine Learning from Disaster** competition on Kaggle. The main objective is to build a predictive model that determines whether a passenger survived or not based on various features such as age, gender, and socio-economic class.

## 📊 Dataset  
The dataset used in this project consists of:  
- **train.csv**: Training data with the `Survived` label.  
- **test.csv**: Test data without labels that need to be predicted.  
- **gender_submission.csv**: Example submission format.  

## 🔍 Data Exploration & Preprocessing  
Key steps performed during data exploration and preprocessing:  
✔️ **Handling missing values** in features such as `Age`, `Cabin`, and `Embarked`.  
✔️ **Converting categorical features** such as `Sex` and `Embarked` into numerical values.  
✔️ **Creating new features** to improve model accuracy.  
✔️ **Normalization & encoding** to prepare data for modeling.  

## 🤖 Models Tested  
Several machine learning models were tested:  
- **Logistic Regression**  
- **Random Forest**  
- **Gradient Boosting (XGBoost, LightGBM, CatBoost)**  
- **Support Vector Machine (SVM)**  
- **Neural Network (MLPClassifier)**  

Hyperparameter tuning was performed to enhance model accuracy. The best-performing model so far is **[your best model]** with an accuracy of **[best accuracy score]** on the Kaggle leaderboard.  

## 📤 Submission  
Predictions are made in CSV format with the following structure:  
```
PassengerId,Survived  
892,0  
893,1  
894,0  
```
The final results are then submitted to Kaggle for accuracy evaluation.  

## 📚 Resources & References  
- [Titanic Competition - Kaggle](https://www.kaggle.com/competitions/titanic)  
- Kaggle notebooks and discussion forums  
- Documentation from Scikit-Learn, Pandas, and Matplotlib  

## 🚀 Next Steps  
- **Improve model accuracy** through further feature engineering.  
- **Experiment with ensembling methods** such as stacking and blending for better results.  
- **Explore deep learning approaches** as an alternative method.  
