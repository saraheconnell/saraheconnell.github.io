---
layout: post
title: 2022 and 2023 summaries and comparison
---

Julia and I are teaching GitHub Pages again, which means that it is time for an update to this blog series. Since it's [been a while](https://saraheconnell.github.io/preview/), there's quite a lot to update about. In 2022 and 2023, I standardized the way I've been tracking animal sightings to include the number of animals as well as the location from which I spotted them. Just as I did in [deciding how to identify the animals I see](https://saraheconnell.github.io/natureJournal/), my decisions about location are highly personalized to the ways that I experience my own geographies. For example, I track four different locations in downtown Exeter separately, because those feel significantly distinct to my experiences of them, but in many other cases I don't get any more precise than the name of the town. Because I was living in the same location *and* tracking my animal sightings in the same way for 2022 and 2023, I can at last compare year-to-year data. I'll post on that next.

Before I get to comparison, let's just look at the animals I saw in those two years. Since this blog is something I maintain as part of my teaching for Northeastern's [Graduate Certificate in Digital Humanities](https://cssh.northeastern.edu/nulab/program/dh-certificate/), I wanted to test out the same tools that Julia and I have been using in class to talk about data prototyping for DH Certificate [final projects](https://cssh.northeastern.edu/nulab/program/dh-certificate/project-showcase/). In particular, I thought that [RawGraphs](https://www.rawgraphs.io/) and [GoogleMyMaps](https://www.google.com/maps/d/) would have some useful insights to reveal. This wasn't purely speculation, because I've been using my 2022 data as a sample in one of our prototyping classes, so I know exactly what it looks like when it's loaded into either tool. 

Like many teaching datasets, my animal sightings data is designed to give students ample opportunities to suggest ways that it could be improved; the same features that make the data personal and fun enough that I'm still doing this four years later also mean that there's a lot that could be more rigorously formalized. Typically, students in the class will identify these as the greatest needs for the dataset:
- Much more consistent standardization in the locations and the ways I am identifying the animals, particularly in the wildly varying levels of granularity at stake for both (which, again, is a feature for how I interact with the data, but would very much be a bug if this were something meant to support serious research).  
- Groupings of animal types, to draw out patterns more successfully. I saw 44 different animal types (by my accounting) in 2023 and 45 types in 2022. Those do not color-code in ways that either GoogleMyMaps or RawGraphs can handle. 
- Many more features than would pass the "is it fun?" test. Suggestions have included: genuinely distinctive geo-coordinates for each individual sighting (rather than what I have done, which is to just map each location to the most reasonable lat/long coordinates); time of day for each sighting; relative size of animals sighted; description of any distinctive characteristics of each animal, and so on. 

I can't do anything about items one and three in the list above, but item two is certainly in scope. So, I took a little time over the winter break to create both mid-size and broad categorizations for my animals. The broad ones were: birds, mammals, reptiles/amphibians, and fish/crustaceans. The mid-sized ones were an interesting challenge where (yet again) I had to think about what levels of specificity and detail were authentic to my uses for this data. This is what I came up with:
- Raptors (such as eagles, vultures, hawks, and owls)
- Passerines (songbirds, such as baltimore orioles, cedar waxwings, and goldfinches)
- Wading birds (egrets, herons, cranes, ibises, spoonbills)
- Galliformes (just turkeys so far, though I know there are quail that visit my father's yard)
- Woodpeckers (so far, these are downy, hairy, pileated, and red-bellied woodpeckers, plus flickers) 
- Water birds (I am not in love with this category, but so far it is how I'm lumping together ducks, geese, loons, pelicans, and swans)
- Cervids (just deer for now, but you never know when you might see a moose) 
- Canines (coyotes, foxes) 
- Musteloids (fisher cats, otters, skunks, raccoons)
- Rodents (beavers, flying squirrels, muskrats, prairie dogs)
- Marsupials (opossums) 
- Lagomorphs (rabbits)
- Pinnipeds (seals) 
- Cetaceans (whales, dolphins)
- Fish (stingrays; I don't track any other kind of fish so far)
- Reptiles (lizards, various kinds of turtles, snakes)
- Amphibians (toads, frogs)
- Crustaceans (various kinds of crabs)

Some animals are distinctive enough that larger categories won't ever be called for (some of my larger categories are aspirational—I would *really* like to see a walrus someday): hummingbirds, kingfishers, bats, and moles (which, I learned while making these categories, are not rodents). 

So (drumroll), here is what RawGraphs made of my data. To get a sense of just the overall patterns in which kinds of animals I see most often, I tried out the "Circle Packing" chart type. 

Here is the 2022 data: 
![2022 circles]({{ site.baseurl }}/images/2022-circles.png)

And here is 2023: 
![2023 circles]({{ site.baseurl }}/images/2023-circles.png)

For reasons that will become clear in my next post, a straight comparison across years has some limitations, so I don't want to get too caught up in analysis here. I'll just point out that the overall proportions are fairly consistent, and that this gives you a good way to see the "heavy hitters," which really boil down to: herons, turkey vultures, hawks, and rabbits. The high numbers of seals in 2022 are because I walked by several large seal colonies while on Cape Cod that year (keeping a safe distance, of course!). 

This gives you a sense of what kinds of animals I see most often, but it doesn't get at the annual patterns of sightings. To see that, I tried a beeswarm chart. In these, the size of the circles indicate how many animals I saw in each "sighting" and the color-coding is based on the broad animal types:
- orange = mammals
- blue = birds
- green = reptiles and amphibians
- red = fish and crustaceans 

Here is 2022:
![2022 beeswarm]({{ site.baseurl }}/images/2022-beeswarm.png)

And here is 2023:
![2023 beeswarm]({{ site.baseurl }}/images/2023-beeswarm.png)

These really make the peaks in animal activity during late spring and summer very visible. They also show some of the places where I spotted large numbers of animals at once, especially in 2022, where you can see those large seal colonies in August, and then a lot of ibises I saw along the Nile in November. In both years, you can see large numbers of turtles in April and May. 2023 also had some really outrageous numbers of rabbits I saw in a few walks in the later summer. 

I enjoyed making these charts, but what I learned most from them was that, if I was going to get at that goal of comparing data from one year to another, I would need a different approach. The ibises I saw on the Nile are the most obvious symptom of this issue—in fall of 2022, I was lucky enough to travel with my husband's family to Egypt, and I saw So Many Ibises. This was exciting, of course, but produced some misleading results in the data, especially since I barely left New England in 2023. I'll get to how I chose to handle this question in the next post, though, since this one is already more than long enough! 
