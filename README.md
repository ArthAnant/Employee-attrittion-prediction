I used Seaborn and matplotlib to visualize the relationships between different factors that lead to employee attretion. This was done on the IBM HR dataset from Kaggle<br/>
The link to the dataset is : - https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?datasetId=1067 <br/>
I then used LabelEncoder from the sklearn.preprocessing librady to encode the categorical values into quantitative values. <br/>
Then the data was aplit into training and testing data. <br/>
RobustScalar was used for feature scaling as the data was negatively skewed. <br/>
After the data was prepared, Logistic Regression and SVM algorithms were applied as the prediction values were yes/no and these algorithms are good for binary  classification. <br/>
I found that Logistic Regression gave a better accuracy on this particular dataset. <br/>
