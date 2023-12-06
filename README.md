# GEOG5995_FinalProject
Supporting information for Masters python programming module

## Background to my project
* Adult social care in its simplest terms means help with day-to-day living. This could include support for those with a learning disability, assistance to help people stay independent in their own home if struggling with mobility issues, or placements in care homes when they need round-the-clock support. In England this care is means-tested, unlike the NHS which is free at the point of contact, and where individuals are eligible for state support, this is arranged by local authorities. This means that the numbers supported per local authority can vary considerably across England.

I was keen to use open data to provide additional insight into the provision of long term adult social care in England for adults aged 65 and older, with visualisations that made it easy for the public to understand a couple of factors which might influence how this varies across the country. My intended audience is the general public, or as described in the Office for National Statistics User Personas, Inquiring Citizens who "want simply worded visually engaging summaries, charts and inforgraphics" <a href="https://service-manual.ons.gov.uk/content/writing-for-users/user-personas#inquiring-citizens">[1]</a>.

## This repository contains the following files
* jupyter notebook documenting the code and final visualisations
* downloaded adult social care activity data (ASCFR and SALT Data Tables 2021-22)
* downloaded local authority shapefile data (England_utla_2022_bgc)
* downloaded Index of Multiple Deprivation data (File_11_-_IoD2019_Local_Authority_District_Summaries__upper-tier__)

## What the code aims to do
* The notebook contains code which will outline the additional datasets I linked data with, to provide further context, and the process I followed.

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
