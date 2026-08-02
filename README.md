# electric-vehicles
Jupyter Notebook with an analysis of electric vehicles for the state of Washington

# Purpose:
This notebook consolidates and cleans data which can be used for the analysis of electric vehicles in the state of Washington.

# Data:
The data is pulled from three sources
 - [Washington EV registration data](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data)
 - [US Census SAIPE State & County Estimates for 2024](https://www.census.gov/data/datasets/2024/demo/saipe/2024-state-and-county.html) (provides income)
 - [Washington Population Change by County, 2020-2026](https://data.wa.gov/demographics/WAOFM-April-1-Population-Change-and-Rank-by-County/nde6-xvwf/about_data)

The consolidated/cleaned data contains the following fields:
 - County
 - City
 - State_x
 - Postal Code_x
 - Model Year
 - Electric Vehicle Type
 - Clean Alternative Fuel Vehicle (CAFV) Eligibility
 - DOL Vehicle ID
   - a unique identifier for each vehicle
 - Median Household Income
   - median household income for the county where the vehicle is registered
 - POP_2024
   - population of the county where the vehicle is registered, according to 2024 census data

# How to run this notebook
Before running this notebook, you'll need to download the data from the links above.  
Upload the data files when prompted.  
You can either name the files according to the filenames provided in the notebook, or you can alter the notebook to match the file names of your choosing.  
Note: the US Census SAIPE State & County Estimates for 2024 will need to be converted to .csv.  

Use the resulting data for whatever analysis suits your needs.
