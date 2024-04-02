---
title: "Dope in the City: San Francisco's Ongoing Battle with Drugs"
---
<div align="justify">  
<p> San Francisco has had a long battle with drugs. According to the <a href="https://drugabusestatistics.org/">National Institute on Drug Abuse</a>, drug overdose deaths have been increasing each year in the US since 1999, where the drug overdose has been the cause of over 700,000 reported deaths.</p>

<p> As late as the 2nd Feb 2024, <a href="https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html#:~:text=San%20Francisco%20is%20in%20the,Francisco%20get%20to%20this%20point%3F">New York Times</a>  says that “San Francisco is in the middle of a drug crisis”. <a href="https://www.theguardian.com/us-news/2023/apr/27/overdose-deaths-in-san-francisco-hit-200-in-three-months-a-crying-shame">The San Fransisco Chronicle</a> states that on Dec. 17, 2021, San Francisco Mayor London Breed declared an official state of emergency in the Tenderloin district to address the escalating epidemic. The <a href="https://abc7news.com/san-francisco-record-overdose-deaths-fentanyl-wastewater-drug-testing/14186379/">ABC 7 News</a> declares 2023 as San Fransisco's deadliest year ever for drug overdoses. </p>

<p>The effect of drugs on the city is undeniable. This page will investigate the social situation through the police reportings of the Police Department from 2003 to 2017.</p>

<p>The dataset is obtained from <a href="https://datasf.org/opendata/">DataSF</a> containing all crime occurrences in San Francisco from 2003 to the beginning of 2018. The incidents on drugs and narcotics are selected and analyzed which include incidents related to illegal drugs or controlled substances and may include manufacturing, distribution, possession, and trafficking, amongst others. The dataset contains information about the type of crime, the date and time, the police district, the crime location, and more. The analysis was limited to whole years for clarity, hence the instances in the year 2018 were excluded from the data. This data will be used to shed light on the social situation in San Francisco.</p>
</div>

# San Francisco's "bad" districts


<div align="justify">
<p>San Francisco has 10 districts spanning over 121 kilometers and is the home of 808,437 residents [reference]. It is common knowledge that districts within a city have different characteristics, especially in a city as big as San Francisco. Hence, the number of drugs/narcotic-related reportings from 2003 to 2017 is illustrated in the figure below. Plot 1 in the right panel illustrates the drug-related crime count per year, color-coded according to district. The three districts with the highest total crime count are illustrated in Plots 2, 3, and 4. These districts are Tenderloin, Southern, and Mission respectively.</p>

<img src="{{site.url}}/imgs/drug_crime_all.png" style="display: block; margin: auto;" />

<p><em>Figure 1. Plot 1 (left): The barplot displays the count of DRUG/NARCOTICS crime reports in San Francisco from 2003 to 2017; Plot 2-4 (right): The barplots display the count of DRUG/NARCOTICS crime reports in Tenderloin, Southern, and Mission, respectively, from 2003 to 2017. Note that the range for Plot 1 spans from 0 to 12000 counts whereas the range for Plot 2-4 spans from 0 to 5000 counts.</em></p>

<p>Plot 1 illustrates a significant downward trend of drug and narcotics incidents reported since 2003 after peaking in 2009, with a slight increase in 2013. The number of incidents reported in 2017 is the lowest in the period analyzed. </p>

<p>Plot 2, 3 and 4 show that Tenderloin is the district with the highest number of drug and narcotics incidents reported in San Francisco, which is followed by Southern and Mission, respectively. Note the contrast between Tenderloin and the other neighborhoods. Throughout the analyzed period, Tenderloin generally reports more incidents than Southern and Mission combined.</p>

<p>The data clearly shows that the trend for drug-related crimes from 2003 to 2017 decrease, even for the district with the highest total crime count. This contrasts with the current media representation of the drug situation in San Fransisco.</p>

</div>


# San Francisco's favorite drugs

<div align="justify">
<p>To get a deeper look into Tenderloin's drug situation. the most recurring drugs were extracted from the police report descriptions. This includes the categories "Narcotics paraphernalia" referring to drug-related equipment and "Other" including all uncategorized instances. The development of the police reportings after the year 2003 is illustrated in the following interactive plot categorized by drug type. Note that the timeline is discretized with an interval of 6 months.</p>

{% include drug_reportings_tenderloin.html %}

<p><em>Figure 2: Interactive line chart of the reporting counts for each drug category in the years after 2003 with 6 months interval. Note that the values are discrete but illustrated as continuous for the sake of clarity.</em></p>

<p>The data shows that cocaine has been the most dominant drug in circulation with a decreasing trend similar to the trend of the overall drug reportings. Narcotic paraphernalia and other drug-related offenses also follow the trend with a smaller magnitude and a smaller peak in 2009 compared to cocaine. "Narcotics paraphernalia" and "Other" have their own categories but these crimes may be a consequence of other drug-related crimes. The trends of these categories could be directly correlated, e.g. the use of cocaine. Therefore, little information can be derived from these categories. The remaining categories show a more stable evolution of around 150 counts per 6 months with a slight negative slope. Altogether, the figures show that cocaine has a big influence on the drug-related crime reportings in Tenderloin, San Francisco.</p>
</div>
 
# Where to find the dirtiest block?

<div align="justify">
<p>In 2018, Tenderloin got honored by hosting the dirtiest block in all San Francisco (<a href="https://www.nytimes.com/2018/10/08/us/san-francisco-dirtiest-street-london-breed.html">The New York Times</a>), the 300 block of Hyde Street. This block, located in the heart of the Tenderloin neighborhood, is known to be the a gathering spot for homeless population and drug users for years. Consequently, it has become a unclean and smelly area with multiple heroin needles and human feces out in the open.</p>

<p> Could the presence of such troubled subjects and the out in the open drug activity in this block contribute to more reports of drug-related incidents? In order to analysise this, we've analyzed the intensity of drug and narcotics crimes across different areas within Tenderloin, as seen in Figure 3. </p>
<embed type="text/html" src="imgs/heatmap_tenderloin_map.html" width="110%" height="950"/>
<p><em> Figure 3: heatmap which illustrates the intensity of DRUG/NARCOTICS crime reports across the Tenderloin neighborhood from 2003 to 2017. Note that the colours seen describe the frequency of incidents: from cool blues indicating lower activity to fiery reds signaling higher occurrences. Keep an eye out for the "dirtiest" block identified by a marker. </em></p>

<p>The big focus made by the media about the 300 block of Hyde Street and its home to in the open drug activity could create the impression that this is a place where most of the drug and narcotics incidents are reported. However, the map below shows that this is not the case. As it happens, the whole area is covered with red dots, indicating no corner is free from this type of illicit activity.</p>
</div>

# So... What is actually happening?


<div align="justify">
<p>The data clearly shows trends that contradict the current media representation, when it comes to the continuing drug problem and the representation of the worst blocks. The drug situation seems to get better and the distribution of drug-related crimes seems to be uniformly distributed over Tenderloin.</p>

<p>The media sources stating that San Fransisco struggle with drugs dates from the early 2020s. The situation may have worsened in the years after 2017 as the information for those years is not available. A crisis such as COVID-19 could cause isolated people to find satisfaction in drugs. Or it could be a change in social behavior that has led police officers to respond less to drug related situations rather than an actual decrease in drug-related activities. It is not possible to uncover the reasoning behind the trends of drug-related reportings solely through the data. To understand the trends, one must be critical of the data source and look for external information to support or disprove theories. The data used shows only the reported incidents of drug-related crimes and does not reflect the actual activity of drug consumption in San Francisco. </p>
</div>