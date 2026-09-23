---
{"dg-publish":true,"permalink":"/notes/z-semester-1/physics/measurements/"}
---

[video](https://www.youtube.com/watch?v=V0ZRvvHfF0E)
error is synonymous with uncertainty
- **Absolute Uncertainty:** the range given in the *same units* as the physical quantity e.g. $13.0 \pu{ ms ^{-1} } \pm 0.5\pu{ ms ^{-1} }$
- **Relative Uncertainty:** the relative range give in percentage with *no units* i.e. $\dfrac{\delta_{v}}{v}$ e.g. $\dfrac{0.5}{13}=3.8\%$ that is $13.0 \pu{ ms ^{-1} } \pm 3.8 \%$
## Arithmatics of uncertainties
### Additions/Subtraction
- when two quantities are added or subtracted the ==uncertainties are always added==
	- $(4.3 \pm 0.2) + (2.1 \pm 0.4) = 6.4 \pm 0.6$
	- $(4.3 \pm 0.2) - (2.1 \pm 0.4) = 2.2 \pm 0.6$
### Multiplication and Division
- for multiplication and division you ==convert to relative uncertainties, then **add** the relative uncertainties==
	- $(4.3 \pm (\dfrac{0.2}{4.3}\times100))\times (2.1 \pm \dfrac{0.4}{2.1}\times100))$
	- $(4.3 \pm 4.6\%)\times (2.1 \pm 19\%)) =9.0 \pm 23.6\%$

also the result measurement should have the same number of significant digits, round the last digit


# Error Propagation in a function
## single variable:
- the uncertainty introduced in a function $f(x)$ i.e. $\delta_{f}$, due to uncertainty in its variable $x$ is determined by:
$$\begin{align}
\delta_{f}=  & \dfrac{d_{f}}{d_{x}}\times \delta_{x}  \\
 \\
e.g. \  K(v) = \dfrac{1}{2}mv^{2}   & \text{ then;}\qquad d K=\frac{d}{dv}( \dfrac{1}{2}mv^{2}) \times(d_{v}) \\
\end{align}$$
where $\dfrac{d_{f}}{d_{v}}$ is the derivative of $f(x)$ with respect to the uncertain variable $x$ and $\delta_{x}$ is its( K's ) uncertainty.
## double and triple variable
- now lets assume both mass and velocity as uncertain to some range $\delta _m \text{ and } \delta_{v}$ then uncertainty in the kinetic energy $\delta_{K}$ is
$$\begin{align}
  \delta_{K} = \sqrt{\underbrace{  (\delta_{K_{m}})^{2} + (\delta_{K_{v}})^{2}  }_{ \text{variance}  }} \\
 \\
 \text{where $\delta_{K_{m}}$ and $\delta_{K_{m}}$ are equal to} \\ \\
 \delta_{K_{m}} = \underbrace{ \frac{ \partial _{K} }{ \partial_{m} } }_{ \substack{ {\text{sensitivity}} \\{ \text{coefficient}} } }\times \delta_{m} \qquad \text{and}\qquad  \delta_{K_{v}} = \frac{ \partial _{K} }{ \partial_{m} }\times \delta_{v}
\end{align}$$
where $\frac{ \partial y }{ \partial x }$ are partial derivative[^1]
- The ==sensitivity co-efficient== when multiplied by their uncertainties gives us their contribution to the final uncertainty
$\text{contribution} = \text{sensitivity}\times \text{uncertainty}$
- ==Variance==($_{(\delta_{K_{m}})^{2} + (\delta_{K_{v}})^{2}}$) can be used to give us the contribution in percentage, as $(\dfrac{\text{sensitivity}}{\text{variance}}\times 100) \%$
- 
### example
- say $\pu{ m }= 10.0 \ \pu{ kg } \pm 0.5 \ \pu{ kg }$ and $\pu{ v }= 20.0 \ \pu{ ms^{-1} } \pm 0.4 \ \pu{ ms^{-1} }$ then what is the kinetic energy and its uncertainty
	- so we start by finding $\delta_{K_{m}}$ and $\delta_{K_{v}}$
	  $\delta_{K_{v}} = \frac{\partial}{\partial_{v}}( \dfrac{1}{2}mv^{2}) \times(\delta_{v}) = (mv)\times\delta_{v}$
	  $= (10\times 20)\times(0.4) = 80.0 \ \pu{ J }$

	  $\delta_{K_{m}} = \frac{\partial}{\partial_{m}}( \dfrac{1}{2}mv^{2}) \times(\delta_{m}) = (\dfrac{1}{2}v^{2})\times\delta_{m}$
	  $= (\dfrac{1}{2}\times(20)^{2})\times(0.5)=100.0 \  \pu{ J }$
	  
	  so $\delta_{K} = \sqrt{ 100^{2}+80^{2} }=128.1 \ \pu{ J }$
	  and $K.E = \dfrac{1}{2}mv^{2}=\dfrac{1}{2}\times(10.0)\times(20.0)^{2}=2 \ \pu{ kJ }\pm 100  \ \pu{J}$
  

[^1]: functions same as derivative but we consider every other variable except $x$ as constant
