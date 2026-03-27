[<- Back to Robotics System Overview](./Overview.md)

# Titan Rover: J3 Wrist Joint

<img width="282" height="413" alt="image" src="https://github.com/user-attachments/assets/f26c9abc-a32c-4936-850f-2f046c648f16" />

J3 is the wrist component of the design, intended to provide the gripper's pitch and roll. We needed two different types of movement because our gripper had to manipulate keyboards and joysticks and perform general tasks that required more than one plane of rotation.

<img width="328" height="258" alt="image" src="https://github.com/user-attachments/assets/b8e1362c-c024-4707-9f24-2b3e1eb9c339" />

To achieve infinite rotation, we used a 12-wire slipring rated for 2A at our roll joint to simplify wiring. The rotation orbital gear was custom-designed entirely around this slipring. A Nema 11 motor provides the rotation and is offset from the main slipring.

<img width="404" height="500" alt="image" src="https://github.com/user-attachments/assets/a8a6bd07-d021-4bd8-b60b-eceec4cfbdfe" /><img width="417" height="548" alt="image" src="https://github.com/user-attachments/assets/6b382ae5-674d-4134-942c-c244f47f98bb" />


As this design was fully custom, I utilized FDM and SLA printing to manufacture the parts. Specifically, I used a Formlabs Form 2 resin printer for the structural components and an Ender 3 S1 Pro. Thrust bearings were sandwiched against the main frame to allow smooth rotation.

<img width="318" height="339" alt="image" src="https://github.com/user-attachments/assets/e4934d4c-5a29-431a-85d8-694bd452a2c7" /><img width="366" height="447" alt="image" src="https://github.com/user-attachments/assets/949a6a5d-f75b-4c34-b4ef-b01c0c9a2cc1" />



**Vital Skills Utilized:**
* SLA 3D Printing with Engineering Strength Materials
* Electrical Routing
* Motor Selection (Nema 11 with 14:1 gearbox)
