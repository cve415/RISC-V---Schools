**Compiled By:** Christopher Velasco, RISC-V International Academia & Training SIG member

---

## Overview

Europe is one of the three global centers of RISC-V academic gravity alongside the United States and China. European RISC-V academia is distinguished by three structural advantages: the **PULP Platform** (ETH Zurich / University of Bologna), which has produced the most widely adopted open-source RISC-V cores globally (CVA6, Ibex, Snitch); the **European Processor Initiative (EPI)** and a dense network of Horizon Europe research projects that institutionalize RISC-V across national boundaries; and the **Barcelona Supercomputing Center**, which anchors Spain's and Europe's safety-critical RISC-V research.

Primary sources: RISC-V Europe Summit 2023 poster session proceedings and RISC-V Europe Summit 2025 keynote/talk content — institutions whose researchers presented documented RISC-V work are treated as confirmed. Additional entries draw on known research program records.

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
- Participant in European Processor Initiative (EPI) vector acceleration work

---

### University of Bologna — Bologna, Italy

Co-originator of the PULP Platform with ETH Zurich. Prof. Luca Benini holds a dual appointment at ETH Zurich and Bologna; the PULP research group has roots at Bologna's **Department of Electrical, Electronic and Information Engineering (DEI)**.

- PULP cluster architecture and energy-efficient RISC-V multi-core research
- Graduate computer architecture courses use RISC-V; student teams contribute to open-source PULP cores
- RISC-V silicon tapeouts including GAP8 (GreenWaves Technologies, spun out of Bologna/EPFL research)
- **Marco Fariselli** (MSc Bologna 2019 → GreenWaves Technologies → Luxottica embedded AI): his 2025 summit talk on RISC-V for smart glasses traces a direct career arc from Bologna's academic RISC-V program to production edge AI silicon — one of the clearest examples of Bologna's graduate-to-industry RISC-V pipeline
- One of Europe's clearest examples of academic RISC-V research becoming commercial silicon; Luca Benini's 2025 keynote further confirms Bologna's co-anchoring role

---

### Barcelona Supercomputing Center (BSC) / Universitat Politècnica de Catalunya (UPC) — Barcelona, Spain

Europe's strongest RISC-V safety-critical research program. BSC's **CAOS group** (Computer Architecture / Operating Systems) has produced the NOEL-V processor, led multiple Horizon Europe RISC-V projects, and holds the RISC-V Educator of the Year Award (Dr. Leonidas Kosmidis, 2019).

- **NOEL-V**: BSC's open RISC-V processor (extending Gaisler's design) for safety-critical applications
- Documented RISC-V poster presentations at RISC-V Europe 2023: **Marcel Sarraseca** (SafeLS lockstep NOEL-V), **Francisco Javier Fuentes** (SafeTI traffic injector), **Leonidas Kosmidis** (METASAT multicore RISC-V platform)
- Active on Horizon Europe projects: FRACTAL, NimbleAI, METASAT, AERO
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

---

### Politecnico di Torino — Turin, Italy

Active RISC-V safety research program with documented publications and coursework.

- **Prof. Matteo Sonza Reorda** (Politecnico di Torino): RISC-V Self-Test Libraries (STLs) for safety-critical applications — RISC-V Europe 2023 poster, 400+ publications, IEEE Fellow
- Computer Engineering and Electronics courses use RISC-V
- Participant in European projects targeting RISC-V automotive and space applications
- Strong connections to the PULP ecosystem through Italian research networks

---

### CEA (French Alternative Energies and Atomic Energy Commission) — Grenoble / Saclay, France

France's primary RISC-V research institution, spanning multiple laboratories with documented RISC-V hardware security and SoC work.

- **CEA Leti (Grenoble)**: RISC-V Trace Encoder security work — **Anthony Zgheib** (PhD at Mines Saint-Étienne / CEA Leti) presented at RISC-V Europe 2023; Memory Authenticated Encryption Engine for CVA6 — **Karim Ait Lahssaine** (CEA Grenoble)
- **CEA List (Paris-Saclay / Grenoble)**: 128-bit RISC-V simulation — **Eduardo Tomasi Ribeiro**; VPSim virtual prototyping for RISC-V HPC — **Ayoub Mouhagir**; security platform — **Caaliph Andriamisaina**
- CEA participates in European Processor Initiative (EPI)
- Graduate students from Mines Saint-Étienne, Paris-Saclay, and Grenoble Alpes co-supervised with CEA labs

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
Present at RISC-V Europe 2023. Computer science and ECE programs with architecture research.

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

---

*Maintenance tip:* The RISC-V Europe Summit (held annually) is the fastest European verification source — poster and talk presenter affiliations are the most reliable indicator of active institutional RISC-V research. Cross-reference with Horizon Europe grant databases (cordis.europa.eu) for project-level institutional participation.
