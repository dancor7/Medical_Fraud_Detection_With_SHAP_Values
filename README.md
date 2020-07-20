# Medical_Fraud_Detection_With_SHAP_Values
Using SHAP values for finding the best variables for a medical fraud classifier model, this code was reported in this [article](https://medium.com/@dan7cor/medical-fraud-detection-using-shap-values-in-feature-selection-4f98746da7a3)

Libraries: 
In this project, we used pandas, numpy, sklearn, catboost, shap, random, itertools, seaborn and matplotlib

Project Motivation: 
My field of interest is machine learning for the medical field, these include opitmizing the processes that make healthcare more accesible to everyone.

Files: 
- Paramsearch.py: this is a python file that holds a class used for hypertuning the parameters of a catboost model
- Medical_Fraud.ipynb: This holds the notebook used for cleaning the data and training the model
- data.rar: rar file with the input datasets for the model, this must be unpacked first before running the code

Summary of findings: 
We discovered that SHAP values were very useful for finding good variables for a logistic model, giving high scores in recall and in accuracy

acknowledgements: 
Thanks to the the Kaggle user DIMA for his code which helped me understand the input variables, since there was no data dictionary, and for giving inspiration on how to clean the certain columns of the dataset.
