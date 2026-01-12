# Extracted Content — Fluid Antenna System—Part I: Preliminaries

Source: `Fluid_Antenna_SystemPart_I_Preliminaries.pdf` (IEEE Communications Letters, Vol. 27, No. 8, Aug. 2023)

## Diagrams, Figures, and Illustrations

### Fig. 1. Average rate of SIMO and MIMO FAS against the SNR.

![](Fluid_Antenna_SystemPart_I_assets/Fig1.png)

### Fig. 2. gDoF of different approaches against α when Γ = 30 dB.

![](Fluid_Antenna_SystemPart_I_assets/Fig2.png)

## Equations and Mathematical Models

Equation images are provided as cropped renderings from the paper to preserve exact formatting and symbols.

### Eq. (1) — extracted from page 2

![](Fluid_Antenna_SystemPart_I_assets/Eq01.png)

### Eq. (2) — extracted from page 2

![](Fluid_Antenna_SystemPart_I_assets/Eq02.png)

### Eq. (3) — extracted from page 2

![](Fluid_Antenna_SystemPart_I_assets/Eq03.png)

### Eq. (4) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq04.png)

### Eq. (5) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq05.png)

### Eq. (6) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq06.png)

### Eq. (7) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq07.png)

### Eq. (8) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq08.png)

### Eq. (9) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq09.png)

### Eq. (10) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq10.png)

### Eq. (11) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq11.png)

### Eq. (12) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq12.png)

### Eq. (13) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq13.png)

### Eq. (14) — extracted from page 3

![](Fluid_Antenna_SystemPart_I_assets/Eq14.png)

### Eq. (15) — extracted from page 4

![](Fluid_Antenna_SystemPart_I_assets/Eq15.png)

### Eq. (16) — extracted from page 4

![](Fluid_Antenna_SystemPart_I_assets/Eq16.png)

### Eq. (17) — extracted from page 4

![](Fluid_Antenna_SystemPart_I_assets/Eq17.png)

### Eq. (18) — extracted from page 4

![](Fluid_Antenna_SystemPart_I_assets/Eq18.png)

### Eq. (19) — extracted from page 4

![](Fluid_Antenna_SystemPart_I_assets/Eq19.png)

## Simulation Results and Performance Metrics

- Performance plots are provided in **Fig. 1** (average rate vs SNR) and **Fig. 2** (gDoF vs α).
- Reported average gDoFs (two-user case): **TIN = 0.146**, **HK = 0.606**, **FAMA (3λ×1λ, 30×10 ports) = 0.7782**, **FAMA (9λ×3λ, 90×30 ports) = 0.9079**.

## Technical Specifications of Each Antenna or Relevant Component

- **1D FAS geometry:** line structure of size **W·λ** with **N** evenly distributed ports (port represents a selectable physical location).
- **SIMO received signal model:** see Eq. (1) and outage formulation Eq. (2).
- **FAMA UE surface examples (Fig. 2 discussion):**
  - **30×10** ports over area **3λ×1λ**
  - **90×30** ports over area **9λ×3λ**
- **Channel correlation/covariance:** Bessel-function correlation (Eq. (10)) and eigenvalue-based representation (Eq. (9)–(11)); 2D MIMO-FAS model (Eq. (12)).

## Design Techniques, Configurations, and Methodologies

The excerpts below are taken directly from the paper text (with IEEE header/footer text retained where it appears in the extraction).

### Excerpt — pages 1–2 (context and FAS/FAMA preliminaries)



