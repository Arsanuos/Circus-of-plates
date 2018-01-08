# Circus-of-plates
* It is two player-game in which each clown carry two stacks of plates, and there are a set of colored plates
queues that end up falling down.
* The user gets a point when he collects three consecutive shapes from the same
color (even if they are different shapes). 

# Design patterns used
This assignment mainly tackles the application of what you studied in the course
of design patterns.
the used design patterns:
1) Singleton : to create the game objects once.
2) Factory : to create diffrent types of plates.
3) Iterator : to iterate over the list of create plates.
4) Dynamic Linkage : to load plates on run time.
5) Snapshot : to take a shot of the current state of the game to be able to store(save) it in file.
6) State : to implement different states in the game (win state, pause state, ...)
7) Strategy : to implement different difficulty modes in the game.
8) Observer : to observe the players and count score.
9) MVC : for better structure of the code for reusablity.
10) Object Pool : to create limited numbers of objects at the begining of the execution the use them later.
