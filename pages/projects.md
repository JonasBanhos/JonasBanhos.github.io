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
In aerospace applications Ramjets are used in mechanisms that require supersonic flow, such as
to propel short range rockets. It uses its own speed to generate the compression necessary to decelerate the
flow and produce thrust through added heat in the combustion chamber and further expansion through the
nozzle.
For this type of device, the engine needs to be started via another vehicle travelling at supersonic
speeds or by means of high pressure chambers in a testing setting.

Therefore the project will focus on the design of a Ramjet engine travelling at Mach 4, 2000 lbf of pressure and temperature of 519 R. The
design furthermore requires that the Mach number at the combustion chamber to be no greater than 0.25
and that the engine be powered by JP10 fuel with a heating value of 18,900 BTU/lbm and stoichiometric
air-fuel ratio of 0.0704.

The engine dimensions are bounded by a total length of no greater than 215” and
20” wide, with special consideration to the throat-to-throat distance of 72” inches.

The project will focus on the design for the given Mach conditions and as well as the analysis of flow at off-design conditions at
Mach 2 and Mach 3 given identical ambient conditions.

The project relies on the underlying compressible flow equations including
isentropic flow,
normal shock theory,
expansion theory,
oblique shock theory,
quasi 1-D flow
and method of characteristics to determine flow patterns for a given
Rayleigh Flow equations (Heat Addition)
engine component.

The design will follow parametric design techniques in order to estimate the most
suitable configuration given the design requirements to determine the overall engine configuration for the
oblique shock diffuser, combustor and nozzle.

 The following section will discuss in detail the analytical
methods used, equations and geometrical considerations of the system.

  
</div><br/>
  
## <a name="section3"><a/>Project2
<div style="text-align: justify">

  
</div><br/>
  
  
## <a name="section4"><a/>Project2
<div style="text-align: justify">

  
</div><br/>
 
 <p align="center"><img src="../pics/compTEST.png"/></p>
