#### [home](../README.md)

 Through my academic carrerr I have decided to build a few simple programs either in school/home to help me understand a little better the physics and programming itself. 
 
 
 
+ [Finite Element Method - Fin Equation - JAVA Application](#Section1)
+ [Pipeline - JAVA Application](#Section2)
+ [Steal Beam - Cross-Section - Fire/Insulation Damage - Transient Analysis - JAVA Application](#Section3)
+ [Composite Software - JAVA Application](#Section4)


 



## Finite Element Method - Fin Equation - JAVA Application
FEM implementation for the fin equation. From the Applied Finite Element Methods class at WPI in 2015. The project included the full derivation of the FEM formulation and software design document with pseudo code. The stand-alone software can read a user input file, display the information on output window, perform iterations and display results. User is able to save results to file. JFreeChart library was used to provide plotting capabilities. 

---

# Pipeline - JAVA Application

A model of a pipeline, involving the transport of oil and permafrost. The problem was proposed in my applied Adv. Heat Transfer Class in 2014.  The goal was to provide a stand-alone tool that can display flow input and output parameters, as well as varying pipe and insulation diameters. It used integration and closed formulas to attain solution.

---

# <a name="section1"><a/>Steal Beam - Cross-Section - Fire/Insulation Damage - Transient Analysis - JAVA Application

Another Adv. Heat Transfer problem in 2014. The goal was to investigate the effects of thermal insulation damage on a steel beam under fire. It uses Finite Volume Method (FVM) on a uniform grid to obtain the transient solution. Overall it is a simple implementation where every cell has its own numerical scheme (boundary, corner, solid, etc). Again I took the opportunity to practice Java. The user can define material zones via vertices and assign specific ids to those. Object oriented programing was needed where the domain is made up of "rectangles" containing properties. The program displays node id and color-coded areas. There s no file user inputs where they are specified directly in the Java code. Note that a .csv file is created containing thermal results. They can be plotted in Excel. Ideally, values could have been plotted directly in the JFrame. Again, future implementation needed here. For now, good practice.
