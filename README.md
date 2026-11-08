# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
## 1. Set up the design

1. Open Fusion 360 and create a **New Design**.
2. In the Browser, expand **Document Settings**.
3. Set the units to **mm**.
4. Save the design with an appropriate name.
5. In the **Solid** workspace, select **Create Sketch**.
<img width="1920" height="1028" alt="Screenshot (293)" src="https://github.com/user-attachments/assets/877f9172-359a-439f-ad77-4138b866c1f1" />

## 2. Draw the three-rectangle bracket profile

1. Open **Create > Rectangle** and choose **Center Rectangle**.
2. Click the origin to center the first rectangle.
3. <img width="1920" height="1019" alt="Screenshot (297)" src="https://github.com/user-attachments/assets/f398393b-22a9-45d2-b4a8-f508b2f13797" />

4. Draw the outer rectangle, then use **Sketch Dimension** to set:
   - Overall width: **40 mm**
   - Overall height: **52 mm**
5. Choose **Center Rectangle** again and draw the inner opening rectangle in the upper part of the outer rectangle.
6. Dimension the opening width to **18 mm**.
7. Position the opening so the two arms and bottom crosspiece are each **11 mm** thick:
   - Left arm: **11 mm**
   - Right arm: **11 mm**
   - Bottom crosspiece: **11 mm**
8. Draw the third rectangle to define the remaining interior opening area. Align its sides with the intended inside edges of the arms and its bottom edge with the top of the crosspiece.
9. Choose **Sketch > Modify > Trim**.
10. Click the line segments inside the U-shaped opening that should be removed. Keep the outer boundary and the inner edges that form the arms and crosspiece.
11. <img width="1920" height="1011" alt="Screenshot (298)" src="https://github.com/user-attachments/assets/a3218771-9b1e-4e78-974c-3c7ed03df62a" />
  
14. Click **Finish Sketch**.
<img width="1920" height="1004" alt="Screenshot (299)" src="https://github.com/user-attachments/assets/01c49810-8b6e-479b-82b0-b405d49e0a11" />

## 3. Extrude the bracket body

1. Select **Solid > Create > Extrude**.
2. Click the shaded U-shaped profile.
3. Enter the bracket depth from the drawing. This dimension is not readable in the screenshot.
4. Check the preview to ensure the bracket extrudes in the intended direction.
5. Set **Operation** to **New Body**.
6. Click **OK**.
<img width="1920" height="1020" alt="Screenshot (300)" src="https://github.com/user-attachments/assets/e9000af6-b831-4a36-8414-440eb0cfc44f" />
<img width="1920" height="1008" alt="Screenshot (301)" src="https://github.com/user-attachments/assets/839a451b-8859-4e34-9ee3-3aa1cae5cc6d" />

## 4. Add the projecting shaft to the base

1. Orbit the model and select the outer face of the bottom crosspiece.
2. Choose **Create Sketch**.
3. Select **Create > Circle > Center Diameter Circle**.
4. Click the center of the crosspiece face to place the circle center.
5. Set the circle’s radius to **9 mm**. If Fusion requests a diameter, enter **18 mm**.
6. <img width="1920" height="1021" alt="Screenshot (302)" src="https://github.com/user-attachments/assets/1be472a2-a314-487e-ba9d-6f7930d77127" />

8. Click **Finish Sketch**.
9. Select **Solid > Create > Extrude**.
10. Select the circular profile.
11. Enter **32 mm** for the extrusion distance, directed outward from the bracket.
12. Set **Operation** to **Join** so the shaft attaches to the crosspiece.
13. Click **OK**.
<img width="1920" height="1029" alt="Screenshot (303)" src="https://github.com/user-attachments/assets/c0ad12e5-1d3e-4fc2-9655-e0f16aaf9922" />

## 5. Cut the hole through the upper arms

1. Rotate the model to view the side face of the right arm.
2. Select that face and choose **Create Sketch**.
3. Select **Create > Circle > Center Diameter Circle**.
4. Draw a circle on the arm face at the hole location shown in the drawing.
5. Set the hole radius to **8 mm**. If Fusion requests a diameter, enter **16 mm**.
<img width="1920" height="1022" alt="Screenshot (304)" src="https://github.com/user-attachments/assets/a833e090-fbaf-47f1-a385-6b74c4e6e4f3" />

7. Click **Finish Sketch**.
8. Select **Solid > Create > Extrude**.
9. Select the circular profile.
10. Set **Operation** to **Cut**.
11. Set the extent to **Through All** if the cut should pass completely through the selected arm.
12. Check the preview to make sure the cut goes through the arm, then click **OK**.
<img width="1920" height="1015" alt="Screenshot (305)" src="https://github.com/user-attachments/assets/87e13f22-d273-4da3-975c-c99e2e90d1e8" />

## 7. Fillet the ends of both arms

1. Select **Modify > Fillet**.
2. Select the outer edge or edges at the free end of the first arm.
3. Enter a fillet radius of **8 mm**.
4. Check the preview. If the fillet fails or rounds the wrong edges, cancel and select only the end edges shown as rounded in the drawing.
5. Repeat for the other arm, or select the corresponding edges on both arms in the same Fillet command.
6. Click **OK**.
<img width="1920" height="1015" alt="Screenshot (306)" src="https://github.com/user-attachments/assets/dfdd269f-6880-48b4-9ae8-ee97e4043c7e" />

## 8. Check the finished model

1. Orbit the model and compare it with the isometric view.
2. Confirm:
   - Overall bracket profile: **40 mm wide × 52 mm high**
   - Opening width: **18 mm**
   - Arm thickness: **11 mm**
   - Bottom crosspiece thickness: **11 mm**
   - Shaft radius: **9 mm**
   - Shaft projection: **32 mm**
   - Arm-hole radius: **8 mm**
   - Rounded arm ends: **R8**
4. Save the design.
<img width="1920" height="1015" alt="Screenshot (309)" src="https://github.com/user-attachments/assets/0875ffbf-1dd7-440a-80d2-5450ad7e5c6f" />


## 9. Create the drawing

1. Save the model.
2. Choose **Design > Drawing > From Design**.
3. <img width="1920" height="1013" alt="Screenshot (308)" src="https://github.com/user-attachments/assets/b53f1465-4a6c-44c3-8186-bc9ad1575cbe" />

4. Set the drawing standard, units, and sheet size.
5. Place a base view that clearly shows the U-shaped bracket profile.
6. Add projected top and side views.
7. Add an isometric view.
9. Fill in the title block with the drawing name, scale, date, and other required details.
10. Save the drawing.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="1920" height="1010" alt="Screenshot (295)" src="https://github.com/user-attachments/assets/1b0107aa-2fc6-4e7e-9f1b-a4702f8713de" />

## RESULT:
Thus, 3D model is created from orthographic projection.
