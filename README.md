I used Seaborn and matplotlib to visualize the relationships between different factors that lead to employee attretion. This was done on the IBM HR dataset from Kaggle
The link to the dataset is : - https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?datasetId=1067
I then used LabelEncoder from the sklearn.preprocessing librady to encode the categorical values into quantitative values.
Then the data was aplit into training and testing data.
RobustScalar was used for feature scaling as the data was negatively skewed.
After the data was prepared, Logistic Regression and SVM algorithms were applied as the prediction values were yes/no and these algorithms are good for binary classification.
I found that Logistic Regression gave a better accuracy on this particular dataset.
