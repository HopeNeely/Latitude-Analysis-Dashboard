Latitude Analysis Dashboard

The challenge here is to create a visualization dashboard website using visualizations created in the matplotlib challenge. Specifically, the data ploted is [weather data](Resources/cities.csv).

In this dashboard, individual pages have been created for each plot and links to navigate between them. These pages contain the visualizations and their corresponding explanations. A landing page is included showing the comparison of all of the plots, and another page where we can view the data used to build them.

The website consists of 7 pages total, including:

* A Home paige containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.

The website includes, at the top of every page, have a navigation menu that:
 * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
 * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
 * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
