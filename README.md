# Project_Miami_Housing
This repository is created for Miami housing analysis project.

# Setup Instructions
- Make a copy of config.py.dev and rename it config.py
- Paste your own Geoapify key in config.py

# Data Flow of the project (E2E Data Pipeline)-

- Miami housing sample 01. - Take sample from complete dataset and save css file
- Miami fetch postcode 02 - Fetch post codes from API
- Miami api calls 03 - Fetch restaurants, schools and hospitals data and merge with dataset
- Miami hypythesis 04 - T test for sample and internal factors significance on sales price
- Miami zip code hypothesis 05 - top 10 zip codes with maximum sales and contribution of zip codes to overall sale
- Miami ext factor hypothesis 06 - External factors such as schools, hospital and restaurants significance on sales price
