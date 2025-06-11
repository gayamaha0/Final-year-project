# Final-year-project:Pneumatic  Industrial Robot for Pick and Place Application

Overview:
This project Developed in collaboration with Axis Global Institute of Industrial Training, focuses on the design and development of a Pneumatic-Based Pick and Place Robot for industrial automation. Built as part of our final year engineering curriculum, the robot is controlled using a Delta DVP-14SS2 PLC and operates entirely through ladder logic without sensor feedback.

The robot uses solenoid valves to drive pneumatic actuators, enabling precise pick and place operations. A mechanical gripper built using a crank and slider mechanism is used for object handling. The design includes a 4th waxis linear motion, allowing extended reach and flexibility for object placement along an additional axis.


Tools and Technologies Used:
---------------------------------------------------------------------
|        Description        |        Components                     |    
---------------------------------------------------------------------
|  Controller               |   Delta DVP14SS2 PLC                  |
|  Pneumatic Actuation      |   Double Acting  5/2 Solenoid valves  |
|  Power Supply             |   MCB,SMPS, Industrial Relay          |
|  Programming              |   Ladder Logic Design                 |
|  Software                 |   AutoCAD mechanicl,WPLSoft 2.52      |
|  Gripper                  |   Mechanical Gripper                  |
|  Wiring Components        |   Terminal Blocks,Wires,Connectors    |
---------------------------------------------------------------------

Working Principle:

The working principle of the Pneumatic Pick and Place Robot is based on a sequential process controlled by a Delta DVP-14SS2 PLC using ladder logic programming. The cycle begins with the robotic arm moving up from its initial position to avoid interference with nearby components. It then moves forward toward the object to be picked. Once aligned, the gripper closes to securely grasp the object. After gripping, the arm moves backward to retract from the pickup area. It then moves down to the designated drop location. Finally, the gripper opens to release the object in place. Each of these movements is carried out using pneumatic cylinders operated by solenoid valves, and the entire sequence is managed through timed instructions in the PLC without any sensor integration. This open-loop, timer-based control ensures smooth and repetitive pick-and-place operations ideal for structured industrial environments.


