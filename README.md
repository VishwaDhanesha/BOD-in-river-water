# BOD-in-river-water
This dataset represents the Biochemical Oxygen Demand(BOD) in river water from 7 different stations. There are total 9 features with 147 observations. There is a target column named 'target' and 7 stations are named as columns 1,2,3,4,5,6 and 7. Most of the observations in columns 3,4,5,6 and 7 are missing. Hence, these features are removed from the data. There are a total of 569 missing values in the data. Also, there are 3 observations among columns 1 and 2 and thus these 3 observations are also removed. Further analysis is done only using 3 columns - 'target','1' and '2'. Various models are used to compare the accuracy of output obtained from each model. Models such as Linear Regression, Decision Tree, Random FOrest and XGB Regressor are used. MAE, MSE, R2 and cross validation is used to compare the accuracy of outputs obtained from each model. Using these, it was concluded that XGB Regressor gives better accuracy than the rest of the models. 
