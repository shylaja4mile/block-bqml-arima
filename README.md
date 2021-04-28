## About this LookML Block

Use this block to design user-friendly Looker Explores that allow business users to build and evaluate BQML ARIMA Plus models from the Looker UI.


## Implementation

1. Install block from Looker Marketplace
2. Update the database connection and looker temporary dataset constants in the manifest
3. Create a subfolder in the *use_case_refinements* IDE folder for your use case
4. Create a refinement of the *input_data* View for your use case
5. Create a model for your use case
6. Create an Explore in your new use case model that extends the *bqml_arima* Explore
7. Define the JOIN between your input data and forecasts in the extending Explore


## Resources

[BigQuery ML Tutorial: Single time-series forecasting from Google Analytics data]
(https://cloud.google.com/bigquery-ml/docs/arima-single-time-series-forecasting-tutorial)



##### Author: Chris Schmidt, Cihan Gursoy
