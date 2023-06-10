# belly-button-challenge-M14
Module 14: Belly-Button Challenge - wbsite data visualization using Visial Studion with Json, Plotly & D3

# Instructions
## Complete the following steps:

### Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

### Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
- Use sample_values as the values for the bar chart.
- Use otu_ids as the labels for the bar chart.
- Use otu_labels as the hovertext for the chart.


### Create a bubble chart that displays each sample.
- Use otu_ids for the x values.
- Use sample_values for the y values.
- Use sample_values for the marker size.
- Use otu_ids for the marker colors.
- Use otu_labels for the text values.


### Display the sample metadata, i.e., an individual's demographic information.
- Display each key-value pair from the metadata JSON object somewhere on the page.
- Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

## Advanced Challenge Assignment (Optional with no extra points earning)
The following task is advanced and therefore optional.
- Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.
- You will need to modify the example gauge code to account for values ranging from 0 through 9.
- Update the chart whenever a new sample is selected.



## Hints
Use console.log inside of your JavaScript code to see what your data looks like at each step.
Refer to the Plotly.js documentationLinks to an external site. when building the plots.

# Requirements
## Bar Chart (30 points)
1) Chart initializes without error (10 points)
2) Chart updates when a new sample is selected (5 points)
3) Chart uses Top 10 sample values as values (5 points)
4) Chart uses otu_ids as the labels (5 points)
5) Chart uses otu_labels as the tooltip (5 points)

![Top_10_H_bar_chart](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/Top_10_H_bar_chart.png)

## Bubble Charts (40 points)
1) Chart initializes without error (10 points)
2) Chart updates when a new sample is selected (5 points)
3) Chart uses otu_ids for the x values (5 points)
4) Chart uses otu_ids for marker colors (5 points)
5) Chart uses sample_values for the y values (5 points)
6) Chart uses sample_values for the marker size (5 points)
7) Chart uses `otu_labels for text values (5 points)

![Bubble_chart](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/Bubble_chart.png)

## Metadata and Deployment (30 points)
1) Metadata initializes without error (10 points)
2) Metadata updates when a new sample is selected (10 points)
3) App Successfully Deployed to Github Pages (10 points)

![ID_Dropdown_List_&_Demographic](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/ID_Dropdown_List_&_Demographic.png)
![ID_Dropdown_List](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/ID_Dropdown_List.png)

## Gauge Chart (Bonus)

![Gauge](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/Gauge.png)

![overall_layout](https://github.com/hanydief/belly-button-challenge/tree/main/Outputs/overall_layout.png)
