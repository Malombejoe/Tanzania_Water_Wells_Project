
# Tanzanian Water Wells Classification

![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/f2775647-a408-419f-9e75-76ea1125cfbb)



## Business Case

Clean water, basic toilets and good hygiene practices are essential for the survival and development of children. For children under five, water- and sanitation-related diseases are one of the leading causes of death. Every day, over 800 children die from preventable diseases caused by poor water, and a lack of sanitation and hygiene. UNICEF’s water, sanitation and hygiene (WASH) team works in over 100 countries worldwide to improve water and sanitation services, as well as basic hygiene practices. Last year, UNICEF’s efforts provided nearly 14 million people with clean water and over 11 million with basic toilets. Our current mission is to predict the condition of water wells in Tanzania, as they are facing a massive water crisis. 


## Objective of the project
*Build a multi-classifier to predict the condition of water wells using various machine learning algorithms*

#### Technologies Used:
* Pandas for Data Cleaning
* Matplotlib and Seaborn for Data Visualization
* Numpy for Basic Calculations
* Scikit Learn for Logistic Regression, Decision Trees, Random Forests, AdaBoost, and Gradient Boost

### Process Overview

![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/534cb693-74f5-4206-9c33-193dc800a9ff)


* Cast columns to the appropriate data types
   * Convert data types of 'object' to appropriate numerical data type

* Identify and deal with null values appropriately

* Filter data set
   * Convert all columns to contain only the top 5 most frequently seen values
   * Use Boruta algorithm in later stages to determine which features I wanted to keep for my model 

* Deal with categorical variables using dummy variables for modelling purposes

 ## Exploratory Data Analysis
 
 ### Distribution of Well Conditions
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/d141425c-9b29-49ec-9582-473e1b276a61)

 
 
 ### Date Recorded of Wells
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/d2b3fa78-45b1-434a-8067-a215697bd560)

 
 
 ### Construction Years of Wells
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/db05043a-8f0f-47f3-a693-9173adc8b265)

 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/2c445e91-4930-451c-bca0-fc9422accf3a)

 
 
 ### Distribution of the Altitude of Wells
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/ad952dee-caa4-4b83-95e4-e83c2e7d7e67)

 
 
 ### Distribution of the region codes of Wells
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/c30cd773-2912-4b49-8c2a-70767820b953)

 
 
 ### Best Water Sources
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/d0646e6f-a14c-4b3a-956e-2b5bd521e2a1)

 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/cbae6c1f-3d94-4f5b-a18a-d5f75b966513)

 
 
 ### Best Water Quantity
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/a54a82ed-097a-424d-9d12-96ed0077d4c0)

 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/881772a9-d8d9-41e0-a8fd-70685d434692)

 
 
 ### Best Water Quality
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/93416f05-c5ea-4d24-969d-f1b9b08962e5)

 
 
 ### Check for multicollinearity
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/a79f5ef5-58fd-4b7c-b1e3-e0f9010d4d1b)

 
 ## Modelling
 
 **Final Model Selected: Random Forest**; **Final Accuracy Score: 70.2%**
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/df6bad90-d68c-4f9b-8e45-101f17129fe5)

 
 # Conclusion
 
 ### Top 10 Features
 
![image](https://github.com/Malombejoe/Tanzania_Water_Wells_Project/assets/99344966/97b2f286-3edb-41d8-8024-568ecdf02893)

 
 **Next Steps**
 
  * Trying different data cleaning methods
  * Having more time to play around with combining unused features together
  * Collect more data to train the model
  * Transforming more categorical variables into numerical ones for modelling purposes
  * Making predictions with another modelling algorithm such as XGBoost

 
 
  
