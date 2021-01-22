# starbucks

This project was undertaken as a capstone project from the Data science nanodegree. The data is generated from a simulation of the spending habits of starbucks customers. 

The aim of this project was to build a model capable of predicting the response of the customers when faced with various offers. The simulation assumes only one product is available from starbucks and runs for 714 hours. 

Three datasets were provided

- portfolio: detailed the offers available to the customers and their metadata
- profile: contained all the customers on record and their metadata 
- transcript: a record of all the transactions made and offer interactions across the customer base


Initially attempts were made to produce a multilabel classification solution, using estimators available through skearn. This approach used each customer as a datapoint and predicted the interaction with each product. A time-based binary classification process was also used. This instead treated each instance of an offer being receieved as a data point, and predicted whether the offer was successfully completed or not. 


Blog post available here: https://medium.com/@sam.hopkinsoncook/an-attempt-at-latte-ral-thinking-25f1a3833d4a


## Files 

- Starbucks_Capstone_notebook-updated.ipynb : An annotated jupiter notebook containing the project description courtesy of Udacity and all the analysis and exploration undergine by myself. 




## Libraries Used:
-  math
- numpy
- pandas
- json
- seaborn 
- matplotlib
- sklearn


## Acknowledgements 

Thanks to both Udacity and Starbucks for providing the data and the platform for this analysis. 

I'm also grateful to sklearn for the vast amount of information available on machine learning models.  
