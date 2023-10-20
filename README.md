# Data Cleaning NYC Shootings Data
![NYC Logo](https://i.pinimg.com/originals/11/54/50/115450a179130f8cd1c647dd57cffde2.jpg)

This is the data cleaning code for a NYC Shootings dataset that is used for my NYC Shootings Tableau Dashboard project.

Link to the Dataset: [Click Here](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8)



Link to Tableau Project: [Click Here](https://public.tableau.com/app/profile/andy.li5977/viz/NYC_ShootingsDashboard/HomeDashboard)

## Data Cleaning Approach
- Loaded the dataset into a Pandas dataframe in a Jupyter Notebook for data cleaning
- Checked for outlier values and nulls in each column, all outlier values were fixed and null values were filled in
- Removed unnecessary columns and filtered out rows of data that were not needed for my Tableau dashboard
- Changed the structure of the original dataset by splitting it into two seperate CSV files that can be joined together in Tableau

## Files in this Repo
- NY_Shootings.csv: The original NYC Shootings CSV dataset downloaded from NYC Open Data
- clean_ny_tableau.ipynb: The data cleaning code for the original dataset
- shootings_tableau.csv: One of the CSV files resulting from the data cleaning
- incidents_tableau.csv: The other CSV file resulting from the data cleaning, shootings_tableau.csv and incidents_tableau.csv can be joined together




