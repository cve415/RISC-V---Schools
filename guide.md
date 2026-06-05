# University Program Framework


This program provides an open, accessible, and progressive blueprint for universities to transition or expand their Computer Science (CS) and Computer Engineering (CE) curricula into the RISC-V ecosystem.

---

# 🏛️ Program Structure: The Three Tiers

To accommodate varying university budgets, student levels, and course requirements, this framework organizes RISC-V education into three progressive tiers.

| Tier 1: Foundations             | Tier 2: Embedded Systems      | Tier 3: Advanced Architecture      |
| ------------------------------- | ----------------------------- | ---------------------------------- |
| Software Emulation & Simulation | Bare-Metal & RTOS Programming | Custom RTL Design & SoCs           |
| Intro to Systems & Assembly     | Microcontrollers & IoT        | Advanced Microarchitecture & Linux |
| Cost: $0 (Uses Existing PCs)    | Cost: $5–$15 per Student      | Cost: $70–$350 per Workstation     |

---

# 🔹 Tier 1: Software & Simulation Foundations

**Target Level:** Freshmen / Sophomores

**Typical Courses:**

* Introduction to Computer Systems
* Computer Organization
* Basic Assembly Programming

**Focus Areas:**

* Writing assembly code
* Understanding RISC-V registers
* Instruction Set Architecture (ISA)
* Calling conventions
* Software execution without hardware dependencies

**Environment:**

* Web-based simulators
* Lightweight desktop tools
* Existing university computer labs
* Student laptops

---

# 🔹 Tier 2: Microcontrollers & Embedded Systems

**Target Level:** Sophomores / Juniors

**Typical Courses:**

* Embedded Systems
* Internet of Things (IoT)
* Hardware Interfacing

**Focus Areas:**

* Bare-metal programming
* GPIO control
* I²C communication
* SPI communication
* UART communication
* Real-Time Operating Systems (RTOS)
* Sensor integration and peripheral control

---

# 🔹 Tier 3: Advanced Computer Architecture & RTL Design

**Target Level:** Seniors / Graduate Students

**Typical Courses:**

* Digital Logic Design
* Computer Architecture
* VLSI Design
* SoC Design

**Focus Areas:**

* Designing and modifying hardware
* Implementing open-source RISC-V cores
* RTL development using:

  * Verilog
  * SystemVerilog
  * Chisel
* FPGA synthesis and verification
* Multi-core operating system deployment

**Example Open RISC-V Cores:**

* SweRV EH1
* Rocket Core
* Ibex

**Advanced Topics:**

* Linux on RISC-V
* FreeBSD on RISC-V
* Custom processor extensions
* SoC integration
* Tape-out preparation workflows

---

# 🛠️ Hardware Requirements & Cost Estimates

Building a world-class semiconductor education lab with RISC-V is uniquely affordable. Universities can leverage existing infrastructure via emulation or deploy low-cost native RISC-V hardware.

## 📊 Cost Breakdown and Hardware Options

Educational Tier,Infrastructure Model,Hardware Requirements & Recommendations,Estimated Cost (Per Student / Workstation)
Tier 1: Foundations,Non-RISC-V (Software Emulation),"Existing x86/ARM desktop lab PCs or student laptops running open-source instruction-set simulators (Jupiter, Venus, QEMU).",$0(No new hardware needed)

Tier 2: Embedded Systems,Native RISC-V (Silicon MCU Boards),Microcontroller evaluation boards:• Espressif ESP32-H2 / ESP32-C3 / ESP32-C6 (Excellent Wi-Fi/BLE options)• Milk-V Duo (Dual-core CV1800B chip)• SparkFun RED-V RedBoard (Featuring SiFive FE310 or CH32V chips),$5 – $15(Highly scalable for large classrooms)

Tier 3: Advanced Architecture,Native RISC-V (FPGA Workbenches),FPGA Development Kits for synthesis & RTL simulation:• Digilent Basys 3 (Xilinx Artix-7 35T)• Digilent Nexys A7 (Xilinx Artix-7 50T or 100T),$150 – $350(Shared workstations across lab cycles)

Tier 3: System / Linux Deployment,Native RISC-V (Linux SBCs),"Single-Board Computers for operating system, compiler, and toolchain development:• StarFive VisionFive 2 (High-performance quad-core 64-bit)• Lichee Pi 4A (Altheat TH1520 platform)",$70 – $120(Ideal for operating systems courses)

Tier 3: Next-Gen Dev Workstations,Native RISC-V (Modular Laptop / Hardware Integration),"Premium Developer Hardware:• DeepComputing DC-ROMA RISC-V Mainboard III (SpacemiT K3, first laptop mainboard to support the RVA23 profile, up to 60 TOPS general-purpose AI computing, fully compatible with the Framework Laptop 13 architecture)","$699.00(Designed for advanced capstones, AI workloads, and graduate researchers)"
---

# 💡 Cost-Saving Strategy

A university can run an entire introductory Computer Organization course using only Tier 1 resources and free simulators.

This means:

* No new hardware purchases
* Immediate deployment
* Zero financial barrier to entry
* Budget can be allocated toward upper-level architecture and semiconductor courses

---

# 📚 Key Resources for University Program Leaders

Universities do not need to build curriculum from scratch. Significant open-source educational resources already exist.

---

## 1. Flagship Curriculum Frameworks

### RVfpga (RISC-V Academic Program)

Developed through collaboration among:

* RISC-V International
* Imagination Technologies
* Digi-Key

Provides:

* Lecture slides
* Student laboratory manuals
* Instructor materials
* FPGA integration guides
* Commercial-grade SweRV EH1 curriculum

Available free to verified academic instructors.

---

### UC Berkeley EECS Courseware

As the birthplace of RISC-V, UC Berkeley provides public access to substantial educational resources.

Includes:

* CS61C course materials
* Public lecture recordings
* Laboratory assignments
* Pipeline design projects
* Open-source toolchains

Provides a proven blueprint for undergraduate computer architecture education.

---

## 2. Standard Industry Textbooks

### Computer Organization and Design: RISC-V Edition

**Authors:**

* David A. Patterson
* John L. Hennessy

Often considered the gold-standard introduction to computer architecture using RISC-V.

---

### Digital Design and Computer Architecture: RISC-V Edition

**Authors:**

* Sarah L. Harris
* David Harris

Excellent for:

* Digital logic design
* FPGA coursework
* RTL development
* Advanced architecture laboratories

---

## 3. Open-Source Toolchains & Simulators

### Assembly-Level Simulation

#### RARS

Features:

* Visual execution environment
* Register tracing
* Step-by-step debugging
* Classroom-friendly interface

#### Venus

Features:

* Browser-based
* No installation required
* Ideal for introductory coursework

---

### Full-System Emulation

#### QEMU

Provides:

* Full-system emulation
* Linux execution
* Multi-core simulation
* Software stack validation

#### Spike

Provides:

* Official RISC-V ISA simulation
* Architectural compliance testing
* Extension validation

---

### HDL Simulation

#### Verilator

Features:

* Open source
* High-performance Verilog simulation
* C++-based execution model
* Industry adoption

#### EDA Playground

Features:

* Browser-based HDL development
* Waveform visualization
* No local installation
* Useful for introductory RTL labs

---

# 🌐 Community & Student Engagement

Successful programs extend beyond the classroom.

---

## Establish a RISC-V Student Advocate Chapter

RISC-V International sponsors a global Student Advocates program.

Benefits include:

* Student leadership development
* Peer-led workshops
* Hackathons
* Technical presentations
* Community building
* Industry networking

---

## Contribute Upstream

Encourage students to contribute directly to open-source projects through:

* Senior capstone projects
* Undergraduate research
* Graduate research
* Independent study projects

Potential organizations include:

* OpenHW Group
* CHIPS Alliance
* lowRISC

Examples:

* Peripheral development
* Documentation improvements
* Core optimizations
* Verification infrastructure
* Software tooling

---

# 💻 Website Integration Recommendations

This framework can be adapted into a university website, departmental portal, or student resource center.

Recommended navigation structure:

## Tab 1: Curriculum Pathways

* Tier 1 Foundations
* Tier 2 Embedded Systems
* Tier 3 Advanced Architecture

## Tab 2: Lab Infrastructure

* Emulation Options
* Hardware Requirements
* Budget Planning
* Cost Comparisons

## Tab 3: Student Hub

* Simulator Links
* Learning Resources
* Student Advocate Programs
* Open-Source Contribution Opportunities

---

# Conclusion

This University Program Framework provides a scalable path from introductory computer systems education to advanced semiconductor and system-on-chip design. Through free software tools, low-cost embedded hardware, and open-source curriculum resources, universities can establish modern computer engineering programs with minimal barriers to entry while preparing students for careers in semiconductors, embedded systems, computer architecture, and open hardware development.
