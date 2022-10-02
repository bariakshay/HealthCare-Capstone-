# Healthcare Project

Step 1:- Performing Descriptive Analysis to get insight and understanding variable of data.
        1. There is 768 observations of 9 variable. Independent variables are Pregnencies ,
        Glucose, BloodPressure, Insulin, BMI and DiabetesPedigree Function. Age is
        Outcome Variable. Average Age of Patients are 33.24 with minimum being 21 and
        maximum 81. Avg. value of independent variables are Preg = 3.845052,Glucose =
        120.894531, BP = 69.105469, ST=20.536458, Insulin = 79.799479, BMI = 31.992578
        DPF = 0.471876
        2. All zeros values are replace with mean of this Variable.
        
Step 2:- Data Exploration
        1. Creating Count Plot. SO Here we can see that both the outcome i.e 0 & 1 is seen to be
        Balanced. So we can used this data to for training a model.
        2. Creating Scatter Plot. We can see from scatter plot that there is no strong
        multicolinearity among features, but between skin thickness and BMI, Pregnancies
        and age it looks like there is small chance of positive correlation..i will explore more
        when analyzing correlation
        3. Performing Corelation Analysis.So here we get insight,Glucose and BMI has strong
        impact on the Outcome. There is a strong positive correlation between BMI and
        Skinthickness or Pregnancies and age
        
Step 3:- Data Modeling
        1. Predicted outcome using multiple module i.e. KNN, SVM, Logistic Regression,
        Random Forest Classification by standarizing the data.
        2. The Random Forest module look better because it has better accuracy score=83%
        and AUC Score=87% of Forest module Classifier module as compare to KNN
        module,Logistic Regression & Support vector machine. It has better balanced of
        classes between precision,recall,f1-score as compared to other model. So we choose
        Random Forest Classifier best fit module.
        
Step 4:- Data Reporting
        1. Create a tableau Dashboard to understand the data correlation and analyze the data
        distribution
