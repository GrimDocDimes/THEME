<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a1a,50:1a0a2e,100:3d0000&height=200&section=header&text=GrimDocDimes&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Electronics%20%26%20Communication%20Engineer%20%7C%20FPGA%20%7C%20RTL%20%7C%20SoC%20Design&descAlignY=60&descSize=17&animation=fadeIn" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=E8002D&center=true&vCenter=true&width=750&lines=Electronics+%26+Communication+Engineer;FPGA+%7C+RTL+Design+%7C+SoC+Architecture+%7C+VLSI;From+Verilog+to+GDSII+%E2%80%94+Gate+by+Gate;Hardware+that+doesn't+just+simulate+%E2%80%94+it+ships" alt="Typing SVG" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=GrimDocDimes&color=e8002d&style=for-the-badge&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/GrimDocDimes?label=Followers&style=for-the-badge&color=e8002d&labelColor=0a0a1a)](https://github.com/GrimDocDimes?tab=followers)

</div>

---

## `$ cat whoami.v`

```verilog
module GrimDocDimes #(
  parameter DEGREE = "B.E. Electronics & Communication Engineering"
) (
  input  wire  curiosity,
  input  wire  coffee,
  output reg   silicon_dreams
);

  // ─── Core Strengths ────────────────────────────────
  localparam FPGA_DESIGN   = 1;
  localparam SOC_ARCH      = 1;
  localparam RTL_CODING    = 1;
  localparam HW_CRYPTO     = 1;
  localparam ML_INFERENCE  = 1;   // on silicon, not in Python

  always @(posedge curiosity or posedge coffee) begin
    silicon_dreams <= FPGA_DESIGN | SOC_ARCH  |
                      RTL_CODING  | HW_CRYPTO |
                      ML_INFERENCE;
  end

  // ─── Off the clock ──────────────────────────────────
  // 🏎️  F1  —  Red Bull Racing  //  #MaxVerstappen
  // ⚽  Football

endmodule
```

---

<div align="center">

## 🔬 Tech Stack

**Hardware Design & Verification**

![Verilog](https://img.shields.io/badge/Verilog-FF6B35?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF4081?style=for-the-badge)
![VHDL](https://img.shields.io/badge/VHDL-7C3AED?style=for-the-badge)
![RTL](https://img.shields.io/badge/RTL%20Design-0F3460?style=for-the-badge)

**EDA Tools & FPGA Platforms**

![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-E01F3D?style=for-the-badge&logo=xilinx&logoColor=white)
![PYNQ-Z2](https://img.shields.io/badge/PYNQ--Z2-FF6900?style=for-the-badge)
![Nexys4DDR](https://img.shields.io/badge/Nexys%204%20DDR-0047AB?style=for-the-badge)
![OpenROAD](https://img.shields.io/badge/OpenROAD%20VLSI-6D28D9?style=for-the-badge)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)

**Protocols & Interfaces**

![AXI4](https://img.shields.io/badge/AXI4%20%2F%20AXI--Lite-FF2D55?style=for-the-badge)
![JTAG](https://img.shields.io/badge/JTAG-2C2C2C?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-00B4D8?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-0077B6?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-023E8A?style=for-the-badge)

**Software & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![TCL](https://img.shields.io/badge/TCL%20Scripting-EF7B00?style=for-the-badge)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

---

## 🚀 Projects

> *Hardware that doesn't just simulate — it ships.*

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [zynq-cnn-fpga](https://github.com/GrimDocDimes/zynq-cnn-fpga)
**Real-Time CNN Inference on Zynq FPGA**

Hardware-accelerated **MobileNetV1** object detection on the PYNQ-Z2 Zynq SoC. Offloads the inference pipeline from the ARM PS core to custom Verilog IP in the FPGA fabric — achieving real-time throughput with minimal latency.

`C++` `Verilog` `HLS` `PYNQ-Z2` `MobileNetV1`

⭐ **4 Stars** — Most starred project

---

</td>
<td width="50%" valign="top">

### ⚙️ [riscv-gpu-soc](https://github.com/GrimDocDimes/riscv-gpu-soc)
**RISC-V + Custom GPU System-on-Chip**

A complete SoC on PYNQ-Z2: **PicoRV32** RISC-V soft-core tightly coupled via AXI4 to a custom hardware GPU accelerator for 2D graphics rendering. Demonstrates full RTL SoC integration from processor to peripheral.

`Verilog` `RISC-V` `PicoRV32` `AXI4` `PYNQ-Z2`

⭐ **1 Star**

---

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [2d-gpu-pynq](https://github.com/GrimDocDimes/2d-gpu-pynq)
**Custom Hardware 2D GPU on PYNQ-Z2**

A hardware 2D graphics accelerator built from scratch in Verilog — pipelined **Bresenham line engine**, AXI4 burst DMA writer, and a clean Python API. Renders directly to display with zero software rendering overhead.

`Verilog` `Python` `AXI4 Burst DMA` `PYNQ-Z2` `Bresenham`

---

</td>
<td width="50%" valign="top">

### 🔐 [FPGA-AES](https://github.com/GrimDocDimes/FPGA-AES)
**AES-128 Hardware Cryptographic Accelerator**

Fully pipelined AES-128 encryption engine in Verilog, deployed on Nexys 4 DDR via **JTAG-to-AXI**. Automated test harness verifies all FIPS-197 standard test vectors using a Tcl script — hardware crypto, done right.

`Verilog` `AES-128` `JTAG` `FIPS-197` `Nexys 4 DDR`

⭐ **1 Star** · 🍴 **1 Fork**

---

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [AES-128](https://github.com/GrimDocDimes/AES-128)
**AES-128 RTL → GDSII Physical Design Flow**

Takes the AES-128 core through a complete **VLSI physical design flow** using OpenROAD — synthesis, floorplanning, placement, routing, and GDSII export. Bridging the gap between RTL and real silicon.

`Verilog` `OpenROAD` `VLSI` `Synthesis` `GDSII`

---

</td>
<td width="50%" valign="top">

### 📡 [Sobel-Operator-FPGA](https://github.com/GrimDocDimes/Sobel-Operator-FPGA)
**Real-Time Pipelined Sobel Edge Detector**

A fully pipelined Sobel edge-detection accelerator on the Nexys 4 DDR. Processes live video at full wire-speed — no buffering, no software bottlenecks, pure RTL throughput from pixel to edge.

`Verilog` `Nexys 4 DDR` `Image Processing` `Pipeline RTL`

---

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ [Tamper-Detection](https://github.com/GrimDocDimes/Tamper-Detection)
**ESP32 Anti-Tamper Weighing System**

An IoT security system using **ESP32** that detects physical tampering or weight manipulation in real-time. Ensures transparency and accuracy in trade measurements — firmware meets real-world integrity.

`JavaScript` `ESP32` `IoT` `Embedded Systems`

🍴 **1 Fork**

---

</td>
<td width="50%" valign="top">

### 📶 [Signal-Modulation-App](https://github.com/GrimDocDimes/Signal-Modulation-App)
**Signal Modulation Visualizer**

A Python application for visualizing and exploring signal modulation techniques — AM, FM, PM and more. Built as an educational tool bridging theory and interactive simulation for comm-systems fundamentals.

`Python` `Signal Processing` `Communications` `Modulation`

---

</td>
</tr>
</table>

---

<div align="center">

## 📊 GitHub Stats

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=GrimDocDimes&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=ff6b35&text_color=c9d1d9&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GrimDocDimes&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=6"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=GrimDocDimes&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=ff6b35&currStreakLabel=a78bfa)](https://git.io/streak-stats)

</div>

---

## 🔭 What I'm Exploring

```
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│  🏗️  VLSI Physical Design   →  RTL-to-GDSII with OpenROAD           │
│  🧮  Hardware ML Inference  →  CNN / Transformer acceleration        │
│  🔐  Cryptographic Hardware →  AES, future post-quantum RTL          │
│  📡  RF & Antenna Design    →  Patch antennas, Butler Matrix BFN     │
│  🖥️  Custom SoC Arch        →  RISC-V cores + custom AXI4 IPs        │
│  📈  DSP on FPGA            →  FFT engines, FIR/IIR pipelines        │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

---

![F1](https://img.shields.io/badge/Formula%201-E8002D?style=for-the-badge&logo=f1&logoColor=white)
![Red Bull Racing](https://img.shields.io/badge/Red%20Bull%20Racing-1E1B4B?style=for-the-badge&logo=redbull&logoColor=white)
![Max Verstappen](https://img.shields.io/badge/%231%20Max%20Verstappen-3d0000?style=for-the-badge)
![Football](https://img.shields.io/badge/Football-1a1a2e?style=for-the-badge&logo=transfermarkt&logoColor=white)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d0000,50:1a0a2e,100:0a0a1a&height=120&section=footer" />

</div>
