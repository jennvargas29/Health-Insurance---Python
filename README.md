# Analyzing Risk Factors for Health Insurance Costs in Python

Health insurance companies rely on data-driven strategies to set policy prices, assess risk, and predict claim costs. Accurately estimating insurance charges based on demographic and medical factors helps insurers create fair and competitive pricing models while enabling policyholders to understand how lifestyle and health choices impact their premiums.



📌OBJETIVE📌
- Identify key factors that influence health insurance costs using exploratory data analysis (EDA) and linear regression modeling.
-  Dataset Attributes: Age, sex, BMI, number of children, smoking status, region, and insurance charges.
-  Problem Statement: Understand the relationship between demographic/medical factors and their impact on insurance costs.
-  Data Preprocessing: Included handling missing values, converting categorical variables to numerical representations, and conducting exploratory data analysis (EDA).
-  Linear Regression was the chosen algorithm to model the relationship between independent variables and insurance charges.








📌MODEL PERFORMANCE: Predicting Insurance Charges:📌

-  The Linear Regression model was built to predict insurance charges using BMI, age, smoking status, number of children, and region as input features.
-  The model captured major trends well, showing that:

🔍 BMI contributes to higher costs, but its impact is amplified when combined with smoking and age.
- Example: A 25-year-old non-smoker with a BMI of 28 might have predicted charges around $5,000, while a 55-year-old smoker with a BMI of 28 could have predicted charges around $35,000.

-  Importance of Machine Learning: Emphasized the importance of utilizing machine learning techniques, particularly linear regression, in predicting insurance charges.
-  Future Research Directions: Identified the need for further model refinement or exploration of alternative algorithms to enhance predictive accuracy and discover additional factors influencing insurance costs.


📌CONCLUSION📌
- In summary, the analysis successfully predicted insurance charges using demographic and medical data, confirming that BMI plays a role in determining costs. However, the results showed that BMI alone is not the strongest predictor—smoking status and age have a much greater impact. The linear regression model provided reasonable predictions, and the findings align with how real-world insurance pricing works. If more detailed health data (e.g., cholesterol levels, and exercise habits) were available, we could further refine the model and improve its accuracy.
  

📌RECOMMENDATIONS📌
- Insurance Company should:
-  Refine pricing models by incorporating additional health factors.
-  Offer personalized premium adjustments for smoking and BMI improvements.
-  Encourage healthier lifestyles through targeted discounts and policy recommendations.
