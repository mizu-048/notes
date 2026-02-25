---
{"dg-publish":true,"permalink":"/tekno-fest/tekno-fest-rocketry/"}
---


> [!NOTE]- bleeeee
> - **Category:** A4 
> 	- Single-Stage Rocket
> 	- COTS (Commercial Off-The-Shelf) Solid Propellant Rocket Motor
> 	- Goal: to Reach the Highest Altitude
> - Min 4 and Max 6 members at assembly/firing range
> - 100 points if half or more members brought to Aksaray Hisar Firing Range are females
> - Aside from reaching minimum of 8000ft, we must also be within $\pm 15\%$ tolerance of our declared(predicted) altitude, which we will submit after assembly at their firing range
> - Minimum of $85\%$ score is required in each stage to be considered for the next stage.
> - Other than the minimum a threshold will be set based on how many teams should go into the next stage
> - Teams advancing to next stage will be
> $$
> \begin{align}
>  \text{PDR} \xrightarrow{13  \text{ teams}} &   \text{CDR} \\
>  \text{CDR} \xrightarrow{8  \text{ teams}}  &  \text{LRR} \\
>  \text{LRR} \xrightarrow{6  \text{ teams}}  &  \text{Finalist} \\
> \end{align}
> $$
> - and the number of participating teams in 2025 was: 1175
> - We can object their evaluation at max twice in each stage
> - Atleast 1 advisor per team (Teachers, academicians, instructors, and members of teams that have previously won the right to launch a rocket in any rocket competition (provided they are over 18 years of age) can participate as advisors)
> - Members can added or removed until the CDR submission date
> 
> 
> 
> 
> - maximum 2 second delay between apogee/nose down orientation and primary parachute deployment
> - 400-600 meters (1,312 to 1,969ft) range above ground, for secondary parachute deployment 
> - ![operation concept.png|600](/img/user/TeknoFest/attachments/operation%20concept.png)
> - Motor to be provided at range is Aerotech M1850 motor
> - separate tracking system for both rocket and payload
> - Altimeter will be provided on assembly day by teknofest
> - payload should be a minimum of 4kg
> 
> - CONTINUE FROM PAGE 16 i got bored :(

### 1. Core Aerodynamic Design Rules

- **Constant Diameter:** There must be no change in the rocket’s external body diameter along its flight axis.
- **Surface Gaps:** There should not be any gap larger than 0.1 mm between the airframe and its covers.
- **Prohibited Designs:** The use of movable flight control surfaces (movable fins in the tail area) that provide active flight control is strictly prohibited. Additionally, "Boat Tail" designs (base drag-reducing designs) are not allowed.
- **Protrusions:** Apart from necessary external sensors, antennas, and cameras, no components that lack a special function and create protrusions in the cross-sectional area or disrupt aerodynamic integrity may be used.
- **Protrusion Placement:** Any parts that do protrude into the rocket's cross-sectional area must be located beyond the new center of mass that emerges after the rocket motor has finished its burn.

### 2. Flight Dynamics & Stability

- **Target and Minimum Altitudes:** Your rocket must reach a minimum altitude of 8,000 ft. Furthermore, you must hit your officially declared target altitude with a maximum tolerance of **±15%**.
- **Stability Margin:** Rockets in the A4 category must have a stability value between 1.5 and 2.5 at Mach 0.3.
    - _Note on Calculation:_ The rulebook defines Static Margin (SM) as the dimensionless number obtained by dividing the distance between the center of pressure (XCP​) and the center of gravity (XCG​) by the rocket body diameter (DB​):
$$
SM = \dfrac{X_{CP}-X_{CG}}{D_{B}}
$$
- **Liftoff Speed:** The minimum exit speed of your rocket as it leaves the launch ramp must be at least 25 m/sec.
- **Launch Angle:** Rockets will be launched with an elevation angle of 85° from the ground.
### 3. Simulation & OpenRocket Requirements

- **Software Mandate:** It is mandatory to perform trajectory simulations using OpenRocket and attach the outputs to your reports.
- **Payload Configuration:** The payload must not be entered as an "Unspecified Mass". It must be specifically named "PAYLOAD" and its mass must be entered as a minimum of 4,000 grams (4 kg).
- **Launch Conditions:** You must use the exact values shown on the “Launch Simulation” screen provided in Figure 3.2 of the rulebook (e.g., wind speed, launch site altitude, launch rod length). Reports missing simulations with these exact values will not be evaluated.
- **Data Consistency:** The data in your submitted OpenRocket (.ork) files must be perfectly identical to the data presented in your PDR and CDR reports.

### 4. Materials & Structural-Aerodynamic Overlaps

- **Forbidden Materials:** You are strictly forbidden from using PVC, compressed paper/kraft, or PLA materials on surfaces exposed to aerodynamic forces, which includes the airframe, fins, and nose cone.
- **Flutter Resistance:** You must prove that the rocket fins are resistant to flutter, and the corresponding design and flutter analyses must be demonstrated in the PDR and CDR reports.
- **Aerodynamic Load Resistance:** The rocket must be resistant to loads acting on all aerodynamic surfaces (body tube, fins, nose cone).

### 5. Reporting Responsibilities (PDR, CDR, & LRR)

- **PDR & CDR Checkpoints:** The stability value at Mach 0.3 must be explicitly calculated and presented in both the Preliminary Design Report (PDR) and Critical Design Report (CDR).
- **Detailed Fluid Dynamics (CDR):** In your subsystem design reports (CDR phase), fluid dynamics analyses must be highly detailed, including the solution network used, boundary conditions, convergence details, fluid properties, results, and interpretation of the results.
- **Launch Readiness Report (LRR):** For the LRR, you must perform a final flight simulation using the actual, completed rocket data (final mass, thrust-to-weight values) to calculate the ramp exit speed.
- **Velocity Tolerance (CDR vs LRR):** When comparing the launch rail exit velocity values presented in your CDR against those obtained during the LRR phase, the two values must differ by no more than **±5%**.

Hello, I am an AI
