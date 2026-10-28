<h1 align="center">Atharva Kalage</h1> <p align="center"><b>Hardware Engineer · FPGA · PCB Design · CAD · Robotics · Signal Analysis</b><br> Reliable & space-grade electronics | Final-year E&amp;TC, Pune, India 🇮🇳</p> <p align="center"> <a href="https://www.linkedin.com/in/atharva-kalage-01692a28a"><img src="https://img.shields.io/badge/LinkedIn-Atharva_Kalage-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a> <a href="mailto:atharvakalage@gmail.com"><img src="https://img.shields.io/badge/Email-atharvakalage@gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a> <img src="https://img.shields.io/badge/Open_to-Hardware_Design_Roles-2ea44f" alt="Open to hardware design roles"> </p>
👋 About me

I'm a final-year B.E. Electronics and Telecommunication student at Pimpri Chinchwad College of Engineering & Research (PCCOER), Pune (CGPA 9.0/10, expected 2027), focused on hardware design: schematics, multi-layer PCBs, power stages, and the interfaces that connect video and digital systems.

I care about electronics that keep working: sensible derating, solid power integrity, protected inputs, and testing that goes beyond "it powers on." That mindset is what draws me toward high-reliability and space-grade hardware, which I'm currently researching hands-on through my internship.

Currently

🔧 Hardware Intern at Bit Mapper Integration (Aug 2026 – Jan 2027): video/digital interface integration, component research, characterization and endurance testing.
🛠️ Building a portable oscilloscope + function generator + multimeter in one battery-powered instrument.
🎯 Looking for hardware design roles (PCB design, high-reliability electronics, FPGA/video interfaces).
🧰 Skills
Area	What I work with
Hardware design	Schematic capture, multi-layer PCB layout, component selection, datasheet analysis, BOM management, derating, DFM/DFT basics
Analog & power	LDO / buck / boost supplies, MOSFET gate drive, op-amp signal conditioning, ADC/DAC interfacing, power integrity & decoupling
High-reliability	Space-grade and high-precision component research, package/footprint review, operating-limit review, endurance testing
Video & digital interfaces	PAL/NTSC, HDMI, LVDS, DDR, PCIe; interface integration, signal-integrity awareness, FPGA-facing signal paths
Validation & lab	Board bring-up, fault isolation, test planning, test reports; oscilloscope, logic analyzer, DMM, bench supplies
Signal analysis	ADC capture chains, waveform measurement, point-cloud/data visualization in MATLAB
Robotics	Line-following and pick-and-place robots, multi-robot coordination, motor drivers
CAD	Fusion 360 (enclosures, mounts, mechanical fit)
Microcontrollers	STM32, ESP32, Raspberry Pi Pico, Arduino; I2C, UART, SPI

Tools

Show Image Show Image Show Image Show Image Show Image Show Image Show Image Show Image Show Image Show Image Show Image

🚀 Featured projects
1. Multi-Utility Test Instrument (BE Final-Year Project, in progress)

Oscilloscope + function generator + multimeter in one portable, battery-powered device.

Built around STM32 and Raspberry Pi Pico: 2-channel input through a protection circuit → ADC → STM32, displayed on an IPS LCD.
Three modes in one device, designed around a battery supply for field use.
Focus: input protection, ADC accuracy, signal capture, UI.
🔗 Repo: stm32-portable-scope-multimeter (add link)
🏷️ STM32 ADC IPS-LCD signal-analysis battery-powered
2. Sensorless BLDC Motor Controller (ESC)

Three-phase BLDC speed controller designed from scratch.

Power stage with gate drivers and MOSFETs, STM32 control with complementary PWM (hardware dead-time).
Back-EMF sensing for sensorless commutation, overcurrent protection and decoupling reviewed over multiple design-review cycles.
Focus: power-stage design, gate drive, protection, design review.
🔗 Repo: stm32-sensorless-bldc-esc (add link)
🏷️ power-electronics BLDC gate-driver STM32 EasyEDA
3. STM32F405 Flight Controller PCB

Compact multi-layer flight controller board.

Component selection, schematic capture and board layout in KiCad.
Multi-sheet schematic (power, MCU + USB, sensors, motor I/O), with pin-mux conflicts found and documented during review.
Focus: high-density layout, power integrity, peripheral/pin planning.
🔗 Repo: stm32f405-flight-controller-pcb (add link)
🏷️ PCB-design KiCad STM32F405 flight-controller
4. Dual Swarm-Bot Warehouse Automation

Two cooperating ESP32 robots for warehouse tasks.

ESP-NOW mesh communication, auction-based task allocation, A* pathfinding.
Shared docking station with priority-queue auto-charging.
Focus: multi-robot coordination, power/charging, system integration.
🔗 Repo: esp32-swarm-warehouse-automation (add link)
🏷️ robotics ESP32 ESP-NOW multi-robot pathfinding
5. 3D LiDAR Scanner

360° scanning using a LiDAR module and stepper motors.

Raspberry Pi Pico firmware for LiDAR readout and stepper-driver control.
Point clouds visualized in MATLAB / Processing.
Focus: sensor interfacing, motion control, data visualization.
🔗 Repo: pico-3d-lidar-scanner (add link)
🏷️ LiDAR Raspberry-Pi-Pico stepper-motor MATLAB point-cloud
6. Dynamic Wireless EV Charging System

In-motion wireless power-transfer concept using resonant inductive coils.

Explored coil geometry and behavior under misalignment; architecture secured a copyright.
Focus: resonant power transfer, coil design, system architecture.
🔗 Docs: dynamic-wireless-ev-charging (add link)
🏷️ power-electronics wireless-power resonant-coupling EV
💼 Experience

Hardware Intern, Bit Mapper Integration (Aug 2026 – Jan 2027)

Supporting integration and debugging of HDMI, LVDS, DDR and PCIe interfaces, including PAL/NTSC analog-video paths and FPGA-facing signals.
Researching space-grade and high-reliability components from datasheets, package/footprint data and electrical specifications to support design decisions.
Contributing to electronics hardware design: circuit-level investigation, component selection, interface engineering.
Running high-precision characterization and endurance tests; preparing component comparisons, test records and technical reports for design reviews.

Robotics Intern, Workshop Team, RoboHawk (3 months)

Developed and tested line-following and pick-and-place robots: schematic design, electronics integration, firmware and functional verification.
Delivered hands-on workshops on embedded systems and robotics for students.
🎓 Education & certifications
B.E. Electronics & Telecommunication, PCCOER, Ravet, Pune | Expected 2027 | CGPA 9.0/10
Altium Education: PCB Design
MathWorks: MATLAB Onramp
IIT Bombay (Spoken Tutorial): eSIM Training
🧭 How I approach hardware
Read the datasheet first: operating limits, derating and package details before a part goes in the BOM.
Protect inputs, decouple supplies: power integrity and protection are designed in, not patched on.
Review before layout: schematic design reviews catch pin conflicts and missing parts early.
Test it properly: bring-up plans, bench measurements, endurance runs and written reports.
Document everything: every repo has a schematic PDF, BOM, build notes and known issues.
🎯 What I'm looking for

Hardware design roles in PCB design, high-reliability / space-grade electronics, video & FPGA interfaces, and robotics hardware. Open to internships and full-time positions.

📫 Reach me: atharvakalage@gmail.com · LinkedIn

<p align="center"><i>Building electronics that are meant to last.</i></p>
