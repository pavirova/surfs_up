# Surf's up

## Overview of the analysis:
This analysis consisted of using Python along with tools like Jupyter Notebook, SQLAlchemy, and SQLite to link Python to sqlite data containing temperature trends for Hawaii. Specifically, we analyzed temperature trends in the city of Oahu for the months of June and December to see if the weather year-round makes it economically viable to open up a surf shop there.

## Results:
- The temperature average for June is lower than the average temperature for the month of December, with December being about 3.9 degrees colder on average.
- The 25th, 50th, and 75th perntiles are approximately 4 degrees hotter for the month of June than they are for December.
- The minimum temperatures between the two months are what vary the most, with December temperatures being 8 degrees colder than June.

The above observations are gathered from comparing the statistics between June and December, shown in the images below:
![June_Temps](/June_Temps.png)

![December_Temps](/December_Temps.png)

## Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
Overall, although the temperatures in December are slightly lower than of June temperatures, wihch is expected, the temperature differences are not drastic, meaning it should be economically viable to run a surf shop year-round in Oahu. 

Another two additional queries that can be performed to gather more weather data would be one query that showcases precipitation levels for the month of June, and one query that showcases the precipitation levels for the month of December. We can then gather the summary statistics for each using Pandas, and can better gage how much rain the city of Oahu receives on average, since this is an important factor to consider, as too much rain could hinder the profitability of the surf shop.
