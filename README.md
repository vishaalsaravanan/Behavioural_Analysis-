**Note about the datasets:**
Dataset **appdata10.csv** is the initial dataset in which you will be working in the first place!. It contains a unique user id with the set of feature columns that will be removed in case if some features calculated were less co-related to user behavior.**Top_screens.csv** used to pre-process the dataset. The final preprocessed data will be stored as a new dataset called **new_appdata10.csv**.
# Brief:
Assessing consumer behavior in this data-driven world is of more importance. In the above code in **Analysis.py**, I have performed data preprocessing in dataset appdata10.csv to remove the less co-related features and transforming the dataset into the sparse form to make it ready for the model building phase in **Model_Analysis.py** since the ultimate goal of this model is to predict whether the consumer subscribes to given service or not.So,I have used the simple logistic regression classifier with penalty parameter "L1" for the final prediction.
# How to Run?
Head to the project directory and run
1. pip install -r requirements.txt
2. python Analysis.py 
3. python Model_For_Analysis.py 

