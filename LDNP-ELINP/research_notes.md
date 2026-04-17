# ELI-NP Research Notes
## Extreme Light Infrastructure – Nuclear Physics, Magurele, Romania

**Compiled:** April 2026  
**Primary Sources:** arXiv:2201.01068 (TDR), eli-np.ro official website, ELI-NP TDR document series, ELI ERIC, Wikipedia, Science|Business, journal publications.

---

## A. Facility Overview

### What is ELI-NP?
ELI-NP (Extreme Light Infrastructure – Nuclear Physics) is described as "the most advanced research facility in the world in the field of photonuclear physics." It is the nuclear physics pillar of the Pan-European Distributed Research Infrastructure ELI (Extreme Light Infrastructure), started in 2012.

### Location
- **City/Country:** Magurele (Măgurele), Ilfov County, Romania (near Bucharest)
- **Site:** Horia Hulubei National Institute of Physics and Nuclear Engineering (IFIN-HH) campus

### Implementing Institution and Funding
- **Implementing Institution:** Horia Hulubei National Institute of Physics and Nuclear Engineering (IFIN-HH)
- **Funding:** Co-financed by the European Commission and Romanian Government through the European Regional Development Fund (ERDF)
- **Total Implementation Budget:** ~310 million EUR (85% European funds, 15% national budget); EU structural funds allocation of 293.1 million EUR approved October 2012
- **Significance:** Largest scientific investment in Romania's history; IFIN-HH generates ~10% of Romania's total scientific output

### ELI ERIC Status
- Romania was excluded from ELI ERIC (European Research Infrastructure Consortium) formation in 2021 due to contract disputes
- Romania regained "founding observer" status in ELI ERIC on June 13, 2023, with a plan for full integration over three years

### The Two Main Systems
1. **HPLS – High Power Laser System**: Dual-arm 10 PW Ti:Sapphire laser (built by Thales)
2. **ELI-GBS (VEGA) – Variable Energy Gamma-ray (Beam) System**: Inverse Compton scattering gamma source (still under construction as of early 2026)

---

## B. Laser Systems — Technical Specifications (HPLS)

### Architecture
- **Technology:** Hybrid CPA–OPCPA (Chirped Pulse Amplification combined with Optical Parametric CPA)
- **Gain medium:** Ti:Sapphire crystals (200 mm diameter crystals used at the final amplification stage)
- **Front end:** OPCPA front-end delivering >10 mJ pulses with spectral bandwidth >70 nm FWHM, seeding both beamlines
- **Manufacturer:** Thales Optronique SAS (France) and Thales Systems Romania; contract signed July 11, 2013
- **Warranty started:** January 1, 2020 (40-month warranty)

### Output Structure — Six Optical Outputs (Two Arms)
| Output | Power | Repetition Rate |
|--------|-------|-----------------|
| 2 × Arm A low power | 0.1 PW (100 TW) each | 10 Hz |
| 2 × Arm B mid power | 1 PW each | 1 Hz |
| 2 × Arm C high power | 10 PW each | 1 shot/min (1/60 Hz) |

Each arm can deliver 0.1 PW at 10 Hz, 1 PW at 1 Hz, or 10 PW at 1 shot per minute — these are not simultaneous but selectable outputs from each arm.

### 10 PW Output Specifications
- **Peak power:** 10 PW per arm (2 × 10 PW total)
- **Pulse energy:** ~242 J (calculated); earlier commissioning showed >120 J before final amplifier stage; design target ~240 J
- **Pulse duration:** <23 fs (design goal <25 fs)
- **Central wavelength:** ~810 nm (Ti:Sapphire)
- **Repetition rate:** 1 shot per minute
- **Intensity contrast:** > 10¹² (design requirement)
- **Strehl ratio:** ≥ 0.9
- **Beam energy stability:** ≤ 5% RMS
- **Focused intensity on target:** ~6 × 10²² W/cm² (measured in E1 commissioning, 2023)
- **Focal spot:** 2.8 μm FWHM (measured at E1)
- **Pointing stability:** < 2 μrad

### Achieved Milestones
- **March 13, 2019:** HPLS achieved its designed 10 PW performance (output before compression; proof of capability)
- **August 19, 2020:** Successfully achieved 10 PW shots (230 J, 23 fs) through the entire system at 1-shot-per-minute intervals; also demonstrated repeated shots at 3, 7, 8, 10 PW — 10 PW capability confirmed
- **October 2022:** Commissioning of 10 PW experimental setup started (E1 area)
- **April 13, 2023:** First 10 PW laser pulses focused on a solid target in the world — a historic milestone
- **2023–2024:** Laser delivered 67 weeks of beam time to users, distributed across 100 TW, 1 PW, and 10 PW modes

### Beam Transport
- **Laser Beam Transport System (LBTS):** Delivers beams to experimental areas E1, E6, and E7; contract awarded December 2017
- LBTS successfully delivers pulses to experimental areas without impact on system integrity

### Related Facility: CETAL
- CETAL (Center for Advanced Laser Technologies) is part of INFLPR (Institute for Plasma Research and Nuclear Fusion in Romania), separate from ELI-NP but a key collaborator
- CETAL-PW: 1 PW @ 0.1 Hz, 45 TW @ 10 Hz Ti:Sapphire laser (Thales); used for preparatory research for ELI-NP science cases

---

## C. Gamma Beam System (ELI-GBS / VEGA System)

### Concept
The ELI-NP Gamma Beam System is based on **Inverse Compton Scattering (ICS)** — also called Compton backscattering — of laser light off relativistic electron bunches from a linear accelerator.

### Key Specifications (Design Goals)
| Parameter | Value |
|-----------|-------|
| Gamma-ray energy range | 1 MeV – 19.5 MeV (continuously tunable) |
| Energy bandwidth | < 0.5% relative bandwidth |
| Spectral density | > 5 × 10³ photons/s/eV (some sources cite > 10⁴ photons/s/eV) |
| Peak brilliance | > 10²¹ photons/s/mm²/mrad²/0.1%BW |
| Flux | ~10⁸ photons/s |
| Linear polarization | > 95–99% |
| Transverse beam size | millimeter range |
| Electron beam max energy | ~720 MeV |

### Technical Design (EuroGammaS TDR, arXiv:1407.3669)
- Electron beam from a normal-conducting warm RF linear accelerator
- Linac composed of: 2 S-band RF structures + 12 C-band RF structures
- Laser system for collision: diode-pumped Yb:YAG laser in a Fabry-Perot enhancement cavity
- The "VEGA" name (Variable Energy Gamma-ray) refers to the planned storage-ring-based advanced upgrade; the initial GBS design uses a linac
- The VEGA upgrade concept uses a **storage ring** with a high-finesse Fabry-Perot cavity to resonantly build up laser power, enabling higher flux and smaller bandwidth than initial linac-only design

### Troubled History of GBS Construction
1. **Original contract:** EuroGammaS consortium (led by INFN, Italy; Franco-Italian-led European academic consortium) awarded the initial GBS contract
2. **Contract terminated ~2015:** IFIN-HH terminated the EuroGammaS contract citing failure to deliver; EuroGammaS cited uneven building floor as the reason they could not install
3. **Lyncean Technologies (USA):** Won a new contract (€42M) signed October 4, 2019; Lyncean subsequently filed for bankruptcy (ca. 2022–2023) and had major problems delivering
4. **EuroGammaS re-engagement:** IFIN-HH and EuroGammaS reached a new agreement and EuroGammaS was invited back to the negotiating table
5. **RI Research Instruments contract (December 2025):** RI Research Instruments (majority-owned by Bruker Corporation) announced orders for key components worth ~€35 million; major deliveries expected late 2026; Phase 1: expand existing particle accelerator + supply beam guidance/focusing components; Phase 2: upgrade Linac to increase pulse rate by factor of 200×

### Current Commissioning Status (as of early 2026)
- **February 2026:** First RF power injected into ELI-GBS Linac — first real milestone
- **January 2026:** LINAC Module 5 installed and ready for high-power RF
- **June–December 2025:** High-power RF stations commissioned
- **March–December 2025:** Photocathode laser successfully tested
- **September 2025:** RF Laboratory implemented
- GBS is still under construction and not yet delivering gamma beams to physics experiments
- Department head: Dr. Cătălin Matei (PhD, Ohio University, 2006; >15 years nuclear physics experience)

---

## D. Experimental Areas

ELI-NP has multiple dedicated experimental halls/areas:

| Area | Purpose |
|------|---------|
| E1 | 10 PW laser — short focal parabolic mirror; solid target laser-nuclear experiments |
| E6 | 10 PW laser — long focal spherical mirror; QED/wakefield acceleration experiments |
| E7 | Combined laser + gamma experiments |
| E4 | Combined laser + gamma experiments |
| E8 | Main gamma-driven experiments hall (ELIADE, ELIGANT-GN) |
| E9 | Additional gamma experiments |

---

## E. Key Experiments and Instruments

### E1 Area — Laser-Driven Nuclear Physics
- **Science:** Laser-plasma interactions, particle acceleration, laser-γ conversion ("γ-flash"), nuclear excitation in plasma
- **Commissioning:** Started October 2022; first 10 PW on solid target April 13, 2023
- **Key result:** Proton energies exceeding 100 MeV achieved during commissioning (with some pre-pulses affecting contrast; partially fixed)
- Main regime: TNSA (Target Normal Sheath Acceleration) at 1 PW; higher-energy regimes at 10 PW

### E6 Area — High-Field Physics and QED
- **Chamber:** 24 m³ interaction chamber with ISO-7 clean room; 30-meter focal length spherical mirror
- **Science:** 
  - Laser wakefield electron acceleration to multi-GeV energies
  - Radiation Reaction Physics (classical and quantum)
  - Breit-Wheeler pair production (photon-photon → e⁺e⁻)
  - Schwinger mechanism (vacuum pair creation)
  - Vacuum birefringence measurement
  - Compton/Thomson scattering (linear and nonlinear)
  - Atoms in extreme laser fields
- **Equipment:** Multi-GeV electron/gamma spectrometers, gas target designs, supersonic nozzles, laser/plasma diagnostics
- **Commissioning:** 12 proposals submitted for E6 commissioning runs (dual 10 PW beams)

### ELIADE — ELI Array of DEtectors
- **Purpose:** Primary detector array for NRF (Nuclear Resonance Fluorescence) studies using the gamma beam
- **Composition:** 8 segmented clover HPGe (High-Purity Germanium) detectors + 4 LaBr₃ detectors
- **Geometry:** Arranged in rings at 90° and 135° relative to beam axis
- **Efficiency:** ~6% overall
- **Capabilities:** γ-ray energy, intensity, angular distributions, polarization asymmetries, γγ coincidences; unique spin-parity assignments
- **Location:** Experimental hall E8
- **Head:** Dmitry Testov
- **Published result:** First in-beam experiment with ELIADE detectors: spectroscopic study of ¹³⁰La (published ca. 2021)

### ELIGANT — ELI Gamma Above Neutron Threshold
The ELIGANT family of instruments addresses physics above the neutron separation energy:

#### ELIGANT-GN (Gamma-Neutron Setup)
- **Composition:** 15 LaBr₃(Ce) + 19 CeBr₃ gamma detectors; 33 BC501A liquid scintillator neutron detectors + 29 ⁶Li-glass neutron detectors (total 33+22 or 33+29 depending on source)
- Some sources cite: 17 LaBr₃(Ce) + 17 CeBr₃ + 33 BC501A + 29 ⁶Li-glass
- **Location:** Experimental hall E8 (co-located with ELIADE)
- **Physics:** (γ,γ'), (γ,n), (γ,γ'n), (γ,νn) reactions; Giant Dipole Resonance (GDR), Pygmy Dipole Resonance (PDR), spin-flip M1 resonance (MDR)
- **Head:** Pär-Anders Söderström

#### ELIGANT-TN
- **Composition:** 28 helium-3 (³He) tubes embedded in polyethylene cube
- **Physics:** Photoneutron cross-section measurements

### ELI-BIC — Photofission Detector
- **Composition:** 4 double-sided Frisch-grid ionization chambers with 8 ΔE-E telescopes
- **Physics:** Photofission cross-sections, fission fragment distributions, exotic nuclei from photofission

### ELITHGEM — Photofission Gas Detector
- **Composition:** 12 THGEM (Thick Gas Electron Multiplier) detectors
- **Coverage:** ~80% of 4π solid angle
- **Physics:** Photofission studies
- **Head (Photofission program):** Mihai Cuciuc

### ELISOL — ELI Separation Online
- **Purpose:** Produces radioactive ion beams via photofission; exotic nuclear structure studies
- **Components:** Cryogenic stopping cell + RFQ (Radio-Frequency Quadrupole) + MR-ToF (Multi-Reflection Time-of-Flight) mass spectrometer
- **Head:** Paul Constantin

### ELISSA — ELI Silicon Strip Array
- **Composition:** Silicon-strip detector array
- **Physics:** Astrophysically relevant reactions

### ELI-TPC — Time Projection Chamber
- **Physics:** Nuclear decay and photodisintegration studies

### ELI Positron Program
- **Purpose:** Production of intense moderated positron beams (up to 31–45% polarization)
- **Applications:** Materials science, positronium studies

---

## F. Physics Programs

### F.1 Laser-Driven Nuclear Physics (E1 Area)
- **Particle acceleration:** Protons via TNSA and advanced schemes; target: 200+ MeV protons (using 10 PW); demonstrated >100 MeV in commissioning
- **Neutron generation:** Add-on to proton experiments
- **Laser-γ conversion ("γ-flash"):** High-energy bremsstrahlung/betatron from laser-plasma; nuclear reactions in plasma
- **Ion acceleration:** Helium, carbon, oxygen ions at MeV/nucleon range
- **Nuclear excitation in laser plasma:** Direct laser-driven nuclear transitions

### F.2 High-Field QED and Fundamental Physics (E6 Area)
- **Vacuum birefringence:** Measurement of QED-predicted polarization rotation of light in intense fields; theoretical studies of ELI-NP 10 PW pump laser as probe
- **Breit-Wheeler pair production:** Photon-photon → e⁺e⁻ (nonlinear); testing QED in extreme fields
- **Schwinger mechanism:** Vacuum breakdown and spontaneous pair creation
- **Radiation reaction:** Classical and quantum regimes; test of QED predictions for electron dynamics in intense fields
- **Multi-GeV electron acceleration:** Laser wakefield acceleration in gas targets
- **Compton/Thomson scattering:** Linear and nonlinear regimes with relativistic electrons

### F.3 Nuclear Resonance Fluorescence (E8/E9 Areas, Gamma Beam)
- **Instrument:** ELIADE
- **Physics:** Nuclear structure (spin, parity, transition strengths of excited states), M1 and E1 transitions, parity doublets, nuclear deformation
- **Applied NRF:** Non-destructive assay (NDA) of radioactive waste, nuclear non-proliferation (detection of fissile material), cultural heritage
- **Key feature:** Narrow-bandwidth (<0.5%) gamma beam enables precise resonance excitation

### F.4 Photonuclear Reactions and Astrophysics (E8 Area, Gamma Beam)

#### p-Process Nucleosynthesis
- (γ,n), (γ,p), (γ,α) photodisintegration cross-sections on p-nuclei (proton-rich stable isotopes)
- These reactions cannot be studied with s- or r-processes; ELI-NP GBS tunable energy is ideal
- Relevant reactions: photodisintegration of stable isotopes in the mass A = 74–196 range
- Published paper: Frontiers in Astronomy and Space Sciences (2023) on prospects for (γ,n) cross-sections of p-nuclei at ELI-NP

#### r-Process Nucleosynthesis
- Cascaded fission-fusion reactions producing very neutron-rich heavy nuclei
- Investigation of N=126 waiting point of the r-process (key bottleneck in heavy element production)
- Connects to understanding production of elements beyond iron in neutron star mergers/supernovae

#### Giant Dipole Resonance (GDR)
- New compilation of total and partial photoneutron cross-sections
- GDR systematics across the nuclear chart using tunable gamma beam

#### Pygmy Dipole Resonance (PDR)
- Collective oscillation of neutron skin against proton-neutron core
- Related to neutron skin thickness and nuclear symmetry energy

#### Photo-fission
- Cross-sections, fragment distributions
- Production of exotic neutron-rich nuclei by photofission of actinides

### F.5 Combined Laser + Gamma Experiments (E7, E4 Areas)
- Simultaneous use of high-power laser and gamma beam
- Exotic nuclei in extreme electromagnetic environments
- Tests of fundamental physics at the interface of QED and nuclear structure

### F.6 Nuclear Isomers and Applied Nuclear Physics
- Neutron production via gamma-beam excitation of neutron-halo isomers (photon beam dissociates neutron halo states)
- Isomer triggering / controlled nuclear de-excitation
- Nuclear clock applications (connection to precision metrology)

### F.7 Applied Research
- **Medical radioisotopes:** Photonuclear reactions producing medical radioisotopes with high specific activity
- **Industrial NRF:** Non-destructive testing, isotope detection (explosives, nuclear material)
- **Radioscopy/Tomography:** Gamma-ray based industrial imaging
- **Materials under extreme radiation:** Accelerator, reactor, and space material studies
- **Laser-based NMR battery diagnostics:** Contributed to international breakthrough (January 2026)

---

## G. Key People

### Current Leadership (as of 2025–2026)
| Name | Role |
|------|------|
| Dr. Călin A. Ur | Project Director; formerly Head of GAMMA Experiment at INFN-Padova; >380 papers; heads PhD School on Engineering and Applications of Lasers and Accelerators at Politehnica University Bucharest (since 2015) |
| Prof. Dr. Victor Malka | Scientific Director; world-renowned plasma physicist; >400 articles; Research Director (Exceptional Class) at CNRS; Professor at Weizmann Institute of Science; laureate of many international prizes |
| Dr. Ioan Dăncuș | Technical Director; PhD in Nonlinear Optics; >10 years at ELI-NP; associate professor at Politehnica University of Bucharest and West University of Timișoara |
| Ec. Alexandru Popescu | Economic Director; managing 310 M EUR budget since 2012 |
| Dr. Cătălin Matei | Head, Gamma System Department; PhD Ohio University 2006 |
| Prof. Dimiter Balabanski | Head, Gamma Driven Experiments Department; 25+ years nuclear physics experience |
| Dmitry Testov | Head, NRF/ELIADE program |
| Pär-Anders Söderström | Head, ELIGANT-GN program |
| Mihai Cuciuc | Head, Photofission program |
| Paul Constantin | Head, ELISOL program |

### Historical/Founding Figures
- **Prof. Gérard Mourou (Nobel Prize 2018):** Initiator and promoter of the European ELI project; Nobel Prize in Physics 2018 for CPA invention; visited during French President Hollande's trip (September 2016)
- **Nicolae Zamfir:** Former ELI-NP Director (director during early construction phases)

### TDR Authors (arXiv:2201.01068)
Lead authors: F. Negoita, M. Roth, P.G. Thirolf, S. Tudisco; total 56 authors from multiple international institutions

---

## H. Collaborations and International Context

### ELI Ecosystem
- **ELI ERIC:** The pan-European consortium governing the three ELI pillars; Romania as founding observer since June 2023
- **ELI-Beamlines (Czech Republic):** High-power laser pillar with different emphasis (attosecond, X-ray, proton therapy)
- **ELI-ALPS (Hungary):** Attosecond Light Pulse Source pillar

### Key Collaboration Partners
- **EuroGammaS:** INFN-led European consortium (including INFN Frascati, LAL, LNF, Elettra, etc.) that developed the original GBS TDR (arXiv:1407.3669); now re-engaged after disputes
- **Thales Group (France):** Manufacturer of the HPLS laser system; ongoing collaboration including Marvel Fusion partnership announcement (2022)
- **Marvel Fusion:** Collaboration with Thales and ELI-NP for inertial fusion research using the 10 PW laser
- **IFIN-HH:** Implementing institution; also home to the TANDEM accelerator and other nuclear physics infrastructure
- **JRC (Joint Research Centre, EU):** Scientific Cooperation Protocol signed
- **Japan:** Joint Committee for science and technology cooperation; High-Power Optics Center partnership
- **NuPECC (Nuclear Physics European Collaboration Committee):** ELI-NP selected as major facility in NuPECC Long Range Plan 2024; NuPECC LRP2024 Town Meeting hosted by IFIN-HH/ELI-NP in Bucharest, April 2024
- **CETAL (INFLPR, Romania):** National laser facility partner for preparatory research
- **TAU Systems:** Commercial company with beam time on ELI-NP 10 PW laser (2024–2025)

---

## I. Key Papers and Documents

### Primary TDR
- **arXiv:2201.01068** — "Laser Driven Nuclear Physics at ELI-NP" (TDR), F. Negoita, M. Roth, P.G. Thirolf, S. Tudisco et al. (56 authors), submitted January 4, 2022. Covers the full scientific case for laser-driven nuclear physics at ELI-NP.

### Gamma Beam System TDR
- **arXiv:1407.3669** — "Technical Design Report: EuroGammaS proposal for the ELI-NP Gamma Beam System" (2014). Authored by Adriani, Albergo et al. Covers full GBS design including linac, ICS geometry, beam parameters.

### HPLS Technical Papers
- **Radier et al., High Power Laser Science and Engineering (2022)** — "10 PW peak power femtosecond laser pulses at ELI-NP" — documents the 10 PW achievement in full
- **Lureau et al.** — earlier HPLS system description paper referenced in the 10 PW paper
- **High Power Laser Science and Engineering** — "High-energy hybrid femtosecond laser system demonstrating 2 × 10 PW capability"

### First Results Paper
- **Ur, C.A., Balabanski, D., Cernăianu, M. et al., European Physical Journal A, vol. 61, article 248 (2025)** — "Extreme Light Infrastructure – Nuclear Physics: first results" — overview of first results obtained with the commissioned laser infrastructure; DOI: 10.1140/epja/s10050-025-01713-3

### Detector / Instrument Papers
- First in-beam experiment with ELIADE: spectroscopic study of ¹³⁰La (ResearchGate, ca. 2021)
- "Implementation of the ELIGANT neutron and gamma detector arrays at ELI-NP" (ResearchGate, 2020; J. Phys. Conf. Ser. 1643, 2020)
- "ELIGANT-GN – ELI Gamma Above Neutron Threshold: The Gamma-Neutron setup" (2021)

### ELI-NP TDR Series (internal TDRs published ~2016 in Romanian Reports in Physics, Vol. 68, Supplement)
Available at eli-np.ro/tdrs.php — 17 chapters covering all subsystems and experiment programs.

### Status and Review Papers
- "Current status and highlights of the ELI-NP research program," Matter and Radiation at Extremes, AIP Publishing (2020), vol. 5, 024402
- "The extreme light infrastructure-nuclear physics (ELI-NP) facility: new horizons in physics with 10 PW ultra-intense lasers and 20 MeV brilliant gamma beams," PubMed/RPOR (2019)
- "Perspectives for photonuclear research at ELI-NP," European Physical Journal A (2015)

### Astrophysics Applications
- "Prospect for measurements of (γ, n) reaction cross-sections of p-nuclei at ELI-NP," Frontiers in Astronomy and Space Sciences (2023)

### Nobel Prize Connection
- CPA (Chirped Pulse Amplification) — the technique enabling all PW lasers — Nobel Prize in Physics 2018 awarded to Gérard Mourou and Donna Strickland; Mourou was a key promoter of ELI

---

## J. Timeline / Commissioning Status Summary

| Date | Event |
|------|-------|
| 2008 Feb | ELI Preparatory Phase launch (Paris, CNRS) |
| 2010 Apr | ELI-DC kick-off meeting (Prague) |
| 2012 Oct | EU structural funds approved: 293.1 M EUR for ELI-NP |
| 2013 Jun | Foundation stone ceremony (Magurele) |
| 2013 Jul | HPLS contract signed with Thales Optronique SAS |
| 2016 Sep | Civil construction of ELI-NP building completed |
| 2018 Oct | Nobel Prize in Physics to Mourou (CPA) |
| 2019 Mar | HPLS demonstrated 10 PW performance (first milestone) |
| 2019 Oct | VEGA/GBS contract signed with Lyncean Technologies (€42M) |
| 2020 Jan | Thales 40-month warranty starts |
| 2020 Aug | 10 PW confirmed through entire system (230 J, 23 fs) |
| 2022 Oct | 10 PW commissioning experimental campaign begins (E1 area) |
| 2022 | 1 PW experimental campaign completed |
| 2023 Jan | arXiv:2201.01068 TDR available |
| 2023 Apr 13 | **First 10 PW on solid target in world** (E1 commissioning) |
| 2023 | Proton energies >100 MeV demonstrated at 10 PW |
| 2023 Jun | Romania accepted as ELI ERIC founding observer |
| 2023 end | 10 PW long-focal-mirror commissioning (E6) begins |
| 2024 Apr | NuPECC LRP2024 Town Meeting hosted at ELI-NP |
| 2024 | 67 weeks of beam time delivered to users (100 TW, 1 PW, 10 PW) |
| 2025 Mar–Dec | Photocathode laser for GBS successfully tested |
| 2025 Jun–Dec | GBS high-power RF stations commissioned |
| 2025 Sep | GBS RF Laboratory implemented |
| 2025 Dec | RI Research Instruments (Bruker) orders for GBS (~€35M) announced |
| 2026 Jan | GBS LINAC Module 5 installed |
| 2026 Feb | **First RF power injected into ELI-GBS Linac** |
| 2026 late | Major RI Research Instruments deliveries expected |
| TBD | GBS first gamma beam delivery (not yet scheduled) |
| TBD | Phase II VEGA storage ring upgrade |

---

## K. Key Numbers Quick Reference

| Parameter | Value |
|-----------|-------|
| HPLS peak power (per arm) | 10 PW |
| HPLS arms | 2 (2 × 10 PW simultaneous possible) |
| HPLS 10PW pulse energy | ~242 J |
| HPLS 10PW pulse duration | < 23 fs |
| HPLS 10PW wavelength | ~810 nm |
| HPLS 10PW repetition rate | 1 shot/min |
| HPLS 10PW intensity contrast | > 10¹² |
| HPLS focused intensity | ~6 × 10²² W/cm² (achieved) |
| HPLS focal spot (E1) | 2.8 μm FWHM |
| Max intensity achievable | ~10²³–10²⁴ W/cm² |
| GBS gamma energy range | 1–19.5 MeV |
| GBS bandwidth | < 0.5% |
| GBS spectral density | > 5 × 10³ photons/s/eV |
| GBS flux | ~10⁸ photons/s |
| GBS peak brilliance | > 10²¹ ph/s/mm²/mrad²/0.1%BW |
| GBS linear polarization | > 95–99% |
| GBS electron beam energy | up to ~720 MeV |
| Max proton energy (commissioning) | >100 MeV (1 PW-class); target >200 MeV at 10 PW |
| Total budget | ~310 M EUR |
| Building area | >33,000 m² |

---

## L. Uncertainties and Gaps

1. **GBS first beam date:** Not yet confirmed; major deliveries from RI Research Instruments expected late 2026, but no confirmed first-beam date for gamma physics experiments.
2. **VEGA storage ring timeline:** The Phase II VEGA upgrade (storage ring + Fabry-Perot cavity) is a longer-term goal; no construction timeline found.
3. **10 PW proton record details:** Reports say >100 MeV protons during commissioning with pre-pulses affecting contrast; the "200+ MeV" goal at full 10 PW contrast is still a commissioning objective.
4. **E6 dual-beam QED experiments:** The E6 area was beginning commissioning with long-focal mirror in late 2023; actual QED experiment results not yet published as of April 2026.
5. **ELISOL status:** Commissioning status of the ELISOL radioactive beam facility not confirmed.
6. **ELI ERIC full membership:** Romania began observer status June 2023; timeline to full membership not publicly finalized.
7. **EuroGammaS re-engagement details:** The exact scope of EuroGammaS involvement in the new GBS construction (alongside RI Research Instruments) is not fully clear.
8. **Marcel Fusion / Thales upgrade:** Details of the commercial fusion research collaboration at ELI-NP (Thales + Marvel Fusion, announced 2022) are not publicly detailed.
9. **Nuclear astrophysics first measurements:** Since GBS is not yet delivering beam, all astrophysics experiments (p-process, r-process, GDR, PDR) are still in the planning/preparation phase.
10. **arXiv:2201.01068 full text:** The full PDF could not be parsed (compressed binary); all content from that document is reconstructed from other sources.

---

## M. Source URLs

- ELI-NP Official Website: https://www.eli-np.ro
- ELI-NP in a Nutshell: https://www.eli-np.ro/eli-np-in-a-nutshell.php
- ELI-NP Milestones: https://www.eli-np.ro/milestones.php
- ELI-NP TDR Series: https://www.eli-np.ro/tdrs.php
- ELI-NP Management: https://www.eli-np.ro/management.php
- ELI-NP Gamma System Dept: https://www.eli-np.ro/gsd.php
- ELI-NP Gamma Driven Experiments Dept: https://www.eli-np.ro/gded.php
- ELI-NP E6 Area: http://www.eli-np.ro/e6.php
- arXiv:2201.01068 (Laser Driven Nuclear Physics TDR): https://arxiv.org/abs/2201.01068
- arXiv:1407.3669 (GBS EuroGammaS TDR): https://arxiv.org/abs/1407.3669
- EPJ A First Results paper (2025): https://link.springer.com/article/10.1140/epja/s10050-025-01713-3
- 10 PW paper (Cambridge Core): https://www.cambridge.org/core/journals/high-power-laser-science-and-engineering/article/10-pw-peak-power-femtosecond-laser-pulses-at-elinp/7F68E8E791BE58DAD69566A9DD53A96B
- ELI ERIC status page: https://www.eli-laser.eu/news/status-of-high-power-laser-system-at-eli-np/
- Wikipedia ELI: https://en.wikipedia.org/wiki/Extreme_Light_Infrastructure
- RI Research Instruments announcement: https://www.businesswire.com/news/home/20251222557179/en/RI-Research-Instruments-Announces-Major-Orders-for-Enabling-Technology-for-the-Gamma-Ray-Source-of-the-Extreme-Light-Infrastructure-ELI
- Laser Focus World visit: https://www.laserfocusworld.com/blogs/article/14184274/visiting-eli-np-which-hosts-the-most-powerful-laser-in-the-world-with-a-power-of-10-pw
- NuPECC LRP 2024 (arXiv:2503.15575): https://arxiv.org/abs/2503.15575
- Thales world record press release: https://www.thalesgroup.com/en/worldwide-market-specific-solutions/lasers/news/new-world-record-thales-lasers-eli-np
- Frontiers p-nuclei paper (2023): https://www.frontiersin.org/journals/astronomy-and-space-sciences/articles/10.3389/fspas.2023.1248834/full
