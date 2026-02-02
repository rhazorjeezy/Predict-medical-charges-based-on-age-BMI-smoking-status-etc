Predict Medical Charges

Project Overview
This project focuses on predicting medical insurance charges based on individual attributes such as age, BMI, smoking status, number of dependents, and region**.  
Using machine learning techniques, the goal is to model how these factors influence healthcare costs and to generate accurate cost predictions.

---

Dataset
The dataset contains demographic and health-related information, including:

- **age** – Age of the individual  
- **sex** – Gender  
- **bmi** – Body Mass Index  
- **children** – Number of dependents  
- **smoker** – Smoking status (yes/no)  
- **region** – Residential region  
- **charges** – Medical insurance cost (target variable)

---

Approach
1. **Data Exploration & Cleaning**
   - Handle categorical variables
   - Check for missing values
   - Analyze correlations and distributions

2. **Feature Engineering**
   - Encoding categorical features
   - Scaling numerical features (if required)

3. **Model Training**
   - Regression models such as:
     - Linear Regression

4. **Model Evaluation**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score

---

Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---
Results
The final model demonstrates that smoking status and BMI are the most influential factors in predicting medical charges.  
Ensemble models typically outperform simple linear regression for this dataset.

---

Future Improvements
- Hyperparameter tuning
- Feature interaction analysis
- Deployment as a web application
- Testing additional regression models

