---
name: HW5 Vega-Lite Plot
tools: [Python, Vega-Lite, Altair]
image: assets/pngs/cars.png
description: Visualization from Homework 5 using Vega-Lite embedded with JSON.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

## Seasonal Trend in Observing by State

This visualization shows the trend in the number of observations throughout different seasons in different states. Observing in different environments may exhibit different preferences and patterns. Users should focus on one state at a time to better compare trends in different seasons, as the number could get overwhelming in all states. This allows the user to see what times of the year and what states are associated with greater frequency of observation. This can provide valuable information about the frequency of observations, revealing on a large scale what areas of the country are more likely to be used and when they are, which may provide some clarity for plans, allocation of resources, or intention-making regarding the use of time and/or resources based on observation.

<vegachart schema-url="{{ site.baseurl }}/assets/json/hw5_chart1.json" style="width: 100%"></vegachart>

---

## Temperature vs. Observations

This plot explores the relationship between mid-range temperature and observations. We wish to understand if there are conditions where observations may be more likely or unlikely, and if there's a relationship between those conditions and observation frequency, including how this may vary by season. With the use of a scatter plot and seasonal color code, the following chart shows possible patterns (more activity during the mild weather) and the way the environment might cause changes in the way one may observe.

<vegachart schema-url="{{ site.baseurl }}/assets/json/hw5_chart2.json" style="width: 100%"></vegachart>
