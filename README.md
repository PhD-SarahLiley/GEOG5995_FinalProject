# GEOG5995_FinalProject
Supporting information for Masters python programming module

## Background to my project: How does the number of older people supported by the local authority for social care needs vary across England, and why might that be?
Adult social care in its simplest terms means help with day-to-day living. This could include support for those with a learning disability, assistance to help people stay independent in their own home if struggling with mobility issues, or placements in care homes when they need round-the-clock support. In England this care is means-tested, unlike the NHS which is free at the point of contact, and where individuals are eligible for state support, this is arranged by local authorities. This means that the numbers supported per local authority can vary considerably across England.

I was keen to use open data to provide additional insight into the provision of long term adult social care in England for adults aged 65 and older. This would be achieved with visualisations that made it easy for the public to understand a couple of factors which might influence how this varies across the country. My intended audience is the general public, or as described in the Office for National Statistics User Personas, Inquiring Citizens who "want simply worded, visually engaging summaries, charts and infographics" https://service-manual.ons.gov.uk/content/writing-for-users/user-personas#inquiring-citizens.

## This repository contains the following files
* jupyter notebook documenting the code and final visualisations
* downloaded adult social care activity data (ASCFR and SALT Data Tables 2021-22) from https://digital.nhs.uk/data-and-information/publications/statistical/adult-social-care-activity-and-finance-report/2021-22
* downloaded local authority shapefile data (England_utla_2022_bgc) from https://borders.ukdataservice.ac.uk/bds.html. To note, these files should be moved out from the folder before running the notebook.
* downloaded Index of Multiple Deprivation data (File_11_-_IoD2019_Local_Authority_District_Summaries__upper-tier__) from https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019

## What the code aims to do
* The notebook contains code which outlines the process undertaken to produce two visualisations to help the general public better understand "How does the number of older people supported by the local authority for social care needs vary across England, and why might that be?"

* I used the five stages of data science process as per the course materials; Collection, Cleaning, Exploratory Data Analysis, Model Building and Model Deployment, adopting an iterative process, with checks after each step, so that if any issues emerged, they could be quickly rectified.
  
## Further information required to run code and reproduce analysis
This code assumes that the spatial environment has already been loaded, and that the following packages are already installed, ready for import.

* seaborn 
* matplotlib.pyplot 
* pandas 
* numpy 
* scipy 
* geopandas 

## Further information on Adult Social Care
* Further Adult Social Care data is available here:https://digital.nhs.uk/data-and-information/data-tools-and-services/data-services/adult-social-care-data-hub
* The Kings Fund have created an explainer on Adult Social Care which provides a useful introduction for those unfamiliar with the topic :  https://www.kingsfund.org.uk/health-care-explained#social-care
