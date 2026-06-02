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

* **Fuselage Length:** 1.3 - 1.5 meters
* **Fuselage Height:** 30 cm
* **Wingspan:** ~1.0 meter
* **Wing Area:** ~1.0 m²
* **Total Control Surfaces:** 6 channels (2x Flaps, 2x Ailerons, 2x Stabilators)
* **Landing Gear System(in Advanced version):** 3x Retractable landing gear assemblies featuring fully operational actuated bay doors.
* **Special Aerodynamic Feature:** Features an integrated custom-engineered S-Duct intake system designed to stabilize air intake turbulence under high static pressures.
* **Performance Profile:** Estimated empty airframe weight ranges from 2 - ~3 kg. Powered by a high-output 12S electric ducted fan producing between 4.0 - 5.0 kg of static thrust, the airframe targets a top speed vector of 100 - 110 mph.

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

The step-by-step physical assembly tracking sequence for the PT-1 fuselage is structured as follows:

1. **Propulsion Core Installation:** Secure the internal S-duct intake tube structure directly to the primary structural bulkheads.
2. **Powerplant Integration:** Mount the 80mm EDF housing unit directly onto the reinforced plywood mounting brackets located at the center-rear alignment junction of the airframe ducting.
3. **Internal Structure Alignment:** Fix the primary interlocking longitudinal fuselage ribs and vertical bulkheads along the exterior boundary lines of the central air duct.
4. **Avionics & Actuator Routing:** Secure the servos into their respective precut frame brackets, thread the signal leads along the guide channels to the central receiver bay, and test overall surface throws before finalizing external panels.
5. **Skin Application:** Wrap and bond the external pre-contoured Depron foam panels or lightweight LW-PLA skins seamlessly over the completed structural rib cage.
If viusals are required u can look upto em under this short guide;

---

## Credits

* **My Father:** A seasoned professional in his aviation field who taught me the foundational mechanics of aircraft design, and inspired me to build this dream.
* **My Brother:** The catalyst who challenged me to test my limits, stepped up my design thinking, and introduced me to the open-source hardware community.
* **Hack Club Blueprint & Stasis Teams:** For establishing a development pipeline that empowers teenagers to scale up their hardware engineering skills and bring complex concepts to life.

---

## License

This project is open-source and tracking under the terms of the 
