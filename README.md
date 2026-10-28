<!-- ============ HEADER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Atharva%20Kalage&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Hardware%20Engineer%20%E2%80%A2%20PCBs%20%E2%80%A2%20FPGA%20%E2%80%A2%20Robotics&descSize=20&descAlignY=60" width="100%" alt="header"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=00F5D4&center=true&vCenter=true&width=760&lines=Designing+electronics+that+actually+survive+;Space-grade+mindset%2C+student+budget+;Schematic+%E2%86%92+PCB+%E2%86%92+bring-up+%E2%86%92+debug+%E2%86%92+repeat;Currently+building+a+pocket+oscilloscope+%E2%9A%A1" alt="Typing SVG" /></a>

<br/>

<a href="https://www.linkedin.com/in/atharva-kalage-01692a28a"><img src="https://img.shields.io/badge/LinkedIn-let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:atharvakalage@gmail.com"><img src="https://img.shields.io/badge/Email-hit_me_up-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Status-open_to_hardware_roles-00F5D4?style=for-the-badge&labelColor=0d1117"/>

</div>

<br/>

## ⚡ Who Am I

```text
> name       : Atharva Kalage
> role       : Final-year E&TC engineer (CGPA 9.0/10) · PCCOER, Pune 🇮🇳
> obsessed   : reliable electronics, space-grade parts, clean PCBs
> intern     : Hardware @ Bit Mapper Integration  (Aug 2026 → Jan 2027)
> building   : STM32 + Pico portable scope / function gen / multimeter
> looking 4  : hardware design roles (PCB · high-reliability · FPGA/video · robotics)
```

I like hardware that **works on the bench, then keeps working**: sensible derating, clean power, protected inputs, and tests that go past "it powers on." 🔬

---

## 🔥 Currently

| 🛠️ Building | 📚 Researching | 🎯 Aiming for |
|:---:|:---:|:---:|
| Portable 3-in-1 test instrument *(BE final-year project)* | Space-grade & high-reliability components | Hardware design role in high-reliability / video / FPGA electronics |

---

## 🧪 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Pocket Test Instrument
**Oscilloscope + function generator + multimeter in one battery-powered box.**<br>
🎓 *BE final-year project · in progress*

2-ch protected input → ADC → STM32 → IPS LCD. Built around **STM32 + Raspberry Pi Pico**.

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![ADC](https://img.shields.io/badge/ADC-signal_chain-00F5D4?style=flat-square) ![LCD](https://img.shields.io/badge/IPS_LCD-UI-9B5DE5?style=flat-square)

🔗 `stm32-portable-scope-multimeter` *(add link)*

</td>
<td width="50%" valign="top">

### 🚁 Flight Controller PCB
**STM32F405 board, multi-layer, compact.**

Component selection → schematic → layout in **KiCad**. Multi-sheet design (power, MCU + USB, sensors, motor I/O). Pin-mux conflicts caught in review, not on the bench.

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) ![STM32F405](https://img.shields.io/badge/STM32F405-03234B?style=flat-square) ![PCB](https://img.shields.io/badge/multi--layer-PCB-F15BB5?style=flat-square)

🔗 `stm32f405-flight-controller-pcb` *(add link)*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔋 Sensorless BLDC ESC
**Three-phase motor controller, designed from scratch.**

Gate drivers + MOSFET power stage, complementary PWM with hardware dead-time, back-EMF sensing, protection reviewed over multiple design-review rounds.

![Power](https://img.shields.io/badge/power_electronics-FEE440?style=flat-square&labelColor=222) ![Gate driver](https://img.shields.io/badge/gate_driver-00BBF9?style=flat-square) ![BLDC](https://img.shields.io/badge/BLDC-sensorless-00F5D4?style=flat-square)

🔗 `stm32-sensorless-bldc-esc` *(add link)*

</td>
<td width="50%" valign="top">

### 🤖 Dual Swarm-Bot Warehouse
**Two ESP32 robots that negotiate who does what.**

**ESP-NOW** mesh · **auction-based** task allocation · **A\*** pathfinding · shared docking station with **priority-queue auto-charging**.

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Robotics](https://img.shields.io/badge/robotics-multi--robot-9B5DE5?style=flat-square) ![A*](https://img.shields.io/badge/A*-pathfinding-00F5D4?style=flat-square)

🔗 `esp32-swarm-warehouse-automation` *(add link)*

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 3D LiDAR Scanner
**360° scanning with LiDAR + stepper motors.**

Pico firmware for LiDAR readout and stepper-driver control. Point clouds visualized in **MATLAB / Processing**.

![Pico](https://img.shields.io/badge/RPi_Pico-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square) ![LiDAR](https://img.shields.io/badge/LiDAR-point_cloud-00BBF9?style=flat-square)

🔗 `pico-3d-lidar-scanner` *(add link)*

</td>
<td width="50%" valign="top">

### 🚗 Dynamic Wireless EV Charging
**Charge while you drive: resonant inductive coil concept.**

Explored coil geometry under **misalignment**. Architecture **secured a copyright** ©️

![Wireless power](https://img.shields.io/badge/wireless_power-resonant-FEE440?style=flat-square&labelColor=222) ![EV](https://img.shields.io/badge/EV-charging-00F5D4?style=flat-square) ![Copyright](https://img.shields.io/badge/copyright-secured-9B5DE5?style=flat-square)

🔗 `dynamic-wireless-ev-charging` *(add link)*

</td>
</tr>
</table>

### 🧬 Signal chain of the test instrument

```mermaid
flowchart LR
    A[Probe CH1/CH2] --> B[Input protection]
    B --> C[Signal conditioning]
    C --> D[ADC]
    D --> E[STM32]
    E --> F[IPS LCD]
    G[Battery] --> H[Power rails]
    H --> E
    H --> F
    E --> I[Function generator out]
```

---

## 🛠️ Toolbox

<div align="center">

**EDA & CAD**

![Altium](https://img.shields.io/badge/Altium-A5915F?style=for-the-badge)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![EasyEDA](https://img.shields.io/badge/EasyEDA-1C6BFF?style=for-the-badge)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6F00?style=for-the-badge)

**FPGA & Simulation**

![Vivado](https://img.shields.io/badge/Vivado-E21F26?style=for-the-badge)
![Vitis](https://img.shields.io/badge/Vitis-E21F26?style=for-the-badge)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge)

**Boards & Code**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi Pico](https://img.shields.io/badge/RPi_Pico-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<details>
<summary><b>📖 Full skill breakdown (click to expand)</b></summary>
<br>

| Area | What I do |
|---|---|
| **Hardware design** | Schematic capture, multi-layer PCB layout, component selection, datasheet analysis, BOM management, derating, DFM/DFT basics |
| **Analog & power** | LDO / buck / boost supplies, MOSFET gate drive, op-amp signal conditioning, ADC/DAC interfacing, power integrity & decoupling |
| **High-reliability** | Space-grade & high-precision component research, package/footprint review, operating-limit review, endurance testing |
| **Video & digital interfaces** | PAL/NTSC, HDMI, LVDS, DDR, PCIe, signal-integrity awareness, FPGA-facing signal paths |
| **Validation & lab** | Board bring-up, fault isolation, test planning, test reports; oscilloscope, logic analyzer, DMM, bench supplies |
| **Embedded** | STM32, ESP32, Raspberry Pi Pico, Arduino · I2C, UART, SPI · firmware-hardware integration |

</details>

---

## 💼 Experience

<details open>
<summary><b>🛰️ Hardware Intern · Bit Mapper Integration</b> &nbsp;|&nbsp; Aug 2026 – Jan 2027</summary>
<br>

- 🔌 Supporting integration & debugging of **HDMI, LVDS, DDR, PCIe**, plus **PAL/NTSC analog-video paths** and **FPGA-facing signals**
- 🔍 Researching **space-grade & high-reliability components** from datasheets, package/footprint data and electrical specs
- 🧩 Contributing to hardware design: circuit-level investigation, component selection, interface engineering
- 📊 Running **high-precision characterization & endurance tests**; writing component comparisons, test records and technical reports for design reviews

</details>

<details>
<summary><b>🤖 Robotics Intern (Workshop Team) · RoboHawk</b> &nbsp;|&nbsp; 3 months</summary>
<br>

- Built & tested **line-following and pick-and-place robots**: schematics, electronics integration, firmware, functional verification
- Ran **hands-on workshops** on embedded systems & robotics for students

</details>

---

## 🧭 My hardware rules

```text
01  Read the datasheet before the part hits the BOM.
02  Protect inputs. Decouple everything.
03  Review the schematic before you route a single trace.
04  "It powers on" is not a test plan.
05  If it isn't documented, it doesn't exist.
```

---

## 🎓 Education & certs

🎓 **B.E. Electronics & Telecommunication** · PCCOER, Ravet, Pune · Expected 2027 · **CGPA 9.0/10**

🏅 Altium Education: PCB Design &nbsp;·&nbsp; MathWorks: MATLAB Onramp &nbsp;·&nbsp; IIT Bombay (Spoken Tutorial): eSIM Training

---

## 📈 GitHub stats

<div align="center">

<!-- Replace YOUR_USERNAME with your GitHub username -->
<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" />

</div>

---

## 📫 Let's build something

Hiring for **PCB design, high-reliability electronics, video/FPGA interfaces or robotics hardware**? Or just want to nerd out over gate-drive layouts?

<div align="center">

<a href="mailto:atharvakalage@gmail.com"><img src="https://img.shields.io/badge/📧_atharvakalage@gmail.com-0d1117?style=for-the-badge"/></a>
<a href="https://www.linkedin.com/in/atharva-kalage-01692a28a"><img src="https://img.shields.io/badge/💼_LinkedIn-0d1117?style=for-the-badge"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="footer"/>

</div>
