# **Capstone Project 3: Machine Learning**
This project is made for my module 3 project in Purwadhika Digital Technology School
# **California Housing Price**
# **Contents**
I.  Business Understanding </br>
II. Libraries & Dataset </br>
III. Explaratory Data Analysis </br>
IV. Machine Learning </br>
V. Extreme Gradient Boost</br>
VI. Conclusion and Recommendation</br>
VII. Business Recommendation
___
# **I. Business Understanding**
## **i. Background**
The California Housing Dataset provides a comprehensive view of the state's housing landscape as recorded in the 1990 census. While its primary purpose may not be to predict today's housing market, it serves as an invaluable resource for individuals entering the realm of machine learning. This dataset encompasses a variety of attributes, including geographical coordinates, housing details, demographic information, proximity to the ocean, and property values. It offers a holistic insight into the factors that significantly influenced the housing trends in California in 1990.
## **ii. Problem Statement**
In the vibrant real estate market of California, **accurately pricing newly constructed houses is a pivotal challenge**. The state's diverse neighborhoods and housing markets require careful consideration when determining property values. **Setting prices too high may lead to prolonged time on the market and deter potential buyers, while pricing properties too low could result in financial losses or prompt inquiries into the fairness of transactions**. California's complex housing market dynamics, influenced by regional diversity and buyer demographics, necessitate data-driven solutions.
## **iii. Goals**
In response to these challenges, **our goal as developers is to leverage machine learning to create predictive models that provide precise estimates of house prices**. By using comprehensive datasets without specifying individual features, we aim to provide a valuable resource for home sellers and buyers. **Our objective is to equip users with insights for making informed pricing decisions**, ensuring that houses are competitively priced and transactions are conducted transparently and efficiently in California's housing market.
## **iv. Analytic Approach**
We'll gather and preprocess California housing data, experiment with machine learning models, optimize performance, and deploy the best model for real-time house price predictions. Continuous improvements will ensure adaptability to market changes, addressing the challenge of precise pricing in California's dynamic housing market.
## **v. Metric Evaluation**
To determine the best model from the provided table, we need to assess several evaluation metrics:

1. **RMSE (Root Mean Square Error)**: This measures the discrepancy between the model's predictions and the actual values. A lower RMSE indicates a superior model.
2. **MAE (Mean Absolute Error)**: This evaluates the absolute difference between predictions and the actual observations. A model with a lower MAE is deemed better.
3. **MAPE (Mean Absolute Percentage Error)**: This gauges the relative difference between predictions and actual observations. The lower the MAPE, the better the model.

Let's compare each model based on these three evaluation metrics to pinpoint the top-performing one:

1. **Model with the Lowest RMSE**: A lower RMSE signifies a better model.
2. **Model with the Lowest MAE**: A lower MAE denotes a better model.
3. **Model with the Lowest MAPE**: A model with a lower MAPE is seen as superior.

Considering the above criteria, we'll identify the best model. These metrics suggest that the XGBoost Regressor is the model with the lowest RMSE, MAE, and MAPE. The second-best model is the RandomForest Regressor. Based on this, we'll select these two models as our benchmark models for predictions on the test set.
## **Limitation**
- Outdated Dataset = Outdated Model

Given that our dataset pertains to California House Pricing in 1990, it's important to acknowledge the substantial **time gap between 2023 and 1990**. Over the years, the value of real estate has typically seen considerable appreciation, with **house prices often increasing significantly as the economy grows and matures**. This temporal disparity should be taken into account when interpreting and applying the dataset to contemporary scenarios.
- District Names 

In this model, we incorporate latitude and longitude data, whereas current practices favor district names or postal codes. **To use this model effectively, additional reference data is required to map those names and codes to latitude and longitude coordinates which are not ideal practices**.

# **VII. Business Recommendation**
We cannot accurately predict the hypothetical effectiveness of mispricing reduction after implementing machine learning; instead, we need to conduct implementation testing and make comparisons between scenarios with and without machine learning. A few testing options include A/B testing, cross-validation, and real-world performance assessment. Ultimately, our core objective is to minimize the cost associated with mispricing.
___
The goal of implementing machine learning is not only focused on hypothetical mispricing calculations, but rather on exploring the hypothetical potential for reducing the overall cost associated with the processes that precede these critical aspects. By automating and streamlining various tasks and data analysis, machine learning helps optimize resource utilization and operational efficiency, ultimately driving cost savings across the board.

Based on [California Housing Prices on 1990](http://www.demographia.com/db-statehouse$2000.htm), averagin on 194.300.

Taken from [Market Connections](https://www.marketconnectionsinc.com/lets-talk-price-how-much-does-research-cost/)
___

In the old days, market researcher for real estate agent requires [3 to 6 months](https://www.quora.com/How-long-does-it-take-for-an-average-newbie-realtor-to-make-a-sale). Which means they spend a lot of time and equally spend a lot of money.

By using Machine Learning, this whole process could take 1 day easily if you have the data up to 1 month if you need to gather one.

Equation is:

Efficiency Saved (%) = [(Original Time - Reduced Time) / Original Time] * 100

- Original Time = 3 to 6 months (let's take the average, which is 4.5 months)
- Reduced Time = 1 day to 1 month (let's take the average, which is 15.5 days or approximately 0.5 months)

Efficiency Saved (%) = [(4.5 months - 0.5 months) / 4.5 months] * 100

Efficiency Saved (%) = (4 months / 4.5 months) * 100

Efficiency Saved (%) ≈ 88.89%
___

Let's say Real Estate Field is a big company, which means $100k market research team funding.

At the end, 88.89% x $100.000, we saved $88,890 which then can go into Machine Learning Building/AI Building.


 
