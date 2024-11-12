# MVP PRD1
 MVP PRD1 of Shadows Over Suburbia
 **Play::** https://mstrykul1336.github.io/Shadows-Over-Suburbia-MVP-PRD1/
 **Full Project:** https://github.com/mstrykul1336/Shadows-Over-Suburbia-Prototype-

 **11/11/24:**
**What was done:**
- created a how to play screen and added it into the how to play section of the title screen. It is now a graphic with more organized steps should it should be clearer to understand and pick up.

- created a roles and abilities screen and added it into the roles and abilities section of the title screen. It is also now a graphic so it should be easier to understand.

- added the new roles and abilities image to the F1 key too

- added in the ability to have a 3rd person POV camera. You can toggle between 1st POV and 3rd by hitting F3. 

- Added F3 to the final controls image and added that to controls 

- Added new animations of the neighborhood for day and night cycles. 

- For transition to night cycle, the sky box is a night sky. It will switch everyone's cameras to the main camera to play the town animation, with fancy red spot light. 

- For transition to day cycle, the sky box will turn to the day sky. The animation will play again. 

- Timers have been mostly fixed (hopefully). All timers have been changed to use Photon Network time to hopefully keep synchronized. 

- Added a character model select screen! Choose from villager, goblin, elf, witch, citizen or villager (but blue)! Every other player will see the model you chose in game (thanks hashtables).

- Made it so if the player doesn't choose a model, it will default to a goblin (otherwise it crashes).

- Added new background image to lobby screen (it used to be just black). 

- Changed the shopkeepers model from a capsule to one of the villagers (and changed the collider to be bigger)

- Added controls image to settings menu 

- Added in code to make sure the mayor is pointed out with a diamond on the player list 

- Made sure player list looked neat 

- Drew profile picture asset for Mayor 

- Added in code to change your profile picture based on your role (I need to still draw the rest of them, so for now it's demo assets)

- Added in code functionality so that your profile picture displays in the newspaper on death (which will change based on role)

- Added intro music to the lobby screen 

- Added villagers to animation in the title screen 

- Added how to play, controls and roles/abilities instructions to lobby screen while waiting for the host to start the game (requested through a user story)

- **To Do:**
- As a player, I want clearer role instructions in a picture format so I can visualize my abilities and other role’s abilities.  

- As a player, I want to be clearer on how to play instructions in a picture format so I can visualize and comprehend the game mechanics easier.  

- As a visual player, I want animations between night and day cycles so that the game has more dramatic elements and worldbuilding. 

- As a visual player, I want the player profile pictures so that I know what character I am visually.  

- As a player, I want the timers to sync properly so I can play the game synchronized with other players.  

- As a player. I want the option to change the camera point of view from first person to third person so that I don’t get dizzy or sick from the camera controls.  

- User Stories 2: 

- As someone who enjoys deduction games, I would like a brief explanation of rules and controls before the gameplay starts, possibly on the game room waiting screen, so people can understand the game better while playing. 

- User Stories 3:  

- As a new player, I would like a ui text telling me the controls, especially for player abilities. 

- As a player, I want to see more worldbuilding in the game so that I can be more immersed in the game.  

- As a player who likes story and characters, I would like to see character models for the players 
