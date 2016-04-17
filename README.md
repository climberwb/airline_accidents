 <h1>Airline Accidents</h1>

<h2>Abstract:</h2>
<p>To analyze data that contain all airline accidents within the united states.
The aim of this analysis is to identify the most dangerous times and places to travel</p> 

<h2>Method:</h2>
<p>The data is located in AvationData.txt. The analysis of the data is located
in AviationAccidents.ipynb. The original text file has information on the type of plane, location, type/severity of accident, time of accident, etc...
</p>
<p>This analysis focuses on location, frequency, time and severity of the accidents.
With the aid of pandas and numpy the data was converted from a text file into dataframe. Making use of matplot and basemap, the dataframe was then
used to create a color coded map and a bar graph. 
The color coded map of the united states highlights the frequency of the accidents. The darker states have 
more accidents than the lighter colored states. The dataframe used for the bargraph was filterd to only
contain deadly accidents and serious injuries. The bar graph counts this filtered data per month.
</p>
 
 <h2>Discussion:</h2>
 <h3>Color Coded Map</h3>
 <p> The color coded map ranges from white to orange, displaying the full spectrum 
     of incident frequency. By far the 3 most aviation accidents occur in California Texas and Florida, with counts in the high 50's and 60's. 
     The leased aviation accidents seem to
 occur in the northeastern tip of the country with states like Vermont and Maine. West Virginia and Nebraska also 
 have very little color indicating few aviation accidents. 
 This could correlate to the sheer volume of airplane traffic. Florida and California are 
 internationally known travel destinations. A further study could be to compare data of the number of flights per state vs. the 
 number of accidents per state 
 </p>
 
 <h3>Bar graph</h3>
 <p>  The bar graph shows the summer months have the most fatal and dangerous incidents with a peak in number 
 of people hurt or killed in August. This could also relate to an overwhelming amount of people traveling
 in the summer months vs. any other month. A further study could be to compare the amount of people traveling 
 per month to the current data set.
 </p>