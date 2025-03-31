# deployable_pipeline
A tool kit to be able to rapidly deploy to a given dataset with the emphasis on parametrisation throughout to increase usability 


## Broken into separate components:

1. Ingestion - learning openpxyl to create template which could be applied. Different routes based on template formats a) Time series data with 2 variables, identification of time series and a preference selection on variable 1 and 2.
   
2. Transformation - pandas, creating a meta data table alongisde a thin slice notebook. Included with widgets to be able to aggregate on specific basis and enable point and click elements. This is then outputed as csvs with a specific file path. Also a report generated from the transformation which could be used for monitoring.
  
3. Output - summaries and visualisations based on the templated route. Time series then a line graph/ categorical template bar charts. 
