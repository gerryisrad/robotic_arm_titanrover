# Titan Rover: Robotics System Overview

This directory contains the documentation and design details for the Titan Rover robotics system. The robotic arm features 6 points of actuation, giving it 5 degrees of freedom. Select a subsystem below for detailed mechanical breakdowns and CAD information.

## Subsystem 1: [Base and Shoulder](./base_and_shoulder.md)
* The base provides the main source of yaw for the arm and actuates the shoulder joint using a linear actuator with high holding torque.
* Base rotation is driven by a Nema 24 motor and an orbital gear system achieving a 62:12 gear ratio.
* The assembly is constructed from Aluminum 6061 to reduce weight while maintaining structural stability.

## Subsystem 2: [J2 Elbow Joint](./j2_elbow_joint.md)
* The elbow joint features a custom-designed cycloidal gearbox.
* It utilizes a 14:1 gear ratio, resulting in an output torque of 36.4Nm.
* The housing is made from nylon 6/6, and it uses metal pins joined with acetal disks to reduce friction.

## Subsystem 3: [J3 Wrist](./j3_wrist.md)
* The wrist component provides both pitch and roll for the gripper.
* It incorporates a 12-wire 2A slipring at the roll joint to allow for infinite rotation and simplified wiring.
* Rotation is powered by an offset Nema 11 motor and a custom orbital gear designed around the slipring.
* Parts were fabricated using SLA (Formlabs Form 2) and FDM (Ender 3 S1 Pro) 3D printing.

## Subsystem 4: [Gripper (End Effector)](./gripper.md)
* The gripper is designed to lift a 10lb payload from the floor.
* It utilizes a worm drive, allowing each end of the gripper to exert up to 42lb of force.
* The mechanism is driven by a Nema 11 motor with a 5:1 gearbox and a 35:1 gear reduction from the worm drive.
* The housing and links are made from Formlabs Rigid 4000 material, combined with nylon gears and a brass worm to eliminate the need for lubrication.
