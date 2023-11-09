# Predict_Flow
## Dataset information : 
Context
We at Stutern (https://stutern.com) are passionate about ensuring that African graduates have a better outlook and that companies can find the best match when it comes to hiring. Our products and services have been created to help us achieve our mission.

Over the past 4 years , we have built a strong local community of young graduates across all fields. In order to provide more transparency for ourselves and the world on graduates outlook, we conducted a survey of Nigerian recent graduates from February 2018 till May. We got an astounding 5K responses! The survey asked Nigerian graduates many questions around their skills, educational background, current role, and more. We provided a high-level report of our findings from this survey yesterday (see acknowledgements below).

We have since focused more on understanding trends about graduates and the how different factors contribute to their employment status. On October 8 we released our high-level report on our findings. This report is based on survey responses from Nigerian graduates, and it is available here: Nigerian Graduate Report by Stutern 2018

The data set we are releasing here is the full dataset of 5K responses from our graduate survey.

Content
The date consist of one file:

Nigerian-Graduate-Survey-2018.csv: a CSV file with the raw survey responses. Each row is one respondent, and all respondents are anonymous, the timestamp of when the survey was started and ended, and the plain responses to each question. This is the data file that we used for our analysis.

#
A total of 5,219 Nigerian graduates completed the survey.
These graduates completed their degree within the last 5 years (2013 - 2017).
The survey was live from February 8 through May 15, 2018.
The survey was hosted using Google Forms and Stutern recruited respondents via email and social media sites.
To account for graduates in marginalized locations, tracking officers from BudgITCo conducted the offline version in 5 states (Edo, Enugu, Ibadan, Imo and Kaduna State).
We removed about 600 responses that were incomplete from the offline version of the survey before we arrived at 5,219 total responses.
Not every question was shown to every respondent, as some questions were specifically for those who are employed or other cases as it may be.

## EDA and Data visualisation: 
The first analysis was just exploring the data and genearting the insights and analysis from the dataset. 
It is displayed in 

### Visualisation using Power BI
![image](https://github.com/crockrocks/Predict_Flow/assets/91060961/ff9252ce-f737-4d47-b6ec-9858ba9541fc)
![image](https://github.com/crockrocks/Predict_Flow/assets/91060961/7a3070b8-13e0-4dd7-9665-e43081307981)
![image](https://github.com/crockrocks/Predict_Flow/assets/91060961/2693f645-9a1f-4081-b7d4-10444dcd7c37)



## Feature Engineering and modelling
The next step was to study the analysis and visualisations to figure out the important columns and collect information out of those columns , converting categorical columns into numerical quantities , ordinal encoding of the values to simplify the dataset and to improve the overall quality of dataset for model training .
Adding features such as standard of living from the columns and then computing the correlation of the columns.

Modelling involved selecting linear regression as the machine learning model as it suited our problem statement and to train it on the dataset generated using feature engineering.
The code can be shown in : https://github.com/crockrocks/Predict_Flow/blob/main/feature_engineering_modelling.ipynb
