# Cost_insurance_analysis_with_python
The analysis aimed to identify key predictors of insurance charges, highlighting smoking status as most significant. Using Python and advanced modeling techniques, the study improved prediction accuracy, enhanced pricing strategies, and refined risk assessment, providing a competitive pricing advantage in the insurance industry.
<img width="1792" alt="01" src="https://github.com/user-attachments/assets/b7452b42-9d1e-46f0-a4bb-809511345c9d">
<img width="1792" alt="02" src="https://github.com/user-attachments/assets/c42bb180-4bfa-489d-8eb4-02023d586a3e">
<img width="1792" alt="03" src="https://github.com/user-attachments/assets/70308197-7bae-4b93-9e46-3064dc666bf4">
<img width="1792" alt="04" src="https://github.com/user-attachments/assets/825a8799-c2d8-4b99-a924-529164ad9d28">
<img width="1792" alt="05" src="https://github.com/user-attachments/assets/8123592c-9100-42b2-a15c-737742d0b93e">
<img width="1792" alt="06" src="https://github.com/user-attachments/assets/e57ab57e-4172-4cf9-bbe9-a19586e08362">
<img width="1792" alt="07" src="https://github.com/user-attachments/assets/3202b51e-b504-4b4d-b456-6ec6c9f50a92">
<img width="1792" alt="08" src="https://github.com/user-attachments/assets/69a76a59-fe40-454f-a1e5-1ce13e2bf64e">
<img width="1792" alt="09" src="https://github.com/user-attachments/assets/2e1f0e63-29ea-4fff-86f1-033f7487b669">
The provided correlation matrix shows the relationships between various attributes and insurance charges. Here’s a summary of the key insights:
* Age and Charges (0.299): There is a moderate positive correlation between age and charges, indicating that older individuals tend to have higher insurance costs.
* Gender and Charges (0.063): Gender shows a very weak positive correlation with charges, suggesting minimal impact on insurance costs.
* Body Mass Index (BMI) and Charges (0.200): There is a positive correlation between BMI and charges, indicating that individuals with higher BMI generally incur higher charges.
* Number of Children and Charges (0.066): The number of children has a very weak positive correlation with charges, suggesting a minimal effect on insurance costs.
* Smoker and Charges (0.789): There is a strong positive correlation between smoking status and charges, indicating that smokers typically face significantly higher insurance costs compared to non-smokers.
* Region and Charges (0.054): The region shows a very weak positive correlation with charges, suggesting that geographic location has a minor impact on insurance costs.
Summary: The strongest predictor of insurance charges in this dataset is whether the individual is a smoker, followed by age and BMI. Gender, number of children, and region have minimal impact on insurance charges.
Feature Importance:
* Smoking Status: This attribute has a strong correlation with insurance charges. Models that include smoking status are more effective at predicting charges.
* Additional Features: Including other features like age, BMI, and number of children improves prediction accuracy, highlighting their importance in determining insurance costs.
Model Performance:
* Basic Model: A simple model using only one feature (smoker) explained about 62.2% of the variance in charges.
* Extended Feature Set: Using all available features improved the model, explaining about 75.0% of the variance.
* Polynomial Features: Adding polynomial transformations further enhanced the model, explaining about 84.5% of the variance. This suggests that complex relationships between features significantly impact prediction accuracy.
* Ridge Regression: Regularization with Ridge regression provided a more generalizable model, though with slightly lower performance (67.6%) compared to the polynomial model. The polynomial Ridge model achieved 78.4%, showing that polynomial features combined with regularization help capture more complexity without overfitting.
Practical Implications:
* Enhanced Pricing Accuracy: Improved models lead to more accurate pricing of insurance policies, benefiting both the company and its customers by providing fairer rates based on a comprehensive set of features.
* Risk Assessment: Better predictive models help in assessing risk more effectively, leading to more informed underwriting decisions.
* Competitive Advantage: Advanced modeling techniques such as polynomial regression and Ridge regression can offer a competitive edge by refining the accuracy of predictions and potentially optimizing pricing strategies.

