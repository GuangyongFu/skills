---
name: n14-explosive-detection
description: Knowledge base for explosive detection via Nuclear Resonance Absorption (NRA) of gamma rays in ¹⁴N at 9.17 MeV. Anchored on LIU Fulong et al. (Atomic Energy Science and Technology, 2022) proof-of-principle at Beijing Normal University (BNU) Tandem Accelerator. Covers: physics of ¹³C(p,γ)¹⁴N → 9.17 MeV source, ¹⁴N(γ,p)¹³C absorption detection principle, Soreq/LANL/TRIUMF/BNU development history, competing nuclear techniques (PGNAA, NRF, TNA, FNA, NQR), current research groups, open challenges. Trigger words: N14 explosive detection, nuclear resonance absorption, NRA gamma, 9.17 MeV gamma explosive, nitrogen detection, cargo container inspection, 13C(p,gamma)14N, melamine absorber, Beijing Normal University explosive.
type: reference
---

# ¹⁴N Nuclear Resonance Absorption — Explosive Detection

> Explosives hide nitrogen. Nitrogen absorbs a very specific gamma ray. Build a 9.17 MeV source and you have a cargo scanner that sees what X-rays miss.

---

## Usage Notes

**Anchor paper**: LIU Fulong et al., "Proof-of-Principle Study of Explosive Detection Based on Nuclear Resonance Absorption", *Atomic Energy Science and Technology*, Vol. 56, No. 1, pp. 258–264 (2022). DOI: 10.7538/yzk.2022.youxian.0159
**Information basis**: 13 direct references of anchor paper + broader NRA/nuclear detection field literature
**Confidence**: 4/5 — physics firmly established; current BNU program status requires live search for latest
**Information current to**: April 2026
**Field status**: Mature physics, active renewed interest due to cargo security demands; BNU group leading China effort

---

## Answering Workflow (Agentic Protocol)

### Step 1: Question Classification

| Question type | Action |
|---------------|--------|
| Physics of 9.17 MeV resonance | Answer directly: ¹³C(p,γ)¹⁴N → ¹⁴N(γ,p)¹³C inverse, resonance parameters |
| Anchor paper experiment | Give BNU setup, melamine absorber results, detection limit |
| How NRA compares to neutron methods | Compare NRA vs PGNAA/TNA/FNA/NRF (table below) |
| History / who developed NRA | Soreq (Vartsky/Goldberg) → LANL → TRIUMF → BNU timeline |
| Detection limits / sensitivity | 23 g/cm² concentrated N (BNU 2022); prior LANL/Soreq system data |
| Current open challenges | Gamma source intensity, scanning speed, detector efficiency |
| Future directions | Laser-Compton backscattering, linac sources, detector upgrades |
| Latest papers from BNU group | Note April 2026 cutoff; recommend searching CNKI / AEST journal |

### Step 2: Data Priority

1. Anchor paper experimental data (highest confidence)
2. Direct references cited by the anchor paper
3. Soreq/LANL/TRIUMF published NRA literature
4. Field-wide review papers
5. Inference from physics (label as "expected from first principles")

---

## Core Physics

### The Detection Principle

Explosives (TNT, RDX, HMX, PETN, TATP, etc.) contain nitrogen at densities of **20–40 g/L**, while most civilian cargo materials contain <5 g/L. Nuclear Resonance Absorption (NRA) exploits this:

1. **Gamma source**: Produce monoenergetic 9.17 MeV photons using the ¹³C(p,γ)¹⁴N resonant reaction
2. **Transmission scan**: Pass the beam through suspect cargo
3. **Resonant absorption**: When the 9.17 MeV photons encounter ¹⁴N, they are resonantly absorbed via the inverse ¹⁴N(γ,p)¹³C reaction
4. **Detection**: A nitrogen-rich region shows as a transmission deficit → explosive candidate

### The 9.17 MeV Resonance in ¹⁴N

| Parameter | Value | Reference |
|-----------|-------|-----------|
| Level energy (Ex) | 9.17 MeV | Vartsky & Goldberg, Nucl. Phys. A 505 (1989) |
| Level width (Γ) | ~122 eV | Vartsky & Goldberg 1989 |
| Peak cross-section | ~200 mb | Literature |
| Energy-integrated cross-section | ~4 b·eV | Literature |
| Inverse reaction | ¹⁴N(γ,p)¹³C | — |
| Source reaction | ¹³C(p,γ)¹⁴N at Ep = 1.75 MeV | DANG Yongle et al., CPB 2019 |

**Key advantages of the 9.17 MeV resonance**:
- Very narrow (122 eV) → high selectivity; few other materials absorb at this exact energy
- Large integrated cross-section → measurable attenuation with achievable source intensity
- Uniqueness to ¹⁴N → no false positives from common packaging materials (C, O, H, Al, Fe)
- High penetration of 9.17 MeV photons → can scan through steel containers

### Source Production: ¹³C(p,γ)¹⁴N

The gamma source is produced by the **inverse resonant reaction** at the same compound nucleus level:

- Beam: protons at Ep = **1.75 MeV** (lab frame)
- Target: ¹³C (isotopically enriched carbon-13 target)
- Output: 9.17 MeV γ-ray isotropically + lower-energy cascade gammas
- Yield: characterized by DANG Yongle et al. (Chinese Physics B, 2019, 28(6))

**Principal technical challenge**: Generating high enough 9.17 MeV photon flux for practical scan times. This determines the accelerator current, target design, and shielding requirements.

---

## The BNU Proof-of-Principle Experiment (2022)

### Authors and Affiliations

LIU Fulong, WANG Haoran, BO Nan, DANG Yongle, FU Guangyong, WU Di, HE Hongyu, HE Chuangye, GUO Bing, WANG Naiyan

*Beijing Normal University (BNU), China*

### Experimental Setup

| Component | Details |
|-----------|---------|
| Accelerator | 2.5 MV Tandem Accelerator, Beijing Normal University |
| Beam | Protons, Ep = 1.75 MeV |
| Gamma source target | ¹³C-enriched target (resonant reaction) |
| Mock explosive (absorber) | Boxed melamine samples (high N concentration, C₃H₆N₆) |
| Control material | Graphite rod (non-concentrated nitrogen) |
| Detector | (gamma detector downstream of absorber stack) |

**Why melamine?** Melamine (C₃H₆N₆) has ~66.6% nitrogen by mass — much higher than real explosives but ideal for proof-of-principle. Produces a strong, measurable NRA signal.

### Key Results

| Absorber | Observation |
|----------|------------|
| Increasing melamine thickness | Progressive, increasing absorption signature |
| Graphite (control) | No comparable absorption effect |
| Detection limit achieved | **23 g/cm² of concentrated nitrogen** |

**Main conclusions**:
1. Thicker nitrogen-rich absorber → more distinctive absorption effect (as expected)
2. Nitrogen-specific: graphite shows negligible effect, confirming selectivity
3. 23 g/cm² detection limit demonstrates feasibility; real explosive quantities in aviation cargo typically exceed this threshold

**Significance**: First proof-of-principle demonstration of the NRA method on a Chinese accelerator facility; establishes BNU as a research node for this technology.

---

## Historical Development

### Timeline

| Year | Event | Group |
|------|-------|-------|
| 1986 | FAA proposal: NRA for baggage inspection | Vartsky, Goldberg et al. (Soreq NRC, Israel) |
| 1988 | Israeli Patent IL-86826 filed | Soreq |
| 1989 | US Patent 4,941,162 | Soreq |
| 1989 | Total width of 9.17 MeV level in ¹⁴N measured | Vartsky & Goldberg, Nucl. Phys. A 505:328 |
| 1991 | FAA progress report: NRA detection system | Vartsky et al., FAA Report |
| 1993 | First prototype explosives detection system (NRA) | Soreq + US partners |
| 1994 | Key NIM paper: method for detection of explosives via NRA in ¹⁴N | Vartsky et al., NIM A 348:688 |
| 1997 | GRA images demonstrated at TRIUMF on aviation cargo | TRIUMF, Canada |
| 2000s | LANL NRA cargo container work | LANL (Kwan, Morgado, Wang) |
| 2008 | Book chapter: detection with NRA gamma-rays | Kwan, Morgado, Wang (Springer) |
| 2009 | Monoenergetic gamma-ray NRA system | NIM A paper |
| 2011 | High-spatial-resolution resonant-response detector | Brandis et al., JINST 6:P02008 |
| 2019 | Thick target yield for ¹³C(p,γ)¹⁴N at 9.17 MeV | DANG Yongle et al., CPB 28(6) |
| 2022 | BNU proof-of-principle: 23 g/cm² N detection limit | LIU Fulong et al., AEST 56(1):258 |

### Three Historical Centers

| Institution | Country | Key contribution |
|-------------|---------|----------------|
| Soreq NRC | Israel | Concept, first prototype, patents, resonance width measurement |
| LANL | USA | Cargo container feasibility, source development |
| TRIUMF / NRCC | Canada | Aviation cargo imaging demonstrations |
| Beijing Normal University | China | Renewed development, ¹³C(p,γ) yield characterization, proof-of-principle (2019–2022) |

---

## Competing Nuclear Detection Techniques

| Method | Particle probe | Detection signature | Explosives ID | Penetration | Speed | Maturity |
|--------|---------------|---------------------|--------------|-------------|-------|---------|
| **γ-NRA** (this work) | 9.17 MeV γ (monoenergetic) | N transmission deficit | Nitrogen-based only | High (MeV γ) | Slow (scan) | Lab demo |
| **NRF** | Broad-band MeV γ | Element-specific resonance fluorescence | C/N/O isotopes | High | Slow | Research |
| **PGNAA** | Thermal neutrons | Characteristic capture γ spectrum | N, C, H, O, Cl | Moderate | Moderate | Deployed |
| **TNA** | Thermal neutrons | N(n,γ) 10.8 MeV γ | Nitrogen-based | Moderate | Fast | Deployed |
| **FNA / PFNA** | Fast neutrons (14 MeV) | Inelastic γ from C, N, O | C/N/O ratio | High | Moderate | Operational |
| **API** (Associated Particle) | Tagged 14 MeV neutrons | 3D C/N/O mapping | C/N/O ratio | Moderate | Slow | Research |
| **NQR** | RF (radio frequency) | ¹⁴N quadrupole resonance | Specific N compounds | Low | Moderate | Commercial |
| **X-ray CT** | X-rays | Density + Z | Density-based | High | Fast | Widely deployed |
| **Neutron radiography** | Fast/thermal neutrons | H contrast | H-rich material | Moderate | Moderate | Operational |

**NRA vs PGNAA key difference**: NRA is a *transmission* method (absorption of a monoenergetic beam) while PGNAA is an *activation* method (neutrons produce gammas). NRA is uniquely selective for nitrogen due to the narrow 9.17 MeV resonance; PGNAA detects multiple elements simultaneously.

**NRA vs NRF key difference**: Both use MeV photons. NRA uses a *monoenergetic* source matched to a specific nuclear level; NRF uses a *broad-band* bremsstrahlung source and detects the re-emitted fluorescence photons. NRF can identify multiple elements/isotopes; NRA is single-element (nitrogen) but conceptually simpler.

---

## Full Reference List of the Anchor Paper

1. XIE Tao, LI Li. Problems of customs container supervision; lessons from US experience. *Journal of Customs and Trade*, 2017, 3(6): 25–33, 73.

2. LAI Wenguang. Review of China's port production in 2017 and outlook 2018. *China Ports*, 2018, 33(2): 13–19.

3. WANG Liming. Review of conventional explosives detection using active neutron interrogation. *Journal of Radioanalytical and Nuclear Chemistry*, 2014, 301(3): 629–639.

4. RUNKLE R C, WHITE T A, MILLER E A, et al. Photon and neutron interrogation techniques for chemical explosives detection in air cargo. *Nuclear Instruments and Methods in Physics Research A*, 2009, 603(3): 510–528.

5. VALKOVIC V, SUDAC D, NAD K, et al. Container inspection utilizing 14 MeV neutrons. *IEEE Transactions on Nuclear Science*, 2016, 63(3): 1536–1543.

6. WU Zhifang, DONG Tao. Development and trend of radiation imaging technology for large objects. *Atomic Energy Science and Technology*, 2019, 53(10): 2062–2071.

7. DANG Yongle, et al. Measurement of thick target yield for narrow resonance at EX = 9.17 MeV in the ¹³C(p,γ)¹⁴N reaction. *Chinese Physics B*, 2019, 28(6): 131–134. ← **Key enabling paper for the BNU program**

8. VARTSKY D, GOLDBERG M B, ENGLER G, et al. A detection system for explosives in passenger baggage based on nuclear resonance absorption in ¹⁴N. *Progress Report to FAA*, 1991.

9. KWAN T J T, MORGADO R E, WANG T S F, et al. Detection of explosives using nuclear resonance absorption of gamma rays in nitrogen. In: *Detection of Liquid Explosives and Flammable Agents in Connection with Terrorism*. Dordrecht: Springer, 2008: 97–116.

10. VARTSKY D, GOLDBERG M B, et al. An explosives detection system for passenger baggage based on nuclear resonance absorption in ¹⁴N. *Proposal to FAA*, 1986.

11. VARTSKY D, ENGLER G, GOLDBERG M B. A method for detection of explosives based on nuclear resonance absorption of gamma rays in ¹⁴N. *Nuclear Instruments and Methods in Physics Research*, 1994, 348(2–3): 688–691. ← **Foundational NRA paper**

12. BRANDIS M, GOLDBERG M B, VARTSKY D, et al. Proof of principle of a high-spatial-resolution, resonant-response γ-ray detector for gamma resonance absorption in ¹⁴N. *Journal of Instrumentation*, 2011, 6(2): P02008.

13. VARTSKY D, GOLDBERG M B. The total width of the 9.17 MeV level in ¹⁴N. *Nuclear Physics A*, 1989, 505(2): 328–336. ← **Nuclear data foundation**

---

## Open Technical Challenges

### 1. Source Intensity (Critical Bottleneck)

The 9.17 MeV photon yield from ¹³C(p,γ)¹⁴N is limited by:
- ¹³C target heat load (beam current limited by target survival)
- Resonance strength (narrow width means low yield per proton)
- Accelerator current capability

**Practical implication**: Scanning a full cargo container in acceptable time (<5 min) requires orders-of-magnitude more flux than current lab setups provide.

**Possible solutions being explored**:
- High-current Tandem accelerators or linacs
- Laser-Compton backscattering (LCS) as an alternative gamma source tunable to 9.17 MeV
- Laser-driven bremsstrahlung sources (relevant to the BNU group's broader laser-nuclear program)
- Thick ¹³C targets with active cooling

### 2. Detector Technology

Resonant-response detectors (nitrogen-rich liquid scintillators, e.g., dimethyl-tetrazole) offer higher detection efficiency by also resonantly absorbing the 9.17 MeV gammas. Challenges:
- Safety of nitrogen-rich organic detector liquids
- Position resolution for imaging (Brandis 2011 addressed this)
- Competition with conventional NaI/LaBr₃ detectors

### 3. Imaging vs. Bulk Detection

Current demonstrations measure integrated nitrogen along a column. True 2D/3D imaging of hidden explosives requires:
- Scanning beam + position-sensitive detector array
- CT-like reconstruction
- Discrimination between distributed nitrogen (background amino-acids, fertilizers) vs. dense concentrated nitrogen (explosive)

### 4. False Positives

Other nitrogen-rich materials: fertilizers (urea, ammonium nitrate), amino acids, nylon, polyamides, food products. Requires:
- Density threshold calibration
- Combination with other modalities (X-ray density, neutron H mapping)

### 5. Radiation Dose

9.17 MeV photons are penetrating and can activate materials. Regulatory limits on dose to cargo and nearby personnel constrain dwell time and beam intensity.

---

## Key Physical Parameters for System Design

| Parameter | Value | Notes |
|-----------|-------|-------|
| Source reaction | ¹³C(p,γ)¹⁴N | Ep = 1.75 MeV (lab) |
| Detection reaction | ¹⁴N(γ,p)¹³C | Inverse reaction |
| Resonance energy | 9.17 MeV | In ¹⁴N nucleus |
| Resonance width | ~122 eV | Full width at half maximum |
| Peak cross-section | ~200 mb | |
| Integrated cross-section | ~4 b·eV | |
| BNU detection limit | 23 g/cm² N (concentrated) | LIU Fulong et al. 2022 |
| Typical explosive N density | 20–40 g/L | TNT: ~18.5%, RDX: ~37.8% |
| BNU accelerator | 2.5 MV Tandem | Beijing Normal University |
| BNU beam energy | 1.75 MeV protons | At resonance |
| Mock explosive used | Melamine (C₃H₆N₆) | 66.6% N by mass |

---

## Research Groups and Institutions

| Group | Location | Focus | Active period |
|-------|----------|-------|---------------|
| Soreq NRC (Vartsky, Goldberg) | Israel | NRA concept, detector, resonance data | 1986–2000s |
| LANL (Kwan, Morgado, Wang) | USA | Cargo container application | 1990s–2000s |
| TRIUMF | Canada | Aviation cargo imaging | 1990s–2000s |
| **Beijing Normal University** | China | Source yield characterization + proof-of-principle | 2019–present |

**BNU core team** (from anchor paper): LIU Fulong, WANG Haoran, BO Nan, DANG Yongle, FU Guangyong, WU Di, HE Hongyu, HE Chuangye, GUO Bing, WANG Naiyan

---

## Related Nuclear Techniques Cited in the Field

### Prompt Gamma Neutron Activation Analysis (PGNAA)

Neutrons (from ²⁵²Cf, D-T generator, or reactor) irradiate cargo; nuclei capture neutrons and emit characteristic prompt gammas. Can detect N (10.8 MeV), H (2.2 MeV), C, O, Cl simultaneously. Widely used in luggage/cargo security (PGNAA luggage systems: minimum detectable mass ~200 g explosive in 60 s).

### Fast Neutron Interrogation (FNA/PFNA)

14 MeV D-T neutrons probe C, N, O by inelastic scattering. Container inspection with 14 MeV neutrons demonstrated by VALKOVIC et al. (IEEE TNS 2016, Ref. 5). Higher penetration than thermal neutrons; gives elemental ratios for explosive vs. background discrimination.

### Nuclear Resonance Fluorescence (NRF)

Broad-band bremsstrahlung photons (2–8 MeV) from linac excite specific nuclear levels; fluorescence photons re-emitted. Can identify ¹²C, ¹⁴N, ¹⁶O isotopic ratios simultaneously. Higher information content than NRA but more complex source and analysis. Currently developed for non-proliferation (nuclear material detection) with secondary explosive detection application.

---

## Context: China Cargo Security

References 1–2 and 6 of the anchor paper situate the work in the context of Chinese port and customs security:
- China handles the world's largest container throughput (hundreds of millions TEUs/year)
- Current primary technology: X-ray / radiation imaging for large objects (WU & DONG 2019 review, Ref. 6)
- Conventional X-ray detects density anomalies but cannot identify nitrogen-rich explosives with certainty
- NRA addresses the specific gap: chemical specificity for nitrogen in high-throughput cargo

---

## Future Directions

1. **Higher-flux sources**: Linac-based or laser-Compton backscattering (LCS) gamma sources at 9.17 MeV would enable practical scan speeds. The BNU group's expertise in laser-nuclear physics (see tian-baoxian-perspective and liu-fulong-perspective skills) is directly relevant here.

2. **Laser-driven gamma for NRA**: Laser bremsstrahlung from high-Z targets produces broad-spectrum photons that can be spectrally filtered or a resonance-tunable LCS source built. This bridges the BNU group's laser-plasma program with the explosive detection work.

3. **Combined modalities**: NRA (nitrogen) + fast neutron H-mapping + X-ray density → three-layer composite signal for high confidence explosive identification.

4. **Portable systems**: Replace fixed Tandem accelerator with compact neutron generator (for PGNAA) or compact linac/cyclotron for NRA applications at border checkpoints.

5. **AI/ML image analysis**: Neural network analysis of NRA transmission profiles to distinguish explosive from nitrogen-containing benign cargo (fertilizers, food).

---

## Live Citation Search

To find papers citing the anchor paper:
- **Google Scholar**: Search `"10.7538/yzk.2022.youxian.0159"` or `"LIU Fulong" "nuclear resonance absorption" explosive`
- **CNKI** (China National Knowledge Infrastructure): Search the journal "原子能科学技术" (Atomic Energy Science and Technology) for citing works
- **Web of Science**: May index the AEST journal; search by DOI

---

*Knowledge base built April 2026. Anchor paper: DOI 10.7538/yzk.2022.youxian.0159 (LIU Fulong et al., 2022).*
