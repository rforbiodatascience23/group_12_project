# group_12_project_

Final group project for Group 12 in R for Bio Data Science course.
## Project Contributors
s223712 - Arlinda96
s222785 - jadth

## Description

Based on [A global dataset of pandemic- and epidemic-prone disease outbreaks](https://www.nature.com/articles/s41597-022-01797-2).

These datasets contains the raw data from 2721 DONs (Disease Outbreak News) extracted from (http://www.who.int/emergencies/disease-outbreak-news). 
It represents information from 1996 to March 2022 (last DON was registered on 25 March 2022).

And data of CoVid-19 outbreaks extracted from (http://www.covid19.who.int).

The outbreak data is then merged with geospatial data from: (https://public.opendatasoft.com/explore/dataset/world-administrative-boundaries/export/).

In addition to these data, we used data from the world bank, to incorporate data on socio-economic status of the countries 
[here](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators).


## Aim
The aim of this project is to 
  - reproduce the dataset from the article
  - reproduce some of the graphics from the article
  - add socio-economic data, to explore relation between outbreaks and country income
  - generate novel data-analysis and graphics

All of it in tidyverse R codes. 

## Data

The outbreak-data used in this project can be found [here](https://figshare.com/articles/dataset/A_global_dataset_of_pandemic-_and_epidemic-prone_disease_outbreaks/17207183)

1. Download DiseaseOutbreaks.7z and open the file on your local devise (as uploading zipfiles is not possible on the R server solutioin) 
2. Upload the following CSVs into \_raw folder (create folder or 01_load.qmd will create it and advise adding files):

            DONsRaw.csv
            COVIDOutbreaks.csv
            Outbreaks.csv
            UniqueDONs.csv
            icd1011.csv
            isocodes.csv

The geospacial data is found [here](https://public.opendatasoft.com/explore/dataset/world-administrative-boundaries/export/)

3. Download and upload the following CSV file into \_raw folder:

            world-administrative-boundaries.csv

From the world data bank [here](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators): 

3. Download WDI_CSV.zip and open it on your local devise. 
4. Upload the following CSV into \_raw folder:

             WDICountry.csv

5.  Run 01_load.qmd in R folder to extract the files and create dataframes for each file.
