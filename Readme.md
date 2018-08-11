Ludum Dare 42
=============

/.*/?

The answer to life, the universe, and everything.

Details
-------

This is a game submission for the Ludum Dare 42. The theme was "Running out of
space."

Brainstorming
-------------

Space in a room
Space in space
Space as a character
Space as a person (a bit spacey that)

Running out as in having a set amount and running out of it
Running as in literally running
Running as in water running out of a space

Obvious ones
* Filling up a room
* Needing to add things to accomplish other things, but only having so much space
* Needing to accomplish the task as you run out of space to move
* Escape space - Explosive decompression, run away from the expanding vacuum on a doomed space ship. How long can you survive. (idea)

Can I make this a tower defense?
Yes
* You are defending an island or something
* Over time, you lose spaces to build towers
* You need to upgrade the towers you have to make sure you keep up with the growing waves of enemies

Can I make this an FPS?
Probably... I don't do FPS... usually. Might be fun

Breakout seems obvious
Or tetris

Old Western theme?
Town is running out of space... too much dysentery?
Gun battles... too many opponents

One mechanical idea is to have limited inventory space (or similar space) and to have some constant influx of something useless or challenging taking up that space
So you have increasingly less space to put things in your inventory

Say, for instance, a mech game where you only have so many augmentation slots, but each upgrade comes with additional useless pieces that must be added.
Or the pieces could be larger with each upgrade so you have less space for variety. Eventually you have to choose between speed or shields or guns, making you
a rather specialized unit, but not very effective in certain ways.

Fluid running out of a space seems like an interesting idea but represents a significant programming challenge, especially in 3d
What would be the goal and what would be the mechanics?

* Fill up these things? Meh
* Open up the path so you can go from one end to the other.
	- Like it, but level design challenge
	- Also clarifying how this hits the theme would be difficult
	- But then that doesn't really matter too much

Runner where the path is continually disappearing

Puzzle with rooms on top of one another, each room has a set amount of liquid
You can decrease the amount of liquid in the room by dumping it into the next room,
but then you have to navigate through it since the exit is at the bottom

Floodgait :)
Flood-Gate

Allow bidirectional travel between rooms
Add mechanisms that only work outside of water
- Doors
- Raising and lowering blocks

The problem is the irrevesableness of water draining to the room below

Also the puzzles I can think of aren't very difficult or interesting

So the fun of the game is debateable

Pity, because I like the idea

-----------------------------

Base something off of the inventory idea?

Shooters of some variety are an obvious choice
But basically you want something where the inventory is used for something useful
But also have something where the inventory could be filled by something and progressively run out of space
The tower defense idea is essentially one of those, only the inventory is tower space

The idea of a population draining the resources while you try to get rid of them is interesting
Earth and resources is an obvious iteration of that
You could extend that to bugs, eating all the food. Gross

I like the idea of a game where you want to consume space to gain benefit, but
also limit yourself by consuming that space

Space equals power
Inventory that means more power takes up more inventory space
But that's simple

Something using the space bar?
Limited uses of the spacebar for something critical? Like jumping? :)

You can only jump so many times
The more you progress, the more you can't jump

The level encroaches on you as you progress

Collect things and leave level?

Simple 3d platforming?
FPS platforming

Enemies in a room put in another room?
The problem is how do you scale puzzles with the choice to delay penalties?
Too high level of a question for my brain in a brainstorming state

Cows

An rpg that wants you to pick everything up?
Globberlike? where your character gradually just holds everything at once is a really large mass?

Limited spacebar running out over time, so it's not so much how much you use it
but how much time has passed before you lose it

Spacebar can be attack
Can be jump
Can be another ability
Can be activate thingy

Runner through level
with these you want interesting levels

You could have recharges for the spacebar

Could be a top down shooter
Where your a boat or a spaceship
You have fuel which runs out over time
While you have fuel you can fire your lasers
When you have no fuel, you lose mometum until you stop

Either there are enemies
Or you are escaping from something

... say a waterfall

As you try to escape from the waterfall, you are running out of fuel
If you run out of fuel, you'll be drawn in by the river until you plunge over
the waterfall

You must blast logs out of the way, go around them

Rivers mean water though... can I do water in unreal... psshhhtttt... totally :)

So...

Le Amazon
* Escape from the edge of a waterfall
* Boat upstream around obstacles like rocks, logs, and alligators
* You are constantly running out of fuel, so be sure to pick some up along the way
* Use fuel to clear obstacles by pressing `space` (shoot the alligator, shoot
the log, shoot the rocks)


Strengths
* Simple
* Auto-genable
* Infinite possibilities
* Can add lazors

Weaknesses
* The theme is weak with this one
* Alligator AI
* WATER

------------------------------------------------

FPS puzzler

You go from room to room

You must collect all the blocks of a given color to make the door open

These stay in your inventory as you leave the room

You can only hold a single color of block at a time

So to pick up the next color of block, you'll need to unload the current color
of block

So design is key in this game
You'll need to make each level by hand
And balance it
Fortunately, the game mechanics seem simple
Physics driven

Getting the cubes to stay in place once placed will be interesting
But you should be able to physics sleep and then make them static
I wonder if there's an event to listen for sleeping
If so, you just inactivate the physics component after sleep

How many levels can I make?

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

Occlusion
Obstruction
Blockage
