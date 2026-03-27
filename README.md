# Titan Rover: 5-DOF Robotic Arm System

## Overview
This repository contains the mechanical designs, CAD files, and documentation for the robotics subsystem developed for the Titan Rover[cite: 233]. The system is a custom-engineered robotic arm featuring 5 degrees of freedom (DOF) across 6 points of actuation[cite: 235]. It was designed with strict weight and size constraints, utilizing specialized gearboxes and manufacturing techniques to achieve high torque and precision[cite: 266].

## Key Features & Specifications
* **Kinematics:** 5 degrees of freedom capable of lifting a 10 lb payload from the floor[cite: 235, 321].
* **Base (Yaw & Shoulder):** Utilizes an orbital gear reduction (62:12 ratio) with a Nema 24 motor for smooth, high-torque base rotation[cite: 253, 254]. Built with Aluminum 6061 for structural stability[cite: 255].
* **Elbow Joint (J2):** Features a custom-designed compact cycloidal gearbox (14:1 ratio) generating 36.4 Nm of output torque to support the 2.5kg distal weight[cite: 265, 267, 269, 270]. 
* **Wrist (J3):** Incorporates a 12-wire 2A slipring to allow for infinite roll rotation, simplifying wiring while enabling complex manipulation tasks[cite: 300, 301, 302].
* **End Effector (Gripper):** Powered by a Nema 11 motor with a 5:1 planetary gearbox and a custom 35:1 worm drive, allowing each tip to exert up to 42 lbs of force[cite: 320, 322, 323].

## Manufacturing & Materials
* **Metals:** Aluminum 6061 used for the base assembly and main structural crossbars (waterjet and machined)[cite: 255].
* **Plastics & 3D Printing:** * Cycloidal housing machined from Nylon 6/6 for reduced friction[cite: 271].
    * Complex components, including the gripper links and housing, fabricated using Formlabs Rigid 4000 SLA resin for engineering-grade strength[cite: 304, 325].
    * FDM printing utilized for rapid prototyping and non-load-bearing enclosures[cite: 304].
* **Hardware:** Nylon gears paired with a brass worm to eliminate the need for lubrication in the end effector[cite: 326].
