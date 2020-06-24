## Project Title: Sentiment Analysis of Amazon review dataset 2018

## Project Description:
As nowadays we usually do shopping based on other users reviews on amazon. So reviews matters a most. 
Here Based on that reviews I have developed a system which tells whether particular review is positive or not.

## Requirement

Python 3.x

## Steps to run

1. Download the `reviews` for as much as categories you want from [here](http://deepyeti.ucsd.edu/jianmo/amazon/index.html) and put this all `json.gz` files in `data` folder.
2. Run the `data_preprocessing.ipynb` file which takes input from `data` folder(which is having all gzs files) and output will be cleaned data, we call it `data.csv`
3. The `model_generation_loading.ipynb` takes input as data.csv and gives Machine Learning models we call it `count_tf_gs.joblib`. Later on this model can be used to predict any new review.



    

 