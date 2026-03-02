# -Insurance-Cost-Analysis-
**Project Overview**
The objective of this project is to analyze factors affecting medical insurance charges and build insights that help insurance companies make better pricing and risk management decisions.
This project uses statistical analysis, exploratory data analysis (EDA), and predictive modeling techniques to identify key variables influencing insurance costs.

**Business Objective**
Insurance companies need to:
Identify high-risk customers.
Predict medical insurance charges.
Optimize premium pricing.

**Dataset Description**
age :	Age of the customer.
sex	: Gender (male/female).
bmi	: Body Mass Index.
children	: Number of dependents.
smoker :	Smoking status (yes/no).
region	: Residential region.
charges :	Medical insurance cost (target variable).

**Data Cleaning**
Checked for missing values.
Verified data types.
Removed duplicates.
Converted categorical variables where required.
Ensured dataset consistency.

**Key Insights from EDA**
1. Smoking is the strongest factor affecting charges.
    Smokers have significantly higher insurance costs.

2. Age has positive relationship with charges.
    Charges increase with age.

3. BMI moderately affects charges.
    Higher BMI leads to higher medical costs.

4. Region has minimal impact on charges.
   
**Statistical Analysis**
T-Test Result: Smoker vs Non-Smoker Charges

**Null Hypothesis (H₀):** Smoking does not affect charges.

**Alternative Hypothesis (H₁):** Smoking affects charges.

**Result:**
p-value = 0.0000
Since p-value < 0.05, reject Null Hypothesis
**Conclusion:** Smoking significantly increases insurance charges.

**Tools and Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

**Final Conclusion of Project :**
Smoking, age, and BMI are major factors influencing insurance charges.
Smoking is the most significant predictor.
Predictive modeling and risk-based pricing strategies can help insurance companies optimize pricing, reduce risk, and increase profitability.
