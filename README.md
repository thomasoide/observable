# Observable Notebooks
Ever since I learned about Observable at NICAR 2019, I've been trying to find ways to use the platform. I think it has so much potential and I'm very much looking forward to integrating it into my workflows. See some of the notebooks I've worked on below:
## Twins Home Runs
[Link to the notebook](https://observablehq.com/@thomasoide/twins-hrs)

This notebook is the embodiment of everything good about Observable. As the Minnesota Twins approached the MLB home run record, I was tasked with creating a graphic that told the story of the season. To do that, I found the statistics to plot, game-by-game, all the home runs the Twins hit compared to the top 15 home-running hitting teams in baseball history. The last thing I wanted to do was create 18 separate charts in Illustrator, so I did it in D3/Observable instead. 

[Link to the project](http://www.startribune.com/smashing-homers-shattering-a-record/537432771/)

I built out a simple Scrollymagic framework that pinned each slide to the top of the page for 500 pixels and sussed out the order of my graphics. That way, when the Twins actually broke the record, it was a matter of downloading an SVG from Observable, quickly annotating the graphics in AI and dropping them in an S3 bucket for the page to pull from. 

## Missouri Small Water Systems Map
[Link to the notebook](https://observablehq.com/@thomasoide/missouris-chlorinated-small-water-systems)

I built this map in Observable using D3 and TopoJSON. I did the necessary data processing using an R script and hosted the resulting csv file in a gist. The map is meant to show the number of small water systems that use chlorine across the state of Missouri and the median age of those systems. I added a tooltip in the notebook, but since this eventually turned into a static graphic, it wasn't used in production. 
## Missouri House/Senate Bill Process Graphic
[Link to the notebook](https://observablehq.com/@thomasoide/missouri-legislature-house-bill-process)

This is a newsroom tool I created using Jeremy Ashkenas' Inputs library and D3. The Columbia Missourian's graphic desk came up with an idea to illustrate to readers where bills are in the legislative process. However, these graphics were generic, and didn't have any other information about the bill attached to them. I wanted to see if I could find a way to use Observable to make these graphics custom, in real-time by using information written by the 30+ Missourian reporters who cover the Missouri legislature from week to week. 
