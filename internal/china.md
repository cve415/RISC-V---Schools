**Compiled By:** Christopher Velasco, RISC-V International Academia & Training SIG member

---

## Overview

China is the most consequential RISC-V ecosystem outside the United States — driven by US export controls on advanced semiconductors accelerating domestic open-ISA adoption, major government investment through the "Made in China 2025" and national chip programs, and a dense cluster of world-class research universities producing RISC-V silicon and toolchain contributions. The XiangShan processor (ICT/CAS), Alibaba's XuanTie T-Head cores, and a growing domestic RISC-V industry have created strong pull from academia to industry and back.

The recent **Uncore PMU proposal** to the RISC-V ISA specification — originating from the T-Head team at Alibaba in Hangzhou — illustrates how Chinese industry and academia are actively shaping the RISC-V standard itself, not just consuming it.

This document tracks the **top 20 Chinese universities and research institutions** most important to RISC-V, following the same Tier 1 / Tier 2 framework. Note: ICT/CAS is a Chinese Academy of Sciences research institute rather than a traditional university, but its impact on RISC-V globally warrants its inclusion as the anchor entry.

---

# China RISC-V University Tracking

---

## Tier 1: Confirmed Coursework, Lab Use, or Named RISC-V Program

*Direct evidence of RISC-V in coursework, syllabi, named research programs, or production silicon tapeouts originating from a student/faculty team.*

---

### Institute of Computing Technology, Chinese Academy of Sciences (ICT/CAS) — Beijing

The most impactful RISC-V research institution in China and one of the most significant globally. The **XiangShan (香山)** project — an open-source, high-performance out-of-order RISC-V processor — originated here under faculty and student leadership.

- XiangShan has completed two major tapeouts: **Yanqihu** (28nm) and **Nanhu** (14nm), achieving performance comparable to ARM Cortex-A75/A76
- The project is fully open-source on GitHub (OpenXiangShan), with active student contributions from top Chinese universities
- Graduate architecture courses at ICT/CAS use RISC-V as the primary design target
- XiangShan is now a reference design studied and built upon by universities across China

---

### Zhejiang University (ZJU, 浙江大学) — Hangzhou, Zhejiang

The geographic anchor of China's RISC-V industry cluster. ZJU sits at the center of Hangzhou's tech ecosystem — home to Alibaba's DAMO Academy and T-Head Semiconductor, which developed the open-source XuanTie RISC-V cores (C906, C910) and authored the Uncore PMU specification proposal.

- Computer Architecture courses use RISC-V as the primary ISA reference
- Faculty and student research groups have published extensively on RISC-V microarchitecture, memory systems, and SoC design
- ZJU–Alibaba joint research programs create a direct pipeline between student RISC-V work and production chip deployment
- ZJU's College of Computer Science and Technology has hosted RISC-V-themed courses and workshops

---

### Tsinghua University (清华大学) — Beijing

China's top-ranked university overall and a pillar of Chinese computer architecture research. The **Department of Computer Science and Technology** and **Institute of Microelectronics** both produce RISC-V aligned research and coursework.

- Computer Organization and Architecture courses use *Patterson & Hennessy RISC-V Edition* as the primary textbook
- Faculty publications include RISC-V processor microarchitecture, hardware security, and compiler backend research
- Student teams participate in national RISC-V design competitions and have contributed to open-source RISC-V toolchains
- Strong collaboration with domestic RISC-V companies (Nuclei System Technology, PerfXLab) for student internships and joint research

---

### Shanghai Jiao Tong University (SJTU, 上海交通大学) — Shanghai

One of China's most research-productive engineering universities. The **School of Electronic Information and Electrical Engineering (SEIEE)** has active RISC-V research groups.

- CS359 (Computer Architecture) and graduate architecture courses use RISC-V as the design ISA
- Published research includes RISC-V based accelerators, vector extensions, and FPGA prototyping
- SJTU participates in the national RISC-V design ecosystem and has student teams in RISC-V processor competitions
- Located in Shanghai's semiconductor design hub, reinforcing industry-aligned RISC-V coursework

---

### Peking University (PKU, 北京大学) — Beijing

Strong CS and microelectronics programs with documented RISC-V coursework and research output.

- Introduction to Computer Systems and Computer Architecture courses have adopted RISC-V as the instructional ISA
- School of Electronics Engineering and Computer Science faculty have published RISC-V microarchitecture and hardware security research
- PKU's **Institute of Software** contributes to open-source RISC-V toolchain development
- Students participate in national RISC-V CPU design contests (held annually in China)

---

### University of Science and Technology of China (USTC, 中国科学技术大学) — Hefei, Anhui

USTC's **School of Computer Science and Technology** has integrated RISC-V into its computer architecture curriculum and research programs.

- Computer Organization courses use RISC-V; lab assignments include pipeline implementation exercises targeting RISC-V
- USTC students have participated in and won national RISC-V processor design competitions
- Research output includes RISC-V based reconfigurable computing and domain-specific accelerator work
- Strong connection to the CAS ecosystem given USTC's founding by the Chinese Academy of Sciences

---

### Huazhong University of Science and Technology (HUST, 华中科技大学) — Wuhan, Hubei

One of China's most engineering-intensive universities with a particularly strong processor design culture.

- Computer Architecture courses are among the most structured in China for RISC-V adoption, with public lab materials including RISC-V pipeline design exercises
- HUST's **School of Computer Science and Technology** has produced student RISC-V CPU implementations documented publicly
- Faculty research covers RISC-V based IoT processors, security extensions, and formal verification
- HUST participates in the national "One Life One Chip" (一生一芯) project — a national initiative where students design and tape out a RISC-V processor as part of their education

---

### "One Life One Chip" (一生一芯) Program — Coordinated Nationally, led by ICT/CAS and partner universities

A dedicated callout for this program which spans multiple institutions. Students design, verify, and tape out a complete RISC-V SoC from scratch — one chip per student lifecycle. Universities officially participating include:

- **ICT/CAS** (program originator)
- **Peking University**
- **Zhejiang University**
- **Huazhong University of Science and Technology**
- **Nanjing University**
- **University of Science and Technology of China**

This is China's most direct equivalent to a national RISC-V curriculum mandate. Any school formally enrolled in 一生一芯 is an automatic Tier 1 entry.

---

### Southeast University (SEU, 东南大学) — Nanjing, Jiangsu

SEU's **School of Electronic Science and Engineering** is one of China's strongest microelectronics programs and a key node in the Yangtze River Delta semiconductor corridor.

- RISC-V processor design appears in digital IC design and computer architecture courses
- Faculty research covers RISC-V based SoC design, VLSI implementation, and low-power embedded cores
- SEU's strong industry ties to Nanjing's chip design cluster (NXP China, Huawei Nanjing, local fabless companies) create direct demand for RISC-V trained graduates

---

### National University of Defense Technology (NUDT, 国防科技大学) — Changsha, Hunan

China's premier military-academic institution and developer of the Tianhe supercomputer series. NUDT's **College of Computer** is one of the most advanced processor design programs in China.

- Computer architecture research at NUDT includes RISC-V processor design and custom ISA extension work
- Graduate-level courses use RISC-V as a design target for high-performance and reliable computing research
- NUDT's influence on national computing standards gives its RISC-V research outsized policy relevance

---

## Tier 2: Active Teaching Materials or Project-Based Use

*Strong evidence of RISC-V content through research publications, textbook adoption, national competition participation, or documented student projects — without a fully public standalone course syllabus confirmed. Promote to Tier 1 once specific course materials or a named program is verified.*

---

### Fudan University (复旦大学) — Shanghai

The **School of Microelectronics** at Fudan is one of China's strongest IC design programs. RISC-V appears in graduate chip design coursework and student tapeout projects; proximity to Shanghai's semiconductor design cluster reinforces adoption.

---

### Nanjing University (NJU, 南京大学) — Nanjing, Jiangsu

One of China's top comprehensive universities. The **Department of Computer Science and Technology** has adopted RISC-V in computer organization courses and participates in the 一生一芯 program, which places NJU on the cusp of Tier 1.

---

### University of Electronic Science and Technology of China (UESTC, 电子科技大学) — Chengdu, Sichuan

China's most electronics-specialized university. RISC-V appears in digital systems, computer architecture, and SoC design coursework. UESTC's location in Chengdu — a growing chip design hub — creates strong industry alignment.

---

### Harbin Institute of Technology (HIT, 哈尔滨工业大学) — Harbin, Heilongjiang

Top engineering university in Northeast China. HIT's **School of Computer Science and Technology** has computer architecture research and coursework referencing RISC-V; student teams participate in national processor design competitions.

---

### Beihang University (BUAA, 北京航空航天大学) — Beijing

Aerospace and defense-oriented engineering university. Computer architecture and embedded systems courses reference RISC-V; faculty research in fault-tolerant and real-time systems aligns with RISC-V's open verification properties.

---

### Xi'an Jiaotong University (XJTU, 西安交通大学) — Xi'an, Shaanxi

One of China's original Jiaotong universities with strong ECE programs. Computer architecture coursework has adopted RISC-V edition materials; research in energy-efficient computing references RISC-V implementations.

---

### Sun Yat-sen University (SYSU, 中山大学) — Guangzhou, Guangdong

The flagship university of South China. CS and ECE programs include computer architecture content with RISC-V; SYSU's location in the Pearl River Delta semiconductor region (Huawei HQ in Shenzhen nearby) creates strong industry pull.

---

### South China University of Technology (SCUT, 华南理工大学) — Guangzhou, Guangdong

Strong engineering programs in South China. ECE and CS architecture courses are tracking the RISC-V textbook transition; faculty research in embedded IoT and SoC design references RISC-V.

---

### Wuhan University (武汉大学) — Wuhan, Hubei

CS and ECE programs with computer architecture coursework. Located in Wuhan alongside HUST, which has the strongest RISC-V program in the region — cross-institutional influence makes Wuhan University a natural Tier 2 entry.

---

### Beijing Institute of Technology (BIT, 北京理工大学) — Beijing

Defense-adjacent engineering university with strong ECE programs. Computer architecture and embedded systems courses reference RISC-V; BIT's focus on safety-critical systems aligns with RISC-V's verifiable open ISA properties.

---

### Institute of Software, Chinese Academy of Sciences (ISCAS) / PLCT Lab — Beijing

The **Programming Language and Compiler Technology (PLCT) Lab** at ISCAS is China's most important RISC-V toolchain contributor — maintaining and extending GCC, LLVM, QEMU, and other open-source tools for RISC-V. While not a degree-granting university, PLCT's graduate students and fellows come from top Chinese universities and its output underpins RISC-V education nationally.

---

## National Context

- **Export control accelerant:** US restrictions on advanced chip technology (EDA tools, advanced nodes) have made open-ISA RISC-V a national strategic priority. University RISC-V adoption is partially policy-driven, not just academic.
- **National CPU design competitions:** China holds annual national RISC-V processor design competitions for university students — schools with competition participants are reliable Tier 1 or Tier 2 indicators.
- **一生一芯 (One Life One Chip):** This national program — where students tape out a real RISC-V chip as part of their degree — is the most direct academic RISC-V integration anywhere in the world. Participation is the clearest Tier 1 signal.
- **T-Head / Alibaba XuanTie:** Alibaba's open-source RISC-V cores (C906, C910, C920) are widely used in Chinese university labs as reference implementations, particularly at ZJU and partner institutions in the Hangzhou–Shanghai corridor.
- **PLCT Lab multiplier:** Like India's NPTEL, PLCT Lab's toolchain work propagates RISC-V capability to universities that might not otherwise have the infrastructure to run RISC-V courses.

---

*Maintenance tip:* The fastest verification path for Chinese institutions is cross-referencing CNKI (China National Knowledge Infrastructure) and GitHub for RISC-V publications and student repositories. National CPU design competition leaderboards (published annually) are also a direct signal of institutional engagement.
