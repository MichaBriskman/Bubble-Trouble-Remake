# Final Project: Bubble Trouble

# Students info:
Michael Basov - </br>
Shlomo Gulayev - </br>
Micha Briskman - </br>
# Video
[![Watch the video](https://www.youtube.com/watch?v=fh4R8KwFs-Y)](https://www.youtube.com/watch?v=fh4R8KwFs-Y)

# Summary:
For the final project of the semester we made a remake for the game called 'Bubble Trouble'.
In the game, the player controls a chrarcter using the arrow (left, right) keys,
the character has to destroy the bouncing balls on each level using their weapon (press 'space' to shoot)
while avoiding getting hit by them. Once every ball is cleared, the game procceeds to next level.
There are four sizes of balls, every size has different color and when the player pops a ball,
two smaller balls drop. A ball can drop a gift, there are different gifts such as different weapons,
shield, extra health and more; On some levels there are doors that open once every ball to the right is popped.
You can play alone or with another player from same computer, or can connect over LAN (wi-fi or physic connection)
to play with another person, the second character is moving using 'A' and 'D' keys for movemennt and shooting with Lshift.

## The game is using two C++ libraries, SFML for graphics and Box2d for physics.

# List of files (each file has .h and .cpp):
Animation - Controls the animation of the Player class.</br>
Ball - Represnts the ball that the player needs to destroy and avoid getting hit by.</br>
Board - Manages the graphics and drawing and game on the window, manages events on the board.</br>
Button - Represents a button that can be pressed.</br>
Caption - Manages the captions, titles and text seen while playing.</br>
ContactListener - Manages collision between different objects in the game.</br>
Controller - Controls the game and levels, everything is controlled over there.</br>
GameObject - Represnts every object in the game. An abstarct class.</br>
Gate - Controls the gates in the game, opens if all balls to the right are destroyed.</br>
Gift - Represents a gift in the game. An abstract class.</br>
HookWeapon - Represnts a weapon that is sticking to the cieling for 3 seconds before disapearing.</br>
LaserWeapon - Represtns a weapon that is smaller and shoots faster lasers.</br>
macros - Stores important includes, enum classes and const variables that used by few classes. does not has a .cpp file.</br>
Menu - Controls the menu options and buttons.</br>
MovingObjects - Represnts every moving object in the game. An abstarct class.</br>
NormalWeapon - Represtns the default weapon the player starts with.</br>
Player - Represents the player, it's collisions and controls.</br>
Resources - A singlton, loads and stores the textures, pictures and sounds to the game.</br>
Shield - Represnts a gift, if player picks it up he gets a shield for few seconds and can't be hit.</br>
Socket - Represents a socket control for LAN connection.</br>
StaticObject - Represnts every static object in the game. An abstarct class.</br>
Wall - Represents a wall that blocks every object in the game.</br>
Weapon - Represents a weapon. An abstarct class.</br>
