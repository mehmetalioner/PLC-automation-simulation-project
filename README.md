# PLC Simulation Project (Conveyor + Sensor + Actuator)

## Overview
This project simulates a small automation process using Siemens S7 PLC logic in TIA Portal.

### Core Logic
- Conveyor motor starts with START button.
- Sensor detects object and activates a pusher.
- Emergency stop shuts down the system safely.

### Fault Handling
- Emergency stop stops conveyor and actuator immediately.
- Restart requires STOP + START sequence.

### Migration
Logic structured in OB1, DB1 with symbols for clarity.

### Notes
- Project prepared in LAD (Ladder Logic).
- For educational & demonstration purposes only.
