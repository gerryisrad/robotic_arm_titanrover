[<- Back to Robotics System Overview](./overview.md)

# Titan Rover: Base and Shoulder Subsystem


<img width="470" height="495" alt="image" src="https://github.com/user-attachments/assets/36b573ce-874b-4c16-90b6-3dbe69e2fd6d" />


The base of the robotic arm required less creativity than the other portions of this project, but it is arguably the most important part of our arm as it is the main source of yaw. It also actuates our shoulder joint using a linear actuator with high holding torque to support the rest of the arm.


<img width="433" height="454" alt="image" src="https://github.com/user-attachments/assets/5b30e539-1c44-4dbb-89ed-4aa9fdbaae1f" />

The main hurdles in this portion of the project involved creating gearboxes capable of generating sufficient force to lift the arm segments. To address base rotation, I designed a system that used an orbital gear to slow our Nema 24 motor, achieving a 62:12 gear ratio. This approach significantly boosted the motor's torque for smoother base rotation and extended arm reach. 

<img width="1253" height="763" alt="image" src="https://github.com/user-attachments/assets/026efca0-2bea-49b5-a7ea-9762a7aae09a" />


Aluminum 6061 was used for all portions of this assembly to reduce the weight while keeping structural stability. The plate itself was cut carbon fiber.

<img width="369" height="410" alt="image" src="https://github.com/user-attachments/assets/3f52336b-1fab-423a-aacb-7dee8fa4e559" />


**Vital Skills Utilized:**
* Waterjet Operations
* Material Selection (Aluminum 6061)
* Stress Analysis on the main crossbar
