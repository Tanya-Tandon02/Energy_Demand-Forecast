# Energy_Demand-Forecast
Business Context:

One of leading electricity Distribution Company would like to understand demand for electricity for the next 1-2 years to manage the production of electricity and managing the vendors for the same. It is one of the important exercises to getting accurate estimation of demand so that they can procure or produce the electricity as per the demand.

Data Preparation :

The data used in this project was collected from the Kaggle. The data was cleaned and preprocessed using Pandas, and feature engineering was performed to create additional variables, such as year and month.

Model Building :

The forecast model used in this project is an ARIMA (Autoregressive Integrated Moving Average) model, implemented using the statsmodels library in Python. The model was trained on a historical dataset consisting of energy consumption in TW per month from year 1973 to 2019 . Model selection was based on evaluating the AIC (Akaike Information Criterion) and BIC (Bayesian Information Criterion) for different parameter combinations.

Results:

The forecast model achieved an accuracy of 98%, as measured by the mean absolute percentage error (MAPE) on a holdout dataset. Visualizations of the forecasted consumption compared to the actual consumption were created using Matplotlib.


![image](https://user-images.githubusercontent.com/112396873/224793290-e8d1e5a4-6d6b-493b-a706-e9299714ae49.png)





