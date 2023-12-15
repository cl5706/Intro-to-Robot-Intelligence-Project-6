# Intro-to-Robot-Intelligence-Project-6
## Author：
Chang Liu cl5706
Haosheng Wang sw2514

## Project Discription:
Implement a rover that can shoot the ball into gate. Where in the video, the red barrier is the "gate", and the rover will keep pushing the ball near the barrier.

## Algorithm:
1. The rover search for the ball and make sure it is in the center of the camera.
2. Check if the gate and the ball are on one line. If they are, the rover move forward to push the ball closer to the gate.
3. If they are not on one line, the rover will adjust its angle with the ball and do step 1-3 recursively.
4. The robot stop when the ball and the gate are already close enough.
