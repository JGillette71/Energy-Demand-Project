# Energy-Demand-Project
Predicting Energy Demand with Linear Regression 

### Project Abstract
The weather events of February 2021 had a dramatic influence on how Texan's view energy reliability and the impacts of extreme shifts in weather. As a result of these events, this project aims to predict electric energy demand based off readily available weather forcasts. In order to achieve this objective, this project uses a polynomial regression model trained with open source weather data as the input and open source energy data as the ground truth. The project scope focuses on the Dallas Metropolitian Area with predictions tailored to Texas' north central region as defined by the Electric Reliability Council of Texas (ERCOT). <br />

After a detailed correlation analysis of weather effects and demand, a quadratic regression model effectively fit the data and successfully predicted demand with a root mean squared error of 2104 MwH relative to an average demand value of approximately 13,000 MwH. Model performance also resulted in a R^2 value of 0.6625 meaning the model accounts for 66.25% of variation in demand targets. <br />

The use of open source data and the performance of the regression model in meeting the prediction objectives has provided a foundation on which a more expansive prediction model can be built. Please review the "extensions" section of this notebook for suggestions or for more information on this project in general. 
