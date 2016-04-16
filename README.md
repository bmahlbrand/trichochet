# trichochet
richochet 

#To do

----------


##Jacob 
1. Enable Pause + logic
2. Enable Restart Game
3. Fix Scoreboard/ level Timer (move vars to gamemode, and spawn two instances, one for each player?)
4. Create end game logic


##Ben
1. Create Six Flying Minions, assign abilities and appropriate resource cost
2. Create Resource Counter to Summon
3. Create Minion Menu to Select 2
4. Enable Player to spawn Chosen Minions


##To Do
1.	Improve Disk Physics
2.	Fix on round restart, character still has the physics movement from before and may fall consequtivally
3.	When timer ends, End Game
4.	Add delay to round restart/start(disable firing guns while falling)
5.	Menu for Music/Disk Color
6.	Clean up arena environment
7.	Fix scoreboard fonts


##Future
1.  Change disk throw velocity on mouse charge


##To Run
start command prompt from<br><br>
C:\Program Files (x86)\Epic Games\4.10\Engine\Binaries\Win64
RUN
UE4Editor-Cmd "PATH TO Project file" -server -log<br><br>
UE4Editor-Cmd "C:\Git\VR\goodTR\tr.uproject" -server -log

RUN TWO CLIENTS<br>
navigate to where you packaged<br>
run<br>
tr.exe IPADDRESSGOESHERE -game
