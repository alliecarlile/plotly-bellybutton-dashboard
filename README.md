Background

For this project, I've built an interactive dashboard to explore the Belly Button Biodiversity which catalogs the microbes that colonize human navels.

Test dashboard <a href="https://alliecarlile.github.io/plotly-bellybutton-dashboard/">here</a>

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Project was completed by using the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

bar Chart

Create a bubble chart that displays each sample.
Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

Bubble Chart

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

Advanced Challenge 

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

Weekly Washing Frequency Gauge

![bellybutton`](https://user-images.githubusercontent.com/105824024/208501221-16936f0c-26da-41bc-8e47-d174a5fab28d.png)


![belly2](https://user-images.githubusercontent.com/105824024/208501264-85f8d92b-04ce-4a96-a124-e5e77021119b.png)


**Methods used:**

JavaScript

HTML

CSS

D3 library 

Plotly 


