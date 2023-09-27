# Weather-data-web-scrape
## Objective
The weather data was used for training a prediction model for business usage.
## Target website
Taiwan government hourly weather stations report website
## Process
1. Scraped each weather station report
2. Cleaned unmeaningfull values
3. Merged station weather report with its station information to get its city/district
4. Averaged the rain volume data by city/district/record date/record hour
5. Filled in missing value with the average value of its previous hour and later hour rain volume record
6. Checked valid data proportion
