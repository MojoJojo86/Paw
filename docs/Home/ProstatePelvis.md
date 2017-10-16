# Prostate and Pelvis

### 1. PTV Margins and Contouring

* #### **PTV3** i.e. 74Gy
  > CTVp - Contour the Prostate Only
  
  > PTVp - Grown from the **CTVp** with a margin of 0.5cm

* #### **PTV2** i.e. 71Gy
  > CTVpsv - Contour Prostate and Seminal Vesicles
  
  > PTVcsv - Grown from the **CTVpsv** with a margin of 1.0cm (0.5mm can be used at clinicians discretion)

* #### **PTV1** i.e. 55Gy
  > CTVn -
  
  > PTVn - Grown from the CTVn by 0.7mm
  
---

* Bowel should extend atleast 1cm sup of **PTVn**

* When creating 71Gy-74Gy Structure, use boolean as dose levels don't vary much

* When creating 55Gy-71Gy, Crop 5mm between the structures to allow for the difference in dose

### 2. OAR Contouring

##### ***Avoid if the overlap looks fine.***
If struggling with bowel and rectal doses it is possible to create the following structures.

  1. ***Rectum_in_74***
     > * Boolean Rectum and 74Gy structure to leave an overlap of these. 
     > * Apply a mean objective of 98% Dose and a Priority of 40.
  2. ***Rectum_in_71***
     > * Boolean Rectum and 71Gy structure to leave an overlap of these. 
     > * Apply a mean objective of 98% Dose and a Priority of 40.
  3. ***Bowel_in_55***
     > * Boolean Bowel and 55Gy structure to leave an overlap of these.
     > * Apply a mean objective of 98% Dose and a Priority of 40.
  
  
![ProstateDoses](_media/prostdoses.png)
  
