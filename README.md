## Background

In order to determine which teams will make it to the NBA playoffs each season,or which players will perform at the elite level for the majority of their teams playoffs run.These are the questions this project seeks to answer by creating a data pipeline that gathers relevant data from the source and displays this data on a dashboard as the final destination.

## Data Wrangling

* The relevant data about the nba teams and the players will be scraped from https://www.basketball-reference.com/

### Goal

* write a python script that scrapes the relevant data 

## DATA TRANSFORMING

### Goal

* write a function that cleans and transforms the data into a csv file for further analysis

### Activities
* Transform data gathered from JSON format to python CSV

* extend the script such that it loads and transforms only a given amount of data at a time.

## DATA LOADING

### Goal

* Write another script that loads the transformed csv data into an sql table at scheduled intervals and deletes the previous csv script to save on memory.

### Activities

* Load the CSV data into MySQL database for staging
* Transform the data in relational database to gather relevant insights and connect it to the dashboard.

### Personal learning goals

* learn how to web scrape data from the internet
* become proficient in data wrangling phases
* learn how to clean and perform initial analysis on data
* learn how to load data in a scheduled way
