# J.A.H. DIRECT DRIVE HUB MOTOR SPECIFICATION
**Document Identifier:** PAS-RL-JTHM-2026-REV5  
**Publication Date:** October 2, 2026  
**Author & Sole Inventor:** Juho Artturi Hemminki  
**Intellectual Property Rights:** Strictly Proprietary / All Rights Reserved  
**Licensing Inquiries:** projectflagcarrier@gmail.com  

---

## 1. PREAMBLE & INTENT (JURIDICAL STATUS)
This document constitutes a formal, public, and legally binding **Defensive Publication** under global patent frameworks (including USPTO, EPO, WIPO, and PRH) to establish an unalterable timestamped baseline of prior art under the sole authorship of **Juho Artturi Hemminki**. 

The explicit intent of this publication is to permanently bar any third-party entity or multi-national corporation from obtaining monopoly patent rights over the mechanical geometries, fluidic traps, fluid-dynamic control mechanics, or business-case optimization logics detailed herein. All commercial exploitation, prototyping, mass production, and distribution rights are strictly and exclusively reserved by the Author.

---

## 2. THE CHASSIS-MOTOR COMPENSATION PARADIGM (THE BUSINESS INVENTIVE STEP)
Prior art traditionally evaluates in-wheel hub motors based purely on electromagnetic efficiency, disregarding the compounding capital expenditure (CapEx) of high-performance materials. This specification documents a novel **Chassis-Motor CapEx Cross-Compensation Paradigm** modeled conceptually on mass-manufactured, brushed universal appliance motors (e.g., historical Rosenlew manufacturing philosophies).

### 2.1 The Financial and Structural Trade-Off
*   **The Baseline Core:** The core of the electromagnetic actuator utilizes a traditional, low-cost structural topology (copper windings on laminated iron stators) driven by simplified power electronics. It completely bypasses the requirement for rare-earth permanent magnets (e.g., Neodymium, Dysprosium).
*   **The Compensation Vector:** The extensive manufacturing cost reductions achieved by using non-rare-earth, simplified winding topologies are systematically and deliberately reallocated to fund highly localized, high-performance material surfaces at the critical kinetic interfaces.
*   **Localized Material Allocation:** The cost savings directly finance chemical vapor deposition (CVD) or physical vapor deposition (PVD) titanium-nitride (TiN) or ceramic anti-galling/anti-corrosion boundaries precisely restricted to the fluidic friction zones, rendering an otherwise cost-prohibitive material architecture economically viable at an enterprise manufacturing scale.

---

## 3. MECHANICAL CONFIGURATION & ASCII SCHEMATICS

To eliminate mechanical wear, brush dust friction, and high-current arcing characteristic of physical carbon commutators under heavy vibrational loads, the physical brushes are replaced with an optimized room-temperature liquid metal alloy (specifically Gallium-Indium-Tin eutectics, hereafter referred to as *Galinstan-variant*).

The electrical bridge is established within a rigid, inverted outer-rotor wheel architecture where the wheel rim itself forms the rotating drum.

### 3.1 Transverse Cross-Sectional Assembly Layout

```
~~~~~ [ LIQUID METAL ALLOY ] ~~~~~
---------------------------------------

|   _______                             |
|  |       |  <-- REVERSE J-POCKET      |
|  |   ____|      FLUIDIC TRAP          |
|  |__|                                 |
---------------------------------------
^
|
[ROTATING WHEEL RIM / ROOT ROTOR]
```

### 3.2 Detail Window: The Reverse J-Pocket Geometry

```
                  STATIONARY INTERNAL SPACE (AXLE SIDE)
 -----------------------------------------------------------------------
                      |
                      |  [STATIONARY CONDUCTIVE CONTACT WING]
                      v
                 +----------+

                 | CONTACT  |
                 |   SHOE   |
                 +----+-----+
                      |
  ~~~~~~~~~~~~~~~~~~~~|~~~~~~~~~~~~~~~~~~~~~~~ <- LIQUID METAL LEVEL AT REST
 =====================v=======================

 |     ___________________________           |
 |    |                           |          |
 |    |   +-------------------+   |          | <- INVERTED J-LIP WALL
 |    |   |                   |   |          |    (Traps fluid outward)
 |    |   |                   |   |          |
 |    |___|                   |___|          |
 |                                           |
 |    [ROTATING RUNNING TRACK BASEMENT]      |
 =============================================
       Direction of Centrifugal Force (Fc) ---> Radially Outward
```

---

## 4. MATHEMATICAL & FLUID KINEMATIC MODEL

The stability of the liquid electrical bridge relies on the equilibrium between centrifugal force, hydrodynamic pressure, and viscous shear forces within the J-pocket geometry during angular acceleration.

### 4.1 Centrifugal Force Accumulation
The radial force $F_c$ acting on the liquid metal volume within the running track is governed by the equation:

$$F_c = m \cdot \omega^2 \cdot r$$

Where:
*   $m$ = Mass of the localized liquid metal volume ($\text{kg}$)
*   $\omega$ = Angular velocity of the outer wheel rim ($\text{rad/s}$)
*   $r$ = Radius from the center of the fixed vehicle axle to the J-pocket basement ($\text{m}$)

As $\omega \to \omega_{\max}$ (high-speed vehicle velocities), $F_c$ forces the fluid density into the deepest section of the inverted J-lip wall, increasing the contact pressure $P_c$ against the stationary contact shoe:

$$P_c = \frac{F_c}{A_c}$$

Where $A_c$ is the active submerged surface area of the stationary conductive contact wing. This mechanical compression guarantees that electrical contact resistance $R_{\text{contact}}$ approaches its theoretical minimum as vehicle velocity scales upward:

$$\lim_{v \to v_{\max}} R_{\text{contact}} = R_{\min}$$

### 4.2 Breakaway Torque Mechanics ($0\text{ RPM}$)
At $0\text{ RPM}$ (stationary position at a traffic light), $\omega = 0$, meaning $F_c = 0$. Gravity stabilizes the liquid alloy volume at the absolute nadir of the pocket. The immersion depth $h_i$ of the stationary contact shoe satisfies the condition:

$$h_i \ge \frac{1}{3} \cdot h_{\text{pocket}}$$

Upon the application of high-phase starting currents, the system utilizes the inherent high starting torque properties of a brushed universal motor configuration. Breakaway torque $T_s$ is maximized instantly due to the complete lack of mechanical field-brush drag ($F_f = 0$):

$$T_s = k \cdot \Phi \cdot I_{\text{start}}$$

Where:
*   $k$ = Constant of the winding geometry
*   $\Phi$ = Magnetic flux density
*   $I_{\text{start}}$ = Peak starting current allowed by the power stage

Because the electrical bridge lacks solid-to-solid friction interfaces, the mechanical drag torque component $T_{\text{drag}}$ is purely viscous, matching the Navier-Stokes thin-film approximation at low shear rates:

$$T_{\text{drag}} = \eta \cdot A_c \cdot \frac{v}{\delta}$$

Where:
*   $\eta$ = Dynamic viscosity of the Galinstan-variant alloy
*   $v$ = Peripheral velocity of the rotating track
*   $\delta$ = Clearance gap dimension between the shoe and the J-pocket floor

---

## 5. THERMAL AND ENVIRONMENTAL BOUNDARIES
*   **Low-Temperature Antifreeze Optimization:** The liquid metal alloy is metallurgically blended with fractional Bismuth (Bi) or Zinc (Zn) additives to depress the crystalline freezing point. This modification guarantees an uninterrupted, fully fluidic and functional state down to **$-40^\circ\text{C}$** without localized crystallization.
*   **Capillary Magnetic Labyrinth Seal:** To prevent external environmental contaminants (water, mud, sand, road salt) from invading the liquid contact track, the entrance throat of the J-pocket is guarded by a multi-stage magnetic fluid labyrinth seal. The stray magnetic field lines emanating from the internal stator windings are captured to pin a secondary protective ferrofluid ring in place, isolating the internal contact chamber hermetically.

---

## 6. THE JUHO ARTTURI HEMMINKI EXCLUSIVE PROPRIETARY LICENSE (J.A.H.-EPL)
This technology is STRICTLY PROPRIETARY. It is NOT open-source, it is NOT copyleft, and it is NOT bound by any public general public license architectures. All rights regarding the physical prototyping, reverse engineering, digital software simulation, replication, or commercial manufacturing of this architecture are strictly and exclusively reserved by the Author.

### 6.1 Commercial Use Restrictions
*   **Unauthorized Prototyping Prohibited:** No automotive manufacturer, corporate entity, academic research institute, or private hobbyist may build or test physical version of this Reverse J-Pocket liquid-metal topology without a written, signed commercial license agreement from Juho Artturi Hemminki.
*   **Mandatory Revenue Protocols:** Commercial application within electric cars, heavy transport vehicles, electric bikes, or industrial drivetrains requires a custom-negotiated corporate license framework, subject to unit-based manufacturing royalties and gross revenue-sharing matrices.

### 6.2 Licensing Contact and Business Inquiries
For all commercial inquiries, joint-venture proposals, investment alignment, or to obtain explicit legal manufacturing concessions, contact the sole author and rights-holder directly at:
 **projectflagcarrier@gmail.com**

---

**Author: Juho Artturi Hemminki**
