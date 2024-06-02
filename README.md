# belly-button-challenge

## GitHub Pages Deployed App

You can view the deployed app on GitHub Pages at the following link:
[GitHub Pages Deployed App](https://your-github-username.github.io/belly-button-biodiversity-dashboard/)

## Context of the Challenge: Background

This interactive dashboard explores the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


## Project Structure

The project consists of the following files:

### HTML
- `index.html`: The main HTML file that sets up the structure of the dashboard, includes necessary libraries, and links to the CSS and JavaScript files.

### CSS
- `styles.css`: The CSS file that provides styling for the HTML elements, including background colors and text colors.

### JavaScript
- `app.js`: The main JavaScript file that contains the functions to build the metadata, charts, and handle the dropdown menu changes.

### External Libraries
- Bootstrap: Used for responsive design and styling.
- D3.js: Used to fetch and manipulate the data.
- Plotly.js: Used to create the charts.

## Files in the Project
1. `index.html`
2. `styles.css`
3. `app.js`

## Usage

1. Open `index.html` in a web browser to view the dashboard.
2. Select a Test Subject ID Number from the dropdown menu to explore the corresponding metadata and charts.
3. The dashboard will dynamically update to display the selected sample's data.

## Setup Instructions

1. Clone the repository to your local machine.
2. Open the `index.html` file in your preferred web browser to view the interactive dashboard.

## Description of Files

### `index.html`
The main HTML file that sets up the structure of the dashboard, includes necessary libraries, and links to the CSS and JavaScript files. It contains:
- A container for the dashboard layout.
- Dropdown menu for selecting test subjects.
- Sections for displaying metadata and charts.

### `styles.css`
The CSS file that provides styling for the HTML elements, including:
- Background color settings for different sections.
- Text color adjustments.

### `app.js`
The main JavaScript file that contains:
- `buildMetadata(sample)`: Fetches and displays metadata for the selected sample.
- `buildCharts(sample)`: Fetches and displays charts for the selected sample.
- `init()`: Initializes the dashboard with the first sample's data.
- `optionChanged(newSample)`: Updates the dashboard when a new sample is selected.

By following these instructions and using the provided files, you can explore the fascinating world of microbial species that inhabit human navels through this interactive dashboard.
