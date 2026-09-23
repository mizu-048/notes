---
{"dg-publish":true,"permalink":"/notes/z-semester-1/physics/lectures/"}
---

# Mass and Momentum
From: 9.1-9.9 and 11.1, 11.2, 11.4 and 11.8
## Center of Mass
$x_{\text{com}}=\dfrac{m_{1}x_{1} +  m_{2}x_{2} + m_{3}x_{3}\dots }{m_{1}+m_{2}+m_{3}\dots}=\dfrac{\sum(m_{i}x_{i})}{\sum m_{i}}$
do the same for $y$ distance to get the $y$ distance of the center of mass
- an object with non uniform mass distribution, rotates about its center of mass whenever it is thrown
- **Changing mass systems:** a flying plane that consumes its fuel, a multistage space rocket, etc
![center_of_mass_example.png|600](/img/user/Notes/zSemester%201/Physics/attachments/center_of_mass_example.png)

- Checkpoint![center of mass checkpoint.png](/img/user/Notes/zSemester%201/Physics/attachments/center%20of%20mass%20checkpoint.png)
	- a) at intersection of x and y axis
	- b) in 4th quadrant(box 3) as 2 and 4 box cancel each other's affect
	- c) on the -y axis, below the x-axis
	- d) stays at origin
	- e) in 3rd quad(box 4) as only box 4 remains
	- f) stays at origin

## Centroid
- an object's centroid will coincide with its center of mass, if the mass distribution along the whole volume of the object is uniform
[eee watch if i have time](https://www.youtube.com/watch?v=SWu_i-19Rn0)

## Momentum
- Momentum = $P=mv$
- Change in momentum = Impulse = $F\times t= \Delta P=(P_{f}-P_{i})$
	- $F=\dfrac{d}{dt}P$
- ![linear momentum checkpoint.png](/img/user/Notes/zSemester%201/Physics/attachments/linear%20momentum%20checkpoint.png)
	- $1 > 3 > 2 \geq 4$
	- 3, as its momentum is decreasing, mass being constant, velocity is decreasing
### rotation
- **Angular Momentum**: $\vec{l}=\vec{r}\times \vec{p}=m(\vec{r}\times \vec{v})$
- **Moment of Inertia:** 
  ![moment of inertia.png|300](/img/user/Notes/zSemester%201/Physics/attachments/moment%20of%20inertia.png)
- **Kinetic Energy:**
$$
K=\dfrac{1}{2}I_{ \text{com}}\omega^{2} + \dfrac{1}{2}Mv^{2}_{ \text{com}}
$$
	- A rolling object has two types of kinetic energy: a rotational kinetic energy $\dfrac{1}{2}I_{ \text{com}}\omega^{2}$ due to its rotation about its center of mass and a translational kinetic$\dfrac{1}{2}Mv^{2}_{ \text{com}}$ energy due to translation of its center of mass.
- **Acceleration of rolling object**:
$$
a_{\text{com}} = -\dfrac{g\sin\theta}{1+{ \dfrac{I_\text{com}}{MR^{2}}}}
$$
	- its the linear acceleration on an include of angle $\theta$
	- rolling is due to the friction, and gravity, otherwise it would slide with no friction
- ![rolling velocity practice.png|500](/img/user/Notes/zSemester%201/Physics/attachments/rolling%20velocity%20practice.png)

### Collision
$v_{1f}=\dfrac{m_{1}-m_2}{m_{1}+m_{2}}v_{1i} \ + \ \dfrac{2m_{2}}{m_{1}+m_{2}}v_{2i}$
- Average Force in a collision: $F_{ \text{avg}}=-\dfrac{\Delta m}{\Delta t}\Delta v$
### Rocket science
- **Thrust Equation**: $Rv_{ \text{rel}}=Ma$
	- Fuel consumption over time: $R=-\dfrac{d}{dt}m$
	- $Ma$ is net force
- **Rocket Equation: $v_{f}-v_{i}=v_{ \text{rel} }\ln(\dfrac{M_{i}}{M_{f}})$
	- to relate the changes in velocity due to the changing mass
	- $v_{ \text{rel}}$: exhaust velocity relative to the rocket
![rocket thrust varying mass practice.png|500](/img/user/Notes/zSemester%201/Physics/attachments/rocket%20thrust%20varying%20mass%20practice.png)
# Modulus, stress and strain
- ![stress-strain-graph.png|400](/img/user/Notes/zSemester%201/Physics/attachments/stress-strain-graph.png)
- initial straight indicates hook's law is follow and shows the young's modulus, the edge at teh end
- ![stress-strain problem.png|400](/img/user/Notes/zSemester%201/Physics/attachments/stress-strain%20problem.png)
# Work, Energy, Force
- $f_{k}=\mu_{k}F_{N}$
- Work done = $\Delta K=W=\dfrac{1}{2}mv^{2}-\dfrac{1}{2}mv^{2}_{o}$