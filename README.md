# MIST4610-Project-2-Group-5

## Team Name: 
62755 Group 5

## Team Members:

## Team Members:
1. Armaan Bhasin [@armaanbhasin](https://github.com/ArmaanBhasin698/MIST4610Project2/tree/main)
2. Colby Cannizzaro [@colbycannizzaro](https://github.com/colbycannizzaro/MIST4610GroupProject2/tree/main)
3. Evan Liu [@evanliu]([https://github.com/evanl0l/4610](https://github.com/evanl0l/Project2)
4. Theresa Nguyen[@theresanguyen](https://github.com/theresaanguyen/MIST4610-Project-2-Group-5))
5. Allison Ramirez Diaz [@allisonramirezdiaz](https://github.com/agr56264/MIST4610-Group-Project-2/tree/main)
   
## Description of dataset:

This dataset consists of the total number of arrests and their characteristics in NYC by the NYD(New York Police Department) from January 1, 2025 to November 1, 2025.  The data is obtained from data.gov(https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date) and reviewed by the Office of Management Analysis and Planning. Each record in the data is assigned an arrest key, which has a number(whole) data type. Following the arrest key is the arrest date with a date data type. There is also a 3-digit classification code(PD_CD) and a general 3-digit classification code(KY_CD), both of which are a number(whole) data type. Next are descriptions of the classification associated with each code(PD_DESC and OFNS_DESC) that are both String data type. There is also information on the law code charge, level of offense, and borough of arrest; these columns have String data types. Following this is the precinct the arrest occurred in and the jurisdiction code, both having number(whole) data type. Additionally, there are demographic columns covering the perpetrator’s age group, sex, and race that all have String data type. The dataset also includes the location of each offense by x-coordinate, y-coordinate, latitude, longitude, and point location. Both coordinates have a data type number(whole), latitude and longitude with data type geographic(latitude and longitude), and point location in data type String.

<img width="498" height="392" alt="image" src="https://github.com/user-attachments/assets/bcb2f1e0-58b6-478f-a718-cf754c0e6b17" />


## Question 1:

Question: What is the relationship between borough and crime severity in New York City?

Importance: 

Understanding the relationship between borough and crime severity is important because it reveals not only how much crime occurs across New York City, but what types of offenses are driving those differences. Our analysis shows that misdemeanors make up the majority of arrests in every borough, suggesting a consistent citywide emphasis on lower-level enforcement. At the same time, meaningful variation emerges when we compare severity levels: for example, Brooklyn records more felony arrests than Manhattan, while Manhattan has relatively fewer serious offenses but a different mix of lower-level crimes. These differences likely reflect variations in population density, daily activity patterns, and borough-specific policing practices. By examining severity rather than total arrests alone, we gain a clearer understanding of how community characteristics and enforcement strategies shape public safety outcomes across the city. By knowing which boroughs have the highest rate of felonies, we can better allocate our resources to the areas that need it the most.

<img width="252" height="407" alt="image" src="https://github.com/user-attachments/assets/f8285854-6756-424e-9e7d-deeafa1e61a5" />



Our first graph illustrates the breakdown of each borough's crime rate by crime severity. 

### Insights Derived
1. Misdemeanors make up the majority of arrests in every borough.
2. If you were the NYPD Police Commissioner, you should allocate most of your resources to the Bronx.
3. Brooklyn and Manhattan have a similar total crime rate, but for different reasons.
4. If you wanted to move to the safest part of New York City, you should move to either Staten Island or Queens.

## Question 2:

Question: Which borough has the highest count of felony assault charges? Which age group from that borough contributed the most?

Importance: 

Knowing the age group that commits felony assaults the most can let NYPD determine solutions such as education programs to reduce instances of assault. This could reduce the amount of arrests for this crime, which is the offense that is committed most across the 5 boroughs.

<img width="528" height="394" alt="image" src="https://github.com/user-attachments/assets/42782d3c-dfdf-40f7-a484-2f6a5484d81b" />

For the first graph, we visualized the data for several age groups, and we can see the total crime rates per borough. 

<img width="611" height="431" alt="image" src="https://github.com/user-attachments/assets/3b896db0-8499-4c60-be4c-e39bf3a552ae" />

For our second graph, we decied to magnify the age group 25-44 because it had the highest total crime rate for felony assault. We drew conclusions from this analysis to support our insights

## Insights Derived: 
1. Increase police staffing in the urban regions of Brooklyn to reduce the instances of assaults committed by people ages 25-44.
2. The R-squared indicates  this model can be used to predict number of felony assaults in  the remaining months of the year.  Enable proactive planning instead of direct approaches.


## Manupulations applied to the data set for analysis:

As part of the analysis, we made a couple of adjustments to help the data tell a clearer story. We added each borough’s population so we weren’t just comparing raw arrest numbers without context. From there, we calculated a new variable, the crime rate per 1,000 residents, by dividing the number of felony assault arrests by the population and multiplying by 1,000. This gave us a fair way to compare boroughs of different sizes and see where felony assaults were happening at a higher rate relative to the number of people living there. These steps helped us understand the data more accurately and made the comparisons between boroughs much more meaningful.

## Analysis
This dataset details all NYPD arrests from January 1 to November 1, 2025, including borough, offense severity, and demographics. Our analysis found that the Bronx has the highest felony rate per capita, while Queens and Staten Island are the safest overall. For felony assaults, Brooklyn recorded the highest total, driven primarily by the 25–44 age group. These findings help identify where crime is most concentrated and guide resource allocation and forecasting for public safety.

## Tableau packaged workbook

Our packaged workbook with the above visualizations is attatched in this repository.
