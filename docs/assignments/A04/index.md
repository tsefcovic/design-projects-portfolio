# A4 – [Topic]

## Objective
Design a motor mount around both stress and strain constraints to withstand a 300 N force at the end of the shaft of the motor, while maintaining a safety factor of 3. 

## Analyze
First I based everything around the motor that was provided. All the dimensions are in mm.

<img width="521" height="208" alt="Screenshot 2026-09-14 182859" src="https://github.com/user-attachments/assets/9e6d8cf2-aadf-45b5-94ce-b6895a3c69a3" />

I then researched the different material options. I am allowed to use PLA, PETG, or ABS. PLA by far had the highest yield stress, however it's modulus of elasticity is very low. This is not a preferred quality for this application. As this would make keeping deflection to a minimum very difficult. That leaves PETG or ABS. Both of which have similar properties from the datasheet that was provided, so I went with PETG. As it seemed to have slightly more preferable material qualities for the task at hand. 

## Decide

I started by sketching the rough shape that I wanted the mount to be. I then used this to determine the height and width. With both of these values solved I will be able to solve for the thickness that each member needs to be in order to meet the design constraints. 

<img width="258" height="335" alt="Screenshot 2026-09-14 182445" src="https://github.com/user-attachments/assets/193dbb29-e70d-4c1a-a3d0-8cd7dc2c6997" />

**Feature 1:**

I started by calculating the thickness needed to meet the stress requirements. 

Knowns: 300 N force applied to the end of the motor shaft that is 16 mm long. The modulus of elasticity of PETG is 2300 MPa and the yield stress is 50 MPa. Max deflection of 0.03 mm.

Unknowns: Thickness of the member. 

I went through the beam calculations that we covered in class and plugged in values that were provided for both the stress and deflection calculations. 

**Feature 2**

Then I calculated the thickness using the same process I used for Feature 1. 

Knowns: 300 N force applied to the end of the motor shaft that is 16 mm long. The modulus of elasticity of PETG is 2300 MPa and the yield stress is 50 MPa, the member is 35 mm long

Unknowns: Thickness of the member.

<img width="566" height="371" alt="Screenshot 2026-09-14 182508" src="https://github.com/user-attachments/assets/3dc91490-47df-47f3-bb1c-28c89399d112" />

Due to the fact that deflection of member 2 was the larger of the two values of the member that I solved for, it is what I used in order to meet both requirements. While I used the number that I solved for stress on member 1 as it was the larger of the two values. 

## Communicate
Through this assignment I learned how to perform basic calculations for a cantilever beam. This assignment took me 3 hours to complete. 
