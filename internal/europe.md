**Compiled By:** Christopher Velasco, RISC-V International Academia & Training SIG member

---

## Overview

Europe is one of the three global centers of RISC-V academic gravity alongside the United States and China. European RISC-V academia is distinguished by three structural advantages: the **PULP Platform** (ETH Zurich / University of Bologna), which has produced the most widely adopted open-source RISC-V cores globally (CVA6, Ibex, Snitch); the **European Processor Initiative (EPI)** and a dense network of Horizon Europe research projects that institutionalize RISC-V across national boundaries; and the **Barcelona Supercomputing Center**, which anchors Spain's and Europe's safety-critical RISC-V research.

Primary sources: RISC-V Europe Summit 2023 poster session proceedings, RISC-V Europe Summit 2025 keynote/talk content, and RISC-V Europe Summit 2026 poster session — institutions whose researchers presented documented RISC-V work are treated as confirmed. Additional entries draw on known research program records.

This document covers **Tier 1 and Tier 2** only. No speculative entries.

---

# Europe RISC-V University & Research Institution Tracking

---

## Tier 1: Confirmed Coursework, Lab Use, or Named RISC-V Program

*Direct evidence of RISC-V in coursework, named research programs, or production silicon originating from a student/faculty team. RISC-V Europe Summit 2023 poster presenters are confirmed Tier 1.*

---

### ETH Zurich — Zurich, Switzerland

The European anchor of RISC-V academia and one of the most important RISC-V institutions globally. ETH Zurich's **Integrated Systems Laboratory (IIS)**, led by Prof. Luca Benini, is home to the **PULP Platform** — the origin of CVA6/Ariane, Ibex (zero-riscy), Snitch, and the wider PULP cluster ecosystem.

- CVA6 (formerly Ariane): 64-bit, Linux-capable, out-of-order RISC-V core — now an OpenHW Group project
- Ibex: 32-bit RV32IMC microcontroller core contributed to lowRISC, foundational to OpenTitan
- Snitch: ultra-compact RISC-V core for high-efficiency compute clusters
- Computer Architecture courses at ETH Zurich use RISC-V as the primary ISA
- Multiple RISC-V Europe 2023 poster presenters affiliated: **Thomas Benz, Paul Scheffler, Marco Bertuletti** (all ETH Zurich / Luca Benini group)
- **RISC-V Europe 2025 keynote:** Luca Benini delivered "RISC-V: Enabling Open Physical AI" — focusing on deep domain specialization for efficient, safe, and reliable Physical AI chips on RISC-V. Confirms ETH's continued leadership at the frontier of RISC-V research directions.
- **RISC-V Europe 2026 tapeout milestone:** Philippe Sauter (ETH IIS) presented MLEM, the first Croc SoC tapeout, confirmed functional at 72 MHz @ 1.2V in IHP 130nm open PDK — and HyperCroc, extending Croc with HyperBus DRAM and DMA for accelerator workloads. Implementable in under one hour on a consumer workstation.
- **2026 — Loom (Florian Zaruba, ETH):** Open-source toolchain that automatically transforms simulation-grade SystemVerilog into FPGA-synthesizable RTL, validated end-to-end on a Snitch RISC-V core on Xilinx Alveo U250. Closes the gap between simulation and FPGA emulation without proprietary tools.
- **2026 — CAGE-V (Moritz Waser, ETH):** Novel confidential computing architecture supporting guest enclaves inside confidential VMs, with hardware extension to CVA6 and a security monitor, demonstrating minor performance impact.
- **2026 — MAGIA-V (ETH / Bologna joint):** Open mesh-of-tiles accelerator template integrating Spatz RVV vector processor with RedMulE tensor engine — enabling concurrent vector + matrix operations.
- **2026 — "RISC-V Silicon at Scale" (Yichao Zhang, ETH/Bologna):** PULP Platform has delivered multiple chips exceeding one billion transistors — made possible through open-source collaboration and RISC-V's openness.
- Participant in European Processor Initiative (EPI) vector acceleration work

---

### University of Bologna — Bologna, Italy

Co-originator of the PULP Platform with ETH Zurich. Prof. Luca Benini holds a dual appointment at ETH Zurich and Bologna; the PULP research group has roots at Bologna's **Department of Electrical, Electronic and Information Engineering (DEI)**.

- PULP cluster architecture and energy-efficient RISC-V multi-core research
- Graduate computer architecture courses use RISC-V; student teams contribute to open-source PULP cores
- RISC-V silicon tapeouts including GAP8 (GreenWaves Technologies, spun out of Bologna/EPFL research)
- **Marco Fariselli** (MSc Bologna 2019 → GreenWaves Technologies → Luxottica embedded AI): his 2025 summit talk on RISC-V for smart glasses traces a direct career arc from Bologna's academic RISC-V program to production edge AI silicon — one of the clearest examples of Bologna's graduate-to-industry RISC-V pipeline
- **2026 — Astral (Yvan Tortorella, Bologna):** Fully open-source, highly parametric RISC-V heterogeneous SoC platform targeting reliable onboard AI for space computers — combining RISC-V cores with accelerators for the harsh space environment.
- **2026 — 5G NTN Space (Marco Bertuletti, ETH/Bologna):** Evaluated end-to-end 5G NTN uplink/downlink on a single rv64gc core; identified RISC-V "V" vector extension as the key to bridging the 273x performance gap for real-time space communications — confirming the PULP group's push into space-grade vector SoCs.
- One of Europe's clearest examples of academic RISC-V research becoming commercial silicon; Luca Benini's 2025 keynote and the 2026 papers further confirm Bologna's co-anchoring role

---

### Barcelona Supercomputing Center (BSC) / Universitat Politècnica de Catalunya (UPC) — Barcelona, Spain

Europe's strongest RISC-V safety-critical research program. BSC's **CAOS group** (Computer Architecture / Operating Systems) has produced the NOEL-V processor, led multiple Horizon Europe RISC-V projects, and holds the RISC-V Educator of the Year Award (Dr. Leonidas Kosmidis, 2019).

- **NOEL-V**: BSC's open RISC-V processor (extending Gaisler's design) for safety-critical applications
- Documented RISC-V poster presentations at RISC-V Europe 2023: **Marcel Sarraseca** (SafeLS lockstep NOEL-V), **Francisco Javier Fuentes** (SafeTI traffic injector), **Leonidas Kosmidis** (METASAT multicore RISC-V platform)
- Active on Horizon Europe projects: FRACTAL, NimbleAI, METASAT, AERO
- **2026 — PQC4eMRTD (Leonidas Kosmidis, BSC):** EC-funded CSA project standardizing post-quantum cryptography for European machine-readable travel documents (passports, national IDs) — RISC-V systems are the implementation target. Directly ties BSC's RISC-V security research to EU digital identity infrastructure.
- **2026 — Sargantana HQC (Vito Cucinelli, BSC):** HQC (NIST's new KEM, March 2025) performance profiling on BSC's Sargantana RV64GBV core, using B and V extensions and RAVE profiling tool.
- **2026 — Bicameral+ (Aitor Echevarría, BSC):** Enhanced vector-aware cache design separating vector/scalar partitions — 7x area reduction, 18x energy savings vs prior version, 1.59x average speedup over conventional cache.
- UPC graduate students formally enrolled in RISC-V research tracks; Computer Architecture coursework uses RISC-V

---

### Technical University of Munich (TUM) — Munich, Germany

Active RISC-V research program with documented silicon tapeouts. Prof. Georg Sigl's **Chair of Security in Information Technology** has produced multiple RISC-V ASICs.

- **Jonas Schupp** (TUM PhD student): three RISC-V ASIC tapeouts for post-quantum cryptography — one in UMC 65nm, two in GlobalFoundries 22nm — presented at RISC-V Europe 2023
- **Karsten Emrich** (TUM): flexible RISC-V simulation environment, Scale4Edge project participant
- Computer architecture and embedded systems courses reference RISC-V
- Participant in **Scale4Edge** — German national program for RISC-V edge computing ecosystem

---

### University of Cambridge — Cambridge, United Kingdom

Home to the **CHERI-RISC-V** project — one of the most consequential hardware security efforts built on RISC-V, jointly with lowRISC and SRI International.

- **Franz Fuchs** (Cambridge PhD): CHERI compartments for transient-execution attack mitigation on RISC-V — RISC-V Europe 2023 poster presenter
- **Peter Rugg** and **Alexandre Joannou** (Cambridge): CHERI capability machine presentations at the same summit
- Prof. Simon Moore's group leads the CHERI hardware work; Prof. Robert Watson leads the broader CHERI project
- Computer Architecture courses in the Department of Computer Science and Technology use RISC-V
- lowRISC CIC (affiliated with Cambridge) maintains Ibex and OpenTitan tooling
- **2026 — RVY ratification infrastructure (Alexandre Joannou, Cambridge):** Cambridge has built the comprehensive validation platform for the CHERI RVY extension — formal golden model, directed-random fuzz testing via Sail, FPGA at scale for software development and performance evaluation. This infrastructure directly enabled convergence toward RVY ratification with high confidence.
- **2026 — RV64Y Temporal Safety (Jonathan Woodruff, Cambridge):** Studies informing the temporal safety provisions in the frozen RV64Y spec — optimized CheriBSD revocation to reduce Spec2006 overhead by 12% and explored PTE encoding for generational capability dirty states. Cambridge is authoring the spec, not just implementing it.

---

### Politecnico di Torino — Turin, Italy

Active RISC-V safety research program with documented publications and coursework.

- **Prof. Matteo Sonza Reorda** (Politecnico di Torino): RISC-V Self-Test Libraries (STLs) for safety-critical applications — RISC-V Europe 2023 poster, 400+ publications, IEEE Fellow
- Computer Engineering and Electronics courses use RISC-V
- Participant in European projects targeting RISC-V automotive and space applications
- Strong connections to the PULP ecosystem through Italian research networks
- **2026 — PQC ISA extensions (Valeria Piscopo + Alessandra Dolmeta):** Three papers at RISC-V Europe 2026 — CIRCE (CROSS PQC signature via CV-X-IF, 2x speedup, Zynq FPGA), HORCRUX (modular PQC ISA extension for ML-KEM/ML-DSA/SLH-DSA/HQC, 65nm ASIC ~26.3 kGE, up to 99.5% energy savings), CHIMERA (ASCON AEAD+hash engine, up to 6x speedup). The most concentrated PQC ISA extension work at any European institution.
- **2026 — Side-channel and fault injection (Stefano Di Carlo + Alessandro Savino):** Flush+Reload cache side-channel attack methodology for RISC-V on gem5 (establishing attack feasibility), and InjectV — a gem5-based fault injection framework using trace-guided candidate injection points, requiring 95.8% fewer injections than random exploration.
- **2026 — ML-KEM 22nm ASIC (Stefano Di Matteo + Ivan Sarno):** Quantitative cost-benefit analysis of a dedicated ML-KEM hardware accelerator on CV32E40P — 139x speedup over software, only 6% total SoC area overhead at 22nm. One of the clearest silicon data points for PQC acceleration on RISC-V.

---

### CEA (French Alternative Energies and Atomic Energy Commission) — Grenoble / Saclay, France

France's primary RISC-V research institution, spanning multiple laboratories with documented RISC-V hardware security and SoC work.

- **CEA Leti (Grenoble)**: RISC-V Trace Encoder security work — **Anthony Zgheib** (PhD at Mines Saint-Étienne / CEA Leti) presented at RISC-V Europe 2023; Memory Authenticated Encryption Engine for CVA6 — **Karim Ait Lahssaine** (CEA Grenoble)
- **CEA List (Paris-Saclay / Grenoble)**: 128-bit RISC-V simulation — **Eduardo Tomasi Ribeiro**; VPSim virtual prototyping for RISC-V HPC — **Ayoub Mouhagir**; security platform — **Caaliph Andriamisaina**
- CEA participates in European Processor Initiative (EPI)
- Graduate students from Mines Saint-Étienne, Paris-Saclay, and Grenoble Alpes co-supervised with CEA labs
- **2026 — Flying V (César Fuguet, CEA):** ECC-hardened HPDcache (open-source L1 data cache for CVA6) with SECDED and background scrubber — 2.1% area overhead in 45nm. First step toward a fully open-source RISC-V aerospace processor with safety-grade memory subsystem.
- **2026 — Fault-Tolerant CVA6 (Jérôme Quévremont, CEA):** Radiation-hardened CVA6 with DCLS, SEU detection, L1 cache ECC, Linux+Zephyr tested — being integrated into a new 18nm SoC for AI. CEA is actively moving open RISC-V into production silicon for space, aero, and automotive.
- **2026 — ALPES (Emanuele Valea + Jérémie Pescatore, CEA):** Versatile SoC platform built around OpenHW CVA6 and CV32E40P — a pre-verified foundation for ASIC projects, supporting multiple Horizon Europe RISC-V research programs.
- **2026 — ANSSI IPECC on CVA6:** French national cybersecurity agency ANSSI contributed IPECC, an open-source side-channel-resistant ECC accelerator, integrated into CVA6 SoC on Genesys 2 FPGA. ECDSA P-256 signature latency reduced from 1.13s to 180ms (6.3x); scales to 9.1x for P-521. CEA/ANSSI collaboration producing open security IP for European RISC-V platforms.

---

## Tier 2: Active Teaching Materials or Project-Based Use

*Documented RISC-V research output, conference presentations, or known Horizon Europe project participation. Promote to Tier 1 once a named course syllabus or standalone RISC-V program is confirmed.*

---

### Germany

**RPTU Kaiserslautern-Landau — Kaiserslautern**
Prof. Wolfgang Kunz's **Electronic Design Automation Group** has published on transient-execution side-channel detection and patching in out-of-order RISC-V cores (SonicBOOM). **Tobias Jauch** (RPTU PhD student) presented at RISC-V Europe 2023. Participant in Scale4Edge.

**University of Bremen / DFKI — Bremen**
**Muhammad Hassan** (DFKI GmbH / University of Bremen): formal verification work on RISC-V presented at RISC-V Europe 2023. Prof. Rolf Drechsler's group has published on RISC-V verification. Computer architecture coursework references RISC-V.

**Forschungszentrum Jülich — Jülich (near Aachen)**
HPC research center with RISC-V vector (RVV) work. **Stepan Nassyr** presented automated BLIS kernel generation for RISC-V RVV at RISC-V Europe 2023 as part of the EUPILOT project targeting RISC-V HPC.

**IHP Microelectronics (Leibniz Institute) — Frankfurt (Oder)**
Prof. Milos Krstic's fault-tolerance group: **Junchao Chen** and **Li Lu** presented two RISC-V papers at RISC-V Europe 2023 — simulation-based fault injection on Ibex, and the TETRISC resilient quad-core RISC-V SoC. Graduate students from University of Potsdam co-supervised.

---

### France

**University of Rennes / IRISA / INRIA — Rennes**
**Prof. Angeliki Kritikakou** (Rennes / IRISA / INRIA): dual-core lockstep RISC-V using HLS for real-time safety-critical systems — RISC-V Europe 2023 presenter. Graduate computer architecture and embedded systems research.

**Université Bretagne Sud (University of Southern Brittany) — Lorient**
**William Pensec** (PhD): DIFT-protected RISC-V cores against fault injection attacks — RISC-V Europe 2023 presenter. Lab-STICC ARCAD team research in hardware security.

**Mines Saint-Étienne (IMT) — Saint-Étienne**
Joint research with CEA Leti; **Anthony Zgheib** PhD co-supervised here. Microelectronics and computer science engineering programs with RISC-V security research.

**Université Grenoble Alpes / TIMA Lab — Grenoble**
**Arthur Perais** (TIMA, Grenoble): high-performance processor microarchitecture research targeting RISC-V. CEA/UGA joint research environment. Strong HPC and architecture research group.

**École Normale Supérieure Paris-Saclay — Gif-sur-Yvette**
**Quentin Schibler** presented at RISC-V Europe 2023. Graduate computer science research with RISC-V components.

---

### Switzerland

**EPFL — Lausanne**
Joint work with TU Delft on RISC-V embedded systems (**Karan Pathak**, TU Delft/EPFL). **Jose A. Miranda Calero** (Carlos III Madrid / EPFL Embedded Systems Lab) conducted RISC-V reconfigurable computing research. EPFL feeds into the Grenoble/ETH RISC-V corridor.

- **2026 — X-HEEP (Pasquale Davide Schiavone, EPFL):** Open-source RISC-V SoC platform explicitly designed to lower the barrier to chip design for research and education. Provides configurable, extensible infrastructure for rapid custom RISC-V SoC development. Schiavone explicitly frames X-HEEP as supporting "broader European initiatives to advance semiconductor capabilities and technological sovereignty." First silicon confirmed via the Croc/MLEM tapeout at IHP 130nm (ETH/EPFL joint flow). X-HEEP has already enabled multiple academic tapeouts and is the basis for HyperCroc and ISOLDE space projects.

---

### United Kingdom

**University of Manchester — Manchester**
**Juan Fumero** (Manchester APT Research Group): TornadoVM hardware acceleration on RISC-V, AERO project — RISC-V Europe 2023 presenter. Advanced Processor Technologies (APT) group has documented RISC-V work.

**University of Edinburgh / EPCC — Edinburgh**
**Nick Brown** (EPCC): HPC work on RISC-V presented at RISC-V Europe 2023. EPCC is the UK's leading HPC research center; RISC-V appears in their emerging architecture evaluation work.

**lowRISC CIC — Cambridge / Bristol**
Not a degree-granting institution, but the nonprofit that maintains Ibex (contributed by ETH Zurich) and OpenTitan. Multiple RISC-V Europe 2023 poster presenters (Ibex UVM testbench paper). A key node connecting European academic RISC-V output to production use.

---

### Spain

**Universidad de Cantabria — Santander**
**Jaime Palacios** (MSc student): "Towards a RISC-V Educational HW Lab" — directly presented at RISC-V Europe 2023, documenting active curriculum development for RISC-V hardware-centric courses in CS/Engineering degrees.

**IMSE-CNM (CSIC / Universidad de Sevilla) — Seville**
**Luis Felipe Rojas Muñoz** (PostDoc): Root-of-Trust components for RISC-V SoCs using RO-PUF/TRNG — RISC-V Europe 2023 presenter. Hardware security research with RISC-V integration.

**Universitat Politècnica de Catalunya (UPC) — Barcelona**
Beyond BSC (already Tier 1), UPC's own faculty and students participate independently in RISC-V work. Graduate programs in Computer Architecture formally include RISC-V.

**Universitat Politècnica de València (UPV) — Valencia**
**Enrique S. Quintana-Ortí** (UPV): TinyML matrix multiplication on multicore RISC-V (GAP8) — RISC-V Europe 2023 presenter. Parallel Architectures Group (GAP) active in RISC-V HPC/embedded work.

**Universidad de Málaga — Málaga**
Present at RISC-V Europe 2023. Computer architecture research with RISC-V elements.

---

### Italy

**Sapienza University of Rome — Rome**
**Marcello Barbirotta** (Sapienza PhD): Dynamic Triple Modular Redundancy on RISC-V microarchitecture — RISC-V Europe 2023 presenter. Hardware fault tolerance research group with documented RISC-V coursework integration.

**University of Pisa — Pisa**
**Daniele Rossi** (University of Pisa): HW-SW Interface for RAS (Reliability, Availability, Serviceability) in RISC-V architectures — RISC-V Europe 2023 presenter. Digital systems and reliability research.

**University of Torino — Turin**
**Iacopo Colonnelli** (University of Torino): distributed workflow systems on RISC-V HPC platforms — RISC-V Europe 2023 presenter. CS department with RISC-V involvement in HPC research.

---

### Belgium

**KU Leuven / imec-DistriNet — Leuven**
**Marton Bognar** (imec-DistriNet, KU Leuven): hardware security work on RISC-V presented at RISC-V Europe 2023. Prof. Frank Piessens's security group. imec's industrial connections create strong applied RISC-V exposure.

---

### Netherlands

**University of Twente — Enschede**
Dr. Gerard Rauwerda (Technolution, PhD from University of Twente): SmallSat RISC-V payload platform — RISC-V Europe 2023 presenter. University of Twente ECE and CS programs have computer architecture research relevant to RISC-V.

---

### Austria

**Johannes Kepler University Linz — Linz**
**Lucas Klemmer** (JKU PhD): DSL for visualizing RISC-V pipelines — RISC-V Europe 2023 presenter. Institute for Complex Systems research in RISC-V tooling, verification, and waveform analysis.

**TU Wien (Vienna University of Technology) — Vienna**
**Philipp Tomsich** (VRULL GmbH, RISC-V Board Treasurer and TSC Vice-Chair) spent a decade at TU Wien teaching software engineering, OS kernels, and researching runtime systems and compilers for HPC — including early AI/ML kernel work. TU Wien's Informatics and Electrical Engineering programs have computer architecture and compiler research directly aligned with RISC-V toolchain development. Tomsich presented matrix extension progress at RISC-V Europe 2025.

---

### Portugal

**Universidade do Minho — Guimarães**
**Prof. Sandro Pinto** (UMinho): CROSSCON IoT security stack with RISC-V opportunity — RISC-V Europe 2023 presenter. Centro ALGORITMI/LASI group has documented RISC-V security research. UMinho's Computer Science and Engineering programs include embedded systems research with RISC-V.

---

### Greece

**University of Athens — Athens**
**Prof. Dimitris Gizopoulos** (Department of Informatics and Telecommunications) is Greece's most active RISC-V researcher and a Horizon Europe project partner.

- Co-PI of the **Vitamin-V** Horizon Europe project (2023–2025): built a production-grade open-source RISC-V cloud ecosystem covering QEMU, gem5, FPGA emulation, OpenStack, Kubernetes, and Kata Containers — with commercial partners Semidynamics, ZeroPoint, and Virtual Open Systems.
- **2026 — Cache Timing Vulnerability Score (CTVS) for RISC-V:** Gizopoulos's group (Vasileios Karakostas, Alexandros Ntyrkai) extended and ported the CTVS methodology to RISC-V, integrating it with gem5 to support RISC-V multicore simulation. Enables systematic early-stage security evaluation during processor design.
- Computer science and ECE architecture research using RISC-V is now documented and Horizon-Europe-scale.

**ICS-FORTH — Heraklion, Crete**
**Manolis Marazakis** (ICS-FORTH, Foundation for Research and Technology Hellas) leads the **RISER Horizon Europe project** (January 2023–): first-generation all-European RISC-V cloud server and accelerator prototypes, building on EPI and EUPILOT processor IP. The RISER Microserver Platform integrates EPAC1.5 RISC-V vector processor into a standalone compute node with NVMe storage and 100 Gbps Ethernet. Targets Europe's open strategic autonomy in cloud infrastructure.

---

### Albania *(Emerging — National Policy Initiative)*

**University of Tirana — Tirana**
Albania does not yet have documented RISC-V coursework, but it is the first Western Balkans country to articulate an explicit national strategy for RISC-V adoption at the EU summit level. **Kushtrim Shala** (Co-Founder, Digital Valley Albania / EDIH; Computing Sciences degree from University of Tirana) presented "Albania is an AI-Factory" at RISC-V Europe 2025 — outlining a strategy to embed RISC-V into Albanian CS and engineering education, establish a RISC-V-native AI compute facility, and transform the country's software outsourcing workforce into open-hardware architects.

- Albania's ICT sector employs tens of thousands of engineers currently focused on software outsourcing — the proposed pivot toward RISC-V education is workforce-scale, not just academic
- Digital Valley Albania is an officially recognized European Digital Innovation Hub (EDIH) under the Digital Europe Programme — giving this initiative EU structural backing
- The University of Tirana is the natural anchor institution for any national RISC-V curriculum rollout
- ALBICT (Albanian ICT Association) has supported 600+ youth projects and 75+ startups — the ecosystem infrastructure for curriculum change exists

*Action item:* Engage Kushtrim Shala directly. Albania represents the earliest-stage but most strategically explicit RISC-V education initiative in the Western Balkans — exactly the greenfield profile worth tracking from inception.

---

## European Context

- **PULP Platform** (ETH Zurich / Bologna): The most prolific source of open-source RISC-V IP in Europe. CVA6, Ibex, and Snitch are used as teaching and research platforms at dozens of European universities.
- **European Processor Initiative (EPI)**: EU-funded effort involving BSC, CEA, ETH Zurich, and others to build a European HPC processor. RISC-V vector accelerators are a core component.
- **Horizon Europe projects**: FRACTAL, NimbleAI, METASAT, AERO, CROSSCON, Scale4Edge, and Vitamin-V all use RISC-V as a primary platform — creating a network of university participants across the continent.
- **Scale4Edge** (Germany): National program scaling RISC-V for edge applications, involving TUM, RPTU, University of Bremen, and others.
- **RISC-V Educator of the Year (2019)**: Awarded to Dr. Leonidas Kosmidis (BSC/UPC) — the strongest European signal of recognized academic RISC-V leadership.
- **Matrix Extensions (2025)**: IME and VME converging on specification freeze, with a unified LLVM-MLIR lowering path in development. European institutions (ETH Zurich, VRULL/TU Wien, PULP partners) are active contributors — giving European academia a role in shaping the RISC-V AI/HPC ISA itself, not just implementing it.
- **Physical AI direction (2025)**: Luca Benini's 2025 keynote signals ETH/Bologna's next research frontier — safety, reliability, and efficiency for autonomous systems on RISC-V. Expect Horizon Europe projects in this space to emerge from the BSC and ETH networks.
- **Western Balkans opening**: Albania's RISC-V Education initiative (RISC-V Europe 2025) is the first explicit national-level RISC-V strategy in an EU accession country. Worth monitoring as a model for other emerging European economies.
- **CHERI/RVY ratification (2026):** Cambridge's 2026 papers reveal that the RVY ("CHERI") RISC-V extension specification is now frozen, with Cambridge having built the full validation infrastructure — formal golden model, fuzz testing, FPGA at scale. European institutions (Cambridge, lowRISC, TU Wien, Bao hypervisor) are central to CHERI's transition from research to ratified RISC-V standard.
- **Vitamin-V completion (2025):** The Horizon Europe Vitamin-V project (UPC/BSC + Univ. Athens + PoliTo + Semidynamics + ZeroPoint + Virtual Open Systems) delivered a production-grade open-source RISC-V cloud ecosystem in 2025 — one of the most comprehensive European RISC-V software stack efforts, enabling RISC-V cloud deployments with OpenStack and Kubernetes.
- **RISER European server platform:** ICS-FORTH-led Horizon Europe project targeting all-European RISC-V cloud server hardware with standalone compute nodes using EPI-derived RISC-V vector processors. The clearest European attempt at sovereign RISC-V cloud infrastructure.
- **IHP 130nm open PDK as European silicon commons:** Germany's IHP Microelectronics institute (Frankfurt/Oder) provides a fully open 130nm process design kit used for European RISC-V tapeouts — Croc (ETH/EPFL), HyperCroc, croc SEU-tolerance (ETH). IHP is becoming the European equivalent of SkyWater 130nm for academic RISC-V silicon.
- **PQC ISA extension wave (2026):** Seven or more RISC-V Europe 2026 papers propose or evaluate post-quantum cryptography ISA extensions (CIRCE, HORCRUX, CHIMERA, PQCUARK, HORCRUX, ACE, ML-KEM accelerators) — primarily from European institutions (PoliTo, BSC, CEA). Europe is positioned as the leading contributor to RISC-V PQC standardization, driven by EU regulation and the EC's post-quantum migration mandate.

---

*Maintenance tip:* The RISC-V Europe Summit (held annually) is the fastest European verification source — poster and talk presenter affiliations are the most reliable indicator of active institutional RISC-V research. Cross-reference with Horizon Europe grant databases (cordis.europa.eu) for project-level institutional participation.
