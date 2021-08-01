# Starbucks Promotion Optimization




### Table of Contents

1. [Project Description](#project)
2. [Installation](#installation)
3. [File Descriptions](#description)
4. [Result](#result)
5. [Credit](#credit)


## Project Description<a name="project"></a>
This portfolio exercise was originally used as a take-home assignment provided by Starbucks for their job candidates. This exercise involves an advertising promotion that was tested to see if it would bring more customers to purchase a specific product priced at $10. 
It costs the company 0.15 to send out each promotion. Full details about these metrics are provided in the notebooks.
The goal of this repository is to display how to analyze an experiment, 
and how to leverage the results to optimize a promotional strategy 
which can yield positive results for the company.

Udacity provided a script to assess the promotional strategy devised.

## Installation<a name="installation"></a>

The necessary libraries to run this project, along with Python 3.7:
* numpy
* pandas
* sklearn
* scipy
* matplotlib
* itertools
* imblearn
* xgboost

## File Description<a name="description"></a>

This repository contains the following files:
* **Starbucks.ipynb**: a Jupyter notebook which contains the repoducible analysis on the
Starbucks dataset
* **test_results.py**: a scoring script provided by Udacity to determine the IRR and
NIR of the promotional strategy on the test dataset
* **train.csv**: the training data provided by Starbucks
* **Test.csv**: the test data provided by Starbucks that Udacity uses in their scoring
script
* **LICENSE**: a license for personal and commercial use

## Result <a name="result"></a>
Model performance: 
* **IRR = 0.0203**
* **NIR = 260.00**


## Credit<a name="credit"></a>

The data was provided by Udacity as part of their Data Scientist Nanodegree.
They also provided the initial prompt for the exercise, along with the logo and 
mathematical definitions for the metrics of interest.

