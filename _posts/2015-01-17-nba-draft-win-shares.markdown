---
title: NBA Teams' Draft Prowess from 2003-2012
layout: post
---
{{ page.date | date:"%-d %B %Y" }}

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

##### Total Win Shares
Here are the top teams in terms of the total win shares earned by all of their draft picks (with their average 1st rd draft position in parentheses).

1 - CHI (14)
2 - OKC (14.2)
3 - CLE (15)
4 - NOK (14.2)
5 - POR (16.9)
6 - UTA (14.9)
7 - **BOS (21.8)**

Here are the worst teams:

26 - HOU (20)
27 - WAS (14.5)
28 - SAS (24.9)
29 - PHO (17.4)
30 - DAL (22.6)

From this metric, Danny Ainge has done a pretty good job finding value and good pros relative to his overall draft position. The teams ahead of Boston in terms of win shares have a few things in common. They’ve been in the lottery a couple times in this time span (UTA, POR, OKC etc.) or they’ve had the good fortune of landing a top pick when a superstar could be had: CHI (Derrick Rose), OKC (Kevin Durant, James Harden), CLE (Lebron James), NOK (Anthony Davis).

Boston on the other hand, only picked in the lottery once in this time span (Marcus Banks in 2013), and on average had the 3rd worst drafting position on average (around the 22nd pick in the 1st round). A good comparison is Dallas, who had the worst total win shares from their draft picks, but also picked lower in the draft (pick 23).

The group of players Ainge has picked in his drafts have carved out roles and contributed to teams in their careers. I’d argue that this is a good accomplishment given they were usually picked later in the draft.

##### Win Shares per Player
Merely adding up all the win shares of all draft picks would skew the numbers to benefit teams who had more draft picks, and thus more players in the pool. Boston had the 3rd most draft picks in this time range, so Ainge picked more players than most other teams.

To work around this issue, I also calculated the average win share per player (WS/P) as a metric of an average “quality” of a given draft pick for each team. This metric would benefit teams who “hit” more often on quality players and penalize teams who had a lot of draft picks.

The numbers play out differently when looking at average quality. Here are the top teams in terms of WS/P (with avg. draft position in parentheses):

1 - CHI 18.85 (14)
2 - CLE 18.81 (15)
3 - NOK 17.57 (14.2)
4 - PHI 15.07 (16.6)
5 - OKC 14.53 (14.2)

…

14 - **BOS 11.68 (21.8)**

So we see here that Boston is about middle of the pack in terms of the average quality of their players drafted. This is not surprising given that they had so many draft picks. They probably hit on some picks and missed on many of other picks, just like any team, which brings their averages down.

Still, given Boston’s draft position, it appears that at least on average Danny Ainge is finding quality value and good pros.

The following graphic illustrates this point a bit better:

![win shares by position](/../images/winshares.png "win shares by position")

The first thing to notice is to look at teams within “bands”. Look at the vertical axis (y) between 20-25. All the teams in this band on average picked between the 20-25th picks in the 1st round: Dallas, LA-Lakers, Houston, San Antonio, and Boston. Of this group, Boston had the highest win shares per player - meaning Danny Ainge had the most success picking quality pros in this portion of the draft.

You can also glean a lot of information about team building and the draft just from this graph. Notice the teams on the far right: New Orleans, Cleveland, Chicago. They all had high quality average win shares per pick. They also all benefitted from lucking into #1 picks with stars like Lebron, Anthony Davis, and Derrick Rose.

NOK is notable in that they did well with some late 1st rounders (David West) and 2nd rounders (Brandon Bass). Chicago did well with other picks such as Omer Asik, Jimmy Butler, Taj Gibson, Thabo Sefalosha, Ben Gordon, Matt Bonner, Kirk Hinrich, Joaquim Noah and Luol Deng. I’d say Chicago was pretty damn good with their picks, getting several pros while also luckily getting Derrick Rose to lead them.

Notice the group in the band between the 5-10th picks. These teams appear to be perpetually in the lottery, but consistently did not draft well: Minnesota, LA-Clippers, Milwaukee, Charlotte, and Toronto. They drafted some pretty good players, but let’s look at this in terms of value.

Danny Ainge’s picks averaged 11.68 win shares while drafting in the late 1st round. Milwaukee and Charlotte’s players averaged around 11.3 win shares while they consistently picked in the lottery.

This graph is quite fascinating to me, and I’ll try to share some more insights from it in future posts.

But for today, I think we can safely say that Danny Ainge has gotten pretty good value in his draft picks between 2003-2012. His past performance will definitely not predict what he does with his draft haul in the next few years, but I have some confidence he’ll find some valuable contributors.

However, this graph also shows that to become an contender, you need to find those one or two star players (either in the draft or free agency) to lead a collection of solid pros, that come together as a team. The best drafting teams in this analysis had the benefit of getting a Lebron or Anthony Davis to skew their numbers up.

Other notable teams are Boston (who traded all that value they got in the draft to get Kevin Garnett and Ray Allen, then rode them and Paul Pierce for a championship) and Miami (who infamously got Lebron and Chris Bosh as free agents to join Dwayne Wade).

Thanks for reading this inaugural post!