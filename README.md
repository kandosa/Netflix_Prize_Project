# Netflix_Prize_Project

Netflix project for course BIA 678 Big data & Technology
<br>
## Data: 
[Netflix Prize Data](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)
<br>
## Goals:
* Learn how to use Pyspark to train model
* Build movie recommendations using Pyspark on Databricks Community Editions
* Compare model performance & time to train base on the different amount of training data
* Applied parameter tunning
<br>
## EDA notebook [EDA.ipynb](https://github.com/kandosa/Netflix_Prize_Project/blob/main/eda.ipynb):
* Combined txt files into one dataframe, and save in csv format
* Performed exploratory data analysis
* Created plots for training time cost in Databricks
<br>
## Netflix_proj notebook [Netflix_proj.ipynb](https://github.com/kandosa/Netflix_Prize_Project/blob/main/Netflix_proj.ipynb):
* Built models using Pyspark.ml.ALS
* Used ParamGridBuilder to hyperparameter tuning ALS
* Train multiple models on different training size to examine how the size of training data may affect on performance and time consuming
