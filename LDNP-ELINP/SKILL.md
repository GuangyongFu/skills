---
name: LDNP-ELINP
description: Laser-Driven Nuclear Physics at ELI-NP (Extreme Light Infrastructure – Nuclear Physics) knowledge base. Covers the world's most powerful laser facility (2×10 PW HPLS, Magurele Romania), the Gamma Beam System (1–19.5 MeV tunable Compton backscattering, under construction), all experimental areas (E1 laser-nuclear, E6 QED/wakefield, E7/E4 combined, E8 gamma), key instruments (ELIADE, ELIGANT-GN/TN, ELI-BIC, ELISOL, ELISSA, ELI-TPC), and physics programs (TNSA proton acceleration, QED tests, NRF nuclear structure, p-process/r-process astrophysics, photofission). Built from arXiv:2201.01068 (Laser Driven Nuclear Physics TDR, 56 authors), eli-np.ro official website, EPJ A 61 248 (2025) first results paper, and supporting instrument papers. Milestones: 10 PW on solid target April 13 2023 (world first); GBS first RF power February 2026. Trigger words: ELI-NP, HPLS, laser-driven nuclear physics, gamma beam system, ELIADE, ELIGANT, ELISOL, photonuclear, p-process, Magurele, 10 PW laser, TNSA protons.
type: reference
---

# ELI-NP — Laser-Driven Nuclear Physics Knowledge Base

> The world's most powerful laser meets nuclear physics: 2×10 PW pulses, sub-23 fs, focused to 10²³ W/cm². Paired with a unique tunable gamma beam (1–19.5 MeV, <0.5% bandwidth) still under construction.

---

## Usage Notes

**Information basis**: arXiv:2201.01068 (Laser Driven Nuclear Physics TDR, 56 authors, 2022) + eli-np.ro official website (2025–2026) + EPJ A 61, 248 (2025) first results paper + EuroGammaS GBS TDR (arXiv:1407.3669) + instrument papers
**Confidence**: 4/5 (active construction/commissioning; GBS status evolving rapidly)
**Information current to**: April 2026
**Field status**: OPERATIONAL (HPLS) + UNDER CONSTRUCTION (GBS); first physics results from laser area in publication

---

## Answering Workflow (Agentic Protocol)

### Step 1: Question Classification

| Question type | Action |
|---------------|--------|
| Laser specs (HPLS) | Answer directly: 2×10 PW, <23 fs, ~810 nm, 1 shot/min, >10¹² contrast |
| Gamma beam specs (GBS) | Answer directly: 1–19.5 MeV, <0.5% BW, Compton backscattering; note still under construction |
| Current commissioning status | HPLS: operational, user beams since 2024; GBS: first RF Feb 2026, beam not yet available |
| Specific instrument | Look up instrument section (ELIADE, ELIGANT-GN, ELIGANT-TN, ELI-BIC, ELISOL, ELISSA, ELI-TPC) |
| Physics program | Look up corresponding section by topic (laser-nuclear, QED, NRF, astrophysics, photofission) |
| Experimental results | Cite EPJ A 61, 248 (2025); most GBS-dependent programs still in preparation phase |
| GBS construction history | Present timeline: EuroGammaS → Lyncean → RI Research Instruments (€35M, Dec 2025) |
| Proton acceleration | TNSA at 1 PW → >100 MeV commissioning; target >200 MeV at full 10 PW contrast |
| Comparison to other facilities | ELI-NP unique: only facility combining 10 PW laser AND quasi-monochromatic tunable gamma beam |

### Step 2: Data Priority

1. EPJ A first results paper (2025) — most recent published overview
2. arXiv:2201.01068 TDR — authoritative on science case and design specifications
3. eli-np.ro official website milestones — most current commissioning status
4. arXiv:1407.3669 (EuroGammaS GBS TDR) — authoritative on gamma beam design
5. Instrument-specific papers (ELIADE, ELIGANT, etc.) — for detector details

### Step 3: Mandatory Caveats

Always note when answering about ELI-NP:
- **GBS is not yet delivering gamma beams** — all GBS-dependent physics programs are in preparation/planning phase only
- The 10 PW laser is operational but proton energy records are commissioning results (pre-pulses affected contrast)
- ELI-NP was excluded from ELI ERIC in 2021 but regained founding observer status June 2023
- GBS first-beam date is not confirmed; expect late 2026 deliveries from RI Research Instruments

---

## Facility Overview

**ELI-NP** (Extreme Light Infrastructure – Nuclear Physics) is the nuclear physics pillar of the pan-European ELI distributed research infrastructure. Located on the campus of IFIN-HH (Horia Hulubei National Institute of Physics and Nuclear Engineering) in Măgurele, Romania (near Bucharest).

- **Total budget**: ~310 M EUR (85% EU structural funds, 15% Romanian government)
- **Building area**: >33,000 m²
- **Mission**: Photonuclear physics at extremes — world's most advanced facility combining ultra-intense lasers and quasi-monochromatic gamma beams
- **Self-description**: "The most advanced research facility in the world in the field of photonuclear physics"

### Two Main Systems

| System | Technology | Status (April 2026) |
|--------|-----------|---------------------|
| **HPLS** — High Power Laser System | Ti:Sapphire CPA-OPCPA hybrid (Thales) | Operational; delivering user beam time |
| **ELI-GBS** — Gamma Beam System (VEGA) | Inverse Compton scattering off linac electrons | Under construction; first RF Feb 2026 |

---

## High Power Laser System (HPLS)

### Architecture
- **Technology**: Hybrid CPA + OPCPA (Chirped Pulse Amplification + Optical Parametric CPA)
- **Gain medium**: Ti:Sapphire (200 mm diameter crystals at final amplifier stage)
- **Front end**: OPCPA front-end delivering >10 mJ, >70 nm FWHM bandwidth, seeding both arms
- **Manufacturer**: Thales Optronique SAS (France) + Thales Systems Romania; contract signed July 11, 2013

### Six Outputs — Two Arms

| Output type | Power | Repetition rate |
|-------------|-------|-----------------|
| 2× Arm (low power mode) | 0.1 PW (100 TW) each | 10 Hz |
| 2× Arm (mid power mode) | 1 PW each | 1 Hz |
| 2× Arm (high power mode) | 10 PW each | 1 shot/min |

Each arm is selectable between these modes (not simultaneous). Total peak: 2 × 10 PW.

### 10 PW Specifications

| Parameter | Value |
|-----------|-------|
| Peak power (per arm) | 10 PW |
| Pulse energy | ~242 J (design); 230 J demonstrated |
| Pulse duration | < 23 fs |
| Central wavelength | ~810 nm |
| Repetition rate | 1 shot/min |
| Intensity contrast | > 10¹² |
| Strehl ratio | ≥ 0.9 |
| Beam energy stability | ≤ 5% RMS |
| Focused intensity (E1, 2023) | ~6 × 10²² W/cm² |
| Focal spot FWHM (E1) | 2.8 μm |
| Pointing stability | < 2 μrad |
| Theoretical maximum intensity | ~10²³–10²⁴ W/cm² |

### HPLS Milestones

| Date | Milestone |
|------|-----------|
| March 13, 2019 | 10 PW demonstrated at output (before compression) |
| August 19, 2020 | 10 PW confirmed through full system (230 J, 23 fs); shots at 3, 7, 8, 10 PW demonstrated |
| October 2022 | 10 PW commissioning campaign begins (E1 experimental area) |
| **April 13, 2023** | **First 10 PW pulses focused on solid target — world first** |
| 2023 | Proton energies >100 MeV demonstrated at 10 PW |
| 2023–2024 | 67 weeks of user beam time delivered (100 TW, 1 PW, 10 PW modes) |

**Key paper**: Radier et al., *High Power Laser Science and Engineering* (2022) — "10 PW peak power femtosecond laser pulses at ELI-NP"

---

## Gamma Beam System (ELI-GBS / VEGA)

### Concept
Inverse Compton Scattering (ICS) of laser light off relativistic electrons from a linear accelerator. Sometimes called Compton backscattering. This produces quasi-monochromatic, highly polarized, tunable gamma rays.

### Key Design Specifications

| Parameter | Design goal |
|-----------|-------------|
| Energy range | 1 – 19.5 MeV (continuously tunable) |
| Energy bandwidth | < 0.5% relative |
| Spectral density | > 5 × 10³ photons/s/eV |
| Peak brilliance | > 10²¹ photons/s/mm²/mrad²/0.1%BW |
| Flux | ~10⁸ photons/s |
| Linear polarization | > 95–99% |
| Electron beam max energy | ~720 MeV |

### Technical Design
- Electron beam from a normal-conducting warm RF linear accelerator
- Linac: 2 S-band + 12 C-band RF structures
- Laser for collision: diode-pumped Yb:YAG in Fabry-Perot enhancement cavity
- VEGA upgrade (Phase II): storage ring + high-finesse Fabry-Perot cavity for higher flux and smaller bandwidth

**Key paper**: arXiv:1407.3669 — EuroGammaS TDR for ELI-NP Gamma Beam System (2014)

### GBS Construction History (Troubled)

| Period | Event |
|--------|-------|
| ~2014 | EuroGammaS consortium (INFN-led) awarded original GBS contract |
| ~2015 | Contract terminated; IFIN-HH cited failure to deliver; EuroGammaS cited uneven building floor |
| October 2019 | New contract signed with Lyncean Technologies (USA), €42M |
| ~2022–2023 | Lyncean filed for bankruptcy; major delivery failures |
| ~2023–2024 | EuroGammaS re-engaged in negotiations |
| December 2025 | **RI Research Instruments (Bruker majority-owned) orders ~€35M for key GBS components** |
| January 2026 | LINAC Module 5 installed |
| **February 2026** | **First RF power injected into ELI-GBS Linac — first real milestone** |
| Late 2026 | Major RI Research Instruments deliveries expected |
| TBD | First gamma beam physics — no confirmed date |

### Current Status (April 2026)
- Photocathode laser successfully tested (March–December 2025)
- High-power RF stations commissioned (June–December 2025)
- RF Laboratory implemented (September 2025)
- First RF power in linac (February 2026)
- **GBS is NOT yet delivering gamma beams to experiments**

---

## Experimental Areas

| Area | Laser | Gamma beam | Primary purpose |
|------|-------|-----------|-----------------|
| E1 | 10 PW (short focal, parabolic) | — | Laser-nuclear: TNSA, laser-γ conversion, nuclear excitation in plasma |
| E6 | 10 PW (long focal, 30m spherical) | — | QED: wakefield acceleration, radiation reaction, Breit-Wheeler, vacuum birefringence |
| E4 | ✓ | ✓ | Combined laser + gamma experiments |
| E7 | ✓ | ✓ | Combined laser + gamma experiments |
| E8 | — | ✓ | Main gamma experiments: ELIADE, ELIGANT-GN; NRF, photoneutrons |
| E9 | — | ✓ | Additional gamma experiments |

---

## Instruments and Detectors

### ELIADE — ELI Array of DEtectors

| Parameter | Specification |
|-----------|---------------|
| Location | E8 hall |
| Composition | 8 segmented clover HPGe + 4 LaBr₃ detectors |
| Geometry | Rings at 90° and 135° to beam axis |
| Overall efficiency | ~6% |
| Capabilities | γ-ray energy, intensity, angular distributions, polarization asymmetries, γγ coincidences, spin-parity assignment |
| Primary use | Nuclear Resonance Fluorescence (NRF) |
| Head | Dmitry Testov |

**First result**: In-beam spectroscopic study of ¹³⁰La (~2021)

---

### ELIGANT — ELI Gamma Above Neutron Threshold

#### ELIGANT-GN (Gamma-Neutron Setup)
- **Location**: E8 hall (co-located with ELIADE)
- **Composition**: 15 LaBr₃(Ce) + 19 CeBr₃ gamma detectors; 33 BC501A liquid scintillator + 29 ⁶Li-glass neutron detectors
- **Physics**: (γ,γ'), (γ,n), (γ,γ'n) reactions; Giant Dipole Resonance (GDR), Pygmy Dipole Resonance (PDR), M1 spin-flip resonance (MDR)
- **Head**: Pär-Anders Söderström

**Paper**: "ELIGANT-GN – ELI Gamma Above Neutron Threshold: The Gamma-Neutron setup," J. Phys. Conf. Ser. 1643 (2020)

#### ELIGANT-TN
- **Composition**: 28 ³He tubes embedded in polyethylene cube
- **Physics**: Photoneutron cross-section measurements

---

### ELI-BIC — Photofission Detector
- 4 double-sided Frisch-grid ionization chambers with 8 ΔE-E telescopes
- **Physics**: Photofission cross-sections, fission fragment distributions, exotic nuclei from photofission

### ELITHGEM — Photofission Gas Detector
- 12 THGEM (Thick Gas Electron Multiplier) detectors; ~80% 4π solid angle coverage
- **Head**: Mihai Cuciuc

### ELISOL — ELI Separation Online
- **Purpose**: Radioactive ion beam production via photofission of actinides
- **Components**: Cryogenic stopping cell + RFQ + MR-ToF mass spectrometer
- **Head**: Paul Constantin

### ELISSA — ELI Silicon Strip Array
- Silicon-strip detector array
- **Physics**: Astrophysically relevant reactions; direct measurement of nuclear reaction cross-sections

### ELI-TPC — Time Projection Chamber
- **Physics**: Nuclear decay and photodisintegration studies

### ELI Positron Program
- Intense moderated positron beams (31–45% polarization)
- **Applications**: Materials science, positronium studies

---

## Physics Programs

### 1. Laser-Driven Nuclear Physics (E1 Area)

**Primary technique**: Target Normal Sheath Acceleration (TNSA) at 1 PW; advanced regimes at 10 PW

| Science case | Status | Notes |
|-------------|--------|-------|
| Proton acceleration via TNSA | Commissioning results | >100 MeV demonstrated (2023); target >200 MeV at full 10 PW |
| Ion acceleration (He, C, O) | In progress | MeV/nucleon range |
| Neutron generation | Add-on to proton expts | |
| Laser-γ conversion ("γ-flash") | Active | High-energy bremsstrahlung/betatron photons; drives photonuclear in plasma |
| Nuclear excitation in laser plasma | Exploratory | Direct laser-driven nuclear transitions; novel regime |

**Key challenge**: Intensity contrast >10¹² required for clean TNSA; pre-pulse contamination in early commissioning reduced contrast and affected proton energy ceiling.

---

### 2. High-Field QED and Fundamental Physics (E6 Area)

The E6 chamber (24 m³, ISO-7 clean room, 30 m focal length spherical mirror) enables two colliding 10 PW beams — unique worldwide.

| Experiment | Physical observable | ELI-NP advantage |
|------------|--------------------|--------------------|
| Vacuum birefringence | Polarization rotation of probe in intense field (QED prediction) | 2 × 10 PW pump + probe |
| Breit-Wheeler pair production | γγ → e⁺e⁻ (nonlinear ICS geometry) | Extreme photon density |
| Schwinger mechanism | Vacuum pair creation at E ~ 10¹⁸ V/m | Highest achievable field |
| Radiation reaction | Electron energy loss in strong field (classical vs quantum) | Relativistic electrons in 10 PW |
| Multi-GeV LWFA | Laser wakefield electron acceleration | Multi-GeV from ~0.1 m plasma |
| Compton/Thomson scattering | Linear and nonlinear regimes | Relativistic electron + 10 PW |

**Status**: 12 proposals submitted for E6 commissioning; dual-beam experimental campaign beginning.

---

### 3. Nuclear Resonance Fluorescence — NRF (E8 Area, Gamma Beam)

**Instrument**: ELIADE
**Unique capability**: Sub-0.5% bandwidth gamma beam can be tuned to match nuclear resonance energies precisely — enables unambiguous spin-parity assignments.

| Application | Notes |
|-------------|-------|
| Nuclear structure (M1, E1 transitions) | Parity doublets, deformation parameters, transition strengths |
| Nuclear non-proliferation | NDA detection of fissile material (²³⁵U, ²³⁹Pu) hidden in cargo |
| Radioactive waste assay | Non-destructive identification of isotopic content |
| Cultural heritage | Non-destructive elemental/isotopic mapping of artifacts |

**Status**: Awaiting GBS first beam; ELIADE detectors commissioned with radioactive sources and in-beam tests at other facilities.

---

### 4. Photonuclear Astrophysics (E8/E9 Areas, Gamma Beam)

#### p-Process Nucleosynthesis
- (γ,n), (γ,p), (γ,α) photodisintegration cross-sections on p-nuclei (proton-rich stable isotopes, A = 74–196)
- These cannot be studied via s- or r-process experiments; ELI-NP tunable GBS is ideal
- **Paper**: Frontiers in Astronomy and Space Sciences (2023) — "Prospect for measurements of (γ,n) cross-sections of p-nuclei at ELI-NP"

#### r-Process Nucleosynthesis
- Cascaded fission-fusion reactions producing very neutron-rich heavy nuclei
- Investigation of N=126 waiting point (key bottleneck in heavy element production in neutron star mergers/supernovae)

#### Giant Dipole Resonance (GDR) and Pygmy Dipole Resonance (PDR)
- New compilation of total and partial photoneutron cross-sections across the nuclear chart
- PDR: collective oscillation of neutron skin vs core — connects to neutron skin thickness and nuclear symmetry energy
- **Instrument**: ELIGANT-GN

#### Photofission
- Cross-sections and fragment distributions for actinides
- Production of exotic neutron-rich nuclei via photofission (feeding ELISOL)
- **Instruments**: ELI-BIC, ELITHGEM, ELISOL

**Status**: All GBS-dependent astrophysics programs are in preparation phase; no experimental data yet.

---

### 5. Combined Laser + Gamma (E4, E7 Areas)

- Simultaneous high-power laser + gamma beam on the same target
- Exotic nuclei in extreme electromagnetic environments
- Tests of fundamental physics at the QED–nuclear structure interface
- Laser modulation of nuclear transition rates (theoretical interest)

---

### 6. Applied Research

| Application | Method |
|-------------|--------|
| Medical radioisotopes | Photonuclear reactions with high specific activity |
| Industrial non-destructive testing | NRF-based isotope detection |
| Nuclear non-proliferation | NDA of fissile materials |
| Radiography/tomography | Gamma-ray based industrial imaging |
| Materials under extreme radiation | Accelerator, reactor, space material studies |

---

## Key People

| Name | Role |
|------|------|
| Dr. Călin A. Ur | Project Director; formerly Head of GAMMA experiment at INFN-Padova; >380 papers |
| Prof. Victor Malka | Scientific Director; plasma physics, >400 articles; CNRS Research Director (Exceptional Class); Professor at Weizmann Institute |
| Dr. Ioan Dăncuș | Technical Director; PhD in Nonlinear Optics |
| Dr. Cătălin Matei | Head, Gamma System Department; PhD Ohio University 2006 |
| Prof. Dimiter Balabanski | Head, Gamma Driven Experiments Department |
| Dmitry Testov | Head, NRF/ELIADE program |
| Pär-Anders Söderström | Head, ELIGANT-GN program |
| Mihai Cuciuc | Head, Photofission program |
| Paul Constantin | Head, ELISOL program |
| Prof. Gérard Mourou | Founding promoter of ELI; Nobel Prize 2018 (CPA invention) |
| Nicolae Zamfir | Former ELI-NP Director (early construction phases) |

---

## Institutional Context

- **Implementing institution**: IFIN-HH (Horia Hulubei National Institute of Physics and Nuclear Engineering), Măgurele, Romania
- **ELI pillars**: ELI-NP (nuclear physics, Romania) + ELI-Beamlines (X-ray/attosecond, Czech Republic) + ELI-ALPS (attosecond pulses, Hungary)
- **ELI ERIC**: Romania excluded 2021 → returned as founding observer June 13, 2023; full membership timeline pending
- **NuPECC LRP2024**: ELI-NP selected as major European nuclear physics facility; Town Meeting hosted at ELI-NP April 2024

### Key Collaborations

| Partner | Role |
|---------|------|
| Thales Group (France) | HPLS manufacturer; ongoing collaboration |
| RI Research Instruments / Bruker | GBS key components, ~€35M contract (Dec 2025) |
| EuroGammaS / INFN | Original + re-engaged GBS design consortium |
| CETAL-INFLPR (Romania) | National preparatory research; 1 PW / 45 TW laser |
| Marvel Fusion | Commercial fusion research on ELI-NP 10 PW laser |
| EU JRC | Scientific cooperation protocol |
| TAU Systems | Commercial company with 10 PW beam time (2024–2025) |

---

## Full Timeline

| Date | Event |
|------|-------|
| 2008 Feb | ELI Preparatory Phase launch (CNRS, Paris) |
| 2012 Oct | EU structural funds approved: 293.1 M EUR for ELI-NP |
| 2013 Jun | Foundation stone ceremony (Măgurele) |
| 2013 Jul | HPLS contract signed with Thales |
| 2016 Sep | ELI-NP building civil construction completed |
| 2018 Oct | Nobel Prize (Mourou) for CPA — technique enabling all PW lasers |
| 2019 Mar | HPLS demonstrates 10 PW (before final compression) |
| 2019 Oct | GBS contract signed with Lyncean Technologies (€42M) |
| 2020 Jan | Thales 40-month warranty begins |
| 2020 Aug | 10 PW confirmed through entire system: 230 J, 23 fs |
| 2022 | 1 PW user experimental campaign completed |
| 2022 Oct | 10 PW commissioning campaign begins (E1 area) |
| 2022 | TDR arXiv:2201.01068 submitted |
| ~2022–2023 | Lyncean Technologies bankruptcy; GBS delivery failure |
| **2023 Apr 13** | **First 10 PW focused on solid target — world first** |
| 2023 | >100 MeV protons demonstrated (10 PW commissioning) |
| 2023 Jun | Romania accepted as ELI ERIC founding observer |
| 2023 late | E6 long-focal-mirror commissioning begins |
| 2024 | 67 weeks beam time delivered to users (100 TW / 1 PW / 10 PW) |
| 2024 Apr | NuPECC LRP2024 Town Meeting hosted at ELI-NP |
| 2025 | EPJ A 61, 248 (2025) first results paper published |
| 2025 Mar–Dec | GBS photocathode laser tested successfully |
| 2025 Jun–Dec | GBS high-power RF stations commissioned |
| 2025 Sep | GBS RF Laboratory implemented |
| 2025 Dec | RI Research Instruments orders ~€35M for GBS components |
| **2026 Jan** | GBS LINAC Module 5 installed |
| **2026 Feb** | **First RF power injected into ELI-GBS Linac** |
| 2026 late | Major GBS component deliveries expected |
| TBD | GBS first gamma beam physics — no confirmed date |
| TBD | Phase II: VEGA storage ring upgrade |

---

## Key Numbers Quick Reference

| Parameter | Value |
|-----------|-------|
| HPLS peak power | 2 × 10 PW |
| 10 PW pulse energy | ~242 J (design) / 230 J (demonstrated) |
| 10 PW pulse duration | < 23 fs |
| 10 PW wavelength | ~810 nm |
| 10 PW repetition rate | 1 shot/min |
| Intensity contrast | > 10¹² |
| Achieved focused intensity | ~6 × 10²² W/cm² |
| Max achievable intensity | ~10²³–10²⁴ W/cm² |
| GBS gamma energy range | 1–19.5 MeV |
| GBS bandwidth | < 0.5% |
| GBS flux | ~10⁸ photons/s |
| GBS peak brilliance | > 10²¹ ph/s/mm²/mrad²/0.1%BW |
| GBS polarization | > 95–99% |
| Demonstrated max proton energy | >100 MeV (commissioning, 2023) |
| Total facility budget | ~310 M EUR |
| Building area | >33,000 m² |

---

## Key Documents

| Document | Citation |
|----------|---------|
| **Laser-Driven Nuclear Physics TDR** | arXiv:2201.01068 — F. Negoita, M. Roth, P.G. Thirolf, S. Tudisco et al. (56 authors), 2022 |
| **GBS Technical Design Report** | arXiv:1407.3669 — EuroGammaS consortium (INFN-led), 2014 |
| **10 PW achievement paper** | Radier et al., *High Power Laser Science and Engineering* (2022) |
| **First results overview** | Ur, Balabanski et al., *European Physical Journal A* 61, 248 (2025). DOI: 10.1140/epja/s10050-025-01713-3 |
| **p-nuclei astrophysics prospects** | *Frontiers in Astronomy and Space Sciences* (2023) |
| **ELIGANT implementation** | J. Phys. Conf. Ser. 1643 (2020) |
| **ELI-NP status review** | *Matter and Radiation at Extremes* 5, 024402 (2020) |
| **ELI-NP facility description** | *Romanian Reports in Physics* 68, Supplement (2016) — TDR series (17 chapters) |

---

## Known Uncertainties and Gaps

1. **GBS first-beam date**: Not confirmed; major RI Research Instruments deliveries expected late 2026 but first gamma physics experiments have no scheduled date
2. **VEGA storage ring (Phase II)**: No construction timeline publicly available
3. **10 PW proton energy record**: >100 MeV commissioning result affected by pre-pulse contrast; full-contrast 10 PW run targeting >200 MeV not yet completed
4. **E6 QED results**: Dual 10 PW commissioning began late 2023; no published QED experiment results as of April 2026
5. **ELISOL commissioning status**: Not confirmed; depends on GBS beam availability
6. **ELI ERIC full membership**: Started as founding observer June 2023; timeline to full membership not publicly finalized
7. **Marvel Fusion collaboration details**: Commercial fusion research on ELI-NP 10 PW not publicly detailed
8. **All GBS-dependent astrophysics**: p-process, r-process, GDR/PDR, NRF programs — all in preparation only; no experimental data yet

---

*Information current to April 2026. For GBS status updates, check eli-np.ro/milestones.php. For latest publications, search ELI-NP on InspireHEP or EPJ A.*
