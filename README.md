# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date :

## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

step 1:


Main body (rounded profile)
Open Fusion 360 and select Design → Solid workspace.
Click Create Sketch and select the Front (XZ) plane.
Choose Sketch → Line and draw the main rectangular portion of the side profile with a height of 32 mm.
Maintain a distance of 36.28 mm from the centre of the rounded end to the rear shoulder.
Choose Sketch → Arc → 3-Point Arc and construct the semicircular front portion with a radius of 16 mm (R16).
<img width="517" height="395" alt="WhatsApp Image 2026-11-25 at 8 23 33 AM" src="https://github.com/user-attachments/assets/582b25b6-4e37-412a-b9f5-081430830454" />
Connect the arc to the straight edges to complete the closed side profile.
Click Finish Sketch.
Select Extrude, choose the closed profile and enter 40 mm as the extrusion distance.
Press Enter to create the main solid body.

Step 2:

Create the central gap between the fork arms
Select the top face of the main body and click Create Sketch.
Choose Sketch → Rectangle → Two-Point Rectangle.
Draw a rectangular profile along the centre of the body.
Set the width of the rectangle to 18 mm and position it equally on both sides, leaving 11 mm on each side of the 40 mm overall width.
Extend the rectangular profile from the front end up to a point 11 mm before the rear shoulder.
Click Finish Sketch.
Select Extrude, select the rectangular profile and choose Cut as the operation.
Set the cut distance to 32 mm so that the central material is removed through the entire height.
Press Enter. This creates two parallel fork arms connected by the rear portion.

Step 3:


Create the circular holes
Select the side face of the fork body and click Create Sketch.
Choose Sketch → Circle → Center Diameter Circle.
Place the centre of the circle at the centre of the rounded end.
Enter 16 mm as the diameter (Ø16).
Click Finish Sketch.
Select Extrude, choose the circular profile and set the operation to Cut.
Extend the cut through the full 40 mm width of the body.
Press Enter to create the circular holes through both fork arms.

Step 4:


Create the rear cylindrical shaft
Select the rear vertical face of the connecting portion and click Create Sketch.
Choose Sketch → Circle → Center Diameter Circle.
Place the circle at the centre of the rear face.
Enter 18 mm as the diameter (Ø18).
Click Finish Sketch.
Select Extrude and choose the circular profile.
Enter 32 mm as the extrusion distance, extending outward from the rear face.
Select Join as the operation to connect the cylindrical shaft to the main body.
Press Enter to complete the shaft.

Step 5:

Final inspection and drawing
Use the Orbit tool to inspect the component from different directions.
Check that the two fork arms have a thickness of 11 mm each and a central gap of 18 mm.
Verify the circular hole diameter of 16 mm and the shaft diameter of 18 mm.
Confirm the overall width of 40 mm, height of 32 mm and shaft length of 32 mm.
Apply the required appearance and save the completed model.
Generate the front, top and end views along with the isometric view using the drawing workspace.





## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198523331-05ace360-502b-4569-b9b4-31c60e3cd554.png)

Output:

<img width="1030" height="707" alt="WhatsApp Image 2026-11-25 at 8 18 09 AM" src="https://github.com/user-attachments/assets/5079a1be-9420-48c2-a813-ce1c24ad9e7e" />

## RESULT: 
Thus, the 3D model is created from given isometric drawing.


