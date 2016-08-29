#Names, Area, Mentor
Luke P, John H
Robotics
Mentor: David Le

#Brief Description
Our project will involve programming the robot to follow an object using two sonar sensors to determine distance and direction of the object. If the object is to the right, the robot will turn right. If the object is on the left, the robot will move to the left. If the object is too close, the robot will simply stop where it is. Otherwise, the robot will continue to move forward.

Additionally, the robot will track its path in memory. It will then be able to follow the same path without any additional assistance.

#Update 8/29/2016
The code for our robot is almost complete. As of now, we have programmed it to track the object using a state machine. It uses the time module in order to track the length of time the robot spends in each state. Once the path is finished being taught to the robot, it is then able to re-trace its steps using only the history of states and length of time the robot spent in each state. The code for this is essentially complete, but still needs polishing and debugging before it is ready to be presented.
