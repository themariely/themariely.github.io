---
title: San Francisco's struggle with drugs and narcotics


Throughout the years San Fransisco has been in a battle with drugs and crime. According to the [National Institute on Drug Abuse](https://drugabusestatistics.org/), drug overdose deaths have been increasing each year in the US since 1999, where over 700,000 drug overdose deaths have been reported. As late as the 2. Feb 2024 New York Times states that “San Fransisco is in the middle of a drug crisis” [reference]. As the influence of drugs in San Fransico is non-negociable, this page will inevstigate how the social situation is reflected in the police reporting of the Police Department from 2003 to 2017. 

The dataset is obtained from  [DataSF](https://datasf.org/opendata/) containing all crime occurrences in San Fransisco over this period. The incidents on drugs and narcotics are extraced and analysed which include incidents related to illegal drugs or controlled substances and may include manufacturing, distribution, possession, and trafficking, amongst others. The dataset contains information about the type of crime, the date and time it occurred, the police district where it occurred, and the latitude and longitude of the location where it occurred and mode. This information will be used to to shed light on the social situation in San Fransisco from an other point of view

# San Fransisco in districts


San Fransisco has 10 districts spanning over 121 kilometers and is the home of 808 437 residents [reference]. It is common knowledge that districts within a city have different characteristics, especially in a city as big as San Fransisco. Hence the number of drugs/narcotic-related reportings from 2003 to 2017 is illustrated in the figure on the left below where the instance location is color-coded according to the district. The three districts with the highest drug-related repotings are highlighted on the right of the figure which are Tenderloin, Southern and Mission respectively. The number of incidents reported has been decreasing since 2003 peaking in 2014. The number of incidents reported in 2017 is the lowest in the period analyzed.

{% include drug_crime_all.png %}

*Plot 1: The barplot displays the count of DRUG/NARCOTICS crime reports in San Francisco from 2003 to 2017; Plot 2-4: The barplots display the count of DRUG/NARCOTICS crime reports in Tenderloin, Southern and Mission, respectively, from 2003 to 2017*

 Plot 1, visible below, illistrates a significant downward trend in the number of drugs and narcotics incidents reported since 2003, with a slight increase in 2015. The number of incidents reported in 2017 is the lowest in the period analyzed.
We can see from the picture displayed that Tenderloin is the neighborhood with the highest number of drug and narcotics incidents reported in San Francisco with around twice as meny reports as the next worst district. Although the number of incidents in Tenderloin is significantly higher than in the other neighborhoods, the trend in the number of incidents is similar across all neighborhoods.
Moreover, in the same plot, it is possible to see that Tenderloin is the neighborhood with the highest number of drug and narcotics incidents reported in San Francisco, which is followed by Southern and Mission, respectively. What's particularly interesting is the sharp contrast between Tenderloin and the other neighborhoods. Throughout the analyzed period, Tenderloin consistently reports more incidents than Southern and Mission combined.
 
This highlights a pressing issue within the Tenderloin neighborhood that needs attetion and planned intervention.
 
 
Make it a bit better "in the heart of San francisco, the Tenderloin neighborhood is the epicenter of drug and narcotics incidents in the city. Throughout the analyzed period, Tenderloin consistently reports more incidents than Southern and Mission combined. This highlights a pressing issue within the Tenderloin neighborhood that needs attention and planned intervention.""

# What types of drug?

The trend of the police reportings contrasts the perceived presence of an increasing drug problem in the media. The reporting instances are therefore categorized by drug type to see if the trend is caused by a specific drug. The most recurring instance descriptions were investigated to make a list of the most popular drugs including the categories "narctosics paraphernalia" referring to drug related equipment and "Other". Each instance was sorted into a category according the the drug name contained in the description. The evolution of the police reporting for each 6 months after the year 2003  is illustrated in the following interactive plot categorized by drug type. 

{% include drug_reportings_tenderloin.html %}

It is clear that Cocaine has been the most dominant drug in circulation with a trend similar to the trend of the overall drug reportings.  Narcotic paraphernalia and other drug related offences also follow the trend with a smaller magnitude and a smaller peak in 2010 compared to cocain. As the specification of the narcotic paraphernalia and the other offences are unknown it one can not reject the possibility that these categories are a consequence of the cocain related consumption. The other categories show a more stable evolution with a slight negative slope. 
 
# Map visualization 

In 2018, Tenderloin got honoured by hosting the distiest block in all San Francisco ([The New York Times](https://www.nytimes.com/2018/10/08/us/san-francisco-dirtiest-street-london-breed.html)), the 300 block of Hyde Street. This block is located in the heart of the Tenderloin neighborhood and is known to be the chosen location for homeless people and drug addicts, thus all the heroine needles and human feces that are constantly seen there.

The map below shows what could be expected according to the information in the section above. The Tenderloin neighbourhood, which has the smallest area of all San Francisco districts, has several hotspots for drug and narcotics incidets spread around its area. 

The big focus made by the media about the 300 block of Hyde Street and its home to in the open drug activity, could create the impression that this is a place where most of the drug and narcotics incidents are reported. However, the map below shows that this is not the case. As it happens, the whole area is covered with red dots, indicating no corner is free from this type of illicit activity.


<embed type="text/html" src="imgs/map_drugs_tenderloin_focus.html" width="110%" height="950"/>
*Interative heatmap showing the variation of DRUG/NARCOTICS crime reports in the Tenderloin neighbourhood from 2003 to 2017*

# Outside factors

It has not been possible to uncover the reasoning behind the drug related reporting trends through the data solely. To understand the evolution one must be critical towards the datasource and look for external information to support or disprove theories. The data used shows only the reported incidens and does not reflect the actual activity of drug consumption in San Fransisco. Despite the decresing drug related reportings, it can not be denied that the “drug crisis” has continues through out the years.

In 2014, the referendum Proposition 47 was passed in the state of california. This measure converted non violent offenses, including drug related offences, from felonies to misdemeanors. The purpose of the measure was to keep offenders out of prison and invest in programs designed to help people in who commited these misdemeanors. [reference] This propositon could be the cause of the decrease in drug related reportings, maybe even in the years the referendum was passed. It would be expected that the referendum only decreased the severness of the penalties rather than the number of instances. However, with this data, it is difficult to say whether the referendum had a big social impact on the conduct and mentality of police officeres leading them to overlook situations involving drugs and focusing there resources on other types of crime.