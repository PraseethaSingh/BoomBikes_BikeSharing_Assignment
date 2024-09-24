# Boom Bikes Bike-Sharing Assignment

> A US bike-sharing provider Boom Bikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Boom Bikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project is done as part of coursework in the Machine Learning module
- Multiple Linear regression is performed for the problem 
- A Bike rental company is to understand the demand for shared bikes among the people. The dataset provided has data collected for various different features that may or may not affect the demand. Our aim is to identify the variables affecting the demand for these shared bikes in the American market.
- The Boom bikes dataset day.csv is used.

## Conclusions
1. The R-squared value of the train set is 83.5% and for the test set is 80%.This indicates that the model explains the variance quite accurately on the test set. Thus we can conclude that it is a good model.

2. The mean squared error for the model is almost 0 for both training and testing datasets. It indicates that the variance is accurately predicted on the test set.

3. A hybrid method was used to develop the model. RFE was used initially followed by manual method of removing independent variables one by one until we reach optimal p_value ( <0.05) and VIF (<5)

4. The Steps involved are -
   Step1 - Data reading and Understanding
   Step2 - EDA ( Data Visualization) 
   Step3 - Preparing the Data ( Handling missing values, Removing non-relevant features, Derived metrics using Dummy Variables, Data preprocessing ( Scaling 	   data using the Min-Max scaler)
   Step4 - Model 
   Step5 - Residual Analysis
   Step6 - Prediction and Model evaluation on test set 




## Technologies Used
- Python 3.10.1 
- Anaconda Navigator 2.5.2
- Jupiter Notebook 7.0.8
- NumPy version: 1.26.4
- Pandas version: 2.1.4
- Matplotlib version: 3.8.0
- Seaborn version: 0.13.2
- SciPy version: 1.11.4
- SKlearn version: 1.2.2
- Statsmodels version: 0.14.0

## Acknowledgements
- This project was inspired by course work on ML

## Contact
Created by @PraseethaSingh - feel free to contact me!
praseetha.singh@gmail.com

