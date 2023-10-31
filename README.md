# GrabbingForce
Gather physics objects in a range together and drag them in the air in front of the player. The gravity will be disabled when the physics objects have been grabbed. When grab release, the gravity will be back.

 To make it works you have to do followings :
- Place some actors you want to grab in the level and make sure all of them have enabled “simulate physics”
- Attach this Grabbing Force component to the first person player
- In first person player blueprint, call “GrabObjects” node when mouse clicked. Call “ReleaseObjects” node when mouse released (or use other custum input event rather than mouse click)
- Attach a “RadialForceBP” in this component’s details panel
- Ready to go



![GrabbingForce](https://github.com/TimChen1383/GrabbingForce/assets/37008451/28eaad66-8389-4e0a-85ae-ff7474b3c508)
