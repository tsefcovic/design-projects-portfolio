# A2 – Truss Stress Analysis

## Objective

Design a lightweight beam around the a given set of parameters. I selected 25 kn as the force that I applied in points P. A is a pin connection while B is a roller. 

<img width="295" height="173" alt="Screenshot 2026-08-31 184705" src="https://github.com/user-attachments/assets/cc189529-7756-44ba-aabe-40c5b0c9e621" />



## Analyze
 The first thing I did was create some quick hand sketches of possible designs for a truss to connect all the points that would be strong enough that the truss itself wouldn’t be heavy. I then selected the design that uses the least amount of members. While keeping each section triangulated, which I know are good at supporting large forces. 

Then I started with solving for the external forces on the beam. I did this by taking the moment about pin A. This allowed me to find the force on the roller or point B. 

<img width="3024" height="4032" alt="IMG_2320" src="https://github.com/user-attachments/assets/e2d1364f-8c58-4d50-8807-e51192b13107" />

This gave me a solid starting point when going into internal forces. For this I decided to use method of joints as it is the method that I am most comfortable with. I started at B as I knew one of the two forces that acted in the y direction which made calculations not only possible but straightforward. I from here I was able to set the force from the roller equal to the vertical component of the force for beam BC. Now that I knew the magnitude of BC I could solve for the sum of the forces in the x direction. Knowing the magnitude of BC I was able to find the value for BE by setting it equal to the x component of BC. I was then able to go to pin C. I started with summing the forces in the x direction, and finding the angle that the member that connects C and E together to make it easy to use trigonometry to isolate the components of the force. Then I moved to pin C, similar to the other pins I was able to sum the forces in the y direction which I originally did incorrectly as I forgot to include the 25 KN force that acts on that pin. This meant that I had to go back and resolve this pin in order to get the correct values. Which again took some time as I originally messed up again and forgot to treat for CB as negative as it is in compression so I got a value that seemed outrageous because it was. From here I was finally able to get values that made sense and continue to work forward. I was able to follow the same process to find forces for the rest of the members. 

<img width="3024" height="4032" alt="IMG_2320" src="https://github.com/user-attachments/assets/d2ac2ed1-d2b2-495d-a89b-92ac8667d9e2" />

Then I was able to start working on the area calculations. The first thing that I did was apply the safety factor by multiplying the largest force that I found by a factor of 3.5. This left me knowing both the force on the member as well as the yield strength of steel being used. 

Following this I repeated the process to find what the minimum area is required for the pins. Here I once again knew the force being applied and the yield strength of hardened tool steel, while I didn’t have the area that is required. 

<img width="3024" height="4032" alt="IMG_2320" src="https://github.com/user-attachments/assets/1dd50327-a378-47a8-a43d-43a5ad078e52" />

I was then able to take these cross sections and calculate the weight of the truss and all of the pins. I found that the total weight would be approximately 5.88 kg. Then after putting everything into CAD, I found that the truss was 5.8 kg and each pin was 0.1 kg. This is slightly more than I calculated, which makes sense because when I calculated I did each beam from center of node to center of node, which doesn’t account for the length of beam beyond each pin. 

<img width="1125" height="745" alt="Screenshot 2026-08-31 183817" src="https://github.com/user-attachments/assets/e744d5dc-05bf-4ef9-a7b0-e2f9429d9045" />

<img width="1122" height="740" alt="Screenshot 2026-08-31 183912" src="https://github.com/user-attachments/assets/0ab23e49-dc0b-49a8-8ae2-a1885fe5effd" />


## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

I selected a design that triangulates everything by placing a triangle in the middle of the trapezoidal shape made by the points we are given. This is a common design that I have seen it in the real world very often. Also it reduces the amount of members some while maintaining strength. 

## Communicate
Through this assignment I learned how to apply the topics that I have learned in previous classes like statics and use them to actually design an entire system. This assignment took me around 8 hours many of which were due to me reworking my CAD after not being content with how it came out originally. 
