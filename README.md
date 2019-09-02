# Starbucks Capstone Project
This project is part of the Udacity Data Scientist Nanodegree. Starbucks is interested to study previous marketing offers and their impact on different types of customers in order to better directing their marketing strategies. The dataset used in this project contains simulated data that mimics customer behaviour on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). 

## Problem Statement
People respond to offers differently and it’s important to distinguish between different types of people to make the most out of the platform. Some get annoyed from constantly receiving notifications for something they’re interested in which might in result affect customer satisfaction. In this project, I will study the factors affecting the customer choice to whether respond to an offer or not and build a machine learning model to predict the customer’s response. I am not a coffee fan but I’m assuming age and income will are important factors. On the other hand, I don’t believe gender will have an impact on the prediction.


## Installation
No libraries are needed other than the ones provided by Anaconda. The code was built on Python 3.

## File Descriptions
* **data**: This folder contains the input data for this project as json files
* **/data/portfolio.json**: This file contains information about each offer
* **/data/profile.json**: This file contains demographic information for each customer
* **/data/transcript.json**: This file conatains records for transactions, offers received, offers viewed, and offers completed (too big to be uploaded)
* **Starbucks_Capstone_notebook.ipynb**: This is the jupyter notebook file used to write all the code required to compplete this project.
* **visuals.py**: This file was given to us, Udacity Data Scientist Nanodegree Student in our first project to help us visualise our results. I used it in this project to compare between different models' performances.
* **clean_dataset.csv**: this file is generated by the starbucks jupyter notebook to save the cleaned data for future analysis
* **pic1/pic2.png**: these images were used by Udacity in the jupyter notebook instructions


## Results
Using Random Forest algorithm, the accuracy and fscore of the best model were 0.6695 and 0.6244 respectively. The most influential factores on offers' success are ordered by the model as follows:
- Difficulty
- Membership year 2018
- Channel - social
- age
- income
You can find more about the analysis either on the Jupyter notebook in this repository or on this [blog](https://asunaidi.github.io/starbucks-capstone-project/).

## Licensing, Authors, Acknowledgements
I Must give credit to Udacity for such great projects and Starbucks for allowing us to work on their data.

