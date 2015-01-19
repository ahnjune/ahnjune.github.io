---
title: NBA Teams' Draft Prowess from 2003-2012
layout: post
---

17 Jan 2015

Several friends of mine recently got into a heated debate concerning the Boston Celtics. Danny Ainge traded away the likes of Rondo, Jeff Green, and Brandon Wright to add to a bevy of draft picks over the next three years. Were the Celtics better off?

My friends were split. Half were dejected by the trades and felt GM Ainge was a terrible drafter (and would waste away these picks). The other half argued Ainge was a pretty good drafter and "In Ainge We Trust".

This got me interested in seeing how Ainge measured up against the rest of the NBA concerning his draft results. 

##### A Quick Analysis
I downloaded the NBA Draft results between the years of 2003-2012 from [basketball-reference.com](http://www.basketball-reference.com/draft/). I did not include the 2013 and 2014 drafts because I felt they were too recent to adequately assess whether the players were quality pros at this point.

The datasets provide the career statistics of each player drafted along with a metric called [Win Shares](http://www.basketball-reference.com/about/ws.html) that attempts to calculate how many team wins a player has contributed to in their career. This analysis will focus on draft picks, draft position, and win shares.

I did a few tweaks that impact how we interpret these results. First, I went through the drafts and tried to account for draft day trades. For example, in 2003 the Celtics and Grizzlies swapped their 1st round picks. In that draft, Troy Bell and Dahntay Jones were attributed to Boston, with Marcus Banks and Kendrick Perkins attributed to Memphis. I swapped those attributions so Boston would be credited with picking Banks/Perkins and vice versa.

Second, I tried to attribute players to the teams who wanted and thus were responsible for picking them. Boston effectively chose Banks/Perkins in 2003 (although Memphis made the picks officially). If a player was drafted by a club, spent some time with that club, and then was traded sometime in the future - I still interpret that team as effectively being responsible for the talent evaluation and ultimate choosing the player. 

This analysis is to take a quick look at "drafting prowess" - did teams pick players that ultimately ended up being good pros? (whether they became good pros with the original club is a different question). An example that clarifies this point is Kyle Korver picked with the 51st pick by the New Jersey Nets (now Brooklyn). Korver's gone on to have a great career with several teams, but I credit the Nets with having recognized and drafted him.

After editing the dataset (as best as I could remember, if there are errors I'm happy to make amendments to this post), I did some quick exploratory analysis. In particular, I decided to tally up all the win shares of all players drafted and attribute them to their teams. I also wanted a decent proxy for whether a team was perpetually drafting from a strong position (e.g. in the lottery all the time) and thus would have more chances to pick better players. So I calculated each teams average drafting position in the 1st round over this 10-year period.

These simple statistics start to tell an interesting story.

