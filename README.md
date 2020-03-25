# SMART BRFSS Prevalence Maps (prevalencemaps)
Prevalencemaps is an online R Shiny application for visualizing and exploring prevalence data for multiple conditions as collected by the Selected Metropolitan/Micropolitan Area Risk Trends (SMART) and Behavioral Risk Factor Surveillance System (BRFSS) survey for U.S Metropolitan and Micropolitan Statistical Areas (MMSAs) from the years of 2011 to 2017

Authors: Lena Leszinsky, Sherrie Xie, Avantika Diwadkar, Rebecca E. Greenblatt, Rebecca A. Hubbard, Blanca E. Himes.

### Rationale

Prevalencemaps is a user-friendly resource for the exploration of relationships among BRFSS variables, including geospatial trends at the level of MMSAs. Data displayed in the maps and MMSA-specific graphs were weighted using survey weights from the BRFSS source data and created with the R rgeos, rgdal, and sf packages. Along with displaying the geographical distribution of various BRFSS health outcomes and demographic factors, the app also provides bivariate and multivariable relationship graphics. 

### Dependencies
Prevalencemaps was created using RStudio's Shiny. Running the app locally requires R, with the following packages installed: shiny, leaflet, shinyWidgets, ggplot2, shinydashboard, tigris,
dplyr, reshape2, rgdal, rgeos, sf, feather, survey, jtools, sjPlot, bbplot


You can access the web application here: http://prevalencemaps.org/ 