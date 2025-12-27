# 🏋️‍♂️ Smart Fitness & Nutrition Analysis  
## A Machine Learning Regression Study on Calorie Burn Prediction

---

## Project Description
This project analyzes the relationship between **fitness behavior, physiological indicators, and caloric expenditure** using **econometric and machine learning regression techniques**.  
Using a dataset of **20,000 fitness records with 21 variables**, the study identifies the most influential factors affecting calories burned during workout sessions and builds **accurate yet interpretable predictive models**.

The project applies **OLS regression, Ridge, Lasso, and ElasticNet** to compare traditional statistical modeling with modern regularization techniques, focusing on **feature selection, model optimization, and business interpretability**.

---

## Objectives
- Identify key predictors of calories burned during workouts  
- Analyze relationships between workout duration, heart rate, experience level, and energy expenditure  
- Compare OLS regression with regularized ML models  
- Reduce feature complexity while maintaining predictive performance  
- Generate actionable insights for fitness apps, trainers, and individuals  

---

## Dataset Overview
- **Total Records:** 20,000  
- **Total Features:** 21  
- **Target Variable:** Calories Burned (per workout session)  
- **Data Quality:**  
  - No missing values  
  - No duplicates  
  - Biologically valid ranges  

### Feature Categories
- **Demographics:** Age, Gender  
- **Anthropometric:** Weight, Height, BMI, Fat %, Lean Mass  
- **Cardiovascular:** Max BPM, Avg BPM, Resting BPM, %HRR  
- **Workout Patterns:** Session Duration, Workout Frequency, Workout Type, Experience Level  
- **Metabolic:** Daily Calories, Calories from Macros, Expected Burn  

---

## Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Distribution analysis  
   - Data quality checks  

2. **Correlation Analysis**  
   - Pearson correlation to identify strong predictors  

3. **Regression Models**  
   - Ordinary Least Squares (OLS)  
   - Ridge Regression  
   - Lasso Regression  
   - ElasticNet Regression  

4. **Feature Selection & Model Refinement**  
   - Regularization reduced predictors from **19 to 6**  
   - Maintained model accuracy while improving interpretability  

5. **Model Evaluation Metrics**  
   - R² Score  
   - RMSE  
   - Statistical significance tests  

---

## Key Findings
- **Session Duration** is the strongest predictor  
  - ~330 additional calories burned per extra workout hour  
- **Experience Level** significantly increases caloric expenditure  
  - ~95 additional calories per session for advanced users  
- **Resting Heart Rate** shows a moderate but significant effect  
- **BMI and body composition** have minimal impact once behavior is controlled  
- **Final Model Performance:**  
  - **R² = 0.681**  
  - **Only 6 features required** after regularization  

---

## Final Selected Features
- Session Duration  
- Experience Level  
- Resting BPM  
- BMI  
- Calories from Macros  
- Expected Burn  

---

## Business Insights
- Workout duration should be the primary input for calorie prediction algorithms  
- Personalization based on experience level improves accuracy  
- Simpler models are more interpretable and scalable for fitness applications  
- Overemphasis on body metrics (BMI, weight) is often misleading  

---

## Tech Stack
- **Language:** Python 3  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - statsmodels  

---
