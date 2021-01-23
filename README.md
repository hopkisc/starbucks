# starbucks


The motivation for this project was to exhibit the technical abilities I have picked up and improved across the duration of the Udacity Data Science Nanodegree. This is manifested as a piece of work that aims to identify which customer demographics are the most likely to respond to a selection of promotional offers, issued by Starbucks,

The data is generated from a simulation of Starbucks customers, which logs the interactions between customers and offers, and the transactions made by the customers. The simulation assumes only one product is available from starbucks and runs for 714 hours. My goal is to produce a model capable of predicting the customer response, on receving an offer. 

Three datasets were provided

- portfolio: detailed the offers available to the customers and their metadata
- profile: contained all the customers on record and their metadata 
- transcript: a record of all the transactions made and offer interactions across the customer base


Initially attempts were made to produce a multilabel classification solution, using estimators available through skearn. This approach uses each customer as a datapoint and predicts the interaction with each product. A time-based binary classification process was also used. This instead treats each instance of an offer being received as a data point, and predicts whether the offer was successfully completed or not. 

The multilabel approach proved intially easier to setup in terms of preprocessing but it became evident that the performance was limited. Improvements were attempted using a variety of methods but to minimal prevail. The binary approach was more difficult to setup as time dependent feature derivation was required. However, the performance of this model was superior, and was improved further using gridsearchCV from sklearn. The final model provides useful insight, and appears valid according to the evaluation metrics implemented. 


Blog post available here: https://medium.com/@sam.hopkinsoncook/an-attempt-at-latte-ral-thinking-25f1a3833d4a

Link to repo: https://github.com/hopkisc/starbucks/blob/main/Starbucks_Capstone_notebook-Copy1.ipynb


## Files 

- Starbucks_Capstone_notebook-Copy1.ipynb : An annotated jupiter notebook containing the project description courtesy of Udacity and all the analysis and exploration undergone by myself. 




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

I'm also grateful to sklearn for the vast amount of information and implementations available on machine learning models.  
