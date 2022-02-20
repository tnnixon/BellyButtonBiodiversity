<h1>Belly Button Biodiversity Dashboard</h1>
<br><br>
<b>Dashboard:</b> https://tnnixon.github.io/BellyButtonBiodiversity/
<br><br>
In this project, I built an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
<br>
<br>
1. Used the D3 library to read in samples.json.
<br>
<br>
2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
<br>
• Used sample_values as the values for the bar chart.<br>
• Used otu_ids as the labels for the bar chart.<br>
• Used otu_labels as the hovertext for the chart.<br>
<br>
<br>
3. Created a bubble chart that displays each sample.
<br>
• Used otu_ids for the x values.<br>
• Used sample_values for the y values.<br>
• Used sample_values for the marker size.<br>
• Used otu_ids for the marker colors.<br>
• Used otu_labels for the text values.<br>
<br>
<br>
4. Displayed the sample metadata, i.e., an individual's demographic information.
<br>
<br>
5. Displayed each key-value pair from the metadata JSON object somewhere on the page.
<br>
<br>
6. Updated all of the plots any time that a new sample is selected.
<br><br>
<b>References</b><br>
Hulcr, J. et al.(2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
