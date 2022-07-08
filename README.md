# COMP20008 Data Science Project

## Authors
Baichuan Yu 1174260\
Jie Xie 1174437\
Kate Zhang 1056915\
Lihang Zhang 792208


## Description
This project explores and investigates the research question, ‘Which suburb in Victoria provides the strongest sense of security to local residents?’ And provide scores and ranking for each local government area in Victoria based on their performances.


## Dependencies

`pandas` `matplotlib` `numpy` `IPython` `seaborn` `geopandas` `sklearn`


## Usage
* `LGA15_Community_Strength.csv` `yearending31dec2014-offences.csv` `offence_rate.csv`: raw datasets
* `vic-security.csv`: preprocessed data
* `vic-security-score.csv`:  csv with scores for each factor with modified column names
* `overall-score.csv`:  csv with overall scores for each local government area in Victoria
* `vic_lga_polyhon_shp`: file needed for geopandas in order to generate the choropleth

## Dataset
* Year ending 31 December 2014 | Crime Statistics Agency Victoria. (2015). [Dataset]. Crime Statistics Agency. https://www.crimestatistics.vic.gov.au/crime-statistics/historical-crime-data/year-ending-31-december-2014
* Torrens University Australia - Public Health Information Development Unit. (2015). LGA15 Community Strength - 2014 - AURIN Data [Dataset]. AURIN. https://data.aurin.org.au/dataset/tua-phidu-tua-phidu-2015-lga-aust-community-strength-2014-lga2011

### Crime Statistics Agency Data
The offence rate in each local government area(LGA) in Victoria from 2010 to 2014.

### LGA15 Community Strength 2014 Data
* `cul_2_asr`: The estimated number of people aged 18 years and over who disagree/strongly disagree with acceptance of other cultures
* `discrim_past_yr_2_asr`: The estimated number of people aged 18 years and over who, in the past 12 months, felt that they had experienced discrimination or have been treated unfairly by others 
* `gsup_2_asr`: The estimated number of people aged 18 years and over who are able to get support in times of crisis from people outside the household
* `psup_2_asr`: The estimated number of people aged 18 years and over (or their partner) who provide support to other relatives living outside the household
* `saf_2_asr`: The estimated number of people aged 18 years and over who felt safe walking in their local area after dark 
* `vol_past_yr_2_asr`: The estimated number of people aged 18 years and over who did unpaid voluntary work in the last 12 months through an organisation 
