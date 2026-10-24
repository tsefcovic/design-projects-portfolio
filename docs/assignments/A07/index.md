# A7 – [Topic]

## Objective
Perform FEA simulations on the bracket that was used in the previous 2 assignments. 

## Analyze
| Metric | Design 1 | Design 2 | Design 3 |
| :--- | :--- | :--- | :--- |
| **Max Stress and Location** | $1.36 \times 10^9$ psi, just above the fillet on the vertical bar | $5.616 \times 10^4$ psi, just above the fillet on the vertical bar | $1.693 \times 10^4$ psi, on the bottom plate/fillet to the pin mount |
| **Max Deflection and Location** | 0.08 in, on the pin the strap goes on | 0.01 in, on the unsupported edge of the pin the strap attaches to | 0.0037 in, in the pin at the unsupported end |
| **Mass** | 1.21 lbs | 1.34 lbs | 1.33 lbs |
| **Safety Factor** | 0.2 | 0.5 | 1.89 |
| **Number of Elements** | Run 1: 9,819<br>Run 2: 12,700 | Run 1: 10,413<br>Run 2: 13,297 | Run 1: 11,197<br>Run 2: 13,742 |

Setting up the first simulation I left the geometry exactly as it was in the other assignments that I used this part for. I first ran the sim with the default mesh that SolidWorks provides that is a medium size. I then repeated with a significantly finer mesh size to see if my results were consistent with the variation of mesh size. My results were as I expected. Both were very similar to one another, and showed the weak point in the same area. This is what I expected to have happen as in my hand math, I made several assumptions that don’t take into account everything that this part will see from the load. 

<img width="914" height="544" alt="Screenshot 2026-10-24 152220" src="https://github.com/user-attachments/assets/203003ec-a133-4057-8bfc-9177eb1eb477" />
<img width="928" height="647" alt="Screenshot 2026-10-24 145331" src="https://github.com/user-attachments/assets/01a76ba7-d7c1-4d69-bc3c-dc639c8c284d" />
<img width="927" height="554" alt="Screenshot 2026-10-24 145301" src="https://github.com/user-attachments/assets/4c75233f-51ef-46c4-8739-06d22a29a14a" />

For the second iteration I increased the diameter of the pin mount in hopes that it would prevent it from reaching its failure point. I increased the diameter to 0.5”. Due to this increase I also had to increase the length of the pin in order to have enough room for the strap to sit on entirely. I then repeated the simulation process in the first design. While this did help rather significantly, it wasn’t enough to where there wouldn’t be failure. 

<img width="926" height="528" alt="Screenshot 2026-10-24 152200" src="https://github.com/user-attachments/assets/67925a07-db36-41e5-a2fb-fa7801d4f978" />
<img width="926" height="539" alt="Screenshot 2026-10-24 151531" src="https://github.com/user-attachments/assets/50ede677-1ad2-4bf8-9257-a605840033be" />
<img width="905" height="533" alt="Screenshot 2026-10-24 151517" src="https://github.com/user-attachments/assets/a2b49363-9e9c-47a1-a325-c5ee67dd9bcd" />

For the third iteration I once again increased the diameter of the pin mount. I was rather aggressive with the size increase as this was my last chance to get a geometry that worked for this assignment so I went to a 1” diameter. This meant once again changing the length of the pin that the strap goes on in order to make the strap fit on it. I also added several fillets across the part and decreased the thickness of the top plate as the previous simulations showed that it was significantly oversized for the load that it saw. I decreased the top plate to .25” thick. 

<img width="836" height="473" alt="Screenshot 2026-10-24 155522" src="https://github.com/user-attachments/assets/e4ee7322-35cd-4238-adb8-0a48c3559c69" />
<img width="887" height="635" alt="Screenshot 2026-10-24 155503" src="https://github.com/user-attachments/assets/52c9d371-5303-4025-adbe-24df1e350b06" />
<img width="914" height="544" alt="Screenshot 2026-10-24 152220" src="https://github.com/user-attachments/assets/fb059697-73c1-4ce9-bcca-c5d70bc50f19" />


## Decide
This proved to be a good decision as when I ran the sims stress was well below the yield stress. Between the two sims that I ran the stress was within 2.5% between the different mesh sizes. It was a similar case for displacement as there was a 3.2% difference between the two values that I got for it between the different mesh sizes. Both showed defections around .003” which is quite small. 

## Communicate
I learned how to apply geometry changes based on results of FEA simulations in order to produce a part that meets assigned criteria. I spent around 2.5 hours working on this assignment. 

CAD:

