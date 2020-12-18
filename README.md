# starbucks

This project was undertaken as a capstone project from the Data science nanodegree. The data is generated from a simulation of the spending habits of starbucks customers. 

The aim of this project was to build a model capable of predicting the response of the customers when faced with various offers. The simulation assumes only one product is available from starbucks and runs for 714 hours. 

Three datasets were provided

- portfolio: detailed the offers available to the customers and their metadata
- profile: contained all the customers on record and their metadata 
- transcript: a record of all the transactions made and offer interactions across the customer base


Initially attempts were made to produce a multilabel classification solution, using estimators available through skearn. A methodology was first used which looked at the final state of the data and performed a train-test split accordingly. A time-based approach was then used to take advantage of the simulated structure of the transcript.
Once these had both been attempted with limited success, a simplified model was developed to predict whether a customer would respond to at least one offer.


## Files 

- Starbucks_Capstone_notebook-Copy1.ipynb : An annotated jupiter notebook containing the project description courtesy of Udacity and all the analysis and exploration undergine by myself. 




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
