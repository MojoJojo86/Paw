# PDP - How to guide.

**External Beam Workspace**
1. Create a verification Plan and select PDP.
2. Create a new treatment course called PDP.
3. Set the SSD dependent on the machine the plan is for.
   100CM SSD = 5, 6, 8 and 9
   105CM SSD = Everything else
4. Use a single fraction and don't alter any of the overides.
5. Once the plan is created, rename the plan to PDP_Plan to avoid confusion.
6. Create a copy of the original plan and paste it into the PDP course, rename this Clinical_Copy.
7. In the Clinical_Copy plan, create a second reference point called Clinical_Copy and place it where the existing ref point is.
8. Make the Clinical_Copy ref point the primary and remove the original.

**Treatment Planning Workspace**
1. Making sure the PDP Plan is selected. Enter the following values into the bed parameters (Top -> Bottom): 15, 50, 0

**Plan Schedule Workspace**
1. On the 1 fraction for the PDP plan, schedule an image. Expand the appointment slot and for each field add an integrated image.

**Reference Points Workspace**
1. Planning Approve both the plans.





