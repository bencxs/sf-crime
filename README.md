# sf-crime
San Francisco Crime Classification

## Introduction
> ###Predict the category of crimes that occurred in the city by the bay

>From 1934 to 1963, San Francisco was infamous for housing some of the world's most notorious criminals on the inescapable island of >Alcatraz.

>Today, the city is known more for its tech scene than its criminal past. But, with rising wealth inequality, housing shortages, and a >proliferation of expensive digital toys riding BART to work, there is no scarcity of crime in the city by the bay.

>From Sunset to SOMA, and Marina to Excelsior, this competition's dataset provides nearly 12 years of crime reports from across all of San >Francisco's neighborhoods. Given time and location, you must predict the category of crime that occurred.

Dataset can be found via [Kaggle](https://www.kaggle.com/c/sf-crime/data)

## Files
`1_preprocess.ipynb` - Code for preprocessing dataset

`2_model,ipynb` - Code for model training and testing

## Status
### Model
* Base model implemented with ExtraTreesClassifier. 
* XGBoost model implementation attempted, however run time is too long.

### Data Visualization
* Geo-data map visualization in-progress
