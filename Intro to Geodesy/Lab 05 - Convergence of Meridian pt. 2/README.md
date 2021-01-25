# CE597 - Mapping Projection and Geometric Geodesy

## Lab No. 5 - Another way of taking care of convergence

Submit a jupyter notebook that addresses below questions. The submitted notebook should be self executable within the current repository.

**Note: Assume the Earth is sphere and the radius of the Earth is 6371 km**

1. **(5/5 points)** Select the same original 11 points on the globe as in Lab 1 and Lab 2 - one point in each octant, NP, SP, and your PoB - then print 2 tables.
  - First table should contain spherical coordinates in DMS format (8 columns) with millimeter accuracy.
  - Second table should contain cartesian coordinates in meter format (4 columns) with millimeter accuracy.
  - Each table should contain header.
  - Each table should contain **name** column.
2. **(7/10 points)** Plot 11 points, coast line, grid lines using 3 different mapping prescriptions.
  - PC: **Unit of the map?**
  - SF: **Unit of the map?**
  - Mercator: For this mapping, make it sure to limit your latitude to +/- 75 degrees.: **Unit of the map?**
3. **(20/20 points)** Select the 15 x 15 degree square of meridian and parallel circle that encloses your PoB, and call this square ABCD. Through measurements and calculation, determine the scale of 3 mapping prescriptions, i.e., the representative fraction of your map for the lines AB, AC, and AD. Show detailed calculations and measurements in the RW and MW.
4. **(18/20 points)** What is your final conclusion about the scale of the 3 mapping prescription? How are these mappings doing as far as preserving angles? Also does the scale behavior improve from Lab No. 3 to No. 4 to No. 5?
  - **NOTE: Your rating for scale behavior is PC, MC, then SF. Why would you rank that way? I see more scale variation from PC than Mercator? We are not comparing scale from two different location. We are just comparing in one location with different direction, so I don't think your statment "if you leave above 75 degrees latitude or below -75 degrees latitude, the Meractor mapping prescription is probably the worst in terms of scale" will be valid.**

## Score: (5+7+20+18) / 55 = 9.1
