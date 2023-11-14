# group_12_project_

Final group project for Group 12 in R for Bio Data Science course.

## Description

Based on [A global dataset of pandemic- and epidemic-prone disease outbreaks](https://www.nature.com/articles/s41597-022-01797-2)

## Data

The data used in this project can be found [here](https://figshare.com/articles/dataset/A_global_dataset_of_pandemic-_and_epidemic-prone_disease_outbreaks/17207183)

1.  Download DiseaseOutbreaks.7z into \_raw folder

This variable is a dataset containing the raw data from 2721 DONs (Disease Outbreak News) extracted from www.who.int/emergencies/disease-outbreak-news. The dataset presents information from 1996 to March 2022 (last DON was registered on 25 March 2022).


Further, we used data from the world bank, to incorporate data on socio-economic status of the countries: 
[here](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators)

2. Download WDI_CSV.zip into \_raw folder

3.  Run 01_load.qmd in R folder to extract the files and create a rawdons variable.
