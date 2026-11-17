# A10 – Lead Screw Translating System

## Objective

The objective of this assignment was to determine the minimum leadscrew diameter, required rotational speed, and maximum operating torque for a mechanically driven tensile testing machine. The tensile tester must apply a
maximum axial load of 2,000 N while maintaining a controllable crosshead speed between 1 and 50 mm/min. The system uses two identical leadscrews to distribute the applied load evenly. A safety factor of 4 is required.

## Design Requirements

-Maximum tensile load: 2,000 N

-Number of leadscrews: 2

-Safety factor: 4

-Crosshead speed: 1–50 mm/min

-Minimum leadscrew length: 18 inches

-Power system: Purely mechanical

## Minimum Leadscrew Diameter

Andrew-

We began by determining the axial load on each leadscrew. Since the system uses two identical leadscrews, we assumed the load would be distributed equally.
Carbon steel was selected due to its strength, machinability, affordability, and availability through McMaster-Carr.


<img width="1080" height="1440" alt="A10 6 (1)" src="https://github.com/user-attachments/assets/9721a483-4da0-4553-9e5d-c733278947a4" />


<img width="1080" height="1440" alt="A10 4 (1)" src="https://github.com/user-attachments/assets/34bcf790-ab04-41d8-b401-3c08920a29a7" />


McMaster-Carr only had the ultimate tensile strength of 64,000 psi. Because the yield strength was not specified, we estimated it using an assumed yield-to-tensile strength ratio of 0.56.
The calculated minimum root diameter was approximately 4.5 mm based on axial yielding alone. Additional checks are needed to verify the screw under combined axial and torsional loading.

## Rotational Speed

<img width="1080" height="1440" alt="A10 3 (1)" src="https://github.com/user-attachments/assets/7a8709e2-8c82-4ed2-99aa-5a76e3abd10a" />


<img width="1080" height="1440" alt="A10 5 (1)" src="https://github.com/user-attachments/assets/6b10bf5c-cf56-468c-b5d7-3879b9ed901e" />


The required rotational speed range is approximately 0.63–31.5 rpm. Both leadscrews must rotate at the same speed to ensure consistent crosshead movement and minimize misalignment.

## Maximum Torque

<img width="1080" height="1440" alt="A10 2 (1)" src="https://github.com/user-attachments/assets/75d1d7e8-15ef-44eb-a6e6-60c498ceb28f" />

<img width="1080" height="1440" alt="A10 1 (1)" src="https://github.com/user-attachments/assets/1d01afcc-b919-4c53-9e0a-fe9c04d0c111" />


The operating thread torque is 0.69 N·m per screw, or 1.4 N·m total. The preliminary factored thread torque is 5.5 N·m.

These results use an assumed friction coefficient of 0.15 and exclude bearing friction and drivetrain losses. They do not establish the maximum allowable torsional capacity of the selected screw, which requires a separate strength check.

4. Leadscrew Selection

After evaluating the calculations, I've selected the following leadscrew

https://www.mcmaster.com/98935A803/

## Analyze
Tyler- Handled the thread calculations, CAD, and price analysis. 


<img width="536" height="483" alt="Screenshot 2026-11-16 185000" src="https://github.com/user-attachments/assets/80253490-a32d-49e2-92be-f8ce627ceaf5" />


<img width="346" height="410" alt="Screenshot 2026-11-16 185012" src="https://github.com/user-attachments/assets/279394d1-0bd5-45de-bd3e-4a0901a5f093" />

<img width="415" height="420" alt="Screenshot 2026-11-16 185025" src="https://github.com/user-attachments/assets/05aa34b4-0760-4427-ac6c-1f9f9d0f4def" />

Every thread calculation that I performed showed that the threads are more than capable of handling the forces that will be seen through this application. 






## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate

<img width="194" height="117" alt="Screenshot 2026-11-16 223330" src="https://github.com/user-attachments/assets/ed6db6ff-99a3-4128-a32d-12bdeeeffe42" />

Links for parts:

https://www.grainger.com/category/material-handling/structural-framing-systems/t-slot-framing-systems/profiles-for-t-slot-framing/metric-profiles-for-t-slot-framing 

https://www.mcmaster.com/98935a803/

https://www.mcmaster.com/95072A881/

https://www.onlinemetals.com/en/buy/aluminum/0-5-x-1-aluminum-rectangle-bar-6061-t6511-extruded/pid/1165?variant=1165_96_0&msclkid=ef2afa38267310de65a290c3eced65f8&utm_source=bing&utm_medium=cpc&utm_campaign=%5BRithum%5D%20%5BShopping%5D-%20Top%20Materials&utm_term=4580840345287860&utm_content=Aluminum


CAD: 

[Tension Testing rig.zip](https://github.com/user-attachments/files/34950602/Tension.Testing.rig.zip)

