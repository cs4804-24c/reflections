![image](https://github.com/AndrewSalls/reflections/assets/77992504/aedf192c-f168-4848-816d-6d8d745f5e02)
https://www.iea.org/countries/united-states

For this week, I looked at the International Energy Agency's representation of where the US gets its energy from.
The page has many different types of graphs. The specific graph I looked at uses the selection Energy supply for the Energy topic dropdown, and Total energy supply (TES) by source for the Indicator dropdown.
There are three different ways this graph can be displayed: as a line chart, a stacked area chart, and a stacked area chart using percentages.
I'm not the biggest fan of the line chart. It's pretty generic, and it's hard to see the relations between energy sources besides a general sense of one energy source being much larger than another.

That complaint is why I prefer the stacked area chart. It makes it much easier to see the relative growth or shrinkage of an energy type (such as coal dropping significantly from the 90s), and makes it easier to compare how much energy two different sources provide.
For example, it's much more clear in this graph that wind and solar (the yellow area) used to provide much less power than hydropower (the dark green area), but by 2020 wind and solar have pretty significantly overtaken hydropower.
The area chart also makes it much more obvious when an external event influenced the need for energy in the US. For instance, there is a clear drop in 2020, which is nearly unoticable in the line chart.
One complaint of the area charts is that some of the energy source's names are not displayed. However, the labels of thin sections being hidden is not as big of a deal because you can hover over a section to view what energy type it represents, as well as seeing the exact amount of energy supplied by that type for the given year.
I think this hovering feature also helps with one of the main issues of line/area charts, which is that it can be very hard to tell what the exact value of a point is, especially when the axes are large, like in these graphs. When the axis uses intervals of 100 million terra-joules, a slight mismeasurement of where a point is on the axis could result in a number thats off by a very large amount.

The last graph option is a percentage-based stacked area chart. For the most part, this graph is very similar to the other stacked area chart, trading a more clear relationship between energy sources for a less clear depicition of the quantities of energy provided by each source.
Ultimately, these graphs aren't particularly creative or fancy, but they are well made, and I feel they do a good job of visualization without making it difficult for other agencies to access the data.

One change that I might make is to make it more clear that the legend at the bottom also serves as a toggle for each energy source. Particularly for the percentage graph, hiding some of the energy types would make comparisons between the remaining energy types much easier, but there's no indication that this is possible.
I was actually about to suggest that they add a toggle, before I considered interacting with the legend.
I used this website for my MQP several times, and this was the first time I discovered that functionality, so it would definitely be beneficial for viewers to make the interactivity more clear. I would suggest either adding a help button like some other areas on the site, or changing the icons from a simple colored circle to a toggle switch with the same color.

(Minor aside)
Looking at the implementation, these graphs use Highcharts, which appears to use a similar svg format to what d3 uses. Some research indicates that Highcharts and d3 are some of the most popular visualization tools for websites, so it would be interesting to look at differences between the two.
