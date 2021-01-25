# CE597 - Mapping Projection and Geometric Geodesy

## Lab No. 1 - Spherical to Cartesian 

Submit a jupyter notebook that addresses below questions. The submitted notebook should be self executable within the current repository.

**Note: Assume the Earth is sphere and the radius of the Earth is 6371 km**

1. (using pandas) Select 11 points (NP(north pole), SP(south pole), PoB(place of brth), select at least 1 point from each octant - total of 8 - of your choice) and print their coordinates in 8 columns (in spherical coordinate system). For example, you can use "**(1)Point_Name Longitude ((2)dd (3)mm (4)ss.sssss) Latitude ((5)dd (6)mm (7)ss.sssss) Height ((8)mm.mmm)**" format. (9/10 points)
  - When you create the 8 points, use DMS format. (2/3 points)
    - Don't save numbers as string. It is not the most efficient way of storing numbers, and you may end up spending much more memory and storage space to store the same numbers.
    - "Tane Mahuta" and "Sydney Opera House" are in the same octant.
  - The DMS format coordinates should be the **ONLY** input to your program.
  - Report longitude, latitude, and height such that you report these quantities with millimeter accuracy. (3/3 points)
  - The printed table should have an appropriate header. (1/1 point)
  - In your discussion(within jupyter notebook), show how you obtained the appropriate number of significant digits. (3/3 points)
2. Calculate earth fixed geocentric cartesian coordinates from the spherical coordinates and print them **nicely**. (7/10 points)
  - The printed table should have an appropriate header.
  - Do not round off numbers in the middle of calculation. When you're convering DMS to decimal degrees, you rounded off numbers and that makes cartesian coordinates do not match with my calculation.
3. (spherical)After adding +1.50000 arcsecond to longitude and latitude and +50 meter to the height, re-calculate the cartesian coordinates and print them **nicely**. (7/10 points)
  - Again, rounding off numbers in the middle of calculation affects here as well. For example, NP and SP, after moving 1.5 arcseconds in longitude and latitude, x,y coordinates shouldn't be zero!
4. Compute the cartesian coordinate difference (*dx, dy, dz*) between 2) and 3), then compare them to the spherical coordinate difference. What do you see? (Explain why they are different: what is the decidding factor? is it a function of lambda, is it a function psi, is it a function of height? you decide.) (7/10 points)
  - Good observation but it would have been even better if you could support your observation with figures.
  
  # Grading
  
  Final score: (9 + 7 + 7 + 7) / 40 = 7.5/10.0
