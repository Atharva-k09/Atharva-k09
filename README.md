<!-- ============ HEADER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Atharva%20Kalage&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Hardware%20Engineer%20%E2%80%A2%20PCBs%20%E2%80%A2%20FPGA%20%E2%80%A2%20Robotics&descSize=20&descAlignY=60" width="100%" alt="header"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=00F5D4&center=true&vCenter=true&width=760&lines=Designing+electronics+that+actually+survive+;Space-grade+mindset%2C+student+budget+;Schematic+%E2%86%92+PCB+%E2%86%92+bring-up+%E2%86%92+debug+%E2%86%92+repeat;Currently+building+a+pocket+oscilloscope+%E2%9A%A1" alt="Typing SVG" /></a>

<a href="https://www.linkedin.com/in/atharva-kalage-01692a28a"><img src="https://img.shields.io/badge/LinkedIn-let's_connect-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
<a href="mailto:atharvakalage@gmail.com"><img src="https://img.shields.io/badge/Email-hit_me_up-D14836?style=flat&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Status-open_to_hardware_roles-00F5D4?style=flat&labelColor=0d1117"/>
</div>


⚡ Who Am I
> name       : Atharva Kalage
> role       : Final-year E&TC engineer (CGPA 9.0/10) · PCCOER, Pune 🇮🇳
> obsessed   : reliable electronics, space-grade parts, clean PCBs
> intern     : Hardware @ Bit Mapper Integration  (Aug 2026 → Jan 2027)
> building   : STM32 + Pico portable scope / function gen / multimeter
> looking 4  : hardware design roles (PCB · high-reliability · FPGA/video · robotics)
I like hardware that works on the bench, then keeps working: sensible derating, clean power, protected inputs, and tests that go past "it powers on." 🔬
🔥 Currently
🛠️ Building	📚 Researching	🎯 Aiming for
Portable 3-in-1 test instrument (BE final-year project)	Space-grade & high-reliability components	Hardware design role in high-reliability / video / FPGA electronics


🧪 Projects
<details open>
<summary><b>⚡ Portable Multi-Utility Test Instrument</b> · BE final-year project</summary>

Battery-powered test instrument combining oscilloscope, function-generator and multimeter modes.
- Two-channel protected analog input and signal conditioning
- ADC-based acquisition, STM32 / Raspberry Pi Pico processing, IPS display
- Focus on input protection, measurement cursors and a compact enclosure
Tech: STM32 · Raspberry Pi Pico · ADC · Analog signal conditioning · IPS LCD
</details>

<details>
<summary><b>🛩️ STM32F405 Flight Controller PCB</b></summary>


Designed a compact flight-controller PCB, covering component selection, schematic capture and board layout. Organized the design into power, MCU/USB, sensors and motor-I/O sections, with pin-mux conflicts reviewed before routing.

Tech: STM32F405 · KiCad · PCB design · Schematic capture
</details>

<details>
<summary><b>🔋 Sensorless BLDC Motor Controller (ESC)</b></summary>


Designed a three-phase motor-controller concept from scratch, including the gate-driver and MOSFET power stage, complementary PWM with hardware dead-time, back-EMF sensing and protection review.

Tech: STM32 · MOSFETs · Gate drivers · PWM · BLDC control
</details>

<details>
<summary><b>🤖 Dual Swarm-Bot Warehouse Automation</b> · BE project</summary>


Two ESP32 robots coordinate warehouse tasks over ESP-NOW. The system uses auction-based task allocation, A* pathfinding and a shared docking station with priority-queue auto-charging.

Tech: ESP32 · ESP-NOW · A* · Multi-robot coordination
</details>

<details>
<summary><b>📡 3D LiDAR Scanner</b></summary>


Developed Raspberry Pi Pico firmware for LiDAR readout and stepper-motor control to perform 360° scanning. Point-cloud data is visualized in MATLAB and Processing.

Tech: Raspberry Pi Pico · LiDAR · Stepper motors · MATLAB · Processing
</details>

<details>
<summary><b>🚗 Dynamic Wireless EV Charging</b></summary>


Explored an in-motion wireless power-transfer concept using resonant inductive coupling, including coil geometry and performance under misalignment. The architecture secured copyright.

Tech: Resonant inductive coupling · Power electronics
</details>

<details>
<summary><b>👁️ Autonomous Vision-Based Pick-and-Place Robot</b></summary>


Built a robotic system using a Raspberry Pi camera-vision pipeline for object detection and an ESP32 for servo-motor actuation and coordinated pick-and-place control.

Tech: Raspberry Pi 4 · ESP32 · USB camera · Computer vision · Servo motors
</details>

<details>
<summary><b>📦 Line-Following and Pick-and-Place Robots</b></summary>


Built and tested autonomous robots as part of robotics work, contributing to schematics, electronics integration, embedded firmware and functional verification.

Tech: Embedded systems · Robotics · Motor control
</details>

<details>
<summary><b>⚡ Heart-Shaped LED Pendant</b> · Personal electronics project</summary>


Compact wearable LED-light concept with an ATtiny13A, multiple SMD LEDs, push-button-controlled blinking patterns, a small battery and USB-C charging.

Tech: ATtiny13A · SMD LEDs · PWM · MCP73831 · USB-C charging
</details>

<details>
<summary><b>🐾 Raspberry Pi Smart Pet Companion</b> · Prototype concept</summary>


Local-first companion concept using a Raspberry Pi Zero W, OLED and speaker, with planned microphone input, camera-based recognition and expressive responses.

Tech: Raspberry Pi Zero W · Python/Linux · OLED · Audio · Camera
</details>

<details>
<summary><b>🔌 HDMI Input Selector</b> · Hardware design concept</summary>


Two-input, one-output HDMI switching concept for an extended-temperature application, with attention to signal integrity and EMI/EMC constraints.

Tech: HDMI · High-speed digital interfaces · Signal integrity
</details>

🛠️ Toolbox
<div align="center">

EDA & CAD




FPGA & Simulation




Boards & Code





</div>

<details>
<summary><b>📖 Full skill breakdown (click to expand)</b></summary>
<br>

Area	What I do
Hardware design	Schematic capture, multi-layer PCB layout, component selection, datasheet analysis, BOM management, derating, DFM/DFT basics
Analog & power	LDO / buck / boost supplies, MOSFET gate drive, op-amp signal conditioning, ADC/DAC interfacing, power integrity & decoupling
High-reliability	Space-grade & high-precision component research, package/footprint review, operating-limit review, endurance testing
Video & digital interfaces	PAL/NTSC, HDMI, LVDS, DDR, PCIe, signal-integrity awareness, FPGA-facing signal paths
Validation & lab	Board bring-up, fault isolation, test planning, test reports; oscilloscope, logic analyzer, DMM, bench supplies
Embedded	STM32, ESP32, Raspberry Pi Pico, Arduino · I2C, UART, SPI · firmware-hardware integration


</details>

💼 Experience
<details open>
<summary><b>🛰️ Hardware Intern · Bit Mapper Integration</b> &nbsp;|&nbsp; Aug 2026 – Jan 2027</summary>
<br>

- 🔌 Supporting integration & debugging of HDMI, LVDS, DDR, PCIe, plus PAL/NTSC analog-video paths and FPGA-facing signals
- 🔍 Researching space-grade & high-reliability components from datasheets, package/footprint data and electrical specs
- 🧩 Contributing to hardware design: circuit-level investigation, component selection, interface engineering
- 📊 Running high-precision characterization & endurance tests; writing component comparisons, test records and technical reports for design reviews
</details>

<details>
<summary><b>🤖 Robotics Intern (Workshop Team) · RoboHawk</b> &nbsp;|&nbsp; 3 months</summary>
<br>

- Built & tested line-following and pick-and-place robots: schematics, electronics integration, firmware, functional verification
- Ran hands-on workshops on embedded systems & robotics for students
</details>

🧭 My hardware rules
01  Read the datasheet before the part hits the BOM.
02  Protect inputs. Decouple everything.
03  Review the schematic before you route a single trace.
04  "It powers on" is not a test plan.
05  If it isn't documented, it doesn't exist.
🎓 Education & certs
🎓 B.E. Electronics & Telecommunication · PCCOER, Ravet, Pune · Expected 2027 · CGPA 9.0/10

🏅 Altium Education: PCB Design  ·  MathWorks: MATLAB Onramp  ·  IIT Bombay (Spoken Tutorial): eSIM Training
📫 Let's build something
Hiring for PCB design, high-reliability electronics, video/FPGA interfaces or robotics hardware? Or just want to nerd out over gate-drive layouts?
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="footer"/>

</div>
