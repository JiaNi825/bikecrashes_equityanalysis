## Group Mini Update
**Equity Analysis of Bike Crashes in LA**  
Members: Jia Ni, Yuxiang Wei, Xingxiang Huang, Hao Wu, Yanling Sang  

[**1. Proposal**](https://github.com/JiaNi825/bikecrashes_equityanalysis/blob/main/Group%20Assignment/proposal.md)  

**2. Roles**  
- **Race Analysis -- Jia Ni**  


- **Income Analysis -- Yuxiang Wei**  
Wei integrated household median income data with bicycle crash data to analyze their spatial relationship across all census tracts in Los Angeles County. Income levels were categorized into low, middle, and high-income groups and mapped onto the census tracts. Bicycle crash data was processed into geospatial points, and an interactive map was created using Folium, with census tracts color-coded by income and bicycle crashes displayed as markers. Marker clustering was implemented for better visualization, and invalid points were removed. The final interactive map, saved as an HTML file, provides insights into the distribution of bicycle crashes and serves as a foundation for further analysis.

- **Population Density Analysis -- Xingxiang Huang**  
Huang explored the relationship between population density and adjusted bicycle crash rates using logarithmic regression models. Huang identified medium-density areas with higher adjusted crash rates and visualized the findings through scatter plots, bar charts, and both interactive and static maps, providing insights into the spatial patterns.  

- **Age Analysis -- Hao Wu**  
Wu prepared the data by categorizing age groups and encoding them for modeling. Wu then split the data into training and testing sets and trained a Random Forest model. Finally, the model’s performance was evaluated using classification metrics and feature importance.  

- **Vehicle Ownership Analysis -- Yanling Sang**  
Sang processed vehicle ownership and bicycle crash data by normalizing the vehicle ownership percentage to improve visualization clarity and assigning the bike crash data to census tracts. Sang then calculated the crash rates for different census tracts and performed correlation and regression analysis to explore the relationship between vehicle ownership and the occurrence of bike crashes. Finally, Sang created a static map using Matplotlib and an interactive map with Folium to visualize the vehicle ownership percentages and bike crash locations.  

**3. Status Update**  
- **General Mood**  
The team is collaborating effectively and is motivated to proceed.

- **Project Progress**  
We have completed the preliminary data cleaning of five socio-economic characteristics for all the census tracts in LA County, including race, income, population density, age, and vehicle ownership. We also analyzed their relationships with bicycle crashes and conducted related data explorations and map visualizations.
For the next steps, we aim to better understand how the five characteristics influence the occurrence of bike crashes, both individually and collectively. Based on this analysis, we can further explore whether there are inequities in bike crashes in LA, and if certain groups or areas bear a disproportionate share of traffic safety issues.  

**4. Data** 
- [2023 Bike Crash Data](https://tims.berkeley.edu/tools/query/summary.php)
