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
  <a href="#electronics--propulsion-system">Electronics Strategy</a> •
  <a href="#system-wiring-diagram">Wiring Diagram</a> •
  <a href="#success-criteria--flight-goals">Flight Goals</a> •
  <a href="#assembly-guide">Assembly</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>
<br>

> **Project Status:** Prototype 1 (PT-1) Engineering, Aerodynamic Simulation & CAD Phase Complete  
> **CAD Platform:** Autodesk Fusion 360  
> **Development Pipeline:** [Hack Club Stasis Dashboard](https://stasis.hackclub.com/dashboard/projects/cmnfqlx3300nv01qimu2rgsk3)  
> **Design Time Investment:** 50+ Hours of High-Fidelity Surface Modeling  
> **Source CAD File:** 💾 [Download Massive Fusion 360 (.f3d) Assembly via Google Drive](https://github.com/47Abdullah47/X-26-GREYWOLF-PT-1/blob/Main-Project-PT-1/SOURCE%20FILE.md)

---

## Technical Specifications

The **X-26 GREYWOLF PT-1** is a high-speed, scratch-built experimental scale RC jet aircraft. It is engineered around an advanced integrated propulsion duct system and a multi-axis high-lift control surface layout to study level transonic airflow behaviors, intake fluid dynamics, and low-altitude flight stability.

* **Total Length of Aircraft:** 1.3 - 1.5 meters
* **Total Height of Aircraft (without landing Gear):** 0.3m (~30cm)
* **Fuselage Hull Height:** 0.1m (~11cm) *(Optimized to wrap tightly around the internal engine bay)*
* **Wingspan:** ~1.0 meter
* **Wing Area:** ~0.1 m²
* **Total Control Channels:** 6 Channels (2x Flaps, 2x Ailerons, 2x Stabilators)
* **Aerodynamic Design & Fluid Optimization:** Validated via rigorous computational fluid dynamics (CFD) steady-state solver testing run at a 20 m/s airspeed vector, establishing a baseline cruise lift coefficient ($C_L$) of 0.0141 and an ultra-low geometric shape drag coefficient ($C_D$) of 0.0018.
* **Special Intake Engineering:** Features a custom-modeled internal S-Duct intake routing system designed to stabilize incoming air turbulence and manage static pressure gradients under high mass flows.
* **Performance Profile:** Estimated empty airframe weight ranges from 2.0 to 3.0 kg. Powered by a high-output 12S electric ducted fan producing between 4.0 - 5.0 kg of static thrust, yielding a >1:1 thrust-to-weight ratio for a flight envelope targeting 100 - 110 mph.
* **Short-Runway (STOL) Takeoff Speeds:**
  * *Unladen / Light Test Rig (3.5 kg):* 21.3 m/s - 23.0 m/s (~76 km/h)
  * *Maximum Operational Testing Payload (4.5 kg):* 24.6 m/s - 26.1 m/s (~94 km/h)
* **Control Surface Mixing:** Implements symmetrical **Flaperon** mixing, deflecting both flaps and main ailerons together at takeoff. This transforms **41.5% of the total wing area ($372.68\text{ cm}^2$)** into an active camber-shifting high-lift surface, rocketing the maximum takeoff lift coefficient ($C_{L_{\text{max}}}$) to approximately 0.165.

*Note: The structural frames, nose cone mechanics, and intake paths are modeled as completely independent components within the source assembly to allow for modular fabrication and fast battery bay accessibility.*

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

> **Design Note on Airframe Influence:** > The X-26 Greywolf airframe merges generation-defining design aspects. It utilizes high-efficiency forward intakes inspired by the F-22 Raptor, twin vertical stabilizing surfaces and an exhaust layout optimized similarly to the F-35 Lightning II, and an internal structural distribution derived from the F-16 Fighting Falcon. 

---

## Airframe Materials List

The structural framework utilizes a lightweight, high-strength composite prototyping approach to handle structural stress thresholds while maximizing the power-to-weight ratio:

1. **Depron Foam / High-Speed LW-PLA:** Used for the aerodynamic outer skin contours, wing surfacing, and lightweight internal fuselage formers.
2. **Carbon Fiber Spars & Rods (3mm):** Integrated directly into high-stress structural joints, serving as the main wing load spars, tail pivot shafts, and longitudinal fuselage stiffeners.
3. **Aircraft-Grade Plywood:** Selected for high-vibration structural hardpoints, specifically the main 12S EDF engine mount and landing gear mounting plates.

---

## Electronics & Propulsion Strategy

The PT-1's avionics bay is engineered to safely sustain high continuous current loads. Comprehensive component sourcing, unit prices, and specific funding breakdowns are tracked in the dedicated [Bill of Materials Guide](BOM.md).

### Power Architecture Summary:
1. **High-Voltage Power Loop:** Two independent 6S LiPo battery packs (5200mAh - 5900mAh) are linked in **series** using a heavy-duty **QS-8 Anti-Spark Series Harness** to deliver a unified 12S nominal voltage supply (44.4V nominal / 50.4V peak) directly to the ESC.
2. **Propulsion Drive Loop:** High-gauge phase leads feed directly from the Hobbywing 100A V2 ESC to the brushless motor inside the 80mm fan shroud.
3. **Low-Voltage Signal Loop:** Signal power to the 10-channel FlySky receiver steps down cleanly via the ESC's integrated Battery Eliminator Circuit (BEC) lines.
4. **Control Surface Actuation:** Symmetrical servos are linked across the receiver layout using heavy-duty Y-harness extensions to maintain precise dual-aileron, dual-flap, and stabilator mechanical sync.

---

## System Wiring Diagram

The PT-1 utilizes a clean point-to-point wiring schematic optimized for minimal line resistance and spatial balance within the narrow fuselage ribbing. 

<p align="center">
  <img width="1366" alt="Point to Point Wiring Schematic" src="https://github.com/user-attachments/assets/5e5e0da4-2eb1-411f-bb1d-6472232fde2c" />
  <img width="1366" alt="Internal Fuselage Electronics Layout" src="https://github.com/user-attachments/assets/3f0233a8-e0d2-44fd-b3ad-49cb08857d07" />
</p>

---

## Success Criteria & Flight Goals

To rigorously evaluate the airframe engineering and telemetry code, the testing program focuses on three definitive goals:
1. **Aerodynamic Validation:** Confirm stable, level cruise tracking at a 20 m/s airspeed vector to ground-truth our baseline steady-state CFD dataset.
2. **STOL Performance:** Verify short-runway rotation and lift-off performance using the 41.5% trailing-edge flaperon configuration under incremental payload loads.


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
<h3><b>Installing the Nose ribs, nose panels, And completing the Fuselage</b></h3>
The Nose is installed by folowing a complex assembling procedure, the Battery block itself serves as a support, The two nose ribs are slided onto the carbon fibre rods, In this way the base of the nose is installed onto the Fuselage.
<img width="1366" height="538" alt="19" src="https://github.com/user-attachments/assets/7e56eac5-f999-4ce2-82db-d0a23321b380" />
The lower nose skin panels are installed onto the assembled Structure of the Nose
<img width="1366" height="538" alt="20" src="https://github.com/user-attachments/assets/b2ec6514-5b85-429a-b886-3be198fd8b95" />
After mounting the lower panels the side Skin panels are mounted onto the so far assembled nose strucutre.
<img width="1366" height="538" alt="21" src="https://github.com/user-attachments/assets/523d6682-1b4b-490c-b6df-2b4e80316580" />
After that The next Nose Rib is installed by three support brigdes,
<img width="1366" height="538" alt="22" src="https://github.com/user-attachments/assets/454351b3-7512-4cad-9998-8d04b7e84a20" />
After adding the next rib, the corresponding side Skin panels are mounted.
<img width="1366" height="538" alt="23" src="https://github.com/user-attachments/assets/2bb6f701-5ef8-4b14-907f-deb8fedfe95b" />
After mounting Side skin panels, the corresponding upper Skin panel is mounted 
<img width="1366" height="538" alt="24" src="https://github.com/user-attachments/assets/1f089d55-bbdc-406c-9420-d3460de044a3" />
after that, another Rib is added to the structure, and corresponding remaining side skin panels are mounted on, 
<img width="1366" height="538" alt="25" src="https://github.com/user-attachments/assets/7e435fc4-6c61-4a63-b00c-a7110ddb68fc" />
After that the last remaining upper skin panel is mounted.
<img width="1366" height="538" alt="26" src="https://github.com/user-attachments/assets/fa1d4f05-e814-4507-93bc-1e9d97bc93b2" />
THE DIVERGERS:-
The divergers are mounted on the tip of the lower intake Skin panel, Its purpose is to separate the low speed skin air from the high speed air,
<img width="1366" height="538" alt="27" src="https://github.com/user-attachments/assets/ecb153b1-d141-49aa-90e1-0287ef52b6e8" />
After All of this process the Construction of the Fuselage is done.
<img width="1366" height="538" alt="28" src="https://github.com/user-attachments/assets/6d77f3e3-ec05-424b-862f-59c6b899b1b6" />
<h3><b>Assembling the V-tails</b></h3>
The Ribs of the tails are mounted onto the one side of the Skins of the tail, 
<img width="1366" height="538" alt="29" src="https://github.com/user-attachments/assets/d37fb54a-03ca-4390-a3cb-6ceb2670ac82" />
After joining the Ribs with one skin, The other skin is mounted onto the ribs and the other skin,
<img width="1366" height="538" alt="30" src="https://github.com/user-attachments/assets/079b0012-5c5a-4f3e-98b7-d9b1696167c4" />
Just like this the second tail is constructed, After joining skins and the ribs of the tail, the lower base root panel is mounted, sealing the whole structure,
<img width="1366" height="538" alt="31" src="https://github.com/user-attachments/assets/072e8ab3-05ba-4d66-8c9d-bffb2efb1bcc" />
After that carbon fibre support rods are slided into pre-built holes in the root panel,
<img width="1366" height="538" alt="32" src="https://github.com/user-attachments/assets/a9cfc476-e97e-4902-8a7e-686b098ddea0" />
This support rib is situated perpendicular to the actuator support of the STABS, its purpose is to lockin the Carbon fibre support Rods of the V-tails.
<img width="1366" height="538" alt="33" src="https://github.com/user-attachments/assets/b69ce9b7-f5e2-4750-bcfb-1e400b1055ac" />
The Tails are slided into the Fuselage, Like This, (this is the inner view removing the outer skin panel from the vie)
<img width="1366" height="538" alt="34" src="https://github.com/user-attachments/assets/48dafd77-78fb-48f7-b434-74358d444251" />
And with that The V-tails are fused into the Fuselage.
<img width="1366" height="538" alt="35" src="https://github.com/user-attachments/assets/720e0554-709f-4555-b594-793835ee5c15" />
<h3><b>Assembling the Wings</b></h3>
<img width="1366" height="538" alt="36" src="https://github.com/user-attachments/assets/59dfd546-9cee-4510-ba1c-eebf2c2f94df" />
<img width="1366" height="538" alt="37" src="https://github.com/user-attachments/assets/a4a8a5ef-414d-44af-9db5-affc3413087f" />
<img width="1366" height="538" alt="38" src="https://github.com/user-attachments/assets/363f8d9c-ffb2-4469-a5d2-6f847c873db9" />
<img width="1366" height="538" alt="39" src="https://github.com/user-attachments/assets/9aa8064d-d71d-4d98-971d-f2dabbd7c36c" />
<img width="1366" height="538" alt="40" src="https://github.com/user-attachments/assets/c86da0d9-57fd-409d-b738-5cfbad9dd27f" />
<img width="1366" height="538" alt="41" src="https://github.com/user-attachments/assets/5cac93d6-a959-403e-a891-4389b29041fd" />
<img width="1366" height="538" alt="42" src="https://github.com/user-attachments/assets/acaf5d64-9801-4471-bcb2-cb461eb02269" />
<img width="1366" height="538" alt="43" src="https://github.com/user-attachments/assets/4f81f428-d731-4538-b3e4-21708eab2146" />
<img width="1366" height="538" alt="44" src="https://github.com/user-attachments/assets/1464d4ca-313f-4bce-8ab6-a5f8f7711c8c" />
<img width="1366" height="538" alt="45" src="https://github.com/user-attachments/assets/f25bf9c6-c438-430c-9db9-7f0ca2e6d81f" />
<img width="1366" height="538" alt="46" src="https://github.com/user-attachments/assets/8c79dff0-5b6f-4311-8389-1c54730089ed" />
<img width="1366" height="538" alt="47" src="https://github.com/user-attachments/assets/75ae0f1f-d8b5-45ce-b8ad-f602ce878d67" />
<img width="1366" height="538" alt="48" src="https://github.com/user-attachments/assets/4b74a3ac-32fa-450b-882f-78eb372b3c5a" />
<img width="1366" height="538" alt="49" src="https://github.com/user-attachments/assets/db458059-57dc-4933-b148-711c1462742e" />
<img width="1366" height="538" alt="50" src="https://github.com/user-attachments/assets/47779cfa-6499-4c5a-b14a-92249d6a9792" />
<img width="1366" height="538" alt="51" src="https://github.com/user-attachments/assets/1d3fa0d9-52c7-4c26-a47b-9a8dafe4b6cd" />
<img width="1366" height="538" alt="52" src="https://github.com/user-attachments/assets/9c94f0e6-c014-4424-bc87-e822c60ab540" />
<img width="1366" height="538" alt="53" src="https://github.com/user-attachments/assets/7d6da8ea-4f58-4924-a2f3-2dcdd666cc03" />
<img width="1366" height="538" alt="54" src="https://github.com/user-attachments/assets/5b3bc090-c49d-4128-9781-f3aeb838bb01" />
<img width="1366" height="538" alt="55" src="https://github.com/user-attachments/assets/eff82d22-f6c3-44cd-8a07-a69ddbf07082" />
<img width="1366" height="538" alt="56" src="https://github.com/user-attachments/assets/9f3aedcd-6745-49d4-998a-770b40e941c3" />
<img width="1366" height="538" alt="57" src="https://github.com/user-attachments/assets/4337ca2e-d7de-4df8-88cf-fe6ba2eccf42" />
<img width="1366" height="538" alt="58" src="https://github.com/user-attachments/assets/56fe2667-f0f1-4000-a86b-bb75fc63a81c" />
<img width="1366" height="538" alt="59" src="https://github.com/user-attachments/assets/241ba5a1-f5dc-46c7-a569-fd42f4c9a28f" />
<img width="1366" height="538" alt="60" src="https://github.com/user-attachments/assets/95dceee6-6e19-4479-937a-b394fb06a36b" />


---

## Credits

* **My Father:** A seasoned professional in his aviation field who taught me the foundational mechanics of aircraft design, and inspired me to build this dream.
* **My Brother:** The catalyst who challenged me to test my limits, stepped up my design thinking, and introduced me to the open-source hardware community.
* **Hack Club Blueprint & Stasis Teams:** For establishing a development pipeline that empowers teenagers to scale up their hardware engineering skills and bring complex concepts to life.

---

## License

This project is open-source and licensed under the terms of the MIT License.
