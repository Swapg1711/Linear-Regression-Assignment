# Linear Regression Assignment
> To build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

- What is the background of your project?
We are the consulting company. BoomBikes Company have contracted a us to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market

- What is the business probem that your project is trying to solve?
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
The company wants to know:
•	Which variables are significant in predicting the demand for shared bikes?
•	How well do those variables describe the bike demands?


- What is the dataset that is being used?
Data has been provided. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Observations and recommondations
- Demand is high in yr, holiday, spring, Light_Snow, Mist_Cloudy,3,5,6,7,8,9,10,Sunday.
- High demand in months  3,5,6,7,8,9,10.
- High demand in weather condition - Light_Snow and Mist_Cloudy
- High demand season - spring


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Pandas 
- library - Numpy
- library - Seaborn
- library - Matplotlib
- library sklearn
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import MinMaxScaler
- library statsmodels.api as sm
- from sklearn.feature_selection import RFE
- from sklearn.linear_model import LinearRegression  
- from statsmodels.stats.outliers_influence import variance_inflation_factor
- from sklearn.metrics import mean_squared_error
- from sklearn.metrics import r2_score


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Swapg1711] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->