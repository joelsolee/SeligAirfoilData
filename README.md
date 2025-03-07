# SeligAirfoilData
Airfoil data in Selig format

All airfoils, whereas created by author or sourced in the cloud, including hybrid airfoils for the transition from root to blade, are handled in Selig format and then saved as .dat files in this GitHub repository.

The Selig format is a commonly used plain-text file format for storing airfoil coordinates. It was popularized by Dr. Michael Selig in the University of Illinois. 

The first line includes the name or description of the airfoil and the subsequent lines, each line has two real numbers representing (x,y) coordinates of the airfoil in a given order. There is no explicit line indicating how many points there are.

- The first coordinate line is the trailing edge on the upper surface (x≈1,y≈0 if the airfoil is normalized to unit chord). 
 
- The list of points then progresses forward along the upper surface to the leading edge. 
 
- It then continues backward along the lower surface, returning to the trailing edge again.
- 
More info at https://m-selig.ae.illinois.edu/ads/coord_database.html 
