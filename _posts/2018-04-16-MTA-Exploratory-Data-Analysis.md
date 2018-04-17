---
layout: post
title: MTA Exploratory Data Analysis
---

# MTA Exploratory Data Analysis

The first week at [Metis](http://www.thisismetis.com/data-science-bootcamps) just wrapped up and our Project Benson is completed!

### Problem

Project Benson provided the task of completing an exploratory data analysis for WomenTechWomenYes (WTWY), a mock client holding a summer fundraising and outreach gala in New York City. WTWY wanted to leverage the MTA’s subway data in order to best place their street teams throughout the city to target potential gala guests for email sign ups and access to free gala tickets.  

### Data

![turnstile](/../images/turnstile.jpg)

The MTA subway data is provided freely and openly on the MTAs website. After scraping the data for an interval of 6 weeks, we were excited to get started on performing our analysis using the [pandas](https://pandas.pydata.org) package and getting some plots of high frequency stations going. Our initial plans, however, were soon put on hold as we learned there was much time to be spent on understanding and cleaning the data set. Once the cleaning was completed, we could finally move on to the analysis!

### Initial Analysis

From here we found the stations with the greatest activity, defined as entrances plus exits, as well as confirmations of our hypotheses that weekdays are busier than weekends and the PM hours are busier than the AM hours.

### Ancillary Data Sets

![women](/../images/women.jpg)

Next came my focus for the project: bringing in outside data sets to help inform our analysis of the MTA data. We wanted to use this additional data to best target the desired demographic of WTWY. Utilizing the [NYC Open Data portal](https://opendata.cityofnewyork.us), I found a data set from the NYC Minority and Women owned Business Enterprise program, which tracks minority and women owned businesses in the New York City area. From this data set we were able to grab the locations of women-owned business and, with the help geo-location service [Geocodio](https://geocod.io), find the areas of Manhattan with a high-density of women owned businesses, where workers may be partial to WTWY’s causes. We also incorporated income data from the American Community Survey 2016 5-year estimates to target zip codes in Manhattan where potential donors and sponsors may live.

### Results

Using the outside data sets to pare down our list of high traffic stations, we selected 4 stations for further investigation and created heat maps showing activity at those stations for each day of the week.

See below for my group's presentation!

https://docs.google.com/presentation/d/1YqWURLT4SYuVXCmxReLBPPbprOBG-669PCY3UDN93CA/edit?usp=sharing

Week one was a whirlwind, and excited to keep the learning going in week two.
