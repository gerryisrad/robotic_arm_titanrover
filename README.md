# Titan Rover: 5-DOF Robotic Arm System

## Overview
This repository contains the mechanical designs, CAD files, and documentation for the robotics subsystem developed for the Titan Rover. The system is a custom-engineered robotic arm featuring 5 degrees of freedom (DOF) across 6 points of actuation. It was designed with strict weight and size constraints, utilizing specialized gearboxes and manufacturing techniques to achieve high torque and precision.

## Key Features & Specifications
* **Kinematics:** 5 degrees of freedom capable of lifting a 10 lb payload from the floor.
* **Base (Yaw & Shoulder):** Utilizes an orbital gear reduction (62:12 ratio) with a Nema 24 motor for smooth, high-torque base rotation. Built with Aluminum 6061 for structural stability.
* **Elbow Joint (J2):** Features a custom-designed compact cycloidal gearbox (14:1 ratio) generating 36.4 Nm of output torque to support the 2.5kg distal weight. 
* **Wrist (J3):** Incorporates a 12-wire 2A slipring to allow for infinite roll rotation, simplifying wiring while enabling complex manipulation tasks.
* **End Effector (Gripper):** Powered by a Nema 11 motor with a 5:1 planetary gearbox and a custom 35:1 worm drive, allowing each tip to exert up to 42 lbs of force.

## Manufacturing & Materials
* **Metals:** Aluminum 6061 used for the base assembly and main structural crossbars (waterjet and machined).
* **Plastics & 3D Printing:** * Cycloidal housing machined from Nylon 6/6 for reduced friction.
    * Complex components, including the gripper links and housing, fabricated using Formlabs Rigid 4000 SLA resin for engineering-grade strength.
    * FDM printing utilized for rapid prototyping and non-load-bearing enclosures.
* **Hardware:** Nylon gears paired with a brass worm to eliminate the need for lubrication in the end effector.
