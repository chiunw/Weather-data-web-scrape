# Weather-data-web-scrape
## Objective
The primary objective of this project was to collect and preprocess weather data in each city and district for training a predictive model for business applications.

## Target Website
I focused on extracting data from the Taiwan government's hourly weather stations reporting website.

## Process
The data collection and preprocessing process involved the following steps:

1. Data Scraping: Scraped data using BeautifulSoup.
2. Data Cleaning: Removed meaningless or erroneous values from the collected rainfall volumes (rain_mm) data.
3. Data Integration: Combined the station-specific weather data with their respective station information to associate each record with its corresponding city or district.
4. Data Aggregation: Calculated average rainfall volumes (rain_mm) by city, district, record date, and record hour.
5. Missing Data Imputation: Filled in the gaps by using the average values from the previous hour and the subsequent hour's rainfall volume (rain_mm) records.
6. Data Validation: Verified the proportion of valid data in the dataset.
