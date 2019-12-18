---
layout: post
title:  "Finally doing some research / exploration"
date:   2019-12-18 10:00:00
author: Petra
categories: Research
---

Hello, fellow epigraphers!

I am have finally got a little time to play with digital datasets and try some of the visualisations. I am hoping to make more detailed post on the technology behind the lovely maps but in short version:

1. We are using dataset from the Epigraphic Database Heidelberg, hencefort known as EDH, as our core dataset (for testing and scoping).
2. We have decided to use EDH mostly because it has clearly stated licence and it has provided an API to access the data.
3. We are using custom made scipts in Python via Google Colab to access the API, download the data (Thanks to hard work of my colleague Vojtech Kase)
4. We are using additional custom Python scripts to interrogate the data based on the current research questions, such as in my case were the milestones.

*My aim was to access the information about all milestones in the EDH database, plot them on the map with relation to the known Roman roads as published and digitized by the Barington Atlas (BA).*

I was puzzled by the following questions for a long time and hopefully I am now closer to finding a satisfactory answer to them.

* Were the milestones placed mostly around major roads?
* Were the milestones distributed equally through space and time?
* Does the language of a milestone change from Latin to Greek as we progress eastward?
* Where were the most milestones placed at - the liminal provinces where the army was constanly on the move, or rather more central provinces where the roads were used mostly by non-military inhabitants?
* Does the time where most milestones where created corresponds with periods of military unrest, building activities, or periods of peace?

Of course the answer depends on the nature of the dataset (EDH), but I am hoping we would be able to get our hands on more datasets to enrich the credibility of the answer. The more data, the more credible image of the ancient historical reality (one would hope).

Here is a simple visualisation of the dataset made Carto.com. Feel free to play with the data, ask me questions. Or reuse (under the CC Attribution-NonCommercial-ShareAlike 4.0 International license).

<iframe width="100%" height="520" frameborder="0" src="https://petrajanouchova.carto.com/builder/e6536d2c-bfee-4eeb-9fcb-7de39bbf1265/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen>


