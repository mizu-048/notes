---
{"dg-publish":true,"permalink":"/akdc/rulebook/"}
---

The 2026 Abul Kalam Design Challenge requires teams to design and build an autonomous, self-contained robot capable of climbing a vertical copper pipe. The competition is divided into a mandatory **Foundation Challenge** and an optional **Advanced Challenge** focusing on precision and timed holds.

---

## Technical Specifications and Constraints

### Device Requirements

| **Feature**          | **Requirement / Constraint**                                                        |
| -------------------- | ----------------------------------------------------------------------------------- |
| **Maximum Diameter** | 400 mm                                                                              |
| **Maximum Length**   | 300 mm                                                                              |
| **Datum Surface**    | Top surface must be flat and even; used for reference and as an inversion switch    |
| **Containment**      | Must be totally self-contained; all starting mechanisms must travel with the device |
| **Attachment**       | Must be self-retaining on the pipe once positioned                                  |

### Pipe constraints

| **Feature**            | **Specification**                                                                                   |
| ---------------------- | --------------------------------------------------------------------------------------------------- |
| **Climbing Substrate** | 25 mm ∓ 2% diameter commercial copper rod                                                           |
| **Total Rig Height**   | 2200 mm ∓ 2% from the support platform                                                              |
| **Starting Position**  | Top of the device must be 400 mm above the base                                                     |
| **Pipe Condition**     | straightness error 4mm/2m "As bought" condition; no lubricants, tape, or surface treatments allowed |
|                        |                                                                                                     |

### Electronics constraints

| **Feature**         | **Requirement**                                                          |
| ------------------- | ------------------------------------------------------------------------ |
| **Power Source**    | Onboard batteries only (no tethers)                                      |
| **Maximum Voltage** | 12 Volts DC                                                              |
| **Safety Hardware** | Must include a clearly accessible main power switch and a fuse           |
| **Communication**   | All external communication (Wi-Fi, Bluetooth, RF) is strictly prohibited |

---

## Operational Requirements and Signaling

The device must communicate its status to judges through specific visual and auditory cues.

- **Green Light:** Must be visible and remain lit for the entire duration of the run.
- **Red Light & Buzzer:** Must activate during the 10-second hold at the intermediate target (Advanced Challenge) and when holding positions.
- **Start Procedure:** The operator must release the device within **two seconds** of activation.
- **Autonomous Operation:** Once started, the device must perform its mission and stop without any external support or human intervention.

---
## Marks

The total score is 100 marks, distributed across three main deliverables:
1. **Physical Model Performance (60 Marks):** Reliability, speed, and precision in the climbing challenges.
2. **Presentation (20 Marks):** A 5-minute briefing on engineering justifications and control logic.
3. **Technical Poster (20 Marks):** Must include a Free Body Diagram and motion visualizations.



      