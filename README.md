# Product Recognition on Store Shelves
Object detection techniques based on computer vision can be deployed in super market scenarios for the
creation of a system capable of recognizing products on store shelves.

For each type of product displayed in the 
shelf the system should report:
1. Number of instances.
2. Dimension of each instance (width and height of the bounding box that enclose them in pixel).
3. Position in the image reference system of each instance (center of the bounding box that enclose 
them in pixel).

## Step A - Multiple Product Detection:
Develop an object detection system to identify single instance of products given: one reference image for 
each item and a scene image.


## Step B - Multiple Instance Detection:
In addition to what achieved at step A, the system should now be able to detect multiple instance of the 
same product.
