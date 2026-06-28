<h1 align="center">﷽</h1>
<h1 align="center">
<font size="6"><b>🛦 X-26 GREYWOLF PT-1</b></font>
</h1><br>

<h4 align="center">
  <b>The First High-Performance Experimental 12S EDF Prototype of the YF-26 GREYWOLF Program</b>
</h4>
<p align="center">
  <a href="#technical-specifications">Technical Specifications</a> •
  <a href="#visual-looks">Visual Looks</a> •
  <a href="#airframe-materials-list">Materials</a> •
  <a href="#electronics--propulsion-system">Electronics</a> •
  <a href="#system-wiring-diagram">Wiring Diagram</a> •
  <a href="#assembly-guide">Assembly</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>
<br>

> **Project Status:** Prototype 1 (PT-1) Engineering & CAD Phase Complete  
> **CAD Platform:** Autodesk Fusion 360  
> **Development Platform:** [Hackclub Stasis](https://stasis.hackclub.com/dashboard/projects/cmnfqlx3300nv01qimu2rgsk3)  
> **Design Time Investment:** 50+ Hours  
> **Source CAD File:** 💾 [Download Massive Fusion 360 (.f3d) File via Google Drive](adadas)

---

## Technical Specifications

The **X-26 GREYWOLF PT-1** is a high-speed, scratch-built experimental scale RC jet aircraft. It is designed around an advanced integrated propulsion duct system and multi-axis control surface layout to study RC level transonic airflow behavior and high-speed stability profiles at low altitudes.

* **Total Length of Aircraft:** 1.3 - 1.5 meters
* **Total height of Aircraft:** 0.3m (~30cm)
* **Fuselage Height:** 0.1m (~11cm)
* **Wingspan:** ~1.0 meter
* **Wing Area:** ~0.1 m²
* **Total Control Surfaces:** 6 channels (2x Flaps, 2x Ailerons, 2x Stabilators)
* **Landing Gear System(in Advanced version):** 3x Retractable landing gear assemblies featuring fully operational actuated bay doors.
* **Special Aerodynamic Feature:** Features an integrated custom-engineered S-Duct intake system designed to stabilize air intake turbulence under high static pressures.
* **Performance Profile:** Estimated empty airframe weight ranges from 2 - ~3 kg. Powered by a high-output 12S electric ducted fan producing between 4.0 - 5.0 kg of static thrust, the airframe targets a top speed vector of 100 - 110 mph.
* **Min-Takeoff Speed:** 21.3m/s-27.6m/s
* **Max-Takeoff Speed:** 24.6m/s-31.9m/s
* **Control Surface Mixing:** Symmetrical Flaperon deployment engaging 41.5% of total wing area 372.68cm^2, Max Takeoff Lift Coefficient to approx 0.165
*Note: The structural components, nose cone sections, and access hatches are modeled as independent components within the source assembly to allow for separate modular fabrication and easy battery bay access.*

---

## Visual Looks

<h3 align="center"><b>CAD Model Overview</b></h3>
<p align="center">
  <img width="1366" alt="CAD Side Perspective" src="https://github.com/user-attachments/assets/79038fe9-667d-4d73-b458-954ee69030db" />
  <img width="1366" alt="CAD Front-Side Perspective" src="https://github.com/user-attachments/assets/3ff2fcdd-5998-4d4d-89cd-29c2dfe3bb96" />
  <img width="1332" alt="CAD Front Perspective" src="https://github.com/user-attachments/assets/44b34efe-ddbe-4e03-9ad8-37d1d54cd98a" />
</p>

<h3 align="center"><b>High-Fidelity Rendered Visuals</b></h3>
<p align="center">
  <img width="1366" alt="Render 1" src="https://github.com/user-attachments/assets/2d3e70eb-05b6-482c-999b-a1dfd2cca9a0" />
  <img width="1366" alt="Render 2" src="https://github.com/user-attachments/assets/05801154-7e74-43a8-a288-93ab383051e0" />
  <img width="1366" alt="Render 3" src="https://github.com/user-attachments/assets/a454421b-2992-45c8-9742-f32c235d7944" />
  <img width="1366" alt="Render 4" src="https://github.com/user-attachments/assets/90b29206-22b7-4296-b81f-d5549d2630e6" />
</p>

> **Design Note on Airframe Influence:** > The X-26 Greywolf airframe is a unique blending of generation-defining design aspects. It utilizes high-efficiency forward intakes inspired by the F-22 Raptor, twin vertical stabilizing surfaces and an exhaust layout optimized similarly to the F-35 Lightning II, and Airframes structurally derived from the F-16 Fighting Falcon. 

---

## Airframe Materials List

For physical scratch-building replication, the structural framework utilizes a composite material approach to meet necessary power-to-weight and stress thresholds:

1. **Depron Foam (or 3D-Printed LW-PLA):** Used for lightweight external aerodynamic skin panels and minor interior structural formers.
2. **Carbon Fiber Spars & Rods:** Implemented across high-stress junctions, including main wing spars, tail pivots, and longitudinal fuselage reinforcement points.
3. **Aircraft-Grade Plywood:** Used selectively for high-vibration structural hardpoints, specifically the primary EDF mounting bracket and landing gear load plates.

---

## Electronics & Propulsion System

### Bill of Materials (BOM)

The electronics bay is configured to handle high-current throughput safely without the need for custom PCB distribution boards. All high-power connections must be hard-wired or connected using high-amperage bullet terminals.

| Component Name | Quantity | Purpose / System Role | Estimated Unit Price | Sourcing Link |
| :--- | :---: | :--- | :---: | :--- |
| **12S 80mm EDF Unit** | 1 | Primary Propulsion Unit | $86.87 | [AliExpress](https://www.aliexpress.com/item/1005005825766168.html) |
| **Hobbywing Skywalker 100A V2 ESC** | 1 | Electronic Speed Controller / Electronic Pump Functional Equivalent | ~PKR 10,800 | [SmartHobby](https://www.smarthobby.pk/product-page/hobby-wing-skywalker-100a-v2-esc) |
| **6S 5200mAh - 5900mAh LiPo Batteries** | 2 | Primary 12S DC Power Source (Split configuration) | ~PKR 19,000 | [Electrobes](https://electrobes.com/product/5200mah-22-2v-6s-40c-lipo-lithium-polymer-rechargeable-battery-pack-for-rc-drone/) |
| **TowerPro SG-90 Servos (180°)** | 6-10 | Actuators for flight control surface manipulation | ~PKR 300 | [Electrobes](https://electrobes.com/product/towerpro-sg-90-servo-motor-180-degree-rotation/) |
| **FlySky FS-iA10B Receiver** | 1 | 10-Channel Radio Control Signal Receiver Component | Excluded(not buying from hc money) | Core RC Gear |

---

## System Wiring Diagram

The PT-1 utilizes a point-to-point wiring schematic layout optimized for minimal line resistance and spatial balance within the narrow fuselage ribbing. 

<p align="center">
  <img width="1366" alt="Point to Point Wiring Schematic" src="https://github.com/user-attachments/assets/5e5e0da4-2eb1-411f-bb1d-6472232fde2c" />
  <img width="1366" alt="Internal Fuselage Electronics Layout" src="https://github.com/user-attachments/assets/3f0233a8-e0d2-44fd-b3ad-49cb08857d07" />
</p>

### Wiring Architecture Summary:
1. **High-Voltage Power Loop:** Two independent 6S LiPo battery packs are linked together in **series** via a heavy-duty **QS-8 Anti-Spark Series Harness** to deliver a unified 12S nominal voltage supply (44.4V nominal / 50.4V peak) directly to the DC inputs of the 100A ESC.
2. **Propulsion Drive Loop:** Three heavy-gauge phase wires route directly from the ESC output to the 80mm EDF brushless motor. (Note: Exhaust rotation direction can be quickly reversed by swapping any two of the three ESC-to-motor wire links).
3. **Low-Voltage Signal Loop:** Low-voltage power to the FlySky FS-iA10B receiver is stepping down cleanly from the main pack via the ESC's integrated Battery Eliminator Circuit (BEC) wire line. 
4. **Control Surface Actuation:** The 6 primary flight servos are synchronized efficiently across the receiver channels using heavy-duty Y-harness extensions to ensure uniform dual-aileron, dual-flap, and dual-stabilator tracking.


---

## Assembly Guide

The proper assembling procedure of the aircraft is as follows:-
<h3><b>THE SPINE</b></h3>
<p>The airduct of the plane has two major and very important roles in the aircraft, it serves as <b>THE SPINE</b> of the plane and the **The duct that** asissts the airflow.
It being <b>The Spine</b>  of the airplane, it will be the one hosting the airframe ribs.
</p>
 <img width="1366" height="538" alt="1" src="https://github.com/user-attachments/assets/9cad2ad2-679b-46e5-bb7c-b2a559e0663c" />
<h3><b>Air-Frame Ribs Placement</b></h3>
<p>  The cuted out airframed ribs are slided onto the air duct, which is the spine of the aircraft. 
</p>
 <img width="1366" height="538" alt="2" src="https://github.com/user-attachments/assets/fc8065d6-6a08-40e1-b84a-f4fe8436b946" />
 <h3><b> First Skin Placement</b></h3>
 After sliding on the Airframe ribs onto the Airduct..The lower fuselage skin is mounted onto the airframe ribs.
<img width="1366" height="538" alt="3" src="https://github.com/user-attachments/assets/bd53c298-0a0e-4170-9009-67793faf5ca3" />
<h3><b>Mounting Side panels</b></h3>
After mounting lower skin panel of the fuselage..the side skin panels are mounted onto the Airframe.
<img width="1366" height="538" alt="4" src="https://github.com/user-attachments/assets/56bde90f-c560-4918-9ed9-06ed85ac06bc" />
<h3><b>Adding support</b></h3>
3mm Carbon fibre rods are slided into the premade holes in airframes..the goal is to provide the airframe with a good tensile and torsion strength.
Also one of the rear support ribs are slided onto the carbin fibre rod for attatching to the main spine and be a part of the barrier against crushing G-force..Also the remaining side panels of the fuselage are mounted onto the rear support ribs.
<img width="1366" height="538" alt="5" src="https://github.com/user-attachments/assets/28dee7aa-5c37-4001-b8e6-f1f8ec763522" />
<h3><b>Mounting Inner Skin Panels</b></h3>
Rear Inner skin panels are also mounted onto the rear support ribs.
<img width="1366" height="538" alt="6" src="https://github.com/user-attachments/assets/d9b6258e-5694-4c6d-8049-25907753fb2f" />
<h3><b>Construction of the Stabs(stabilators)</b></h3>
The stab's construction is simple yet requires carefullness regarding the building process...The root aerofoil is mounted on the outer edges of the stab.
<img width="1366" height="538" alt="7" src="https://github.com/user-attachments/assets/3500fa88-abc2-4abe-8af1-41368810e282" />
After mounting the root aerofoil on the root edge of lower skin panel of the stab...
the upper skin panel is mounted onto the root aerofoil and the corresponding outer edges of the lower skin panel....
<img width="1366" height="538" alt="8" src="https://github.com/user-attachments/assets/91b89b96-a29b-4f61-95d0-0a94c7edb1a5" />
After sucessfully mounting skin panels and the root aerfoil to eachother...the pivot rod is slided into the premade hole in the root aero foil.... 
The stabilators are done being built.
<img width="1366" height="538" alt="9" src="https://github.com/user-attachments/assets/d7d34760-1f13-4736-8242-03564a8eb67b" />
<h3><b>Mounting The Remaining Skin Panels</b></h3>
The remaing rear lower skin panels of the fuselage are also mounted onto the rear support ribs of the Fuselage..with the side skin panels supporting it.
<img width="1366" height="538" alt="10" src="https://github.com/user-attachments/assets/918a7c45-ed82-418b-a4dd-8bda1591704a" />
After completing mounting the rear side of lower skin panels..The rear skin panels of the upper skin are also mounted onto the rear support ribs....
<img width="1366" height="538" alt="11" src="https://github.com/user-attachments/assets/cea30157-e479-403e-ba44-0f0dc5c32214" />
After mounting first rear skin panel of the upper skin...the second pair of skin panels are mounted onto the Airframe ribs...these two skin panels are directly sitting above the main propulsion unit of the UAV..
<img width="1366" height="538" alt="12" src="https://github.com/user-attachments/assets/74b71ae1-3379-441f-b14a-14ab8280a446" />
The side long skin panels are also mounted onto the Airframe ribs..these skin panels cover up the most of the Fuselage's upper skin....
<img width="1366" height="538" alt="13" src="https://github.com/user-attachments/assets/4741cf53-e4c4-4c5d-9e75-70095ca52627" />
The front upper skin panels of the Fuselage are mounted onto the front Airframe Ribs of the Airframe with the remaining upper side panels of the Airframe....the Cavity behind these panels is the space of the removeable panels that allow accessing the inner components of the Aircraft without needing to rip-apart the skin of the Aircraft.
<img width="1366" height="538" alt="14" src="https://github.com/user-attachments/assets/c4d5416e-9feb-473b-bec6-7d8db1f15961" />
<img width="1366" height="538" alt="15" src="https://github.com/user-attachments/assets/b63e0051-5842-4d73-9be4-7c76092d6c46" />
A brief 3d view for the Construction described so far.
<video src="https://github.com/user-attachments/assets/6bf46d65-2bc3-4322-bec0-19ca2d736067" autoplay loop muted width="100%"></video>

<h3><b>Mounting Engine Nozzle</b></h3>
The Engine nozzle is consisted of 5 panels..the first three panels are mounted onto the correspeonding edges of the Inner side panels and Upper skin panels....
<img width="1366" height="538" alt="16" src="https://github.com/user-attachments/assets/bfb93ec4-5818-4ef8-8e84-e338571f8c34" />
The fourth skin panel of the Engine nozzle is mounted onto the corresponding edges of the lower skin panel and onto the corresponding side edges of the second and thord side panels of the engnine side panels.
<img width="1366" height="538" alt="17" src="https://github.com/user-attachments/assets/7f59e64e-742c-46dc-961c-41e0e707e390" />
the last panel is the exhuast panel of the engine bay section, this can be replaced by a servo operated variable engine nozzle too, which is not the part of current development.
<img width="1366" height="538" alt="18" src="https://github.com/user-attachments/assets/bfd1ba1a-0dd0-4d33-bdf4-09afce0fcbac" />
<h3><b>Installing the Nose ribs</b></h3>



## Credits

* **My Father:** A seasoned professional in his aviation field who taught me the foundational mechanics of aircraft design, and inspired me to build this dream.
* **My Brother:** The catalyst who challenged me to test my limits, stepped up my design thinking, and introduced me to the open-source hardware community.
* **Hack Club Blueprint & Stasis Teams:** For establishing a development pipeline that empowers teenagers to scale up their hardware engineering skills and bring complex concepts to life.

---

## License

This project is open-source and tracking under the terms of the 
