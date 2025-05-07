My approved feature/mechanic was to recreate the Blitz ability Assail from Warhammer 40k Darktide. It is a type of homing projectile that flies in the direction in is thrown but if the player is looking at an enemy then the projectile will home in at the enemy they are looking at. The player can also hold right click to lock onto a specific target and then fire the projectile to make it home in at the specific target. Assail has 10 shots that the player can fire and they recharge one at a time every 3 seconds.



CONTROLS TO TEST FEATURE IN SHORT: 
PRESS LEFT CLICK TO FIRE PROJECTILES 
MOVE THE MOUSE TO LOOK AROUND
LOOK AT TARGETS TO HOME IN BY AIMING WITH THE CURSOR AT THE MIDDLE OF THE SCREEN
HOLD RIGHT CLICK AND LOOK AT TARGET TO LOCK ON TO THEM
HOLD RIGHT CLICK AND PRESS LEFT CLICK TO DO THE ALT-FIRE
MOVE WITH W,A,S,D
JUMP WITH SPACEBAR


Long explanation on my feature mechanics:

To be able to test my feature in my project. Press left click to fire a projectile and look at a target to make it home in to them. You can hold left click to fire repeatedly.

Hold right click to lock onto a target you are looking at and while right click is held press left click to fire the alternate projectile that homes in on the locked on target. You can change the locked on target by looking at a different target while right click is held. When the alternate projectile hits a target its homing logic will change into the normal homing logic for the left click fire, which means that you will have to look at new targets to make it home in to them.

The projectiles cannot individually home into the same targets that they have hit in their lifespans. They can still hit previously hit targets if they home in on a different target that causes the shot trajectory to collide with them again.  

Projectiles disappear after about 3 seconds or on hitting a third target. 

