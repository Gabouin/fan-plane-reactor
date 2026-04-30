![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Project](https://img.shields.io/badge/Project-Hardware-yellow.svg)
![Series](https://img.shields.io/badge/Series-Special_Issue-red.svg)

# Fan Plane Reactor



<table>
  <tr>
    <td width="17%">
      <img width=100% alt="image" src="https://github.com/user-attachments/assets/4230d8c9-1605-4a20-8a78-e097826deff4" />
    </td>
    <td>
      <p>
        A 3D-printed desktop fan designed to look like a jet engine / plane reactor. This project combines basic electronics with custom 3D-printed parts to build a functional and visually striking fan that captures the aesthetic of an aircraft turbine.
      </p>
    </td>
  </tr>
</table>




---

## Table of Contents

- [About the Project](#about-the-project)
- [Demo](#demo)
- [Bill of Materials](#bill-of-materials)
- [CAD Files](#cad-files)
- [CAD Previews](#cad-previews)
- [Wiring](#wiring)
- [Finished Build](#finished-build)
- [How to Build](#how-to-build)
- [License](#license)
- [Contributing](#contributing)

---

## About the Project

I built this project out of my passion for aviation and the iconic look of jet engines. It is a straightforward build — much simpler than my RC plane project — requiring only salvaged electronics and 3D-printed parts in PLA.

**To use it:**
1. Plug it in via USB-C.
2. Flip the on/off switch.
3. Control fan speed with the slide potentiometer.

---

## Demo

▶️ [Watch the demo on YouTube Shorts](https://youtube.com/shorts/CXMXyju0Se0)

---

## Bill of Materials

| Item | Description | Quantity | Source | Unit Price | Total |
|------|-------------|----------|--------|------------|-------|
| USB-C Charge Module | USB-C charge module (salvaged from a vape) | 1 | Salvaged | €0.00 | €0.00 |
| Printer Motor | DC motor (salvaged from a printer) | 1 | Salvaged | €0.00 | €0.00 |
| Switch | Simple on/off switch (salvaged from an old kit) | 1 | Salvaged | €0.00 | €0.00 |
| Slide Potentiometer | Variable resistor slider pot (salvaged from a guitar) | 1 | Salvaged | €0.00 | €0.00 |
| White PLA | [Wanhao White PLA 1kg](https://wanhao-europe.com/collections/filament-bambulab-pla-hyper-speed-anycubic-yumi-imprimante-3d/products/pla-wanhao-blanc-white-1kg?variant=47709592420692) | 492 g | Store purchase | €20/kg | €9.84 |
| Black PLA | [Wanhao Black PLA 1kg](https://wanhao-europe.com/collections/filament-bambulab-pla-hyper-speed-anycubic-yumi-imprimante-3d/products/pla-premium-wanhao-noir-1-1-75mm-1kg-ams-bambulab-ace-plastic-carton?variant=50468004168020) | 218 g | Store purchase | €20/kg | €4.36 |

> **Total estimated cost: ~€14.20** (when salvaging the electronic components)

---

## CAD Files

All CAD files are available in both **Fusion 360** (`.f3d`) and **STEP** (`.step`) formats for maximum compatibility.

| Component | Fusion 360 | STEP |
|-----------|-----------|------|
| Reactor structure | `CAD reactor/plane reactor.f3d` | `CAD reactor/plane reactor.step` |
| Motor adaptor | `CAD motor adaptator/motor adaptator.f3d` | `CAD motor adaptator/motor adaptator.step` |
| Support | `CAD support/support.f3d` | `CAD support/support.step` |

> CAD software used: **Autodesk Fusion 360**

---

## CAD Previews

<table>
  <tr>
    <td align="center"><b>Reactor Structure</b></td>
    <td align="center"><b>Support &amp; Adaptor</b></td>
    <td align="center"><b>Motor Adaptor</b></td>
  </tr>
  <tr>
    <td><img width="280" alt="CAD reactor structure" src="https://github.com/user-attachments/assets/9b99516f-dfd9-4b09-99d2-6a102600074e" /></td>
    <td><img width="280" alt="CAD support and adaptor" src="https://github.com/user-attachments/assets/872fbe4d-3a84-4ea6-ad65-6b9b7478bd3c" /></td>
    <td><img width="280" alt="CAD motor adaptor" src="https://github.com/user-attachments/assets/5b600248-3b59-4c38-ac3a-57e406fa5bfc" /></td>
  </tr>
</table>

---

## Wiring

The circuit is minimal: a USB-C module powers the motor through an on/off switch and a slide potentiometer for speed control.

<table>
  <tr>
    <td align="center"><b>Wiring Diagram — Overview</b></td>
    <td align="center"><b>Wiring Diagram — Detail</b></td>
  </tr>
  <tr>
    <td><img width="300" alt="Wiring diagram overview" src="https://github.com/user-attachments/assets/13a92b4d-e30a-4d6a-8c10-2024821da1ec" /></td>
    <td><img width="300" alt="Wiring diagram detail" src="https://github.com/user-attachments/assets/ff847a2a-23f0-4e58-a3d0-7e15594bcfbd" /></td>
  </tr>
</table>

---

## Finished Build

<table>
  <tr>
    <td><img width="260" alt="Finished project front view" src="https://github.com/user-attachments/assets/276703a6-88f4-4d57-90dc-81c76fbc1ad8" /></td>
    <td><img width="260" alt="Finished project side view" src="https://github.com/user-attachments/assets/bdc0ff73-3e33-4de7-b8f3-35edccd5f9fc" /></td>
    <td><img width="260" alt="Finished project back view" src="https://github.com/user-attachments/assets/3f68ac0d-f850-4f86-bd5b-4e94ed372aad" /></td>
  </tr>
</table>

---

## How to Build

1. **Print the parts** — Print all three components (`reactor structure`, `motor adaptor`, `support`) using PLA. White and black PLA are used for contrast, but any colour works.
2. **Assemble the motor** — Attach the printer motor to the reactor body using the motor adaptor.
3. **Mount the support** — Attach the support to the bottom of the reactor so it stands upright.
4. **Wire the electronics** — Follow the wiring diagrams above. Connect the USB-C module → switch → potentiometer → motor.
5. **Power on** — Plug in a USB-C cable, flip the switch, and adjust speed with the potentiometer.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## Contributing

Contributions, improvements, and remixes are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) guide to get started.
