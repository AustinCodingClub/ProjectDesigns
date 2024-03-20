# AimBot (Project FAIM)

## Introduction
Project based on this video:
https://www.youtube.com/watch?v=RwzIq04vd0M

We basically want to make an embedded system that will watch the screen and aim for us in games.

How does it watch the screen?
- OpenCV might be a library that we can use for processing the streamed images.
- We could use a USB connection to stream the images over to a secondary PC.
- This secondary PC will handle the processing as well as the aimbotting.

TODO:
- [ ] Research OpenCV
- [ ] Research USB streaming data back and forth

How does the aimbotting work?
- The image processing will detect the enemies and then send the coordinates of where teh mouse should be back to the primary PC.
- Eventually we want that to be a microcontroller that will move the mouse for us.

TODO: 
- [ ] Research how to update mouse positioning on a PC
- [ ] Research how to move the mouse with a microcontroller