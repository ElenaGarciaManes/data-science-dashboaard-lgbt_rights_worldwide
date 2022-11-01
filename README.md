# Final data science project on LGBTQ rights worldwide

 # Link to the dashboard
 The dashboard is hosted in shinyapps.io: https://elena-garcia-manes.shinyapps.io/flex_shiny/#section-world-map
 
# Executive Summary
How are LGBTQ rights protected in different countries? Are LGBTQ rights communities’ rights in various areas secured with the law in the country? How does the right protection vary by country? These are some the questions that we wanted to explore in our project aiming to provide insightful information on LGBTQ rights worldwide with a variety of data visualization using the Flexdashboard package in R. Our dashboard is divided into four distinct tabs that include a world map visualization, a bar chart, a data table, and a pivot table. Each dashboard has a data visualization that users can interactively engage with in exploring the data and the output. 

# Interactive Dashboard
The first dashboard is a world map representing each country’s LGBTQ rights protection or recognition by the law. Users can select in a drop-down menu the right they are interested in: green dots show where legal protection of each LGBTQ right exists, while red dots show the opposite; orange dots represent limited protection, light green where “de facto” protection exists and gray dots indicate no information on the rights. Users can zoom in and out the world map and see which country has the legal protection on LGBTQ community by simply putting the mouse cursor in a specific position or in a country.

The second dashboard contains a data table with interactive elements. For example, users can choose a country or an indicator by typing it in the box or filtering the data with the arrow. The number of entries in a page can also be determined from 10 to 100. This data table can be used when user wants to figure out whether a specific right is protected in a particular country. Users can type either a full name of a country or a country code of two alphabet characters. 

In the third tab users can find an interactive pivot table which users can create and see different types of tables by filtering. The default table is a heatmap that shows if the number of value is above a certain threshold, the color of the value changes. The heatmap table helps users to recognize if a country has the strong protection on LGBTQ rights by showing the number of value highlighted with colors. Right next to the pivot table a stacked bar chart allows us to see the proportion of various rights protection in the world. Users can observe which legal right is protected the most and the least at a glance. 

 # Team
*Elena García Mañes* (e.garcia-manes@mpp.hertie-school.org) found, cleaned, and transformed the dataset for the project and coded it to create an interactive world map showing how LGBTQ rights are protected in each part of the world. *Hyebin Hong* (h.hong@mpp.hertie-school.org) made a bar chart, an interactive data table, and a pivot table. 

# References

**Data:**

- Every year, along with the State-Sponsored Homophobia report, the International Lesbian, Gay, Bisexual, Trans and Intersex Association (ILGA) publishes data on sexual orientation laws in the world. We used the latest available (year 2020).
 
- The dataset containing spatial data is open source and available on Kaggle: Latitude and Longitude for Every Country and State
GPS coordinates for every world country and every USA state (2019) by Paul Mooney.

**Relevant Packages:**
- Winston Chang, Joe Cheng, JJ Allaire, Carson Sievert, Barret Schloerke, Yihui Xie, Jeff Allen, Jonathan McPherson, Alan
  Dipert and Barbara Borges (2021). **shiny: Web Application Framework for R**. R package version 1.7.1.
  https://CRAN.R-project.org/package=shiny
  
- Joe Cheng, Bhaskar Karambelkar and Yihui Xie (2021). **leaflet: Create Interactive Web Maps with the JavaScript 'Leaflet'
  Library**. R package version 2.0.4.1. https://CRAN.R-project.org/package=leaflet

- Hadley Wickham, Romain François, Lionel Henry and Kirill Müller (2021). **dplyr: A Grammar of Data Manipulation**. R
  package version 1.0.7. https://CRAN.R-project.org/package=dplyr
  
- Hadley Wickham (2019). **stringr: Simple, Consistent Wrappers for Common String Operations**. R package version 1.4.0.
  https://CRAN.R-project.org/package=stringr

- H. Wickham. ggplot2: **Elegant Graphics for Data Analysis**. Springer-Verlag New York, 2016.
