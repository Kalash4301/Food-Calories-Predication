# Food-Calories-Predication


#### Dataset 
We used Food dataset name ECUSTFD which contains 19 kinds of food.

Steps:


#### Step 1 :Image Acquisition Input Image Top View ,  Side View 

#### Step 2 :Pre-processing

#### Step 3 :Object Detection (Faster R-CNN)

#### Step 4 :Image Segmentation (GrabCut)

#### Step 5 :Volume Estimation
The scale’s size is corresponded to the object’s size  to get the actual image size.Different volume estimation formula will be selected for different types of food, based on their shapes such as ellipsoid, column, irregular.

#### Step 6 :Calorie Estimation 
Mass    =   Density (g/cm³) * Volume (cm³)
Calories = Calories per gram (Kcal/g)* Mass(g)

