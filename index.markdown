---
title: Assignment 2
---

Please find below the different assignments made for Social Data Analysis and Visualization.


# Introduction

In this page, we will conduct an analysis of the variation in drug and narcotics incident reports in San Francisco across the majority of the first two decades of the 21st century. For this analysis we are using a dataset obtained from [DataSF](https://datasf.org/opendata/), which contains all crimes occurences reported to San Francisco Police Department from 2003 until the first few months of 2018 (for simplicity we will focus on the period from 2003 to 2017, as the data for 2018 is incomplete). The dataset contains information about the type of crime, the date and time it occurred, the police district where it occurred, and the latitude and longitude of the location where it occurred. We will use this information to shed light to any notable temporal trends and identify hotspots of drug activity.

Drug and narcotics incidents are related to illegal drugs or controlled substances and may include manufacturing, distribution, possession, and trafficking, amongst others. According to the [National Institute on Drug Abuse](https://drugabusestatistics.org/), drug overdose deaths have been increasing each year in the US since 1999. As a matter of fact, over 700,000 drug overdose deaths have been reported. These numbers clearly highlight the importance of understanding the trends in drug and narcotics incidents in order to develop strategies to prevent and reduce them.

# Exploring the data

The graph 1 displays the number of drug and narcotics incidents reported in San Francisco from 2003 to 2017. Graphs 2, 3 and 4 show the number of the same type of incidents reported in the worst neighbourhoods for this category. The number of incidents reported has been decreasing since 2003, with a slight increase in 2015. The number of incidents reported in 2018 is the lowest in the period analyzed.

We can see from the picture displayed that Tenderloin is the neighborhood with the highest number of drug and narcotics incidents reported in San Francisco. This is followed by South of Market and Mission. Although the number of incidents in Tenderloin is significantly higher than in the other neighborhoods, the trend in the number of incidents is similar across all neighborhoods. The number of incidents reported in Tenderloin is decreasing, while the number of incidents in South of Market and Mission is increasing.

<img src="{{site.url}}/imgs/barplot_drugs_districts.png" style="display: block; margin: auto;" />
![Caption for Graph 1]({{site.url}}/imgs/barplot_drugs_districts.png)

# Map visualization 1

Upon looking at such results, one may wonder "but perhaps Tenderloin is larger district than the others". Thus, in order to evaluate how bad the situation is in each district, we have created a map that shows the number of drug and narcotics incidents reported per square kilometer in each district. The map shows that the situation is indeed worse in Tenderloin, with over 90,000 incidents per square kilometer from 2003 to 2017. This is followed by Mission and Nothern, with 2602 and 1726 incidents per square kilometer, respectively.

<embed type="text/html" src="imgs/map_drugs_per_district_area.html" width="110%" height="950"/>


# Map visualization 2

https://www.nbcbayarea.com/news/local/walking-san-franciscos-dirtiest-block-with-snapcrap-app-creator/204130/ reports that in Tenderloin is located the wors