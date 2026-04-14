---
name: sabre-south-experiment
description: SABRE South dark matter direct-detection experiment knowledge base. Built from 15 InspireHEP papers (2022-2026) + official website + news. Core: testing DAMA/LIBRA annual modulation with NaI(Tl) crystals at SUPL underground laboratory in Australia. Covers detector design, background analysis, muon measurement, PMT calibration, sensitivity projections. Data-taking starts 2026. Trigger words: SABRE South, dark matter direct detection, annual modulation, NaI crystal, SUPL, DAMA/LIBRA, liquid scintillator veto, muon veto.
type: reference
---

# SABRE South Experiment

> The Southern Hemisphere's answer to DAMA/LIBRA: same detector technology, inverted seasonal phase, independent test.

---

## Usage Notes

**Information basis**: 15 InspireHEP papers (2022-2026) + SABRE South official website + phys.org news + centredarkmatter.org
**Confidence**: 5/5 (official TDR + published measurements + current news; information current to April 2026)
**Experiment status**: Data-taking begins 2026 — muon flux confirmed acceptable, detector installation ongoing

---

## Answering Workflow (Agentic Protocol)

### Step 1: Question Classification

| Question type | Action |
|---------------|--------|
| Detector technical parameters | Answer directly from TDR data (arXiv:2411.13889) |
| Experiment status / progress | Combine latest news + papers; note information cutoff date |
| Physics motivation (DAMA/LIBRA) | Explain annual modulation principle + how SABRE tests it |
| Background analysis | Cite specific numbers from simulation paper (arXiv:2205.13849) |
| Muon / cosmic-ray environment | Cite published measurement (arXiv:2603.11981) |
| Sensitivity / discovery potential | Cite TDR sensitivity projections |
| Latest news | Note cutoff April 2026; recommend official wiki for real-time updates |

### Step 2: Data Priority

1. Published measurement values (highest confidence)
2. TDR design parameters (arXiv:2411.13889)
3. Official website / news descriptions
4. Design-based inference (label as "design projection")

---

## Core Physics Motivation

### Why SABRE South?

DAMA/LIBRA at Gran Sasso (Italy) reports an annual modulation signal in NaI(Tl) crystals at 13.7σ significance, claimed as evidence for dark matter. Other experiments (COSINE-100, ANAIS-112) using the same crystal type have not confirmed it.

**The crux of the tension**: competing experiments use crystals with higher radioactive backgrounds, making direct comparison difficult.

**SABRE South's unique value**:
1. **Same technology**: Ultra-pure NaI(Tl) crystals -- a like-for-like comparison with DAMA/LIBRA, eliminating detector-technology bias
2. **Southern Hemisphere**: Annual modulation phase is inverted relative to Italy (Australian summer = Italian winter). A genuine dark matter signal must flip phase; a seasonal systematic background will have a different phase relationship
3. **Lower background**: Crystal purity exceeds DAMA/LIBRA (K concentration 4.3 ppb vs DAMA's 13 ppb)

**Possible outcomes with 2 years of data**:
- Anti-phase modulation observed → supports DAMA/LIBRA dark matter interpretation
- No modulation detected → excludes DAMA-like signal at 3σ
- In-phase modulation → signals a seasonal systematic, not dark matter

### Additional Physics Goals
- Migdal effect dark matter detection (atomic ionisation from nuclear recoil)
- Bosonic super-WIMPs (sub-GeV dark matter)
- Supernova neutrino detection

---

## Complete Detector Technical Specifications

### NaI(Tl) Crystal System

| Parameter | Value | Source |
|-----------|-------|--------|
| Number of crystals | 7 | TDR |
| Total active mass | 35 kg (RMD scenario) or 50 kg (SICCAS scenario) | TDR |
| Individual crystal mass | 5 kg (RMD) or 7 kg (SICCAS) | TDR |
| Crystal vendors | Radiation Monitoring Devices (RMD, USA) or SICCAS (China) | TDR |
| Raw material | Merck Astrograde NaI powder, K < 10 ppb | TDR |
| Measured K concentration | 4.3 ppb (natK) | TDR |
| 210Pb concentration | 0.34 mBq/kg | TDR |
| Light yield | ~12-14 photoelectrons/keV | TDR |
| Crystal PMT model | Hamamatsu R11065-20 (76 mm diameter, QE >= 30%) | JINST 2025 |
| PMTs per crystal | 2 | TDR |
| Crystal enclosure | Oxygen-free copper with continuous N2 flushing | TDR |
| Energy threshold (target) | ~1 keVee | TDR |

**Crystal radiopurity comparison** (natK in ppb):

| Experiment | natK (ppb) | 210Pb (mBq/kg) |
|------------|------------|----------------|
| **SABRE South** | **4.3** | **0.34** |
| DAMA/LIBRA | 13 | ~5-30 x 10^-3 |
| COSINE-100 | 35.1 | 1.74 |
| ANAIS-112 | 31 | 1.53 |

### Active Background Rejection (Veto Systems)

**Liquid Scintillator (LS) Veto**:
- Total volume: ~11,600 litres
- Composition: linear alkylbenzene (LAB) + PPO (3.5 g/L) + bis-MSB (15 mg/L)
- PMT model: Hamamatsu R5912 (204 mm diameter)
- Number of PMTs: 18-32
- Performance: 40K background reduced by ~10x; total background suppressed by 27%
- Physics mechanism: In 40K beta+gamma decay, the gamma can escape the crystal but the beta is captured by the LS, enabling coincidence rejection

**Muon Veto**:
- Detector: 8 EJ200 plastic scintillator panels (3 m x 0.4 m x 0.05 m each)
- PMT configuration: dual Hamamatsu R13089 PMTs per panel (one each end)
- Layout: two orthogonal layers (simultaneous flux and angular measurement)
- Function: tag cosmic muon-induced secondary particle events

### Passive Shielding

**Total: 112 tonnes**, layered from inside out:
```
NaI crystals
  -> 8 cm inner steel
  -> 10 cm high-density polyethylene (HDPE, neutron moderation)
  -> 8 cm outer steel
  -> LS Veto (~11,600 L)
  -> Muon Veto (above)
```

External gamma background after shielding: ~10^-4 cpd/kg/keVee

### Data Acquisition System (DAQ)

- 3 independent CAEN digitiser instances: V1730 (crystals) / V2730 (LS veto) / V1743 (muon veto)
- Custom C++ acquisition software + EPICS slow control
- Environmental monitoring: 20+ sensors (temperature, humidity, radon, etc.)
- Machine learning: boosted decision tree (BDT) classifier for noise discrimination in 1-2 keVee range

---

## SUPL Underground Laboratory Environment

### Key Parameters

| Parameter | Value |
|-----------|-------|
| Location | Stawell Gold Mine, Victoria, Australia |
| Depth | 1,025 m |
| Water-equivalent depth | 2,900 mwe |
| Muon flux (measured) | (6.33 +/- 0.04_stat +/- 0.35_sys) x 10^-8 s^-1 cm^-2 |
| Rock radon activity | 415 +/- 5 Bq/m^3 |
| Clean tent radon (measured) | ~12 Bq/m^3 (2025 commissioning test) |
| Laboratory opening | August 2022 |

**Muon flux measurement (arXiv:2603.11981, Astropart. Phys. 2026)**:
- Method: 8 EJ200 panels in telescope mode; geometric mean of dual-PMT charges eliminates position-dependent light attenuation
- Data period: April 2024 - March 2025 (~236 days)
- Single-panel detection efficiency: (99.42 +/- 0.03_stat +/- 0.23_sys)%
- Key result: experimental uncertainty is ~1 order of magnitude smaller than overburden simulation uncertainty
- Significance: SUPL confirmed at comparable shielding level to Boulby (UK, 2,850 mwe) and LNGS (Italy, 3,800 mwe)

---

## Background Analysis

### Total Background Target

**0.72 cpd/kg/keVee** in the 1-6 keV region of interest (ROI)

For comparison: DAMA/LIBRA background ~0.8 cpd/kg/keVee

### Background Source Breakdown (arXiv:2205.13849)

| Source | Level | Mitigation |
|--------|-------|------------|
| 40K in crystals (dominant) | Dominates ROI | LS Veto coincidence (~10x reduction) |
| U/Th decay chains in crystal | Low-energy contribution | Ultra-purification of raw material |
| External gamma (rock / shielding) | ~10^-4 cpd/kg/keVee (post-shielding) | Multi-layer passive shielding |
| Surface alpha contamination | High-energy region | Cu enclosure + N2 purge |
| Muon-induced neutrons | Rare | Muon Veto time coincidence |
| 210Pb-210Bi chain | Low-energy contribution | Raw material pre-purification |

### Background Measurement Philosophy

The SABRE South approach: **measure and characterise every background source before claiming sensitivity to a dark matter signal**. The muon flux measurement (arXiv:2603.11981), the PMT characterisation papers, and the background simulation (arXiv:2205.13849) all represent this philosophy in action -- each quantifies one node in the background chain with experimental uncertainty smaller than the theoretical model uncertainty.

---

## Sensitivity Projections

**Conditions**: 50 kg target mass + 0.72 cpd/kg/keVee background + 2 years of data

| Target | Sensitivity |
|--------|-------------|
| Discovery of DAMA-like signal | 5 sigma |
| Exclusion of DAMA-like signal | 3 sigma |
| Reference signal amplitude | ~0.0119 cpd/kg/keV (DAMA/LIBRA measured value) |

---

## Experiment Timeline

| Date | Milestone |
|------|-----------|
| August 2022 | SUPL officially opened |
| October 2023 | Equipment installation commenced |
| January 2024 | First equipment installed underground; muon veto operational in telescope mode |
| April 2024 | Muon flux data collection begins |
| April 2025 | TDR Executive Summary published (JINST 20, T04001) |
| August 2025 | Crystal Insertion System frame and glovebox delivered to SUPL |
| January 2026 | Clean tent operational (radon ~12 Bq/m^3); PMT testing complete; 7 kg test crystal received |
| April 2026 | Muon flux confirmed meets requirements (arXiv:2603.11981); full data-taking expected later in 2026 |
| 2026 (projected) | Full detector data collection begins |

---

## Collaboration Members and Institutions

### Leadership
- **Elisabetta Barberio** (University of Melbourne; Director, ARC Centre of Excellence for Dark Matter Particle Physics; PI)
- **Phillip Urquijo** (University of Melbourne; co-PI)

### Member Institutions
- **Australia**: University of Melbourne (lead), Australian National University (ANU), Swinburne University of Technology, University of Adelaide, University of Sydney
- **Italy**: INFN Milan
- **Japan**: KEK
- **USA**: Radiation Monitoring Devices / RMD (crystal production)
- **China**: SICCAS (crystal production)

### Key Personnel (identified from publications)
- **L.J. Milligan** (Melbourne; ICHEP2024 and TIPP2023 spokesperson)
- **G. Fu / Guangyong Fu** (Melbourne PhD candidate; first author, muon flux measurement, arXiv:2603.11981)
- **O. Stanley** (first author, R11065-20 PMT characterisation, arXiv:2504.17209)
- **R.S. James** (signal acceptance and energy calibration)
- **L.J. McKie** (ANU; DAQ and trigger system)
- **K.J. Rule** (Melbourne; EPS-HEP2025 spokesperson)
- **I. Bolognino** (INFN Milan / University of Adelaide; QCHSC24 spokesperson)
- **A.E. Stuchbery** (ANU)
- **G.J. Lane** (ANU)
- **B. Suerfu** (crystals / simulation)

---

## SABRE International Context

SABRE (Sodium Iodide with Active Background REjection) is a two-site experiment:
- **SABRE South** (SUPL, Australia) -- this skill's primary subject
- **SABRE North** (LNGS, Gran Sasso, Italy) -- Northern Hemisphere counterpart; phase comparison is scientifically essential

**SABRE Proof-of-Principle (PoP, completed)**: Small prototype operated at LNGS, demonstrating the NaI crystal ultra-purification scheme and liquid scintillator veto concept before full-scale construction.

**Scientific value of dual-site operation**: A genuine dark matter annual modulation must appear with a 6-month phase difference between the two sites. Seasonal systematics (temperature, pressure, cosmic-ray seasonal variation) have a different phase relationship at each site, enabling discrimination.

---

## Key Physics Questions: Quick Reference

**What is annual modulation?**
As Earth orbits the Sun, the dark matter "wind" velocity relative to Earth changes over the year, causing the dark matter-nucleus recoil event rate to oscillate with ~1-3% annual amplitude. The peak occurs around June 2, when Earth's velocity adds constructively to the Sun's velocity through the Milky Way's dark matter halo. DAMA/LIBRA observes a sinusoidal modulation in the 2-6 keV region with amplitude ~0.012 cpd/kg/keV.

**Why does the Southern Hemisphere distinguish signal from background?**
- Genuine dark matter modulation: 180-degree phase difference between Australia and Italy
- Seasonal backgrounds (temperature, muon seasonal variation): also 180-degree phase difference, but with a different amplitude and energy dependence
- Cosmic-ray seasonal modulation: predominantly above 6 keV, small contribution in the ROI

**Why NaI(Tl)?**
- Direct comparison with DAMA/LIBRA uses identical detector technology, eliminating instrumental systematics
- Both Na and I have significant scattering cross-sections for ~10 GeV dark matter
- The Migdal effect is more prominent on lighter nuclei (Na) than heavy targets like Xe or Ge

**How good is SUPL's muon shielding?**
2,900 mwe equivalent depth suppresses the muon flux to (6.33 +/- 0.35) x 10^-8 s^-1 cm^-2, roughly 5 orders of magnitude below the surface flux. This is comparable to Boulby (UK, 2,850 mwe) and within a factor 1.3 of Gran Sasso (3,800 mwe).

---

## Sources

| Source | Type | Confidence |
|--------|------|------------|
| arXiv:2603.11981 (muon flux, Astropart. Phys. 2026) | Published measurement | Highest |
| arXiv:2411.13889 (TDR, JINST 20 T04001, 2025) | Official design document | Highest |
| arXiv:2205.13849 (background simulation, EPJC 2023) | Published analysis | Highest |
| arXiv:2504.17209 (PMT characterisation, JINST 2025) | Published instrumentation | Highest |
| arXiv:2511.16451 (ICHEP2024 overview, 2025) | Conference paper | High |
| sabre-experiment.org.au | Official website | High |
| centredarkmatter.org news | Official news | High |
| phys.org report (April 2026) | Secondary media | Medium-high |

**Information cutoff**: 14 April 2026
**Real-time updates**: https://darkmatteraustralia.atlassian.net/wiki/spaces/SABREPUBLIC/overview

---

> This Skill was built from public academic papers and official websites.
> Created with [Nuwa Skill Creator](https://github.com/alchaincyf/nuwa-skill) by [AlchainHust](https://x.com/AlchainHust)
