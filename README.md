# NBA Three Point Revolution

# Motivation & Introduction
There are numerous reports and studies done about how the NBA has transformed in the past 5 years in regards to the 3-pt shot. The 3-pointer started to become dominant and popular in the NBA following the success of Stephen Curry and his Golden State Warriors (2015, 2017, & 2018 NBA Champions). Here are some great videos and articles about the **"Three Point Revolution"**:

-https://www.nytimes.com/2016/01/21/sports/basketball/how-the-nba-3-point-shot-went-from-gimmick-to-game-changer.html

-How Data Changed the NBA by The Economist (Houston Rockets & Second Spectrum): https://www.youtube.com/watch?v=oUvvfHkXyOA&ab_channel=TheEconomist

-https://fivethirtyeight.com/features/how-mapping-shots-in-the-nba-changed-it-forever/

-https://fivethirtyeight.com/features/basketballs-other-3-point-revolution/

-https://fivethirtyeight.com/features/stephen-curry-is-the-revolution/

-As discussed in the resources above, Data Science & Analytics made coaches, players, and team executives comfortable with adopting the 3-pointer. **Now, we will use Data Science to test if those decisions paid off and are responsible for more wins.**

-In this study, I will **calculate and compare the predictive power of 3-pointer-related Season Average Player Statistics (3PFG%, 3PFGA, etc) in predicting NBA Regular Season team win-pct** in different eras of the 21st century.

-The four eras will be 2000-2004, 2005-2009, 2010-2014, and 2015-2019.

-I will only use data from players that are "Starters" because they have outsized impact on their team's Win% and are enabled to take a wider array of shots. I define a "Starter" as a player that starts >= 50% of games in a season for their team, which is the same way that the NBA defines "Starter" when determining who is a non-"Starter" to award the 6th Man of the Year award.

# My Questions/Hypotheses
-Confirm the narrative: are players actually attempting more 3-pointers as time goes on? (a Simple Linear Regression: 3FieldGoalAttempted ~ Year)

-Are players becoming more efficient 3-point shooters as time goes on as a by-product of the global increase in 3-pointers attempted? (a Simple Linear Regression: 3FieldGoal% ~ Year) My rationale for this is that efficient 3-point shooting has likely gotten more valuable to teams due to my first hypothesis about more 3-pointers being attempted overall, meaning teams will opt to choose players with higher 3-point efficiency over time as their Starters.

-I hypothesize that **3-pt player stats (3-pointers attempted, 3-pointer efficiency, etc) will be statistically significant** even when considering all of the other box score player stats **for ALL 4 eras.** (a Multiple Linear Regression: Win%~All Player Stats)

-Primarily, I am interested to see whether the predictive power of 3pt player stats starts to **OUTWEIGH and DOMINATE** the other player stats traditionally regarded as having the most predictive power (FG%, TREB, AST, etc) as time goes on.
