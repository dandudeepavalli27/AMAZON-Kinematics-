# AMAZON-Kinematics-
Aim
To determine the type of motion of a differential-drive robot based on wheel speeds.
General Objective
To understand the kinematics of differential-drive robots and how wheel velocities influence robot motion.
Specific Objective
To analyze motion when:
Left wheel speed = 3
Right wheel speed = 3
If both wheels move at equal speed → Straight line motion.
Dataset
Differential Drive Dataset
Source: ros2_control
Procedure
Input left wheel speed
Input right wheel speed
Compare both speeds
If equal → Straight motion
Display result
Algorithm
Start
Input left and right speeds
If left == right → Straight motion
Else → Turning motion
Display result
Stop
Code Logic
if left == right:
    motion = "Straight Motion"
Python Code
# SESSION 22 – Kinematics (Differential Drive)

# Step 1: Input wheel speeds
left = 3
right = 3

# Step 2: Determine motion
if left == right:
    print("Straight Line Motion")
else:
    print("Turning Motion")

print("\nProgram Executed Successfully")
Output
Straight Line Motion

Program Executed Successfully
Result
Since both wheel speeds are equal:
Straight Line Motion
Industry Application
Kinematics is used in:
Mobile robots
Autonomous vehicles
Warehouse robots
Delivery systems
Companies like Amazon use this in:
Warehouse robotics
Autonomous navigation
Robotics control systems
Conclusion
Equal wheel speeds in a differential-drive robot result in straight-line motion, which is fundamental for robot navigation.
