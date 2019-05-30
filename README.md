# fluid
I want to make [this](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation/) beautiful thing more useful and keep maximum visual feedback. The early tests are v2.html and v4.html. I'm not a programmer, so use liberally.

## Controls
mouse, touch, keyboard (up, down, left, right, space)

## Goals
1. Make the fluid work in a 3D scene for use in game dev. Eg. the wake of a boat
2. A music visualiser, crazy disco dancing device for your finger.  

The gamedev project makes this a texture in three.js and used accordingly. Also controlled via keyboard.
It could be a canvas set as display:none. That is delicious because I'm experimenting with making good use of it while not going over the top with the processing. I want to make a globe that can express. This might help with that.

The visualiser project is a touch only 'one finger' disco.
I like the idea that a disabled person can use the same thing to dance as that big time DJ. The HUD is juicy invisible buttons and sliders. I am not sure how that works yet.

## done
Added overlay dom element [hero]

Added keyboard controls

Added smokey trails

Moved multipleSplats function

## do
Seperate into gamedev and audio viz projects.

Three.js integration.

Box2D integration.

Optional canvas hero (not a dom element).

Collider objects/walls.

Gamepad, gyro, pacemaker, heartbeat, kinect integration?

Comedy character face sprites for button.

Read audio before playing to find peaks and troughs, then adjust accordingly.

A nice and juicy HUD for settings, samples and dance moves.

Make it dance automatically or via finger. 

Make the 'modes' music/mic/no music/dj/viz. Distinct and fun.
