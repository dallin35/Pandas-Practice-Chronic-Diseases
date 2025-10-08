# CIS3330-CODE-5-Pandas-Practice-Disease-Database

## Instructions

The csv file for this assignment is too large to upload to GitHub. In order to complete the assignment, download the US_chronic_diseases.csv file from Blackboard, then copy it into the same folder as your assignment.py file.

In this coding assignment, your will practice data filtering and retrival from a CSV file using the Python module Pandas. To complete the assignment, your program must have the following functions:

* `get_melanoma_mortality_information_by_state`
  + The function receives the **state_code in lower case**
  + To filter the informationn use the column **"Question"** and the value **"Melanoma, mortality"**
  + The function should return **mean value** of the mortality for melanoma in a given **state** 
  + The value of the mortality rate can be found under **"DataValueAlt** 
  + Round the average value of the mortality rate to **2** decimal numbers
* `get_asthma_mortality_information_by_state`
  + The function receives the **state_code in lower case**
  * To filter the informationn use the column **"Question"** and the value **"Asthma mortality rate"**
  + The function should return **mean value** of the mortality for asthma in a given **state** 
  + The value of the mortality rate can be found under **"DataValueAlt** 
  + Round the average value of the mortality rate to **2** decimal numbers
* `get_chronic_liver_mortality_by_state`
  + The function receives the **state_code in lower case**
  * To filter the informationn use the column **"Question"** and the value **"Chronic liver disease mortality"**
  * Additionally use the column **"DataValueType"** and value **"Crude Rate"** tu filter the information
  + The function should return **mean value** of the chronic liver mortality for a given **state** 
  + The value of the mortality rate can be found under **"DataValueAlt** 
  + Round the average value of the mortality rate to **2** decimal numbers
* `get_missing_values_count_by_state`
  + The function receives the **state_code in lower case**
  + The function should return number of records that are missing
  + You can use the functions **"isnull().sum()"** to count the missing values under the column **"DataValueAlt** 
## Important notes

* The state_code is stored under the column **'LocationAbbr'**
* The mortality rate is stored under the column **'DataValueAlt'**
* Test your functions under the if statement: `if __name__ == "__main__":`.
* Use the built-in function round() to round decimal numbers. For example: `round(0.5556,2)` should return **0.56**

## Copyright disclosure

* The file `US_chronic_diseases.csv` records the "U.S. Chronic Disease Indicators (CDI)" and was obtained from Data.Gov [https://catalog.data.gov/dataset/u-s-chronic-disease-indicators].
* The `US_chronic_diseases.csv`is available in Blackboard.
