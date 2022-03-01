# __Diamonds Selection Tool__

<p align="center"><img src="https://c.tenor.com/Ay4jVLEIo2oAAAAC/diamonds-sparkle.gif"></p>



## **Introduction**

Data analytics is oftentimes referred to as business intelligence, BI development, or product analytics. However, that is just the tip of the iceberg since the data analytics process includes activities such as data formation/creation, data cleansing, exploratory data analysis (especially this part), feature engineering, and interpretation of suggestions/predictions/results derived from advanced modelling analysis (i.e.: Machine Learning).


<p align="center"><img src="https://www.era-environmental.com/hs-fs/hubfs/ETL-era-environmetal-management.png?width=566&name=ETL-era-environmetal-management.png"></p>



## **Project Description**
This is part of Ironhack Data Analytics Bootcamp. The main goal is to build a complete ETL given a database.

For this project we will perform some of these activities in order to analyse the [__diamonds_m2.db__](https://github.com/ivanrepi/data_visualization_project_m2/blob/master/db/diamonds_m2.db) `SQLite` database.


### :computer: **Dependencies**

- This repository is tested on **Python 3.7+**.

- Install [pandas](https://pandas.pydata.org/docs/user_guide/index.html) library. Copy and paste next command in your master branch to install it:
    ```
    conda install pandas
    ```
- Install [numpy](https://numpy.org/doc/stable/) library. Copy and paste next command in your master branch to install it:
    ```
    conda install numpy
    ```
- Install [SQLite](https://www.sqlite.org/index.html). Copy and paste next command in your master branch to install it:
    ```
    conda install -c anaconda sqlite
    ```
- Install [SQLAlchemy](https://www.sqlalchemy.org/library.html) library. Copy and paste next command in your master branch to install it:
    ```
    conda install -c anaconda sqlalchemy
    ```

> __IMPORTANT NOTE:__ BI Report have been made with __Tableau__. Account is not needed for visualization. If edit permissions are needed, contact with the administrator.


---

## :clipboard: **Overview:**

A GitHub repository including:


### **Challenge 1: Data Exploration and Preparation**

The goal of this challenge is to perform an __exploratory analysis__ in order to gain initial insight on our diamonds database and prepare the __data model__ that better fits your visualizations. 

The ETL process have been done with Python and Pandas, Numpy, SQLite and SQLAlchemy libraries.

All data exploration and preparation, can be found in the [__main.ipynb__](https://github.com/ivanrepi/data_visualization_project_m2/blob/master/db/main.ipynb) file.

<p align="center"><img src="https://www.datasciencecentral.com/wp-content/uploads/2021/10/2808308206.jpeg"></p>





### **Challenge 2: Diamanond Selection Dashboard**

BI Reports and Dashboards are powerful tools for communicating important information __at-a-glance__. The goal of this challenge is to build a BI Report/Dashboard using our diamonds database that will help the final user (i.e.: yourself) to perform better during _Module 3 project (Kaggle Competition)_. 

> __Tip:__ you should first consider which data and which indicators should be put on the BI Report/Dashboard. Then, decompose the key indicators from multiple dimensions. 

<p align="center"><img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif"></p>


A BI Report/Dashboard is not exactly a sequential set of descriptive charts like those you have may built in challenge 1 during the analysis. Instead, a BI Report/Dashboard should be __a single interactive interface built around a specific objetive and which components are logically arranged in order to provide data relevant insights effectively__. Therefore, bear in mind the main objective of the competition: _understand the relationship between diamonds attributes (features) or group of attributes, and its price_.



---


