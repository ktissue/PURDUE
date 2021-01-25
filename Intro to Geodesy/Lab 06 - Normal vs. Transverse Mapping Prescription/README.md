# CE597 – Intro to Geodesy

## Lab 06 - Normal vs. Transverse Mapping Prescription

In Lab 3, 4, and 5, we employed mappings in the so-called normal aspect. In this lab, you will plot again the three mappings in the transverse aspect by making the meridian that goes through your PoB, **a new equator**, in the transverse system.

1.	**(5/5 points)** Plot grid line, coast line, and your PoB using normal aspect. You need to provide 3 maps (PC, SF, MC) here. Use only points that are between -80° and 80° latitude for normal MC mapping.
  - Make it sure to provide spherical coordinates of your PoB in DMS format in the code.

2.	**(5/5 points)** Describe in detail the mathematics you used to “make” your PoB meridian to the new equator.

3.	**(15/20 points)** Plot grid line, coast line, and your PoB using transverse aspect. You  need to provide another 3 maps (PC, SF, M) here. Use only points that are between -80° and 80° latitude (after the transformation) for transverse MC mapping.
  - **NOTE: In your all transverse maps, it seems that your X and Y are reversed. Even in transverse aspect, longtude ranges from -180 to 180 and latitude ranges from -90 to 90, so X should be wider than Y?**

4.	**(18/20 points)** For all maps (3 normal and 3 transverse), select a 15°x15° “square” ABCD that contains your POB. Use three lines: EW(AB), NS(AD), NE(AC), e.g. between two “grid” points forming the intersections between meridians and parallel circles. Calculate the scales (NS, NE, EW direction) (representative fraction, e.g. 1:2,000,000) of all maps. Show your measurements in the map, and report in your discussion, too. Calculate the real world distances and the scales inside your code.
  - **NOTE: Although your map is rotated 90 degree, it seems that your calculation is at least consistent**

5.	**(8/10 points)** Generate two tables: one for normal aspects and the other for transverse aspects. Each table must have seven columns: Direction (NS, NE, EW), Scales PC, %, Scales SF, %, Scales M, %. Set your NS scale to 100 %.
  - **NOTE: The same comment as previous one. Numbers do not match with my calculation but seems that it is because your X and Y are not in correct order.**

6.	**(10/10 points)** Discuss the scales using the table generated from 5. What do you (not) like about them as an engineer/surveyor?
  - **NOTE: Great discussion. I would like to comment on one of your statement, "one thing I do not like about the transverse aspect scale behavior, and with the Transverse Mercator specifically, is that the map ABCD does not appear as a perfect square like it does in the normal aspect". Is ABCD in the real world a perfect square?**

## Final score: (5+5+15+18+8+10)/70 = 8.71
