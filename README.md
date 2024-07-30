# belly-button-challenge
In this challenge, I built an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

I completed the following steps:

1. Used the D3 library to read in samples.json from the URL: https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
   
2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in each individual.
   - Used `sample_values` as the values for the bar chart.
   - Used `otu_ids` as the labels for the bar chart.
   - Used `otu_labels` as the hover text for the chart.
     
3. Created a bubble chart that displays each sample.
   - Used `otu_ids` for the x-axis values.
   - Used `sample_values` for the y-axis values.
   - Used `sample_values` for the marker sizes.
   - Used `otu_ids` for the marker colors.
   - Used `otu_labels` for the text values.
     
4. Displayed the sample's metadata, i.e., an individual's demographic information.
   - Looped through each key-value pair from the metadata JSON object and created a text string.
   - Appended an HTML tag with that text to the #sample-metadata panel.
     
5. Updated all the plots when a new sample is selected. You are welcome to create any layout you like for your dashboard. An example dashboard is shown on the following page:
`file:///C:/Users/Isbelis/Documents/Bootcamp/Homework/belly-button-challenge/index.html`

6. Deployed the app to a free static page hosting service, such as GitHub Pages. Submitted the links to the deployment and the GitHub repository. Ensured that the repository has regular commits and a thorough README.md file.
   
## Hints:
   - Used `console.log` inside the JavaScript code to see what the data looks like at each step.
   - Referred to the Plotly.js documentation when building the plots.
  
## References:
Hulcr, J. et al. (2012). A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
