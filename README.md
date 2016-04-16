# trichochet
richochet 

#To do

----------


##Jacob 
1. Disallow firing in start area
2. Clean up textures, lighting, area, etc
3. Add end logic for round timer expiring(what to do??)
4. Call restart game when 10 rounds are over
5. Add delay when starting game/new round
6. Add Billboard to each player to display messages instead of print string (New ROund, Scored Point, etc)
4. Add rules to start arena


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


##todo
1. Fix on round restart, character still has the physics movement from before and may fall consecutively
1. add fourth music choice
1. add music looping??


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
