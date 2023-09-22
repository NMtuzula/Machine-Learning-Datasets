# Stroke prediction dataset- We are trying to figure out the number of people who were once affected with stroke compared to those that were fortunate not to have experienced it. 
## The dataset has all the information required to determine this but it is difficult to read/interpret.
## Source of dataset: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
### The dataset contains results of individuals with their health records and the kind of area that they reside in.
### Visuals of our data
![image](https://github.com/NMtuzula/Machine-Learning-Datasets/assets/138831286/e53378e2-eaa8-41f4-b8a5-7d81334b2e92)
#### The data is left stewed. There is a low correlation between the features and the target as there is no correlation coefficient that is greater than 0.5. Hence this is a negative correlation.
###### Below is a multivariate plot between our target(y variate) and feature X(Gender)
![image](https://github.com/NMtuzula/Machine-Learning-Datasets/assets/138831286/6dacfaa0-19ca-49c4-9225-7e830178fc4a)
###### Best Matrix model has to be the confusion matrix
![image](https://github.com/NMtuzula/Machine-Learning-Datasets/assets/138831286/0fc06a2d-c7a9-4b08-a724-0fa7d74975fe)
###### There are no false positives, as this would have resulted in prescribing an individual stroke medication even though they do not need it, resulting in unforseen medical complications.
###### I would recommend that the data is tuned using different models so as to reduce the false negatives.
