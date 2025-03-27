# Point Cloud for CIE

This repository holds the point cloud for the Center for Immersive Experiences in .pcd form. 

To view the Center for Immersive Experiences, please visit the link to view 360 images of the space: https://immersive.psu.edu/spaces/ 

Due to size limitations with GitHub, each PCD file was split into areas of the space: the main section of CIE, the entry/secondary area, and the theater. The theater has a complex ceiling, so this was done separately as well.  

Data has the following format:

  > \# .PCD v0.7 - Point Cloud Data file format
  VERSION 0.7
  FIELDS x y z rgb normal_x normal_y normal_z curvature
  SIZE 4 4 4 4 4 4 4 4

  TYPE F F F F F F F F

  COUNT 1 1 1 1 1 1 1 1

  WIDTH 250000

HEIGHT 1

VIEWPOINT 0 0 0 1 0 0 0

POINTS 250000

DATA ascii

2.69368 0.88485998 1.8999 1.6316809e-38 0 -0 1 0

2.6828699 0.86001998 1.90011 1.6960736e-38 0 -0 1 0

...
