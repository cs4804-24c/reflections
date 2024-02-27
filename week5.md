https://benschmidt.org/jobs/
![image](https://github.com/AndrewSalls/reflections/assets/77992504/39f97ff5-f0f7-45a1-a91b-c13c7ac2c95f)

This week, I looked ad Ben Schmidt's Sankey diagram depicting the relation between what degree people got and what job they work in.
While not particularly good looking due to the number of different degrees represented, I think this diagram does a good job at utilizing interactivity to make the diagram easier to read.

Firstly, you can click on a degree or job to filter to just connections to that degree/job. You can also click on a specific degree-job link to expand the job and degree effectively combining a filter on the degree and a filter on the job.
Both of these options make it much easier to identify relations between a specific job and degree. For more detail, hovering over one of the connections shows a tooltip containing the exact number of people with a specific job-degree combo, and how that compares to the "expected" number of people with that combo.

There are also several flaws in the diagram. The different jobs and degrees have different colors, but only some of the connections use that color, and many of the jobs/degress displayed are so small that the color is not visible at all.
The problem with size also exists with the connections, since it can be hard to click or hover on smaller lines. I think both of these problems could have been fixed by clustering jobs and degrees into general columns (like the author did on a similar page, but that visualization's code is broken and too difficult to manually fix)
, and then adding a new column on the left and right that break down the clusters into their specific jobs/degrees. That way, you could still filter by a specific job/degree, but it would be much easier to find the job/degree you're looking to compare, and easier to click or hover on the connection.

P.S., when I mentioned that the other page's code is broken, so is the page that I linked, because the author updated to https without fixing their scripts. To load the visualization on-site, run the following script in the web browser terminal (F12 -> Console)
```
var script = document.createElement("script");
script.type = "text/javascript";
script.src = "https://d3js.org/d3.v3.min.js";

document.getElementById("chart").appendChild(script);

var script2 = document.createElement("script");
script2.src = "sankey.js";

document.getElementById("chart").appendChild(script2);

var script3 = document.createElement("script");
script3.src = "jobs.js";

document.getElementById("chart").appendChild(script3);
```
