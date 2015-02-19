# bioviz_lab4
D3 Lab for Bioviz

Since I've used d3 before, I decided to play around with something I had never tried - maps. I went through the [Let's Make a Map] (http://bost.ocks.org/mike/map/) tutorial, which was surprisingly difficult to get working. My main issue was processing the map data, which took some cleanup on my brew and node installs (my MQP included some sudo-ing that left my machine a little rickety). I then added a couple of things, namely removal of several overlapping tags and the addition of highlighting of countries on hover.

I then took a crack at getting the [Non-Contiguous Map](http://bl.ocks.org/mbostock/4055908) example working. I downloaded the US dataset and got the example working, and then added a couple of small things. I added highlighting on hover again, as well as a tooltip that showed the specific obesity rate when hovering over a state. You can get to this by clicking the link at the bottom of the first example.

I also added background lines to each state, because it wasn't clear how much each was varying from its size. Finally, I made hovering on a state grow it back to normal size.

The live version is [here](http://jdb175.github.io/bioviz_lab4/).