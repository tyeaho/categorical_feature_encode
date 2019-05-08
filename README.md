this code is from: https://medium.com/@vaibhavshukla182/want-to-know-the-diff-among-pd-factorize-a8591eb3347d

As generally known, ML models mostly consist of model-understandable numerical data.          
These are 2 steps that can change categorical text data into numerical data        
        
        
step 1) labels-> categorical variables         
use: pd.factorize / sklearn.preprocessing.LabelEncoder
result will have 1-D

step 2) categorical variables
use: pd.get_dummies/ sklearn.preprocessing.OneHotEncoder
result will have n-D
