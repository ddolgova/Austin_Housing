# ATXHomes Austin Real Estate Insights

## Interactive Power BI dashboard can be downloaded [here](https://www.microsoft.com).

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Modeling](#data-modeling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Insights](#results-and-insights)

### Project Overview

This report provides an understanding of the Austin, Texas real estate market based on home price, features, living area size, lot size, location, and schools nearby. By organizing this data in an interactive dashboard, we seek to provide homebuyers a straightforward tool to select a home based on their preferences.

<img width="1255" alt="Austin Housing Summary" src="https://github.com/user-attachments/assets/3871d7d6-2be1-4f3d-8a20-55c841a7b3b1">

<img width="1256" alt="Austin Housing Features" src="https://github.com/user-attachments/assets/1e18e487-49c7-4878-8400-3372099c7d89">


### Data Sources

Real estate data: The main dataset used for this report is the “austinHousingData.xlsx” file, which holds information about listings in the Austin housing market.

### Tools

- Excel: Data cleaning 
- Power Query Editor: Data cleaning, data modeling
- Power BI: Data analysis, data modeling, report building


### Data Cleaning and Preparation

In the first phase of data preparation, I went through the following procedure:

1. Loading the data and performing the initial assessment
2. Finding and treating missing and null values
3. Data formatting
4. Cleaning unnecessary special characters

### Data Modeling

In the next phase of data preparation, I did the following:

1. Inspecting the source data to determine the best modeling approach
2. Referencing a clean copy of the source data to create the fact and dimension tables
3. Determining the cardinality and relationships between the fact and dimension tables
4. Creating some initial DAX measures

### Exploratory Data Analysis
EDA included investigating the housing data to answer the following questions:

What is the difference in median and average home price based on home type?
Which areas had the highest rated schools?
Does median home price change based on different features?
Does the year the home was constructed affect home price?
Which words do listing agents most use to describe properties at different price points?

### Results and Insights

The visualizations resulting from this analysis work well to assist homebuyers in finding a suitable property for purchase based on their selection criteria.
This report also can be utilized by real estate companies, agents, and brokers, to get an overview of the housing market.
Here are some of the insights that appear from the visualizations.
Out of the 15,171 properties, the vast majority - 14,241 - are single family homes.
Multi-family homes had the greatest difference between median and average home price.
The median home price in the Austin, Texas area is $405,000 and the average home price is $512,768.
Properties that are in areas with higher school ratings are on the western side of the Austin, Texas region.
Some of the key influencers in home price increase include having more than 2 stories, more than 4 bedrooms, more than 2 parking/garage spaces, is built before 1957 or after 2017, and lot size/living area increases.






