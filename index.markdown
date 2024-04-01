---
title: Assignment 2
---

Please find below the different assignments made for Social Data Analysis and Visualization.


# Introduction

Drug and narcotics incidents are related to illegal drugs or controlled substances and may include manufacturing, distribution, possession, and trafficking, amongst others. According to the [National Institute on Drug Abuse](https://drugabusestatistics.org/), drug overdose deaths have been increasing each year in the US since 1999. As a matter of fact, over 700,000 drug overdose deaths have been reported. These numbers clearly highlight the importance of understanding the trends in drug and narcotics incidents in order to develop strategies to prevent and reduce them.

In this page, we will conduct an analysis of the variation in drug and narcotics incident reports in San Francisco across the majority of the first two decades of the 21st century. For this analysis we are using a dataset obtained from [DataSF](https://datasf.org/opendata/), which contains all crimes occurences reported to San Francisco Police Department from 2003 until the first few months of 2018 (for simplicity we will focus on the period from 2003 to 2017, as the data for 2018 is incomplete). The dataset contains information about the type of crime, the date and time it occurred, the police district where it occurred, and the latitude and longitude of the location where it occurred. We will use this information to shed light to any notable temporal trends and identify hotspots of drug activity.



# Exploring the data

Plot 1, visible below, illistrates a significant downward trend in the number of drugs and narcotics incidents reported since 2003, with a slight increase in 2015. The number of incidents reported in 2017 is the lowest in the period analyzed. 

Moreover, in the same plot, it is possible to see that Tenderloin is the neighborhood with the highest number of drug and narcotics incidents reported in San Francisco, which is followed by Southern and Mission, respectively. What's particularly interesting is the sharp contrast between Tenderloin and the other neighborhoods. Throughout the analyzed period, Tenderloin consistently reports more incidents than Southern and Mission combined.

This highlights a pressing issue within the Tenderloin neighborhood that needs attetion and planned intervention.


Make it a bit better "in the heart of San francisco, the Tenderloin neighborhood is the epicenter of drug and narcotics incidents in the city. Throughout the analyzed period, Tenderloin consistently reports more incidents than Southern and Mission combined. This highlights a pressing issue within the Tenderloin neighborhood that needs attention and planned intervention.""

<img src="{{site.url}}/imgs/barplot_drugs_districts.png" style="display: block; margin: auto;" />

*Plot 1: The barplot displays the count of DRUG/NARCOTICS crime reports in San Francisco from 2003 to 2017; Plot 2-4: The barplots display the count of DRUG/NARCOTICS crime reports in Tenderloin, Southern and Mission, respectively, from 2003 to 2017*


# Map visualization 

In 2018, Tenderloin got honoured by hosting the distiest block in all San Francisco ([The New York Times](https://www.nytimes.com/2018/10/08/us/san-francisco-dirtiest-street-london-breed.html)), the 300 block of Hyde Street. This block is located in the heart of the Tenderloin neighborhood and is known to be the chosen location for homeless people and drug addicts, thus all the heroine needles and human feces that are constantly seen there.

The map below shows what could be expected according to the information in the section above. The Tenderloin neighbourhood, which has the smallest area of all San Francisco districts, has several hotspots for drug and narcotics incidets spread around its area. 

The big focus made by the media about the 300 block of Hyde Street and its home to in the open drug activity, could create the impression that this is a place where most of the drug and narcotics incidents are reported. However, the map below shows that this is not the case. As it happens, the whole area is covered with red dots, indicating no corner is free from this type of illicit activity.


<embed type="text/html" src="imgs/map_drugs_tenderloin_focus.html" width="110%" height="950"/>
*Interative heatmap showing the variation of DRUG/NARCOTICS crime reports in the Tenderloin neighbourhood from 2003 to 2017*


# Last plot
<embed type="text/html" src="imgs/map_reportings_tenderloin.html" width="110%" height="950"/>

