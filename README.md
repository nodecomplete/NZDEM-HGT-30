# NZDEM-HGT-30

New Zealand Digital Elevation Model (DEM) in 1 arc-second (~30 meter) HGT format. 

I created this dataset back around 2010. It was intended as a resource for the PC gaming community (train, plane, ship simulators...), graphics artists, or anyone who can apply the data safely. At that time NASA had not released 1 arc-second (30 meter) SRTM data for New Zealand or for any country other than the United States. I was able to create a Digital Elevation Model (DEM) by interpolating the contour lines from the Land Information New Zealand (LINZ) topographical database. I wrote [custom software](https://github.com/nodecomplete/NZDEM-HGT-30/blob/master/Screenshots/ConversionApp.jpg?raw=true) to perform the calculations which took (from memory) two 6 core machines about 1 week to complete. This resulted in a grid of evenly spaced points 10 meters apart. From that base grid I interpolated the points to get the 1 arc-second HGT data. Information on the HGT (STRM1) format can be found [here](https://dds.cr.usgs.gov/srtm/version2_1/Documentation/SRTM_Topo.pdf).

To [view](https://github.com/nodecomplete/NZDEM-HGT-30/blob/master/Screenshots/tongariro.jpg) HGT files, 3dem can be downloaded from here http://www.visualizationsoftware.com/3dem. 

You can use the data for commerical and non-commerical purposes according to the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/legalcode). You must attribute the creator in your own works which in this case would be [Land Information New Zealand](https://www.linz.govt.nz/).


Relief shading of HGT file showing Tongariro National Park.

![alt text](https://github.com/nodecomplete/NZDEM-HGT-30/blob/master/Screenshots/tongariro.jpg)

 

 
