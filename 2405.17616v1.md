# Design of a Rectangular Linear Microstrip Patch Antenna Array for 5G Communication

## COMPREHENSIVE TECHNICAL EXTRACTION

**Paper Title:** Design of a Rectangular Linear Microstrip Patch Antenna Array for 5G Communication

**Authors:** Muhammad Asfar Saeed & Augustine O. Nwajana

**Institution:** University of Greenwich, Faculty of Engineering, Medway, United Kingdom

**Conference:** 4th International Conference on Electrical, Computer and Energy Technologies (ICECET 2024)

**Date:** 25-27 July 2024, Sydney, Australia

---

## 1. ABSTRACT SUMMARY

**Key Specifications:**
- **Design Type:** Rectangular Linear Microstrip Patch Antenna Array
- **Operating Frequency:** 18 GHz (Ku-band)
- **Number of Elements:** Six (6) radiating patch elements
- **Array Configuration:** Linear arrangement
- **Substrate Material:** RO3003
- **Substrate Dielectric Constant:** εr = 3
- **Loss Tangent:** tan δ = 0.0009 (low-loss)
- **Substrate Thickness:** h = 1.574 mm
- **Impedance Matching:** 50 Ω
- **Overall Antenna Dimensions:** 29.5 × 7 mm (compact form factor)
- **Resonant Frequency:** 18 GHz
- **-10 dB Impedance Bandwidth:** 700 MHz (1 GHz total)
- **Maximum Gain:** 7.51 dBi
- **Antenna Feeding Method:** Microstrip line feeding mechanism
- **Backing:** Conducting ground plane

---

## 2. DESIGN AND DEVELOPMENT

### 2.1 Array Configuration

**Physical Structure:**
- **Array Type:** Linear arrangement (1D array)
- **Number of Elements:** Six (6) rectangular patches
- **Patch Arrangement:** Aligned in linear configuration along substrate
- **Element Spacing:** Determined by transmission line coupling
- **Total Array Footprint:** 29.5 mm (length) × 7 mm (width)

**Feeding Mechanism:**
- **Primary Feed Type:** Microstrip line feeding method
- **Feed Configuration:** Edge-mounted connector at one end
- **Feed Location:** Excites entire linear array through transmission line
- **Feed Line Dimensions:**
  - Length (FL): 1 mm
  - Width (FW): 0.20 mm
- **Transmission Line Type:** Thin microstrip lines interconnecting radiating patches
- **Excitation Result:** Generation of fan beam pattern with constructive and destructive interference

### 2.2 Substrate Material Selection

**Material:** RO3003 (Rogers Corporation)

**Advantages:**
1. **Low Dielectric Loss**
   - Minimal energy dissipation
   - Efficient signal transmission
   - Low tangent of loss (0.0009)

2. **High Dielectric Constant**
   - Enables compact antenna design
   - Reduces wavelength by factor of √εr
   - Contributes to smaller overall dimensions
   - Core objective: miniaturization

3. **Stable Electrical Properties**
   - Wide frequency range stability
   - Wide temperature range stability
   - Critical for varied operational environments
   - Suitable for high-temperature exposure scenarios

4. **Mechanical Stability**
   - Enhanced durability
   - Improved reliability
   - Long-term operation capability
   - Mechanical rigidity during fabrication

5. **Manufacturing Integration**
   - Easy circuit integration
   - Simplifies overall design process
   - Compatible with standard PCB manufacturing

### 2.3 Antenna Dimensions

**Complete Dimensional Specifications:**

**Patch Dimensions:**
- Length (L): 3.85 mm
- Width (W): 5.89 mm

**Ground Plane Specifications:**
- Length (GL): 29.50 mm
- Width (GW): 7 mm
- Thickness (t): 0.5 mm

**Substrate Specifications:**
- Length (L): 29.50 mm
- Width (W): 7 mm
- Thickness (h): 1.574 mm
- Relative Permittivity (εr): 3
- Loss Tangent (tan δ): 0.0009

**Feed Line Specifications:**
- Length (FL): 1 mm
- Width (FW): 0.20 mm

### 2.4 Design Methodology

**Simulation Software:** CST Microwave Studio®

**Numerical Method:** Finite Integration Technique (FIT)

**FIT Capabilities:**
- Solves Maxwell's equations with high accuracy
- Analyzes electromagnetic behavior including:
  - Wave propagation
  - Reflection phenomena
  - Diffraction effects
  - Near-field interactions
  - Far-field radiation patterns
- Full-wave analysis accounting for all electromagnetic effects
- Frequency range support: Millimeter-wave frequencies (18 GHz)
- High-fidelity simulation of complex electromagnetic interactions

---

## 3. PERFORMANCE EVALUATION AND RESULTS

### 3.1 Reflection Coefficient (S11 Parameter)

**Definition:** Measures ratio of reflected power to incident power upon antenna

**Performance Metric:** S11 indicates impedance matching quality between antenna and transmission line

**Measured Results:**
- **Resonant Frequency:** 18 GHz
- **Return Loss at Resonance:** ≤ -16 dB (minimal reflection)
- **-10 dB Impedance Bandwidth:** 1 GHz (0.7 GHz margin noted)
- **Return Loss Level:** Lesser than -16 dB indicates excellent impedance matching
- **Reflection Characteristics:** Minimal reflection within transmission line
- **Power Transfer Efficiency:** Maximized through excellent matching

**Significance:** Low S11 values indicate good impedance matching and maximized power transfer efficiency

### 3.2 Impedance Matching

**Configuration:** Microstrip line feeding method

**Target Impedance:** 50 Ω (standard RF transmission line impedance)

**Measured Results:**
- **Impedance at Resonance:** 50 Ω (perfectly matched)
- **Reference Impedance Characteristic:** Maximum current flowing from transmission line
- **Matching Result:** Antenna input impedance matches transmission line characteristic impedance

**Benefits of Impedance Matching:**
- Minimized signal reflections
- Maximized power transfer efficiency
- Optimal RF performance
- Reduced signal losses

### 3.3 Current Distribution Analysis

**Observation:** Progressive wave pattern formation across array elements

**Distribution Characteristics:**
- **Pattern Type:** Progressive wave propagation
- **Behavior:** Current flows through transmission line to each patch element
- **Distribution Method:** Along linear array from feed point

**Analysis Importance:**
- Provides insights into electromagnetic energy distribution
- Reveals antenna radiation characteristics
- Enables design optimization for desired performance
- Validates electromagnetic field behavior

### 3.4 Radiation Pattern

**Pattern Type:** 3D Far-field radiation pattern (fan beam)

**E-Plane (Electric Plane) Performance:**
- Good coverage characteristics
- Defined beamwidth
- Controlled sidelobe levels
- Directional radiation concentration

**H-Plane (Magnetic Plane) Performance:**
- Good coverage characteristics
- Consistent directional properties
- Sidelobe management

**Overall Pattern Characteristics:**
- **Beam Type:** Fan beam (narrow in one dimension, broad in another)
- **Beamwidth:** Determined by linear array configuration
- **Coverage:** Well-defined in both E-plane and H-plane
- **Directivity:** Concentration of radiation in primary beam direction
- **Sidelobe Levels:** Controlled and measured

**Pattern Parameters Defined:**
- Beamwidth
- Directivity
- Sidelobe levels
- Coverage area
- Spatial focusing capabilities

### 3.5 Antenna Gain

**Measured Gain Value:** 7.51 dBi (higher gain realized)

**Gain Representation in Simulated Results:** 7.91 dBi (noted in comparison table)

**Gain Definition:** Quantifies radiation intensity in particular direction relative to isotropic radiator

**Isotropic Radiator Reference:** Radiates uniformly in all directions

**Physical Significance:**
- Higher gain indicates greater radiation concentration in desired direction
- Improved communication range capability
- Enhanced signal strength in primary beam direction
- Superior communication effectiveness

**Practical Implications:**
- Increased link budget
- Extended communication distance
- Better signal-to-noise ratio
- Enhanced overall system performance

---

## 4. FIGURES AND DIAGRAMS

### Figure 1: Proposed MPA Array
- **Description:** Schematic illustration of the linear microstrip patch antenna array
- **Components Shown:**
  - Six radiating patches in linear arrangement
  - Ground plane backing
  - Substrate layer
  - Feed line connection point
- **Dimensions:** 29.5 × 7 mm overall footprint
- **Configuration:** Linear arrangement of rectangular patches on RO3003 substrate

### Figure 2: Simulated Reflection Coefficient Response
- **Axis:** Frequency response plot
- **Y-axis:** S11 parameter (dB)
- **X-axis:** Frequency range (centered at 18 GHz)
- **Key Points:**
  - Resonant frequency at 18 GHz
  - Return loss ≤ -16 dB at resonance
  - -10 dB bandwidth = 1 GHz
  - Good impedance matching demonstrated

### Figure 3: Current Distribution of Proposed MPA Array
- **Visualization:** Electromagnetic field visualization of current flow
- **Direction:** Current progression from feed point through array
- **Pattern:** Progressive wave pattern formation
- **Significance:** Shows energy distribution and coupling between elements
- **Analysis:** Reveals electromagnetic behavior and validates design

### Figure 4: 3-D Far-Field Radiation Pattern
- **Pattern Type:** Three-dimensional radiation pattern
- **Characteristics:**
  - Fan beam pattern formation
  - Good E-plane and H-plane coverage
  - Directional concentration
  - Defined beamwidth
  - Controlled sidelobe levels
- **Beam Direction:** Oriented along array normal direction
- **Coverage:** Comprehensive spatial radiation characteristics

### Figure 5: Reference Impedance
- **Plot Type:** Smith chart or impedance plot
- **Reference:** 50 Ω impedance line
- **Measurement Point:** Antenna input impedance
- **Result:** Perfect impedance matching at 50 Ω
- **Significance:** Validates RF circuit compatibility

---

## 5. TABLES

### Table I: Dimensions of the MPA Array Antenna Elements

| Antenna Element | Parameters | Dimensions (mm) |
|---|---|---|
| **PATCH** | Length (L) | 3.85 |
| | Width (W) | 5.89 |
| **GROUND** | Length (GL) | 29.50 |
| | Width (GW) | 7 |
| | Thickness (t) | 0.5 |
| **FEEDLINE** | Length (FL) | 1 |
| | Width (FW) | 0.20 |
| **SUBSTRATE** | Length (L) | 29.50 |
| | Width (W) | 7 |
| | Thickness (h) | 1.574 |
| | Permittivity (εr) | 3 |

### Table II: Comparison of the MPA Array with Literature References

| Reference | Antenna Type | Resonant Frequency | Return Loss (dB) | Gain (dBi) |
|---|---|---|---|---|
| [12] | Planar Array | 4-7 GHz | -22 | 6.5 |
| [13] | Coupled Array | 28.5 GHz | -14 | 1.51 |
| [8] | Phased Array | 25-33 GHz | -23 | 5 |
| **PROPOSED** | **Linear Array** | **18 GHz** | **-16** | **7.91** |

**Comparative Analysis:**
- Proposed design operates at mid-range frequency (18 GHz)
- Return loss of -16 dB is acceptable for practical applications
- Gain of 7.91 dBi is competitive with literature designs
- Compact dimensions achieved
- Trade-off between complexity and performance well-balanced

---

## 6. MATHEMATICAL MODELS AND EQUATIONS

### 6.1 Fundamental Antenna Equations

**Impedance Matching Condition:**
- Z_antenna = Z_line = 50 Ω (transmission line impedance)
- Ensures maximum power transfer

**Resonant Frequency Relationship:**
- Patch dimensions (L, W) determine resonant frequency
- Direct relationship with dielectric constant: f ∝ 1/(εr × dimension)

**Far-Field Radiation Pattern:**
- Determined by linear array configuration
- Elements separated by specific distances
- Interference patterns (constructive/destructive) shape beam

**Fan Beam Pattern Formation:**
- Linear array creates narrow beam in one direction
- Broad beam in perpendicular direction
- Results from linear element spacing and phasing

### 6.2 Performance Metrics

**Return Loss (dB):**
- RL = -10 × log10(|S11|²)
- Lower (more negative) value indicates better matching

**Gain Definition:**
- G (dBi) = 10 × log10(radiation intensity / isotropic reference)
- Measures antenna directivity and efficiency

**Bandwidth Definition:**
- -10 dB impedance bandwidth = frequency range where |S11| ≤ -10 dB
- Measured: 1 GHz total at 18 GHz resonance

---

## 7. DESIGN TECHNIQUES AND METHODOLOGIES

### 7.1 Linear Array Beamforming Approach

**Basic Principle:** Linear arrangement of radiating elements creates directional beam pattern

**Element Coupling:**
- Coupling between radiating elements within array
- Responsible for achieving wide-angle beamforming
- Works in both linear and phased arrays

**Beamforming Techniques Employed:**
1. **Element Width Expansion**
   - Increases current distribution
   - Enables wave propagation increase
   - Affects radiation characteristics

2. **Transmission Line Coupling**
   - Thin microstrip lines interconnect patches
   - Provides current path between elements
   - Controls phase and amplitude relationship

3. **Fan Beam Generation**
   - Linear arrangement produces fan pattern
   - Constructive interference in desired direction
   - Destructive interference suppresses sidelobes

### 7.2 Design Optimization Process

**Iterative Design Methodology:**
1. Define antenna specifications (frequency, gain, impedance)
2. Calculate patch dimensions using resonant frequency equations
3. Design transmission line feed network
4. Simulate in CST Microwave Studio using FIT method
5. Analyze performance parameters (S11, impedance, gain, pattern)
6. Optimize dimensions for desired performance
7. Validate final design

**Key Design Parameters Optimized:**
- Patch length and width for resonant frequency
- Element spacing for array performance
- Feed line dimensions for impedance matching
- Ground plane size for radiation efficiency

### 7.3 Related Techniques in Literature

**Multilayer Substrate Approaches:**
- Adding multiple dielectric layers
- Improves bandwidth and radiation efficiency
- Increases design complexity

**Circular Polarization Techniques:**
- Quad-ridged waveguide designs
- Slot-fed waveguide arrays
- Enables circular polarization for enhanced performance

**High-Gain Directional Pointing:**
- Millimeter-wave microstrip array antennas
- Alumina thin-film substrates
- Integration of beamforming capabilities

**Tapered Array Designs:**
- Progressive variation in element size
- Reduces sidelobe levels
- Improves directional characteristics

**Limitations of Alternative Approaches:**
- Complex antenna structures
- Beam scanning accuracy challenges
- Inefficiency in some configurations
- Gain fluctuations during operation
- Increased fabrication complexity

---

## 8. TECHNICAL SPECIFICATIONS SUMMARY

### Electrical Specifications:

| Parameter | Value | Unit |
|---|---|---|
| Operating Frequency | 18 | GHz |
| Frequency Band | Ku-band | — |
| Impedance | 50 | Ω |
| Return Loss at Resonance | -16 | dB |
| -10 dB Bandwidth | 1 | GHz |
| Maximum Gain | 7.51 | dBi |
| Number of Elements | 6 | — |
| Array Configuration | Linear | — |

### Physical Specifications:

| Parameter | Value | Unit |
|---|---|---|
| Overall Dimensions | 29.5 × 7 × 1.574 | mm |
| Patch Length | 3.85 | mm |
| Patch Width | 5.89 | mm |
| Feed Line Width | 0.20 | mm |
| Ground Plane Thickness | 0.5 | mm |
| Substrate Thickness | 1.574 | mm |

### Material Specifications:

| Parameter | Value | Unit |
|---|---|---|
| Substrate Material | RO3003 | — |
| Dielectric Constant | 3 | — |
| Loss Tangent | 0.0009 | — |
| Substrate Density | — | — |
| Operating Temperature Range | Wide | — |

### Electromagnetic Characteristics:

| Parameter | Value | Unit |
|---|---|---|
| Beam Type | Fan Beam | — |
| E-Plane Coverage | Good | — |
| H-Plane Coverage | Good | — |
| Sidelobe Control | Managed | — |
| Radiation Pattern | Directional | — |

---

## 9. APPLICATION CONTEXT

### Primary Applications:

1. **5G Communication Systems**
   - Frequency compatibility with 5G Ku-band
   - High data rate support
   - Compact integration capability

2. **Future 6G Systems**
   - Scalable architecture
   - Beamforming-ready design
   - Foundation for advanced technologies

### Supporting Use Cases:

**Communication Enhancement:**
- Ultra-high-definition video streaming
- Internet of Things (IoT) connectivity
- Low-latency data transmission
- Massive device connectivity support

**Advantages for Target Applications:**
- Compact form factor enables device integration
- Cost-effectiveness compared to waveguide designs
- Flexible beamforming capabilities
- Broad impedance and radiation coverage

---

## 10. CITATIONS AND REFERENCES

[1] Jabbar, Abdul, Qammer Abbasi, Zhibo Pang, Muhammad Ali Imran, and Masood Ur-Rehman. "High Performance 60 GHz Beamforming Antenna Array For 5G and Beyond Industrial Applications." In 2023 17th European Conference on Antennas and Propagation (EuCAP), pp. 1-5. IEEE, 2023

[2] Jabbar et al., "A Wideband Frequency Beam-Scanning Antenna Array for Millimeter-Wave Industrial Wireless Sensing Applications," in IEEE Sensors Journal, vol. 24, no. 8, pp. 13315-13325, 15 April 2024, doi: 10.1109/JSEN.2024.3370135

[3] M. A. Saeed and M. Ur-Rehman, "Design of an LCP-based Antenna Array for 5G/B5G Wearable Applications," 2019 UK/China Emerging Technologies (UCET), Glasgow, UK, 2019, pp. 1-5, doi: 10.1109/UCET.2019.8881850

[4] M. Ur-Rehman, Q. H. Abbasi, A. Rahman, I. Khan, H. T. Chattha, and M. Matin, "Millimetre-Wave Antennas and Systems for the Future 5G," International Journal of Antennas and Propagation, vol. 2017, pp. 1–2, Jan. 2017, doi: 10.1155/2017/6135601

[5] M. A. Saeed and A. Nwajana, "A novel beamforming antenna array for 5G and beyond applications," 2022 International Conference on Engineering and Emerging Technologies (ICEET), Kuala Lumpur, Malaysia, 2022, pp. 1-4, doi: 10.1109/ICEET56468.2022.10007412

[6] Q. H. Abbasi et al., "Ultra wideband antenna diversity characterisation for off‐body communications in an indoor environment," IET Microwaves, Antennas & Propagation, vol. 8, no. 14, pp. 1161–1169, Nov. 2014, doi: 10.1049/iet-map.2013.0370

[7] H. T. Zhang, W. Wang, Z. Zheng, M. P. Jin, X. Fang and G. Huang, "Design of A Beamforming Circular-polarization Waveguide Antenna Array," 2018 IEEE Asia-Pacific Conference on Antennas and Propagation (APCAP), Auckland, New Zealand, 2018, pp. 64-65, doi: 10.1109/APCAP.2018.8538115

[8] Syrytsin I, Zhang S, Pedersen GF, Morris AS (2018) Broadband mm-wave microstrip array antenna with improved radiation characteristics for different 5G applications. IEEE Antennas Wireless Propagation Letters 66(9):4648–4657

[9] M. A. Saeed, M. Ahmad, A. Nwajana, M. U. Rehman, M. A. Sohaib and A. Naseer, "Coaxial Feed Ultra-Wideband Microstrip Antenna for Medical Applications," 2022 International Conference on Electrical, Computer and Energy Technologies (ICECET), Prague, Czech Republic, 2022, pp. 1-4, doi: 10.1109/ICECET55527.2022.9872795

[10] M. A. Saeed and A. Nwajana, "U-Shaped Terahertz Microstrip Patch Antenna for 6G Future Communications," 2023 7th International Electromagnetic Compatibility Conference (EMC Turkiye), İstanbul, Türkiye, 2023, pp. 1-4, doi: 10.1109/EMCTurkiye59424.2023.10287461

[11] A. O. Nwajana, Dual-Band microwave filter for WiMax application. 2020. [Online]. Available: https://gala.gre.ac.uk/id/eprint/29414/

[12] Saeed, M. A., & Nwajana, A. O. (2024). A review of beamforming microstrip patch antenna array for future 5G/6G networks. Frontiers in Mechanical Engineering, 9, 1288171

[13] Hao Z-C, He M, Fan K, Luo G (2017) A planar broadband antenna for the E-band gigabyte wireless communication. IEEE Transactions on Antennas and Propagation 65(3):1369–1373

[14] Ta SX, Park I (2017) Compact wideband circularly polarized patch antenna array using metasurface. IEEE Antennas and Wireless Propagation Letters 16:1932–1936

[15] I. K. Ihianle, A. O. Nwajana, S. H. Ebenuwa, R. I. Otuka, K. Owa, and M. O. Orisatoki, "A deep learning approach for human activities recognition from multimodal sensing devices," IEEE Access, vol. 8, pp. 179028–179038, Jan. 2020, doi: 10.1109/access.2020.3027979

[16] CST-Microwave Studio Users Manual, 2019

---

## 11. CONCLUSIONS AND FINDINGS

**Design Success:**
- Successfully designed and simulated rectangular linear microstrip patch antenna array
- Operating at 18 GHz in Ku-band frequency range
- Six radiating patches in linear configuration

**Key Performance Achievements:**
- Excellent impedance matching at 50 Ω
- Return loss of -16 dB indicates good RF performance
- Compact dimensions of 29.5 × 7 mm achieved
- High gain of 7.51 dBi realized
- Effective beamforming pattern formation

**Beamforming Capability:**
- Successfully formed fan beam pattern
- Linear array configuration enables directional radiation
- Constructive and destructive interference properly utilized
- Directional concentration of electromagnetic energy achieved

**Practical Applicability:**
- Design validates potential for practical implementation in 5G communication systems
- Compact form factor enables device integration
- Cost-effectiveness compared to alternative approaches
- Excellent radiation characteristics

**Foundation for Future Development:**
- Lays groundwork for continued exploration of high-frequency antenna technologies
- Enables development of advanced 5G/6G communication systems
- Provides platform for further optimization and enhancement

