#### [←home](../README.md)

 I have built a few Java programs for a variety of academic projects. It helped me understand a little better the physics and the programming language itself. 
 
+ [Finite Element Method - Fin Equation - JAVA Application](#section1)
+ [Pipeline - JAVA Application](#section2)
+ [Steal Beam - Cross-Section - Fire/Insulation Damage - Transient Analysis - JAVA Application](#section3)
+ [Composite Software - JAVA Application](#section4)

---

## <a name="section1"><a/>Finite Element Method - Fin Equation - JAVA Application
<div style="text-align: justify">
FEM implementation for the fin equation. From Applied Finite Element Methods class (2015). The project included the full derivation of the FEM formulation and software design document with pseudo code. The stand-alone software can read a user input file, display the information on output window, perform iterations and display results. User is able to save results to file. JFreeChart library was used to provide plotting capabilities. 
</div><br/>
 
![process](../pics/FEM.png)

---

## <a name="section2"><a/>Pipeline - JAVA Application

<div style="text-align: justify">
A model of a pipeline, involving the transport of oil through permafrost. Project is from Adv. Heat Transfer Class (2014).  The goal was to provide a stand-alone tool that can display flow input and output parameters, as well as varying pipe and insulation diameters. It uses integration and closed formulas to attain solution.
</div><br/>
 
![process](../pics/pipeline.png)

---

## <a name="section3"><a/>Steal Beam - Cross-Section - Fire/Insulation Damage - Transient Analysis - JAVA Application

 <div style="text-align: justify">
Another Adv. Heat Transfer problem (2014). The goal was to investigate the effects of thermal insulation damage on a steel beam under fire. It uses Finite Volume Method (FVM) on a uniform grid to obtain the transient solution. Overall, it is a simple implementation where every cell has its own numerical scheme (boundary, corner, solid, etc). The user can define material zones via vertices and assign specific ids to those. The program displays node id and color-coded areas. No file user inputs, they are specified directly in the Java code. Note that a .csv file is created containing thermal results. They can be plotted in Excel. Ideally, values could have been plotted directly in the JFrame. Again, future implementation needed here. For now, good practice.
</div><br/>

<p align="center"><img src="../pics/thermo1.png" width="600"/></p>
 
<p align="center"><img src="../pics/thermo2.png" width="600"/></p>
 
---

## <a name="section4"><a/>Composite Software - JAVA Application

<div style="text-align: justify">
A more complex Java program based on Composite Design class at UConn (2018) and its book Design and Analysis of Composite Structures, 2nd Edition. Hence, I decided to translate most of the book into a true composites software. My original goal was to master Composite Laminate Theory (CLT) and dive deep into closed-form solutions for various composite components (laminates, plates, beams, panels, sandwiches) under various loads (tension, compression, bending, shear) given various failure theories. Again, by building it in Java I wanted to create something useful and easy to use. For example, user can build a laminate, use it to create a plate and have various plates to build a beam. User can inspect output window and plot a variety of results. I started this project in 2018 (work-in-progress), regardless I am showcasing it here. 
</div><br/>
 
<p align="center"><img src="../pics/comp1.png" width="600"/></p>

<p align="center"><img src="../pics/comp2.png" width="600"/></p>

<p align="center"><img src="../pics/comp3.png" width="600"/></p>

<p align="center"><img src="../pics/comp4.png" width="400"/></p>

---

