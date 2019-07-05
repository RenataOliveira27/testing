
                                     _____ __        __       ____             __  
                                    / ___// /_____ _/ /______/ __ \____ ______/ /_ 
                                    \__ \/ __/ __ `/ __/ ___/ / / / __ `/ ___/ __ \
                                   ___/ / /_/ /_/ / /_(__  ) /_/ / /_/ (__  ) / / /
                                  /____/\__/\__,_/\__/____/_____/\__,_/____/_/ /_/ 


                                    
Full stack web application using JavaScript, Node, SQL, axios, ajax, to provide in depth player statistics for all your favorite sports players and teams.

#origin and future aims of our database
we utilized a sports stats API for the purpose of building a baseline of historical stats. For the future we will be integrating custom sets of stats which will give users acess to even more interesting and usefull stats not readily available. Stats such as "What is Steph Currys shooting percentage with 2 minutes or less left in the fourth quarter".

# building our database

We were presented with a unique challenge with the API we chose. We were limitied to 1000 API calls/month at a rate of 1 call per second. Given that there are 536 active players in the NBA it was a time consuming process to construct this database. We created a complex for loop to search both conferences, the three divisions in each conference, and the five teams in each division.
![imageOfPlayerStatsLogic](https://github.com/po1sigala/images/blob/master/statsDash/playerStatsJS.JPG?raw=true)

We stored every stat associated with the player in our database

[![statsdash](https://img.youtube.com/vi/HbdrZ5W-Ca4/0.jpg)(https://www.youtube.com/watch?v=HbdrZ5W-Ca4)
