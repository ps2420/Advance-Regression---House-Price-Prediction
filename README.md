# Advance Regression - House price prediction
> Repository contains an analysis of A US-based housing company, which has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.:

* Which variables are significant in predicting the price of a house.
* How well those variables describe the price of a house


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Repository contains the jypter notebook and some useful insights about the case study described in pdf.
- The jypter note book explains the relation ship between different variables and summarizes the keysteps required for model building

## Conclusions
Features which impacts the sales price most are listed below
- GrLivArea: Above grade (ground) living area square feet
- OverallQual: Rates the overall material and finish of the house.
- Neighborhood_Crawfor: Physical locations within Ames city limits. 
- SaleCondition_Normal: Condition of sale (i.e. when its normal)
- MSZoning: Identifies the general zoning classification of the sale (Type: FV)
- OverallCond: Rates the overall condition of the house

Features which impacts the sales price negatively are listed below
- PropertyAge: Age of the property at the time of seeling
- HeatingQC_Fa: Heating quality and condition (when its fair).

## Technologies Used
- Python 3.2.1, Panda, Seaborn, Matplot lib, sklearn & statsmodel
- All the version of softwares were installed as part of Anaconda package, which packages most of the libraries used for Data Science.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad online learning community https://www.upgrad.com/
- This project was based on linear regressioin module.


## Contact
Created by [@ps2420] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
