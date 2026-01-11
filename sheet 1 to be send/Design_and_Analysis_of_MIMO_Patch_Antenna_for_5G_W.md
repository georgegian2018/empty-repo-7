**Technical Extraction Document**

---

## Document Information

**Title:** Design and Analysis of MIMO Patch Antenna for 5G Wireless Communication Systems

**Authors:** Pallavi H. V¹*, A P Jagadeesh Chandra², Paramesha³

**Affiliations:**
- ¹ Department of ECE, Government Engineering College, Hassan, Karnataka, India
- ² Department of ECE, Adichunchanagiri Institute of Technology, Chikkamagalur, Karnataka, India
- ³ Department of ECE, Central University of Karnataka, Kalaburagi, Karnataka, India

**Source:** International Journal of Computer Networks & Communications (IJCNC), Vol.14, No.4, July 2022

**DOI:** 10.5121/ijcnc.2022.14403

---

## Abstract

A circular array microstrip patch antenna (MPA) design is proposed for 5G wireless communication utilizing millimeter-wave frequency to enhance coverage area. The Multi Input Multi Output (MIMO) feeding technique is employed to improve performance at a resonant frequency of 35 GHz. The substrate material is RT-Duroid 5880 with dielectric constant 2.2 and thickness 0.5 mm. Simulation analysis obtained gain of 8.8 dB and return loss of -41.9 dB. Comparative analysis validates that the circular array MPA is superior to single element MPA and 2×2 rectangular array MPA designs for 5G wireless communication.

**Keywords:** Wireless communication, Bandwidth, Radiation efficiency, Antennas, Microstrip patch antenna (MPA)

---

## Equations and Mathematical Models

### Design Parameter Equations

**Equation 1: Patch Width Calculation**

$$W_p = \frac{c}{2f_r\sqrt{\frac{\varepsilon_r + 1}{2}}}$$

Where:
- $W_p$ = patch width
- $c$ = speed of light (3 × 10⁸ m/s)
- $f_r$ = resonance frequency
- $\varepsilon_r$ = dielectric constant value

**Equation 2: Patch Length Calculation**

$$L_p = L_{peff} - 2\Delta L_p$$

Where:
- $L_p$ = length of patch
- $L_{peff}$ = effective length of patch
- $\Delta L_p$ = extension length of patch

**Equation 3: Effective Patch Length**

$$L_{peff} = \frac{c}{2f_r\sqrt{\varepsilon_{reff}}}$$

Where:
- $\varepsilon_{reff}$ = effective dielectric constant

**Equation 4: Patch Length Extension**

$$\Delta L_p = 0.412h \frac{(\varepsilon_{reff} + 0.3)(\frac{W_p}{h} + 0.264)}{(\varepsilon_{reff} - 0.258)(\frac{W_p}{h} + 0.8)}$$

Where:
- $h$ = substrate thickness
- $\varepsilon_{reff}$ = effective dielectric constant

**Equation 5: Effective Dielectric Constant**

$$\varepsilon_{reff} = \frac{\varepsilon_r + 1}{2} + \frac{\varepsilon_r - 1}{2}\left[1 + 12\frac{h}{W_p}\right]^{-1/2}$$

**Equation 6: Substrate Length**

$$L_g = 6h + L_p$$

Where:
- $L_g$ = length of substrate

**Equation 7: Substrate Width**

$$W_g = 6h + W_p$$

Where:
- $W_g$ = width of substrate

**Equation 8: Microstrip Feed Line Length**

$$L_f = \frac{1}{4}\lambda_g$$

Where:
- $L_f$ = length of microstrip feed line
- $\lambda_g$ = guided wave length

**Equation 9: Guided Wavelength**

$$\lambda_g = \frac{\lambda}{\sqrt{\varepsilon_{reff}}}$$

**Equation 10: Free Space Wavelength**

$$\lambda = \frac{c}{f_r}$$

**Equation 11: Feed Line Width**

$$W_f = \frac{7.48 \times h}{e^{\left(\frac{Z_0\sqrt{\varepsilon_r + 1.41}}{87} - 1.25 \times t\right)}}$$

Where:
- $W_f$ = width of feed line
- $Z_0$ = impedance value (50 Ω)
- $t$ = trace thickness (0.0175 mm)

---

## Technical Specifications and Design Parameters

### Substrate Material Specifications

| Specification | Value | Unit |
|---|---|---|
| Material | RT-Duroid 5880 | - |
| Dielectric Constant | 2.2 | - |
| Thickness | 0.5 | mm |
| Resonance Frequency | 35 | GHz |
| Conductor Material (Patch & Ground) | Copper | - |
| Conductor Thickness | 0.0175 | mm |
| Port Impedance | 50 | Ω |
| Trace Thickness | 0.0175 | mm |

### Calculated and Optimized Design Parameters

\begin{table}
\begin{tabular}{|l|l|c|c|}
\hline
Design Parameter & Description & Calculated (mm) & Optimized (mm) \\
\hline
$W_p$ & Width of patch & 3.386 & 3.62 \\
$L_p$ & Length of patch & 2.551 & 2.45 \\
$W_g$ & Width of substrate and ground plane & 5.49 & 6 \\
$L_g$ & Length of substrate and ground plane & 4.65 & 6 \\
$W_f$ & Width of feed line & 0.46 & 0.46 \\
$L_f$ & Length of feed line & 1.57 & 1.57 \\
\hline
\end{tabular}
\caption{Obtained and Optimized Values of Design Parameters}
\end{table}

---

## Design Configurations and Methodologies

### Three Antenna Designs Analyzed

#### 1. Single Element Microstrip Patch Antenna (MPA)

**Configuration:**
- Single circular patch element
- Single feed line
- Single port (SISO - Single Input Single Output)
- Optimized substrate dimensions: 6 × 6 mm
- Optimized ground plane dimensions: 6 × 6 mm
- Radiation box dimensions: 15 mm length × 15 mm width × 8 mm height

**Design Features:**
- Simple single-element design serving as baseline
- Designed and analyzed using HFSS (High-Frequency Structure Simulation) software
- Port impedance: 50 Ω
- Simulation frequency range: 28 GHz to 42 GHz
- Maximum simulation passes: 20

**Design Methodology:**
The substrate is designed first utilizing optimized parameters. Patch and feed line are designed on one side of substrate; ground plane covers the other side. Port placement is at appropriate location. Radiation box is designed around structure. Boundaries are assigned: patch, feed line, and ground plane as perfect E; radiation box as radiation boundary. Port assigned as lumped port excitation with full port impedance 50 Ω.

#### 2. 2×2 Rectangular Array Microstrip Patch Antenna

**Configuration:**
- Four patch elements arranged in 2×2 rectangular formation
- Four ports with MIMO feeding
- Four feed lines
- Substrate dimensions: 12 × 12 mm (doubled from single element)
- Ground plane dimensions: 12 × 12 mm
- Radiation box dimensions: 20 mm length × 20 mm width × 10 mm height

**Patch Positioning:**
- Two patches placed horizontally with 0° rotation
- Two patches placed above first two with 90° rotation
- Rectangular grid arrangement

**Design Features:**
- MIMO structure implementation
- Each port impedance: 50 Ω
- Similar analysis setup as single element MPA
- Enhanced radiation properties through array configuration

#### 3. Circular Array Microstrip Patch Antenna (Proposed Design)

**Configuration:**
- Four patch elements arranged in circular formation
- Four ports with MIMO feeding
- Four feed lines
- Substrate dimensions: 12 × 12 mm (same as rectangular array)
- Ground plane dimensions: 12 × 12 mm
- Radiation box dimensions: 20 mm length × 20 mm width × 10 mm height (same as rectangular)

**Patch Positioning:**
- Patches located at angular positions: 0°, 90°, 180°, and 270°
- Arranged in circular pattern around center
- Each patch rotated at respective angular positions

**Design Features:**
- MIMO structure implementation
- Each port impedance: 50 Ω
- Novel circular array configuration for improved performance
- Optimized for 5G millimeter-wave applications

**Design Methodology - All Three Designs:**
All designs utilize High-Frequency Structure Simulation (HFSS) software platform from ANSYS. Complete design flow includes: parameter setup → geometry creation → boundary conditions assignment → port definition → radiation box definition → simulation setup (sweep) → frequency analysis and results extraction.

---

## Simulation Results and Performance Metrics

### Performance Metrics Definition

The following performance parameters are evaluated for all antenna designs:

- **Gain:** Strength of transmitted/received RF signals in particular direction (dB)
- **Return Loss (S₁₁):** Ratio of reflected to applied frequencies; should be < 0 for good impedance matching (dB)
- **VSWR (Voltage Standing Wave Ratio):** Efficiency of transmitted RF power; optimal range 1-2 (dimensionless)
- **Bandwidth:** Range of frequencies where antenna can properly transmit/receive (GHz)
- **Mutual Coupling:** Electromagnetic interactions between antenna elements; should be minimal (dB)
- **Radiation Efficiency:** Ratio of radiated power to input power (absolute value)
- **Radiation Pattern:** Energy distribution radiated from antenna (E-plane and H-plane)

### Single Element MPA Results

\begin{table}
\begin{tabular}{|c|c|c|c|c|c|}
\hline
Resonance Frequency (GHz) & Gain (dB) & Return Loss (dB) & VSWR & Bandwidth (GHz) & Radiation Efficiency (abs) \\
\hline
35 & 8.1 & -34.5 & 1.18 & 1.9 (35.7–33.8) & 1.02 \\
\hline
\end{tabular}
\caption{Performance Analysis Results of Single Element MPA}
\end{table}

**Key Findings:**
- Achieved -10 dB return loss at 35 GHz bandwidth
- VSWR of 1.18 indicates good impedance matching
- Bandwidth of 1.9 GHz (35.7–33.8 GHz)
- Radiation efficiency of 1.02 (absolute value)

### 2×2 Rectangular Array MPA Results

\begin{table}
\begin{tabular}{|c|c|c|c|c|c|c|}
\hline
Resonance Frequency (GHz) & Gain (dB) & Return Loss (dB) & VSWR & Bandwidth (GHz) & Mutual Coupling (dB) & Radiation Efficiency (abs) \\
\hline
35 & 8.4 & -33.9 & 1.6 & 1.9 (35.3–33.4) & -23.05 & 1.02 \\
\hline
\end{tabular}
\caption{Performance Analysis Results of 2×2 Rectangular Array MPA}
\end{table}

**Key Findings:**
- Improved gain to 8.4 dB compared to single element
- Return loss of -33.9 dB
- VSWR of 1.6 (acceptable but higher than single element)
- Bandwidth maintained at 1.9 GHz (35.3–33.4 GHz)
- Mutual coupling between elements: -23.05 dB
- Radiation efficiency: 1.02 (absolute value)

### Proposed Circular Array MPA Results

\begin{table}
\begin{tabular}{|c|c|c|c|c|c|c|}
\hline
Resonance Frequency (GHz) & Gain (dB) & Return Loss (dB) & VSWR & Bandwidth (GHz) & Mutual Coupling (dB) & Radiation Efficiency (abs) \\
\hline
35 & 8.8 & -41.9 & 1.19 & 2 (35.7–33.7) & -26.82 & 1.02 \\
\hline
\end{tabular}
\caption{Performance Results of Proposed Circular Array MPA}
\end{table}

**Key Findings:**
- **Highest gain:** 8.8 dB (0.4 dB improvement over rectangular, 0.7 dB over single element)
- **Best return loss:** -41.9 dB (8 dB improvement over rectangular, 7.4 dB over single element)
- **Lowest VSWR:** 1.19 (similar to single element, 0.41 dB lower than rectangular)
- **Widest bandwidth:** 2 GHz (35.7–33.7 GHz) - 0.1 GHz improvement over others
- **Best mutual coupling:** -26.82 dB (3.77 dB improvement over rectangular)
- **Radiation efficiency:** 1.02 (absolute value, consistent across all designs)

### Comparative Analysis of All Three Designs

\begin{table}
\begin{tabular}{|l|c|c|c|c|c|c|}
\hline
Antenna Design & Gain (dB) & Return Loss (dB) & VSWR & Bandwidth (GHz) & Mutual Coupling (dB) & Radiation Efficiency (abs) \\
\hline
Single Element MPA & 8.1 & -34.5 & 1.18 & 1.9 & — & 1.02 \\
2×2 Rectangular Array MPA & 8.4 & -33.9 & 1.6 & 1.9 & -23.05 & 1.02 \\
Circular Array MPA (Proposed) & 8.8 & -41.9 & 1.19 & 2 & -26.82 & 1.02 \\
\hline
\end{tabular}
\caption{Comparative Analysis of Three MPA Designs}
\end{table}

**Performance Conclusions:**

The circular array MPA demonstrates superior overall performance across all critical parameters:
- **Gain improvement:** 8.8% higher than single element, 4.8% higher than rectangular
- **Return loss improvement:** 21.5% better than single element, 23.1% better than rectangular
- **VSWR performance:** Lowest value at 1.19, indicating optimal impedance matching
- **Bandwidth advantage:** 2 GHz bandwidth (widest among three designs)
- **Mutual coupling:** Best isolation with -26.82 dB (3.77 dB better than rectangular)
- **Radiation efficiency:** Consistent 1.02 across all designs

---

## Figures and Illustrations

### Single Element MPA Designs

**Figure 1: 2D Design of Single Element MPA**
- Illustrates top-down view of single circular patch element
- Shows patch dimensions, feed line positioning, and substrate layout
- All dimensions correspond to optimized parameters from Table 1

**Figure 2: 3D Design of Single Element MPA**
- Three-dimensional representation of single element MPA
- Shows spatial relationship between patch (top), substrate layer, ground plane (bottom)
- Depicts feed line connection point
- Illustrates vertical substrate structure

### 2×2 Rectangular Array MPA Designs

**Figure 3: 2D Design for 2×2 Rectangular MPA Array**
- Top-down view showing four patch elements in rectangular 2×2 formation
- Two patches aligned horizontally (0° rotation)
- Two patches positioned above first pair (90° rotation)
- Shows substrate dimensions expanded to 12 × 12 mm
- Illustrates four feed line connections

**Figure 4: 3D Design for 2×2 Rectangular MPA Array**
- Three-dimensional representation of rectangular array
- Shows four patch elements with alternating orientation
- Ground plane extended to 12 × 12 mm
- Visualizes substrate layer and feed network structure

### Circular Array MPA Designs

**Figure 5: 2D Design for Novel Circular Array MPA**
- Top-down view showing four patch elements in circular formation
- Patches positioned at angular intervals: 0°, 90°, 180°, 270°
- Patches arranged around central point
- Substrate dimensions: 12 × 12 mm
- Shows four feed line connections to central hub

**Figure 6: 3D Design for Novel Circular Array MPA**
- Three-dimensional representation of circular array configuration
- Four patches spatially distributed at angular positions
- Ground plane visible beneath substrate layer
- Central feed network connecting to four ports
- Depicts complete array structure in 3D space

### Performance Graphs - Single Element MPA

**Figure 7: Return Loss Plot for Single Element MPA**
- Rectangular plot showing S₁₁ (return loss) vs. frequency
- Frequency range: 28–42 GHz
- Minimum return loss achieved at 35 GHz: -34.5 dB
- -10 dB bandwidth clearly marked
- Plot demonstrates good impedance matching

**Figure 8: VSWR Plot for Single Element MPA**
- Rectangular plot showing VSWR vs. frequency
- VSWR value at 35 GHz: 1.18
- Demonstrates acceptable VSWR in 1–2 range
- Shows frequency response around resonance

**Figure 9: Radiation Pattern for Single Element MPA**
- (a) E-plane radiation pattern (θ varied, φ = 0°)
  - Shows radiation intensity in electric field plane
  - Omnidirectional characteristics in E-plane
- (b) H-plane radiation pattern (θ varied, φ = 90°)
  - Shows radiation intensity in magnetic field plane
  - Demonstrates pattern in perpendicular direction

### Performance Graphs - 2×2 Rectangular Array MPA

**Figure 10: Return Loss Plot for 2×2 Rectangular Array MPA**
- Rectangular plot showing S₁₁ vs. frequency
- Frequency range: 28–42 GHz
- Return loss at 35 GHz: -33.9 dB
- Shows frequency response of rectangular array

**Figure 11: VSWR Plot for 2×2 Rectangular Array MPA**
- Rectangular plot showing VSWR vs. frequency
- VSWR value at 35 GHz: 1.6
- Within acceptable range but higher than single element
- Reflects impact of four-element array

**Figure 12: Mutual Coupling Plot for 2×2 Rectangular Array MPA**
- Rectangular plot showing mutual coupling (S₂₁, S₃₁, etc.) vs. frequency
- Isolation level: -23.05 dB at 35 GHz
- Shows electromagnetic coupling between array elements
- Indicates moderate isolation between neighboring patches

**Figure 13: Radiation Pattern for 2×2 Rectangular Array MPA**
- (a) E-plane radiation pattern
  - Shows radiation characteristics in E-plane
  - Enhanced directivity compared to single element
- (b) H-plane radiation pattern
  - Shows radiation in perpendicular direction
  - Array effects visible in pattern

### Performance Graphs - Proposed Circular Array MPA

**Figure 14: Return Loss Plot for Proposed Circular Array MPA**
- Rectangular plot showing S₁₁ vs. frequency
- Frequency range: 28–42 GHz
- Return loss at 35 GHz: -41.9 dB (best performance)
- Demonstrates superior impedance matching
- Sharp resonance peak at 35 GHz

**Figure 15: VSWR Plot for Circular Array MPA**
- Rectangular plot showing VSWR vs. frequency
- VSWR value at 35 GHz: 1.19
- Excellent VSWR performance (second lowest)
- Narrow bandwidth indicates sharp resonance

**Figure 16: Mutual Coupling Plot for Circular Array MPA**
- Rectangular plot showing mutual coupling vs. frequency
- Isolation level: -26.82 dB at 35 GHz (best isolation)
- Shows significantly reduced electromagnetic coupling
- Circular geometry provides superior element isolation

**Figure 17: Radiation Pattern for Circular Array MPA**
- (a) E-plane radiation pattern
  - Shows enhanced directivity characteristic
  - Circular array geometry reflected in pattern
- (b) H-plane radiation pattern
  - Shows perpendicular plane radiation
  - Demonstrates omnidirectional characteristics

---

## References

[1] Liu, M., Xue, W., Jia, P., Makarov, S.B. and Li, B., 2020. Research on spectrum optimization technology for a wireless communication system. *Symmetry*, 12(1), p.34.

[2] Sandi, E., Rusmono, A.D., Diamah, A. and Vinda, K., 2020. Ultra-wide band Microstrip Array Antenna for 5G Millimeter-wave Applications. *J. Commun.*, 15(2), pp.198-204.

[3] Simkó, M. and Mattsson, M.O., 2019. 5G wireless communication and health effects—A pragmatic review based on available studies regarding 6 to 100GHz. *International Journal of Environmental Research and Public Health*, 16(18), p.3406.

[4] Lodro, Z., Tirmizi, S.B. and Lodro, M., 2019, November. Compact Microstrip Patch Antenna Array Design for 5G Wireless Communication. In *2019 Second International Conference on Latest Trends in Electrical Engineering and Computing Technologies (INTELLECT)* (pp.1-4). IEEE.

[5] Famoriji, O.J., Yang, S., Li, Y., Chen, W., Fadamiro, A., Zhang, Z. and Lin, F., 2019. Design of a simple circularly polarised dual-frequency reconfigurable microstrip patch antenna array for millimetre-wave applications. *IET Microwaves, Antennas & Propagation*, 13(10), pp.1671-1677.

[6] Umayah, E.N. and Srivastava, V.M., 2019. Comparative view of return loss, VSWR, gain, and efficiency of cylindrical surrounding patch antenna with frequency shift. *Int. J. of Electrical and Electronic Engineering & Telecommunications*, 8(6), pp.352-357.

[7] Guttula, R. and Nandanavanam, V.R., 2020. Mutation probability-based lion algorithm for design and optimization of microstrip patch antenna. *Evolutionary Intelligence*, 13(3), pp.331-344.

[8] Rajan, S.P. and Vivek, C., 2019. Analysis and design of microstrip patch antenna for radar communication. *Journal of Electrical Engineering & Technology*, 14(2), pp.923-929.

[9] Bansal, A. and Gupta, R., 2020. A review on microstrip patch antenna and feeding techniques. *International Journal of Information Technology*, 12(1), pp.149-154.

[10] Hussain, N., Jeong, M.J., Abbas, A., Kim, T.J. and Kim, N., 2020. A meta surface-based low-profile wide band circularly polarized patch antenna for 5G millimeter-wave systems. *IEEE Access*, 8, pp.22127-22135.

[11] Priyadharshini, R.A., Arivazhagan, S., Arun, M. and Arunadevi, A., 2021. Half mode rogers RT-duroid 5880 substrate integrated wave guide cavity backed V-slot antenna for C-band applications. *Materials Today: Proceedings*, 37, pp.1854-1858.

[12] Nguyen, D.H., Ala-Laurinaho, J., Moll, J., Krozer, V. and Zimmer, G., 2020. Improved side lobe-suppression microstrip patch antenna array by uniform feeding networks. *IEEE Transactions on Antennas and Propagation*, 68(11), pp.7339-7347.

[13] Su, G.R., Li, E.S., Kuo, T.W., Jin, H., Chiang, Y.C. and Chin, K.S., 2020. 79-GHz Wide-Beam Microstrip Patch Antenna and Antenna Array for Millimeter-Wave Applications. *IEEE Access*, 8, pp.200823-200833.

[14] Saad, A.A.R. and Mohamed, H.A., 2019. Printed millimeter-wave MIMO-based slot antenna arrays for 5G networks. *AEU-International Journal of Electronics and Communications*, 99, pp.59-69.

[15] Abdelaziz, A. and Hamad, E.K., 2020. Isolation enhancement of 5G multiple-input multiple-output microstrip patch antenna using meta materials and the theory of characteristic modes. *International Journal of RF and Microwave Computer-Aided Engineering*, 30(11), p.e22416.

[16] Olaimat, M. and Al-Qaisi, A., 2015. Novel designs of broadband patch antenna for wireless communication. *International Journal of Computer Networks and Communications*, 7(3), pp.161-169.

---

## Document Summary

This technical extraction document comprehensively organizes all content from the research paper "Design and Analysis of MIMO Patch Antenna for 5G Wireless Communication Systems." The document includes:

- **11 mathematical equations** for antenna design parameter calculations
- **Complete technical specifications** for substrate material and antenna components
- **Detailed descriptions** of three antenna design configurations
- **Comprehensive performance metrics** with simulation results
- **8 figures** documenting antenna geometry and performance characteristics
- **5 data tables** presenting design parameters and performance comparisons
- **16 complete citations** in proper academic format
- **Comparative analysis framework** showing circular array MPA superiority

