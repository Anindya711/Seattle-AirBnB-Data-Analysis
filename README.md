# Seattle-AirBnB-Data-Analysis
This repository consists of analysis of Seattle AirBnB data using python.

**Motivation** \
Airbnb offers air beds and shared spaces to a variety of properties including entire homes and apartments, private rooms, castles, boats, manors for people to lease or rent for short-term lodging. The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking. So, if you want to go somewhere unplanned, not able to afford luxurious hotels, knock Airbnb's door.
In this post, we are going to analyze the Seattle Airbnb data, provided to us publicly for data mining works.

**Data**\
The data could be found at https://www.kaggle.com/airbnb/seattle.
The data consists of 3 .csv files. The listings dataset, the calendars dataset, and the reviews dataset. Listings, including full descriptions and average review score. Reviews, including a unique id for each reviewer and detailed comments. Calendar, including listing id and the price and availability for that day. In this analysis, only listings and calendar are used. 
The listing dataset has information about 92 attributes like listing_id, host, neighborhood, price, monthly_price, number_of_reviews, etc. on 3,818 homes. The home availability data for Seattle was provided from January 2016 to January 2017. In order to have consistency, only 2016 data were considered for this analysis.

**Approach**\
The CRISP-DM Process (Cross Industry Process for Data Mining) is a standard process while dealing with data science problems across the industry. In this project, we will try to answer some fundamental questions about Seattle AirBnB data, while keeping in mind below standards in the CRISP-DM process.

  1.Business Understanding
  2.Data Understanding
  3.Prepare Data
  4.Data Modeling
  5.Evaluate the Results
  6.Deploy
  
**Goal**\
In this analysis, we are going answer questions related to 3 areas, those are

  **Availability Analysis**
    An Airbnb host can set up a calendar for their listing so that it is only available for a few days or weeks a year.
    listings are available all year round (except for when it is already booked).
    We will try to analyze below points here in regards to Availability.
    
    1.What percent of listings are highly available throughout the year? We will consider a metric of 60% as the measure of high
    a availability.
    
    2.How the listings are distributed across a number of days? Are there a huge number of available listings? What could be the
    the reason behind that?
    
  **Time Series and Engagement Analysis**
  
    1.What are the busiest times of the year to visit Seattle? 
    
    2.Which day is the busiest of all the days?
    
    3.Which months show most visitors in the area?
    
  **Pricing Analysis**
  
    1.How much do people charge to rent their homes (on average, minimum, maximum)? 
    
    2.How the price changes in those busy schedules?
  
**Files**\
  This repository contains 2 files apart from this readme file. The Seattle Data Analysis.ipynb contains the all the code and analysis
  and the Seattle Data Analysis.html is the html export of the same file.
    
**Summary**\
  The final analysis results has been published via a medium post. Please find the link to the post below,
  https://medium.com/@anindya.prince/airbnb-deep-analysis-of-seattle-homes-4e0cbd655cc7?postPublishedType=initial

Inspired by : http://insideairbnb.com/behind.html
