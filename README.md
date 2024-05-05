## NYC Crime Data Analysis

This is a Python script to analyze NYC crime data from 2006 to 2022. The script utilizes pandas for data manipulation and plotly.express for visualizations.

### Data

The script reads data from a CSV file named `NYPD_Complaint_Data_Historic_20231129.csv`. The data includes information about crimes committed in New York City, such as:

* Crime type
* Location (borough, neighborhood, street address)
* Date
* Time
* Victim information (age, race, sex)
* Offender information (age, race, sex)

### Visualizations

The script generates four visualizations to explore crime trends:

1. **Major Crimes in New York City:** This treemap visualization shows the most frequent crime types (offenses) in New York City.
2. **Crime count on each day:** This bar chart shows the distribution of crimes across the days of the week. 
3. **Crime count on each Hour:** This histogram shows the distribution of crimes throughout the day (by hour).
4. **Crime count per Category on each Year:** This time series histogram shows the yearly trend of crimes categorized by offense type.

### Heatmap (Not included in the script)

The code includes a commented section to create a heatmap using `folium`. This heatmap can be visualized by uncommenting the relevant lines. 

### Summary

This script provides a basic analysis of NYC crime data. It reveals that:

* The most common crimes are petit larceny, grand larceny, robbery, burglary, and dangerous weapons.
* Crime rates are highest on Wednesdays and Tuesdays, and lowest on Sundays.
* Crime rates are highest between 3pm and 10pm, and lowest between 6am and 9am. 
* Overall crime rates have been declining in recent years.
