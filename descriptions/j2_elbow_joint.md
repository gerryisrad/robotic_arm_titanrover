[<- Back to Robotics System Overview](./overview.md)

# Titan Rover: J2 Elbow Joint

<img width="529" height="454" alt="image" src="https://github.com/user-attachments/assets/adfe4adb-2079-4583-a53d-3e33005a22e8" />


J2 is the elbow joint of the robotic arm. For this joint, it was imperative to create a gearbox with sufficient torque output to withstand the 2.5kg weight of the distal joints and gripper.

<img width="809" height="598" alt="image" src="https://github.com/user-attachments/assets/2edb9acc-3285-42b1-a5f2-2304b15b91de" />

Developing a compact, large gearbox was the most challenging part of the robotic arm design, given strict size and weight constraints. I opted for a cycloidal gearbox, using a formula I developed to determine gear ratios, diameter, and height. By placing two cycloids opposite each other, vibrations from eccentric rotation were reduced.

<img width="425" height="387" alt="image" src="https://github.com/user-attachments/assets/5745e6fd-f1e6-422c-b110-03b338ff14e4" />


The chosen gear ratio for this subsystem was 14:1, meaning there were 15 rollers for every 14 lobes. Paired with the selected motor, the output torque was 36.4 N · m. I used metal pins joined by acetal disks to reduce friction, and the housing is made of nylon 6/6 to further minimize friction between components.


<img width="250" height="332" alt="image" src="https://github.com/user-attachments/assets/e5237385-35f5-4aba-ab25-8b62df000b5d" /> <img width="182" height="336" alt="image" src="https://github.com/user-attachments/assets/6da69159-4454-4eec-b8e7-f3c566102ac2" />




**Vital Skills Utilized:**
* Lathe/Mill Operations
* MATLAB Programming (Cycloid Formula Generator)
* Motor Selection for Torque Specs
* Material Selection (Nylon 6/6, Acetal)
