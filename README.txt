Module 14 Challenge - Belly Button Biodiversity dataset

Background
In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogues the microbes that colonise human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Instructions
Complete the following steps:
1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual
  a) Use sample_values as the values for the bar chart.
  b) Use otu_ids as the labels for the bar chart.
  c) Use otu_labels as the hovertext for the chart.

<img src="https://github.com/kirsty185/belly-button-challenge/assets/126469546/a6e11aea-2931-49a1-b647-af3d8d477e0a" width="45%"></img> 
<img src="https://github.com/kirsty185/belly-button-challenge/assets/126469546/a2ecfffd-77ab-4396-adb8-e9dcdf5d305e" width="45%"></img> 

3. Create a bubble chart that displays each sample
  a) Use otu_ids for the x values.
  b) Use sample_values for the y values.
  c) Use sample_values for the marker size.
  d) Use otu_ids for the marker colors.
  e) Use otu_labels for the text values.
4. Display the sample metadata, i.e., an individual's demographic information.
5. Display each key-value pair from the metadata JSON object somewhere on the page.
6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. 
7. Deploy your app to a free static page hosting service, such as GitHub Pages. (Bellybutton Biodiversity html)

kirsty185.github.io

References
https://plotly.com/javascript/
https://d3js.org/
