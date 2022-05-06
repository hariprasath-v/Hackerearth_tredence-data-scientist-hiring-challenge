# Hackerearth_tredence-data-scientist-hiring-challenge

### Competition hosted on <a href="https://assessment.hackerearth.com/challenges/hiring/tredence-data-scientist-hiring-challenge/"> Hackerearth </a>

# About

### Machine Learning model to predict the weekly dispatch count of the warehouse based on the different warehouses' product-wise daily dispatch data.


### Final Score 82.4

### Evaluation Metric is Mean Absolute Percentage Error.

### File information

 * tredence-data-scientist-hiring-challenge_EDA.ipynb
    ### Packages Used,
        * seaborn
        * Pandas
        * klib
        * Numpy
        * Matplotlib
        * re
    ### Basic Exploratory Data Analysis
    
    
    
* tredence-data-scientist-hiring-challenge_Model.ipynb
    ### Packages Used,
        * Sklearn
        * re
        * Pandas
        * Numpy
        * Matplotlib
        * catboost
     ### Data Pre-processing
         
     ### For the test data daily dispatch count is to be predicted. So first build the catboost regressor model to predict the          daily dispatch count and then by using the daily dispatch count build the final catboost regressor model for weekly            dispatch count prediction.      
 

    
### Daily Dispatch Model Feature Importance  

![Alt text](https://github.com/hariprasath-v/Hackerearth_tredence-data-scientist-hiring-challenge/blob/main/Daily_Dispatch_Model_Feature_Importance_Plot.png)


### Weely Dispatch Model Feature Importance  

![Alt text](https://github.com/hariprasath-v/Hackerearth_tredence-data-scientist-hiring-challenge/blob/main/Weekly_Dispatch_Model_Feature_Importance_Plot.png)


### Daily Dispatch Count Prediction Plot

![Alt text](https://github.com/hariprasath-v/Hackerearth_tredence-data-scientist-hiring-challenge/blob/main/Daily_Dispatch_Count_Prediction_Plot.png)


### Weekly Dispatch Count Prediction Plot

![Alt text](https://github.com/hariprasath-v/Hackerearth_tredence-data-scientist-hiring-challenge/blob/main/Weekly_Dispatch_Count_Prediction_Plot.png)


