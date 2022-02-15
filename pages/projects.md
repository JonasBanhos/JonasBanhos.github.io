#### [←home](../README.md)

Some of my interesting academic projects. 
 
+ [Rayleigh–Bénard Convection - 2D - CFD](#section1)
+ [Ramjet Engine Sizing - Analytical](#section2)
+ [Linear Variable Reluctance Motor - Desing Optimization](#section3)
+ [Vortex Shedding Frequency for Circular and Square Cylinders - 2D - CFD](#section4)
+ [Air-Jet Vortex Generators - 2D - CFD](#section5)

---
 
## <a name="section1"><a/>Rayleigh–Bénard Convection - 2D - CFD
<div style="text-align: justify">
CFD code the Rayleigh–Bénard Convection problem by full 2D implementation through Matlab. This is a research-quality code. Project from the CFD class ME5311 at UConn (2019).
</div>

### Implementation Highlights
 
| Topic | Comments |
| ------ | ----------- |
| Program    |  Matlab  |
| Governing PDEs    |  Non-dimensional Form   |
| Imcompressibility   | Satisfied via Poisson equation |
| Poisson equation  | Fourier Transform solution |
| BCs | Periodic |
| Grid  | Staggered |
| Time Integration    |  Fractional Step Method via Runge–Kutta  |
| Stability    |  Max between Convection-Diffusion stability Limit (CFL)  |

### Domain
<p align="left"><img src="../pics/cfddomain.png" width="600"/></p>
 
### Solution 
 
Grid=64^2, Ra=10^6 ,Pr=1,T_end=0.005s
 
<p align="left"><img src="../pics/OneTenthSec5.gif" width="600"/></p>
 
---
 
## <a name="section2"><a/>Ramjet Engine Sizing - Analytical
<div style="text-align: justify">
In aerospace applications Ramjets are used in mechanisms that require supersonic flow, such as to propel short range rockets. It uses its own speed to generate the compression necessary to decelerate the flow and produce thrust through added heat in the combustion chamber and further expansion through the nozzle.
For this type of device, the engine needs to be started via another vehicle travelling at supersonic speeds or by means of high pressure chambers in a testing setting. Great project from the Compressible Flow class ME702 at Manhattan College (2014).
</div>
 
### Engine Parameters 
 
* Ramjet engine at Mach 4, 2000 lbf/ft^2 of pressure and temperature of 519 R
* Combustion chamber Mach number <= 0.25
* Engine powered by JP10 fuel (heating value of 18,900 BTU/lbm) 
* Stoichiometric air-fuel ratio of 0.0704
* Engine Envelope: Total Length < 215”, width < 20”, throat-to-throat distance = 72” 
* Off-design analysis: Mach 2 and Mach 3

### Compressible Flow Analytical Approach
 
| Topic | Comments |
| ------ | ----------- |
| Quasi 1-D Flow |Cross-section area and thermodynamic variables: f(x)|
| Isentropic Flow    |  Facilitates use of Isentropic flow tables  |
| Normal Shock Theory   | Normal shock at diffuser throat  |
| Oblique Shock Theory| Diffuser optimization, oblique shock waves |
| Method of Characteristics  |  To determine nozzle shape  |
| Rayleigh Flow equations    |  Heat addition in combustor |

### Method of Characteristics Example

 <p align="left"><img src="../pics/nozzle-characMeth.png" width="800"/></p>

### Results

 <p align="left"><img src="../pics/stations.png" width="800"/></p>

|FLOW # | MACH | P | T | P0 | T0 |
| :---: | :---: | :---: | :---: | :---: | :---: |
|1|4.0|2000.0|513.2|303670.4|2155.3|
|2|2.60|10368.9|926.7|204027.7|2171.1|
|3|1.72|34144.5|1366.2|173890.5|2175.3|
|4|0.63|132521.3|2012.8|173890.5|2175.3|
|5|0.25|166491.7|2148.4|173890.5|2175.3|
|6|0.60|120520.0|6463.0|153604.5|6926.8|
|7|1.00|81146.1|5772.3|153603.9|6926.8|
|8|3.50|2000.0|2003.8|153603.9|6926.8|
 
<p align="left"><img src="../pics/ramjet.png" width="800"/></p>
 
---
 
## <a name="section3"><a/>Linear Variable Reluctance Motor - Desing Optimization  
<div style="text-align: justify">
My senior desing project at UConn (2011/2012). Design, analysis and validation of a Linear Variable Reluctance Motor. 
The task scope: mathematical derivation of a simplified configuration, magnetic modeling with [FEMM](https://www.femm.info/wiki/HomePage) and [Faraday](https://www.integratedsoft.com/products/Faraday) optimization, testing fixtures manufacturing (CNC machining) and final report to the client. 3 students and 2 semesters.
</div>

### Basic Configuration

<p align="left"><img src="../pics/LSRM7-diagram.png" width="600"/></p>

### Simulation

[FEMM](https://www.femm.info/wiki/HomePage): 2D Opensource software (Finite Element Method Magnetics).
 
<p align="left"><img src="../pics/LSRM11.png" width="800"/></p>

[Faraday](https://www.integratedsoft.com/products/Faraday): 3D time-harmonic eddy current field solver.
 
<p align="left"><img src="../pics/Faraday_Video3.gif" width="800"/></p>

### Machining/Testing

Over 100+ hours of precision manufacturing at UConn. A great hands-on experience and very useful knowledge torward design and manufacturing.
  
<p align="left"><img src="../pics/LSRM10.png" width="800"/></p>
 
### Validation

<p align="left"><img src="../pics/LSRM4-validation.png" width="800"/></p>

---
 
## <a name="section4"><a/>Vortex Shedding Frequency for Circular and Square Cylinders - 2D - CFD
<div style="text-align: justify">
Vortex shedding plays an important role in flow measurement since is provides a high degree of accuracy, even in slow flow conditions, with minimal disruption to the flow.  The study compared two types of blunt bodies, circular and square shapes. Project from the CFD ME704 at Manhattan College (2014).
</div><br/>

### Meshing 
 
Circular and square meshes
 
<p align="left"><img src="../pics/cfd1_2.png" width="800"/></p>

### Results

<p align="left"><img src="../pics/cfd3b.png" width="800"/></p>
 
<p align="left"><img src="../pics/cfd4.png" width="800"/></p>
 
## <a name="section5"><a/>Air-Jet Vortex Generators - 2D - CFD
<div style="text-align: justify">
The study focused on the comparison between counter-rotating and co-rotating arrangements of air-jet vortex generators and the three computational turbulence k-epsilon models, Standard, RNG and Realizable via ANSYS Fluent. Project from the CFD ME704 at Manhattan College (2014).
</div><br/>
 
### Implementation Highlights
 
| Topic | Comments |
| ------ | ----------- |
| Program    |  Ansys Fluent  |
| Meshing    |  Biased and structured   |
| Turbulence Models   | k-epsilon, RNG and Realizable  |

### Domain 
  
<p align="left"><img src="../pics/cfd6.png" width="800"/></p>

### Results

<p align="left"><img src="../pics/cfd5.png" width="800"/></p>
 
<p align="left"><img src="../pics/cfd7.png" width="800"/></p>
 
## <a name="section6"><a/>Air-Jet Vortex Generators - 2D - CFD
<div style="text-align: justify">
Undergrad lab study at UConn (2011) of fluid flow through an immersed body of circular shape using Particle Image Velocimetry (PIV). Results correlated to CFD and determination of fluid parameters via Matlab.
</div><br/>
 
 ### Experimental Setup 
  
<p align="left"><img src="../pics/flow.gif" width="600"/></p>

### Results

Velocity magnitude and cfd prediction (top) / curl and divergence (bottom)

<p align="left"><img src="../pics/flow2.png" width="800"/></p>

Velocity profiles and stream lines
<p align="left"><img src="../pics/flow4.png" width="800"/></p>
