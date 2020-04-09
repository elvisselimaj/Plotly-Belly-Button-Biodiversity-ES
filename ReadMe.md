![bay](elvis-images/gauge.png)

![bay1](elvis-images/pie_chart.png)

![bay2](elvis-images/dashboard_part1.png)

Belly_Button_Diversity

Plot.ly Homework - Belly Button Biodiversity

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity DataSet.

Before You Begin

Create a new repository for this project called plotly-challenge. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, create a directory for the Plotly challenge. Use the folder name to correspond to the challenge: Belly_Button_Diversity.

This is a full stack app so add your html, js, css, python and sqlite files.

Push the above changes to GitHub or GitLab.

Step 1 - Plotly.js Use Plotly.js to build interactive charts for your dashboard.

Create a PIE chart that uses data from your samples route (/samples/) to display the top 10 samples.

Use sample_values as the values for the PIE chart.

Use otu_ids as the labels for the pie chart.

Use otu_labels as the hovertext for the chart.

Create a Bubble Chart that uses data from your samples route (/samples/) to display each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

Display the sample metadata from the route /metadata/

Display each key/value pair from the metadata JSON object somewhere on the page.

Update all of the plots any time that a new sample is selected.

You are welcome to create any layout that you would like for your dashboard. An example dashboard page might look something like the following.

Step 2 - Heroku Deploy your Flask app to Heroku.

You can use the provided sqlite file for the database.

Ask your Instructor and TAs for help!

Advanced Challenge Assignment (Optional) The following task is completely optional and is very advanced.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the Weekly Washing Frequency obtained from the /metadata/route.

You will need to modify the example gauge code to account for values ranging from 0 - 9.

Update the chart whenever a new sample is selected.

Flask API Use Flask API starter code to serve the data needed for your plots.

Test your routes by visiting each one in the browser.

Hints

Don't forget to pip install -r requirements.txt before you start your server.

Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js Documentation when building the plots.
