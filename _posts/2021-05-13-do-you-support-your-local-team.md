---
layout: post
title: "Do You Support Your Local Team? I Have Proof."
description: Proving which UK football team you should support with data. 
author: Evan
header-image: local_team_header.jpg
preview-image: local_team_preview.jpg
category: football
---
***THERE IS AN INTERACTIVE VERSION OF ALL OF THE MAPS SHOWN <a href='{{ site.baseurl }}/closest-teams' target = '_blank'>HERE</a>***

Every now and then in my days supporting and following Cardiff City, we got to play one of the so-called "big clubs", maybe in the FA cup or in the couple of seasons that we spent in the Premier League. One chant was consistent through all of those usually miserable days: "WE SUPPORT OUR LOCAL TEAM!". It's a terrible chant, was the only thing we could possibly have over a "big" club a weak moral high-ground? And I often thought, was it even true? Surely a lot of the accents around me belonged to people who lived slightly closer to Newport? Obviously, if we took into account all the football clubs in the UK, almost no-one would support their local team and there would be a lot more fans of Hampton & Richmond Borough, Slough Town, or Swansea City, for example. 

Well, I've set out to see if everyone in the UK **had** to support their "local team", who would they support? I've looked at 104 in the UK, the 92 teams from the EFL and the Premier League, as well as the 12 teams of the Scottish Premiership. Using a series of maps and a visualisation technique called a <a href = 'https://en.wikipedia.org/wiki/Voronoi_diagram' target = '_blank'>Voronoi Tessellation</a>, I can show the areas that are closest to each club. Most notably, there are no clubs represented in Northern Ireland, and so usually one team takes over the whole country, and only the top 12 clubs in Scotland, meaning that quite large areas will be represented by these sides.

## The Premier League in The UK

Firstly, if everyone in the UK had to support their "local" premier league side, who would they support? 

![UK Local Premier League Sides](/assets/img/premier_league_uk.jpg)*UK's Local Premier League Sides*

For anyone in Northern Ireland, and Ynys Môn, it's got to be Everton for you, and anyone in the **whole** of Scotland has to support Newcastle United. The most widely supported London club would be Tottenham Hotspur, whose influence expands all the way to Norwich and beyond. Southampton do well, covering all of Cornwall and the south west, and Wolves take nearly all of Wales. 

![Manchester Split](/assets/img/manchester_split.jpg)*Manchester Split Down the Middle*

Manchester is split almost perfectly down the middle and the smallest area that a club represents is this one in London belonging to the minnows of Chelsea. 

![Chelsea Surrounded](/assets/img/chelsea_area.jpg)*Chelsea Surrounded*

## Other UK Teams

Now this is a good place to start, but I wanted more depth in my search for the largest local club in the UK (if that makes sense). So, I went for it. I gathered the geographical data for all 72 English Football League clubs and the 12 teams in the Scottish premiership. Take a look (all the colours are the team's colours):

![UK Local Teams](/assets/img/all_clubs_uk.jpg)*UK's Local Teams*

This is a lot to take in, and there is so much to describe that it's best that you take a look yourself. There is an interactive version of all the maps shown plus a few more <a href='{{ site.baseurl }}/closest-teams' target = '_blank'>here</a>. 

So, instead of describing this map I decided to come up with a better measure of representation and produce an *alternative league table* for my big UK Super League (*I wrote this article before the announcement of the European Super League*). I didn't include Northern Ireland in this calculation as I didn't think it was fair. Also, the areas shown in this table may be slightly different to the ones shown on the map and so teams that appear smaller on the map may be bigger in the league table. This is because of the way the areas are projected onto the earth (don't ask - it was a massive headache figuring this out). This is a very large table showing the area that all of the teams above represent, how well does your team do?

{% include local-team-table.html %}

The undisputed champions of this league are the mighty Ross County, probably owing to their control of the entirety of the Highlands and Islands. They not only win this league, but win it by a **HUGE** majority. Their influence expands **over 30,000 KM<sup>2</sup>**, or **~13%** of Great Britain. Interestingly, in this measure, some of the "big clubs" perform poorly - maybe good teams tend to be closer together, and therefore can not represent as large an area as others? Swansea City just nip in to the "Europa League places" in 5<sup>th</sup>, with an unlikely 4<sup>th</sup> place finish from Shrewsbury Town. The Bottom 6 clubs are all in London, owing to the high density of clubs in the capital.

This is obvioulsy a bizarre measure, and just an interesting way of seeing "local teams" in the UK. What would be really interesting is if we could find out the population density within these areas, and therefore find how many **fans** each team would have if everyone in the UK was bound to their "local" club. I could write a whole other article about how I made these graphs, how I find the data, how to project these areas onto the earth, how to calculate the area of the areas shown. It was a minefield. But I hope that the results are interesting.

Explore these maps, there is an interactive version of all the maps shown (plus a few more) <a href='{{ site.baseurl }}/closest-teams' target = '_blank'>here</a>.  