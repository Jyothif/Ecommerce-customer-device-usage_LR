# Ecommerce-customer-device-usage_LR : Overview

* There was a time mobile devices were primarily used for making telephone calls. Nowadays, mobile devices are ubiquitous and are used for a variety of purposes. From finding transportation to doing taxes, mobile app solutions have been growing at an exponential rate. One of the fastest growing mobile app verticals is eCommerce. In fact, eMarketer forecasts that the global eCommerce revenue will rise 19% in 2020 to $4.206 trillion (up from $3.535 trillion in 2019). By 2021, they expect global eCommerce revenue will approach $5 trillion. 

* As the Linear Regression project, I have implemented the best fit line by cross examine using MAE,MSE,RMSE


# Code and Resource 

* **Python version:** 3.7.6

* **Packages:** Pandas, Numpy, Sklearn, Matplotlib, Seaborn 

* **Jupyter notebook Version:** 6.0.3



# Data collection : 

* Extracted from kaggle Datasets
* This Dataset consists of no null values and missing values

This Dataset consists of following variables.

 1   Email                  
 2   Address                
 3   Avatar                 
 4   Avg. Session Length   
 5   Time on App           
 6   Time on Website       
 7   Length of Membership  
 8   Yearly Amount Spent 

 
# EDA

* I looked at the distribution of data and Value Counts for the various categorical variables.Some of the highlights from the Results.


![alt text](https://github.com/Jyothif/Ecommerce-customer-device-usage_LR/blob/master/images/jointplot.png)![alt text](https://github.com/Jyothif/Ecommerce-customer-device-usage_LR/blob/master/images/histogram_device_usage.png)![alt text](https://github.com/Jyothif/Ecommerce-customer-device-usage_LR/blob/master/images/heatmap%20LR.png)

# Model Building

* I split the data into train and test sets,  I have used linear regression model for the best fit line 
* I have used  LR Model evaluated using 
  + Mean Absolute Error(MAE),
  + Mean Squared error(MSE),
  + Root Mean Squared Error(RMSE)
  
  
# Model Performance

* I have used LR Model approaches on the test and validation sets.

  + Mean Absolute Error(MAE) = 7.22
  + Mean Squared error(MSE) = 79.81
  + Root Mean Squared Error(RMSE) = 8.93
  
* I evaluated variance score about 0.98
I also found residual coefficients of the model

![alt text](https://github.com/Jyothif/Ecommerce-customer-device-usage_LR/blob/master/images/residuals.PNG)


 



