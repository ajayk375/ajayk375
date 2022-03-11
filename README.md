CONTENTS OF THE FILE
=======================
* [ Introduction ](#intro)
* [ Requirements ](#reqd)
* [ What's Included ](#include)
* [ File Description ](#desc)
* [ Summary of results ](#summary)
* [ Licensing, Author(s) and Acknowledgement(s) ](#acknow)

<a name="intro"></a>
## Introduction
-------------
The project is to find the factors responsible for price of a property listing on AirBNB within Seattle (US), and predict the price based on 
available data. There are few more business questions we are trying to answer,
1. What months in year 2016 had highest and lowest occupancy rate?
2. What period during 2016 are the costliest and cheapest to stay?
3. What are the different features/factors having influence on price?
4. What are the areas in Seattle with most and least occupancy rate?

<a name="reqd"></a>
## Requirements
-------------
To analyze and prepare data we have used Jupyter Notebook and following libraries:
Pandas
Numpy
Sklearn
Seaborn
Matplotlib

<a name="include"></a>
## What's Included
----------------
1. Directory: airbnb_data containing data from airbnb
2. File: AirBnB_Project3.ipnyb 
3. File: AirBnB_Project3.html
4. File: README.md

<a name="desc"></a>
## File Description
-----------------
File: AirBnB_Project3.ipynb - The files contains all the steps to predict the price of a listing. File also contains proper comments to 
understand what each step is trying to accomplish.

File: AirBnB_Project3.html - This file is the html version of Jupyter notebook.

File: README.md - Contains information about the project and GitHub Repo structure.

Directory: airbnb_data - This directory contains all the data files required for the project.

<a name="summary"></a>
## Summary of results
--------------------
We were able to find answers to some of the business questions we had initially, and the most interesting finding was about the time period when 
listings price are highest during the year, occupancy remains at lowest levels.

Occupancy in Seattle Airbnb listings remains lowest during December and highest during January which is clearly noticed in following plot -

![Occupancy Rate during year 2016](https://github.com/ajayk375/ajayk375/blob/master/Screenshot%202022-03-04%20at%2017.32.56.png)

Price of the listings are consistently high from June until December, and price is at peak during December and cheapest during January. This clearly visible
from the following plot -

![Average Price during 2016](https://github.com/ajayk375/ajayk375/blob/master/Screenshot%202022-03-04%20at%2017.27.47.png)

We also noticed that following features influence listings price the most are mumber of bathrooms and bedrooms in the listing. Following 
plot reflects that finding -

![Features impacting listings price](https://github.com/ajayk375/ajayk375/blob/master/Screenshot%202022-03-05%20at%2017.14.12.png)

For futher details, please checkout my blog on Medium - 

https://medium.com/@ajay1.kumar/another-data-science-project-3cd7b2eb476b

<a name="acknow"></a>
## Licensing, Author(s) and Acknowledgement(s)
--------------------------------------------
Licensing: Open Source and available in public GitHub Repository - https://github.com/ajayk375/ajayk375

Author: Ajay Kumar

Acknowledgements: Udacity (Citizen Data Scientist)
