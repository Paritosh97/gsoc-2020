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

- Dig deep into projection modes and shader coding based on the pre existing Projector class in KStars.

- Transformation updates based on signals instead of frame by frame.


## The Code

 - [My fork for KStars](https://invent.kde.org/paritosh/kstars)

## Useful Links

 - [GSoC Proposal](https://storage.googleapis.com/summerofcode-prod.appspot.com/gsoc/core_project/doc/5468988994224128_1522087817_Technical_Proposal.pdf?Expires=1533768052&GoogleAccessId=summerofcode-prod@appspot.gserviceaccount.com&Signature=pdppYy8Nvq5GRZXz%2byB6AJFQ6r1Ui%2bsGZN//SzNny0o76T1QnAfIrcdp8yFmXw5gY2l21UtvH88vA%2bRwwDxTPtEJQIg0F2vqY6r%2bMkbFEv9g/d8XCNCAe6MHQZGhHnhlJZ3evS7ZwJ9eITJeq3xfD84xvMRVp1MEvS1SV5fOY5ZUnXjCS6/lRJXFTnNhWZK4uuLCYInrbfqJwxRGJddn6zO6D5w5txnZm%2bTj4hkNxrdc05ioy%2brG2993/AbotKM%2bnjng4TlOEAiLeSUEFd2Ukg0r833qpYfLOoCrbQ/uCfOaIICKdfl9wGBzEp55Vn5BW%2bgOoVDYmW8mugJeD0OqTg==)
 - [Progress Report #1](https://godotengine.org/article/gsoc-2018-progress-report-1#gearvr-daydream)
