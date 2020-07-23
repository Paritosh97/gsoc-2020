# GSoC Week 6 - Qt3D based backend for KStars

In the seventh week of GSoC, I worked on adding all existing init and update calls to skymapcompsite and subsequent classes derived from skycomponent. This completes the integration with the KStars backend.

## What's done this week

- Init calls for skycomponent derive classes which help setup the Qt3D scenegraph

- Update calls which adjust shader uniforms an enable update and mouse events.


## The Challenges

- Integration issues with the original SkyPainter API written to support multiple backends. The CustomWindow class doesn't utilize SkyPainter but has similar draw calls.

## What remains

My priorities for the next week include.

- Completing all the update calls

- Debugging and adding other sky objects.

## The Code

 - [Celestial Sphere Prototype](https://github.com/Paritosh97/celestial-sphere-sim)
 - [My fork for KStars](https://invent.kde.org/paritosh/kstars)
