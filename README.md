 ## 🥗 Calorie Burn Prediction

A simple machine learning project to predict calories burned during a workout

## 🏁 Problem Statement
Given a dataset with features like Age, Gender, Height, Weight, Duration, etc., the task is to predict the Calories burnt. 
The evaluation metric is Root Mean Squared Logarithmic Error (RMSLE).

## 📁 Project Structure

```
calorie-burn-prediction/
│
├── notebooks/
│   └── eda                      # Exploratory Data Analysis
|   └── model_training_calorie   # Model building and evaluation
|
├── models/
│   └── best_model.pkl            # Trained ML model
|   └── linear_reg.pkl
│
└── README.md                    # Project overview
```

 ## Key Steps

📦 Data loading 

🔍 Exploratory Data Analysis (EDA)

⚙️ Feature engineering

🔄 One-Hot Encoding for categorical features (Sex)

⚒️ Model training with:

  Linear Regression
  
  Gradient Boosting Regressor
  
🔍 Hyperparameter tuning with GridSearchCV

📈 Evaluation using RMSLE


## 🚀 Model Performance

       Model	                    RMSLE 

Gradient Boosting + GridSearch	     0.07888

Linear Regression	                  0.57401


## 💡 What I Learned

Proper handling of categorical variables using pd.get_dummies
Model evaluation with RMSLE
How GridSearchCV can greatly improve results 
