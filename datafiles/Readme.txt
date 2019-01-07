-----------------------------------------
Guerra [Spanish for WAR] README
-----------------------------------------
v 0.01

---------------------
MAIN OBJECTIVES
---------------------
Draw a map.
Starting from your flag, get to the opponents flag first.

------------
TUTORIAL
------------
1. Draw a line of Barbwire.
	You must press left mouse button and drag your mouse to draw barbwire fencing.

2. Select Mine.
	You must press and release mouse button on the Mine Button.
	
3. Place several Mines.
	You must press mouse button to place mine. Dragging your mouse while button is down will move the mine. Release to place.

4. Place a Gun with several bullets.
	You must press mouse button to place gun. Dragging the mouse while button is down will draw bullets towards the cursor. Release to place.

5. Place a Flag
	You must press mouse button to place a flag. Dragging your mouse while button is down will move the flag. Release to place. Only 1 flag can be placed.

6. Finish the map.
	To ensure there is a path to the end, a path must be drawn from the flag to the bridge at the bottom of the map. Press mouse button on cursor near flag.
	Dragging will start to draw a path. Draw a path to the bridge without hitting any obstacles. Hitting obstacles will restart you at the flag.

7. Play your first round.
	Now that you are finished with the map, let's see if you can get to the bridge via normal play. As the previous step you must press mouse button on cursor.
	This time, you will notice the screen has gone black. With the best of your ability and memory, draw a path to the bridge. If you hit an obstacle, you will be
	moved back a certain number of pixels depending what kind of obstacle you have hit.  Once you have reached the bridge, you have finished the tutorial!

----------------------
PLAYER VS PLAYER
----------------------

1. Player 1 will have to draw a map  (as indicated in Tutorial steps 1-6, but not necessarily that order). 
2. Upon finishing, Player 2 will have to draw a map.
3. Player 1 starts moving from Player 1's flag to Player 2's flag without sight (like Tutorial step 7). Upon collision, it will be Player 2's turn.
4. Player 2 start moving from Player 2's flag to Player 1's flag without sight. Upon collision, it will be Player 1's turn.
5. Player 1 will start a certain amount of pixels from last collision, depending on object. Player 1 will continue to proceed to Player 2's flag. Upon collision, it will be Player 2's turn.
6. Player 2 will start a certain amount of pixels from last collision, depending on object. Player 2 will continue to proceed to Player 1's flag. Upon collision, it will be Player 1's turn.

7. Steps 5 and 6 will be repeated until a player reaches the opponent's flag. First player to reach the opponent's flag is the victor.

-------------------
RELEASE NOTES
-------------------

Game is intended to be played with Mouse or Touch Screen.

Alt + Enter -- Toggles Fullscreen

------
v0.01 
------
- Missing Tutorial Step #7
- Missing Player vs Player Steps #2-7

- I've caught a cold Saturday morning, and it's been a hard journey getting this far. I'll try to have a playable game (v0.02) by class time Tuesday (9/30/2014).
- Thanks and sorry!