# NETN_FHM_Photos 
This repo contains code to compile data for and run the Northeast Temperate Network forest 
plot viewer and data summary for the most recent visit to NETN plots (2023 to 2026). 

The following files are part of the repo:  

<ul>
<li>ui.R: user interface for shiny app</li>
<li>server.R: server for shiny app</li>
<li>global.R: global parameters and data frames sourced by shiny app</li>
<li>data_and_photo_prep.R: folder containing scripts used to compile/update data for the shiny app </li>
<li>data/boundboxes.csv: lat/long coordinates to bound the leaflet map</li>
<li>data/Plots.csv: contains the info summarized in popups for each plot.</li>
<li>www/: folder containing wetland photopoints, CSS and other objects sourced by the app</li>
</ul>

The data used for this shiny app are available publicly on NPS DataStore 
<a href = "https://irma.nps.gov/DataStore/Reference/Profile/2315861">record 2315861</a>. 