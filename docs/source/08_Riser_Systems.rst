Riser Systems and Hydrodynamics
===============================

Risers are vertical or near-vertical pipelines that transport production fluids, injection fluids, or drilling fluids between the seabed and surface facilities such as Floating Production Units (FPU). This section covers the design, classification, and dynamic response of risers under environmental loads.

Types of Riser Systems
-----------------------

Risers are categorized based on application and configuration:

- **Top Tensioned Risers (TTRs)**  
  - Vertically suspended from tensioning devices on platforms (e.g., TLPs)
  - Common in drilling and dry tree production
  - High axial load and VIV sensitivity

- **Steel Catenary Risers (SCRs)**  
  - Curved risers suspended in a catenary shape
  - Suited for deepwater and harsh environments
  - Simpler design but sensitive to fatigue near touch-down point

- **Flexible Risers**  
  - Composite structures with multiple layers (carcass, pressure sheath, armor)
  - Tolerant to motion and suitable for FPSO and dynamic environments

- **Hybrid Riser Towers (HRTs)**  
  - Vertical column supported by buoyancy and connected to seabed via jumpers
  - Combines benefits of SCR and flexible riser systems

Riser Design Considerations
----------------------------

Riser design must account for:

- **Axial tension** and top tension requirements
- **Bending moments** and stress due to platform motion
- **Hydrodynamic loading** from waves and currents
- **Thermal expansion** and flow-induced vibration
- **Interaction with seabed (for SCRs)**

Key design codes:

- **API RP 2RD** – Riser design guidelines
- **DNVGL-ST-F201** – Dynamic risers
- **ISO 13628-7** – Flexible pipe systems

Hydrodynamic Analysis
----------------------

Risers are subject to time-varying forces from:

- **Wave kinematics** (Airy, Stokes, or irregular waves)
- **Current profiles** (uniform or shear)
- **Mooring dynamics of the host vessel**

Hydrodynamic forces are estimated using **Morison’s Equation**:

.. math::

   F = \frac{1}{2} \rho C_d A u|u| + \rho C_m V \frac{du}{dt}

Where:

- :math:`\rho` = water density  
- :math:`C_d`, :math:`C_m` = drag and inertia coefficients  
- :math:`u` = water particle velocity  
- :math:`A`, :math:`V` = projected area and displaced volume

Vortex-Induced Vibration (VIV)
-------------------------------

VIV occurs when periodic vortex shedding synchronizes with riser natural frequency.

- Can cause significant fatigue damage
- Common in TTRs and SCRs
- Affected by current speed, diameter, and riser tension

Mitigation methods:

- **Helical strakes**
- **Fairings**
- **Tuned Mass Dampers (TMDs)**



Touchdown and Seabed Interaction
---------------------------------

For SCRs, the **touchdown zone (TDZ)** is a critical fatigue hotspot.

- Soil stiffness affects bending stress
- Free span and cyclic loading lead to potential buckling
- Seabed trenching or rock dumping may be required

Time-Domain Dynamic Simulation
-------------------------------

Dynamic analysis tools simulate riser response under environmental loading:

- **OrcaFlex** – Coupled vessel-riser-mooring simulation
- **DeepRiser**, **Flexcom**, **SIMA** – Riser-specific modeling
- Include vessel motion (heave, pitch, surge), wave spectrum, and current shear

Analysis outputs:

- Tension and curvature profiles
- Time history of bending moments
- Fatigue damage at critical points
- VIV frequency response

Installation and Operation
---------------------------

Installation methods:

- **Over-boarding** using lay tower or A&R system
- **Hang-off and tensioning** from topside
- Pre-lay routing for SCRs to avoid excessive bending

Operational considerations:

- Dynamic loading from FPSO movement
- Start-up pressure and thermal cycling
- Inspection and maintenance at splash zone and TDZ

.. note::

   Riser systems are among the most dynamically sensitive components of offshore infrastructure. Accurate modeling and robust design are vital to prevent fatigue failure and ensure safe long-term operation.

