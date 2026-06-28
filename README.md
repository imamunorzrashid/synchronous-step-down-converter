# Low-EMI 4-Layer Synchronous Step-Down Converter (LMQ61460-Q1)

A 4-layer synchronous buck converter designed around the **Texas Instruments LMQ61460-Q1** automotive-grade regulator. The converter steps an input voltage of **26 V (30 V maximum)** down to **5 V at up to 6 A** while emphasizing **low electromagnetic interference (EMI)** through careful PCB layout and stack-up design.

---

## Overview

This project was developed to gain practical experience in high-frequency power electronics and EMI-aware PCB design. Particular attention was given to minimizing switching noise by following the layout recommendations provided in the LMQ61460-Q1 datasheet.

The design uses a **4-layer PCB** to improve return-current paths, reduce radiated emissions, and enhance thermal performance.

---

## Specifications

| Parameter           | Value                         |
| ------------------- | ----------------------------- |
| Controller          | Texas Instruments LMQ61460-Q1 |
| Topology            | Synchronous Buck Converter    |
| Input Voltage       | 26 V nominal (30 V maximum)   |
| Output Voltage      | 5 V                           |
| Output Current      | 6 A                           |
| Switching Frequency | 2.1 MHz                       |
| PCB                 | 4 Layers                      |

---

## Design Highlights

* 4-layer PCB optimized for low EMI
* Continuous ground planes for reduced return-loop inductance
* Stitching vias to improve grounding and thermal conduction
* Compact switching loop following TI layout guidelines
* Copper pours for improved current handling and heat dissipation
* Surface-mount component implementation for reduced parasitics

---

## PCB Stack-up

The PCB uses four layers:

* Layer 1 — Components and power routing
* Layer 2 — Solid ground plane
* Layer 3 — Signal and power routing
* Layer 4 — Ground plane and thermal dissipation

This stack-up reduces radiated EMI and provides low-impedance return paths for high-frequency switching currents.

---

## Design Resources

The design was developed primarily using the recommendations presented in the **Texas Instruments LMQ61460-Q1 datasheet**, with additional PCB layout insights from the *Kevin Does EE* educational channel.

---

## Repository Contents

* PCB layer images
* 3D PCB renderings
* Design overview
* Project documentation

> **Note:** The original KiCad project files were unfortunately lost due to a storage failure. This repository preserves the completed PCB design and documentation for reference.

---

## Future Improvements

* Replace electrolytic capacitors with compact tantalum or ceramic capacitors
* Further optimize switching-loop layout
* Validate conducted and radiated EMI experimentally
* Perform thermal characterization under full-load operation

---

## Author

**Mamun Or Rashid**

B.Sc. in Mechatronics Engineering
Rajshahi University of Engineering & Technology (RUET)

---

## License

Released under the MIT License.
