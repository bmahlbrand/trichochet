# trichochet
2 Player Networked Multiplayer Game

Choose from 3 Classes!

Offensive:
1. Blind
2. Summon disc throwing minion

Defensive:
1. Shield
2. Wall to slow enemy fire

Magical:
1. Sap other player's energy
2. Summon Clone



##To Run Server

Find Path to "UE4Editor-Cmd" depends on installation.  Will be something like:

C:\Program Files (x86)\Epic Games\4.10\Engine\Binaries\Win64
OR
C:\Program Files\Unreal\4.10\Engine\Binaries\Win64

RUN
UE4Editor-Cmd "PATH TO Project file" -server -log<br><br>
UE4Editor-Cmd "C:\Git\VR\goodTR\tr.uproject" -server -log

This will start the server

##To connect with clients
tr.exe IPADDRESSOFSERVERGOESHERE -game

##To use VR
Press alt-enter after starting the game
