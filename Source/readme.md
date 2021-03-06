	
Each of these tests provides a basic feature of the data. To run:
```
cd path/to/RGBD-Dog/Source
python test_TESTNAME.py
```

Code for importing the animated skeleton and mesh is located in Source/Blender. Code for a GUI to visualise the entire sequence of each motion is included in Source/Data_Viewer_GUI.

### test_3dReconstruction: 
Reconstruct the points in the Kinect depth image

![RGBD-Dog](/figs/test_3dReconstruction.png)
### test_3dSkeletonAndMarkers: 
Plot the skeleton and markers in 3D space

![RGBD-Dog](/figs/test_3dSkeletonAndMarkers.png)
### test_mask: 
Apply the mask to the image

![RGBD-Dog](/figs/test_mask.png)
### test_projection: 
Project either the skeleton or marker positions onto the image

![RGBD-Dog](/figs/test_projections.png)
### test_skinning: 
Apply the animation from a bvh file to the dog

![RGBD-Dog](/figs/test_skinning.png)

### test_meshToSmalMesh
Convert the resulting skinned mesh to the SMAL representation and calculate 3D joint locations

![RGBD-Dog](/figs/test_SMAL.png)

Each file contains variables to edit before running. Please see the file itself.

