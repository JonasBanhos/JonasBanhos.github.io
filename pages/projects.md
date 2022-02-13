#### [←home](../README.md)

Some of my interesting academic projects related to thermo-fluids. 
 
+ [Rayleigh–Bénard Convection - 2D - Matlab](#Section1)
+ [Project2](#Section2)
+ [Project3](#Section3)
+ [Project4](#Section4)

## <a name="section1"><a/>Rayleigh–Bénard Convection - 2D - Matlab
<div style="text-align: justify">
CFD code solving the Rayleigh–Bénard Convection problem by full 2D implementation through Matlab. 
</div>

### Implementation Highlights
 
| Steps | Comments |
| ------ | ----------- |
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
 
Grid=64^2, Ra=10^6 ,Pr=1,Tend=0.005
 
<p align="left"><img src="../pics/OneTenthSec5.gif" width="600"/></p>
 
## <a name="section2"><a/>Ramjet Engine Sizing - Analytical
<div style="text-align: justify">
In aerospace applications Ramjets are used in mechanisms that require supersonic flow, such as to propel short range rockets. It uses its own speed to generate the compression necessary to decelerate the flow and produce thrust through added heat in the combustion chamber and further expansion through the nozzle.
For this type of device, the engine needs to be started via another vehicle travelling at supersonic speeds or by means of high pressure chambers in a testing setting.
</div>
 
### Engine Parameters 
 
* Ramjet engine at Mach 4, 2000 lbf/ft^2 of pressure and temperature of 519 R
* Mach number at the combustion chamber no greater than 0.25
* Engine be powered by JP10 fuel with a heating value of 18,900 BTU/lbm 
* Stoichiometric air-fuel ratio of 0.0704
* Engine Envelope: Total Length < 215”, width < 20”, throat-to-throat distance = 72” 
* Off-design analysis: Mach 2 and Mach 3

### Compressible Flow Analytical Approach
 
| Techniques | Comments |
| ------ | ----------- |
| Quasi 1-D Flow |Cross-section area varies in one direction, thermodinamic variables f(x)|
| Isentropic Flow    |  Facilitates use of Isentropic flow tables  |
| Normal Shock Theory   | Normal shock at diffuser throat  |
| Oblique Shock Theory| Diffuser optimization, oblique shock waves |
| Method of Characteristics  |  To determine nozzle shape  |
| Rayleigh Flow equations    |  Heat addition in combustor |

### Method of Characteristics Example

 <p align="left"><img src="../pics/nozzle-characMeth.png" width="600"/></p>

### Results

 <p align="left"><img src="../pics/stations.png" width="600"/></p>

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
 
<p align="left"><img src="../pics/ramjet.png" width="600"/></p>

## <a name="section3"><a/>Project2
<div style="text-align: justify">

  
</div><br/>
  
  
## <a name="section4"><a/>Project2
<div style="text-align: justify">

  
</div><br/>
 
 <p align="center"><img src="../pics/compTEST.png"/></p>
