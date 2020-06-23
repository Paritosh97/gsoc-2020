
# GSoC Week 2 - Qt3D based backend for KStars


In the second week of GSoC, I worked on handling projections, instance rendering for multiple stars, updating SkyObject coordinates and worked on porting the existing grid system in KStars to Qt3D.


## What's done this week

- Setup of the Celestial Sphere.

- Displaying stars on the screen using simple 3D point on the Celestial sphere.

- Implementation of SkyPolyLines for drawing grids on the celestial sphere.

- Sync with backend for transformations.


## The Challenges

- Integration issues with the original SkyPainter API written to support multiple backends.

- Qt3D's scenegraph based rendering on KStars which displays and updates data frame-by-frame.

- Projection modes for different grid systems.

- Transform Synchronization base on the projection mode used.


## What remains

My priorities for the next week include.

- Instance rendering for millions of stars displayed by KStars.

- Dig deep into projection modes and shader coding based on the pre-existing Projector class in KStars.

- Updates using SkyComposite.

## Demo
![Grid System](./../assets/posts/images/week-2-1.gif)


## The Code

 - [My fork for KStars](https://invent.kde.org/paritosh/kstars)
