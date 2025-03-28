# ICDS Challenge! 
## Goal
The goal is to provide object detection using a Point Cloud of the Center for Immersive Experiences. 
## Prize! 
The winning team will receive the following endorsement prize package:​
1. ICDS developed a press release on the winning team’s submission from HackPSU weekend to be published on the ICDS website and other Penn State media channels.​
1. Social media promotion on ICDS-branded channels for the winning team’s submission. ​
1. LinkedIn endorsement referencing the winning team’s submission.​
1. A presentation invite to a future ICDS Lunch and Learn (free lunch!).

This repository holds the point cloud for the Center for Immersive Experiences in .pcd form. 
## 360 Images
To view the Center for Immersive Experiences, please visit the link to view 360 images of the space: https://immersive.psu.edu/spaces/ 
## Data
Due to size limitations with GitHub, each PCD file was split into areas of the space: the main section of CIE, the entry/secondary area, and the theater. The theater has a complex ceiling, so this was done separately as well.  

> \# .PCD v0.7 - Point Cloud Data file format\
VERSION 0.7\
FIELDS x y z rgb normal_x normal_y normal_z curvature\
SIZE 4 4 4 4 4 4 4 4\
TYPE F F F F F F F F\
COUNT 1 1 1 1 1 1 1 1\
WIDTH 250000\
HEIGHT 1\
VIEWPOINT 0 0 0 1 0 0 0\
POINTS 250000\
DATA ascii\
2.69368 0.88485998 1.8999 1.6316809e-38 0 -0 1 0\
2.6828699 0.86001998 1.90011 1.6960736e-38 0 -0 1 0\
...
## Objects in the Space
* Chairs, tables, monitors, a projection screen, projectors, TVs, computers, and misc objects.

## QR Code
![image](https://github.com/user-attachments/assets/3d6e905f-1e80-4aa7-bd2d-988b780a9184)

## Merging the Data Set

Here is a Google Colab notebook to merge all data points to create CIE: 

https://colab.research.google.com/drive/1uSnbEDQ4gphZQ24yHF4NsbFxbi0Pqujb?usp=sharing 
