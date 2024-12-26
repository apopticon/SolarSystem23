This fork of the excellent SolarSystem23 has two changes.
First is the addition of some delay in the Galaxy TurnAround kicker. If the ball bounces off the switch, it can wind up stuck in the turnaround. Adding a little delay lets the ball settle and (so far) seems to have solved the problem.
Second is the new game code uses the G.I. control to turn off the playfield lights at the beginning of a new ball, and the playfield is dark until the ball passes thru the top lanes. I have disabled that. You can turn it back on by uncommenting those two lines in the code. Search for SetGeneralIllumination(false) and remove the comment. One is in InitNewBall and the other is in ManageGameMode.


# SolarSystem23
All new code for a classic pinball machine. With an Arduino connected to the MPU, this code will run on a Galaxy pinball machine (1980).  
  
## How to build this for your machine  
1) build or buy a board to interface an Arduino MEGA 2560 PRO with the MPU processor socket or J5 connector  
2) get this code, put it in a SolarSystem23 folder  
3) update configuration in RPU_config.h to match your board type  
4) compile/install code on the Arduino MEGA 2560 PRO
  
## More Information  
http://pinballrefresh.com  


## Example WAV Trigger Files
https://drive.google.com/file/d/1FlPcCNtWVUEnNESh3lf867T1IfVJk6ec/view?usp=sharing   

  
## Test / Audit / Settings from coin-door switch  
Tests (test number shown in Credits, Ball in Play is blank)  
1 - Lamps  
2 - Displays  
3 - Solenoids  
4 - Switches  
5 - Sounds (not applicable)  
  
Settings & Audits (page number shown in Ball in Play, Credits is blank)  
1 - Award Score 1  
2 - Award Score 2  
3 - Award Score 3  
4 - High Score  
5 - Credits  
6 - Total Plays  
7 - Total Replays  
8 - High Score Beat  
9 - Chute 2 Coins  
10 - Chute 1 Coins  
11 - Chute 3 Coins  
12 - Reboot (All displays show 8007 (as in "BOOT"), and Credit/Reset button restarts)  
13 - Coins per Credit for Chute 1  
14 - Coins per Credit for Chute 2  
15 - Coins per Credit for Chute 3  
16 - Free Play  
17 - Ball Save  
18 - Sound Selector  
19 - Music Volume  
20 - Sound Effects Volume  
21 - Callouts Volume  
22 - Tournament Scoring  
23 - Tilt Warnings  
24 - Award Scores (0 = all extra balls, 7 = all specals)  
25 - Number of Balls Per Game  
26 - Scrolling Scores  
27 - Extra Ball Award (for tournament scoring)  
28 - Special Award (for tournament scoring)  
29 - Dim level  
30 - Extra Ball Rank  
31 - Special Rank  
32 - Sun Mission Rank  
33 - Side Quest Start  
34 - GALAXY Ball Save  
35 - Save Progress  

  
