---
name: Vega Lite Example Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Plot 1

My first plot was created to show the distribution of all the various license types. This served to get a feel for what data made up most of the dataset. Doing this analysis and creating this chart showed me that the licenses in the dataset were mostly cosmotology, detective, and dental. As for my encoding types, I used the license category for the x, the corresponding count for the y values, a bar plot to depict my vizualization and a rainbow of colors to differentiate each license in the plot. While I created a similar plot in Homework #7, the method for counting the licenses was very different in altair, which took some getting used to.

```
<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>

```
