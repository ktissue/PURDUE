# CE597 – Intro to Geodesy

## Lab 9 - Dissimilar Coordinate Transformation for Ellipsoidal Coordinates

We derived formulas for dissimilar coordinate transformation between Ellipsoidal and geocentric Cartesian coordinates. However, as I mentioned in the lecture, deriving closed form formulas for dissimilar coordinate transformation from the geocentric Cartesian coordinates to the Ellipsoidal coordinates is too complicated and not practical.
In lab 9, we will perform the dissimilar coordinate transformation from the geocentric Cartesian coordinates to the Ellipsoidal coordinates – based on NAD83 - using numerical approach.  
You will use 8 points of your choice (one point from each octant) and Q 94 from the NGS data sheet.

1.	**(10/10points)** Make an input file (9 points: 8 points of your choice + Q 94) for your Python program.
The input file must follow the below format (8 columns with header, and each column is separated by comma).
Make it sure to include this input file in the repository when you submit your lab.

| pid | Lon (deg) | Lon (min) | Lon (sec) | Lat (deg) | Lat (min) | Lat (sec) | H (m) |
|:----|:----------|:----------|:----------|:----------|:----------|:----------|:------|
| ... | ...       | ...       | ...       | ...       | ...       | ...       | ...   |
| ... | ...       | ...       | ...       | ...       | ...       | ...       | ...   |

2.	**(20/20points)** From the input file generated from 1,
print a table (Ellipsoidal coordinate → geocentric Cartesian coordinates) using below format
for 9 points (8 points of your choice + Q 94).

| pid | Lon (deg) | Lon (min) | Lon (sec) | Lat (deg) | Lat (min) | Lat (sec) | H (m) | X (m) | Y (m) | Z (m) |
|:----|:----------|:----------|:----------|:----------|:----------|:----------|:------|:------|:------|:------|
| ... | ...       | ...       | ...       | ...       | ...       | ...       | ...   | ...   | ...   | ...   |
| ... | ...       | ...       | ...       | ...       | ...       | ...       | ...   | ...   | ...   | ...   |

3.	**(20/20points)** Using the x,y,z coordinates (exact value) that are calculated from 2,
perform dissimilar coordinate transformation (geocentric Cartesian coordinates → Ellipsoidal coordinates)
using the numerical approach mentioned in the lecture, and print a table using below format for the 9 points.

| pid | X (m) | Y (m) | Z (m) | Lon (deg) | Lon (min) | Lon (sec) | Lat (deg) | Lat (min) | Lat (sec) | H (m) |
|:----|:------|:------|:------|:----------|:----------|:----------|:----------|:----------|:----------|:------|
| ... | ...   | ...   | ...   | ...       | ...       | ...       | ...       | ...       | ...       | ...   |
| ... | ...   | ...   | ...   | ...       | ...       | ...       | ...       | ...       | ...       | ...   |

4.	**(20/20points)** Using the x,y,z coordinates (rounded at the mm level) that are calculated from 2,
perform dissimilar coordinate transformation (geocentric Cartesian coordinates → Ellipsoidal coordinates)
using the numerical approach mentioned in the lecture, and print a table using below format for the 9 points.

| pid | X (m) | Y (m) | Z (m) | Lon (deg) | Lon (min) | Lon (sec) | Lat (deg) | Lat (min) | Lat (sec) | H (m) |
|:----|:------|:------|:------|:----------|:----------|:----------|:----------|:----------|:----------|:------|
| ... | ...   | ...   | ...   | ...       | ...       | ...       | ...       | ...       | ...       | ...   |
| ... | ...   | ...   | ...   | ...       | ...       | ...       | ...       | ...       | ...       | ...   |

5.	**(10/10points)** Compare the input Ellipsoidal coordinates from 2 with the calculated Ellipsoidal coordinates from 3 and 4, and discuss.
Include discussion on your choice of the epsilon value for the numerical approach.

## Score: 10
