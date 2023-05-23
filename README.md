# ParkingSpace
## Parking lot monitoring system in real time using security cameras
I developed an interesting project in Python that includes the implementation of a parking lot monitoring system in real time. The project receives information from security cameras installed in the parking lot and displays in real time the status of the occupied and vacant parking lots.
That is, if you look at the video, you will see that as soon as a parking space becomes available, the light turns green,
It works in a very simple way:
First of all I took a static picture and marked all the available parking spaces, after that I converted the video to a binary video and according to this I can check the amount of pixels in each parking space that I marked, you see the numbers in each parking space, I developed an algorithm with a simple condition, if the numbers (the number of frames) exceeds 900, then the square will be red, if below 900 it means there are not many frames, the algorithm kind of turns the parking lot and turns the square green
It is on one leg, of course there are other related algorithms besides that but this is the main one
I sunk in
The project was developed with Computer Vision, OpenAi, numpy, and more
