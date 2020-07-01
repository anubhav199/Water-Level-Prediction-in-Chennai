# Water-Level-Prediction-in-Chennai
An attempt to put together all the data-sets that have the information about the various water sources available in the city Chennai.
## Objectives
1. Visualize the water need / usage of the city
2. Identify whether the water sources availability will be able to meet the needs till the subsequent monsoon?
3. How bad is the current water crisis compared to previous years?
## Algorithm
• Multiple Linear Regression <br/>
• Time Series Forecasting
## Dataset Desription
This dataset has details about the water availability in the four main reservoirs over the last 15 years :- <br/>
Poondi, Cholavaram, Redhills, Chembarambakkam <br/>
The data is available on a daily basis and the unit is million cubic feet. <br/>
Link: https://www.kaggle.com/sudalairajkumar/chennai-water-management
## Conclusion
Since, Time Series is having the less RMSE error as compare to the Multiple Linear Regression hence it is working best on the dataset. The reason for this might be that the time series algorithm takes several factors into consideration like seasonality, trend, cyclicity, irregularity into consideration before making any prediction but multiple linear regression don’t take these factors into consideration. <br/>
Hence, Time Series Forecasting worked best for this dataset.

Hope this project will help, Happy Coding....!
