# belly-button-challenge
Module 14 Challenge

<h1>Background</h1>
In this assignment, you will build an interactive dashboard to explore the <a href="https://robdunnlab.com/projects/belly-button-biodiversity/">Belly Button Biodiversity dataset</a> to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

<h1>Instructions</h1>
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
    - Use sample_values as the values for the bar chart.
    - Use otu_ids as the labels for the bar chart.
    - Use otu_labels as the hovertext for the chart.

3. Create a bubble chart that displays each sample.
    - Use otu_ids for the x values.
    - Use sample_values for the y values.
    - Use sample_values for the marker size.
    - Use otu_ids for the marker colors.
    - Use otu_labels for the text values.

4. Display the sample's metadata, i.e., an individual's demographic information.
    - Loop through each key-value pair from the metadata JSON object and create a text string.
    - Append an html tag with that text to the #sample-metadata panel.

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.

6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md 

<h3>Resources</h3>

- Tutoring Session
- Xpert Learning Session
- < a href="https://plot.ly/javascript/">Plotly.js documentation</a>