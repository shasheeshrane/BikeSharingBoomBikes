# BikeSharingBoomBikes - Linear Regression Assignment
This is being submitted as an assignment in Module 3 - Machine Learning1 - By Shasheesh Rane from AI-ML-C36


## STUDY GROUP DETAILS:

      Team Member : Shasheesh Rane
      Group Facilitator :Shasheesh Rane
      Batch :ML-C36 , Dec-2021


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## General Info:

This Assignment is for BoomBikes, A Bike Sharing Company. This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.  

## To Predict below:
      a. Which variables are significant in predicting the demand for shared bikes.
      b. How well those variables describe the bike demands


## MAIN SECTIONS OF THE ASSIGNMENT ARE AS BELOW:

      A. DATA UNDERSTANDING , PREPARATION AND EDA
      B. MODEL BUILDING AND EVALUATION
      C. ASSIGNMENT BASED SUBJECTIVE QUESTIONS


## Technologies used:

For Analysis we have used the Python libraries like matplotlib, plt, seaborn, numpy, sklearn, warnings

### For Dataset feed Files Hosting we have used AWS S3 URLs as below:
      1. We Uploaded the File day.csv to https://s3.ap-south-1.amazonaws.com/myawscloud.uk/day.csv
      2. We Uploaded the File Data_Dictionary.xlsx to https://s3.ap-south-1.amazonaws.com/myawscloud.uk/Readme.txt

These Files are uploaded in AWS S3 directories in Online AWS Storage Account of Shasheesh Rane
Also Uploaded in this Github Folder
For Coding we have used Jupyter notebook and the Google Collab online

#### ASSIGNMENT FILES UPLOADED:
      a. Bike_Sharing_Jupyter_notebook_Shasheesh_Rane_AI-ML_C36.ipynb ---------- this contains the EDA and Linear Regression code,written in Python Jupyter notebook.
      b. Answers to Subjective Questions-Shasheesh_Rane-AI-ML_C36--------------- this contains the Answers to Subjective Questions for this Assignment


## Acknowledgements:

We are grateful to IIIT-B and Upgrad , and our teachers Dinesh J Babu, to help us gain understanding of the Linear Regression.

## Conclusions:

#### As for the Assignment is concerned we got below Conclusions & learning:
EDA:  

      ● Most Booking in Season type Fall. And, in each season the Booking count has increased drastically from 2018 to 2019.
      ● Most of the bookings have been done during the month of may, june, july, aug, sep and oct. bookingTrend increased starting of the year till mid of the year and then it started decreasing as we approached the end of year.
      ● Clear weather attracted more booking Due to better Visibility in Decreasing order of Clear, Misty . Light_snowrain
      ● Wed, Thu, Fri, Sat have more number of bookings as compared to the other weekdays.
      ● When it’s not holiday, booking seems to be less in number which seems reasonable as on holidays, people may want to spend time at home and enjoy with family. 
            Time can be allocated for Outings and physical activity like cycling/bikes.
      ● Booking seemed to be almost equal either on working day or non-working day.2019 attracted more number of booking from the previous year, which shows good progress in terms of business.

#### LINEAR REGRESSION:
      ● Creating a regression model by Spiltting the Data into training and test sets using sklearn.
      ● Using plots and derving the co-relation coefficients.
      ● Building the Linear Prediction model using the regression by reduction of VIF < 5 and dletion of high p-value/VIF variables
      ● Validating the Regression Prediction Model by ERROR TERMS NORMALITY, LINEAR RELATIONSHIP, MULTI-COLINEARITY CHECK
      ● Plotting and fitting the linear prediction model against the test Data.
      
      

This Assignment helped us develop skills in Data Analytics, and furthermore , upcoming assignments and industry related cases studies will help us gain
more insights and techniques, tools and observations to progress towards Machine Learning and AI Skills


## Contact
Created by [@shasheeshrane] 
feel free to contact me! [shasheesh.rane@gmail.com]

<p align="right">(<a href="#top">back to top</a>)</p>
