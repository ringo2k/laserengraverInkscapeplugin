# laserengraverInkscapeplugin
A laser engraver GCODE generator for Marlin firmware (RepRap) to control a laser or mill. Generated GCODE Out of inkscape files. 

The idea is based on this article: http://www.instructables.com/id/Pocket-laser-engraver/


I added some functions to work with a normal MARLIN firmare (the M3 and M5 commands must be added in Firmare like I did in
https://github.com/ringo2k/Marlin/commit/eeccc0bf93881d14582e844aa4cd383413825a75


It gives you the chance to add a laser on your 3D printer to make cool stuff :D
I added some features so it is easier to use with a 3D printer. 

* When you installed your laser on your printer it sure has another x=0 and y=0 so i added the possibilitie to make a
  offset on x and y!
* The laser doesn't need to be focused when the nozzle is on Z=0. The focus on the bed of the laser can be once determined
  and then written in the Z Offset. Also when you like to engrave larger objects, which have a own heigt, add this height
  to the parameter to make the laser spot on the top of the object focus again. 


