# car-price-analysis
What drives the price of a car?

## Overview
This report analyzes the given car data set with 426K rows and provides a recommnedation on the features that impacts the price. These insights can be used by a dealership to:

- Increase profitability
- Target customers more accurately
- Make smarter inventory decisions

## Key Findings

On the cleaned data set, I applied different data models like Linear Regression, Ridge Regression model with GridSearchCV and Lasso Regression. For this I used the pipeline function and compared RMSE scores. After analyzing the top features, we can plot them like this:

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a2e1c227-ec2e-4939-9c23-5f3b59f8f279" />

It clearly indicates that "model" is the most influential feature here. After that customers pay attention to manufacturer, cylinders, year and title. Rest of the features play a secondary role in decision making process.

## Summary
Dealers can prioritize the high demanding models from the top manufacturers in the inventory. Newer models are always the preferred choice of customers. A cleaner title with more cylinders has higher selling chances than the rest. Dealers can optimize their inventory based on this recommendation.

