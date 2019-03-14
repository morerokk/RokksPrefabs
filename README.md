# Overview

A collection of VRChat prefabs made by me.

* **Binoculars:** Working binoculars that use cameras to actually zoom.
* **Blinking:** A toggle-able blinking prefab that does not use legacy animations.
* **Custom Humanoid Animator:** A sample humanoid animator controller with improved gesture support. Cannot be used on your avatar directly yet.
* **Mesh Particle Stick In Surfaces:** A sample particle system for properly aligning mesh particles and sticking them into surfaces. Ideal for arrows or knives. Increasing the simulation speed of the first subemitter may improve responsiveness.
* **Oneshot Particles:** A burst particle system. Features an always-on particle system and a toggle-able "trigger" system. Every time the Trigger system activates, the other system spews out one burst. Allows shooting one particle burst per activation, without erasing the already existing particles. You may have to set the speed of the trigger system to 0.1.
* **Prop Orientation:** Uses Dynamic Bone to orient a prop towards an inside-bounds collider. Ideal for two-handed guns or weapons.
* **Portal Shaders:** A stencil-based "portal" effect that makes your avatar invisible unless viewed from certain angles.
* **World Objects:** Non-legacy world objects. Comes with an automatic position reset when not in use, meaning that it won't break after the first activation. Also fixed for Unity 2017.
