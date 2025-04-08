Subsea Control Systems
=======================

Subsea control systems are critical for the operation, safety, and integrity of offshore production facilities. These systems transmit commands from topside or onshore control rooms to subsea valves, sensors, and actuators, enabling real-time monitoring and control of the entire subsea architecture.

System Overview
----------------

A typical subsea control system includes:

- Subsea Control Module (SCM)
- Subsea Distribution Unit (SDU)
- Umbilicals (power, signal, fluid)
- Master Control Station (MCS, topside)
- Hydraulic Power Unit (HPU, topside or local)



Subsea Control Module (SCM)
----------------------------

The SCM is mounted on subsea trees or manifolds and acts as the **brain** of the subsea system. It includes:

- Solenoid valves for hydraulic actuation
- Pressure and temperature sensors
- Communication units (modem or fiber)
- Redundant power supplies and diagnostic circuits

Functions:

- Execute valve commands from topside
- Transmit sensor data to operators
- Monitor system status and trigger shutdowns

Electrical and Hydraulic Power
-------------------------------

Subsea systems require both **electrical power** (for control and data) and **hydraulic power** (for valve actuation).

- Electrical:
  - 24VDC or 48VDC low-power distribution
  - Fiber optics for high-speed telemetry
  - EMC shielding is critical in long umbilicals

- Hydraulic:
  - Provided via **umbilicals** from topside HPUs
  - Used for opening/closing gate valves and shear rams
  - Redundant lines are common (Main + Hot Backup)

Control Umbilicals
-------------------

Umbilicals are multi-core cables containing:

- Electrical conductors (signal, power)
- Hydraulic tubing (fluid delivery)
- Optical fibers (data)
- Chemical injection lines

Design considerations:

- Cross-sectional layout (spiral, bundled, modular)
- Minimum bend radius (MBR)
- Tension and torsion during installation
- Wet-mateable or dry-mateable connectors at terminations

Sensors and Feedback
---------------------

Subsea systems utilize multiple sensors for real-time data acquisition:

- **Pressure sensors** (wellbore, annulus, control lines)
- **Temperature sensors** (production fluid monitoring)
- **Position sensors** (valve confirmation)
- **Leak detection** (in umbilicals or SCMs)

Data from sensors is transmitted via SCMs to topside using modbus, CANbus, or proprietary protocols.

Communication and Redundancy
-----------------------------

Modern control systems adopt fault-tolerant architectures with:

- Dual SCMs (primary and backup)
- Fiber optic ring networks
- Redundant subsea modems
- Fail-safe default states (e.g., valves close on power loss)

Common protocols:

- Modbus RTU/TCP
- CANopen for subsea control networks
- IEC 61850 for integration with digital oilfield systems

Valve Actuation and Control Logic
----------------------------------

Valves are typically actuated via:

- **Electro-Hydraulic Valve Actuators (EHVA)**
- **Electric Actuators (all-electric subsea systems)**

Logic control layers include:

- Low-level device logic (in SCM)
- Mid-level control sequences (via MCS PLC)
- High-level SCADA or DCS integration (onshore)

Subsea Safety and Shutdown
---------------------------

Emergency shutdown functionality is integrated into the control logic:

- **ESD (Emergency Shutdown)**
- **HIPS (High-Integrity Pressure Protection System)**
- **SSIV (Subsea Isolation Valve)**

These systems are designed to act autonomously when specific thresholds are exceeded, ensuring asset protection and environmental safety.

.. note::

   The trend toward **all-electric subsea systems** reduces hydraulic complexity, improves modularity, and supports longer step-outs in deepwater fields.

