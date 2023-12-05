# MIST 4610 Group Project 2

## Team Name:
39217 Group 7
## Team Members
1. Dylan McMorrow [@DylanMcMorrow](https://github.com/dylanmcmorrow5/MIST4610GroupProject2.git)
2. Aafreen Anjum [@AafreenAnjum]
3. Jack Drummond [@JackDrummond]
4. Ishi Gupta [@IshiGupta]
5. Miral Lakhani [@MiralLakhani]


## Description of Dataset:
Our dataset shows all of the NYPD arrest records in the 5 boroughs of New York City for the current year (January 2023 through September 2023). We obtained our dataset from US Data.gov website (https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date). The data contains dimensions that include information on the date of the arrest, offense description, and corresponding law code. The date dimension is of type date, while the offense description and law code are of type string. There are also columns to record the demographics of the arrested individuals, including gender, race, and age group, which are all of type string. The dataset divides the age groups into 5 different categories (<18, 18-24, 25-44, 45-64, and 65+). There are also multiple columns describing location data. The “Arrest_Boro” column is type string, and specifies which of the 5 boroughs in New York City the arrest took place. Each borough is depicted by a letter (“B” - Bronx, “S” - Staten Island, “K” - Brooklyn, “M” - Manhattan, and “Q” - Queens). Each record in the dataset contains a unique and randomly generated “Arrest_Key”, which is a numeric data type and serves as the primary key to identify each arrest. The “Law_Cat_Cd” dimension is of type string, and classifies the level of offense into 3 categories (“F” - Felony, “M” - Misdemeanor, and “V” - Violation). The Jurisdiction dimension is a numeric data type and specifies which jurisdiction led to the arrest. “0” represents Patrol, “1” represents Transit, and “2” is Housing. All code numbers after 2 represent jurisdictions outside of the NYPD. The Arrest Precinct is a numeric data type which represents the number of the precinct the arrest occurred at. The Ky code dimension is a numeric data type, which is a 3-digit number corresponding to the offense description. The Pd Description is a string data type, and it is a more specific description of the crime compared with the Offense Description. The corresponding Pd Code is numeric data. There are also multiple columns describing the latitude and longitude of the arrest location, which are numeric data (specifically decimals).  The X and Y Coordinate Cd columns represent the location of the arrest using the New York State Plane Coordinate System, while the Latitude and Longitude columns represent the global coordinates. For more detailed information on the dataset, please follow this link (https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc).
## Question 1:
## Question 2:
## Manipulations Applied to the Dataset:
## Tableau Packaged Workbook:
