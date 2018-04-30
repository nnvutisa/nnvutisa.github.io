---
layout: post
title: US Monthly Average Precipitation and Snowfall
excerpt: "A state level interactive map of average precipitation and snowfall using the Python package Bokeh"
tags:
- data visualization 
- Bokeh
link: https://nnvutisa.github.io/weather/index.html
---

This visualization project started because I wanted location weather data as features for another analysis project. After constructing a table of monthly precipitation and snowfall level for each state, I wanted to quickly visualize the data. Then the simple visualization turned into a more complicated interactive visualization. The plots were created using Bokeh, a Python interactive visualization library. This project does not use a data server. Instead, Bokeh converts the python code into Javascript that renders the plots in the browser. Anyone interested in interactive visualization in Python might also want to check out [Dash](https://plot.ly/products/dash/) by Plotly, which came out a bit after this project. 

[Check out the visualization](https://nnvutisa.github.io/weather/)

You can use the slider at the bottom to change the displayed month. Hover over the states to see the values. 

The code for the data and the plots are on [this Github page](https://github.com/nnvutisa/weather). The data files are also available for anyone interested. 
