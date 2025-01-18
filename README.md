# Belly Button Biodiversity Dashboard

## Here's a brief overview of what each section does:

## Build the Metadata Panel:

+ Fetch data and get the metadata field.

+ Filter metadata for the desired sample.

+ Select the #sample-metadata panel and clear existing content.

+ Append new tags for each key-value pair in the filtered metadata.

## Build the Charts:

+ Fetch data and get the samples field.

+ Filter samples for the desired sample.

+ Extract otu_ids, otu_labels, and sample_values.

+ Build and render a Bubble Chart.

+ Build and render a Bar Chart.

## Initialize the Dashboard:

+ Fetch data and get the sample names.

+ Select the dropdown and populate it with sample names.

+ Build initial charts and metadata panel with the first sample.

## Event Listener Function:

+ Update charts and metadata panel when a new sample is selected.

