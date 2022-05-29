# ReCell-Refurburbished Devices
Buying and selling used phones and tablets used to be something that happened on a handful of online marketplace sites. But the used and refurbished device market has grown considerably over the past decade, and a new IDC (International Data Corporation) forecast predicts that the used phone market would be worth $52.7bn by 2023 with a compound annual growth rate (CAGR) of 13.6% from 2018 to 2023.
This growth can be attributed to an uptick in demand for used phones and tablets that offer considerable savings compared with new models.
Refurbished and used devices continue to provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing one. There are plenty of other benefits associated with the used device market.
Used and refurbished devices can be sold with warranties and can also be insured with proof of purchase. Third-party vendors/platforms, such as Verizon, Amazon, etc., provide attractive offers to customers for refurbished devices. 
Maximizing the longevity of devices through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. The impact of the COVID-19 outbreak may further boost this segment as consumers cut back on discretionary spending and buy phones and tablets only for immediate needs.
The rising potential of this comparatively under-the-radar market fuels the need for an ML-based solution to develop a dynamic pricing strategy for used and refurbished devices. ReCell, a startup aiming to tap the potential in this market.
As a data scientist I have been hired to analyze the data provided and build a linear regression model to predict the price of a used phone/tablet and identify factors that significantly influence it.

Tools used
•	Python: statsmodel, sklearn, sklearn.metrics, pycountry-convert
•	Linear regression using training data and test data
•	Result interpretation: Adjust R-squared, Const coefficient, Coefficient of predictor variable, Root mean square deviation (RMSE), Mean absolute error (MAE), Mean absolute percentage error (MAPE)

Project Coverage
•	Develop a dynamic pricing strategy for used and refurbished phones
Tasks Performed
•	Making statistical inference from the data
•	Build supervised learning model using Linear Regression
•	Built linear regression model using statsmodel testing for R-squared and Adjusted R squared to determine the factor(s) leading to price variation
•	Determine price segments based on the price of a new model of the used device being sold
•	Visual analytics using labeled bar plot to determine if features in a phone affect the used device price
•	Check model performance on actual prices and use metric function RMSE,  MAE and MAPE to check overfitting, mean error and large prediction errors
•	Check linear regression assumptions No Multicollinearity, Linearity of variables, Independence of error terms, Normality of error terms, No Heteroscedasticity
•	Data pre-processing: Feature engineering, heat map

Business Insights
•	The most significant predictors of the used device price are the price of a new device of the same model, the size of the devices screen, the resolution of the rear and front cameras, the number of days it was used, the amount of RAM, and the availability of 4G and 5G network.
•	A unit increase in new model price will result in a 0.09% increase in the used device price.
•	Built five point criteria needed for used devices which if implemented could lead to a 20% increase in revenue
•	A unit increase in size of the device's screen will result in a 5.76% increase in the used device price.
•	A unit increase in the amount of RAM will result in a 3.69% increase in the used device price
