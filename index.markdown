---
title: Dope in the City - San Francisco's struggle with drugs
---
<div align="justify">
<p>Throughout the years San Francisco has been in a battle with drug related crimes. According to the <a href="https://drugabusestatistics.org/">National Institute on Drug Abuse</a>, drug overdose deaths have been increasing each year in the US since 1999 where the drug overdose has been the cause of over 700 000 reported deaths.</p>

<p>As late as the 2nd Feb 2024, New York Times states that “San Francisco is in the middle of a drug crisis” [reference]. As the influence of drugs in San Francisco is non-negotiable, this page will investigate how the social situation is reflected in the police reportings of the Police Department from 2003 to 2017.</p>

<p>The dataset is obtained from <a href="https://datasf.org/opendata/">DataSF</a> containing all crime occurrences in San Francisco over this period. The incidents on drugs and narcotics are extracted and analysed which include incidents related to illegal drugs or controlled substances and may include manufacturing, distribution, possession, and trafficking, amongst others. The dataset contains information about the type of crime, the date and time, the police district, the crime location and more. This information will be used to shed light on the social situation in San Francisco from another point of view.</p>
</div>



# San Fransisco in districts


<div align="justify">
<p>San Francisco has 10 districts spanning over 121 kilometers and is the home of 808,437 residents [<a href="reference">reference</a>]. It is common knowledge that districts within a city have different characteristics, especially in a city as big as San Francisco. Hence, the number of drugs/narcotic-related reportings from 2003 to 2017 is illustrated in the figure on the left below where the instance location is color-coded according to the district. The three districts with the highest drug-related repotings are highlighted on the right of the figure which are Tenderloin, Southern and Mission respectively.</p>

<img src="{{site.url}}/imgs/drug_crime_all.png" style="display: block; margin: auto;" />

<p><em>Figure 1. Plot 1 (left): The barplot displays the count of DRUG/NARCOTICS crime reports in San Francisco from 2003 to 2017; Plot 2-4 (right): The barplots display the count of DRUG/NARCOTICS crime reports in Tenderloin, Southern and Mission, respectively, from 2003 to 2017. Note that the range for Plot 1 spans from 0 to 12000 counts where the range for Plot 2-4 spans from 0 to 5000 counts.</em></p>

<p>Plot 1 illustrates a significant downward trend of drugs and narcotics incidents reported since 2003 after peaking in 2009, with a slight increase in 2013. The number of incidents reported in 2017 is the lowest in the period analyzed.</p>

<p>The comparison of the three districts with the most crime counts reveals that Tenderloin is the district with the highest number of drug and narcotics incidents reported in San Francisco, which is followed by Southern and Mission, respectively. What's particularly interesting is the sharp contrast between Tenderloin and the other neighborhoods. Throughout the analyzed period, Tenderloin generally reports more incidents than Southern and Mission combined.</p>
</div>


# What types of drug?

<div align="justify">
<p>The media currently represents the drug problem in Tenderloin as problematic, as mentioned earlier. This contrasts with the decreasing trend of the police reportings up until the year 2017. To get a deeper look into the behavior of the drug market through police reportings in Tenderloin, the most recurring drugs were extracted from the report descriptions. This includes categories such as "Narcotics paraphernalia" referring to drug related equipment and "Other" including all uncategorised instances. The development of the police reporting for each 6 months after the year 2003 is illustrated in the following interactive plot categorized by drug type.</p>

{% include drug_reportings_tenderloin.html %}

<p><em>Figure 2: Interactive line chart of the reporting counts for each drug category in the years after 2003 with 6 months interval. Note that the values are discrete but illustrated as continuous for the sake of clarity.</em></p>

<p>It is clear that cocaine has been the most dominant drug in circulation with a decreasing trend similar to the trend of the overall drug reportings. Narcotic paraphernalia and other drug related offences also follow the trend with a smaller magnitude and a smaller peak in 2009 compared to cocaine. The specific activities related to "Narcotics paraphernalia" and "Other" are unknown. This means that their trends could be directly correlated with other activities, e.g. cocaine related activities. Therefore, little information can be derived from these categories. The remaining categories show a more stable evolution around 150 counts per 6 months with a slight negative slope. It is clear that cocaine has a big influence on the drug related crime reportings in Tenderloin, San Francisco.</p>
</div>
 
# Map visualization 

<div align="justify">
<p>In 2018, Tenderloin got honored by hosting the dirtiest block in all San Francisco (<a href="https://www.nytimes.com/2018/10/08/us/san-francisco-dirtiest-street-london-breed.html">The New York Times</a>), the 300 block of Hyde Street. This block is located in the heart of the Tenderloin neighborhood and is known to be the chosen location for homeless people and drug addicts, thus all the heroin needles and human feces that are constantly seen there.</p>

<p>The map below shows what could be expected according to the information in the section above. The Tenderloin neighborhood, which has the smallest area of all San Francisco districts, has several hotspots for drug and narcotics incidents spread around its area.</p>

<p>The big focus made by the media about the 300 block of Hyde Street and its home to in the open drug activity could create the impression that this is a place where most of the drug and narcotics incidents are reported. However, the map below shows that this is not the case. As it happens, the whole area is covered with red dots, indicating no corner is free from this type of illicit activity.</p>
</div>

<embed type="text/html" src="imgs/heatmap_tenderloin_map.html" width="110%" height="950"/>
<p><em>Interactive heatmap showing the variation of DRUG/NARCOTICS crime reports in the Tenderloin neighborhood from 2003 to 2017</em></p>


# Outside factors

<div align="justify">
<p>It has not been possible to uncover the reasoning behind the drug-related reporting trends through the data solely. To understand the evolution, one must be critical towards the data source and look for external information to support or disprove theories. The data used shows only the reported incidents and does not reflect the actual activity of drug consumption in San Francisco. Despite the decreasing drug-related reportings, it cannot be denied that the “drug crisis” has continued throughout the years.</p>

<p>In 2014, the referendum Proposition 47 was passed in the state of California. This measure converted non-violent offenses, including drug-related offenses, from felonies to misdemeanors. The purpose of the measure was to keep offenders out of prison and invest in programs designed to help people who committed these misdemeanors. [<a href="https://your-reference-url.com">Reference</a>] This proposition could be the cause of the decrease in drug-related reportings, maybe even in the years the referendum was passed. It would be expected that the referendum only decreased the severity of the penalties rather than the number of instances. However, with this data, it is difficult to say whether the referendum had a big social impact on the conduct and mentality of police officers, leading them to overlook situations involving drugs and focus their resources on other types of crime.</p>
</div>