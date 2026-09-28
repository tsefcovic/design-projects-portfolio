# A6 – [Topic]

## Objective

Create an easy to read and accurate drawing of the bracket that was designed in the last assignment.

## Analyze

  **Reworked Math**
  
The first thing that I did was rework some of the math that I did for the previous assignment. I did this because I did the last assignment in a rush, leading to work that I wasn't entirely happy with and led to me overlooking some factors that I wasn't happy with. 

<img width="278" height="107" alt="Screenshot 2026-09-26 123016" src="https://github.com/user-attachments/assets/8f5cb826-cdd8-43ab-b804-aa7533272488" />
<img width="341" height="53" alt="Screenshot 2026-09-26 131821" src="https://github.com/user-attachments/assets/11d04191-1010-4a7e-8f07-dd9973390bf0" />
<img width="140" height="77" alt="Screenshot 2026-09-26 131932" src="https://github.com/user-attachments/assets/d4dfb561-dbbb-481e-bcd7-931a06739ca6" />
<img width="241" height="136" alt="Screenshot 2026-09-26 131921" src="https://github.com/user-attachments/assets/97768327-f880-4cdc-80e9-e2f307c1c314" />
<img width="318" height="137" alt="Screenshot 2026-09-26 131844" src="https://github.com/user-attachments/assets/15bf2956-c383-441d-9a9b-27292e2a5745" />

## Decide
  **CAD Modeling**
  
I then modeled what I designed last week with some small edits into Solidworks. I used global variables so that if I found anything else that I wasn't happy with I could easily change the model. I added some fillets to the model as I have some experience with Solidworks and know that fillets often are used to help the manufacturability of a part. This is something that I hope to focus on as I am comfortable with the software itself but could use more practice with ensuring the components I design are actually able to be produced. 

<img width="1130" height="717" alt="Screenshot 2026-09-26 131519" src="https://github.com/user-attachments/assets/e4fcb69c-8d9b-4fb1-812a-39175f2d8cf8" />


**CAD Drawing**

I then used the model that I created to make a 3 view drawing of the part still utilizing Solidworks. Here I inserted different views and added dimensions to each as they applied to the model, until I was confident that I could reproduce the model with no other information if handed the drawing that was creating. 



## Communicate

**Lessons Learned**

For the Top flange with the strength requirement value of 0.79 inches. To input this to the model I utilized a global variable. This paired with the other calculated values being global variables, it was simple to make a model that is capable of updating to values being changed without having to go through the entirety of the model. 

I applied tighter tolerances to the entirety of the dimensions that impacted the mating surfaces between the bracket and the T beam. This would ensure that a sliding fit would be ensured on all parts within tolerance of a worst case scenario from both components. The rest of the model is significantly less tightly tolerance. This is because the rest of the dimensions don't affect the fit. This means that they can be less dimensionally accurate to the design but still function entirely as intended. This avoids the many problems that come along with having tight tolerances across the entirety of the part. If tolerances are tight across the entire part then production takes longer, and is significantly more expensive. 

I spent 2 hours working on this project. 

CAD: [docs/assignments/A06/Bracket.SLDPRT ](https://github.com/tsefcovic/design-projects-portfolio/blob/3f4e0199f093cb8b762515739579076767e11ad9/docs/assignments/A06/Bracket.SLDPRT)

Drawing: [docs/assignments/A06/Bracket.SLDDRW](https://github.com/tsefcovic/design-projects-portfolio/blob/ac80b2c52ab218d5bc6199a06900237a69ebf19a/docs/assignments/A06/Bracket.SLDDRW) 


