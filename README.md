# NZDEM-HGT-30

New Zealand Digital Elevation Model (DEM) in 1 arc-second (~30 meter) HGT/SRTM1 format. 

I created this dataset back around 2010. It was intended as a resource for the PC gaming community (train, plane, ship simulators...), graphics artists, or anyone who can apply the data safely. At that time NASA had not released 1 arc-second (30 meter) SRTM data for New Zealand or for any country other than the United States. I was able to create a Digital Elevation Model (DEM) by interpolating the contour lines from the Land Information New Zealand (LINZ) topographical database. I wrote [custom software](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/ConversionApp.jpg?raw=true) to perform the calculations which took (from memory) two 6 core machines about 1 week to complete. This resulted in a grid of evenly spaced points 10 meters apart. From that base grid I interpolated the points to get the 1 arc-second HGT data. Information on the HGT (STRM1) format can be found [here](https://dds.cr.usgs.gov/srtm/version2_1/Documentation/SRTM_Topo.pdf).

To view HGT files:
1) 3dem can be downloaded from here http://www.visualizationsoftware.com/3dem. 
2) or see my [HGT-Relief-Map](https://github.com/JohnLeber/HGT-Relief-Map) project for code on how to create renders from the HGT files. This application was used to create the relief maps in this project (see images below). A complete set of renders of all the HGT files can be found in the [images folder](https://github.com/JohnLeber/NZDEM-HGT-30/tree/master/Images).

You can use the data for commerical and non-commerical purposes according to the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/legalcode). You must attribute the creator in your own works which in this case would be [Land Information New Zealand](https://www.linz.govt.nz/).


The image below is a render of the S40E175.hgt file showing Tongariro National Park.

![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/tongariro.jpg)

 
Render of S37E175.hgt - Great Barrier and the Coromandel Peninsula (below).
![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/GreatBarrier.jpg)

Render of S39E175.hgt - Lake Taupo (below).
![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/Taupo.jpg)

Render of S44E170.hgt - West Coast/Southern Alps (below).
![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/WestCoast.jpg)
 
North and South Island Map Index (below).
![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/NorthMap.jpg)
![alt text](https://github.com/JohnLeber/NZDEM-HGT-30/blob/master/Screenshots/SouthMap.jpg)
