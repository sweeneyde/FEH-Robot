# FEH-Robot
The program used for Team E4 (Zach Boledovic, Mason Cobb, Luke Koury and Dennis Sweeney) in the 2018 FEH Robot competition at The Ohio State University

[Here](https://youtu.be/oKg_p1pnAxA) is a video of the robot's performance.


Of particular interest is our implementation of "true" omnidirectional motion. That is, instead of being limited to 4 or 8 cardinal directions, the robot was able to move along a straight line with any specified angle, without first rotating in place. This allowed a level of abstraction in the program in which we could specify the coordinates of a point on the course, and the robot would immediately move exactly to that point in a straight line and adjust itself until correct.
