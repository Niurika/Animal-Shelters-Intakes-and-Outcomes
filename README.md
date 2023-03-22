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

national_totals.ipynb - compare nation wide shelter intake and outake for each year

symmary_df.ipynb - create a map of adoption rate per state

Regional_Data.ipynb - comparison of intake/outake between regions

## Built With:
* Python 
* Pandas 
* Matplotlib


## Contributors

Hannah Kim, Georgia Myers, Kyle Hunstein, Niurika Gonzalez
