# Foresight

Foresight is my deep-dive into taking what might normally be an [Exploratorium](https://www.github.com/dataframing/exploratorium) post and turning into a web application. I'll be working with 311 complaint data from the NYC Open Data platform.

## Data

The data is sourced from [NYC's Open Data](https://opendata.cityofnewyork.us/) initiative [here](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9). At approximately 15.2 million rows, the dataset represents millions of complaints made by New Yorkers from 2010 to the present.

## Background

As part of the Big Data course at NYU's Center for Data Science, myself and two group members looked into the 311 data set. Our group used a whole bunch of buzz-word tools and frameworks, like: PySpark, sparkle, dplyr, ggplot, and more!

We saw a ton of interesting avenues for analysis, but had to limit ourselves to about two or three. I'll be pursuing and coming up with more avenues for analysis here.

## Going Forward

Keep an eye on this repository as I hack on public data! It'll be a good time, I promise.

In more concrete terms, I've planned this project to be a web application using the Flask framework. A user can enter a NYC address or ZIP code, which will trigger a Google Maps API query. Afterwards, they'll receive descriptive statistics regarding their location of interest. To really tell the story, I'll be using D3.js to make the experience more interactive. Fun!