# ETL_Project
Team 9 ETL Project

We used 2 different datasets from the public platform Open Minneapolis which lead us to the 2015 Police Data. The data we use from Open Minneapolis include the following on each police incident:
* Public Address
* Precinct
* Incident Date
* Offence
* Description of Offence
* Neighborhood
* Zip code

IRS Data:
*Zip code
*Number of returns
*Income

The following sources for our datasets used:

https://opendata.minneapolismn.gov/datasets/police-incidents-2015 - For police incidents

https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi - For the IRS data



Step 1 - Cloning Repo
     
    Clone the ETL-Project Repo on to your own computer with the "git clone <insert repo url>" command.

Step 2 - This is already done, only here for completeness. Start with Step 2!
  
    First we need to add zip codes to the police data, in a jupyter notebook run Add Zip Codes.ipynb.
    We add the zip codes using the Google API and the latitude and longitude provided in the police data CSV.

Step 3
  
    In PGAdmin 
