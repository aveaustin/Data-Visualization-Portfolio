# Visualizing Government Debt
These are various representations of government debt, as a percentage of their GDP

## Embedding directly from OECD.org

<iframe src="https://data.oecd.org/chart/7aYF" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7aYF" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

## A Grid of Line Charts

<div class="flourish-embed flourish-chart" data-src="visualisation/14930937"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## My own custom visualizations

A static chart which allows the user to select individual countries and see how the line changes from the previous country
<div class="flourish-embed flourish-chart" data-src="visualisation/14931058"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This visualization could be optimal for a scenario in which the viewer would like to assess the debt-to-GDP of individual countries and have the ability to switch from one to another and see how the respective line changes when a different country is selected

## A dynamic visualization showing the top five debt-to-GDP ratios since 1995
<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/14931378"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This visualization would be useful to get a quick glimpse at how the highest debt-to-GDP countries have changed over time. While not useful for a specific quantitative analysis, this visualization could be useful if the debt-to-GDP landscape was a talking point within a larger context. 

## A brief reflection on my design choices
The only change to the data I made was removing the included average datapoints, since I only wanted to capture individual countreis. 

The first design I created resulted from a frustration with the second design. I feel like it is easy to look at but hard to read. Because each country has its own small graph, if a viewer wants to compare two countries which are far apart in the grid, they must take a mental snapshot of one and overlay it with the other. To solve this, I created a simple line graph, with a dynamic selector option which allows a viewer to look at one country's data, and then select another and watch how the line changes. Upon reflecting on this, I realized that maybe some viewers do not want to compare specific countreis but instead get an overview of how the data looked over time. These thoughts inspired my second visualization, the racing bar chart. 
The racing bar chart idea came from an idea I had while considering how I could visualize who has had the highest debt-to-GDP ratio over time. While this visualziation does not provide specific quantitative takeaways, it could support a claim regarding debt-to-GDP within a broader context. For example, an academic presenting on the side effects of Japan's rapid technical indsutry growth since 2000 could use a visualization like this to briefly show how their debt-GDP has grown to surpass other countries within and outside of Asia. 

These two visualizations serve ver different purposes. While one is dynamic and interactive for a very detail-concerned user, the other is quite the opposite: lending itself to use as a broad overview on a larger topic. I decided to go with these two extremes because I have found that I typically try to do both within one visualization and it usually leaves both aims unfulfilled. 
