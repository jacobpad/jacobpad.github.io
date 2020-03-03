<h1>This is my Unit 2 project - NBA Salaries Predictions</h1>

<h3>Intro</h3>
<p>I was able to obtain some stats from 
<a href='https://stats.nba.com/players/traditional/?PerMode=Totals&dir=-1&sort=PTS&Season=2019-20&SeasonType=Regular%20Season'>
NBA.com</a>, and the salaries from <a href='http://www.espn.com/nba/salaries'>ESPN.com</a> (which I scraped the data). I 
combined the two peices of data together, which gave me a set of all players in the National Basketball Association, from 
every team, all 30 teams.</p>

<h3>Target</h3>
<p>I wanted to be able to predict how much an incoming player may earn (in USD) if the player could provide a certain benefit 
to the franchise by giving the stats they would average.</p>

<h3>Evaluation Metric</h3>
<p>I'm going with Linear Regression for this. I'm managed to fit a model with a single feature of points. In other words, 
it basically takes the average of the data I'm starting my work with and figures out how much each point is worth. So, 
an incomming player can assume that for every single point they score, based on scoring alone, they can expect to average 
around $15,693 per point. So, a player that scores 1,500 points in a season can anticipate somewhere around $24,853,148.
Now, that doesn't add up right. $15,693 multiplied by 1,500 points is $23,539,500. That's a difference of $1,313,648. Well, 
I move on, it'll get more accurate, plus, the players need paid something and remember, we did only the stat of how many 
points one would make during a season.
</p>

<h3>Moving On</h3>
<p>As I move on toward my goal of trying to predict the salary of an incoming player, one thing important to do is to know 
which stats are more important than others. I figured off the top of my head, and throughout my years of playing basketball 
myself, that the number of points a player could make would be the leading factor in how much money they would earn as a 
professional athlete. I was surprised when I ran the bit of code that generated the following picture and proved me wrong. 
As we can see, there are many other stats that are more important than points, including... now this really threw me off, 
the number of losses a player has. 
</p>

<p>
Field Goals Attempted  <br>
Free Throw Percentage  <br>
Defensive Rebounds <br>
Minutes Played  <br>
Total Rebounds  <br>
Personal Fouls  <br>
Three Points Made  <br>
Three Point Average  <br>
Losses  <br>
Block Shots <br> 
Offensive Rebounds  <br>
Points Scored  <br>
Wins  <br>
Field Goal Percentage <br>
Free Throws Made  <br>
Turnovers <br>
Free Throws Attempted <br>
Steals  <br>
Field Goals Made <br><br>
...and it keeps going.</p>

<span>
<img src="https://github.com/jacobpad/jacobpad.github.io/blob/master/data/top_20_nba_stats.png?raw=true", alt="Top 20 Stats Ranked In Order"
</span>

