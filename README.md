This project was prepared for Global AI Hub Aygaz Bootcamp

The dataset is large version of Titanic Dataset. There are 1 million rows and 12 columns.

Unnecessary columns which do not affect the model's performance were removed. 

Missing values were filled with mode value if it is categorical and median was preferred if it is numeric.

Seaborn and matplotlib libraries was used for Data Visulation.

There were just 2 columns whose are categorical data after removing unnecessary columns. Method get_dummies was preferred because of the simplicity of these columns for data preprocessing.

In order to decrease complexity, standard scaler was done and all datas was brought an interval.

The target variable is passenger's survived situation(if he/she dies or survived). Consequently it is a classification problem and models are tried on dataset with cross validation. XGB Classifier beccame the best model then hyperparameter optimization was done on XGB Classifier. 

The best f1-score was obtained 85.31%

WARNING: The dataset was uploded with .zip type because of big size of data(almost 87MB). If you cannot reach, Kaggle link of dataset: https://www.kaggle.com/datasets/marcpaulo/titanic-huge-dataset-1m-passengers

You can reach at this page Kaggle Notebook of this project: https://www.kaggle.com/datasets/marcpaulo/titanic-huge-dataset-1m-passengers/code
