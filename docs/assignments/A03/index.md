# A3 – [Topic]

## Objective
For this project I was tasked with designing a beam that will deflect a maximum amount of 0.009 inches under a load between 300 and 500 pounds of force. The beam is to be made of Aluminum that has a young’s modulus from (8.5-11.5)10^6 psi. I decided to use a force of 450 pounds and a young’s modulus of 10,000,000 psi.

## Analyze
The first task is to determine the cross-sectional area. To do this I selected a number based on what seemed reasonable after plugging several in. I then plugged that into the equation for length and solved. I then put these same numbers into the SolidWorks model. 

<img width="556" height="370" alt="Screenshot 2026-09-07 232739" src="https://github.com/user-attachments/assets/ec36ae05-5355-4c54-8c66-3fe5dd287a02" />


I then used this to create a model of the beam to then simulate. I was able to get all the plots fairly easily. I then had to spend some time figuring out how to change units as everything was in SI units to begin with. 

The deflection that I got was very close to the maximum allowable which makes sense as that was the value that I was using in my hand math to determine the size of the beam itself. 

<img width="1133" height="731" alt="Screenshot 2026-09-07 225900" src="https://github.com/user-attachments/assets/724cc6d6-b9ef-4b7e-ab40-36c9fb0b857a" />

I then checked the stress plot and found that it was under the yield point of aluminum at approximately 31 ksi. This leaves a safety factor of 1.29. 

<img width="1133" height="759" alt="Screenshot 2026-09-07 225308" src="https://github.com/user-attachments/assets/ed0ae493-086c-497f-b1e2-f85fb067d190" />



## Decide
There was a difference but a rather small one when it came to deflection. I performed my calculations with a deflection of .009 in where the simulation produced a simulation produced a deflection of .008 in. I think that the two were so similar because the simulation was a relatively basic one. The geometry was simple, so I wasn’t having to make any large assumptions when it came to hand solving. It also meant that using a fairly coarse mesh is fine as it won’t be losing a large amount of detail. 

I would trust the FEA more than my hand calculations as it goes into a significant amount more detail that what I did for my quick and simple hand calculations

<img width="443" height="178" alt="Screenshot 2026-09-07 232839" src="https://github.com/user-attachments/assets/d73b87a2-26cf-4cf9-994a-696398bc1b8c" />


After calculating the stress if a hole with a diameter of 0.060 in was drilled in the part I found that the part would fail as the maximum stress due to the new stress concentrator is around 69.5 ksi which is significantly higher than the yield stress.


## Communicate
This project helped me to learn how to do FEA in SolidWorks. It took me 3 hours.  
Cad:[Beam for FEA (SolidWorks Part)](./Beam%20for%20FEA.SLDPRT) 
