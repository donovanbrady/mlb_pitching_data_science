# mlb_pitching_data_science
This is the final project for a data science course that I took back in the late fall of 2021. 

The goal was to use machine learning algorithms to predict how successful a major league pitcher would perform. Essentially, I wanted to see if machine learning could make baseball scouts look irrelevant. Therefore, I focused on data that involved the pitchers innate skills rather than their historical performance against hitters. This is because I did not want whoever was at bat to influence the pitcher data. 

The goal was to see if I could take information, such as how fast a pitcher throws, how much does their pitch spin, or how accurate they can throw, to see if I can make some guess as to whether or not a pitcher will generate wins for thier team. 

The project had mixed results, mostly due to the fact that it is uncertain how to measure how "accurate" a pitcher throws. Also, there is a TON of different measures on a pitcher, which means maybe I didn't consider something (possibly how much movement the ball has in the x or y plane?). Regardless, the goal was to apply algorithms such as linear regression and random forest to try to make a more educated guess. My hope was that I could apply the most accurate model to mlb prospect data, and then make predictions of who is going to be successful or not. However, data on minor league pitchers is not as extensive as major league pitchers. 

If I had to do this again, I would probably not put as many artificial constraints on the problem as I did, possibly accounting for pitcher vs. batter statistics as well. The reason I put this constraints on myself is because scouts often have to make judgements on pitchers who have never faced top-tier talent. Therefore, if I were to use a prospects "performance" data and compare it to the "performance" of pitchers in the major league, then there would be a disparity between the two simply due to the difference in difficulty. Oh well. I had fun.
