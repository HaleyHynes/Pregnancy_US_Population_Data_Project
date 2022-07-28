# Pregnancy US Population Data Project

By Haley Hynes

This project uses Python version 3.10.5

In this project I analyze pregnancy data from 2017 in the United States to determine how many women were pregnant in each state and region and how that compares to the population data for women in each state and region.


## Requirement #1: Reading Data In

To meet this requirement I read in total_pregnancies.csv and women_population.csv using pandas to create dataframes.


## Requirement #2: Cleaning and Manipulating Data

To meet this requirement I:
* Change column names
* Delete columns
* Create two dataframes from one in order to isolate variables
* Reset the index of one dataframe
* Add the column of one dataframe to another dataframe
* Sort a dataframe by the alphabetical order of a column
* Change the index from numerical to state abbreviations
* Move columns around


## Requirement #3: Analyzing Data

First I separate my data in to regions of the US based on US Census data: West, Midwest, Northeast, and South. Next, I create a function to apply the sum method to each column in the dataframes. Then, I create a percentage function and apply it to each dataframe.


## Requirement #4: Visualize Data

I create a dataframe from the last row in each dataframe so I have the sum data for each region and my new percentage columns. I then create two graphs using matplotlib: one comparing the total pregnancies and births in numbers and the other comparing total pregnancies and births in percentage.


## Requirement #5: Interpret the Data

Throughout the project I used markdown cells to explain my python cells.