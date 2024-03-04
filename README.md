# Bike Sharing Demands

Predicting bike rental demand in the Capital Bikeshare program in Washington, D.C using historical weather data from the Bike Sharing Demand dataset available through Kaggle (https://www.kaggle.com/c/bike-sharing-demand/data). 

Using a random forests algorithm:
* Fit a model to predict the number of total rentals
* Tune the model parameters
* Find the most important features
* Use a Gradient Boosting Regressor to find the most important features
* Use a Stochastic Gradient Boosting Regressor to find the most important features

The directory structure: 

```
├── README.md          
├── data
├── notebooks
    ├── RF_regressor.ipynb         
├── requirements.txt   
├── src                
    ├── plot_features_importance.py
```
