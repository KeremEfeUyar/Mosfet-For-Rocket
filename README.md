# Mosfet For Rocket
Mosfet for rockets
<img width="977" height="722" alt="image" src="https://github.com/user-attachments/assets/c4c7ca5a-14cb-4a6c-b918-4bd51d3f79b6" />
<img width="927" height="602" alt="image" src="https://github.com/user-attachments/assets/2f720686-41bc-4e66-8fac-0e2ae0213738" />
This project is a **MOSFET-based pyro-driver circuit card** designed to provide safe ignition (pyro) control in avionics systems and model rocketry applications.
* **Safe Power Control:** Power received from the `J3` terminal block is protected at the hardware level by the `SW1` switch and `F1` fuse.
* **MOSFET Driver Circuit:** Safely triggers high-current loads (igniters) via the `Q1` MOSFET; provides reverse current/voltage protection with a pull-down resistor (`R2`) and flyback diode (`D1`).
* **Noise Reduction:** Designed with a full-coverage GND copper fill (filled zone) architecture on the `B.Cu` layer.
* **Production Ready:** Designed in KiCad and has passed all DRC (Design Rule Check) tests with zero errors.


