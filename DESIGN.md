# Data Sources
-Drug abuse(http://datafiles.samhsa.gov/study-series/national-survey-drug-use-and-health-nsduh-nid13517)
-Drug use(http://pdas.samhsa.gov/saes/state)
    I'm going to take data from every year since 2002. I will need to put that data in one file and
    into a JSON.
-Drug related arrests(http://www.drugwarfacts.org/table/total_arrests)
    I will need to put this data into a JSON file.
-Drug overdoses(https://www.drugabuse.gov/related-topics/trends-statistics/overdose-death-rates,
    https://data.unodc.org/)
    I will need to take the relevant data into a JSON.

# Components and needs
For the map visualization I need the Datamaps plugin for d3.js. I will have to enter the data and
change the color with a range of percentages. This will be updateable with the slider.

For the barchart I will need to create a function that updates the barchart when the slider is moved.
I will also have to assign colors for different drugs.

The line chart needs a function that puts a vertical line on it, relating to which year is shown on
other visualizations. I will also have to create a second y axis for the amount of money spent on DEA.

The scatterplot needs a dropdown that changes the variable on the y axis.

# D3 plugins

I will need Datamaps to render a map. The rest is done with d3.js
