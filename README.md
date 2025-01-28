# Driver Churn Prediction and Retention Optimization for Ola

## 🎯 Objective
To develop a robust and interpretable churn prediction model that can be integrated into Ola’s operations. This model will allow the company to identify at-risk drivers early and implement personalized retention strategies, ultimately improving driver satisfaction and reducing operational costs. This project aims to serve as a data-driven solution to address the ongoing churn problem in the ride-hailing industry while providing actionable insights for sustainable workforce management

## 📝 Project Report
-You can access the complete project python file here - [Python](https://github.com/nikhilsree5/OlaCaseStudy/blob/main/Ola_Case_study.ipynb)
-You can access the complete project in pdf format here - [Report](https://github.com/nikhilsree5/OlaCaseStudy/blob/main/Ola_Case_study.pdf)

## 📚 About Data
This study focuses on predicting driver churn based on a variety of driver attributes and operational data. By leveraging historical data from 2019 and 2020 for a segment of drivers, the goal is to build a predictive model to classify drivers into two categories: those likely to leave (churn) and those likely to stay. 

| Feature | Description |
|:--------|:------------|
| MMMM-YY | Reporting Date (Monthly)|
| Driver_ID | Unique id for drivers|
| Age | Age of the driver |
| Gender | Gender of the driver – Male : 0, Female: 1|
| City | City Code of the driver |
| Education_Level |  Education level – 0 for 10+ ,1 for 12+ ,2 for graduate |
| Income |  Monthly average Income of the driver | 
| Country | Name of the country where each customer resides. | 
|Date Of Joining | Joining date for the driver |
|LastWorkingDate | Last date of working for the driver |
|Joining Designation | Designation of the driver at the time of joining |
|Grade | Grade of the driver at the time of reporting |
|Total Business Value | The total business value acquired by the driver in a month (negative business indicates cancellation/refund or car EMI adjustments) |
|Quarterly Rating | Quarterly rating of the driver: 1,2,3,4,5 (higher is better) |

## Outcome Insights and Reccomendations

-The bagging as well as boosting algorithms have performed well with a good resting accuracy.
-These models could be used to predict the churn of drivers in a future percpective.
-Promotional offers like reduction in commission rate etc could be provided to the drivers to prevent them from leaving.
-From the feature importance, Tenure, Total Business value, Rating increment, and Age are found to be most important is deciding the churn rate of drivers from Ola.
-Drivers could be classified based on the above matrices to coin targeted promotional features which will help bring down the churn rate.
