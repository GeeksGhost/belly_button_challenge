# Belly button Button
This assignment uses Javascript to parse data gathered from https://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/. Then uses Plotly to visualize the parsed info. 

## Project Overview
The project create an interactive dashboard to explore the Belly Button Biodiversity dataset, which shows that a few microbial species are common in over 70% of people, while most are rare.

## Project Data Sources
-- https://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
-- https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json

## Exploring and ploting data
Uses D3 library to read json informaiton in. Then seperates the data to be used to:
  - populate "test subject ID Number" pull down menu"
  - run a sort function to find the top 10 OTU's per subject
  - Creates a bubble chart on Bacteria cultures per sample
  - Creates a bar chart to visualize top 10 OTU's per subject 

## The project main code can be found: 
https://github.com/GeeksGhost/belly_button_challenge/blob/main/static/js/app.js
