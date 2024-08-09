# Airbnb Listings Analysis Using Python
**By Samuel Oyedele**

## Introduction
### Dataset Description
> Airbnb data for 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews.

## Objective
> Analyze Airbnb listings in Paris to determine the impact of recent regulations.

## Questions
1. Can you spot any major differences in the Airbnb market between cities?
2. Which attributes have the biggest influence in price?
3. Are you able to identify any trends or seasonality in the listings data?

**Tools Used:** Pandas (data manipulation), Matplotlib / Seaborn (data visualization)

## Data Wrangling
> In this section, the dataset are gathered, assessed for quality and tidiness issues and cleaned for further analysis and visualizations.

### Data Gathering
> The dataset (Listings) in CSV file is loaded into a dataframe using pandas `read_csv`.

### Assessing Data
>  In this section, the loaded data is assessed for any quality and tidiness issues.

#### Quality Issues
> They are issues with the data content like missing data, Inaccurate data, Inconsistent data etc. It is also known as dirty data.
- Missing values in some columns
- Data type issue: incorrect data type for host_since and bedrooms columns.

#### Data Cleaning
> The dataset quality issues will be cleaned for analysis and visualizations. The data cleaning is done following the steps: Define, Code and Test.

## Exploratory Data Analysis
> The cleaned dataset will be analyzed and visualize to identify the trends and patterns in Airbnb listings by cities with major focus on Paris.

### Key Metrics
- Average Listing Price by City
- Average Price Listings by Neighborhood
- Average Price Listings by Accommodation
- Airbnb Hosts and Price Over Time in Paris

## Summary of Findings
- The average price listings for each city varies different based on their currency rate.
- **Mexico City** has the highest review scores rating of 94.84 ~ followed closely by **Rio de Janeiro** and **Cape Town**. **Hong Kong** has the lowest review scores rating of 89.7.
- **Elysee** neighbourhood is the most expensive neighbourhood in Paris while **Menilmontant** is the cheapest neighbourhood in Paris.
- The higher the accommodates, the higher the listing price. The most expensive listings have accommodations of 14 people for €971. The highest accommodations '16' has only one listing compare to two listings for '14' accommodations.
- The higher the bedrooms, the higher the listing price. The most expensive listings have 6 bedrooms for €602.
- **Hotel room** space is the most expensive listings room type with average price of €378 followed by **Entire place** space.
- Since the launched of **Airbnb** in 2008, the no of new hosts in Paris increase rapidly from 4 hosts in 2008 to **12147** hosts in **2015**. Since the government regulations in 2015, the no of new hosts decreases drastically yearly.
- The average Airbnb price peak in 2009 then begin to decline due to rise of new hosts which create competition for customers. After the 2015 regulations in prices, the average price rise again to a high point in 2020 before the pandemic due to decline of new hosts which later declined during the middle of the Covid lockdown in 2021.
- 2015 regulations lead to fewer number of new hosts with higher prices.

## Conclusions
From the analysis, I was able to identify the trends and patterns in Airbnb listings in Paris city. Uncovered insights on the Airbnb market in Paris and factors with the biggest influence in price.

The 2015 regulations had a great impact in Airbnb listings in Paris which lead to fewer number of new hosts, higher prices from 2015 till 2021.

**Skill Highlighted:** Data wrangling (data cleaning), data analysis, data visualization.
