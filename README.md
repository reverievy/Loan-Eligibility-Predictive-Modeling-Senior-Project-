# Loan-Eligibility-Predictive-Modeling-Senior-Project-

📊 **Quick-read!**

For my senior project as a Business Analytics major at Drexel University, I strengthened my expertise in predictive modeling, utilizing supervised learning techniques with a particular focus on data wrangling for skewed datasets. As the main data analyst for the project, I managed the data rebalancing effort and the Decision Tree model development. 

📍**Stakeholders:** Data & Analytics, Risk & Fraud Management

📍**Skills:** R, Data Preprocessing, Predictive Modeling (Decision Trees, Logistic Regressions, Random Forests)



## **Project Description**
The Risk Management department at the Bank seeks to establish a robust approach to assess loan eligibility for new and current customers by accurately predicting whether a client represents a low or high credit risk. By developing two predictive models, the team aims to improve risk assessment and enhance decision-making in the loan approval process.

**Key Challenges**

1. The target variable bad_client_target is **heavily skewed**, with only 11.4% of the total observations being ineligible clients. This imbalance causes the Decision Tree models to not be able to split properly, or not split at all, and diminishes the Logistic Regression predictive ability.
2. A struggle with the Precision rate in the models and accurately identifying bad clients, ***emphasizing the cost of failing to identify a bad client over mistakenly identifying a good client as bad.***

**Key Actions**
- **Data Preprocessing & Exploration**: Conducted data type conversions, managed missing and duplicate variables, and performed outlier analysis.
- **Variable Selection:** Utilized Stepwise Regression Analysis to identify critical variables
- **Dataset Balancing**: Applied Oversampling, Undersampling, and Cost Matrix training to transform a heavily skewed dataset, ensuring model performance across metrics like precision and recall.
- **Model Development**: Built and evaluated Classification Tree and Logistic Regression models.
- **Evaluation & Optimization**: Conducted accuracy, precision, and recall assessments, ensuring consistent results from the training set to the test set.

**Model Evaluations**
<img width="889" alt="image" src="https://github.com/user-attachments/assets/438b97ad-39bc-43dd-9f7e-ef440c173fb1" />


**Conclusions & Next Steps**

The team addressed the dataset imbalance challenge effectively with Downsampling and Cost Matrix training, enhancing the fairness and usability of the predictive models. Utilizing this updated sample, we continuously refined the two different model approaches. 

For the objective of predicting loan eligibility and prioritizing the reduction of false negatives, while both models have their strengths and weaknesses, the **Logistic Regression Model** seems more robust and consistent, especially in an operational environment where it will encounter data it has not been trained on.

If we were to move forward with this project, we would:
1. Utilize Synthetic Minority Oversampling Technique: 
2. Cost Sensitivity Tuning: 
3. Threshold Adjustment:
4. Employ Cross-Validation Techniques:

