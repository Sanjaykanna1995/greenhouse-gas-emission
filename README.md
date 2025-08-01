📥 Data Loading: Imported Excel data for 2010–2016

🧹 Data Cleaning: Removed irrelevant columns, handled nulls

🔁 Encoding: Converted categorical data (Substance, Unit, Source) to numeric using LabelEncoder

📊 Visualization: Plotted distributions and relationships using seaborn and matplotlib

📐 Scaling: Used StandardScaler for feature scaling

📤 Data Splitting: Applied train_test_split for model training

🌲 Model Training:

Random Forest Regressor (main model)

Linear Regression and Gradient Boosting (for comparison)

🔍 Hyperparameter Tuning: Used GridSearchCV for the Random Forest model

📈 Model Evaluation: Compared models using RMSE and R² Score

💾 Model Saving: Saved the best model and scaler using joblib
