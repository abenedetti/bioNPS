*Biodiversity in National Parks* is an app that let you visualize [Kaggle's biodiversity dataset](https://www.kaggle.com/nationalparkservice/park-biodiversity). By using the National Park Service  database of animal and plant species identified in individual national parks, the application offers a graphical representation of the data with maps and charts.

![bioNPS|690x369](code/bioNPS.png) 

**Links**

* **RStudio Cloud project:** [https://rstudio.cloud/project/243079 ](https://rstudio.cloud/project/243079)
* **Shinyapps:** [https://abenedetti.shinyapps.io/bioNPS/](https://abenedetti.shinyapps.io/bioNPS/)
* **Github:** [https://github.com/abenedetti/bioNPS/ ](https://github.com/abenedetti/bioNPS/)

**Features**

* The application layout is made with [**shinydashboard**](https://rstudio.github.io/shinydashboard/), that semplifies the creation of dashboards

* The maps are realized with the [**leaflet**](https://rstudio.github.io/leaflet/) package, with an implementation of the species [choropleth map](https://en.wikipedia.org/wiki/Choropleth_map)

* A visual representation of the species' [taxonomy](https://en.wikipedia.org/wiki/Taxonomy_(biology)) is made with the [**collapsibleTree**](https://github.com/AdeelK93/collapsibleTree) package, which make very effective the graphical representation of hierarchical trees

* A web scraping component runs in the backend, and retrieves parks pictures by using the [**rvest**](https://blog.rstudio.com/2014/11/24/rvest-easy-web-scraping-with-r/) package

* Integrated with the [google analytics.js library](https://shiny.rstudio.com/articles/google-analytics.html), to measure how users interact with the app

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.</a>
