# CC-Laser-Module

This project is a **high-power handheld visible-laser emitter** using a **6–7W 445nm diode module**, controlled through a **constant-current laser driver** with **microcontroller-based soft-start and safety interlock** functions.

The laser diode is mounted in a **copper heat spreader** and secured to a **fan-assisted aluminum heatsink** to maintain stable thermal operation during extended use. Power is supplied by a **protected 18650 battery pack** with both **fuse** and **BMS** for safe current delivery and cell balancing.

The enclosure is **CAD-modeled and 3D printed** for ergonomic handling, secure optical alignment, and ease of maintenance or part replacement.

Firmware functions include:
- Trigger input handling and debounce  
- Controlled current **ramp-up** to protect the diode  
- **Fault detection and cutoff**  
- Optional **continuous, burst, or pulsed** output modes  

These features ensure consistent, reliable performance while minimizing thermal and electrical stress on the optical components.
