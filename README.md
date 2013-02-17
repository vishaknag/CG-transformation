CG-transformation
=================

Adding the transformation process to rasterizer 

------------------------------------------------------------------------------------

File Reference

Gz.h : Graphics library header

Application3.cpp , Applicaiont3.h : New application that calls rend.cpp API functions
 
rend.cpp : New skeleton file with API definition and comments 

tri.asc :	A one-triangle data file 

tri.ppm	: The result of running "app3 <tri.asc >tri.ppm" 

pot4.asc : The Utah teapot triangle data file 

pot4.ppm : The result with default camera 

pot4.cam.ppm : The result of with app1 camera 

------------------------------------------------------------------------------------

* The result images are created in a 256x256 window

User interface

* If you click edit button, you can choose three transformation options; Rotate, Translate, and Scale

* Choose “Rotate Object”, rotation dialog pops up and you can type the value.

* Choose “Translate Object”, translation dialog pops up and you can type the value.

* Choose “Scale Object”, scale dialog pops up and you can type the value

------------------------------------------------------------------------------------
Camera defaults

#define	DEFAULT_FOV		35.0

#define	DEFAULT_IM_Z	(-10.0)  // world coords for image plane origin

#define	DEFAULT_IM_Y	(5.0)    // default look-at point = 0,0,0

#define	DEFAULT_IM_X	(-10.0) 
------------------------------------------------------------------------------------
