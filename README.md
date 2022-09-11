# San Francisco Housing Data Dashboard

## Background
Harold's company has just started a new Real Estate Investment division to provide customers with a broader range of portfolio options. Harold was tasked with building a prototype dashboard and he needs your help. The real estate team wants to trial this initial offering with investment opportunities for the San Francisco market. If the new service is popular, then they can start to expand to other markets.
The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.
In this homework assignment, you will help Harold accomplish the following tasks:


Complete a notebook of rental analysis.


Create a dashboard of interactive visualizations to explore the market data.

## Instructions

### Rental Analysis
The first step to building the dashboard is to work out all of the calculations and visualizations in an analysis notebook. Once the code is worked out here, it can be copied over to a dashboard code and used with Panel to create the final layout. Use the rental_analysis.ipynb to complete the following:

### Housing Units Per Year
In this section, you will calculate the number of housing units per year and visualize the results as a bar chart using the Pandas plot function.

### Average Housing Costs in San Francisco Per Year
In this section, you want to determine the average sales price per year and the average gross rent per year to better understand housing costs over time. For example, a customer will want to know if they should expect an increase or decrease in the property value or rent over time so they can determine how long to hold the rental property. You will visualize the average (mean) gross rent and average price per square foot per year and visualize it as a bar chart.

1. Calculate the mean gross_rent and sale_price_sqr_foot for each year.
2. Visualize the mean gross_rent and sale_price_sqr_foot for each year as two line charts.

### Average Prices By Neighborhood
In this section, you will use hvplot to create two interactive visulizations of average prices with a dropdown selector for the neighborhood. The first visualization will be a line plot showing the trend of average price per square foot over time for each neighborhood.  The second will be a line plot showing the trend of average montly rent over time for each neighborhood.

### Top 10 Most Expensive Neighborhoods
In this section, you want to figure out which neighborhoods are the most expensive. You will need to calculate the mean sale price for each neighborhood and then sort the values to obtain the top 10 most expensive neighborhoods on average. Plot the results as a bar chart.

### Comparing Cost to Purchase Versus Rental Income
In this section, you will use hvplot to create an interactive visualization with a dropdown selector for the neighborhood. This visualization will feature a side-by-side comparison of average price per square foot versus average monthly rent by year.

### Neighborhood Map
In this final section, you will read in neighborhood location data and build an interactive map with the average prices per neighborhood. Use a scatter mapbox object from plotly express to create the visualization. Remember, you will need your mapbox API key for this.

### Cost Analysis - Optional Challenge
In this optional challenge section, you will use plotly express to create a Parallel Coordinates plot, Parallel Categories plot, and a Sunburst plot so that investors can interactively filter and explore various factors related to the sales price of the neighborhoods.

1. Create a Parallel Coordinates Plot.
2. Create a Parallel Categories Plot.

## Dashboard
Now that you have worked out all of the code and analysis, you will use the Panel library to build an interactive dashboard for all of the visualizations. There are no hard requirements for the layout of this dashboard, so use your own imagination and creativity!
Use the provided starter notebook, dashboard.ipynb, for your dashboard code. Copy the code for each visualization from the analysis notebook and place it into separate functions (1 function per visualization). This will make it easier to build and modify the layout later. Each function should return the plot figure in a format that Panel can use to plot the visualization.