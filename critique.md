# Part 1: Visualization critique

I saw a tweet from [Mike Bostock](https://twitter.com/mbostock) showing off a [d3 ridgeline plot](https://beta.observablehq.com/@mbostock/d3-ridgeline-plot) as an alternative to [horizon plots](https://bl.ocks.org/mbostock/1483226). The ridgeline plot does a decent job of including a lot of data in a small area. The density of the plot cost clarity and interpretability.

This visualization is simple and straightforward. That being said, the third dimension is unlabeled. The height of the area chart within each German city is undefined. While this isn't untruthful or misleading it isn't complete and not presenting the entire story is not fully truthful.

Especially when compared to a horizon plot this type of graphics doesn't add anything functional. Beyond a table of numbers this allows the reader to recognize the relationship between time and traffic more easily, but without sufficient labeling, it's not clear that this leads to any particular conclusion.

The ridgeline plot has something that draws the eye more than the horizon plot. With some careful consideration for ordering on the y-axis, I think this diagram could better show the relationship between towns. The overlapping plots hide data unnecessarily. Due to its simplicity, it may be easy to dismiss it without searching for insight.

There is a clear pattern of the day. Traffic consistently rises early in the day at drops off around 12 PM. Something to be looked into is the peaks on the first five days in relation to the gaussian on the sixth day.

Policy decisions could be influenced by this graphic. It shows a traffic pattern. With some thought, the peaks could be more evenly distributed for maximum efficiency.

Overall this visualization of traffic in German towns is not great. There are several iterations of visualizations of this data from the source of the data. [Moritz](https://beta.observablehq.com/@moklick) starts with a [historgram](https://beta.observablehq.com/@moklick/histo) and evolves to a [multiple line chart](https://beta.observablehq.com/@moklick/traffic-data-lines) and then a [multiple area chart](https://beta.observablehq.com/@moklick/traffic-small-muliple-lines) that I think best displays this data while still lacking a complete explanation of the data.