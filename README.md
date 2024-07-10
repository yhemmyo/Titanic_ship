# Titanic_ship
### Project Overview
This dataset is on the titanic ship which occurred in 1912, the titanic was said to break apart after striking an iceberg which led it to sink to the bottom of the ocean while resulting in deaths. The major focus of this analysis will be on the demographics of people who survived, what’s there an advantage to surviving?
### Data Source
Data was gotten from [Kaggle](https://www.kaggle.com/c/titanic)
### Tools
Excel
### Data Preparation

- Duplicates were searched for and none was found 
- Preparation involved trimming and keeping the data in a proper form using the TRIM and PROPER formula
- There were missing values, they were ignored as it was mostly Cabin and few were Age, Cabin is negligible.
- Age was grouped into ranges with intervals of 10.
### Exploratory Data Analysis
The aim of the analysis is to find the classes or type of people who survived the crash and if there are factors which affected the chance of surviving, the target questions were:
1. Did the Gender, Age and presence of relative play a role in those who survived or not?
2. Did Ship class, fare play a role in those who survived or not?
### Data Analysis
Fields given in the data are:
PassengerID (categorical), Name of passenger (categorical), Survived (Boolean 0-No, 1-Yes), Ticket class as Pclass (categorical), Sex (categorical), Age (numerical), Number of siblings and spouses aboard as SibSp (numerical), Number of Parents and Children aboard as Parch (numerical), Ticket number as ticket (categorical), Passenger fare as fare (numerical), Cabin number as Cabin (categorical) and Port of Embarkation as Embarked (categorical).
### Findings
- 41% survived the sink while 59% could not survive
- Chances of survival increased with the Ticket class, i.e the higher the ticket class, the higher the chance of surviving. Let’s take a look at the percentage of survivor for each ticket class-

1st class-62.96%
2nd class-47.28%
3rd class-24.24%
- 74.2% of the female on the ship survived the sink while only 18.9% of the male survived
- Children within the range of 0–10 had the highest survival rate of 61.2% while the least survival rate was those within the age range of 60–70 and 70–80.
### Recommendations
- From the data, most passengers did not survive, this shows that more preventive and prescriptive measures should be taken next time by the crew to avoid this number of deaths.

- Passengers whose safety is paramount should book 1st class as it seems to receive top priority from crew, same as children between the age of 0 and 10.
### Limitations
More details on the passengers could have helped to make more informed decision
### References
- [Kaggle](www.kaggle.com)
  
