<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a1a,40:1a0830,100:3d0000&height=200&section=header&text=GrimDocDimes&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=ECE%20Engineer%20%7C%20FPGA%20%7C%20RTL%20Design%20%7C%20SoC%20%7C%20VLSI&descAlignY=60&descSize=17&animation=fadeIn" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=21&pause=1200&color=E8002D&center=true&vCenter=true&width=750&lines=Electronics+%26+Communication+Engineer;FPGA+%7C+RTL+Design+%7C+SoC+Architecture+%7C+VLSI;From+Verilog+to+GDSII+%E2%80%94+Gate+by+Gate;Hardware+that+doesn't+just+simulate+%E2%80%94+it+ships" alt="Typing SVG" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=GrimDocDimes&color=e8002d&style=for-the-badge&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/GrimDocDimes?label=Followers&style=for-the-badge&color=e8002d&labelColor=0a0a1a)](https://github.com/GrimDocDimes?tab=followers)

</div>

---

---

<div align="center">

## 🔬 Tech Stack

**Hardware Design & Verification**

![Verilog](https://img.shields.io/badge/Verilog-E8002D?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-c0001f?style=for-the-badge)
![VHDL](https://img.shields.io/badge/VHDL-3d0000?style=for-the-badge)
![RTL Design](https://img.shields.io/badge/RTL%20Design-1E1B4B?style=for-the-badge)

**EDA Tools & FPGA Platforms**

![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-E8002D?style=for-the-badge&logo=xilinx&logoColor=white)
![PYNQ-Z2](https://img.shields.io/badge/PYNQ--Z2-1E1B4B?style=for-the-badge)
![Nexys4DDR](https://img.shields.io/badge/Nexys%204%20DDR-1a0830?style=for-the-badge)
![OpenROAD](https://img.shields.io/badge/OpenROAD%20VLSI-3d0000?style=for-the-badge)
![KiCad](https://img.shields.io/badge/KiCad-0a0a1a?style=for-the-badge&logo=kicad&logoColor=white)

**Protocols & Interfaces**

![AXI4](https://img.shields.io/badge/AXI4%20%2F%20AXI--Lite-E8002D?style=for-the-badge)
![JTAG](https://img.shields.io/badge/JTAG-1E1B4B?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-1a0830?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-3d0000?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-0a0a1a?style=for-the-badge)

**Software & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![TCL](https://img.shields.io/badge/TCL%20Scripting-E8002D?style=for-the-badge)
![Bash](https://img.shields.io/badge/Bash-1a0830?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [zynq-cnn-fpga](https://github.com/GrimDocDimes/zynq-cnn-fpga)
**Real-Time CNN Inference on Zynq FPGA**

Hardware-accelerated **MobileNetV1** object detection on PYNQ-Z2. Offloads the full inference pipeline from the ARM PS core to custom Verilog IP in the FPGA fabric.

`C++` `Verilog` `HLS` `PYNQ-Z2` `MobileNetV1`

⭐ **4**

</td>
<td width="50%" valign="top">

### ⚙️ [riscv-gpu-soc](https://github.com/GrimDocDimes/riscv-gpu-soc)
**RISC-V + Custom GPU System-on-Chip**

Complete SoC on PYNQ-Z2: **PicoRV32** RISC-V soft-core coupled via AXI4 to a custom hardware 2D GPU accelerator. Full RTL SoC integration — processor to peripheral.

`Verilog` `RISC-V` `PicoRV32` `AXI4` `PYNQ-Z2`

⭐ **1**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [2d-gpu-pynq](https://github.com/GrimDocDimes/2d-gpu-pynq)
**Custom Hardware 2D GPU on PYNQ-Z2**

Pipelined **Bresenham line engine** in Verilog with AXI4 burst DMA writer and Python API. Renders directly to display — zero software rendering overhead.

`Verilog` `Python` `AXI4 Burst DMA` `PYNQ-Z2`

</td>
<td width="50%" valign="top">

### 🔐 [FPGA-AES](https://github.com/GrimDocDimes/FPGA-AES)
**AES-128 Hardware Cryptographic Accelerator**

Fully pipelined AES-128 engine in Verilog on Nexys 4 DDR, deployed via **JTAG-to-AXI**. Tcl-driven test harness auto-verifies all FIPS-197 test vectors.

`Verilog` `AES-128` `JTAG` `FIPS-197` `Nexys 4 DDR`

⭐ **1** · 🍴 **1**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [AES-128](https://github.com/GrimDocDimes/AES-128)
**AES-128 RTL → GDSII Physical Design Flow**

Full **VLSI physical design** using OpenROAD: synthesis, floorplanning, placement, CTS, routing, and GDSII export of the AES-128 core.

`Verilog` `OpenROAD` `VLSI` `Synthesis` `GDSII`

</td>
<td width="50%" valign="top">

### 📡 [Sobel-Operator-FPGA](https://github.com/GrimDocDimes/Sobel-Operator-FPGA)
**Real-Time Pipelined Sobel Edge Detector**

Fully pipelined Sobel edge-detection accelerator on Nexys 4 DDR. Full wire-speed video processing — no buffering, pure RTL throughput.

`Verilog` `Nexys 4 DDR` `Image Processing`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ [Tamper-Detection](https://github.com/GrimDocDimes/Tamper-Detection)
**ESP32 Anti-Tamper Weighing System**

IoT security system on **ESP32** detecting physical tampering or weight manipulation in real-time. Ensures measurement integrity at the firmware level.

`JavaScript` `ESP32` `IoT` `Embedded`

🍴 **1**

</td>
<td width="50%" valign="top">

### 📶 [Signal-Modulation-App](https://github.com/GrimDocDimes/Signal-Modulation-App)
**Signal Modulation Visualizer**

Python app for interactive visualization of AM, FM, and PM modulation techniques. Built as a hands-on companion to communications theory.

`Python` `Signal Processing` `Comms` `Modulation`

</td>
</tr>
</table>

---

<div align="center">

## 📊 Stats

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=GrimDocDimes&theme=onestar&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=GrimDocDimes&hide_border=true&background=0a0a1a&ring=E8002D&fire=E8002D&currStreakLabel=E8002D&sideLabels=c9d1d9&sideNums=ffffff&dates=888888&currStreakNum=ffffff)](https://git.io/streak-stats)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=GrimDocDimes&bg_color=0a0a1a&color=E8002D&line=E8002D&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

![F1](https://img.shields.io/badge/Formula%201-E8002D?style=for-the-badge&logo=f1&logoColor=white)
![Red Bull Racing](https://img.shields.io/badge/Red%20Bull%20Racing-1E1B4B?style=for-the-badge&logo=redbull&logoColor=e8002d)
![Max Verstappen](https://img.shields.io/badge/%231%20Max%20Verstappen-3d0000?style=for-the-badge)
![Football](https://img.shields.io/badge/Football-0a0a1a?style=for-the-badge)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d0000,50:1a0830,100:0a0a1a&height=120&section=footer" />

</div>
