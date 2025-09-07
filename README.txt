This project investigates the demand between HighVolume ForHire Vehicles (HVFHVs, e.g., Uber, Lyft) and traditional Yellow Taxis in New York City, the analysis quantifies how different factors—including time of day, weather, and pricing—affect the relative usage of each service.

The specifics of the process can be found in the report titled Project1_1356157

Notebooks Summary downloading_data.ipynb Outlines the acquisition of trip records and weather data. Includes code for getting and storing the data (parquets)

data_preprocessing.ipynb Covers cleaning and transformation steps, including handling missing values, aggregating trips by hour, joining weather data and generating derived features for analysis.

visualisations.ipynb Presents plots used for Exploratory data analysis.providing descriptive insights that motivated the choice of models.

regression_model.ipynb Implements regression models to quantify the effect of time, weather, and other variables on the ratio of Yellow Taxi to HVFHV trips.

RF_model.ipynb Applies a Random Forest model to assess feature importance.

Clone the repository and install the required packages:

https://github.com/cspanger64/Project1_MAST30034
pip install -r requirements.txt

Done for MAST30034 project 1 2025
