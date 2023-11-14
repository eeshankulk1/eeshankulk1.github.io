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

<vegachart schema-url="{{ site.baseurl }}/assets/json/charthw81.json" style="width: 100%"></vegachart>


# Plot 2

For plot 2, I wanted to see how the license statuses varied from license to license. For this, I created an interactive plot that allows you to choose the license you want to investigate, and the bar plot adapts to show the counts of each license status for said license. I chose to do this for my interactive visualization because it allowed me to see the "history" of each license type, and what the status of those who obtained the lience is. It was actually very interesting, as many licenses had a much higher rate of suspended or not renewed compared to others, suggesting that profession might have a lot of people leaving after working for a few years.


<vegachart schema-url="{{ site.baseurl }}/assets/json/charthw82actual.json" style="width: 100%"></vegachart>


<div class="left">
{% include elements/button.html link="[https://github.com/vega/vega/blob/main/docs/data/cars.json](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv)" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

