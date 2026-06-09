# RISC-V Global Academic Directory

An open-source directory mapping universities and research groups worldwide where RISC-V is part of the curriculum, the lab, or the research agenda.

**Live site:** https://cve415.github.io/RISC-V---Schools/

---

## What This Is

Tracking RISC-V academic adoption globally is highly fragmented. This repository aggregates verified institutional data into a single, filterable resource — organized by region and hardware focus area.

**Current coverage:** 125+ institutions across 26 countries — United States, Europe, China, Taiwan, India, Southeast Asia, Philippines, and Latin America.

Institutions are classified into two tiers:

| Tier | Criteria |
|------|----------|
| **Tier 1 — Confirmed** | Documented RISC-V coursework, published research, or silicon tapeout. Verifiable via syllabus, paper, or public repo. |
| **Tier 2 — Active** | Known RISC-V activity; verification source pending or partial. |

---

## Repository Structure

```
docs/               # GitHub Pages site (HTML + JSON datasets)
  data/
    schools.json    # Canonical institution dataset
    projects.json   # Student and academic project registry
internal/           # Working files, research notes, and watchlist (not served publicly)
  watchlist.md      # Candidate institutions pending verification
```

---

## Data

All institution data lives in [`docs/data/schools.json`](docs/data/schools.json). Each entry follows this schema:

```json
{
  "id": "eth-zurich",
  "name": "ETH Zürich",
  "country": "Switzerland",
  "region": "Europe",
  "tier_level": 1,
  "description": "...",
  "hardware_focus": ["CVA6 / Ariane Core", "Snitch Compute Clusters"],
  "website": "https://ee.ethz.ch",
  "is_active_chapter": true
}
```

Student and academic projects live in [`docs/data/projects.json`](docs/data/projects.json).

---

## How to Contribute

Submissions welcome via GitHub Issues or Pull Requests.

### Add a University
Open an issue titled `[Add University] Institution Name` and include:
- Institution name and country
- Evidence of RISC-V integration (course name/number, syllabus URL, published paper, or public repo)
- Primary hardware focus areas (e.g., FPGA prototyping, ASIC tapeout, embedded systems)
- Official department or lab URL

### Submit a Student Project
Open an issue titled `[Add Project] Project Name` and include:
- Project name and brief description
- Affiliated institution
- Public repository or publication URL
- Category (e.g., Microarchitecture, Embedded/MCU, SoC Generator)

### Update Existing Data
If a tier classification, website, or description is outdated, open an issue or submit a PR directly against the relevant JSON file.

---

## Maintainer

**Christopher Velasco** — RISC-V International Academia & Training SIG member  
Compiled from primary sources including course catalogs, published technical reports, NPTEL, RISC-V Summit and RISC-V Europe publications, and institutional research pages.

---

## License

Source code (HTML, JavaScript): [MIT License](LICENSE)

Dataset (`docs/data/schools.json`, `docs/data/projects.json`): [Creative Commons Attribution 4.0 International (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/) — free to use with attribution.

RISC-V® is a registered trademark of RISC-V International. This repository is an independent community resource and is not affiliated with or endorsed by RISC-V International.
