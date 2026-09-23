---
{"dg-publish":true,"permalink":"/notes/z-semester-1/aero/numericals/"}
---

>[!tldr]- Reynold's Number
> - ratio of **inertial forces** to **viscous forces** within a fluid, describing the type of flow
> - $R_{e}=\dfrac{\rho_{1}V c}{\mu}$
> 	- $\rho:$ density of the fluid medium is around $1.225 \ \pu{ kg/m^{3} }$
> 	- $V:$ Velocity of fluid $\ \pu{ m/s }$
> 	- $c:$ chord length of wing $\ \pu{ m }$
> 	- $\mu:$ dynamic viscosity for air is $1.789\times 10^{-5} \ \pu{ kg/ms }$
> - has no unit
> - **Application:**
> 	- **Laminar Flow:** at low Re, about < 2000 inside a pipe
> 	- **Turbulent Flow:** at high Re, about  > 4000 inside a pipe
> 	- **Transition Regime:** between laminar and turbulent, is unstable and Re is between 2300 and 4000 

>[!tldr]- Lift/Drag per Unit Span
> - **Lift per unit span:** $\dfrac{L'}{S}$
> - **Drag per unit span:** $\dfrac{D'}{S}$
> - $L'=\dfrac{1}{2}\ \pu{ \rho_{1}V^{2}S C_{l}}$
> - $D'=\dfrac{1}{2}\ \pu{ \rho_{1}V^{2}S C_{d}}$
> 	- $L':$ Lift force $(\ \pu{ N/m })$
> 	- $D':$ Drag force $(\ \pu{ N/m })$
> 	- $q_{\infty}=\dfrac{1}{2}\rho_{1}V^{2}:$ Dynamic Pressure $(\ \pu{ Pa })$
> 	- $S:$ wing planform area of wing $(\ \pu{m^{2} })$ for a rectangular wing, it is the product of wing span and chord length $S=c\times \text{wing span}$
> 	- $C_{\ \pu{ l/d }}:$ Coefficient of lift/drag (no unit) determined through experimentation for each airfoil at 

>[!tldr]- Lift to Drag ratio
> - $\dfrac{L'}{D'}=\dfrac{C_{l}}{C_{d}}$
> - each of which are defined in the previous callout

  >[!tldr]- Turning Radius
  > - $R=\dfrac{V^{2}}{g\sqrt{ n^{2}-1 }}$
>	- where $n$ is the [[Notes/zSemester 1/Aero/1st-sem#^loadfactor\|load factor]]


$R=\dfrac{V^{2}}{g\sqrt{ n^{2}-1 }} \text{or maybe do somethign liek this}\underbrace{ \dfrac{d}{dt}\Delta \rho \mu }_{  \substack{ {\text{hello}} \\{hi} } }$
# Derivations

> [!tldr]- Continuity:

For a compressible fluid of density $\rho_{1}$ at the lower end of the pipe, flowing for an interval $\Delta t$ covering a distance $\Delta x_{1}$, having velocity $v_{1}$, gives an equation
$$\begin{align}
 & v_{1}=\dfrac{\Delta x_{1}}{\Delta t} \\
OR \qquad  & \Delta x_{1}=v_{1}\times \Delta t \qquad \ \ \textemdash(i)
\end{align}
$$

the volume of this fluid at the starting point is 
$$\begin{align}
V_{1}=A_{1}\times \Delta x_{1};\qquad \textemdash(ii)
\end{align}
$$
where $A_{1}$ is the cross-section  of the pipe, using formula of density($\rho_{1}=\dfrac{m}{V}$), the mass of the fluid is 
$$\begin{align}

 & \Delta m_{1}=\rho_{1}\times V_{1} \\
 \\
 & \Delta m_{1}=\rho_{1}\times (A_{1} \times\Delta x_{1}) \qquad  & \because V_{1}=A_{1}\times \Delta x_{1}\qquad  \text{from } (ii) \\
 \\

 & \underbrace{ \dfrac{\Delta m_{1}}{\Delta t}=\rho_{1}\times A_{1} \times\Delta v_{1}  }_{ \text{mass flux} }\qquad  \textemdash (iii) & \because \Delta x_{1}=v_{1}\times \Delta t\qquad  \text{from } (i)
 \\ \\
  & \text{similarly for the upper end of the pipe} \\ \\

 & \dfrac{\Delta m_{2}}{\Delta t}=\rho_{2}\times A_{2} \times\Delta v_{2}\qquad\textemdash (iv)
\end{align}

$$

since the fluid is incompressible and hence the density at both ends and similarly the mass flux are equal so equation $(iii)$ and $(iv)$ are equal
$$
\begin{align}
    \dfrac{\Delta m_{1}}{\Delta t}  =\dfrac{\Delta m_{2}}{\Delta t} \\
 \\
     \underbrace{ \rho_{1}\ A_{1}  \ \Delta v_{1}  =\rho_{2} \  A_{2}  \ \Delta v_{2} }_{ \text{for an compressible fluid}  } \\
 \\
  \qquad \underbrace{ \ A_{1}  \ \Delta v_{1} = \  A_{2}  \ \Delta v_{2}  }_{  \text{for an incompressible fluid}}\qquad 
\end{align}
$$
since in an incompressible fluid $\rho_{1}=\rho_{2}$ as the density doesn't change



$\sum F=m \ \dfrac{d}{dx}v=P \ dA-(P+dP)dA$


let $A_{1}$ be the cross section at point 1 and $V_{1}$ be the velocity, then after an elapse of time $dt$, all elements have covered a distance $\Delta x= V \ dt$, cross section $A_{1}$ travelling distance $\Delta x$ gives volume
$V=A \ \Delta x=A \ V \ dt$



## Momentum stuff
- forces acting on a small object flowing through a fluid
	- pressure on all sides
	- frictional on all sides
	- gravity pulling it
- let $dx \ dz$ be the area of the left face, and $p \ (dx \ dz)$ be the force on it, this force is along the x-axis,
- there is a change in pressure per unit length of the fluid, symbolized by $\dfrac{d \ p}{dx\ }$, hence moving a distance $dx$ along the x-axis gives a pressure change of $dx \ \dfrac{d\ p}{dx}$
- hence the pressure on the right face of the object is $p \ + (\dfrac{dp}{dx})dx$, its area is also $dx \ dz$ hence force on it is $[ \ p \ + (\dfrac{dp}{dx})dx] \times(dx \ dz)$ but it acts in the negative x direction so total force on x-axis is
$$
F=p(dz \ dy) -(p+\dfrac{d \ p}{dx}dx) \ dz \ dy
$$
this simplifies to
$$\begin{align}

F & =(p - p -\dfrac{d \ p}{dx}dx) \ dz \ dy \\
F & =-(\dfrac{d \ p}{dx})dx \ dz \ dy \\

\end{align}
$$