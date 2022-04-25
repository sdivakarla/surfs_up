# Surf's Up

W.Avy, a client in Oahu, is planning to start a surf shop and needs to know the temperature range year-round.  Using SQL Alchemy, a weather dataset from Hawaii can be filtered to look at temperatures in June and December.  

# Overview

The weather stations in Oahu are collecting temperatures multiple times a day.  In order to understand the typical temperatures in different months, the readings were filtered for two selected months, June and December. Then the readings for those temperatures could be evaluated with standard summary statistics.  The statistics that were determined include: count, mean, median, mode, minimum, maximum and percentiles. For W. Avy to determine if the weather is amenable to a year-round surf shop he needs to know the temperature ranges. 

# Results 

1. June Temperature Data - There were 1700 readings collected in the month of June with an average temperature of 74.9 degrees Farenheit. The readings were collected between 2010 and 2017.  The summary statistics for June are shown below: 
<img width="216" alt="June_Summary_Statistics" src="https://user-images.githubusercontent.com/98054953/165132971-467a138d-4266-4b91-b4bb-068844453c45.png">
 
2. December Temperature Data - There were 1517 readings collected in the month of December with an average temperature of 71 degrees Farenheit. The readings were collected between 2010 and 2017.  The summary statistics for December are shown below: 
<img width="282" alt="Dec_Summary_Statistics" src="https://user-images.githubusercontent.com/98054953/165133269-06ef8c74-cad5-4222-a9be-feec3ceafc02.png">

3. Comparision of June and December Data
- The average monthly temperatures are similar (75 degrees vs 71 degrees)
- More samples were collected during June than December so there may be a more accurate picture of the temperatures in June. 
- The minimum in June (64 degrees) is higher than the minimum recorded in December (56 degrees).
- The maximum values are similar for June (85 degrees) and December (83 degrees). 

# Discussion 

Using the temperature data in two months, W. Avy has an idea of what to expect in terms of surfing conditions based on temperature. There are some additional analysis that coule be performed to better answer the question of whether a surf shop should be opened. 

 1. The frequency of temperature occurances would provide some input on the variation of the weather through out the month.  Histograms of weather readings in June and December are shown below.  The histograms show a higher occurance of lower temperature days in December.  W. Avy should be aware that there may be more days in December when it is too cold to surf. 
 <img width="610" alt="June_histogram" src="https://user-images.githubusercontent.com/98054953/165134427-fc6dd5d1-bf60-464a-b5c0-9f18073f6cb3.png"> <img width="594" alt="Dec_historgram" src="https://user-images.githubusercontent.com/98054953/165134430-b3bba0ea-f4f2-4d57-a04b-ac34fb189583.png">
 2. Another analysis could look at additional months.  June and December may provide the extremes in temperature, but the variability in the other months could help determine the feasibility of the surf shop. 
 3. If there is a temperature below which it is too cold to surf, an analysis could be run on how many a days a year are below that target temperture. 


