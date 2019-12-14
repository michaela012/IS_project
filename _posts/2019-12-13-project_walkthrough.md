---
layout: post
title: Project Walkthrough
subtitle: (and reflections)
---

#### We've done it! Read on for a walkthrough, or just check it out [here](link.com). 

## homepage
We start with this, the main homepage. It links to all available color families, as well as a descriptive overview page. 
![](/is-project/img/home.png)

## informational pages
The first page shown here is the overview page, which is linked to from the homepage. The overview page has several supplementary links, including the second page shown here. This 'notes' page gives more information on the information available for each image, as well as a brief description on how the image classification was handled. 
![](/is-project/img/overview.png)
![](/is-project/img/notes.png)

## main color pages
The color pages are the most fun, and of course, these are the heart of the visualization. Each color category is subdivided into two components: light and dark images. Clicking the 'light', 'dark', or color tag (central node) toggles the visibility of the component and makes the color selection menu visible. Some examples at different stages and sizes:

![](/is-project/img/purple-open.png)
![](/is-project/img/purple_banana.png)
![](/is-project/img/cyan_menu.png)
![](/is-project/img/cyan_landscape.png)
![](/is-project/img/black-dark.png)

Credit and thanks to the work of [Mike Bostock](http://bl.ocks.org/mbostock/1062288), [Sundar Singh](https://bl.ocks.org/eesur), and [Paul Brady](https://bl.ocks.org/Paul-Brady) --a combination of these works formed the starter code for this portion of the project.
 
## special sepia layout
When you hear 'sepia' you might not think 'special', but I had great fun with this portion of the project layout. Even after severely limiting the constraints for sepia classification, there was still an overabundance of pieces (for details on the classification process for this color range, read the overview page shown above). There were too many images for a graph, so I opted for a grid layout instead-- and note the size of the scroll bar! The header contains the nav links, and detailed piece information is shown when the user hovers over each image. 

![](/is-project/img/sepia_open.png)
![](/is-project/img/sepia_expanded.png)
![](/is-project/img/sepia_scrolled.png)

Thanks to Andy Barefoot's [Medium post](https://medium.com/@andybarefoot/d3-and-css-grid-with-expanding-content-3c8aaf783cb1) for a tutorial on D3 grid basics. 

## reflections
Overall, I'm pretty pleased with how this turned out, and I'm happy with this as a first attempt at info vis and the d3 library, not to mention my first real go at html and css. That said, there are two main things that are really bothering me about the main (graph) color pages, and that hopefully I'll be able to fix in the future: the lack of dynamic sizing and the fact that the graph is fully expanded when the page loads. 

The former is an issue on any screen that differs from the size of my laptop. The second matters on the larger color categories, but not the smaller ones. It's troubling. For the annoying (and sometimes amusing) issues that I *did* manage to fix, see my next post!

