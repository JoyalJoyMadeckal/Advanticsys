# Advanticsys

## Background

Project Partner : Advanticsys

Partners are specialized in field of data monitoring and system

They provide solutions by providing monitoring and controlling products that enhance services in several industries

Solar power plant consist of set of solar panels connected to inverters which is connected to main powerhouse

Solar panel produce DC power and with help of inverter that power is converted to AC power


## Problem definition and aim

Objective is to identify potential anomalies if present, in solar plant in the new built Bangalore, India

Partners identified; solar panels does not generate enough energy after some interval

Potential anomalies which can lead to low power generation

Some issues they encountered are : Failed PV module, reduced revenue, reputations damage and more labor cost for inspection

We will achieve with the help of statistical analysis, Machine learning predictions and data visualization through Tableau


## Data

Today_Energy 
Total_Energy
Inv_Temp - Inverter temperation recording
WMS01_Irradiance - for inverter 01 to 05
WMS01_Temp - for inverter 01 to 05
WMS02_Irradiance - for inverter 06 to 10
WMS02_Temp - for inverter 06 to 10


## Report Updating Working Process

link to GitHub working files
https://github.com/Lu3302/Advanticsys/tree/main


### Step 1 - Download 'Final Root Folder' from GitHub


### Step 2 - Load yearly input files into the folder: 'Final Root Folder/Data_Raw_Data'

### Step 3 - run 'Working File 1 Raw_Data_cleansing_and_save_for_prediction.ipynb' file to merge all data into one data frame for energy production prediction


run the function 'saveCleanData(year)' for each year in the 'Data_Raw_Data' folder

output will be saved in the folder 'Final Root Folder/Data_Clean'

### Step 4 - run 'Working File 2 Predictions.ipynb' to make prediction, the predicted energy production will be saved in the folder 'Final Root Folder/Data_Predictions'


### Step 5 - run 'Working File 3 Summarise_Data_Into_15_Mins_interval_and_conduct_statistical_analysis.ipynb' to combine actual data and prediction data together in one csv file. The combined file will saved in the folder 'Final Root Folder/Data_Output'

### Step 6 - open tableau report 'Abnormal Detection Report.twb', connect data scource to the output file created in step 5 in the folder 'Final Root Folder/Data_Output'



## End