# Physics Equations Reference

## 📐 Mechanics

### Kinematics

**Position and Displacement**
- Displacement: $\Delta x = x_f - x_i$
- Average velocity: $v_{avg} = \frac{\Delta x}{\Delta t}$
- Instantaneous velocity: $v = \frac{dx}{dt}$

**Constant Acceleration Equations**
- $v = v_0 + at$
- $x = x_0 + v_0t + \frac{1}{2}at^2$
- $v^2 = v_0^2 + 2a(x - x_0)$
- $x = x_0 + \frac{1}{2}(v_0 + v)t$

**Projectile Motion**
- Horizontal: $x = v_0\cos\theta \cdot t$
- Vertical: $y = v_0\sin\theta \cdot t - \frac{1}{2}gt^2$
- Range: $R = \frac{v_0^2\sin(2\theta)}{g}$
- Maximum height: $h_{max} = \frac{v_0^2\sin^2\theta}{2g}$

**Circular Motion**
- Angular velocity: $\omega = \frac{d\theta}{dt}$
- Centripetal acceleration: $a_c = \frac{v^2}{r} = \omega^2 r$
- Centripetal force: $F_c = \frac{mv^2}{r}$
- Period: $T = \frac{2\pi r}{v} = \frac{2\pi}{\omega}$

### Dynamics

**Newton's Laws**
- First Law: $\sum F = 0$ when $v = constant$
- Second Law: $\sum F = ma$
- Third Law: $F_{12} = -F_{21}$

**Friction**
- Static friction: $f_s \leq \mu_s N$
- Kinetic friction: $f_k = \mu_k N$

**Universal Gravitation**
- $F_g = G\frac{m_1m_2}{r^2}$ where $G = 6.674 \times 10^{-11}$ N⋅m²/kg²
- Gravitational potential energy: $U_g = -G\frac{m_1m_2}{r}$
- Orbital velocity: $v = \sqrt{\frac{GM}{r}}$
- Escape velocity: $v_{esc} = \sqrt{\frac{2GM}{r}}$

### Energy and Work

**Work**
- $W = \vec{F} \cdot \vec{d} = Fd\cos\theta$
- Work-energy theorem: $W_{net} = \Delta KE$

**Kinetic Energy**
- $KE = \frac{1}{2}mv^2$

**Potential Energy**
- Gravitational (near Earth): $U_g = mgh$
- Elastic (spring): $U_s = \frac{1}{2}kx^2$ (Hooke's Law: $F = -kx$)

**Conservation of Energy**
- $E_{total} = KE + PE = constant$
- $KE_i + PE_i = KE_f + PE_f$

**Power**
- $P = \frac{W}{t} = \frac{dW}{dt}$
- $P = \vec{F} \cdot \vec{v}$

### Momentum

**Linear Momentum**
- $\vec{p} = m\vec{v}$
- $\vec{F} = \frac{d\vec{p}}{dt}$
- Impulse: $\vec{J} = \vec{F}\Delta t = \Delta \vec{p}$

**Conservation of Momentum**
- $\sum \vec{p}_i = \sum \vec{p}_f$ (isolated system)

**Collisions**
- Elastic: $KE_i = KE_f$ and $\vec{p}_i = \vec{p}_f$
- Inelastic: $\vec{p}_i = \vec{p}_f$ but $KE_i > KE_f$
- Perfectly inelastic: Objects stick together

### Rotational Motion

**Angular Kinematics**
- $\omega = \frac{d\theta}{dt}$, $\alpha = \frac{d\omega}{dt}$
- $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$
- $\omega^2 = \omega_0^2 + 2\alpha(\theta - \theta_0)$

**Moment of Inertia**
- Point mass: $I = mr^2$
- Rod (center): $I = \frac{1}{12}ML^2$
- Rod (end): $I = \frac{1}{3}ML^2$
- Disk/cylinder (axis): $I = \frac{1}{2}MR^2$
- Sphere (solid): $I = \frac{2}{5}MR^2$
- Sphere (hollow): $I = \frac{2}{3}MR^2$

**Rotational Dynamics**
- Torque: $\tau = \vec{r} \times \vec{F} = rF\sin\theta$
- $\sum \tau = I\alpha$
- Rotational KE: $KE_{rot} = \frac{1}{2}I\omega^2$

**Angular Momentum**
- $\vec{L} = I\vec{\omega} = \vec{r} \times \vec{p}$
- $\sum \tau = \frac{d\vec{L}}{dt}$
- Conservation: $L_i = L_f$ (isolated system)

**Rolling Motion**
- $v_{cm} = R\omega$ (no slipping)
- $KE_{total} = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2$

### Fluid Mechanics

**Pressure**
- $P = \frac{F}{A}$
- Hydrostatic pressure: $P = P_0 + \rho gh$
- Atmospheric pressure: $1 \text{ atm} = 101,325 \text{ Pa}$

**Buoyancy**
- Archimedes' principle: $F_b = \rho_{fluid} V_{displaced} g$

**Continuity Equation**
- $A_1v_1 = A_2v_2$ (incompressible fluid)

**Bernoulli's Equation**
- $P_1 + \frac{1}{2}\rho v_1^2 + \rho gh_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho gh_2$

## 🌊 Waves and Oscillations

### Simple Harmonic Motion

**General SHM**
- $x(t) = A\cos(\omega t + \phi)$
- $v(t) = -A\omega\sin(\omega t + \phi)$
- $a(t) = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x$

**Mass-Spring System**
- $\omega = \sqrt{\frac{k}{m}}$
- $T = 2\pi\sqrt{\frac{m}{k}}$
- $f = \frac{1}{2\pi}\sqrt{\frac{k}{m}}$

**Simple Pendulum**
- $\omega = \sqrt{\frac{g}{L}}$
- $T = 2\pi\sqrt{\frac{L}{g}}$ (small angles)

**Energy in SHM**
- Total: $E = \frac{1}{2}kA^2$
- $E = \frac{1}{2}kx^2 + \frac{1}{2}mv^2$

**Damped Oscillations**
- $x(t) = Ae^{-bt/2m}\cos(\omega't + \phi)$
- $\omega' = \sqrt{\omega_0^2 - \frac{b^2}{4m^2}}$

### Wave Properties

**Wave Equation**
- $y(x,t) = A\sin(kx - \omega t + \phi)$
- Wave speed: $v = \frac{\omega}{k} = \lambda f$
- Wave number: $k = \frac{2\pi}{\lambda}$
- Angular frequency: $\omega = 2\pi f$

**Wave Speed**
- String: $v = \sqrt{\frac{T}{\mu}}$ where $\mu = \frac{m}{L}$
- Sound in gas: $v = \sqrt{\frac{\gamma RT}{M}}$

**Wave Intensity**
- $I = \frac{1}{2}\rho v \omega^2 A^2$
- Intensity level: $\beta = 10\log\left(\frac{I}{I_0}\right)$ dB

**Interference**
- Constructive: $\Delta L = n\lambda$ where $n = 0, 1, 2, ...$
- Destructive: $\Delta L = (n + \frac{1}{2})\lambda$

**Standing Waves**
- String (both ends fixed): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$
- Pipe (open-open): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$
- Pipe (open-closed): $\lambda_n = \frac{4L}{n}$, $f_n = n\frac{v}{4L}$ (n = 1, 3, 5...)

### Sound

**Doppler Effect**
- Observer moving: $f' = f\left(1 + \frac{v_o}{v}\right)$
- Source moving: $f' = f\left(\frac{v}{v \mp v_s}\right)$
- General: $f' = f\frac{v \pm v_o}{v \mp v_s}$

**Beat Frequency**
- $f_{beat} = |f_1 - f_2|$

## 🔥 Thermodynamics

### Temperature and Heat

**Temperature Scales**
- $T_C = \frac{5}{9}(T_F - 32)$
- $T_K = T_C + 273.15$

**Thermal Expansion**
- Linear: $\Delta L = \alpha L_0 \Delta T$
- Volume: $\Delta V = \beta V_0 \Delta T$ where $\beta \approx 3\alpha$

**Heat Transfer**
- $Q = mc\Delta T$ (specific heat)
- $Q = mL$ (latent heat: fusion or vaporization)

**Heat Conduction**
- $\frac{Q}{t} = kA\frac{T_H - T_C}{L}$ (Fourier's law)

**Stefan-Boltzmann Law**
- $P = \sigma A e T^4$ where $\sigma = 5.67 \times 10^{-8}$ W/(m²⋅K⁴)

### Gas Laws

**Ideal Gas Law**
- $PV = nRT$ where $R = 8.314$ J/(mol⋅K)
- $PV = NkT$ where $k = 1.38 \times 10^{-23}$ J/K

**Kinetic Theory**
- $\langle KE \rangle = \frac{3}{2}kT$
- $v_{rms} = \sqrt{\frac{3kT}{m}} = \sqrt{\frac{3RT}{M}}$

### First Law of Thermodynamics

**Energy Conservation**
- $\Delta U = Q - W$
- Work by gas: $W = \int P dV$
- Isobaric: $W = P\Delta V$
- Isothermal (ideal gas): $W = nRT\ln\frac{V_f}{V_i}$

**Molar Heat Capacity**
- $C_V = \frac{3}{2}R$ (monatomic gas)
- $C_P = C_V + R$
- $\gamma = \frac{C_P}{C_V}$

**Adiabatic Process**
- $PV^\gamma = constant$
- $TV^{\gamma-1} = constant$

### Second Law of Thermodynamics

**Entropy**
- $\Delta S = \frac{Q_{rev}}{T}$
- Carnot engine: $\Delta S_{universe} = 0$
- Real process: $\Delta S_{universe} > 0$

**Heat Engines**
- Efficiency: $e = \frac{W}{Q_H} = 1 - \frac{Q_C}{Q_H}$
- Carnot efficiency: $e_{Carnot} = 1 - \frac{T_C}{T_H}$

**Refrigerators**
- COP: $K = \frac{Q_C}{W} = \frac{Q_C}{Q_H - Q_C}$

## ⚡ Electromagnetism

### Electric Fields

**Coulomb's Law**
- $\vec{F} = k\frac{q_1q_2}{r^2}\hat{r}$ where $k = 8.99 \times 10^9$ N⋅m²/C²
- $k = \frac{1}{4\pi\epsilon_0}$ where $\epsilon_0 = 8.85 \times 10^{-12}$ C²/(N⋅m²)

**Electric Field**
- $\vec{E} = \frac{\vec{F}}{q_0}$
- Point charge: $E = k\frac{|q|}{r^2}$
- Infinite line: $E = \frac{\lambda}{2\pi\epsilon_0 r}$
- Infinite sheet: $E = \frac{\sigma}{2\epsilon_0}$

**Gauss's Law**
- $\oint \vec{E} \cdot d\vec{A} = \frac{Q_{enc}}{\epsilon_0}$

### Electric Potential

**Potential Energy**
- $\Delta U_e = q\Delta V$
- Point charge: $U = k\frac{q_1q_2}{r}$

**Electric Potential**
- $\Delta V = -\int \vec{E} \cdot d\vec{l}$
- Point charge: $V = k\frac{q}{r}$
- $\vec{E} = -\nabla V$

### Capacitance

**Definition**
- $C = \frac{Q}{V}$
- Parallel plate: $C = \epsilon_0\frac{A}{d}$
- With dielectric: $C = \kappa\epsilon_0\frac{A}{d}$

**Energy Stored**
- $U = \frac{1}{2}CV^2 = \frac{1}{2}QV = \frac{Q^2}{2C}$

**Capacitor Combinations**
- Series: $\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + ...$
- Parallel: $C_{eq} = C_1 + C_2 + ...$

### Circuits

**Ohm's Law**
- $V = IR$
- $R = \rho\frac{L}{A}$

**Power**
- $P = IV = I^2R = \frac{V^2}{R}$

**Resistor Combinations**
- Series: $R_{eq} = R_1 + R_2 + ...$
- Parallel: $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$

**Kirchhoff's Laws**
- Junction rule: $\sum I_{in} = \sum I_{out}$
- Loop rule: $\sum V = 0$ around closed loop

**RC Circuits**
- Charging: $Q(t) = Q_0(1 - e^{-t/RC})$
- Discharging: $Q(t) = Q_0 e^{-t/RC}$
- Time constant: $\tau = RC$

**RL Circuits**
- Current growth: $I(t) = \frac{\varepsilon}{R}(1 - e^{-Rt/L})$
- Time constant: $\tau = \frac{L}{R}$

### Magnetism

**Lorentz Force**
- $\vec{F} = q\vec{v} \times \vec{B}$
- $F = qvB\sin\theta$

**Magnetic Force on Current**
- $\vec{F} = I\vec{L} \times \vec{B}$
- $F = ILB\sin\theta$

**Biot-Savart Law**
- $d\vec{B} = \frac{\mu_0}{4\pi}\frac{Id\vec{l} \times \hat{r}}{r^2}$

**Ampère's Law**
- $\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enc}$
- $\mu_0 = 4\pi \times 10^{-7}$ T⋅m/A

**Magnetic Field Sources**
- Long straight wire: $B = \frac{\mu_0 I}{2\pi r}$
- Center of loop: $B = \frac{\mu_0 I}{2R}$
- Solenoid: $B = \mu_0 nI$ where $n = N/L$

### Electromagnetic Induction

**Faraday's Law**
- $\varepsilon = -\frac{d\Phi_B}{dt}$
- $\Phi_B = \int \vec{B} \cdot d\vec{A}$

**Motional EMF**
- $\varepsilon = vBL$

**Inductance**
- Self-inductance: $\varepsilon = -L\frac{dI}{dt}$
- Mutual inductance: $\varepsilon_2 = -M\frac{dI_1}{dt}$
- Energy: $U_L = \frac{1}{2}LI^2$

**AC Circuits**
- $V = V_0\sin(\omega t)$
- $I = I_0\sin(\omega t - \phi)$
- Impedance: $Z = \sqrt{R^2 + (X_L - X_C)^2}$
- $X_L = \omega L$, $X_C = \frac{1}{\omega C}$
- Phase angle: $\tan\phi = \frac{X_L - X_C}{R}$

**Electromagnetic Waves**
- $c = \frac{1}{\sqrt{\mu_0\epsilon_0}} = 3.00 \times 10^8$ m/s
- $c = \lambda f$
- $E = cB$

## 💡 Optics

### Geometric Optics

**Reflection**
- Law of reflection: $\theta_i = \theta_r$

**Refraction**
- Snell's law: $n_1\sin\theta_1 = n_2\sin\theta_2$
- Index of refraction: $n = \frac{c}{v}$
- Critical angle: $\sin\theta_c = \frac{n_2}{n_1}$ (TIR when $\theta > \theta_c$)

**Mirrors**
- Mirror equation: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$
- Magnification: $m = -\frac{d_i}{d_o} = \frac{h_i}{h_o}$
- Spherical mirror: $f = \frac{R}{2}$

**Lenses**
- Thin lens equation: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$
- Lensmaker's equation: $\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$

### Wave Optics

**Double-Slit Interference**
- Bright fringes: $d\sin\theta = m\lambda$ where $m = 0, 1, 2, ...$
- Dark fringes: $d\sin\theta = (m + \frac{1}{2})\lambda$
- Fringe spacing: $y = \frac{m\lambda L}{d}$

**Single-Slit Diffraction**
- Dark fringes: $a\sin\theta = m\lambda$ where $m = \pm1, \pm2, ...$
- First minimum: $\sin\theta = \frac{\lambda}{a}$

**Diffraction Grating**
- $d\sin\theta = m\lambda$
- Resolving power: $R = \frac{\lambda}{\Delta\lambda} = mN$

**Thin Film Interference**
- Constructive (reflected): $2nt = (m + \frac{1}{2})\lambda$
- Destructive (reflected): $2nt = m\lambda$

**Polarization**
- Malus's law: $I = I_0\cos^2\theta$
- Brewster's angle: $\tan\theta_B = \frac{n_2}{n_1}$

## 🌌 Modern Physics

### Special Relativity

**Time Dilation**
- $\Delta t = \frac{\Delta t_0}{\sqrt{1 - v^2/c^2}} = \gamma \Delta t_0$
- $\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$

**Length Contraction**
- $L = L_0\sqrt{1 - v^2/c^2} = \frac{L_0}{\gamma}$

**Relativistic Momentum**
- $\vec{p} = \gamma m\vec{v}$

**Mass-Energy Equivalence**
- $E = mc^2$
- $E^2 = (pc)^2 + (mc^2)^2$
- $E_k = (\gamma - 1)mc^2$

**Velocity Addition**
- $v = \frac{v_1 + v_2}{1 + v_1v_2/c^2}$

### Quantum Mechanics

**Photoelectric Effect**
- $E_{photon} = hf = \frac{hc}{\lambda}$
- $K_{max} = hf - \phi$ where $\phi$ is work function
- $h = 6.626 \times 10^{-34}$ J⋅s (Planck's constant)

**de Broglie Wavelength**
- $\lambda = \frac{h}{p} = \frac{h}{mv}$

**Heisenberg Uncertainty Principle**
- $\Delta x \Delta p \geq \frac{\hbar}{2}$ where $\hbar = \frac{h}{2\pi}$
- $\Delta E \Delta t \geq \frac{\hbar}{2}$

**Schrödinger Equation**
- Time-independent: $-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + U(x)\psi = E\psi$

**Bohr Model**
- Allowed orbits: $L = n\hbar$ where $n = 1, 2, 3, ...$
- Energy levels: $E_n = -\frac{13.6 \text{ eV}}{n^2}$ (hydrogen)
- Photon emission: $E_{photon} = E_i - E_f = hf$

**Quantum Numbers**
- Principal: $n = 1, 2, 3, ...$
- Angular momentum: $l = 0, 1, 2, ..., n-1$
- Magnetic: $m_l = -l, -l+1, ..., 0, ..., l-1, l$
- Spin: $m_s = \pm\frac{1}{2}$

### Nuclear Physics

**Nuclear Composition**
- Mass number: $A = Z + N$
- $Z$ = atomic number (protons)
- $N$ = neutron number

**Binding Energy**
- $E_b = (Zm_p + Nm_n - m_{nucleus})c^2$
- Binding energy per nucleon: $\frac{E_b}{A}$

**Radioactive Decay**
- $N(t) = N_0 e^{-\lambda t}$
- Activity: $R = \lambda N = R_0 e^{-\lambda t}$
- Half-life: $t_{1/2} = \frac{\ln 2}{\lambda} = \frac{0.693}{\lambda}$

**Decay Types**
- Alpha: $^A_ZX \rightarrow ^{A-4}_{Z-2}Y + ^4_2He$
- Beta minus: $^A_ZX \rightarrow ^{A}_{Z+1}Y + e^- + \bar{\nu}_e$
- Beta plus: $^A_ZX \rightarrow ^{A}_{Z-1}Y + e^+ + \nu_e$
- Gamma: $^A_Z X^* \rightarrow ^A_ZX + \gamma$

**Nuclear Reactions**
- $Q = (m_{reactants} - m_{products})c^2$
- Fission: Heavy nucleus splits
- Fusion: Light nuclei combine
