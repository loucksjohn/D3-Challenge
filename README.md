# D3-Challenge
data journalism and D3



![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Description

This D3 project is a data visualization of the current trends shaping people's lives.

Based off information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System, I have created an interactive scatterplot to explore the health risks facing particular demographics.  The data set included in this repository  is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), and includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."



## Operating Instructions

In order to view the dashboard, you will need to navigate to  https://loucksjohn.github.io/D3-Challenge/. in your internet browser. Once the site has loaded, you can select between Poverty (%) or Age (Median) just below the X-axis. The circles representing states will then move location based on your selection.  If you mouse over the circles a pop-up will appear that will give you the data for the state that you moused over.

## Resources

In the GitHub repository for this project you will find all the resources necessary for the creation of this dashboard. Here's a quick rundow of those files and a brief explanation:

- data.csv - this is the data that is being leveraged to build the chart and is from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System
- index.html - is the the webpage framework that displays the interactive chart in the browser
  - please note that within the index.html file you will find addtional outside sources. Bootstrap is being referenced in the building of the webpage structure, D3 is being used as a source to manipulate the data in the files , and d3-tip is also being used as a source to help create the charts/graphs.
- app.js - this is the javascript file that that is running in the HTML. in app.js, I am reading in the 'data.csv' file and then manipulating it so that it can be used to create the chart.

## Other Notes

There is a folder entitled "experiment" in my repository that you might notice, as well.  I was attempting to add additional selections to the Y-Axis as part of the bonus, and I was keeping all of those files separate in the "experiment" folder.  I ran out of time and didn't get to the final product, but you can see from the app2.js file that I was making progress in having a chart containg two possible selctions on both the X and Y axis.

## Author

John Loucks
Email: [johnloucks@gmail.com](mailto:johnloucks@gmail.com)
GitHub: https://github.com/loucksjohn