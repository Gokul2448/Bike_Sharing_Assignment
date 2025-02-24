# Bike_Sharing
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 
This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 
They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. 
It will be used by the management to understand how exactly the demands vary with different features. 
They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The goal is to model the demand for shared bikes with the available independent variables. 
It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
- ## Conclusion 1 from the analysis of train data

  After the first round of RFE analysis with 15 Features on train data , below are the analysis
  
1) VIF value for working day was very high (50.68) and hence that feature was removed and LR model was created
2) In the second round the VIF value for humidity was very high and hence it was removed and LR model was created.
   The Summary was showing good reduction in values
3) Later sat,july,spring features were removed based on P value and VIF and stable model with all features having 0 P value was obtained
   The value for VIF for all variables were below 5
4) The model had a decent R^2 value of 0.839
5) F-static is 235.2 which is greater than 1 and prob of F-static is almost zero indicates that the model is good
6) The Residual analysis was showing a normal distribution and there were no special patterns observed for error distribution
7) The mean value for Error is Zero which indicates model is good.


- ## Conclusion 2 from the analysis of test data 
  
  After the model is tested on train data , below are the analysis
  
1) The R^2 value calculated on test data is 0.796 and it is almost matching with the train data value.
2) Adjusted R^2 value was also calculated on test data and value of 0.76 was obtained compared to 0.83 value for train data



## Technologies Used
- [Python](https://www.python.org/) - version 3.14
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- UpGrad tutorials on Linear Regression and Multiple Linear Regression on the learning platform


## Contact
Created by [Gokul Narayanan](https://github.com/Gokul2448)
