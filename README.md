# Freecad-Tutorial
### Discription:-
This tutorial will help a beginner to learn 3d modeling and 2d drawing in very easy manner from scratch 

### Contents-:
1. About FreeCAD and its installation.
2. Working with FreeCAD.
3. FreeCAD Workbenches.
4. Saving Files in FreeCAD.
5. Exporting Files in FreeCAD.
6. Importing Files into FreeCAD.
7. Common Tools in Various FreeCAD Workbenches and Their Function
8. Navigation




## 1. About FreeCAD and its installation:
FreeCAD is designed for technical 3-D modelling where we tend to design parts with regular [shapes.It](https://www.google.com "Google's Homepage") is still in an early stage of development, so you might not be as productive as with another CAD application, and you will certainly encounter bugs, or experience crashes. FreeCAD now has the ability to save backup files. The number of those backup files can be specified in the preferences dialog. Don’t hesitate to allow 2 or 3 backup files until you know well how to deal with FreeCAD.

Save your work often, from time to time save your work under a different name, so you have a “safe” copy to fall back to, and be prepared to the possibility that some commands might not give you the expected results.

### What is CAD?

CAD stands for Computer-Aided Design. It’s a technology that allows engineers, architects, and designers to create detailed drawings and models of objects or buildings on a computer. Instead of drawing by hand, they use special software that helps them design things more accurately and efficiently.

CAD software lets you create 2D drawings or 3D models of almost anything you can imagine, from simple objects like furniture to complex structures like skyscrapers or even parts for machines.




### Installation
To download FreeCAD, follow the steps below:

Visit the organization’s website [FreeCAD.org](https://www.google.com)

Click on the Download tab to open the webpage containing the FreeCAD download files
Download the file by clicking on the download file that corresponds to your computer’s operating system (as mentioned, FreeCAD is available on Windows, macOS, and Linux)
The process of downloading FreeCAD is similar across the various operating systems. This is because the steps above download the FreeCAD installer or package, which is the file that contains the software.
Curent stable version is 0.21.2





## 2. Working with FreeCAD
Orientation
After installing the FreeCAD software, you shall need to understand the FreeCAD interface before starting to draw or model. That way, you shall know where to get the specific tools for performing certain tasks or where to look for certain things as you draw/model.

At the start, the interface may seem complicated, but with the help of this guide, we hope you shall be able to grasp most of the basic features of the interface. With practice, the features shall stick and you shall find it easier with time.

If you are familiar with other CAD software, you shall realize that the main buttons of ‘File’, ‘Edit’, ‘View’, ‘Tools’, ‘Windows’, and ‘Help’ will be found where you expect them to be. The only new button is probably the ‘Macro’ button, which we shall look at later in this guide.

When you open FreeCAD, you will be presented with the FreeCAD start center that looks like the screenshot below. The start center is a welcome screen and it has three tabs namely document, help, and activity.







## 3. FreeCAD Workbenches
FreeCAD groups toolbar buttons, menus, and other interface controls that are specific for certain specialties into different sets called workbenches. If you want to do some architectural modeling, you should use the ‘Arch’ workbench while if you want to draw and model some mechanical parts you can use the ‘Part’ workbench.



You can look at it as one workshop that has separate workbenches (tables) with specific tools for different specialists.






## 4. Saving Files in FreeCAD
You can choose to assign a name for your newly created FreeCAD file by clicking File > Save As or hitting the CTRL+S keyboard shortcut. Next, type out a name, choose the folder you want the file to be saved, and, finally, click Save. By default, FreeCAD saves the files using the FCStd file format.





## 5. Exporting Files in FreeCAD
To save the files using other [supported file formats on FreeCAD](https://wiki.freecad.org/Import_Export) – such as DXF, DWG, IDES, STEP, STL, SVG, VRML, and more – you have to use the Export command. Wondering how to export files in FreeCAD? The process is quite simple; it involves the following steps:

Select all the solids you want to export. You can achieve this by manually selecting the objects or using the CTRL+A keyboard shortcut
Click the File button and select Export or use the CTRL+E keyboard shortcut
Choose the file format to which you want to export your project
Click Save




## 6. Importing Files into FreeCAD
To import files into FreeCAD, follow the steps below:

Create a new FreeCAD project
Switch to the workbench that best represents the model you want to import
Click the File button and select Import or use the CTRL+I keyboard shortcut
4 In the file explorer window, navigate to the location of the file you want to import and double-click on that file to import it
If you have imported mesh formats like STL/OBJ, which are dimensionless, scale the model after converting it to a solid. You can also scale the model in the application it was created with prior to exporting it. Scaling is essential because FreeCAD assumes that the units used in the model are millimeters.


## 7. Common Tools in Various FreeCAD Workbenches and Their Function
## Sketcher workbench
|Tool              	|Description|
|:-----------------:|:------------------:|
|Point              |Drawing a point|
|Line by 2 points  	|Drawing a line by joining two points|
|Arc	              |Drawing an arc using the center, radius, start angle and end angle|
|Arc by 3 points	  |Uses two endpoints and another point on the circumference to draw an arc|
|Circle	            |Drawing a circle using center and radius|
|Circle by 3 points	|Draws circle using three points on the circumference|
|Rectangle          |Drawing rectangle using two opposite points|
|Triangle          	|Drawing a regular triangle|
|Square            	|Draws a regular Square|
|Hexagon           	|Draws a regular hexagon|
|Pentagon          	|Draws a regular pentagon|
|Trim              	|Trims a line, arc, or circle with respect to a clicked point|
|Construction Mode	|Toggles an element to/from construction mode where an object will not be used in a 3D geometry operation and it is only visible while editing the sketch that contains it|
|Mirror            	|Mirrors selected elements of a sketch|
|Merge	            |Merges sketches|


## Part Design Workbench
Tool	         | Description
---------------|-------------
Pad	           |  Extrudes a solid part from a sketch
Revolution     |  Revolves a sketch about an axis to produce a solid part
Chamfer        |  Chamfers the edges
Pocket         |	Created a pocket from a selected sketch that is mapped to an existing solid part
Groove         |	Revolves a sketch around an axis to generate a groove
Fillet         |	Rounds or creates fillets on the edges of an object
Mirrored       |	Mirrors objects on a face or plane
Linear pattern |  Replicates parts in a linear pattern
Polar Pattern  |  Replicates parts in a circular/polar pattern


You can also select create a new sketch in Part Design workbench to access all the tools from Sketcher workbench. The Part workbench contains tools that are similar to those in the Part Design workbench.

With practice, you will get acquainted with more advanced tools from the workbenches you frequently use.

## Navigating using keyboard shortcuts
Shortcut                                 | Output
----------------------------------------:|:----------:
CRTL + ‘+’                               |  	Zoom In
CRTL + ‘-‘                               | 	Zoom Out
Arrows                                   | 	To view left, right, up, and down
SHIFT + Left arrow                       |	Rotate 90 degrees to the left
SHIFT + Right arrow                      | Rotate 90 degrees to the right
0,1,2,3,4,5,6                            |	For Isometric, Front, Top, Right, Rear, Bottom and Left respectively
VO (held at the same time)	             | Orthographic view
VP (held at the same time)	             | Perspective view
CTRL and right-click on parts/features   | Selecting more than one feature/parts
