# Capstone Project - The Severity of Accident

## 1st week

### 1. Problem and background understanding
    In this project, we focus on the subject of predicting the severity of an accident. people travel and transport by driving alot in America, Sometimes, it is unfortunate but inevitable to be involved in a traffic accident. The purpose of this project is making predictions of the severity of accident based on some attributes like weather and the road condition. This prediction can offer a reference for drivers about the possibility of getting into a car accident and how severe it would be, so that they would drive more carefully or even change the travel.

### 2. Data Description
    The Collisions dataset includes records of collisions happened on road from 2004 to Present. The dataset contains 194673 rows and 38 columns, each row is a record of accident, and each column is an attribute. The first column "SEVERITYCODE" is the labeled data, which describes the fatality of an accident. . The remaining 37 columns have different types of attributes. Some or all can be used to train the model. 
    * There are missing values.  
    * Data type of some attributes are not clear.
    * Some attributes are not useful in building a machine learning model.
    * The data has unbalanced labels. There are 136485 obs of label1 but only 58188 obs of label2.     
    Most of the observations are good to train and test the machine learning model, but a data preprocessing and data selecting procedure need to be conducted. More detialed description of each attribute can be found on the website. 
