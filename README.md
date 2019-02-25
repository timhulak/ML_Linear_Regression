# Linear Regression Project:
- This was a 'Machine Learning: Linear Regression' project from the Udemy course: Python for Data Science and Machine Learning Bootcamp (https://www.udemy.com/python-for-data-science-and-machine-learning-bootcamp/).

## Scenario: 
#### Congratulations! You just got some contract work with an Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.The company is trying to decide whether to focus their efforts on their mobile app experience or their website. They've hired you on contract to help them figure it out! Let's get started!

## Methods:
- Python 3 (Pandas, Numpy)
- Visualization (Matplotlib, Seaborn)
- Machine Learning (Scikit-Learn)

## Question:
- Do you think the company should focus more on their mobile app or on their website?

## Plotting:
- Jointplot: Time on Website vs. Yearly Amount Spent
- Jointplot: Time on App vs. Yearly Amount Spent
- Pairplot: Ecommerce DataFrame
- Linear Model Plot: Yearly Amount Spent vs. Length of Membership
- Scatte Plot: Predicted Values vs Actual Values
- Distribution: Test Values -minus- Predictions

## Metrics Gathered:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Residual Sum of Squares and the Explained Variance Score (R^2)
- Coeffecient values of variables

## Findings based in Coeffecients:
### Holding all other features fixed:
- A (1) unit increase in the Avg. Session Length is associated with an increase of approx. $26 more spent
- A (1) unit increase in the Time on App is associated with an increase of approx. $38 more spent per year.
- A (1) unit increase in the Time on Website is associated with an increase of approx. $0.20 more spent
- A (1) unit increase in the Length of Membership is associated with an increase of approx. $61 more  spent

## My Answer Based on Analysis and Testing: 
- A little more info is needed about the cost of each choice to make a solid recommendation. Aside from that, we could push more resources toward the App because, based on the analysis and Coeffecients, it it generating more revenue for the company. However, this could also mean that the website is in need of resources because it is NOT bringing the company much revenue each year. --Tim


