# belly-button-challenge
# Overview

This project involves creating an interactive dashboard that visualizes microbial data using D3.js and Plotly.js. The dashboard allows users to explore bacterial samples from individuals, displaying key insights through a bar chart, bubble chart, and demographic panel. The app is dynamically updated based on user selection and is deployed using GitHub Pages.
# Project Components

__1. Data Retrieval and Processing__
Uses D3.js to fetch microbial data from samples.json and extract key insights. Retrieves sample_values (bacterial counts), otu_ids (unique bacterial identifiers), and otu_labels (bacterial descriptions). Additionally, includes metadata with demographic details for each individual.

__2. Data Visualization__
The dashboard features two main charts: a bar chart and a bubble chart. The bar chart displays the Top 10 OTUs for a selected individual, with sample_values on the x-axis, otu_ids as labels on the y-axis, and otu_labels as hovertext. The bubble chart visualizes all OTUs, using otu_ids for the x-axis, sample_values for the y-axis, sample_values for marker size, and otu_ids for marker color. Both charts dynamically update when a new individual is selected.

__3. Demographic Information Panel__
Displays metadata for the selected individual by extracting key details such as age, gender, and ethnicity. Updates dynamically when a new individual is selected.
__4. Interactive Dropdown Menu__
Allows users to select an individual’s sample ID, dynamically updating all charts and the metadata panel.

# Files

__index.html:__ Main HTML structure for the dashboard.
__app.js:__ JavaScript file handling data fetching, chart creation, and interactivity.
__samples.json:__ JSON data file containing bacterial sample information.
__style.css__ – Optional styling for the dashboard.

# Key Features

__Data Retrieval:__
Fetches and processes JSON data using D3.js.
Extracts sample values, OTU IDs, and metadata.

__Data Visualization:__
Bar Chart: Displays the top 10 bacterial species for a selected individual.
Bubble Chart: Shows the overall microbial composition in a sample.
Metadata Panel: Displays demographic details of an individual.

__Interactivity:__
Dropdown menu allows users to select an individual’s sample.
All charts and metadata panel update dynamically upon selection.

__Deployment:__
The dashboard is deployed via GitHub Pages for easy access.

# Dependencies

__Data Handling:__
Uses D3.js to fetch and parse JSON data.
Ensures proper structuring for visualization.

__Charting & UI:__
Plotly.js for dynamic and interactive charts.
HTML & CSS for page structure and styling.
Deployment
GitHub Pages for hosting the dashboard.

# Technologies Used
__D3.js__: Fetches and processes JSON data.
__Plotly.js:__ Generates interactive charts.
__JavaScript (ES6)__: Handles logic for data transformation and visualization.
__HTML & CSS__: – Structures and styles the dashboard.
__GitHub Pages:__ – Hosts the live version of the dashboard.

# How to Use

1. Clone this repository to your local environment.
2. Open index.html in a web browser.
3. Select a sample ID from the dropdown menu to view the bacterial composition and metadata.
4. Observe the bar chart, bubble chart, and metadata panel updating dynamically.
Deployment Instructions



<!--Mod 14-->
