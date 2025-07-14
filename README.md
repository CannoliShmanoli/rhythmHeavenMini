# rhythmHeavenMini
Rhythm Heaven Mini is a scratch project that aims to recreate tickflow, but in a much easier way to read, write, and play.
It also supports custom games, and custom builds.




+---------+
|  Guide  |
+---------+

Common
—------------
rest (beats)
gameChange (gameID)
playSound (soundName)
endGame


Karate Man (AGBkarate)
—-----------
Cues:
obj (objID)
(more will be here later….)

Template (AGBtemplate)
—-----------
(none so far)

For custom games, to add custom cues, that don't just broadcast the cue name in the minitickflow list, 
Step 1: Go to the listcontroller object.
Step 2: Go to the "define parse event" block
Step 3: Add "if (item (1) of (splitstroutput) = [cue name] then"
Step 4: Add the code you want it to run
Step 5 (Optional): For adding other things to the cue, add "if (item (2) of (splitstroutput) = [other] then" inside of it.


+------+
| Help |
+------+

WARNING: If you try to run a remix with custom games, please make sure to have the build of the custom remix. If not, the game will spit out a NG screen.
(NG screen = a grey screen saying "No Game/Bad Build")


Happy Making!
