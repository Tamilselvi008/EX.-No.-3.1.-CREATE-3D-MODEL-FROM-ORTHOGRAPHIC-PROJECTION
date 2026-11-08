# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:14-10-2026

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

## 2. Draw the rectangular profile

1. Open **Create > Line** and draw a horizontal line through the origin.
 <img width="1920" height="1011" alt="Screenshot (313)" src="https://github.com/user-attachments/assets/22761027-e133-4f12-8c69-34296dd8eddf" />

2. Use **Sketch Dimension** to set the line to **40 mm**. This defines the outer width.
3. From each endpoint, draw vertical lines **52 mm** high, then connect their top endpoints to make the outer rectangle.
4. Choose **Line** again and draw the inner edges of the two arms, each **11 mm** from its corresponding outer edge.
5. Draw a horizontal line **11 mm** above the outer rectangle’s bottom edge to define the top of the crosspiece.
6. Draw the top of the opening between the inner arm edges, then dimension the opening width to **18 mm**.
7. Draw the remaining interior lines, aligning them with the inner arm edges and the top of the crosspiece.
8. Choose **Sketch > Modify > Trim**.
9. Click **Finish Sketch**.
<img width="1920" height="1024" alt="Screenshot (314)" src="https://github.com/user-attachments/assets/a18005a7-c119-4c06-804d-307c98152ffe" />

## 3. Extrude the bracket body

1. Select **Solid > Create > Extrude**.
2. Check the preview to ensure the bracket extrudes in the intended direction.
3. Set **Operation** to **New Body**.
4. Click **OK**.
<img width="1920" height="1010" alt="Screenshot (315)" src="https://github.com/user-attachments/assets/8054d968-ac42-429f-90ed-687c450dbffe" />
<img width="1920" height="1004" alt="Screenshot (316)" src="https://github.com/user-attachments/assets/77e66d63-f9bc-4ce7-8fa9-fecf468fcb46" />

## 4. Add the projecting shaft to the base

1. Orbit the model and select the outer face of the bottom crosspiece.
2. Choose **Create Sketch**.
3. Select **Create > Circle > Center Diameter Circle**.
4. Click the center of the crosspiece face to place the circle center.
5. Set the circle’s radius to **9 mm**. If Fusion requests a diameter, enter **18 mm**.
<img width="1920" height="1010" alt="Screenshot (317)" src="https://github.com/user-attachments/assets/96170c2a-5ca4-4008-9feb-c135a3f53051" />

6. Click **Finish Sketch**.
7. Select **Solid > Create > Extrude**.
8. Select the circular profile.
9. Enter **32 mm** for the extrusion distance, directed outward from the bracket.
10. Set **Operation** to **Join** so the shaft attaches to the crosspiece.
11. Click **OK**.
    <img width="1920" height="1019" alt="Screenshot (318)" src="https://github.com/user-attachments/assets/d62ff6bf-d018-4ada-8ad3-2b612c716794" />

## 5. Fillet the ends of both arms

1. Select **Modify > Fillet**.
2. Select the outer edge or edges at the free end of the first arm.
3. Enter a fillet radius of **8 mm**.
4. Check the preview. If the fillet fails or rounds the wrong edges, cancel and select only the end edges shown as rounded in the drawing.
5. Repeat for the other arm, or select the corresponding edges on both arms in the same Fillet command.
6. Click **OK**.
7. <img width="1920" height="1024" alt="Screenshot (319)" src="https://github.com/user-attachments/assets/cd265e59-3890-447e-b418-cee68a4e0a1a" />
<img width="1920" height="1008" alt="Screenshot (320)" src="https://github.com/user-attachments/assets/9655a986-141a-4522-9833-a2e9efe20220" />

## 6. Cut the hole through the upper arms

1. Rotate the model to view the side face of the right arm.
2. Select that face and choose **Create Sketch**.
3. Select **Create > Circle > Center Diameter Circle**.
4. Draw a circle on the arm face at the hole location shown in the drawing.
5. Set the hole radius to **8 mm**. If Fusion requests a diameter, enter **16 mm**.
<img width="1920" height="1022" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/82c40751-ea54-48d3-82a1-517a74717137" />

6. Click **Finish Sketch**.
7. Select **Solid > Create > Extrude**.
8. Select the circular profile.
9. Set **Operation** to **Cut**.
10. Set the extent to **Through All** if the cut should pass completely through the selected arm.
11. Check the preview to make sure the cut goes through the arm, then click **OK**.
<img width="1920" height="1031" alt="Screenshot (322)" src="https://github.com/user-attachments/assets/57384d6d-0d9e-45ea-a245-d5ec61f0e9d6" />

## 7. Check the finished model

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
3. Save the design.
<img width="1920" height="1001" alt="Screenshot (311)" src="https://github.com/user-attachments/assets/a690ce92-4ff4-46ea-a28e-92fff41f1fb6" />


## 8. Create the drawing

1. Save the model.
2. Choose **Design > Drawing > From Design**.

<img width="1920" height="1026" alt="Screenshot (324)" src="https://github.com/user-attachments/assets/5f2614cd-9c38-42ab-b425-e6251094e6fc" />

3. Set the drawing standard, units, and sheet size.
4. Place a base view that clearly shows the U-shaped bracket profile.
5. Add projected top and side views.
6. Add an isometric view.
7. Fill in the title block with the drawing name, scale, date, and other required details.
8. Save the drawing.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="1920" height="1017" alt="Screenshot (312)" src="https://github.com/user-attachments/assets/cbac36ad-b062-418f-b63f-57b8dc1e0c09" />

## RESULT:
Thus, 3D model is created from orthographic projection.
