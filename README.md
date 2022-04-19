# Netflix_Prize_Project

FInal project for course BIA 678 Big data & Technology
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

## EDA notebook: 
* [EDA.ipynb](https://github.com/kandosa/Netflix_Prize_Project/blob/main/eda.ipynb)
* Combined txt files into one dataframe, and save in csv format
* Performed exploratory data analysis
* Created plots for training time cost in Databricks

<br>

## Netflix_proj notebook: 
* [Netflix_proj.ipynb](https://github.com/kandosa/Netflix_Prize_Project/blob/main/Netflix_proj.ipynb)
* Built models using Pyspark.ml.ALS
* Used ParamGridBuilder to hyperparameter tuning ALS
* Train multiple models on different training size to examine how the size of training data may affect on performance and time consuming

<br>

## TLDR:
* As scale increases, the training model will generally increase the performance of the model, at the same time the time cost of training will increase when the scale increases
* x-axis are scale of training data for both plots
* y-axis for left plot is time cost in hours, y-axis for the right plot is RMSE score

![BIA 678 project report_Img0](https://user-images.githubusercontent.com/43526555/163901166-d0bdf676-ce54-42a0-83a1-e179f694353c.png)
