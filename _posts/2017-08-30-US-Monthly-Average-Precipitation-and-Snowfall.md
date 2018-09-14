---
layout: post
title: US Monthly Average Precipitation and Snowfall
excerpt: "A state level interactive map of average precipitation and snowfall using the Python package Bokeh"
tags:
- data visualization 
- Bokeh
link: https://nnvutisa.github.io/weather/index.html
---

#### [Click to see the visualization](https://nnvutisa.github.io/weather/)

This is an interactive visualization of precipitation and snowfall data for the 48 mainland states. The wather data was obtained from the [NOAA](https://www.ncdc.noaa.gov/cdo-web/) 1981-2010 climate normal dataset. The plot shows the monthly average values calculated as unweighted averages of all the values from weather stations within each state. 

You can use the slider at the bottom to change the displayed month. Hover over the states to see the values. 

The plots were created using Bokeh, a Python interactive visualization library. This project does not use a data server. Instead, Bokeh converts the python code into Javascript that renders the plots in the browser. Anyone interested in interactive visualization in Python might also want to check out [Dash](https://plot.ly/products/dash/) by Plotly, which came out a bit after this project. 

The code for the data and the plots are on [this Github page](https://github.com/nnvutisa/weather). The data files are also available for anyone interested. 
