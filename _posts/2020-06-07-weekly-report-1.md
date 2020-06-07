
# GSoC Week 1 - Qt3D based backend for KStars


The coding period for GSoC officially started on 1st of June. My project aims at adding a 3D based backend to KStars which currently utilizes QPainter to render the realtime night sky in 2D.


## What's done this week

- Extension of the original KStars Skymap to show a Qt3D scene.

- A horizon which displays a clear sky where skyobjects are supposed to be rendered.

- Addition of textures and few skyobjects(Sun and Moon).

- Connection of the scene with KStars backend to get the positions of respective skyobjects.


## The Challenges

- Integration issues with the original SkyPainter API written to support multiple backends.

- Qt3D's scenegraph based rendering on KStars which displays and updates data frame-by-frame.

- Environment Light support to color the horizon based on Sun/Moon position.

- Position Synchronization base on the projection mode used.


## What remains

My priorities for the next week include.

- Instance rendering for millions of stars displayed by KStars.

- Dig deep into projection modes and shader coding based on the pre-existing Projector class in KStars.

- Transformation updates based on signals instead of frame by frame.

## Demo
![Skybox and Sun](./../assets/posts/images/week-1-1.gif)


## The Code

 - [My fork for KStars](https://invent.kde.org/paritosh/kstars)
