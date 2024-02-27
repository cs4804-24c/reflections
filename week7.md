https://xkcd.com/radiation/
https://blog.xkcd.com/2011/04/26/radiation-chart-update/
![image](https://github.com/AndrewSalls/reflections/assets/77992504/0fe33d63-df69-450f-8986-595595451da5)

This week, I looked at XKCD's Radiation Dose Chart. The image here is slightly misleading due to how small it is; the actual chart is very large. This matters because at a smaller scale the text is much harder to read.

The chart shows a bunch of sources of radiation in increasing order by the amount of Sieverts (Sv) you are exposed to from that source. The chart breaks up the sources of radiation by relative group, using different colors for each group.
One thing it does really well is make it easy to compare groups. First, all of the Sv counts are given through square or nearly square grids, which makes it a lot easier to compare to other radiation sources in the same group.
For comparing to a differently colored group, the graph includes the total of the previous group in the next group. While it is still somewhat difficult to do exact comparisons, this makes it fairly easy to compare the rough scales.

Unfortunately, I think that it's still difficult to get a sense of the overall scale between the largest and smallest radiation sources.
I think that making the image into a scrollable interactive image would help, since you could scale the size of each square to match each other's scale (e.g., there are 400 blue squares in a green square, so a blue square could be 1/400th the size of a blue square)
without sacrificing readability. You could also stack the squares into a 1 square wide tower, say that a blue square is 1 foot tall, and then compare the heights of the various stacks to each other and to various famous tall things to provide a better sense of scale.

Also, the units don't really help at all, since most people won't know enough about Sieverts to accurately understand what one square of a specific color means,
and because it's not really possible to convert from multiple squares of one color to the number of squares in a lower color (e.g., how many blue squares are in 4 red squares, without doing the math?)
