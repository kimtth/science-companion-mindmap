# General Physics Overview

## 🎯 Purpose
This mindmap provides a comprehensive overview of college-level physics, covering fundamental concepts from classical mechanics to modern quantum physics. It serves as a visual learning tool to understand the hierarchical relationships between physical concepts and their applications.

## 📚 Main Topics

### 1. Mechanics
The foundation of physics, dealing with motion and forces. Mechanics is divided into kinematics (describing motion) and dynamics (explaining motion through forces). This section covers:
- **Kinematics**: Describes how objects move (position, velocity, acceleration)
  - Vector nature of motion in multiple dimensions
  - Calculus-based approach: derivatives and integrals of motion
  - Projectile motion combines independent horizontal and vertical components
- **Dynamics**: Explains why objects move (Newton's laws, forces)
  - Inertial reference frames vs non-inertial frames
  - Free-body diagrams as problem-solving tools
  - Friction as a non-conservative force
- **Energy & Work**: Fundamental concept of energy conservation
  - Work-energy theorem connects force and energy
  - Conservative vs non-conservative forces
  - Potential energy landscapes and equilibrium
- **Rotational Motion**: Angular equivalents of linear motion
  - Every linear quantity has a rotational analog
  - Parallel axis and perpendicular axis theorems
  - Rolling motion combines translation and rotation
- **Gravitation**: Universal force governing planetary motion
  - Inverse square law and field theory
  - Gravitational potential energy and escape velocity
  - Kepler's laws derived from Newton's law
- **Fluid Mechanics**: Behavior of liquids and gases
  - Continuity equation from mass conservation
  - Bernoulli's equation from energy conservation
  - Viscosity and turbulence in real fluids

**Physical Insights**:
- Newton's laws are valid only in inertial reference frames
- Energy conservation is more fundamental than Newton's laws (works in quantum mechanics)
- Symmetries in physics lead to conservation laws (Noether's theorem)
- Friction converts mechanical energy to thermal energy (entropy increase)

**Key Applications**: Engineering design, sports physics, vehicle dynamics, aerospace, robotics, biomechanics

### 2. Waves & Oscillations
Studies periodic motion and wave phenomena. Oscillations are repeated motions about equilibrium, while waves are propagating disturbances that transfer energy without transferring matter:
- **Simple Harmonic Motion (SHM)**: Springs, pendulums, oscillators
  - Restoring force proportional to displacement: F = -kx
  - Sinusoidal solutions: x(t) = A cos(ωt + φ)
  - Energy oscillates between kinetic and potential
  - Damped oscillations: exponential decay with friction
  - Driven oscillations and resonance phenomena
- **Wave Properties**: Amplitude, frequency, wavelength, interference
  - Transverse (perpendicular) vs longitudinal (parallel) waves
  - Wave equation: ∂²y/∂t² = v²∂²y/∂x²
  - Superposition principle: waves add linearly
  - Standing waves from boundary conditions
- **Sound Waves**: Mechanical longitudinal waves requiring a medium
  - Pressure variations propagating through matter
  - Speed depends on medium elasticity and density
  - Human hearing: 20 Hz to 20 kHz
  - Beat frequency: |f₁ - f₂| from superposition
- **Interference**: Wave superposition creating patterns
  - Constructive: crests align (path difference = nλ)
  - Destructive: crest meets trough (path difference = (n+½)λ)
  - Double-slit demonstrates wave nature of light
- **Resonance**: Maximum amplitude at natural frequency
  - Energy builds up with periodic forcing
  - Critical for structures (bridges, buildings)
  - Quality factor Q measures sharpness of resonance

**Physical Insights**:
- SHM arises whenever restoring force is proportional to displacement
- All waves carry energy and momentum, but not matter
- Wave-particle duality: all matter exhibits wave properties
- Fourier analysis: any periodic function is sum of sinusoids

**Key Applications**: Musical instruments, seismology, acoustic engineering, telecommunications, medical ultrasound, radar

### 3. Thermodynamics
The science of heat, energy transfer, and the fundamental limits on energy conversion. Thermodynamics is based on empirical laws that apply to macroscopic systems:
- **Temperature & Heat**: Thermal energy and its transfer mechanisms
  - Temperature measures average kinetic energy of particles
  - Heat is energy transfer due to temperature difference
  - Zeroth law: thermal equilibrium is transitive (defines temperature)
  - Three modes of heat transfer: conduction (direct contact), convection (fluid motion), radiation (EM waves)
  - Thermal equilibrium and thermometers
- **First Law**: Energy conservation in thermal systems
  - ΔU = Q - W: energy can change form but not be created/destroyed
  - Internal energy U is a state function (path-independent)
  - Work done by gas: W = ∫P dV
  - Specific heat capacities: Cₚ > Cᵥ for gases
- **Second Law**: Entropy and the direction of natural processes
  - Entropy S measures disorder/number of microstates
  - ΔS_universe ≥ 0: entropy of isolated system increases
  - Heat flows spontaneously from hot to cold
  - No perfect heat engine (efficiency < 100%)
  - Statistical interpretation: systems evolve toward most probable states
- **Third Law**: Absolute zero and perfect crystals
  - S → 0 as T → 0 K for perfect crystal
  - Absolute zero is unattainable
- **Heat Engines**: Converting thermal to mechanical energy
  - Efficiency: e = W/Q_h = 1 - Q_c/Q_h
  - Carnot cycle: maximum efficiency = 1 - T_c/T_h
  - Refrigerators and heat pumps: reverse engines
  - Coefficient of performance (COP)
- **Thermodynamic Processes**:
  - Isothermal (constant T): ΔU = 0, Q = W
  - Adiabatic (Q = 0): ΔU = -W, PVᵞ = constant
  - Isobaric (constant P): W = PΔV
  - Isochoric (constant V): W = 0, ΔU = Q

**Physical Insights**:
- Thermodynamics is independent of atomic theory (predates it)
- Second law defines the arrow of time
- Entropy connects microscopic (statistical) to macroscopic (thermodynamic)
- Reversible processes are idealizations; all real processes are irreversible
- Maximum work extracted when process is reversible

**Key Applications**: Engines, refrigeration, climate science, materials science, power generation, cryogenics, chemical reactions

### 4. Electromagnetism
Electric and magnetic phenomena unified by Maxwell's equations. Electromagnetism describes how charged particles interact and how changing electric/magnetic fields create each other:
- **Electric Fields & Potential**: Force fields around charges
  - Electric field E is force per unit charge
  - Field lines point from + to - charges
  - Gauss's law: flux through closed surface ∝ enclosed charge
  - Electric potential V is potential energy per unit charge
  - Equipotential surfaces perpendicular to field lines
  - Capacitance stores electrical energy in electric fields
  - Dielectric materials increase capacitance and reduce field
- **Circuits**: Flow of electric current and electronic devices
  - Current I = dQ/dt (charge flow rate)
  - Ohm's law: V = IR (linear materials)
  - Resistance: R = ρL/A (depends on material and geometry)
  - Kirchhoff's laws from charge/energy conservation
  - Series: same current; Parallel: same voltage
  - RC circuits: exponential charging/discharging
  - AC circuits: impedance, phase shifts, power factor
- **Magnetic Fields**: Fields around moving charges and magnets
  - Magnetic field B exerts force on moving charges: F = qv×B
  - No magnetic monopoles: ∇·B = 0
  - Biot-Savart law: dB ∝ (I dl × r)/r³
  - Ampère's law: ∮B·dl = μ₀I_enc (with symmetry)
  - Magnetic force on current-carrying wires
  - Magnetic dipole moment and torque on loops
- **Electromagnetic Induction**: Changing magnetic fields create electricity
  - Faraday's law: ε = -dΦ_B/dt (induced emf)
  - Lenz's law: induced current opposes flux change
  - Motional emf: ε = Blv (moving conductor)
  - Self-inductance L stores energy in magnetic field
  - Mutual inductance and transformers
  - RL circuits: exponential current changes
- **Maxwell's Equations**: Complete theory predicting electromagnetic waves
  1. Gauss (E): ∇·E = ρ/ε₀ (charges create E fields)
  2. Gauss (B): ∇·B = 0 (no magnetic monopoles)
  3. Faraday: ∇×E = -∂B/∂t (changing B creates E)
  4. Ampère-Maxwell: ∇×B = μ₀J + μ₀ε₀∂E/∂t (currents and changing E create B)
  - Maxwell added displacement current term
  - Predict EM waves travel at c = 1/√(μ₀ε₀)
  - Light is an electromagnetic wave
  - EM waves carry energy and momentum

**Physical Insights**:
- Electric and magnetic fields are components of electromagnetic field tensor
- Symmetry between E and B in Maxwell's equations
- Changing E field creates B field and vice versa
- Electromagnetic waves require no medium (unlike sound)
- Relativity: E and B fields transform into each other between reference frames
- Gauge invariance: potentials have freedom in choice

**Key Applications**: Electronics, power generation, telecommunications, medical imaging, motors, generators, wireless charging, particle accelerators

### 5. Optics
The study of light and its interactions with matter, from ray tracing to wave phenomena:

**Geometric Optics** (Light as rays):
- **Reflection**: 
  - Law of reflection: θ_incident = θ_reflected (measured from normal)
  - Plane mirrors: virtual image, same size, reversed left-right
  - Spherical mirrors: 
    - Concave (converging): can form real or virtual images, f > 0
    - Convex (diverging): only virtual images, f < 0
  - Mirror equation: 1/f = 1/d_o + 1/d_i
  - Magnification: m = -d_i/d_o = h_i/h_o
  - Focal length f = R/2 (R = radius of curvature)
- **Refraction**: 
  - Snell's law: n₁sinθ₁ = n₂sinθ₂
  - Index of refraction: n = c/v (speed of light in medium)
  - Bending toward normal when entering denser medium (n₂ > n₁)
  - Total internal reflection: θ_c = sin⁻¹(n₂/n₁) when n₁ > n₂
  - Applications: fiber optics, diamonds, mirages, prisms
  - Dispersion: n depends on wavelength (red bends less than blue)
- **Lenses**:
  - Converging (convex): brings parallel rays to focus, f > 0
  - Diverging (concave): spreads parallel rays, f < 0
  - Thin lens equation: 1/f = 1/d_o + 1/d_i (same as mirrors)
  - Lensmaker's equation: 1/f = (n-1)(1/R₁ - 1/R₂)
  - Multiple lenses: total magnification = product of individual magnifications
- **Optical Instruments**:
  - Eye: cornea/lens focus on retina; near point ~25 cm, far point ∞
  - Magnifying glass: angular magnification M = 25cm/f
  - Microscope: M_total = m_objective × M_eyepiece (two-lens system)
  - Telescope: M = -f_objective/f_eyepiece (large objective collects light)
  - Cameras: lens focuses on sensor/film, f-stop controls exposure
- **Aberrations**: Imperfections in image formation
  - Spherical: rays far from axis focus differently
  - Chromatic: different colors focus at different points
  - Corrections: compound lenses, parabolic mirrors

**Wave Optics** (Light as waves):
- **Nature of Light**:
  - Electromagnetic wave: E and B fields oscillate perpendicular
  - Speed: c = 3.00×10⁸ m/s (in vacuum)
  - Wavelength range: visible ~400-700 nm (violet to red)
  - Frequency: f = c/λ (determines color)
- **Interference**:
  - Coherent sources: constant phase relationship needed
  - Young's double slit: 
    - Bright fringes: dsinθ = mλ (m = 0, ±1, ±2...)
    - Dark fringes: dsinθ = (m + ½)λ
    - Fringe spacing: y = mλL/d (on screen distance L away)
  - Thin film interference: 
    - Phase change at higher-n interface (π shift)
    - Constructive: 2nt = (m + ½)λ (reflected light)
    - Destructive: 2nt = mλ
    - Applications: anti-reflective coatings, soap bubbles
  - Multiple slit: sharper, narrower maxima
- **Diffraction**:
  - Bending of waves around obstacles/through openings
  - Single slit: 
    - Dark fringes: asinθ = mλ (m = ±1, ±2...)
    - Central maximum wider and brighter than others
    - Width ∝ λ/a (narrower slit → wider pattern)
  - Circular aperture: Airy disk, resolution limit
  - Rayleigh criterion: θ_min = 1.22λ/D (just resolve two sources)
  - Diffraction grating:
    - Many slits: dsinθ = mλ (very sharp, bright maxima)
    - Resolving power: R = λ/Δλ = mN (order × number of slits)
    - Applications: spectroscopy, wavelength measurement
- **Polarization**:
  - Transverse wave property (not present in sound)
  - Linear polarization: E field oscillates in one plane
  - Polarizers: transmit only one polarization component
  - Malus's law: I = I₀cos²θ (transmitted intensity)
  - Sources: reflection, scattering, birefringent materials
  - Brewster's angle: tanθ_B = n₂/n₁ (fully polarized reflected light)
  - Applications: sunglasses, LCD displays, 3D movies, stress analysis
- **Huygens' Principle**: Every point on wavefront is source of spherical wavelets
- **Applications**: Microscopy, spectroscopy, holography, optical communications, laser technology

**Wave-Particle Duality**: Light exhibits both wave (interference, diffraction) and particle (photoelectric effect, Compton scattering) properties

### 6. Modern Physics
20th-century revolutions that revealed the nature of space, time, and matter at extreme scales. Modern physics shows classical physics is an approximation:
- **Special Relativity**: Physics at speeds approaching light speed
  - Two postulates: (1) laws same in all inertial frames, (2) speed of light constant
  - Simultaneity is relative (no absolute time)
  - Time dilation: moving clocks run slow (γ factor)
  - Length contraction: moving objects contract along motion direction
  - Mass-energy equivalence: E = mc² (mass is concentrated energy)
  - Relativistic momentum: p = γmv (approaches ∞ as v→c)
  - Spacetime: 4D continuum, events are points
  - Causality preserved: no information faster than c
  - Twin paradox: acceleration breaks symmetry
- **Quantum Mechanics**: Behavior of matter at atomic scales
  - Wave-particle duality: all matter has both properties
  - De Broglie wavelength: λ = h/p (smaller for massive objects)
  - Photoelectric effect: light consists of photons E = hf
  - Heisenberg uncertainty: ΔxΔp ≥ ℏ/2, ΔEΔt ≥ ℏ/2
  - Wave function Ψ: probability amplitude (|Ψ|² = probability density)
  - Schrödinger equation: time evolution of wave function
  - Quantization: energy levels are discrete (not continuous)
  - Quantum tunneling: particles penetrate barriers
  - Superposition: particles in multiple states simultaneously
  - Measurement collapses wave function (Copenhagen interpretation)
  - Entanglement: correlated quantum states (Einstein's "spooky action")
- **Atomic Physics**: Structure and properties of atoms
  - Bohr model: quantized angular momentum L = nℏ
  - Energy levels: E_n ∝ -1/n² for hydrogen
  - Quantum numbers: n, ℓ, m_ℓ, m_s describe electron states
  - Pauli exclusion: no two fermions in same quantum state
  - Electron configuration determines chemical properties
  - Atomic spectra: discrete emission/absorption lines
  - Selection rules: Δℓ = ±1 for allowed transitions
  - Fine structure: relativistic and spin-orbit effects
  - Zeeman effect: spectral line splitting in B field
  - Lasers: stimulated emission and population inversion
- **Nuclear Physics**: Properties of atomic nuclei and radioactivity
  - Strong nuclear force binds protons and neutrons
  - Mass defect: Δm = (Zm_p + Nm_n) - M_nucleus
  - Binding energy: BE = Δmc² (energy to disassemble)
  - Binding energy per nucleon peaks at Fe-56 (most stable)
  - Radioactive decay: probabilistic process, exponential law
  - Alpha decay: 2p + 2n emitted (helium nucleus)
  - Beta decay: weak force converts n→p or p→n
  - Gamma decay: excited nucleus emits photon
  - Half-life: time for half to decay (characteristic of isotope)
  - Nuclear fission: heavy nucleus splits (U, Pu)
  - Nuclear fusion: light nuclei combine (H→He in sun)
  - Chain reactions: fission neutrons cause more fissions
  - Critical mass: minimum for sustained chain reaction

**Physical Insights**:
- Classical physics fails at high speeds (relativity) and small scales (quantum)
- Relativity: space and time are relative, spacetime is absolute
- Quantum mechanics: determinism replaced by probability
- Complementarity: wave and particle are complementary descriptions
- Correspondence principle: quantum → classical for large quantum numbers
- Quantum field theory: particles are excitations of fields
- Standard Model: particles and three of four fundamental forces
- Unsolved: quantum gravity, dark matter, dark energy

**Key Applications**: Nuclear energy, semiconductors, lasers, medical imaging, quantum computing, GPS (relativity corrections), particle physics, cosmology, cryptography

## 🔗 Interconnections
- Mechanics provides the foundation for understanding all other areas
- Waves connect to both sound (mechanics) and light (electromagnetism)
- Thermodynamics bridges macroscopic and microscopic physics
- Electromagnetism explains light as electromagnetic waves
- Modern physics extends classical concepts to extreme conditions

## 💡 Learning Path
1. Start with **Mechanics** - essential foundation
   - Master vectors, calculus, and problem-solving
   - Understand energy conservation deeply
2. Move to **Waves** - introduces periodic phenomena
   - Connects mechanics to electromagnetic waves
   - Develop intuition for oscillations and resonance
3. Study **Thermodynamics** - links energy concepts
   - Statistical and macroscopic viewpoints
   - Understand entropy and irreversibility
4. Explore **Electromagnetism** - most complex classical physics
   - Unification of electricity and magnetism
   - Maxwell's equations as pinnacle of classical physics
5. Add **Optics** - application of wave and EM theory
   - Both geometric (ray) and wave approaches
6. Finish with **Modern Physics** - contemporary understanding
   - Requires strong mathematics (linear algebra, differential equations)
   - Challenges classical intuition

**Mathematical Prerequisites**: Calculus (derivatives, integrals, differential equations), vectors, linear algebra (for quantum mechanics)

## 🎓 Why This Matters
Physics is the most fundamental natural science, seeking universal laws governing matter, energy, space, and time. It provides the foundation for:
- **Engineering and technology**: All technology based on physical principles
- **Understanding natural phenomena**: From earthquakes to auroras to black holes
- **Medical physics**: Imaging (X-rays, MRI, ultrasound), radiation therapy
- **Energy**: Production, storage, transmission, and efficiency
- **Space exploration**: Orbital mechanics, propulsion, life support
- **Computing**: Semiconductors, quantum computing, information theory
- **Materials science**: Properties emerge from atomic/molecular physics
- **Climate science**: Thermodynamics and fluid dynamics of atmosphere/oceans
- **Fundamental research**: Nature of reality, origin of universe, fundamental particles

**Philosophical Impact**: Physics challenges our intuitions about time, causality, determinism, and reality itself. Quantum mechanics and relativity revolutionized philosophy of science.

---

## 🔢 Key Concepts & Formulas

### Mechanics

**Kinematics**
- Position: $x(t)$
- Velocity: $v = \frac{dx}{dt}$, Average: $v_{avg} = \frac{\Delta x}{\Delta t}$
- Acceleration: $a = \frac{dv}{dt}$
- Kinematic equations (constant acceleration):
  - $v = v_0 + at$
  - $x = x_0 + v_0t + \frac{1}{2}at^2$
  - $v^2 = v_0^2 + 2a(x - x_0)$
- **Projectile motion**: Horizontal (constant v) + vertical (free fall)

**Dynamics**
- **Newton's Laws**:
  1. Inertia: Objects maintain motion state
  2. $F = ma$ (force causes acceleration)
  3. Action-reaction pairs: $F_{AB} = -F_{BA}$
- **Friction**: $f_s \leq \mu_s N$, $f_k = \mu_k N$
- **Circular motion**: $a_c = \frac{v^2}{r}$, $F_c = \frac{mv^2}{r}$

**Energy & Work**
- **Work**: $W = Fd\cos\theta = \int F \cdot dx$
- **Kinetic energy**: $KE = \frac{1}{2}mv^2$
- **Potential energy**: 
  - Gravitational: $PE = mgh$
  - Elastic: $PE = \frac{1}{2}kx^2$
- **Conservation**: $E_{total} = KE + PE = \text{constant}$ (isolated system)
- **Power**: $P = \frac{W}{t} = Fv$

**Rotation**
- **Angular kinematics**: $\omega = \frac{d\theta}{dt}$, $\alpha = \frac{d\omega}{dt}$
- **Torque**: $\tau = r F \sin\theta = I\alpha$
- **Moment of inertia**: $I = \sum m_i r_i^2$ (discrete), $I = \int r^2 dm$ (continuous)
- **Angular momentum**: $L = I\omega$ (conserved in isolated system)
- **Rotational KE**: $KE_{rot} = \frac{1}{2}I\omega^2$

**Gravitation**
- **Newton's law**: $F = G\frac{m_1 m_2}{r^2}$
- **Gravitational field**: $g = \frac{GM}{r^2}$
- **Potential energy**: $U = -\frac{GMm}{r}$
- **Orbital velocity**: $v = \sqrt{\frac{GM}{r}}$
- **Kepler's laws**:
  1. Elliptical orbits
  2. Equal areas in equal times
  3. $T^2 \propto r^3$

**Fluids**
- **Pressure**: $P = \frac{F}{A}$
- **Hydrostatic**: $P = P_0 + \rho gh$
- **Buoyancy**: $F_b = \rho_{fluid} V_{displaced} g$ (Archimedes)
- **Continuity**: $A_1 v_1 = A_2 v_2$ (incompressible)
- **Bernoulli**: $P + \frac{1}{2}\rho v^2 + \rho gh = \text{constant}$

### Waves & Oscillations

**Simple Harmonic Motion**
- **Spring**: $F = -kx$, $\omega = \sqrt{\frac{k}{m}}$, $T = 2\pi\sqrt{\frac{m}{k}}$
- **Pendulum**: $T = 2\pi\sqrt{\frac{L}{g}}$ (small angles)
- **Position**: $x(t) = A\cos(\omega t + \phi)$
- **Energy**: $E = \frac{1}{2}kA^2$ (constant, oscillates between KE and PE)

**Wave Properties**
- **Wave equation**: $v = f\lambda$
- **Speed**: Depends on medium (strings: $v = \sqrt{\frac{T}{\mu}}$)
- **Superposition**: Waves add algebraically
- **Interference**: Constructive (in phase) vs destructive (out of phase)

**Sound**
- **Speed in air**: ~343 m/s (depends on temperature)
- **Intensity**: $I = \frac{P}{A}$, measured in dB: $\beta = 10\log\frac{I}{I_0}$
- **Doppler effect**: $f' = f\frac{v \pm v_o}{v \mp v_s}$

### Thermodynamics

**Temperature & Heat**
- **Kelvin**: $T(K) = T(°C) + 273.15$
- **Heat capacity**: $Q = mc\Delta T$
- **Latent heat**: $Q = mL$ (phase change)
- **Heat transfer**: Conduction ($Q = kA\frac{\Delta T}{d}t$), convection, radiation ($P = \sigma A T^4$)

**Gas Laws**
- **Ideal gas law**: $PV = nRT$ ($R = 8.314$ J/mol·K)
- **Kinetic theory**: $KE_{avg} = \frac{3}{2}k_B T$
- **Boyle**: $P_1V_1 = P_2V_2$ (constant T)
- **Charles**: $\frac{V_1}{T_1} = \frac{V_2}{T_2}$ (constant P)

**Laws of Thermodynamics**
- **First Law**: $\Delta U = Q - W$ (energy conservation)
  - $W = P\Delta V$ for gases
- **Second Law**: Entropy increases in spontaneous processes
  - $\Delta S \geq 0$ for isolated system
- **Carnot efficiency**: $e = 1 - \frac{T_c}{T_h}$ (maximum possible)

### Electromagnetism

**Electric Fields**
- **Coulomb's law**: $F = k\frac{q_1 q_2}{r^2}$ ($k = 8.99 \times 10^9$ N·m²/C²)
- **Electric field**: $E = \frac{F}{q} = k\frac{Q}{r^2}$
- **Gauss's law**: $\Phi_E = \oint E \cdot dA = \frac{Q_{enc}}{\epsilon_0}$

**Electric Potential**
- **Voltage**: $V = \frac{U}{q} = \frac{kQ}{r}$ (point charge)
- **Potential energy**: $U = qV$
- **Relationship to field**: $E = -\frac{dV}{dx}$
- **Capacitance**: $C = \frac{Q}{V}$, Energy: $U = \frac{1}{2}CV^2 = \frac{1}{2}QV$

**Circuits**
- **Ohm's law**: $V = IR$
- **Power**: $P = IV = I^2R = \frac{V^2}{R}$
- **Resistors in series**: $R_{total} = R_1 + R_2 + ...$
- **Resistors in parallel**: $\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$
- **Kirchhoff's laws**:
  - Current: $\sum I_{in} = \sum I_{out}$ (junction)
  - Voltage: $\sum V = 0$ (closed loop)
- **RC circuits**: $Q(t) = Q_0(1 - e^{-t/RC})$ (charging), $\tau = RC$

**Magnetic Fields**
- **Lorentz force**: $F = qvB\sin\theta$
- **Biot-Savart law**: $dB = \frac{\mu_0}{4\pi}\frac{I d\ell \times \hat{r}}{r^2}$
- **Ampère's law**: $\oint B \cdot d\ell = \mu_0 I_{enc}$
- **Solenoid**: $B = \mu_0 nI$ (inside)

**Electromagnetic Induction**
- **Faraday's law**: $\mathcal{E} = -\frac{d\Phi_B}{dt} = -N\frac{d(BA\cos\theta)}{dt}$
- **Lenz's law**: Induced current opposes flux change
- **Inductance**: $\mathcal{E} = -L\frac{dI}{dt}$, Energy: $U = \frac{1}{2}LI^2$
- **Transformer**: $\frac{V_2}{V_1} = \frac{N_2}{N_1}$

**Maxwell's Equations**
1. Gauss (E): $\nabla \cdot E = \frac{\rho}{\epsilon_0}$
2. Gauss (B): $\nabla \cdot B = 0$
3. Faraday: $\nabla \times E = -\frac{\partial B}{\partial t}$
4. Ampère-Maxwell: $\nabla \times B = \mu_0 J + \mu_0\epsilon_0\frac{\partial E}{\partial t}$

**Electromagnetic Waves**
- **Speed**: $c = \frac{1}{\sqrt{\mu_0\epsilon_0}} = 3.00 \times 10^8$ m/s
- **Energy**: $E = hf$ (photon), $h = 6.626 \times 10^{-34}$ J·s
- **Spectrum**: Radio → Microwave → IR → Visible → UV → X-ray → Gamma

### Optics

**Geometric Optics**
- **Reflection**: $\theta_i = \theta_r$
- **Refraction**: $n_1\sin\theta_1 = n_2\sin\theta_2$ (Snell's law)
- **Index of refraction**: $n = \frac{c}{v}$
- **Mirror/lens equation**: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$
- **Magnification**: $m = -\frac{d_i}{d_o} = \frac{h_i}{h_o}$
- **Lens maker's equation**: $\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$

**Wave Optics**
- **Double-slit interference**: $d\sin\theta = m\lambda$ (bright), $d\sin\theta = (m+\frac{1}{2})\lambda$ (dark)
- **Single-slit diffraction**: $a\sin\theta = m\lambda$ (dark minima)
- **Diffraction grating**: $d\sin\theta = m\lambda$ (maxima)
- **Thin-film interference**: $2nt = m\lambda$ (constructive with phase shift)
- **Rayleigh criterion**: $\theta_{min} = 1.22\frac{\lambda}{D}$ (resolution limit)

### Modern Physics

**Special Relativity**
- **Postulates**: 
  1. Laws of physics same in all inertial frames
  2. Speed of light constant ($c$) in all frames
- **Time dilation**: $\Delta t = \frac{\Delta t_0}{\sqrt{1-v^2/c^2}} = \gamma \Delta t_0$
- **Length contraction**: $L = L_0\sqrt{1-v^2/c^2} = \frac{L_0}{\gamma}$
- **Lorentz factor**: $\gamma = \frac{1}{\sqrt{1-v^2/c^2}}$
- **Mass-energy**: $E = mc^2$, $E^2 = (pc)^2 + (mc^2)^2$
- **Relativistic momentum**: $p = \gamma mv$

**Quantum Mechanics**
- **Photoelectric effect**: $KE_{max} = hf - \phi$ (work function $\phi$)
- **de Broglie wavelength**: $\lambda = \frac{h}{p} = \frac{h}{mv}$
- **Heisenberg uncertainty**: $\Delta x \Delta p \geq \frac{\hbar}{2}$, $\Delta E \Delta t \geq \frac{\hbar}{2}$
- **Schrödinger equation**: $i\hbar\frac{\partial\Psi}{\partial t} = \hat{H}\Psi$
- **Wave function**: $|\Psi|^2$ gives probability density
- **Energy quantization**: $E_n = \frac{n^2h^2}{8mL^2}$ (particle in box)

**Atomic Physics**
- **Bohr model**: $E_n = -\frac{13.6 \text{ eV}}{n^2}$ (hydrogen)
- **Photon emission**: $\Delta E = hf = \frac{hc}{\lambda}$
- **Rydberg formula**: $\frac{1}{\lambda} = R\left(\frac{1}{n_f^2} - \frac{1}{n_i^2}\right)$
- **Quantum numbers**: n (principal), ℓ (angular momentum), $m_\ell$ (magnetic), $m_s$ (spin)
- **Pauli exclusion**: No two electrons in same quantum state

**Nuclear Physics**
- **Binding energy**: $BE = \Delta mc^2$ (mass defect)
- **Radioactive decay**: $N(t) = N_0 e^{-\lambda t}$
- **Half-life**: $t_{1/2} = \frac{0.693}{\lambda}$
- **Decay types**:
  - Alpha: $^A_Z X \rightarrow ^{A-4}_{Z-2}Y + ^4_2He$
  - Beta⁻: $^A_Z X \rightarrow ^{A}_{Z+1}Y + e^- + \bar{\nu}_e$
  - Gamma: High-energy photon emission
- **Fission**: Heavy nucleus splits
- **Fusion**: Light nuclei combine (requires high T & P)

---

## 📊 Important Constants

- Speed of light: $c = 3.00 \times 10^8$ m/s
- Gravitational constant: $G = 6.67 \times 10^{-11}$ N·m²/kg²
- Coulomb constant: $k = 8.99 \times 10^9$ N·m²/C²
- Elementary charge: $e = 1.60 \times 10^{-19}$ C
- Planck constant: $h = 6.626 \times 10^{-34}$ J·s, $\hbar = \frac{h}{2\pi}$
- Boltzmann constant: $k_B = 1.38 \times 10^{-23}$ J/K
- Avogadro's number: $N_A = 6.02 \times 10^{23}$ mol⁻¹
- Gas constant: $R = 8.314$ J/(mol·K)
- Permittivity: $\epsilon_0 = 8.85 \times 10^{-12}$ C²/(N·m²)
- Permeability: $\mu_0 = 4\pi \times 10^{-7}$ T·m/A