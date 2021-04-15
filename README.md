# Effect of suicide rates on life expectancy
Experiment performed by Filip Zoubek (https://orcid.org/0000-0003-1269-2668).

## Table of contents
* [General info](#general-info)
* [Data](#data)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
In 2015, approximately 55 million people died worldwide, of which 8 million committed suicide. In the USA, one of the main causes of death is the aforementioned suicide, therefore, this experiment is dealing with the question of how much suicide rates affects the statistics of average life expectancy.
The experiment takes two datasets, one with the number of suicides and life expectancy in the second one and combine data into one dataset. Subsequently, I try to find any patterns and correlations among the variables and perform statistical test using simple regression to confirm my assumptions. 

## Data
The experiment uses two datasets - WHO Suicide statistics and WHO life expectancy, which are under license. Please look at the license file. You can find the used dataset in the folder 10_Data.

## Technologies
The experiment was performed with Python 3.7.9 and using libraries pandas, numpy, seaborn, matplotlib, statsmodels, scikit-learn. You can find the exact versions in the file requirements.txt, through which you can also set up the python environment. 

## Setup
The experiment is written in the Jupyter notebook, which is available for python as well, and through which the experiment can be performed.

Install Jupyter notebook
```
$ pip install jupyterlab
```

How to run experiment
```
$ cd <PATH-TO-FILE-WITH-EXPERIMENT-FOLDER/effect-of-suicide-rates-on-life-expectancy
$ jupyterlab
```

Go to the folder 20_Code, where is code for the experiment and run it.