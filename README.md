# San-Francisco-Housing
![image](https://user-images.githubusercontent.com/114365472/202554097-455eda22-f266-4370-9b8a-1d9b0f44c847.png)

Background

Proptech, the application of technology to real-estate markets, is an innovative domain in the fintech industry. Assume that you’re an analyst at a proptech company that wants to offer an instant, one-click service for people to buy properties and then rent them. The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

Your job is to use your data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.
What You're Creating

For this Challenge assignment, you’ll need to create and submit the following deliverable:

    A Jupyter notebook that contains your analysis of the housing rental market data for San Francisco. The analysis will be complete with professionally styled and formatted interactive visualizations.

Remember to upload your Jupyter notebook for this assignment to your GitHub repository. Make sure to update the README.md file to explain your project and any information that’s needed to interact with your plots.

Instructions

Use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.

Note that this assignment requires you to create a visualization by using hvPlot and GeoViews. Additionally, you need to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame that you’ll use in the analysis.

The main task in this Challenge is to visualize and analyze the real-estate data in your Jupyter notebook. Use the san_francisco_housing.ipynb notebook to complete the following tasks:

    Calculate and plot the housing units per year.

    Calculate and plot the average prices per square foot.

    Compare the average prices by neighborhood.

    Build an interactive neighborhood map.

    Compose your data story.

Calculate and Plot the Housing Units per Year

For this part of the assignment, use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart. To do so, complete the following steps:

    Use the groupby function to group the data by year. Aggregate the results by the mean of the groups.

    Use the hvplot function to plot the housing_units_by_year DataFrame as a bar chart. Make the x-axis represent the year and the y-axis represent the housing_units.

    Style and format the line plot to ensure a professionally styled visualization.

    Note that your resulting plot should appear similar to the following image:

