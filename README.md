# What Affect SAT Scores 
***
## Topic
To investigate socioeconomic factors that influence students' SAT scores 

## Data
- NYC Student SAT score (source: https://data.cityofnewyork.us/api/views/f9bf-2cp4/rows.csv?accessType=DOWNLOAD)
- NYC School Crime data (source: https://data.cityofnewyork.us/api/views/qybk-bjjc/rows.csv?accessType=DOWNLOAD)
- NYC Asthma and Drug Hospital Discharge data (source: https://health.data.ny.gov/api/views/u4ud-w55t/rows.csv?accessType=DOWNLOAD)
- NYC Census data (source: https://www2.census.gov/programs-surveys/acs/data/pums/2016/5-Year/csv_hny.zip)

## Methodology
### 1. Visulizaiton and Exploratoy Analysis
#### Map of SAT score 
<img src="https://github.com/rylanwan/What_Affect_SAT_Scores/blob/master/SAT.png" alt="alt text" width="1000" height="350">

#### Map of Crime Data
<img src="https://github.com/rylanwan/What_Affect_SAT_Scores/blob/master/crime.png" alt="alt text" width="1200" height="250">

#### Map of The Asthma Ratio and Drug Ratio
<img src="https://github.com/rylanwan/What_Affect_SAT_Scores/blob/master/health.png" alt="alt text" width="1000" height="350">

#### Map of the Distributon of Household Income 
<img src="https://github.com/rylanwan/What_Affect_SAT_Scores/blob/master/income.png" alt="alt text" width="420" height="350">

#### Correlation Matrix for SAT Scores, Crime Rate, Health features, and income
<img src="https://github.com/rylanwan/What_Affect_SAT_Scores/blob/master/Correlation.png" alt="alt text" width="350" height="350">

The covariance matrix shows that despite the yellow diagnoal area(variable against itself), SAT features have very strong positive correlation with each other, and both of them have strong positive correlation with crime data, stronger with average crime data than individual crime data. Both SAT features have a weak positive correlation with household income. Other than SAT features, the five AVERAGE crime features have very strong postiive correlation with each other as well. Another five crime features have strong postivie correlation with each other as well. The crime data almost have no correlation with medical data and household income.

### 2. Modeling
  - Linear Regression 
  - Random Forest
