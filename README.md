# House Prices - Predictions

## Overview of the Project

  * Develop and evaluate a model while using tools like PGadmin and Tableau to predict house prices in Ames, Iowa. We will use all the different information from the train.csv dataset to predict a house price depending on different criteria we give the model.
  

## Tools used 

  * Python
  * PGadmin/SQL
  * Jupyter Notebook
  * Visual Code
  * Tableau

## Data
The dataset used in this project comes from a Kaggle prediction competition (Machine Learning), .csv files compiled by Dean De Cook for educational purposes. 

The data observes during a period between 2006 and 2010, 80 features of many physical attributes ([data_description.txt](https://github.com/JabboRamirez/BootCamp_Project/files/7867192/data_description.txt)) of 1459 residential properties in Ames, Iowa, that are taken into consideration when buying a house, access the data base in the following links [train.csv](https://github.com/JabboRamirez/BootCamp_Project/files/7867205/train.csv)
[test.csv](https://github.com/JabboRamirez/BootCamp_Project/files/7867206/test.csv). 

To address the question of how much a house cost based on the different features, the data was processed/cleansed by assessing wether the feature is key or not to determine  the prices of the house. 


## Communication Protocols

Python -> Jupyter noteboook -> PgAdmin -> SQLAlchemy -> Tableau

## Outline

* First, the information from both  [train.csv](https://github.com/JabboRamirez/BootCamp_Project/files/7867205/train.csv) and [test.csv](https://github.com/JabboRamirez/BootCamp_Project/files/7867206/test.csv) was ran through a code in python/Jupyter Notebook to clean the data of null values and irrelevant information that doesnt affect the price of any of the houses. 
* Second, we applied the clean file train_clean.csv to PGadmin by running a SQL code to create a database. 

## Links to Final Project
[Presentation](https://docs.google.com/presentation/d/1ar3zJimIbIBp_f1oIs8sqTa2pa7_hjVMsRKenYktXIE/edit#slide=id.g10e9a3a0275_0_37)
[Tableau Public Story](https://public.tableau.com/app/profile/hanna.bustamante/viz/HousingPricePrediction/Story1)
