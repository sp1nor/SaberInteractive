## Title: Program does not run without audio devices
## Product: [kkrieger demo]
## Version: [unknown]

## Operating System: [Windows 11 version 21H2]

## Description: 
The program fails to launch if no audio devices are connected to the computer. Without following message program freezes and becomes unresponsive.

## Expected Results: 
The program should run without any audio devices connected.

## Actual Results: 
The program does not start without any audio devices connected or devices turned off in windows Device Manager.

## Steps to Reproduce:

* Turned off in Windows Device Manager all audio devices from the computer
* Launch the program
* Observe freezes and becomes unresponsive.

## Additional Information: 
The program requires audio devices to be connected, even if the program does not have any audio-related features.

## Priority: 
High

-----------

## Title: Player gets stuck in door textures
## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]

## Description
In the game, when an Player collides with the door, it sometimes gets stuck in the door textures and cannot be moved.

## Expected Results
Players should collide with the door, but not get stuck in the textures.

## Actual Results
Players collide with the door and get stuck in the textures, making them unable to be moved.

## Steps to Reproduce
* Launch the game
* Move an Player towards a open door
* Allow the Player to collide with the door
* Observe the Player getting stuck in the door textures

## Additional Information
This issue occurs with various types of Players, and does not seem to be related to the size or weight of the Player.
The issue occurs more frequently with certain types of doors or in certain areas of the game.
## Priority 
Medium

-------------------

## Title: Object gets stuck in door textures
## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]

## Description
In the game, when an object collides with the door, it sometimes gets stuck in the door textures and cannot be moved.

## Expected Results
Objects should collide with the door, but not get stuck in the textures.

## Actual Results
Objects collide with the door and get stuck in the textures, making them unable to be moved.

## Steps to Reproduce
* Launch the game
* Move an object towards a closed door
* Allow the object to collide with the door
* Observe the object getting stuck in the door textures

## Screenshots

![spider in a door](/images/spider_In_Door.jpg "spider in a door")

## Additional Information
This issue occurs with various types of objects, and does not seem to be related to the size or weight of the object.
The issue occurs more frequently with certain types of doors or in certain areas of the game.

## Priority
Medium

-------------------------

## Bug Report: Program freezes and becomes unresponsive when switching with Alt+Tab
## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]

## Description
When switching to another program using the Alt+Tab keyboard shortcut, the program freezes and becomes unresponsive, requiring the user to force quit the program.

## Expected Results
The program should be able to switch to another program using the Alt+Tab keyboard shortcut without freezing or becoming unresponsive.

## Actual Results
The program freezes and becomes unresponsive when switching to another program using the Alt+Tab keyboard shortcut.

## Steps to Reproduce
* Launch the program
* Open another program, such as a web browser or a text editor
* Use the Alt+Tab keyboard shortcut to switch back to the program
* Observe the program freezing and becoming unresponsive

## Additional Information
This issue occurs consistently and has been observed by multiple users.
The program may also freeze and become unresponsive when switching to another program using other keyboard shortcuts or methods, such as clicking on the program icon in the taskbar.

## Priority
High

-----------------

## Bug Report: Mouse cursor freezes in one position and does not move when switching programs with Alt+Tab
## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]

## Description
When switching to another program using the Alt+Tab keyboard shortcut, the mouse cursor freezes in one position and does not move when trying to move it to another coordinate on the screen.

## Expected Results
The mouse cursor should move freely and respond to user input when switching to another program using the Alt+Tab keyboard shortcut.

## Actual Results
The mouse cursor freezes in one position and does not move when trying to move it to another coordinate on the screen.

## Steps to Reproduce
* Launch the program
* Open another program, such as a web browser or a text editor
* Use the Alt+Tab keyboard shortcut to switch back to the program
* Try to move the mouse cursor to another position on the screen
* Observe the mouse cursor freezing in one position and not responding to user input
Screenshots/Videos
[If possible, include screenshots or videos to help illustrate the issue]

## Additional Information
This issue occurs consistently and has been observed by multiple users.
The issue may be resolved by restarting the program or the operating system.

## Priority
High

--------------

## Bug Report: Enemy unit not active after spawning, not attacking, and not moving
## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]
## Description

After an enemy unit spawns, it remains inactive, not attacking or moving towards the player's character.
## Expected Results

Enemy units should become active upon spawning, moving and attacking the player's character as intended.
## Actual Results

Enemy units remain inactive and do not attack or move towards the player's character.
## Steps to Reproduce
* Launch the game
* Begin a level or encounter where enemy units are spawned
* Observe the behavior of the spawned enemy unit
* Note that it remains inactive and does not attack or move towards the player's character

## Additional Information

This issue occurs consistently and has been observed by multiple users.
It is unclear whether the issue affects all types of enemy units or only specific ones.
The issue may be related to the spawning mechanism of the enemy units.

## Priority

High

-------------

## Bug Report: Enemy unit moves in the air after spawning

## Product: [kkrieger demo]
## Version: [unknown]
## Operating System: [Windows 11 version 21H2]
## Description

After an enemy unit spawns, it moves in the air instead of on the ground or intended path.
## Expected Results

Enemy units should move on the ground or on their intended path upon spawning, and not move in the air.
## Actual Results

Enemy units move in the air after spawning.

## Steps to Reproduce

*Launch the game
*Begin a level or encounter where enemy units are spawned
*Observe the behavior of the spawned enemy unit
* Note that it moves in the air instead of on the ground or intended path

## Screenshots/Videos

![enemy in air](/images/bug_enemy_in_air.jpg "enemy in air")

## Additional Information

This issue occurs consistently and has been observed by multiple users.
It is unclear whether the issue affects all types of enemy units or only specific ones.
The issue may be related to the collision detection or pathfinding mechanism of the enemy units.

## Priority

Medium