# ElectroNet Research Methodology

## Comprehensive Methods for Microplastic Removal via Electrocoagulation

**Project Period:** November 15 - December 26, 2025
**Testing Date:** December 15, 2025
**Testing Location:** Universiti Sains Malaysia, Kampus Kejuruteraan

---

## 1. Research Overview

### 1.1 Objective
To develop and validate an electrocoagulation-based system (ElectroNet) for removing polyvinyl chloride (PVC) microplastics from water through particle aggregation, as measured by changes in particle size distribution and surface charge (zeta potential).

### 1.2 Hypothesis
Electromagnetic fields applied through electrocoagulation will induce aggregation of suspended PVC microplastics, resulting in:
- Increased particle size (facilitating mechanical filtration)
- Reduced zeta potential (indicating surface charge neutralization)
- Improved water quality metrics

### 1.3 Experimental Approach
The study employed a comparative before-and-after experimental design, with multiple water matrices tested to evaluate the ElectroNet system's performance under varied conditions. Validation was conducted using advanced analytical techniques at Universiti Sains Malaysia's engineering laboratories.

---

## 2. Sample Preparation

### 2.1 Water Sample Types
Five distinct water samples were prepared to evaluate the ElectroNet system across different contamination scenarios:

| Sample ID | Description | Purpose |
|-----------|-------------|---------|
| Sample 1 | Sterilized water | Negative control (baseline) |
| Sample 2 | School pipe water | Real-world urban water matrix |
| Sample 3 | Reverse Osmosis (RO) water | Purified water matrix control |
| Sample 4 | PVC-contaminated water | Primary test sample for microplastic removal |
| Sample 5 | Water with facial cleanser | Secondary microplastic source (cosmetic contamination) |

### 2.2 PVC Microplastic Preparation (Sample 4)
**Method:** Mechanical abrasion of PVC pipe material
- **Source material:** PVC pipe
- **Preparation technique:** Manual sanding using sandpaper to generate microplastic particles
- **Quantity:** Sufficient amount added to achieve visible suspension in water
- **Water matrix:** 250 mL sample volume per bottle
- **Note:** Exact particle concentration and size distribution prior to treatment were not quantified during preparation but were characterized post-treatment via Dynamic Light Scattering (DLS) analysis

### 2.3 Facial Cleanser Sample (Sample 5)
**Method:** Direct addition of commercial facial cleanser containing microbeads
- **Product type:** Commercial facial cleanser (brand not specified)
- **Quantity:** Sufficient amount to create microplastic suspension
- **Water matrix:** 250 mL sample volume per bottle

### 2.4 Sample Containers and Storage
- **Container type:** Glass bottles (250 mL capacity)
- **Replication:** One bottle prepared per sample type
- **Labeling:** Samples labeled for tracking through treatment and analysis
  - **B01:** PVC-contaminated water (before treatment)
  - **B04:** PVC-contaminated water (after electrocoagulation treatment)

---

## 3. ElectroNet Prototype Specifications

### 3.1 System Design Philosophy
The ElectroNet device utilizes electrocoagulation principles to destabilize colloidal suspensions of microplastics through electrochemical processes, inducing particle aggregation via:
- Charge neutralization at the particle-water interface
- Sweep flocculation through hydroxide precipitation
- Electrostatic attraction between charged species

### 3.2 Electrode Configuration

**Material Selection Process:**
1. **Initial Design:** Steel electrodes
   - **Observation:** Significant corrosion during operation
   - **Decision:** Material change required

2. **Final Design:** Graphite electrodes
   - **Material:** Graphite rods/plates
   - **Rationale:** Superior corrosion resistance, electrical conductivity
   - **Observed limitation:** Minor graphite particulate leaching into treated water
   - **Assumption:** Graphite particles do not interfere with PVC detection in analytical methods (FTIR spectroscopic fingerprints are distinct; DLS measures size distribution regardless of particle composition)

### 3.3 Electrical Parameters
- **Applied voltage:** 9 V DC
- **Current type:** Direct current (DC)
- **Power source:** battery

### 3.4 Operational Configuration
- **Treatment volume:** Approximately 250 mL per sample
- **Treatment duration:** 60 minutes
- **Temperature:** Ambient laboratory temperature (~25°C, uncontrolled)

---

## 4. Electrocoagulation Treatment Protocol

### 4.1 Pre-Treatment Preparation
1. Sample bottles prepared as described in Section 2
2. Prototype system checked for electrode integrity and electrical connections
3. Initial water sample characteristics documented

### 4.2 Treatment Procedure

1. Pre-treatment sample collection (B01)
2. Transfer of water sample to ElectroNet treatment chamber
3. Application of 9V potential across graphite electrodes
4. Treatment for 60 minutes
5. Power disconnection
6. Post-treatment settling period: 60 minutes
7. Sample collection for analysis (B04)

### 4.3 Post-Treatment Processing

**Particle Separation Method:**
- **Separation technique:** membrane filtration
- **Filter specifications:** Pore size <0.05mm
- **Filtration duration:** 60 minutes

---

## 5. Analytical Methods - USM Laboratory Testing

Testing conducted on **December 15, 2025** at Universiti Sains Malaysia, Kampus Kejuruteraan, under the supervision of:
- **Dr. Mohamad Danial Shafiq** (Professor, Pusat Pengajian Kejuruteraan Awam)
- **Nik Nur Azreen Binti Nik Fauzi** (Master's Student)
- **Amir Muhammad Noh Amin Bin Abdul Rahman** (PhD Student)

*Fakulti Kejuruteraan Bahan & Sumber Mineral*

### 5.1 Dynamic Light Scattering (DLS) Analysis

**Objective:** Characterize particle size distribution and surface charge (zeta potential) before and after electrocoagulation treatment

**Parameters Measured:**
1. **Particle Size Distribution**
   - Measurement principle: Light scattering intensity fluctuations from Brownian motion
   - Output: Mean particle diameter (nm), polydispersity index

2. **Zeta Potential**
   - Measurement principle: Electrophoretic mobility under applied electric field
   - Output: Surface charge (mV) indicating colloidal stability

**Samples Analyzed:**
- **B01:** PVC-contaminated water (before treatment)
- **B04:** PVC-contaminated water (after electrocoagulation treatment)

**Instrument Protocol:**
- Instrument operated by USM laboratory personnel

**Key Results:**
- **B01 (Before):** Average particle size = 1129 nm (1.1 μm), Zeta potential = -20.3 mV
- **B04 (After):** Average particle size = 1657 nm (1.7 μm), Zeta potential = -12.7 mV
- **Interpretation:** 47% increase in particle size indicates successful aggregation; 37% reduction in zeta potential (closer to isoelectric point) confirms charge neutralization mechanism

### 5.2 Fourier Transform Infrared Spectroscopy (FTIR)

**Objective:** Chemical identification and confirmation of PVC presence in water samples

**Measurement Principle:**
- Infrared absorption spectroscopy identifying molecular vibrations characteristic of PVC chemical bonds (C-Cl stretching, C-H bending)

**Expected Outcome:**
- Confirmation of PVC fingerprint in contaminated samples
- Verification that target contaminant is indeed PVC

### 5.3 UV-VIS Spectroscopy

**Objective:** Measure optical properties of water samples to assess clarity and particle concentration

**Measurement Principle:**
- Light absorption/transmission through sample across ultraviolet and visible wavelength range

**Applications:**
- Turbidity assessment (indirect measure of particle concentration)
- Water quality comparison before/after treatment
- Correlation with particle size data from DLS

**Data Files:**
- Raw data: `.csv` and `.DSW` formats
- Analysis: Absorption/transmission spectra graphs

---

## 6. Quality Assurance and Controls

### 6.1 Control Samples
- **Sterilized water (Sample 1):** Negative control to establish baseline measurements in absence of contamination
- **Untreated PVC water (B01):** Establishes initial contamination level before electrocoagulation

### 6.2 Experimental Limitations and Assumptions

**Documented Limitations:**
1. **Single replicate per sample type:** Due to resource constraints, one bottle per sample was prepared
2. **Graphite electrode leaching:** Trace graphite particles may be present in treated water (B04)
   - **Assumption justification:** FTIR spectroscopy can distinguish between PVC and graphite based on distinct molecular signatures; DLS measures overall particle size distribution regardless of composition
3. **Quantification of initial microplastic concentration:** Exact PVC concentration in prepared samples not measured prior to DLS analysis
4. **Process parameters:** Some operational details (electrode spacing, exact treatment time, current monitoring) not fully documented during prototype development phase

### 6.3 Instrument Calibration
- All analytical instruments at USM operated and maintained according to standard laboratory protocols
- Measurements conducted by trained personnel under academic supervision

---

## 7. Data Collection and Analysis

### 7.1 Data Management
- **Raw data formats:**
  - DLS: Numerical output (particle size distributions, zeta potentials)
  - FTIR: Spectral files (`.sp` format)
  - UV-VIS: Comma-separated values (`.csv`), spectral workspace files (`.DSW`)
- **Processed data:** Excel workbooks (`.xlsx`), visual graphs, summary PDFs

### 7.2 Statistical Analysis
- **Comparative analysis:** Before (B01) vs. After (B04) treatment
- **Key metrics:**
  - Percent change in mean particle size
  - Percent change in zeta potential
  - Qualitative assessment of spectroscopic data

### 7.3 Result Interpretation Framework
- **Successful aggregation criteria:**
  - Increase in mean particle diameter (larger aggregates formed)
  - Reduction in zeta potential magnitude (charge neutralization)
  - Improved water clarity (UV-VIS spectroscopy)

---

## 8. Validation and Collaboration

### 8.1 University Partnership
This research was conducted in collaboration with **Universiti Sains Malaysia (USM)**, providing:
- Access to advanced analytical instrumentation
- Technical expertise and guidance
- Independent verification of results
- Academic validation of methodology

### 8.2 Timeline
- **Sample preparation:** December 13-14, 2025
- **Laboratory testing:** December 15, 2025
- **Data receipt and analysis:** December 16-26, 2025

### 8.3 Documentation
- Collaboration formalized through official university correspondence
- Full test reports received from USM laboratory
- Data archived in project repository

---

## 9. Ethical Considerations and Safety

### 9.1 Laboratory Safety
- All electrical work conducted with appropriate safety precautions
- Chemical handling (if any coagulants used beyond electrodes) followed safety protocols
- Prototype testing supervised by experienced mentor and teacher advisor

### 9.2 Environmental Considerations
- Waste water from testing properly disposed according to school guidelines
- Prototype designed for potential real-world application in water treatment systems

---

## References

### Foundational Research Papers
1. Science Direct - Electrocoagulation Study: https://www.sciencedirect.com/science/article/pii/S1674237023001217
2. ACS Langmuir Journal: https://pubs.acs.org/doi/10.1021/acs.langmuir.3c01700
3. UTAR FYP - Electrocoagulation Research: http://eprints.utar.edu.my/5699/1/fyp_EV_2022_FRQ.pdf

### Institutional Documentation
- USM Collaboration Letter: `S44-Final-Surat kolaborasi USM -TEAM 2.pdf`
- USM Laboratory Test Data: `USM-test/` directory
- Project Journey Documentation: `journey.md`
- Test Analysis Summary: `USM-test-analysis.md`

---

**Document Version:** 1.0
**Last Updated:** December 26, 2025
**Prepared by:** ElectroNet Research Team, Sekolah Tuanku Abdul Rahman (STAR)
