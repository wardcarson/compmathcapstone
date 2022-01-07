# Using Python to predict NFL Player Statistics
Capstone project for MAD2502 Intro to Computational Math'

Group members: Carson Ward, Jorge Sempere

# Topic:
	
Statistics of all types have always been fascinating, and naturally watching sports, that is no different. For this project, we wanted to do a deep dive on the statistics on NFL players. Specifically, we wanted to try to be able to predict the career trajectory of a player based on maybe one- or two-years’ worth of stats they compile within the NFL. Obviously, this isn’t going to be a perfect model as stats alone do not explain a given NFL player’s situation within the league, but the stats will give a pretty good indicator of how long their career will last. We have a couple different ideas We’d like to explore, including being able to predict if the player will be replaced based upon their stats in comparison to league averages, and if they may become one of the all-time greats based upon comparison to players already holding those titles. Ideally, this will entail an entire career simulation, as long as it may last based upon how they perform, which will be based upon the stats that were entered by the user. The length of their career would be determined by a formula for which we haven’t determined yet as we need to look into trends for NFL stats, that will simulate their stats year by year, and they will keep playing until one of a couple things happen. The first of these would be that they are at a point where they are deemed replaceable, which would be that their stats are noticeably worse than the league average (possibly determined by standard deviations, or a percentage threshold). The second would be the chance they retire, which would increase as they get older and older until they reach a point where they are forced to retire. This would allow one or two seasons worth of stats to be approximated for an entire career, which could be used to predict future players careers, or even compare the stats of players who have played an entire career to our simulation.

# Programming/Mathematical Concepts:

In order to accomplish the goals of this project, We will need to be able to compile and manipulate large sets of statistics from online sports websites such as Pro Football Reference using Numpy, Matplotlib, and BeautifulSoup. We found a guide online that will ease the difficulty of accessing these statistics and being able to use them for this project. Essentially, the user will pick a position (most likely limited to offense, as stats are more telling on the offensive side) and enter some statistics for a given number of years, and the program will compare them to other players and spit out how the career should go. One goal is  to be able to implement some randomization to it so that it doesn’t yield the same results repeatedly. Another would be to be able to provide a list of players they are similar to and provide a % match to these players based upon how their stats compare.





# Division of Labor:

For this project, we will both attempt to have an even share of the work, which will be accomplished by working on bigger portions together and dividing up the smaller tasks to be more efficient. 

# Outside Sources:

We plan to use various NFL statistics websites, along with a guide for importing these statistics into python for use in the project. Pro Football Reference is a database for all things NFL, which has a rather large amount of these statistics characterized by year, position, team, etc.
As well as this, any documentation on ways to provide variation to an approximation would be beneficial to our project.
•	Guide for compiling these stats
•	Example of a PFR page
	

# Biggest Hurdle:

Currently, the biggest hurdle will be figuring out how to add some sort of variation to the simulations. It will be possible, but we will have to look into how to accomplish in a way that would somewhat accurately reflect real life, while doing so inside of python.


