A write-up of the software stack I've been developing around this robot is located here: [2011/0805-software-framework-for-robotics](https://www.kaliatech.com/projects/2011/0805-software-framework-for-robotics/).

This project originally started with a [Lynxmotion BRAT kit](http://www.lynxmotion.com/p-859-biped-brat-combo-kit-w-botboarduino.aspx) and goal to do smooth servo motions. Differences from BRAT chassis include:

 * Additional 2 DOF so that legs can rotate around the vertical axis. I'm hoping this will allow more natural and flexible walking gaits.
 * Uses ASB-503B from Lynxmotion SES catalog to connect the legs instead of aluminum channel. This widens the stance just a little.
 * Custom mounting for battery, microcontroller, etc. This is simple design cut out of Lexan, but I like how it worked out. It keeps the center-of-gravity relatively low without restricting any movements.
 * Instead of SSC32, uses a custom Parallax Propellor based microcontroller. This was the main point of this particular project. Custom coding for high level group servo moves that are sent from PC over bluetooth.
 * The custom programming and protocol includes servo acceleration/deacceleration parameters...which is the primary thing missing from most off-the-shelf servo controllers.

The 3D modeling was done with Alibre, and the renderings were done with Hypershot. Red color shows the custom piece cut out of lexan.  Alibre interviewed me for one of their case studies. Alibre has gone through a couple owners over the years, and while the case study is no longer online, images of my robot continue to show up on their marketing pieces.
