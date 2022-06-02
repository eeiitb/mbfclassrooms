

Julia Advanced 3D Printer - Usage Information Booklet

Wadhwani Electronics Lab

Department of Electrical Engineering

INDIAN INSTITUTE OF TECHNOLOGY BOMBAY

Rabiya Kunhayi

Shantanu Singh

Sayali Duragkar

Goutham A P

213079012

203070025

193079004





Contents

[1](#br3)

[Computer](#br3)[ ](#br3)[Aided](#br3)[ ](#br3)[3D](#br3)[ ](#br3)[Designing](#br3)

[1.1](#br3)[ ](#br3)[Introduction](#br3)[ ](#br3). . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

[1.2](#br3)[ ](#br3)[Fusion](#br3)[ ](#br3)[360](#br3)[ ](#br3). . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

3

3

3

[2](#br5)

[3](#br6)

[4](#br7)

[5](#br17)

[6](#br20)

[Fracktory](#br5)[ ](#br5)[Slicer](#br5)[ ](#br5)[Software](#br5)

5

6

[The](#br6)[ ](#br6)[Julia](#br6)[ ](#br6)[Advanced](#br6)[ ](#br6)[3D](#br6)[ ](#br6)[Printer](#br6)

[Steps](#br7)[ ](#br7)[to](#br7)[ ](#br7)[follow](#br7)[ ](#br7)[from](#br7)[ ](#br7)[STL](#br7)[ ](#br7)[to](#br7)[ ](#br7)[3D](#br7)[ ](#br7)[printing](#br7)

[Calibration](#br17)

7

17

20

[Precautions](#br20)[ ](#br20)[for](#br20)[ ](#br20)[operating](#br20)[ ](#br20)[the](#br20)[ ](#br20)[Julia](#br20)[ ](#br20)[Advance](#br20)[ ](#br20)[3D](#br20)[ ](#br20)[printer](#br20)

2





1 Computer Aided 3D Designing

1.1 Introduction

The STL (Standard Triangle Language) is the industry standard ﬁle type for

3D Printing. It uses a series of triangles to represent the surfaces of a solid

model. All modern CAD (Computer Aided Design) software allow you to export

their native ﬁle format into STL. The 3D model is then converted into machine

language (G-code) through a process called “slicing” and is ready to print. [? ]

Few popular examples of 3D designing softwares are:

\1. Solidworks :- <https://www.solidworks.com/>

\2. Fusion 360 :- <https://www.autodesk.com/products/fusion-360/>

\3. Solid Edge :- <https://solidedge.siemens.com/en/>

1.2 Fusion 360

Fusion 360 is a cloud-based CAD/CAM/CAE tool for collaborative product

development. Fusion 360 combines fast and easy organic modeling with precise

solid modeling, to help you create manufacturable designs.[? ]

Fusion 360 is free to use for students who register in the Autodesk Educa-

tion Community:- [https://www.autodesk.com/education/edu-software/](https://www.autodesk.com/education/edu-software/overview?sorting=featured&filters=individual)

[overview?sorting=featured&filters=individual](https://www.autodesk.com/education/edu-software/overview?sorting=featured&filters=individual). Few Important Links are

listed below.

• System Requirements:- [https://knowledge.autodesk.com/support/fusion-](https://knowledge.autodesk.com/support/fusion-360/learn-explore/caas/sfdcarticles/sfdcarticles/System-requirements-for-Autodesk-Fusion-360.html)

[360/learn-explore/caas/sfdcarticles/sfdcarticles/System-requirements-for-](https://knowledge.autodesk.com/support/fusion-360/learn-explore/caas/sfdcarticles/sfdcarticles/System-requirements-for-Autodesk-Fusion-360.html)

[Autodesk-Fusion-360.html](https://knowledge.autodesk.com/support/fusion-360/learn-explore/caas/sfdcarticles/sfdcarticles/System-requirements-for-Autodesk-Fusion-360.html)

• Documentation:- <https://help.autodesk.com/view/fusion360/ENU/>

• Tutorials & Self-guided Courses:- [https://help.autodesk.com/view/](https://help.autodesk.com/view/fusion360/ENU/courses/)

[fusion360/ENU/courses/](https://help.autodesk.com/view/fusion360/ENU/courses/)

Few Important Concepts to begin with in the

[https://help.autodesk.com/view/fusion360/ENU/:](https://help.autodesk.com/view/fusion360/ENU/)

• Use the Sketch tools to create the sketch proﬁles that drive the shape

of solid, surface, and T-Spline bodies in your design. Sketches are the

underlying geometry that support the creation of 3D solid, surface, and

T-Spline bodies in your design. Ex: Lines, Shapes, Splines, Mirrors and

Patterns

• The Solid tab contains traditional solid modeling tools within the Design

workspace in Fusion 360, and supports both parametric and solid modeling

modes.

3





• The following commands in the Design workspace, in the Solid > Create

panel, let you create a solid body from a closed sketch proﬁle, open sketch

curve, or planar face in Fusion 360.

– Extrude

– Revolve

– Sweep

– Loft

– Shell

– Fillet

– Champer

– Sweep

After designing, export the STL ﬁle and import it into the slicer software

for 3D printing. There are many websites where we get STL ﬁles of popular

designs, for ex:Makerbot Thingverse:- <https://www.thingiverse.com/>

4





2 Fracktory Slicer Software

A slicer is computer software used in the majority of 3D printing processes for

the conversion of a 3D object model to speciﬁc instructions for the printer. In

particular, the conversion from a model in STL format to printer commands in

g-code format in fused ﬁlament fabrication and other similar processes. [? ]

The slicer ﬁrst divides the object as a stack of ﬂat layers, followed by describ-

ing these layers as linear movements of the 3D printer extruder, ﬁxation laser or

equivalent. All these movements, together with some speciﬁc printer commands

like the ones to control the extruder temperature or bed temperature, are ﬁnally

written in the g-code ﬁle, that can afterwards be transferred to the printer.

\1. Fracktory is a 3D slicer application developed by FRACKTAL WORKS

supported by the 3D printer.

\2. Fracktory software imports the 3D design in .stl/.obj ﬁle format (prefer-

ably .stl as it can be edited). Note that the Fracktory software is used to

print the model not for making the model.

\3. The model is viewed in 3D with bottom plane is build-plate of the printer.

\4. In 3D printing parameters settings, both recommended and customised

options are available. In recommended settings, the parameters are set

automatically based on the design imported and on the other hand, we can

set each parameter manually based on the understanding and experience

in the 3D printing.

\5. Various printing parameters like Inﬁll, Building Support etc. can be set

to preferred values and more information about each one of them can

be obtained by hovering over ‘i’ symbol at each setting type. For more

information, refer to 10 Most Important 3D Printer Slicer Settings:-

<https://all3dp.com/2/3d-slicer-settings-3d-printer/>

\6. After ﬁnalising all the print parameters, click on ‘Prepare’ option at the

bottom-right corner. The estimated time to print the model is shown and

the parameters can be optimised according to the necessity.

5





3 The Julia Advanced 3D Printer

An Introduction to Julia Advanced is given in the link:

Introduction Video:- <https://youtube/FDG05gGNbcc>.

About the printer:-

\1. Manufactoring Company :- FRACKTAL WORKS

\2. Model :- Julia Advanced

\3. Nozzel Size :- 0.4 mm Nozzle

\4. Layer Resolution :- 100 - 300 micron

\5. Supported Materials :- PLA, ABS, EVA

\6. Maximum Dimensions of Model:- 200mm \* 200mm \*200mm

\7. Printing Speed:-

(a) Normal:- 50-55 mm/s

(b) For Fine Printing :- 45 mm/s

(c) Fast :- 60-65 mm/s

Other speciﬁcations are mentioned in the link below.

The Brochure for the Julia Advanced Printer can be found in the following

link: [https://5.imimg.com/data5/BK/ID/TH/SELLER-20503702/3d-printer-](https://5.imimg.com/data5/BK/ID/TH/SELLER-20503702/3d-printer-julia-advanced.pdf)julia-advanced.

[pdf](https://5.imimg.com/data5/BK/ID/TH/SELLER-20503702/3d-printer-julia-advanced.pdf)

6





4 Steps to follow from STL to 3D printing

\1. Select the 3D Printer

Figure 1: Select the printer.

\2. Select the material used for printing.

Figure 2: Select the material.

7





\3. Check whether the selected nozzle size is same as of the printer.

Figure 3: Select the nozzle size

\4. Import the .stl ﬁle into the Fracktory software.

Figure 4: Opening the .stl ﬁle

8





\5. Set the 3D printing parameters according to the requirement. Beginners

are encouraged to use recommended settings. Tick the Build plate adhe-

sion option in the right pane.

Figure 5: Select the setting(Recommended).

\6. If one wants to do customize settings then they are encouraged to change

the wall thickness according to requirement and can choose the inﬁll pat-

tern.

Figure 6: Selecting the setting(Custom).

9





Figure 7: Wall thickness option.

\7. The built-plate adhesion type among brim,raft,skirt can be chosen based

on model otherwise it is mentioned in recommended settings.

Figure 8: Option for Inﬁll.

10





Figure 9: Build plate adhesion type and it’s width.

\8. After setting the print parameters, prepare .gcode ﬁle.

Figure 10: Prepare the model.

11





\9. Export the generated .gcode ﬁle to a USB memory device.

Figure 11: Saving the model in USB memory device

12





\10. Mount the USB memory device to the 3D printer (Julia Advanced) and

select the model to be printed.

Figure 12: Select the model to be printed on the USB device.

\11. Choose the storage(in this case removable disk) where the g-code ﬁle is

stored.

Figure 13: Select the USB option.

13





\12. Select the model.

Figure 14: Review the model.

\13. Print.

Figure 15: Printing starts.

14





\14. Before printing the model the temperature of nozzle and build-plate rises

to a required level.

Figure 16: Temperature of the nozzle(left) and build-plate(right).

\15. After giving the print command the printer does the 9-point calibration

by moving the nozzle at diﬀerent positions on the built plate.

Figure 17: 9-point calibration of printer.

15





\16. Take the model out of the printer only after the minimum temperature of

built plate and nozzle is achieved.

Figure 18: Model just after removing from printer.

\17. Remove the brim of the model with the cutter.

Figure 19: Printed model after cutting the brim.

16





5 Calibration

Calibration is one of the important step in the process of 3D printing. If the

printer is correctly calibrated then one can generate the expected output min-

imising errors. Calibration involves built-plate leveling and nozzle cleaning. The

following steps should be followed for calibration:-

\1. On the printer menu go on calibration option.

Figure 20: Select the calibrate option.

17





\2. Select the wizard menu.

Figure 21: Select the wizard option.

\3. Select ‘Quick Calibration’ and the built-plate will rise and nozzle will move

through 3 points left, right and back.

Figure 22: Select the quick calibration.

18





\4. As the nozzle moves at the ﬁrst point, tighten or loosen screw at the

bottom of built-plate exactly below the position of the nozzle until the Red

LED light at bottom of built-plate stops blinking and glows constantly.It

may happen that Red LED may not be glowing so try to adjust the screw

in both direction so that it starts blinking and then glows solidly.

Figure 23: Calibration begun.

Figure 24: Adjust screw up and down red led goes from blinking to solid red.

19





\5. Then click on ‘Next’ on the screen and repeat Step 4 for the next point.

Repeat the same until all the three points are ﬁnished and then click on

‘Done’ on the screen.

\6. For nozzle cleaning, take a few drops of acetone on a cotton ball and

remove the ﬁlament at nozzle mouth. Warning: The Nozzle temper-

ature should be low while doing this, which can also be seen at

the screen.

\7. For removing extra ﬁlament from nozzle mouth, go to Control Menu →

Load Filament option and remove ﬁlament until it comes out smoothly

for better printing.

\8. Calibration should be done once in a week and make sure that the

temperature of both nozzle and build-plate are low

\9. 3D printer should be switched oﬀ once the model is removed after complete

printing.

6 Precautions for operating the Julia Advance

3D printer

\1. Check whether the material (e.g PLA) used in the the printer is same as

speciﬁed in the Fracktory software.

\2. The calibration of the nozzle and the built plate is important otherwise

printer will not design the shape correctly.

\3. The nozzle and built plate must be clean, dust particles may deteriorate

the model.

\4. The nozzle and built plate are to be preheated to certain temperature to

make the material ﬂow smooth.

\5. Initially, run the nozzle for some time to remove some of the material

ensuring smooth ﬂow for the design.

\6. Before printing, ensure if the model to be printed and the model in the

display of the printer monitor are same. Sometimes, it may take hours to

print the model.

\7. The time for printing and overall time is mentioned on the printer display

when model is in process of printing , model should be removed only after

the overall time is passed.

20


