# Project_Miami_Housing
In this project, we are analysing the significance of various factors on house sales price.

# Team members
Vidya, Brandon, Jen, Emma, Fidel

# Setup Instructions
- Make a copy of config.py.dev and rename it config.py
- Paste your own Geoapify key in config.py

# Data Sources
- Kaggle https://www.kaggle.com/datasets/deepcontractor/miami-housing-dataset 
- GEOAPIFY https://apidocs.geoapify.com/docs/places/#about, https://apidocs.geoapify.com/docs/place-details/#place-details 


# Data flow of the project (E2E Data Pipeline)-

- Miami housing sample 01. - Take sample from complete dataset and save css file
- Miami fetch postcode 02 - Fetch post codes from API
- Miami api calls 03 - Fetch restaurants, schools and hospitals data and merge with dataset
- Miami hypythesis 04 - T test for sample and internal factors significance on sales price
- Miami zip code hypothesis 05 - top 10 zip codes with maximum sales and contribution of zip codes to overall sale
- Miami ext factor hypothesis 06 - External factors such as schools, hospital and restaurants significance on sales price

# Which internal factor of house affects the house sales price the most

After considering couple of things from data such as total living area, sqaure footage, special feature value, ocean distance and age of the house, we can conclude that the most correlated attribute with house price is total living area as per data with a value of 0.6 and then special feature value with correaltion value of 0.4 and square footage with value of 0.29 . Along with these, there are two attributes age and ocean to distance which are negatively correalted with value of -0.12 and -0.24
