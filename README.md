# Belly Button Biodiversity Dashboard

## Project Description

This project creates an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dashboard allows users to select a sample ID from a dropdown menu and view the following information:

* **Top 10 Bacteria Cultures:** A horizontal bar chart displaying the top 10 Operational Taxonomic Units (OTUs) found in the selected sample.
* **Bacteria Cultures Per Sample:** A bubble chart showing the relationship between OTU IDs, sample values, and OTU labels.
* **Demographic Information:** A panel displaying the demographic information for the selected sample.

## Files

* **`index.html`:** The main HTML file for the dashboard.
* **`static/js/app.js`:** The JavaScript file containing the logic for the dashboard.
* **`samples.json`:** The JSON file containing the Belly Button Biodiversity dataset (hosted remotely).

## App Deployment
The site is successfully deplyed to Github pages:  https://pojanart55.github.io/belly-button-challenge/

## Usage

![image](https://github.com/user-attachments/assets/d20bfc61-c9bc-41cd-9e19-87f2c46c6905)


1.  **Select a Sample ID:**
    * Use the dropdown menu labeled "Test Subject ID Number" to select a sample ID.

2.  **View the Charts and Metadata:**
    * The dashboard will automatically update to display the following information for the selected sample:
        * A horizontal bar chart showing the top 10 OTUs.
        * A bubble chart showing the distribution of OTUs.
        * A panel displaying the demographic information.

## Dependencies

* **D3.js:** Used for data manipulation and DOM manipulation. (Included via CDN)
* **Plotly.js:** Used for creating the charts. (Included via CDN)
* **Bootstrap:** Used for layout and styling. (Included via CDN)

## Notes

* This dashboard uses data from the Belly Button Biodiversity dataset, which is hosted remotely at: `https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`.
* The dashboard is designed to be interactive, allowing users to explore the data by selecting different sample IDs.
* **Credit:**
    * The JavaScript code was developed with the aid of research and documentation found on the Mozilla Developer Network (MDN) web documentation: [https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).
    * Google search was used extensively for debugging to coding challenges.

## Reference
* Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.

