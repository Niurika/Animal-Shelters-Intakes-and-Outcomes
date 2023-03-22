# Animal Shelter Data Project

## Background

An analysis on animal shelter data from the years of 2019-2021. We attempt to answer the question of whether Covid-19 had an impact on the shelter intakes and outcomes of animals. The data we collected from the Shelters Animals Count National Database included shelter data on canines and felines for all 50 states. 


## Visualizations Included:
Bar graphs, grouped bar graphs, pie graphs, choropleth

## Data Source
Data found in p1_animals/Resources


## Installation
Code was tested using Python 3.8.  The environment also needs pandas and matplotlib. The environment was setup as follows:

* conda create -n envpy38 python=3.8 anaconda
* source activate envpy38
* jupyter notebook

If environment does not include pandas or matplotlib then install the following from terminal:

* conda install pandas
* conda install matplotlib



## Analysis
There was a noticeable decerease in both shelter intakes and outcomes from 2019 to 2020, presumably due to the beginnig of the pandemic. We saw no signficant difference between species type (canine vs feline). This trend was observed on both national and regional levels, with US resident population in mind. 

## Featured Notebooks:

outcome_comparisons.ipynb - creates pie charts that compare the live/other outcomes of cats and dogs

<img width="1045" alt="Screen Shot 2023-03-22 at 1 00 31 AM" src="https://user-images.githubusercontent.com/110379358/226815895-c6aa393c-ea8c-4dd9-943f-7b5469541c10.png">
<img width="1031" alt="Screen Shot 2023-03-22 at 1 00 19 AM" src="https://user-images.githubusercontent.com/110379358/226815909-caf99a7b-bd4a-413d-bc3d-fc50dcb75e60.png">

national_totals.ipynb - compare nation wide shelter intake and outake for each year

<img width="1195" alt="Screen Shot 2023-03-22 at 12 56 03 AM" src="https://user-images.githubusercontent.com/110379358/226815127-3b1d5432-6190-4a1c-b3a6-9c479191bf8b.png">
<img width="1085" alt="Screen Shot 2023-03-22 at 12 55 47 AM" src="https://user-images.githubusercontent.com/110379358/226815250-a76335eb-af9e-4978-a462-75f56a9f02d6.png">


symmary_df.ipynb - create a map of adoption rate per state

<img width="1058" alt="Screen Shot 2023-03-22 at 1 00 59 AM" src="https://user-images.githubusercontent.com/110379358/226815849-8e163857-f7da-4d5b-9db1-8c3a06461dea.png">

Regional_Data.ipynb - comparison of intake/outake between regions

<img width="1065" alt="Screen Shot 2023-03-22 at 1 00 49 AM" src="https://user-images.githubusercontent.com/110379358/226815789-9183e580-49e1-4490-9d4b-8e7798b652ff.png">


## Built With:
* Python 
* Pandas 
* Matplotlib


## Contributors

Hannah Kim, Georgia Myers, Kyle Hunstein, Niurika Gonzalez
