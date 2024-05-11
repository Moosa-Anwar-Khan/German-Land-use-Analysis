# German Land use Analysis

This project was created as part of the Research Software Engineering course at the University of Potsdam. 

Land use analysis can be interesting. You may get to know which state has covered the most area for any specific purpose in a specific state or year. For example, you are doing research and you want to know that in 2017, how much area was covered for housing purpose in Bayern? If you are interested in such a type of analysis, then this project may catch your attention.

## Problem description

The project will tackle the following questions regarding land use in different states of Germany:

1. Which state has consumed the most area in total? 
2. Which purpose has consumed the most area in total? 
3. Which state has consumed the most area in terms of any specific purpose in a specific year? 
4. Which purpose should be focused more on in any specific state? 
5. What has been the trend for states throughout the years?
6. What has been the trend for specific purposes in specific states throughout the years?

## How to get started and requirements

Download the repository, make sure Python, matplotlib, and pandas are installed. The project was tested using Python 3.11.3, I cannot guarantee that it will function with a lower version.

## Running the Program

The code is stored in the src folder. The src folder consists of two Python notebooks, namely data_preprocssing.ipynb, which consists of basic data cleaning, and land_use_analytics.ipynb, which consists of the analysis.

In order to run the project successfully, you must clone the project, then run data_preprocessing.ipynb, and then run land_use_analytics.ipynb.

## Dataset

The dataset can be obtained from https://www-genesis.destatis.de/genesis//online?operation=table&code=33111-0002&bypass=true&levelindex=1&levelid=1715453491825#abreadcrumb 

The name of the dataset is soil area (actual use): states, reference data, types of use (code 331110002). It shares the area in kilometers squared used for different purposes in different years and states of Germany. For example, area used for housing in Bayern, Berlin, etc. in the period 2016–2022 can be obtained from this dataset.

The code for cleaning of the dataset can viewed in data_processing.ipynb which is located in src folder.

## MIT License
https://gitup.uni-potsdam.de/khan11/land_use_analytics/-/blob/main/LICENSE.txt

## Citation
https://gitup.uni-potsdam.de/khan11/land_use_analytics/-/blob/main/CITATION.cff