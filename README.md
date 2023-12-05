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
Question:

Among the 5 boroughs of New York City, which one has the highest number of assault arrests across various age groups, and how do the other boroughs differ? Additionally, considering the borough and age group with the highest assault arrests, what racial demographic shows the highest number of arrests for assault?

Importance:

Understanding the distribution of assault arrests across New York City's boroughs and various age groups, and subsequently identifying the racial demographic with the highest number of arrests within the most affected borough and age group, is of paramount importance for effective law enforcement and community well-being. This question enables a nuanced analysis that goes beyond mere crime statistics. By pinpointing the borough with the highest assault arrests, law enforcement can strategically allocate resources to address specific geographic hotspots. By looking at different age groups, we can create programs that are better suited to the needs of specific communities. Additionally, finding out which racial group has the highest number of arrests helps us have conversations about whether there might be unfair treatment happening and how we can make sure policing is fair for everyone. In essence, this question addresses not only the where and when of assault arrests but also delves into the who, providing insights crucial for fostering safer communities and promoting fairness within the criminal justice system.

<img width="1216" alt="Question 1A" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/0def6b64-46fc-4a1e-b3f1-ed234cfab3c0">

Upon completing our analysis using Tableau, the data reveals that Brooklyn has the highest count of assault arrests. The criminal offenses we selected are “Felony Assault” and “Assault 3 and Related Offenses”.  This insight is visually represented through the utilization of a stacked bar graph. Brooklyn has the most total arrests for assault of any borough at 11,164, with the Bronx just behind at 11,097. Staten Island has by far the least assault arrests, at 1,685. Across each borough, the age range with the greatest number of assault arrests is between 25 and 44 years old. Brooklyn also had the highest number of assault arrests for this age range of any borough, totaling 6,541 arrests.

<img width="1213" alt="Question 1B" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/bcc61cda-a546-49a7-9ae6-363507a26808">

In order to further our investigation, we looked at the racial distribution of arrests in Brooklyn for those aged 25 to 44. This extra layer of information is helpful because it offers a more complex picture of the demographics associated with these arrests. This helps identify any potential disparities or patterns that can guide focused intervention efforts through social programs and advance equity in law enforcement procedures.


## Question 2:
Question:

Which months in the current year have witnessed the highest number of arrests, and how do they compare to the estimated arrest totals for remaining months of 2023? For the month with the highest number of arrests, what specific offenses were most frequently cited in those arrests?

Importance:

Understanding the months in the current year with the highest volume of arrests and identifying the specific offenses most commonly associated with those arrests is vital for law enforcement strategies and community safety. This question provides a complex viewpoint that is essential for making well-informed decisions, going beyond a simple examination of arrest numbers. Law enforcement can more efficiently deploy resources by identifying the months with higher arrest rates and concentrating on times of increased criminal activity.

This information is a powerful tool for raising public awareness. Knowing which months have higher arrest rates can help people be more vigilant and take preventative action during these times, improving both personal and community safety. By delving deeper into the particular crimes that are most commonly reported in those arrests, the second half of the question expands on the first by offering more context. Understanding the types of crimes makes it possible for the public to become more informed about the kinds of criminal activity that are common throughout particular months.

<img width="1219" alt="Question 2A" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/79731491-3ae8-4041-890d-db10ed20206b">

We created a visual representation of the total arrest counts per month using a line graph. January through August contain actual data from the dataset, while September through December are estimates based on Tableau’s forecasting tool. May clearly displays the highest arrest count, while February dips low on the graph, reflecting the lowest arrest count. Based on our analysis law enforcement can focus on increasing visibility and presence in areas during May, the month identified with the highest number of arrests.

<img width="1225" alt="Question 2B" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/9e0ab630-a561-4ef3-b587-2d18033fcff0">


In order to shed more insight on the most common offenses, we expanded our analysis by examining the most common crimes for May because it is the month with the most arrests. According to our analysis, assault was consistently the most common offense, with petit larceny coming in second. This information is essential because it gives law enforcement a thorough grasp of the kinds of crimes that frequently lead to arrest rates. Law enforcement agencies can tailor their strategies and allocate resources effectively to address these specific challenges. 


## Manipulations Applied to the Dataset:
## Tableau Packaged Workbook:
