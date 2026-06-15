# Inverse Kinematics using MATLAB, Simscape & Robotics System Toolbox

## Overview

Inverse kinematics is used to calculate the joint angles required to move a robot’s end-effector to a desired position.

It is the reverse process of forward kinematics and is used for controlling robot motion based on target positions.

This project demonstrates inverse kinematics using Simscape Multibody and Robotics System Toolbox in MATLAB.

---

## Project Features

- Computes inverse kinematics for a robotic system  
- Uses Simscape Multibody for physical simulation  
- Uses Robotics System Toolbox for mathematical modeling  
- Supports trajectory-based motion using Signal Editor  
- Smooth end-effector motion tracking  

---

## Robot Simulation Model (Simscape Multibody)

- Built using Simscape Multibody blocks  
- Contains two revolute joints for rotation  
- Includes a weld joint to fix the end-effector  
- Represents real mechanical structure of the robot  
- Used for motion simulation  

---

## Robot Mathematical Model (Robotics System Toolbox)

- Defined using a rigidBodyTree model in MATLAB (.m file)  
- Imported into MATLAB workspace  
- Used for kinematic calculations  
- Used for inverse kinematics computation  

---

## Inverse Kinematics Solver

- Implemented using inverseKinematics function  
- Takes desired end-effector position as input  
- Computes required joint angles  
- Outputs joint configurations for the robot  

---

## Input Trajectory

- Trajectory defined using X, Y, Z position values  
- Generated using Signal Editor block  
- Allows custom path definition for the end-effector  
- Used as reference for robot motion  

---

## Simulation Output

- Joint angles are sent to the Simscape model  
- Robot follows the desired trajectory  
- End-effector moves smoothly along the path  
- Accurate position tracking is achieved  

---

## Conclusion

This project successfully implements inverse kinematics using:

- Simscape Multibody simulation model  
- Robotics System Toolbox mathematical model  


---

## Tools Used

- MATLAB  
- Simscape Multibody  
- Robotics System Toolbox  
- Signal Editor  
