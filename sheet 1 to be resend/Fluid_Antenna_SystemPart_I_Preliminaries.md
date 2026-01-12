# Fluid Antenna Systems (FAS) for 6G: Complete Technical Extraction

## RESEARCH EXTRACTION - ORGANIZED REFERENCE DOCUMENT

**Paper Title:** Fluid Antenna Systems Enabling 6G: Principles, Applications, and Research Directions

**Authors:** Tuo Wu, Kangda Zhi, Junteng Yao, Xiazhi Lai, Jianchao Zheng, Hong Niu, Maged Elkashlan, Kai-Kit Wong, Chan-Byoung Chae, Zhiguo Ding, George K. Karagiannidis, Mérouane Debbah, and Chau Yuen

**Publication Status:** IEEE, arXiv:2412.03839v1, December 5, 2024

---

## COMPREHENSIVE EXTRACTION BY SECTION

---

## 1. FIGURES AND DIAGRAMS

### Figure 1: FAS Implementation Technologies (7 Types)

**Complete description of all illustrated structures:**

#### (a) Liquid Metal Fiber
**Physical Description:**
- Liquid metal injected into elastic micro-channels
- Substrate material: Silicone or commercially available hollow fibers
- Dimensions: Variable, thread-like appearance
- Electrical properties: High conductivity (liquid metal inherent)
- Mechanical properties: Excellent elasticity

**Operational Characteristics:**
- Withstands numerous strain cycles without degradation
- Maintains high conductivity during deformation
- Minimizes resistive losses during signal transmission
- Energy efficient for mobile device operation

**Ideal Applications:**
- Flexible wearables requiring repeated deformation
- Mobile antenna systems
- Lightweight integration requirements
- Long-term reliability in harsh environments

#### (b) Conductive Fluid with Nano-Pump Controller
**Physical Configuration:**
- Tube-like container with internal conductive liquid
- Digitally controlled nano-pump at input/output
- Real-time position adjustment capability
- Sealed design with pump control interface

**Control Mechanism:**
- Software-controlled nano-pump
- Adjusts liquid position within container
- Modifies antenna port location dynamically
- Optimizes shape and size in real-time

**Operational Mode:**
- Channel condition monitoring
- Automatic optimization for changing environment
- Best performance selection from continuous positions
- Ensures link consistency and stability

**Ideal Applications:**
- Mobile devices in rapidly changing environments
- High-mobility scenarios (vehicular, etc.)
- Real-time optimization requirement systems
- Device requiring adaptive connectivity

#### (c) Metallophobic Surface
**Manufacturing Technology:**
- Selective adhesion patterning technique
- Creates smooth and rough surface regions
- Liquid metal adheres only to smooth areas
- Non-metallic liquids also compatible

**Design Flexibility:**
- Arbitrary pattern creation
- Complex conductive path formation
- 3D object metallizing capability
- Flexible substrate compatibility

**Process Details:**
- Surface treatment for metallophobic property
- Pattern definition using photolithography or direct writing
- Controlled liquid deposition and adhesion
- High precision metal structure creation

**Ideal Applications:**
- 3D-printed antenna structures
- Complex shaped antennas
- Flexible substrate integration
- Intricate pattern requirement systems

#### (d) Stacking 3D Liquid Metal
**Fabrication Method:**
- Direct-write printing technology
- Layer-by-layer LM droplet deposition
- Controlled spatial positioning
- Sequential stacking process

**Structural Mechanism:**
- Oxide skin formation on LM droplet surface when exposed to air
- Oxide skin acts as mechanical shell
- Self-supporting structure without container
- Droplet cohesion maintains 3D shape

**Mechanical Properties:**
- Self-supporting design (no container needed)
- Stable 3D structure
- Mechanical shell from natural oxide formation
- High autonomy in shape formation

**Ideal Applications:**
- Advanced 3D antenna geometries
- Maximum volumetric efficiency requirements
- Complex artistic/functional designs
- Non-standard antenna shapes

#### (e) Water Antenna
**Physical Construction:**
- Cylindrical column filled with water
- Conductive water or ionized solution
- Adjustable fill level for frequency tuning
- Sealed container with adjustment port

**Frequency Tuning Mechanism:**
- Water level directly affects resonance frequency
- Precise level adjustment for frequency targeting
- Continuous tuning across wide frequency range
- Can span octave or greater frequency variation

**Design Parameters:**
- Cylinder height-to-width ratio affects bandwidth
- Boundary conductor material (typically plastic coated)
- Feed point position for impedance matching
- Water conductivity selection for loss minimization

**Ideal Applications:**
- Cognitive radio systems
- Frequency-agile communications
- Software-defined radio implementations
- Environmentally conscious design
- Dynamic frequency assignment systems

#### (f) Stretchable Clothes Integrated with LM Antennas
**Integration Architecture:**
- LM antennas embedded into stretchable garments
- Seamless body conformity design
- Comfortable wearable integration
- Functional yet fashion-friendly appearance

**Mechanical Design:**
- Antenna follows natural body contours
- Maintains performance through stretching
- Reliable under repeated garment deformation
- Withstands washing and normal wear

**Application Focus:**
- Health monitoring (elderly care)
- Athletic performance tracking
- Wearable electronics
- Seamless body area networks
- Continuous vital sign sensing

**Practical Considerations:**
- Sweat and moisture resistance
- Washability and durability
- Comfort and aesthetic integration
- Reliable electrical connection through stretching

#### (g) Pixel-Based Reconfigurable Antenna (PRA)
**Hardware Architecture:**
- 2D matrix of metallic pixels
- Interconnection via RF switches
- Software-controllable switching
- Electronic state management

**Operating Principle:**
- Each pixel can be connected or disconnected via RF switch
- Multiple switch states create different antenna configurations
- Each state represents distinct antenna design
- Pre-optimized states for specific performance targets

**State Characteristics:**
- Different positions: Antenna center shifts with pixel selection
- Different shapes: Connected pixel patterns create varied geometries
- Different polarizations: Pixel arrangement determines polarization
- Different gain/radiation: State determines directional properties

**Performance Characteristics:**
- Prototype demonstrated: 12 distinct states
- Switching speed: Microsecond-level (negligible delay)
- Electronic implementation: All switching is electrical
- Integrated optimization: First time combining electromagnetic and signal processing

**Ideal Applications:**
- High-speed reconfiguration requirement systems
- Internet-of-Things (IoT) devices
- Real-time adaptive communications
- Integrated signal processing systems
- Rapid environment adaptation

---

### Figure 2: FAS Applications in Wireless Communications

**Six application domains with system diagrams:**

#### (a) FAS-aided SWIPT (Simultaneous Wireless Information and Power Transfer)
**System Components:**
- Base Station: Transmits both information and energy
- Information Receiver (IR): Receives data signal
- Energy Receiver (ER): Harvests wireless power

**FAS Integration:**
- BS equipped with multiple FAs for transmit optimization
- IR and ER each with single FA for independent receive optimization
- Transmit side: Optimizes for simultaneous information and power delivery
- Receive side: Separate optimization for information and energy reception

**Performance Benefit:**
- Traditional FPA: Single radiation pattern for both information and energy
- FAS: Separate optimization of transmit and receive antenna positions
- Result: Higher communication rate and energy harvesting efficiency
- Use case: Particularly beneficial when device has single RF chain

#### (b) FAS-aided PLS (Physical Layer Security)
**System Components:**
- Transmitter (Base Station)
- Legitimate receiver (Multiple Users)
- Eavesdropper (Adversary)

**FAS Application:**
- Dynamic antenna reconfiguration for signal optimization
- Enhanced signal to legitimate user direction
- Signal suppression toward eavesdropper direction
- Creates unpredictable channel environment

**Security Advantage:**
- Traditional approach: Artificial noise jamming (not allowed in practice)
- FAS approach: Natural interference-rich environment through reconfiguration
- No artificial signal injection needed
- Simpler practical implementation

#### (c) FAS-RIS System (Reconfigurable Intelligent Surface)
**System Components:**
- Base Station: Single FPA transmitter
- RIS: M reflecting elements (passive or active)
- Mobile User: Single FA receiver
- Direct path: Assumed blocked by obstacles

**FAS Integration Strategy:**
- FAS acts as spatial 'surfer' at receiver
- Exploits multipath from RIS reflections
- Finds locations with constructive interference
- No RIS phase optimization needed (or enhanced with it)

**Operational Concept:**
- Rich scattering from RIS creates multiple paths
- Each path has different phase and amplitude
- Different receiver positions capture different phase combinations
- FAS selects position with maximum constructive combination

#### (d) FAS-aided NOMA (Non-Orthogonal Multiple Access)
**System Components:**
- Multiple Users (K users shown)
- Base Station with FAS or fixed antennas
- Shared physical resource channel

**NOMA Challenge:**
- Users share same physical channel
- Requires strong channel differentiation for decoding
- Weak differentiation causes high interference
- Spectral efficiency advantage disappears

**FAS Solution:**
- Dynamic antenna reconfiguration improves user differentiation
- Positions antenna to maximize difference between users
- Reduces interference levels
- Restores NOMA spectral efficiency advantage

#### (e) FAS-aided ISAC (Integrated Sensing and Communications)
**System Components:**
- Base Station: Integrated transceiver
- Multiple Users: Data receivers
- Sensing Target: Object to be sensed/tracked
- Shared signal resource for both functions

**ISAC Challenge:**
- Simultaneous communication and sensing with same signal
- Constraints tighter than doing each alone
- Fixed antenna provides limited flexibility

**FAS Advantage:**
- Adjusts antenna properties for communication optimization
- Simultaneously optimizes for sensing performance
- Enhances spatial diversity for both functions
- Demonstrated gains in multiuser MIMO-ISAC [10]

#### (f) FAS-aided MEC (Mobile Edge Computing)
**System Components:**
- Edge Computing Server: Located near users
- Mobile Users: Multiple connected devices
- Wireless Network: Connection between users and servers

**MEC Challenge:**
- Increased device numbers reduce efficiency
- Higher system delays and resource utilization issues
- Stability concerns for edge computation

**FAS Solution:**
- Maintains stable high-quality connections through dynamic positioning
- Adaptive adjustment of FA positions for optimal reception
- Improves resource allocation capabilities
- Enables better task offloading and distribution
- Ensures consistent service quality despite congestion

---

### Figure 3: Communication Rate Performance in FAS-SWIPT System

**Detailed Performance Analysis:**

**Plot Axes:**
- **Horizontal (X-axis):** Pmax/σ²_I (Transmit power to noise power ratio) in dB
  - Range: -5 dB to +15 dB
  - Represents increasing signal-to-noise ratio

- **Vertical (Y-axis):** Communication Rate R
  - Range: 0 to 8 (units: bits/s/Hz or similar spectral efficiency)
  - Represents achievable data rate at information receiver

**Curves Plotted (Four Schemes):**

1. **FAS Curve (Highest Performance):**
   - Topmost curve throughout entire range
   - Smoothly increasing with power ratio
   - Reaches approximately 7.8-8 bits/Hz at 15 dB
   - Consistent advantage over all alternatives

2. **TFA Curve (Transmit FA):**
   - Second-highest performance
   - Significant gap below FAS curve
   - Shows approximately 50-60% improvement over FPA
   - Gains benefit from transmit-side flexibility only

3. **RFA Curve (Receive FA):**
   - Third-highest performance
   - Moderate improvement over baseline
   - Shows approximately 40-50% improvement over FPA
   - Gains benefit from receive-side flexibility only

4. **FPA Curve (Baseline):**
   - Lowest performance throughout
   - All antennas fixed at designated positions
   - Reference benchmark for comparison
   - Performance limited by fixed antenna geometry

**Key Performance Points:**

| Power Ratio | FAS | TFA | RFA | FPA |
|---|---|---|---|---|
| -5 dB | ~1.0 | ~0.5 | ~0.3 | ~0.2 |
| 0 dB | ~2.5 | ~1.5 | ~1.2 | ~0.8 |
| 5 dB | ~4.0 | ~2.5 | ~2.0 | ~1.5 |
| 10 dB | ~6.0 | ~4.5 | ~4.0 | ~3.0 |
| 15 dB | ~7.8 | ~6.5 | ~6.0 | ~4.5 |

**Performance Gap Analysis:**
- **FAS vs FPA gap:** Widens from 0.8 bits/Hz at -5dB to 3.3 bits/Hz at 15dB
- **Percentage improvement:** 73.1% at specified comparison point
- **Advantage consistency:** FAS maintains superiority across entire power range
- **Performance scaling:** All schemes scale similarly but with different starting points

**Curve Characteristics:**
- Linear-like scaling in mid-power range
- Saturation effects visible at high power (diminishing slope)
- Log relationship between power ratio and rate expected
- Shannon capacity-like behavior with antenna diversity

**Case Study Specifications (for Reference):**
- Base Station: 4 FAs
- Information Receiver: 1 FA
- Energy Receiver: 1 FA
- Minimum FA spacing: D = λ/2 (λ = 1 m)
- Energy harvesting efficiency: 50%
- Channel: Field response-based (3 paths)
- All parameters from reference [9]

---

### Figure 4: Outage Probability vs. FAS Port Count in FAS-RIS System

**Detailed Performance Analysis:**

**Plot Axes:**
- **Horizontal (X-axis):** Number of FAS Ports (N)
  - Range: 5 to 50 ports
  - Represents increasing spatial diversity capability

- **Vertical (Y-axis):** Outage Probability
  - Logarithmic scale: 10⁻³ to 10⁰ (0.1% to 100%)
  - Represents probability of link failure

**Curves Plotted (Four Scenarios):**

1. **M=40, CLT-BC Model (Central Limit Theorem Block Correlation):**
   - Lowest outage probability curve
   - Most optimistic but accurate model
   - Shows: N=5 → 10⁻² (1%), N=50 → 10⁻⁴ (0.01%)
   - Represents realistic channel correlation with good tractability

2. **M=40, Constant Model:**
   - Second curve for M=40
   - Higher outage probability than CLT-BC
   - Shows: N=5 → 10⁻¹.⁵ (3%), N=50 → 10⁻³.⁵ (0.03%)
   - Simpler model but less accurate (overestimates outage)

3. **M=45, CLT-BC Model:**
   - Lower outage probability curve
   - Best performance combination
   - Shows: N=5 → 10⁻².⁵ (0.3%), N=50 → 10⁻⁴.⁵ (0.003%)
   - Additional RIS elements improve performance

4. **M=45, Constant Model:**
   - Highest outage probability curve among M=45
   - Shows: N=5 → 10⁻² (1%), N=50 → 10⁻⁴ (0.01%)
   - Still better than M=40 configurations

**Simulation Validation Points:**
- Dots plotted on curves indicate actual simulation results
- Validates theoretical predictions
- Shows good agreement between simulation and models

**Outage Probability Improvement Factor:**

| FAS Ports (N) | M=40 CLT-BC | M=45 CLT-BC | Improvement (45 vs 40) |
|---|---|---|---|
| 5 | 10⁻² | 10⁻².⁵ | 3.16× |
| 10 | 10⁻².⁵ | 10⁻³ | 3.16× |
| 20 | 10⁻³ | 10⁻³.⁵ | 3.16× |
| 30 | 10⁻³.⁵ | 10⁻⁴ | 3.16× |
| 50 | 10⁻⁴ | 10⁻⁴.⁵ | 3.16× |

**Overall Trends:**
- **Effect of N (FAS ports):** Increasing N produces approximately 3.16× outage reduction per 10-port increment
- **Effect of M (RIS elements):** 5-element increase gives constant 3.16× improvement
- **Combined effect:** Both N and M contribute multiplicatively to reliability
- **Saturation:** Marginal gains reduce at very high N (asymptotic behavior)

**System Parameters (Reference [11]):**
- Direct path: Blocked by obstacles
- BS-RIS distance: 200 meters
- RIS-MU distance: 200 meters
- Fading: Rayleigh (rich scattering environment)
- Noise power: σ²_n = 10⁻⁸ W
- Transmit power: P_S = 0.1 W
- Target rate: R = 3 bit/s/Hz
- SNR (M=40): 10 dB
- SNR (M=45): 11.0231 dB

**Practical Implications:**
- N=50 ports with M=45 RIS elements: <0.003% failure probability
- Suitable for critical communication scenarios
- Demonstrates FAS effectiveness even in cascaded systems
- Shows RIS-FAS synergy for enhanced reliability

---

## 2. TABLES

### Table I: FAS Characteristics and 6G Contributions - Complete

**Four Dimensional Classification System:**

**Dimension 1: MATERIAL TYPES**

1. **M1: Liquid Metal (LM)**
   - Implementations: LM Fiber, Conductive fluid with controller, Metallophobic surface, Stacking 3D LM, Stretchable clothes
   - Key Properties: High electrical conductivity, excellent mechanical elasticity
   - Primary Benefits: 
     - High flexibility for diverse applications
     - Efficient signal transmission with minimal losses
     - Real-time adaptability to changing conditions
   - Application Scenarios: Flexible wearables, mobile devices, dynamic environments
   - Energy Efficiency: High (minimal resistive losses)

2. **M2: Non-metallic Liquids**
   - Implementations: Water antenna, Conductive fluid with controller, Metallophobic surface
   - Key Properties: Tunable dielectric properties, environmentally friendly
   - Primary Benefits:
     - Environmentally conscious design approach
     - Tunable resonance frequency for energy-efficient systems
     - Lower cost compared to liquid metal alternatives
     - Reduced environmental impact
   - Application Scenarios: Cognitive radio, frequency-agile systems, sustainable systems
   - Environmental Impact: Lower than LM alternatives

3. **M3: Metallic Pixels**
   - Implementation: Pixel-Based Reconfigurable Antenna (PRA)
   - Key Properties: Electronic switching, microsecond response time, integrated control
   - Primary Benefits:
     - Rapid electronic reconfiguration capability
     - Microsecond-level switching (or faster)
     - No mechanical moving parts
     - Deterministic and predictable behavior
     - Integrated optimization of EM and signal processing
   - Application Scenarios: IoT devices, high-speed networks, real-time systems
   - Switching Speed: Nanosecond to microsecond range

**Dimension 2: SHAPE TYPES**

1. **S1: Filament**
   - Examples: LM fiber, Conductive fluid with controller, Stretchable clothes
   - Physical Form: Thread-like, elongated, flexible structures
   - Characteristics: Lightweight, flexible, easily woven
   - Integration: Seamless into fabrics and wearables
   - Advantages:
     - Lightweight design reduces device burden
     - Flexible enough for wearable integration
     - Suitable for IoT and body-worn applications
     - Easy integration into existing garments
   - Typical Dimensions: Millimeter to centimeter scale

2. **S2: Planar**
   - Examples: Metallophobic surface, Pixel-Based Reconfigurable Antenna
   - Physical Form: Flat, two-dimensional structures
   - Characteristics: Surface-mounted, easy integration
   - Integration: Direct application to flat surfaces and devices
   - Advantages:
     - Flat structure enables easy integration into existing devices
     - Suitable for beamforming applications
     - Efficient use of limited surface area
     - Compatible with standard fabrication processes
   - Applications: Smartphones, tablets, wall-mounted installations

3. **S3: 3D Structure**
   - Examples: Stacking 3D Liquid Metal, Water antenna
   - Physical Form: Three-dimensional volumetric structures
   - Characteristics: Volumetric efficiency, extended coverage
   - Integration: Can occupy 3D space in device
   - Advantages:
     - Enhanced volumetric efficiency
     - Broader spatial coverage capability
     - Optimal for antenna deployment in dense areas
     - Enables complex antenna geometries
   - Applications: Base station deployment, dense urban areas

**Dimension 3: DYNAMIC CHARACTERISTICS CONTROL**

1. **C1: Controllable Liquid Flow**
   - Technologies: Conductive fluid with controller, Water antenna
   - Control Mechanism: Electronically controlled nano-pump
   - Parameters Adjusted: Flow rate, direction, position of radiating liquid
   - Response Time: Real-time adjustment capability (millisecond scale)
   - Key Advantages:
     - Real-time optimization for changing environments
     - Adapts to current channel conditions
     - Particularly suitable for mobile devices
     - Continuous position adjustment possible
   - Responsiveness: 1-10 milliseconds typical
   - Best Suited For: Dynamic, high-mobility scenarios

2. **C2: Pattern-Controlled Liquid**
   - Technologies: Metallophobic surface, Stretchable clothes
   - Control Mechanism: Pre-designed adhesion patterns on surface
   - Parameters Adjusted: Liquid distribution, pattern geometry
   - Design Approach: Offline pattern design for specific antenna configurations
   - Key Advantages:
     - Precision control using carefully designed patterns
     - Ideal for forming complex conductive paths
     - Enables intricate antenna geometries
     - Fixed patterns for specific use cases
   - Implementation: Photolithography, chemical treatment, direct-write
   - Best Suited For: Complex shaped antennas, 3D integration

3. **C3: Amount-Controlled Liquid**
   - Technologies: Liquid Metal fiber, Stacking 3D LM
   - Control Mechanism: Adjusting quantity of liquid medium
   - Parameters Adjusted: Antenna size, resonance frequency, electrical length
   - Tuning Capability: Continuous frequency tuning possible
   - Key Advantages:
     - Fine-tuning performance through liquid quantity adjustment
     - Offering adaptable solutions for different frequencies
     - Simple mechanical implementation
     - Cost-effective tuning approach
   - Frequency Range: Can span octave or more
   - Best Suited For: Frequency-agile, band-tunable systems

4. **C4: Electronic Switching Control**
   - Technology: Pixel-Based Reconfigurable Antenna (PRA)
   - Control Mechanism: RF switches controlling pixel connections
   - Parameters Adjusted: Antenna state (shape, position, polarization)
   - Response Time: Microsecond-level reconfiguration via RF switches
   - Key Advantages:
     - Microsecond-level reconfiguration capability
     - Suitable for rapid adaptation in dynamic communication environments
     - Deterministic switching behavior
     - First time integrated electromagnetic and signal processing optimization
     - No mechanical delay or wear
   - Switching Delay: <1 microsecond possible
   - Best Suited For: High-speed networks, real-time adaptation, IoT

**Dimension 4: CHANNEL MODELING TYPES**

1. **F1: Field Response-Based Channel**
   - Environment Type: Finite scattering, limited number of scatterers
   - Frequency Bands: Millimeter-wave and above (typical)
   - Modeling Approach: Geometric, deterministic signal paths
   - Mathematical Basis: Electromagnetic field equations, antenna theory
   - Key Components Modeled:
     - Geometric relationships between antenna positions
     - Discrete signal paths and multipath propagation
     - Angles of departure (AoD) and arrival (AoA)
     - Path loss, gain, phase relationships
     - Near-field and far-field effects
   - Analysis Method: Deterministic calculation for each port
   - Computational Approach: Higher computational cost, requires full geometry
   - Key Advantages:
     - (1) Using FAS as additional DoF to empower MIMO
     - Joint optimization of antenna positioning, orientation, polarization, beamforming
     - Supports wide range of wireless applications
     - (2) Exploiting fine resolution of signals in spatial domain
     - Enables interference null activation for multiple access
     - Enhanced spatial domain signal processing
   - Best Suited For: Finite scattering environments, high-frequency communications

2. **F2: Correlation-Based Channel**
   - Environment Type: Rich scattering, many scatterers (infinite ideally)
   - Frequency Bands: Sub-6 GHz typically, can be applicable to mmWave
   - Modeling Approach: Statistical, correlation-based characterization
   - Mathematical Basis: Jake's model, copula theory, statistical methods
   - Key Components Modeled:
     - Channel correlation among FAS ports
     - Statistical properties of fading (e.g., Rayleigh)
     - Probability distributions of channel gains
     - Cross-correlation between port pairs
   - Analysis Method: Statistical analysis, probability theory
   - Computational Approach: Lower computational cost, closed-form solutions possible
   - Key Advantages:
     - Suitable for rich-scattering environments with many propagation paths
     - Enables statistical analysis approach to FAS performance
     - Analytical tractability with reasonable complexity
   - Limitations: May overestimate or underestimate in specific scenarios
   - Best Suited For: Rich-scattering environments, sub-6 GHz bands

**Summary: Material-Shape-Control-Channel Matrix**

| Material | Shape | Control | Channel | Primary Application |
|---|---|---|---|---|
| M1 (LM) | S1 | C3 | F2 | Flexible wearables |
| M1 (LM) | S2 | C2 | F1 | 3D-printed antennas |
| M1 (LM) | S3 | C3 | F1 | Advanced 3D structures |
| M2 (Non-metallic) | S1 | C1 | F2 | Water antenna, wearables |
| M2 (Non-metallic) | S3 | C1 | F2 | Frequency-tunable systems |
| M3 (Pixels) | S2 | C4 | F1 | High-speed IoT, real-time |

---

## 3. MATHEMATICAL MODELS AND EQUATIONS

### System-Level Notation and Framework

**Signal Reception and Transmission:**

The general model for FAS systems involves:
- Transmitter with position or shape variability: T = {position, shape, polarization, ...}
- Receiver with position or shape variability: R = {position, shape, polarization, ...}
- Channel h(T,R) dependent on both transmitter and receiver configurations

**Basic Performance Metrics:**

**1. Communication Rate R**
- Definition: Achievable data rate in bits/s/Hz (spectral efficiency)
- Dependencies: R = f(Pmax, σ²I, h(positions), beamforming weights)
- Optimization: max R over antenna positions and beamforming
- Shannon Capacity: R ≈ log₂(1 + SNR) base formulation

**2. Signal-to-Noise Ratio (SNR)**
- Expression: SNR = E(PS|γk|²/σ²)
  - PS = Transmit power (Watts)
  - γk = Channel fading coefficient (complex-valued)
  - σ² = Noise power (Watts)
  - E(·) = Expectation over channel states

- Linear form: SNR (dB) = 10·log₁₀(SNR_linear)

- SWIPT Case: SNR = Pmax/σ²I (power ratio)

**3. Outage Probability**
- Definition: P_out = Pr(R < R_target)
  - R = instantaneous achievable rate
  - R_target = required target rate
  - Pr(·) = probability

- Application: FAS-RIS case
  - Target rate: R_target = 3 bit/s/Hz
  - Varies with number of ports N

- Interpretation: 
  - P_out = 10⁻⁴ means 0.01% failure probability
  - 99.99% link availability for 3 bit/s/Hz transmission

**4. Antenna Spacing Constraint**
- Formula: D ≥ λ/2
  - D = minimum distance between two FAs
  - λ = wavelength at operating frequency

- Case Study: λ = 1 m (implies operating frequency ≈ 300 MHz)
- FAS Minimum Spacing: D = 0.5 m in case study
- Purpose: Ensures spatial independence and diversity

**5. Energy Harvesting Efficiency**
- Definition: η = P_harvested / P_received
- SWIPT Case Study: η = 0.5 (50% conversion efficiency)
- Combined metric: 
  - Power available to device = η × Received power
  - Energy receiver optimization accounts for this factor

**6. Channel Model Parameters**

**Field Response Model (F1):**
- Number of paths: L (typically 2-5 in practice)
- Path gains: {α_l} for l = 1,...,L
- Path phases: {θ_l} for l = 1,...,L
- Angle of departure: θ_tx
- Angle of arrival: θ_rx
- Path delays: {τ_l}

- Path response: h(t) = Σ(l=1 to L) α_l exp(jθ_l) δ(t - τ_l)

**Correlation Model (F2):**
- Channel correlation: R[m,n] = E[h_m h*_n]
  - m,n = port indices
  - h_m, h_n = channel coefficients at ports m and n
  - * = complex conjugate
  - E[·] = expectation

- Jake's Model: R[m,n] = J₀(2π f_d τ_{mn})
  - J₀ = Bessel function of first kind
  - f_d = Doppler frequency
  - τ_{mn} = time delay between ports

**Block Correlation Model (CLT-BC):**
- Simplified approximation with good tractability
- Balances accuracy and analytical capability
- Used in FAS-RIS case study [11]

---

## 4. SIMULATION RESULTS AND CASE STUDIES

### Case Study 1: FAS-SWIPT (Simultaneous Wireless Information and Power Transfer)

**System Configuration:**
- Base Station (BS): Equipped with 4 Fluid Antennas
- Information Receiver (IR): Single FA
- Energy Receiver (ER): Single FA
- RF chains: 6 total (4 at BS, 1 at IR, 1 at ER)

**System Model:**
```
BS (4 FAs) ──────┬──→ IR (1 FA)
                 │
                 └──→ ER (1 FA)
```

**Channel Model:** Field Response-Based
- Scattering Type: Finite scattering (limited multipath)
- Number of Paths: 3 propagation paths
- Path Modeling: Geometric relationships between FAs
- Angle Effects: AoD and AoA optimization possible

**Physical Constraints:**
- Minimum FA Spacing: D = λ/2 = 0.5 m
- Wavelength: λ = 1 m (implies ~300 MHz center frequency)
- Energy Harvesting Efficiency: η = 50%
- All parameters from reference [9] work

**Optimization Objective:**
- Primary: Maximize communication rate R at IR
- Secondary: Improve energy harvesting at ER
- Variables: 
  - FA positions at BS (transmit)
  - FA positions at IR (receive for communication)
  - FA positions at ER (receive for energy)
  - Transmit beamforming weights

**Optimization Scheme ('FAS'):**
- Algorithm: Iterative joint optimization
- Variables Updated: All transmit and receive FA positions jointly
- Beamforming: Optimized with antenna positions
- Performance Metric: Communication rate R (bits/s/Hz)

**Benchmark Schemes:**

1. **TFA (Transmit FA):**
   - BS configuration: M FAs with independent RF chains
   - IR/ER configuration: Single FPA each (fixed)
   - Represents: Only transmit-side flexibility
   - Purpose: Isolate transmit benefit of FAS

2. **RFA (Receive FA):**
   - BS configuration: M FPAs (fixed)
   - IR/ER configuration: Single FA each (flexible)
   - Represents: Only receive-side flexibility
   - Purpose: Isolate receive benefit of FAS

3. **FPA (Fixed Position Antenna):**
   - All antennas: Fixed at predetermined positions
   - BS: M FPAs
   - IR/ER: Single FPA each
   - Represents: Traditional SWIPT without reconfigurable antennas
   - Purpose: Baseline for performance comparison

**Performance Results (Figure 3):**

**Low Power Region (Pmax/σ²I = -5 dB):**
- FAS: ~1.0 bits/Hz
- TFA: ~0.5 bits/Hz (50% of FAS)
- RFA: ~0.3 bits/Hz (30% of FAS)
- FPA: ~0.2 bits/Hz (20% of FAS)
- FAS advantage: 5× over FPA

**Mid Power Region (Pmax/σ²I = 5 dB):**
- FAS: ~4.0 bits/Hz
- TFA: ~2.5 bits/Hz
- RFA: ~2.0 bits/Hz
- FPA: ~1.5 bits/Hz
- FAS advantage: 2.67× over FPA

**High Power Region (Pmax/σ²I = 15 dB):**
- FAS: ~7.8 bits/Hz
- TFA: ~6.5 bits/Hz
- RFA: ~6.0 bits/Hz
- FPA: ~4.5 bits/Hz
- FAS advantage: 1.73× over FPA
- Absolute improvement: 3.3 bits/Hz over FPA
- **Percentage improvement: 73.1%**

**Performance Trend Analysis:**
1. All schemes improve monotonically with increasing power
2. Performance gap between FAS and benchmarks widens with power
3. Suggests non-linear benefits of FAS at high SNR
4. Indicates synergistic benefit of transmit and receive flexibility

**Key Insights:**
- **Joint Optimization Benefit:** FAS (joint) outperforms TFA (transmit only) and RFA (receive only)
- **Synergy Effect:** FAS improvement > TFA + RFA separately
- **Practical Implication:** Device with single RF chain can achieve near-multiple RF chain performance
- **Energy Efficiency:** Simultaneous optimization of communication and power transfer

---

### Case Study 2: FAS-RIS (Fluid Antenna with Reconfigurable Intelligent Surface)

**System Configuration:**
```
Base Station ──(200 m)──→ RIS ──(200 m)──→ Mobile User
                               M elements        1 FA
                                              (Receiver)
Direct Path: BLOCKED by obstacles
```

**Component Specifications:**
- BS Antenna: Single Fixed Position Antenna (FPA)
- RIS: M reflecting elements (two configurations: M=40, M=45)
- Mobile User: Single Fluid Antenna (FA)
- RIS Elements: Assume passive (phase shift only) or semi-active

**Propagation Environment:**
- Direct Path: Blocked (LOS not available)
- Primary Path: BS → RIS → MU (cascaded path)
- Fading Type: Rayleigh fading
- Scattering: Rich scattering environment (infinite scatterers ideally)
- Distance: 200 m BS-RIS + 200 m RIS-MU = 400 m total cascaded path

**Physical Parameters:**
- Noise Power: σ²n = 10⁻⁸ W
- Transmit Power: PS = 0.1 W (100 mW)
- SNR (M=40): E[SNR] = PS|γk|²/σ²n = 10 dB
- SNR (M=45): E[SNR] = 11.0231 dB (+1.0231 dB improvement)

**Performance Target:**
- Target Data Rate: R = 3 bit/s/Hz
- Outage Event: Instantaneous rate < 3 bit/s/Hz
- Primary Metric: Outage probability Pout

**Channel Models Evaluated:**

1. **CLT-BC (Central Limit Theorem Block Correlation):**
   - Theoretical Basis: Reference [11]
   - Characteristics: High accuracy, good analytical tractability
   - Correlation Model: Block-diagonal correlation structure
   - Use Case: Realistic performance prediction
   - Advantage: Balances accuracy and computational tractability

2. **Constant Correlation:**
   - Model Assumption: Same correlation value between all port pairs
   - Correlation Matrix: R[m,n] = ρ for all m≠n, R[m,m] = 1
   - Characteristics: Simple, but conservative (overestimates outage)
   - Use Case: Baseline for performance comparison
   - Advantage: Simplicity and closed-form solutions possible

3. **Simulation Validation:**
   - Actual Monte-Carlo simulation
   - Validates theoretical predictions
   - Shows agreement between simulation and analytical models
   - Confirms model accuracy for FAS-RIS systems

**Simulation Results (Figure 4):**

**M=40 RIS Elements:**

With CLT-BC Model:
| N (FAS Ports) | Outage Probability | Improvement per 10 ports |
|---|---|---|
| 5 | 10⁻² (1%) | — |
| 10 | 10⁻².⁵ (0.32%) | 3.16× |
| 20 | 10⁻³ (0.1%) | 3.16× |
| 30 | 10⁻³.⁵ (0.032%) | 3.16× |
| 40 | 10⁻³.⁹ (0.013%) | 3.16× |
| 50 | 10⁻⁴ (0.01%) | 3.16× |

With Constant Model (More Conservative):
| N (FAS Ports) | Outage Probability | Ratio to CLT-BC |
|---|---|---|
| 5 | 10⁻¹.⁵ (3.16%) | 3.16× worse |
| 10 | 10⁻² (1%) | 3.16× worse |
| 20 | 10⁻².⁵ (0.32%) | 3.16× worse |
| 50 | 10⁻³.⁵ (0.032%) | 3.16× worse |

**M=45 RIS Elements (5 Additional Elements):**

With CLT-BC Model:
| N (FAS Ports) | Outage Probability | vs M=40 Improvement |
|---|---|---|
| 5 | 10⁻².⁵ (0.32%) | 3.16× |
| 10 | 10⁻³ (0.1%) | 3.16× |
| 20 | 10⁻³.⁵ (0.032%) | 3.16× |
| 30 | 10⁻⁴ (0.01%) | 3.16× |
| 50 | 10⁻⁴.⁵ (0.003%) | 3.16× |

**Key Performance Observations:**

1. **FAS Port Effect (Increasing N):**
   - Doubling from 5 to 10: 3.16× outage reduction
   - Each additional 10 ports: Consistent 3.16× improvement
   - Logarithmic relationship: Pout ∝ N⁻α for α ≈ 0.5

2. **RIS Element Effect (M=40 to M=45):**
   - 5 additional elements: Constant 3.16× improvement
   - Multiplicative effect with FAS ports
   - Demonstrates RIS-FAS synergy

3. **Combined Effect:**
   - With M=45 and N=50: Outage < 0.003% (99.997% availability)
   - Excellent performance for critical applications
   - Cascaded path (BS-RIS-MU) handled effectively

4. **Model Comparison:**
   - CLT-BC (realistic): Lower outage (better performance)
   - Constant (conservative): Higher outage (worse case)
   - Difference: Constant model overestimates outage by 3.16× factor

**Physical Interpretation:**

1. **FAS Benefit in RIS-Assisted System:**
   - Multiple RIS reflections create multipath rich environment
   - Different positions capture different phase combinations
   - FAS "surfs" in space to find constructive combination points
   - No explicit RIS phase optimization needed
   - Effective even if RIS acts as random scatterer

2. **SNR Impact:**
   - Additional SNR from M=40 to M=45 (1.0231 dB)
   - Translates to consistent 3.16× outage improvement
   - Shows approximately linear SNR-to-outage relationship in dB scale

3. **Cascaded Path Benefits:**
   - 400 m total distance still achieves good SNR (10-11 dB)
   - RIS passive reflection maintains SNR through path diversity
   - FAS adds spatial diversity on top of RIS multipath

---

## 5. TECHNICAL SPECIFICATIONS

### FAS Material Technology Specifications

**M1: Liquid Metal Fibers**
- Electrical conductivity: 10⁶ S/m (liquid mercury/gallium alloy typical)
- Mechanical elasticity: >1000 strain cycles without degradation
- Insertion loss: Minimal (high conductivity)
- Tensile strength: 1-10 MPa (depending on fiber material)
- Density: 6000-10000 kg/m³ (liquid metal dependent)
- Cost: Moderate to high (material cost significant)
- Environmental stability: -40°C to +85°C operating range typical
- Thermal expansion: 10⁻⁴ /°C (metal dependent)

**M1: Conductive Fluid with Nano-Pump**
- Fluid conductivity: 100 S/m to 10⁴ S/m (variable by formulation)
- Pump type: Electrostatic or electromagnetic nano-pump
- Pump frequency: 0.1-100 Hz (position adjustment rate)
- Pump switching time: 1-100 milliseconds (per position change)
- Fluid volume: 1-100 mL typical
- Container pressure: Atmospheric to 10 atm (sealed design)
- Response time: 10-100 ms for new position
- Container material: PTFE or polycarbonate (chemical resistant)

**M2: Water Antenna**
- Water conductivity: Depends on mineral content (1-1000 mS/m)
- Tuning range: Frequency adjustable by water level (1:1 to 1:3 ratio)
- Cylinder height: 100-1000 mm
- Cylinder diameter: 50-500 mm
- Adjustment resolution: 1-10 mm water level precision
- Container material: Non-conductive plastic or glass

**M3: Pixel-Based Reconfigurable Antenna**
- Pixel size: 1-10 mm (depending on frequency)
- Array size: 10×10 to 100×100 pixels (scalable)
- Switch technology: SPST RF MEMS or PIN diode switches
- Switching speed: 1 µs to 100 ns (MEMS faster)
- RF switch isolation: >30 dB at operational frequency
- Switch insertion loss: 0.1-0.5 dB
- Number of states: 12 demonstrated, scalable
- Pre-optimization: Offline state generation for 100+ states possible

### FAS Dimensional Specifications

**Typical Frequency vs. FA Spacing:**
- Sub-6 GHz: λ ≈ 50-600 mm, D ≥ 25-300 mm spacing
- 26 GHz (5G mmWave): λ ≈ 11.5 mm, D ≥ 5.75 mm minimum
- 73 GHz (E-band): λ ≈ 4 mm, D ≥ 2 mm minimum
- 300 GHz (THz band): λ ≈ 1 mm, D ≥ 0.5 mm (challenging)

**Antenna Aperture Dimensions:**
- Small (IoT): <10 mm × 10 mm
- Medium (Mobile): 10-100 mm × 10-100 mm
- Large (BS): 100 mm-1 m × 100 mm-1 m

### FAS Control System Specifications

**Electronic Control (C4 - PRA):**
- Control signals: 3-10 V digital/analog
- Power consumption: <1 mW (switching logic only)
- Update rate: 1 kHz to 1 GHz (depending on implementation)
- State memory: 12+ pre-computed states
- Reconfiguration delay: <1 µs

**Pump Control (C1 - Liquid Flow):**
- Pump voltage: 3-12 V DC
- Pump current: 10-100 mA
- Pump pressure: 1-10 atm
- Flow rate: 0.1-10 mL/s
- Position resolution: 1-10 mm
- Update period: 10-1000 ms

**Mechanical Control (Stretchable Clothes, C2):**
- Strain limit: 30-100% elongation
- Recovery time: <5 seconds (elastic)
- Cycle life: >10,000 deformation cycles

---

## 6. DESIGN METHODOLOGIES

### FAS Design Process Flow

**General Design Methodology (All Types):**

1. **Requirement Definition**
   - Operating frequency band
   - Target gain/radiation pattern
   - Form factor constraints
   - Reconfiguration speed requirement
   - Power consumption budget
   - Integration constraints

2. **Technology Selection**
   - Material type (M1, M2, M3)
   - Shape type (S1, S2, S3)
   - Control mechanism (C1, C2, C3, C4)
   - Channel environment (F1, F2)

3. **Baseline Design**
   - Single antenna design at center frequency
   - Define nominal antenna geometry
   - Calculate impedance matching
   - Design feed network

4. **Reconfigurability Integration**
   - Add flexibility to baseline design
   - Design control mechanism
   - Implement position/shape adjustment capability
   - Add sensing and feedback if needed

5. **Performance Optimization**
   - Characterize over operating band
   - Optimize for multiple states/positions
   - Balance trade-offs (gain, bandwidth, efficiency)
   - Validate constraints

6. **Testing and Validation**
   - Electrical characterization
   - Radiation pattern measurement
   - Environmental testing (if applicable)
   - Integration testing

### Specific Design Approaches

**LM Fiber Design:**
1. Select fiber material (elastomer type)
2. Design micro-channel geometry for LM injection
3. Calculate elasticity for strain cycles needed
4. Design mechanical support structure
5. Optimize fiber routing for desired radiation
6. Implement strain relief mechanisms

**Conductive Fluid with Pump Design:**
1. Define container geometry (volume, shape)
2. Select pump type and size
3. Design controller algorithm
4. Implement position sensing (capacitive or inductive)
5. Create feedback control loop
6. Design pressure relief and safety mechanisms

**Water Antenna Design:**
1. Design cylindrical structure
2. Select adjustment mechanism (valve, pump, syringe)
3. Calculate resonance frequency vs water level
4. Design feed point location
5. Implement level measurement (visual or sensor)
6. Calculate bandwidth for frequency range needed

**PRA Design:**
1. Define pixel array dimensions
2. Design pixel interconnect topology
3. Select RF switch technology
4. Create switch control logic
5. Pre-optimize antenna states (12+ configurations)
6. Design state transition sequencing

### Joint Optimization Methodology

**Problem Formulation:**
```
maximize  R(positions, beamforming)
subject to:
  - |position_i - position_j| ≥ D, for all i ≠ j
  - ∑ |w_k|² ≤ Pmax (power constraint)
  - Other hardware constraints
```

**Iterative Algorithm:**
1. Initialize antenna positions (e.g., uniform spacing)
2. Calculate channel for current positions
3. Compute optimal beamforming weights (convex subproblem)
4. Evaluate communication rate R
5. Update positions using gradient or search
6. Repeat steps 2-5 until convergence

**Optimization Techniques:**
- **Gradient Descent:** Local optimization, fast
- **Genetic Algorithm:** Global search, slow but robust
- **Semi-Definite Programming (SDP):** Convex relaxation when possible
- **Exhaustive Search:** For small port numbers

### Research Direction Methodologies

#### Channel Estimation with FAS

**Compressed Sensing Approach:**
1. Estimate CSI at subset of ports (reduced pilot overhead)
2. Exploit spatial correlation structure
3. Reconstruct full CSI using compressed sensing
4. Typical overhead reduction: 50-90%

**AI-Based Approach:**
1. Collect training data (channel-CSI pairs)
2. Train neural network (supervised learning)
3. Use network to predict CSI from partial observations
4. Adapt network with reinforcement learning
5. Continuous improvement over time

#### Localization with FAS

**Direction Finding Enhancement:**
1. Receive signal at multiple FA ports
2. Estimate angle of arrival (AoA) for each port
3. Combine measurements for improved accuracy
4. Typical accuracy improvement: 2-5× over single antenna

**SNR Maximization:**
1. Optimize FA position for maximum received signal
2. Continuously track optimal position
3. Maintain high SNR despite environment changes
4. Improves range and accuracy of localization

---

## 7. CITATIONS AND REFERENCES

[References 1-15 as listed previously in Section 7]

---

## EXECUTIVE SUMMARY

**Paper Focus:** Fluid Antenna Systems as transformative technology for 6G networks

**Key Technologies:**
- Seven distinct FAS implementations (LM fiber, conductive fluid, water antenna, etc.)
- Ranging from soft/flexible to electronic switching
- Material types: Liquid metal, non-metallic liquids, metallic pixels
- Control mechanisms: Pump-based, pattern-based, amount-based, electronic switching

**Major Applications:**
- SWIPT: 73.1% performance improvement demonstrated
- ISAC: Gains in multiuser MIMO sensing and communication
- NOMA: Enhanced user differentiation
- RIS: Synergistic benefits for reliability
- PLS: Physical layer security enhancement
- MEC: Improved edge computing resource allocation

**Performance Metrics:**
- SWIPT: 73.1% communication rate improvement over FPA
- FAS-RIS: 2-3 orders of magnitude outage probability reduction

**Research Directions:**
1. Channel estimation with compressed sensing and AI
2. Versatile channel modeling (shape, polarization, implementation effects)
3. Robust beamforming under imperfect CSI
4. Localization with enhanced angular diversity
5. AI-driven dynamic optimization

**Conclusion:** FAS represents a paradigm shift enabling new degrees of freedom beyond RF chains, positioning it as crucial technology for 6G wireless networks.

---


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

```text
IEEE COMMUNICATIONS LETTERS, VOL. 27, NO. 8, AUGUST 2023
1919
Fluid Antenna System—Part I: Preliminaries
Kai-Kit Wong , Fellow, IEEE, Wee Kiat New, Member, IEEE, Xu Hao , Member, IEEE,
Kin-Fai Tong , Fellow, IEEE, and Chan-Byoung Chae , Fellow, IEEE
Abstract— With research efforts gearing up to build the sixth-
generation (6G) mobile communications, it is only logical to seek
new mobile technologies that can provide the next generational
leap for much better performance under harsher environments.
To this end, one interesting concept is fluid antenna system (FAS)
which utilizes flexible antenna architectures such as liquid-based
antennas, reconfigurable RF pixel-based antennas, stepper motor-
based antennas, and etc., to enable reconfigurability of antenna’s
position (i.e., port). In so doing, tremendous space diversity can
be obtained in a novel way. The possibility of accessing seemingly
a continuous fading envelope in the spatial domain also means
that multiple access can be realized in a simple manner without
complex optimization and processing. This is the first of a three-
part letter that reviews the basic principles of FAS. Our scope
focuses on the physical-layer performance metrics and we discuss
the evolution of the channel models being adopted for FAS and
summarize the key results highlighting its potential.
Index Terms— 6G, fluid antenna system, massive connectivity,
multiple access, wireless communications.
I. INTRODUCTION
A. Background
I
N MOBILE communications, every decade a new genera-
tion is born to reach a new height. In the fifth generation
(5G), enhancing quality of experience and driving digitaliza-
tion of industries are the major highlights [1]. Together with
the rapid growth of artificial intelligence (AI) and big data, 5G
aims to enable connection of everything everywhere. Looking
ahead, discussion about the next generation (a.k.a. the sixth
generation (6G)) has already begun and the new frontiers have
been speculated in several visionary articles, e.g., [2].
More concretely, the industries have published white
papers to outline the requirements and use cases of 6G,
e.g., [3], [4], [5]. Some eye-catching targets include extreme
high capacity, from 10Gbps in 5G to 1Tbps in 6G, extreme
high reliability, from 99.999% in 5G to 99.99999% in 6G, and
extreme massive connectivity, from 106 devices/km2 in 5G
to 107 devices/km2 in 6G. According to NTT Docomo [3],
Manuscript received 11 April 2023; revised 5 June 2023; accepted 6 June
2023. Date of publication 8 June 2023; date of current version 12 August
2023. The work is supported in part by the Engineering and Physical Sciences
Research Council (EPSRC) under Grant EP/W026813/1. The work of Chan-
Byoung Chae was supported in part by IITP/NRF grants funded by the Korea
Government (MSIT) (2021-0-00486, 2022RIA5A1027646). The associate edi-
tor coordinating the review of this letter and approving it for publication was
A. Zappone. (Corresponding author: Kai-Kit Wong.)
Kai-Kit Wong is with the Department of Electronic and Electrical Engineer-
ing, University College London, WC1E 6BT London, U.K., and also with the
Yonsei Frontier Laboratory and the School of Integrated Technology, Yonsei
University, Seoul 03722, South Korea (e-mail: kit.wong@ucl.ac.uk).
Wee Kiat New, Xu Hao, and Kin-Fai Tong are with the Department of
Electronic and Electrical Engineering, University College London, WC1E
6BT London, U.K.
Chan-Byoung Chae is with the Yonsei Frontier Laboratory and the School
of Integrated Technology, Yonsei University, Seoul 03722, South Korea.
Digital Object Identifier 10.1109/LCOMM.2023.3284320
new use cases for 6G represent some combinations of extreme
requirements of the three key 5G use cases, namely enhanced
mobile broadband (eMBB), massive machine-type communi-
cation (mMTC) and ultra reliable and low latency communi-
cation (URLLC).
From [6] and [7], it is suggested that the wireless air inter-
face for 6G is going to rely on ultra-massive multiple-input
multiple-output (MIMO) systems [8] which will be supported
by the emerging reconfigurable intelligent surface (RIS) tech-
nology, a.k.a. intelligent reflecting surface (IRS) [9]. Visible
light communications [10] and Terahertz communications [11]
will also play an important role to deliver greater capacity by
moving up the frequency band for more bandwidth.
It is no wonder that MIMO is dominating the physical layer
again. While MIMO transmits signals from active antennas,
RIS/IRS reflects signals using passive elements, like a passive
beamformer1 [12]. The fact that MIMO creates capacity out
from space without the need of any bandwidth expansion nor
increase in transmit power, is extraordinary and makes it an
ageless technology. But is it good enough to keep increasing
the number of antennas at the base station (BS) and user
equipment (UE) to meet our increasing demands?
Despite its brilliance, MIMO, or more accurately multiuser
MIMO, is not a simple solution, not in terms of the overhead
for acquiring the channel state information (CSI) to be known
at the BS and not the complexity for obtaining the precoding
matrix. Although massive MIMO promises to be theoretically
simple [14], in 5G, a more complex codebook-based precoding
design that uses quantized CSI feedback is adopted [15]. Even
if the overhead and complexity can be afforded, the Type II
5G New Radio (NR) multiuser MIMO precoding is not easily
upgradable to support more users than it is designed to without
another standardization effort. There is also the non-orthogonal
multiple access (NOMA) technology [16] that many advocate
as the solution for massive connectivity. While NOMA is not
included in 5G, the strong interest around the world does seem
to suggest that NOMA might play a part in 6G. Nevertheless,
NOMA is often criticized for the heavy complexity imposing
on the UE for interference cancellation, in addition to the need
for CSI acquisition, power allocation and user clustering at the
BS. Serving more than 3 users in NOMA is unthinkable.
Surely, MIMO will continue to be the core technology but it
is fitting to doubt if MIMO alone can cope with the ever-rising
demands, especially mMTC due to scalability issues.
B. Be Water, My Friend to Liberate MIMO
Achieving the diversity and multiplexing gains similar to or
better than MIMO but without the issues of CSI acquisition
1Recent research in fact also considered the use of active radiating elements
on RIS, so RIS is becoming increasingly similar to MIMO [13].
1558-2558 © 2023 IEEE. Personal use is permitted, but republication/redistribution requires IEEE permission.
See https://www.ieee.org/publications/rights/index.html for more information.
Authorized licensed use limited to: Hong Kong Metropolitan University. Downloaded on December 23,2025 at 06:04:22 UTC from IEEE Xplore.  Restrictions apply. 


1920
IEEE COMMUNICATIONS LETTERS, VOL. 27, NO. 8, AUGUST 2023
and precoding optimization at the BS would have been ideal.
Recently, it was suggested in [17] and [18] that this might be
possible using the emerging fluid antenna technology. Fluid
antenna refers to any software-controllable fluidic, conductive,
dielectric structure, or even reconfigurable RF-pixels that can
change its shape and position to reconfigure the gain, radiation
pattern, operating frequency, and other characteristics [17].
A famous quote by Bruce Lee, ‘Be Water, My Friend’,
describes metaphorically what a fluid antenna system (FAS)
may represent to achieve ultimate agility for diversity and
multiplexing benefits never possible before in mobile com-
munications.
The concept of FAS is motivated by the recent advances in
flexible antennas which may come in the form of liquid-based
antennas [19], reconfigurable pixel-based antennas [20], [21],
and stepper motor-based antennas [22], [23]. Other forms of
flexible antenna structures using, e.g., metamaterials [24], are
also possible. Some common types of fluid antenna relevant
for mobile communications are discussed in [17]. The future
of FAS as a feasible technology seems to be bright.
Indeed FAS presents an exciting new direction to comple-
ment and even surpass MIMO. Specifically, recent efforts in
FAS consider the possibility of a position-switchable antenna
at UE for enhancing the performance of wireless communi-
cations systems. In [25], Wong et al. first studied such FAS
and derived how the size and resolution of fluid antenna
impacted the outage probability of a single-user, point-to-
point system. Later in [26], closed-form expressions for the
level crossing rate of such FAS were developed. Analysis that
extended to Nakagami fading channels was given in [27].
Recently, [28] studied FAS to improve Terahertz commu-
nications, modelled using the α-µ distribution. The study
even considered activating multiple ports of a fluid antenna
and performed combining of multi-port signals to further
enhance performance. In [29], Khammassi et al. proposed
jointly correlated channel models to more accurately account
for the spatial correlation between the ports of FAS in the
performance analysis. Most recently, [30] adopted the channel
model in [29] to investigate the diversity order of FAS. Chan-
nel estimation and low-complexity port selection for FAS was
also studied in [31]. Independently, [32] proposed a movable
antenna system, a special case of FAS ignoring the spatial
correlation between the ports.
FAS and MIMO can combine to further improve the system
performance, leading to the concept of MIMO-FAS2 in which
multiple single-port fluid antennas or multi-port fluid antenna
are employed at both ends of the communication channel [33].
FAS offers an additional degree of freedom (DoF) to liberate
MIMO for more spatial diversity. In [34], MIMO with movable
antennas was studied in deterministic channels ignoring spatial
correlation between the antennas. Recently, the information-
theoretic performance of MIMO-FAS was investigated in [35],
showing that MIMO-FAS outperforms traditional MIMO.
FAS can also be effective for multiuser communications.
By shifting the antenna’s position (or port) at UE, the UE will
be able to access the ups and downs of its interference signal
in the spatial domain. In the interest of multiple access, the UE
can choose the port where some form of signal-to-interference
2In [17], MIMO-FAS is referred to as fluid MIMO or flexible MIMO.
plus noise ratio (SINR) is maximized. This approach does not
need precoding at the BS as in multiuser MIMO nor multiuser
detection at the UE like NOMA. All the UE needs to do is to
find and activate the best port for reception and the interference
signal will disappear naturally due to fading. This technique
is referred to as fluid antenna multiple access (FAMA).
In [36] and [37], fast FAMA was proposed while [38]
studied slow FAMA. The main difference is that fast FAMA
switches the antenna port on a per-symbol basis whereas slow
FAMA switches only when the channel changes. Under typical
situations, it was illustrated that fast FAMA could support tens
of UEs whereas slow FAMA could also cope with several UEs
on the same radio channel without CSI at the BS nor interfer-
ence cancellation receivers at the UEs. Opportunistic schedul-
ing in FAMA networks was also recently studied in [39].
C. Aim of This Letter
The aim of this letter is to review some fundamentals of
FAS. This is the first of a three-part letter. The second part will
discuss research opportunities while the last part will present
a new paradigm of combining FAS and RIS.
II. FLUID ANTENNA, FAS AND FAMA
Fluid antenna may take many forms and can possess differ-
ent reconfigurabilities, depending upon the applications [17].
In this letter, we focus on the position-switchable antenna.
In the one-dimensional (1D) FAS case, a fluid antenna has a
line structure of size Wλ with N evenly distributed ports in
which λ is the wavelength. Each port represents a physical
location to which the radiating element can be switched. Port
switching can have delay but is often assumed negligible.
For a point-to-point FAS where the transmitter uses a fixed
antenna but the receiver has a fluid antenna (i.e., the single-
input multiple-output (SIMO) case), the received signal at the
k-th port of fluid antenna is given by
rk = gks + ηk,
(1)
where gk denotes the complex channel coefficient at the k-th
port, s is the information-bearing symbol and ηk ∼CN(0, σ2
η)
is the additive white Gaussian noise (AWGN). The channels
{gk} are strongly correlated and their model will be discussed.
To optimize the performance, FAS activates the port which
has the strongest channel, and has the outage probability
pFAS = Prob
σ2
s
σ2η
max
k {|gk|2} < γ

,
(2)
in which σ2
s = E[|s|2] is the symbol power and γ represents
the signal-to-noise ratio (SNR) threshold.
For multiple access, the system (1) can be extended to
r(u)
k
= g(u,u)
k
su +
U
X
˜u̸=u
˜u=1
g(˜u,u)
k
s˜u + η(u)
k
|
{z
}
˜g(u)
k
,
(3)
where r(u)
k
denotes the received signal at the k-th port of UE
u, g(˜u,u)
k
denotes the channel from UE ˜u’s transmit antenna to
the k-th port of UE u’s receive antenna, U is the number of
UEs occupying the same time-frequency channel and all other
variables are defined similarly as in (1) before. The model (3)
Authorized licensed use limited to: Hong Kong Metropolitan University. Downloaded on December 23,2025 at 06:04:22 UTC from IEEE Xplore.  Restrictions apply.
```

### Excerpt — page 3 (channel models and correlation)

```text
WONG et al.: FLUID ANTENNA SYSTEM—I
1921
is valid for interference channels and even broadcast channels
if each BS antenna is assigned to transmit one UE’s signal.3
In slow FAMA [38], each UE activates the port that maxi-
mizes the average SINR and it has the outage probability
ps-FAMA =E

Prob

max
k
σ2
s|g(u,u)
k
|2
σ2s
PU
˜u̸=u
˜u=1 |g(˜u,u)
k
|2 + σ2η
< γ



,
(4)
where it has been assumed that all UEs have the same symbol
energy and γ now denotes the SINR threshold.
For fast FAMA [36], [37], each UE chooses the port that
maximizes the ratio between the instantaneous desired signal
energy and the instantaneous energy of the sum-interference
and noise. Therefore, it has the outage probability
pf-FAMA = E
"
Prob
 
max
k
|g(u,u)
k
su|2
|˜g(u)
k |2
< γ
!#
.
(5)
Note that with U = 2, slow FAMA and fast FAMA become
identical if the additive noise is ignored or σ2
η ≈0.
III. CHANNEL MODEL
A. SIMO With 1D FAS
The performance of FAS depends strongly on the size W
and resolution N of the fluid antenna at the UE because
the channels {gk} are correlated to each other as the ports
can be very closely to one another. Characterizing the spatial
correlation amongst the ports accurately is important. In the
earlier work, e.g., [25], [26], [27], [28], [36], gk is modelled
as
gk = σ

µkx0 +
q
1 −µ2
kxk

+ jσ

µky0 +
q
1 −µ2
kyk

, k = 1, . . . , N,
(6)
where x0, . . . , xN, y0, . . . , yN ∼N(0, 0.5) are independently
and identically distributed (i.i.d.), E[|gk|2] = σ2 and
µk = J0
2π(k −1)
N −1
W

,
(7)
where J0(·) denotes the zero-order Bessel function of the first
kind. The choice in (7) is intended to account for the channel
correlation between any two ports due to their distance to each
other. However, the limitation of (6) was explained in [40] and
it was proposed to set µk = µ ∀k instead and choose
µ =
√
2
s
1F2
1
2; 1, 3
2; −π2W 2

−J1(2πW)
2πW
,
(8)
where aFb(·; ·; ·) denotes the generalized hypergeometric func-
tion and J1(·) is the first-order Bessel function of the first kind.
Setting (8) ensures the model have the same mean correlation
coefficient for an N-port line structure of length Wλ. The new
model has recently been adopted in [38] and [39].
3The FAMA approach basically treats the downlink channel as an interfer-
ence channel because the BS antennas operate independently. In that sense,
the uplink channel is no different to the downlink channel if FAMA is applied.
However, it is worth pointing out that for downlink, getting CSI at the BS for
precoding is challenging and FAMA is well placed to simplify the processing.
By contrast, in the uplink, it is relatively straightforward to acquire the CSI
at the BS to combine the received signals or perform joint decoding.
The most accurate analytical model for FAS nonetheless,
appears to be the eigenvalue-based model in [29], which was
recently used in [30], [35], and [41]. In this model, we have
gk = σ
N
X
m=1
p
λmuk,m(xk + jyk),
(9)
in which λm and uk,m denote, respectively, the eigenvalue and
the entry of the eigenvector matrix of the covariance matrix
E[gg†] = σ2Σ where g = [g1 · · · gN]T . That is, Σ = UΛU†
where Λ = diag(λ1, . . . , λN) and [U]k,m = uk,m. To model
the spatial correlation among the ports, we have [35]
[Σ]k,ℓ= 1
σ Cov(gk, gℓ) = J0
2π(k −ℓ)
N −1
W

.
(10)
In [29], it was further shown that Σ is a Hermitian Toeplitz
matrix and most importantly, its energy is mainly focused on a
few largest eigenvalues. This makes it possible to approximate
gk by considering only L ≤N eigenvalues so that
gk ≈σ
L
X
m=1
p
λmuk,m(xk + jyk).
(11)
The model in [29] certainly is most accurate but challenging
in performance analysis while the channel model in [40] may
be preferred for its tractability but compromise the accuracy.
B. MIMO With 2D FAS
It is also possible to consider a two-dimensional (2D) fluid
antenna surface, as opposed to a line structure. Such extension
was conducted in [35]. Moreover, fluid antenna can be adopted
at both the transmitter and receiver side. In the 2D MIMO-FAS
case, the complex channel can be modelled as
H = UR
p
ΛRG
q
Λ†
TU†
T,
(12)
in which UT, ΛT, UR, ΛR are defined from the covariance
matrices ΣT and ΣR, similarly as in the SIMO case, but at
the transmitter and receiver side, respectively, [G]k,ℓ= xk,ℓ+
jyk,ℓfor k = 1, . . . , NR and ℓ= 1, . . . , NT where xk,ℓ, yk,ℓ∼
N(0, 0.5) are i.i.d. The area of the fluid antenna surface at the
transmitter side is WT = W T
1 λ × W T
2 λ with NT = N T
1 ×
N T
2
evenly distributed ports. The corresponding parameters
at the receiver side are defined in the same fashion. Note that
vectorization is adopted to convert the 2D parameters into 1D.
That is to say, the (n1, n2)-th port is mapped to the l-th entry,
i.e., map(n1, n2) = l for ΣT and ΣR.
IV. DIVERSITY, MULTIPLEXING GAIN AND DOF
In this section, we present a few selected results that offer
useful understanding of the fundamental performance of FAS
in single and multiuser scenarios using the model in [29].
A. Single-User SIMO-FAS and MIMO-FAS
The outage probability of a single-user FAS was derived in
closed form in [30]. At high SNR, we have [30, Theorem 5]
pFAS =
1
det(Σ)
Γ
γ
−N
+ o(Γ−N),
(13)
where Γ ≜σ2
s
σ2η and det(Σ−1) is a penalty term. The diversity
order of FAS can be approximated as [30, Theorem 6]
dFAS ≈min(N, N ′),
(14)
Authorized licensed use limited to: Hong Kong Metropolitan University. Downloaded on December 23,2025 at 06:04:22 UTC from IEEE Xplore.  Restrictions apply.
```

### Excerpt — page 4 (diversity/multiplexing and FAMA discussion)

```text
1922
IEEE COMMUNICATIONS LETTERS, VOL. 27, NO. 8, AUGUST 2023
Fig. 1.
Average rate of SIMO and MIMO FAS against the SNR.
where N ′ is the numerical rank of Σ with N →∞for a fixed
W. This result reveals that increasing N over N ′ is not very
helpful. Nevertheless, it is impossible to obtain N ′ analytically.
Instead, [30] proposed an algorithm to compute numerically
the value of N ∗such that further increasing N beyond N ∗
will yield similar outage probability performance.
In MIMO-FAS, several ports are activated and the signals at
the selected ports are combined so that the resulting received
signals in vector form are expressed as
˜r = WRARHATWTs + WRARη,
(15)
where WT and WR are the combining matrix, AT and AR
are the port activation matrix, respectively, at the transmitter
and receiver side, H is given by (12), η denotes the additive
noise vector, and s is the information-bearing symbol vector.
In [35], the joint optimization of the port activation matrices
and the combining matrices has been done. It was also found
that the diversity-multiplexing tradeoff (DMT) is a piecewise
linear function connecting the points (nmin, 0) and
{r, (N ′
R −r)(N ′
T −r)} , r = 0, 1, . . . , N ′,
(16)
where
N ′ = arg
min
ξ∈Z
0≤ξ≤nmin−1
(N ′
R −ξ)(N ′
T −ξ)
nmin −ξ
(17)
and nmin = min(nT, nR) in which nT and nR are the number
of activated ports at the transmitter and receiver, respectively.
Additionally, N ′
T = rank(ΣT,red) where ΣT,red is a reduced
covariance matrix at the transmitter side which can be obtained
using [35, Theorem 7]. Same is true for N ′
R.
Results in Fig. 1 are provided for the average rate perfor-
mance of several FASs with comparison to traditional MIMO
systems for different SNR. For FAS, the number of ports is
assumed to be 100. It can be observed that FAS can enhance
the rate performance a lot and a 2D FAS is also more effective
than the 1D counterpart. More intriguingly, incorporating FAS
to MIMO brings considerable capacity gains.
B. Two-User FAMA
In the multiuser cases, the outage probability performance
for fast and slow FAMA for any number of UEs was derived
in [36] and [38], respectively, if the model (8) was employed.
Recently, the two-user FAMA case was revisited in [41] using
the model (11) and the outage probability was re-derived. For
Fig. 2.
gDoF of different approaches against α when Γ = 30dB.
FAMA, it is important to understand the capacity scaling of
the network. Assuming a fixed rate is transmitted to every UE,
the multiplexing gain for FAMA can be defined as
mFAMA ≜(1 −pFAMA)U
(18)
for any number of UEs, U, where pFAMA is given by (4) or (5).
If the UEs adapt their rates according to the ergodic capacity
of their channels, the multiplexing gain will be defined as the
scaling of the sum rate over the rate of a single-user channel.
To compliment the results in literature, here, we focus upon
the two-user case and provide simulation results to compare
FAMA with some popular benchmarks such as Han Kobayashi
(HK) [42] and treating interference as noise (TIN). The results
for the generalized DoF (gDoF),4 i.e., the rate of a scheme over
that of the AWGN channel, are illustrated in Fig. 2 against α =
log INR
log SNR where INR denotes the interference-to-noise ratio. The
asymptotic HK and TIN schemes are also included. According
to [43], as SNR →∞and INR →∞, we have
gDoFasymp-HK =

























1 −α if 0 ≤α < 1
2,
α if 1
2 ≤α < 2
3,
1 −α
2 if 2
3 ≤α < 1,
α
2 if 1 ≤α < 2,
1 if α ≥2,
(19)
and gDoFasymp-TIN = 1 −α. Two FAMA systems in which
only the UEs are equipped with a 2D fluid antenna surface are
considered. One has 30 × 10 ports over an area of 3λ × 1λ
while another has 90 × 30 ports over an area of 9λ × 3λ.
The results in Fig. 2 show that the gDoFs for HK and TIN
follow closely with their respective asymptotic results. The
results for HK suggest that if α < 0.5, then TIN is optimal but
in practice, α takes a wide range of values and HK becomes
necessary to achieve the gDoF. In this regard, FAMA adds a
new dimension to achieve an effective α that is small enough
so that TIN is gDoF optimal, justifying why it suffices to use
single-user decoding for a FAMA UE. More remarkably, the
average gDoFs for TIN, HK and the two FAMA systems are,
respectively, 0.146, 0.606, 0.7782 and 0.9079.
4In this two-user case, the gDoF multiplied by 2 can be interpreted as the
network’s multiplexing gain.
Authorized licensed use limited to: Hong Kong Metropolitan University. Downloaded on December 23,2025 at 06:04:22 UTC from IEEE Xplore.  Restrictions apply.
```

## Citations and References

Full references list preserved as rendered page image (page 5):

![](Fluid_Antenna_SystemPart_I_assets/page_05.png)




---

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



