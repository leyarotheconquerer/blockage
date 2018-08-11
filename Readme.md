Blockage
========

A game about moving blocks to reach the exit.

Concept
-------

### Goal
* You are trying to reach the exit of each room.

### Player Actions
* You can pick up any number of blocks, as long as they are the same color
* You can only pick up blocks nearby (probably no more than 3 blocks distant)
* You can drop blocks one at a time in a location of your choosing (probably no more than 3 blocks distant)
* You can walk on dropped blocks
* You can jump on top of dropped blocks

### Room Mechanisms
* Picking up all blocks of a given color may activate some mechanism
* The door is activated by a certain color in each room
* A bridge may be activated by a different color in each room
* Mechanisms indicate which color is needed to activate them

### Colors
* There are four colors
	- Green (#71E411, rgb(113, 228, 17))
	- Blue (#1476A5, rgb(20, 118, 165))
	- Red (#E51252, rgb(229, 18, 82))
	- Orange (#FF9113, rgb(255, 145, 19))
* Primarily, the level will be grey except for the blocks
	- Light gray (#AAAAAA, rgb(170, 170, 170))
	- Dark gray (#585858, rgb(88, 88, 88))

Level List
----------

* Intro level - simple three or four blocks of different colors on floor
* Secondary Intro level - change colors to introduce inventory mechanics maybe add some more blocks
* First level - blocked door with other color, drop own and pick up others
* Second level - chasm, fill with inventory, pick up others
* Third level - build stairs with inventory, pick up others
* Fourth level - not enough room for all inventory, so place down hole and pick up others
* Fifth level - introduce mechanism (bridge) activated by certain color, then drop that color for final door color
* Sixth level - stair to bridge, pickup bridge color, put down bridge color and pickup door color
* Seventh level - bridge to small room, drop many blocks in small room carefully, bridge to island, fill chasm with inventory, pickup door color
* Eighth level - fill chasm to get to bridge color, return with bridge color to cross

Assets
------

* Logic
	- Player character movement
	- Player pickup blocks
	- Player place blocks
	- Block logic physics, and sleeping
	- Mechanisms listening for all blocks to be picked up
	- Transitioning from one level to the next
	- Menu screen
		+ Level choice screen?
		+ Level finished screen?
			* Blocks picked up
			* Blocks placed
			* Time taken
	- Tutorial dialogs
* Models
	- Player?
		+ Something to point out where blocks will be placed
	- Level pieces?
		+ May just use block geometry
	- Blocks
		+ Color changes
		+ Design changes?
	- Door
		+ Color indicator
		+ Opening and shutting animation
	- Bridge
		+ Endpoints
		+ Bridge itself
		+ Unfolding anim?
* Textures
	- Wall textures for interest
	- Door textures
	- Bridge textures
	- Block place indicator
	- Block design textures?
* Sounds
	- Music
		+ Menu background
		+ Level background(s)
	- Blocks
		+ Pickup
		+ Place
		+ Land on other block?
	- Door
		+ Open
		+ Close?
	- Bridge
		+ Extend
		+ Collapse?
	- Player
		+ Steps?