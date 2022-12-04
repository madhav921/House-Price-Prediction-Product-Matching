# House-Price-Prediction-Product-Matching

## House Price Prediciton:
Analyzed and visualized the given data using differnt graphs and plots etc.
Assumption: Found that transaction date is difficult to interpret by ML models, so I've ignored that data to get my result.

The R^2 value for given data is: 0.5941051435505978
Hence I feel that this data is not perfectly accurate or sufficient to get best results, because I expect something >=0.9 to get best results.

Used 6 different ML models:  
 1: Random Forest 
 2: Linear Regression 
 3: Gradient boost regression 
 4: Theil-Sen Regression 
 5: RANSAC Regression 
 6: Support Vector Machines
 
All the code is in the DS-A1.ipynb file.
 
Outputs of all the models are shared in the repo.

Mean square errors of all the models are as follows: 
'Random Forest': 0.8096921958801633, 
'Linear Regression': 0.7510613988697848, 
'Gradient boost regression': 0.6082533591151116, 
'Theil-Sen Regression': 0.8313660244356224, 
'RANSAC Regression': 0.8494401917375881, 
'Support Vector Machines': 0.8674614744404807

Out of all of these I found Gradient Boosting Regression being accurate and effecient in many ways.
Hence I recommend "Gradient Boosting Regression" as my final prediction model.


## Product Matching:

Analyzed all the given data and observed differnet ways to match the products.
Converted the given data into json format to access all the information as strings explicitly.
Used the product_specifications as major key to match the products and then the name of the products.

All the code is in DS-A2.ipynb.

Output file is of all the products matched and listed as a table in given format.
Any input of product's name in the code ouputs respective details from Flipkart and Amazon by searching from this output file.
