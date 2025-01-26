# Dashboard for Bacteria Cultures Analysis

This project is an interactive dashboard that visualizes bacteria cultures found in different samples. It features a metadata panel, a bubble chart, and a bar chart, which dynamically update based on the selected sample from the dropdown menu.

## Features
- **Metadata Panel**: Displays key-value pairs of metadata for the selected sample.
- **Bubble Chart**: Shows the distribution of bacteria cultures per sample, with markers representing the number of bacteria and their IDs.
- **Bar Chart**: Displays the top 10 bacteria cultures found in the selected sample.

## How It Works
1. The app fetches data from a JSON file using D3.js.
2. Dropdown options are dynamically populated with sample IDs.
3. When a sample is selected, the metadata panel and charts update with data corresponding to the selected sample.

### Key Functions
- **`buildMetadata(sample)`**: Updates the metadata panel with the selected sample's metadata.
- **`buildCharts(sample)`**: Builds and renders both the bubble and bar charts for the selected sample.
- **`init()`**: Initializes the dashboard by loading the data and setting the default sample.
- **`optionChanged(newSample)`**: Event listener that triggers when a new sample is selected.

## Libraries and Tools
- **D3.js**: For data fetching and DOM manipulation.
- **Plotly.js**: For rendering the interactive charts.

## Usage
1. Clone this repository.
2. Ensure you have an internet connection to fetch the JSON file from the external source.
3. Open the project in a browser to interact with the dashboard.

## Project Structure
- `index.html`: The main HTML file containing the structure of the dashboard.
- `app.js`: JavaScript file with the logic for fetching data, creating charts, and handling interactions.

## Data Source
The data is fetched from the following JSON file:
https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json

## Webpage Link
[View the dashboard here] 
(https://metaferya.github.io/belly-button-challenge/)

