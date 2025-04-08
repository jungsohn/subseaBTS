Pipelines and Soil Mechanics
=============================

This section focuses on the design, analysis, and geotechnical considerations associated with subsea pipelines. These pipelines are essential for transporting oil, gas, and fluids between subsea structures and surface facilities. The interaction between pipelines and seabed soil is critical for ensuring structural integrity, stability, and longevity.

Pipeline Design Considerations
-------------------------------

Subsea pipelines are exposed to complex load combinations such as internal pressure, external hydrostatic forces, temperature gradients, and environmental loading. The design process includes:

- **Wall thickness design** for pressure containment
- **Thermal expansion analysis**
- **Stability analysis** on the seabed
- **Corrosion protection strategy**

Stress-Based Design
--------------------

Design codes such as **DNV-ST-F101** and **ASME B31.8** provide criteria for allowable stresses. Key analysis types include:

- **Axial stress** from pressure and temperature
- **Bending stress** due to seabed interaction and installation
- **Hoop stress** from internal/external pressure
- **Von Mises equivalent stress** check for combined loading

.. math::

   \sigma_{eq} = \sqrt{\sigma_{axial}^2 + 3\sigma_{hoop}^2}

Pipeline Buckling and Collapse
-------------------------------

Pipelines may experience:

- **Lateral buckling** from thermal expansion and axial compressive forces
- **Upheaval buckling** when the pipe is buried in soft soil
- **External pressure collapse** in deepwater due to high hydrostatic pressure

Mitigation measures include:

- Snake lay patterns
- Buckle initiators
- Rock dumping or trenching

Pipeline Stability
-------------------

Ensuring a pipeline remains in place under hydrodynamic loading is vital. Stability is assessed via:

- **On-bottom stability analysis**
- **Vertical penetration depth (VPD)**
- **Soil resistance factor (SRF)**

The **DNV-RP-F109** code provides methodologies based on pipe weight, hydrodynamic forces, and soil type.

Soil-Pipe Interaction
----------------------

Soil mechanics play a crucial role in determining how pipelines behave on or within the seabed.

- **Soft clays** may allow excessive settlement or cause free-spanning
- **Sands** offer better bearing resistance but may be prone to scour
- **Backfilling** or **trenching** can improve stability and thermal performance



Free Span and Route Selection
------------------------------

Pipelines must avoid excessive **free spans**, which can result in vibration, fatigue, or collapse.

- **Pre-lay surveys** identify seafloor irregularities
- **Route optimization** minimizes unsupported spans
- **Spanning criteria** include maximum span length, allowable deflection, and fatigue life

Site Investigation
-------------------

Geotechnical site investigation provides essential data for:

- Soil classification (clay, sand, silt, gravel)
- Shear strength and consolidation properties
- Undrained shear strength (su) profile
- CPTu and vane shear testing

The results are input into numerical models for structural and geotechnical simulations (e.g., PLAXIS, ABAQUS).

Pipeline Installation and Commissioning
----------------------------------------

Installation methods:

- **S-Lay**, **J-Lay**, **Reel-Lay**
- Pipe tension control and curvature limitations
- Touchdown monitoring using ROVs

Commissioning steps:

- Flooding, cleaning, and gauging
- Hydrostatic pressure testing
- De-watering and drying
- Final tie-in and pre-production checks

Corrosion and Failure
----------------------

Subsea pipelines are susceptible to various degradation mechanisms:

- **Internal corrosion** due to produced fluids (water, CO₂, H₂S)
- **External corrosion** due to seawater
- **Coating disbondment**
- **Fatigue failure** in free-span or high-cycle regions

Protection strategies include:

- **Fusion-bonded epoxy (FBE) coating**
- **Cathodic protection (sacrificial anodes or ICCP)**
- **Corrosion inhibitors injected via umbilicals**

.. note::

   A robust pipeline design integrates both structural mechanics and soil-structure interaction to withstand operational and environmental challenges.

