# LiDAR-ROI-Mapping
Projects LiDAR point cloud data onto a 2D grid representation of a region of interest (ROI)

# Overview
Given a synthetic or real LiDAR point cloud, this script:
1. Filters points within a specified ROI (Region of Interest).
2. Projects these points onto a 2D bird’s-eye view (BEV) grid.
3. Encodes 3 features in the output image:
   1. Channel 0: Point count (density) per pixel.
   2. Channel 1: Maximum height per pixel.
   3. Channel 2: Average intensity per pixel.

The notebook helps visualize spatial LiDAR data in a grid format, useful for downstream perception and planning tasks in robotics or autonomous driving
