# Oily-Giant
![image](https://user-images.githubusercontent.com/115895428/216845114-ca6cd56f-9a59-40cc-9340-1f62b74a04cd.png)


## Purpose
The purpose of this project is to find the best location for a our customer, OilyGiant, to place a new well for mining oil. We are given oil well parameters in three distinct regions, upon which we will use to create our linear regression model. The model will predict the volume of reserves in the new wells, and the region with the highest total profit will be chosen for the new well. 

## Conclusion
Considering the three datasets, we will suggest OilGiant to start a new site in Region 1. Region 1 has the greatest profit margin, as the range of well reserve volume is better than those of the other regions, due to the higher lower bound. In addition, the chance of losses in Region 1 is around 1%, which is extremely low. Therefore, the chances of randomly picking 200 sites that are extremely profitable will be more likely in Region 1. As we are focusing on as subsample of the 200 most profitable wells out of a 500 well sample, we limit our chance of loss, rather than just randomly picking wells. Overall, our model will perform well when predicting new sites to implement, and predicting the most profitable wells, given the same features we have in our model. 


## [Web Notebook](https://jodiambra.github.io/Oily-Giant-Profit-Predictions/)
