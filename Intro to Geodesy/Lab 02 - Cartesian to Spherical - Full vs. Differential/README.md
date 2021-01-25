# CE597 - Mapping Projection and Geometric Geodesy

## Lab No. 2 - Cartesian to Spherical: Full vs. Differential 

Submit a jupyter notebook that addresses below questions. The submitted notebook should be self executable within the current repository.

**Note: Assume the Earth is sphere and the radius of the Earth is 6371 km**

1. **(10/10 points)** Use the 11 points (NP, SP, PoB, 1 point per octant - total of 8 - of your choice) and print their cartesian coordinates in 4 columns in millimeter accuracy. For example, you can use "**Point_Name X(mmm.mmm) Y(mmm.mmm) Z(mmm.mmm)**" format. 
  - You may want to use *pandas.DataFrame.to_pickle()* and *pandas.DataFrame.read_pickle()* functions (https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_pickle.html#pandas.read_pickle).
  - When you save the cartesian coordinates from Lab 01, make it sure to include the pickle file in the repository.
2. **(10/10 points)** Compute spherical coordinates from the earth-fixed cartesian coordinates and print them in 8 columns.
  - "Point_Name Longitude (dd mm ss.sssss) Latitude (dd mm ss.sssss) Height (mm.mmm)" format
  - You should compute spherical coordinates from the cartesian coordinates. Do not use the original spherical coordinates used in Lab 01.
3. **(10/10 points)** Plot the 11 points on a simple map using *Xm = lambda (deg), Ym = psi (deg)*
  - Which unit do you use for this map?
  - Make it sure units for X and Y axis are the same.
  - Include grid lines that show boundary of each octant.
  - Label each point appropriately.
4. **(20/20 points)** Using the Jacobian matrix, calculate *dx, dy, dz* after adding +1.50000 arcsecond to longitude and latitude and +50 meter to the height. 
  - Print *dx, dy, dz* when calculated using the Jacobian approach
  - Print *dx, dy, dz* calculated in Lab 01.: **NOTE: It may seems that there difference between full and differential coordinate transformation differs at the mm level, but when you look at the difference between the full and differential transformation, it is indeed smaller than 1 mm.**
  - Compare them and discuss.
  - Repeat the comparison after adding +1 degree to longitude and latitude and +50 meter to the height. What do you see?
  - **Great discussion!**
  
# Final score: 10/10
