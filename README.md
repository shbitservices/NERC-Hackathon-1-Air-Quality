# A report for NERC- COVID-19 Hackathons (Hackathon 1: Air Quality) challenge
This repository contains a report and the associated datasets created for "Hackathon 1: Air Quality" organised by the Natural Enviornment Research Council (NERC) and Cranfield University.

## Table of contents:

- [1.0 Overview](#overview)
- [2.0 List of files in this repository](#List-of-files-in-this-repository)
- [3.0 How to run the Jupyter notebook](#How-to-run-Jupyter-notebook)


## Overview
This report has been prepared in response to the Covid-19 Hackathon challenge organised by the Natural Environment Research Council (NERC) and Cranfield University.

This hackthon report provides an overview of the data analysis that has been carried out to explore the relationship between air quality and the severity of COVID-19 infection. 

The datasets used in this study, have been gathered from multiple data sources, including [aqicn.org](https://aqicn.org). The visualisations presented in this report have been developed using Python programming language and Jupyter Notebook environment.

Key steps followed to prepare this report are:

1. Define a solution approach
2. Acquire relevant datasets
3. Explore, clean and wrangle datasets
4. Identify patterns and create visualisation
5. Summerise the key findings 
![alt text][logo]

[logo]: analysis_workflow_h1.JPG "workflow"

A detailed description of each step can be found in this [jupyter notebook](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/code/H1-Covid-19-and-Air-Quality.ipynb). This notebook is stored in the `code` sub-directory of this repository. The report has been prepared by running each of the cells in this notebook in a jupyter notebook environment spawned from Anaconda Navigator.  

##  List of files in this repository

This repository contains the following files. A short description of each file is also given below.

+ [code/H1-Covid-19-and-Air-Quality.ipynb](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/code/H1-Covid-19-and-Air-Quality.ipynb) - This is the main report. This file is a jupyter notebook, which contains the detailed data analysis results and the associated python code. 

+ [code/H1-Covid-19-and-Air-Quality.html](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/code/Air-Quality-V2.html) - This file is an HTML version of the above jupyter notebook. For better readability, please use this file. 

+ [data/airqua_data_till_may.csv](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/data/airqua_data_till_may.csv) - This file has been downloaded from AQICN website. This file contains median and standard deviation of each air quality parameters recorded everyday for different cities. 

+ [data/covid_data_till_may.csv](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/data/covid_data_till_may.csv) - This file contains the daily total number of COVID-19 infected cases at a local authority area level in the UK.

+ [data/df_aq_cd_may_data.csv](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/data/df_aq_cd_may_data.csv) - This file has been created by joining the above air quality and Covid-19 input files.

+ [data/df_aq_cd_may_data_sorted_with_metric.csv](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/data/df_aq_cd_may_data_sorted_with_metric.csv) - This file has been created from df_aq_cd_may_data.csv.  Rows with blank values have also been dropped from this combined file and a new set of metrics has been added to this file. This file has been created from an intermediate file df_aq_cd_may_data.csv. 

+ [data/aq_day1_joined_cd_day7_with_metrics.csv](https://github.com/shbitservices/NERC-Hackathon-1-Air-Quality/tree/master/data/aq_day1_joined_cd_day7_with_metrics.csv) - This file has been created for iteration 2. Please refer to section 4.2.1 for details on this dataset. 

## How to run this Jupyter notebook

The notebook (name of the notebook) can be run in a Jupyter notebook environment.  The following python package versions are required to run the notebook. 

+ Anaconda Navigator        1.9.7
+ Python                    3.7.3
+ scikit-learn              0.20.3           
+ seaborn                   0.9.0  
+ pandas                    0.24.2 
+ numpy                     1.16.2 


## Contact
Sirshendu Biswas (
shbitservices@outlook.com )
## References
+ https://digitalenvironment.org/home/covid-19-digital-sprint-hackathons/

+ https://www.bbc.com/future/article/20200427-how-air-pollution-exacerbates-covid-19

+ https://www.theguardian.com/environment/2020/apr/20/air-pollution-may-be-key-contributor-to-covid-19-deaths-study

+ http://www.ukatmosphere.org/dataplot/DEFRA_sites

+ [COVID-19 dataset for US](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data)
+ [COVID-19 dataset for London](https://data.london.gov.uk/dataset/coronavirus--covid-19--cases)

+ https://www.staceybarr.com/measure-up/an-insight-from-the-covid-19-metric-growth-factor/

+ https://www.worldometers.info/coronavirus/coronavirus-cases/#cases-growth-factor

+ https://www.eea.europa.eu/themes/air/air-quality-and-covid19