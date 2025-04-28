# Transforming a Static Dashboard into an Interactive Dashboard"

For this lab assignment, you are tasked with transforming your previous static
dashboard into an interactive dashboard using either Shiny or webR. 

## Dashboard Requirements

The dashboard you create **must** have the following:

- at least one opportunity for user input via a slide bar
- at least one opportunity for user input via check boxes 

These interactive features are expected to be used to:

- update at least one visualization
- update at least one of your "quick information" cards

*Note: You are free to swap one of your visualizations out for an interactive table!*

## Submission

You are required to submit **both** the link to your GitHub repository 
containing your source code **and** a link to your [published]{.underline}
dashboard. You are expected to publish your dashboard through
[Quarto Pub](https://quarto.org/docs/publishing/quarto-pub.html), a free
publishing service for static content created with Quarto. 

This dashboard can be found at <https://stat541.visruth.com/interactive_dashboard>

## Notes

Memory is limited, so I had to convert the original xlsx data to a csv before reading it in. Apparently reading in an xlsx (using `{{readxl}}` at least) was relatively memory intensive, so using a csv is preferred. I passed a pre-processed CSV to the dashboard.
