# 물리학 방정식 참고자료

*EN: # Physics Equations Reference*

> **네비게이션:** [허브](../physics.md) | [물리학 Notes](physics-note.md) | [용어집](physics-terminology.md) | [역학](../physics/physics-mechanics.md) | [파동](../physics/physics-waves.md) | [Thermodyn.](../physics/physics-thermodynamics.md) | [E&M](../physics/physics-electromagnetism.md) | [광학](../physics/physics-optics.md) | [현대](../physics/physics-modern.md)

*EN: > \*\*Navigation:\*\* [Hub](../physics.md) | [Physics Notes](physics-note.md) | [Terminology](physics-terminology.md) | [Mechanics](../physics/physics-mechanics.md) | [Waves](../physics/physics-waves.md) | [Thermodyn.](../physics/physics-thermodynamics.md) | [E&M](../physics/physics-electromagnetism.md) | [Optics](../physics/physics-optics.md) | [Modern](../physics/physics-modern.md)*

## 📐 역학

*EN: ## 📐 Mechanics*

### 운동학 (Kinematics)

*EN: ### Kinematics*

**위치와 변위 (Position and Displacement)**

*EN: **Position and Displacement***
- 변위: $\Delta x = x_f - x_i$

*EN: - Displacement: $\Delta x = x_f - x_i$*
- 평균 속도: $v_{avg} = \frac{\Delta x}{\Delta t}$

*EN: - Average velocity: $v_{avg} = \frac{\Delta x}{\Delta t}$*
- 순간 속도: $v = \frac{dx}{dt}$

*EN: - Instantaneous velocity: $v = \frac{dx}{dt}$*

**등가속도 방정식 (Constant Acceleration Equations)**

*EN: **Constant Acceleration Equations***
- $v = v_0 + at$

*EN: - $v = v_0 + at$*
- $x = x_0 + v_0t + \frac{1}{2}at^2$

*EN: - $x = x_0 + v_0t + \frac{1}{2}at^2$*
- $v^2 = v_0^2 + 2a(x - x_0)$

*EN: - $v^2 = v_0^2 + 2a(x - x_0)$*
- $x = x_0 + \frac{1}{2}(v_0 + v)t$

*EN: - $x = x_0 + \frac{1}{2}(v_0 + v)t$*

**포물선 운동 (Projectile Motion)**

*EN: **Projectile Motion***
- 수평: $x = v_0\cos\theta \cdot t$

*EN: - Horizontal: $x = v_0\cos\theta \cdot t$*
- 수직: $y = v_0\sin\theta \cdot t - \frac{1}{2}gt^2$

*EN: - Vertical: $y = v_0\sin\theta \cdot t - \frac{1}{2}gt^2$*
- 사정거리: $R = \frac{v_0^2\sin(2\theta)}{g}$

*EN: - Range: $R = \frac{v_0^2\sin(2\theta)}{g}$*
- 최대 높이: $h_{max} = \frac{v_0^2\sin^2\theta}{2g}$

*EN: - Maximum height: $h_{max} = \frac{v_0^2\sin^2\theta}{2g}$*

**원운동 (Circular Motion)**

*EN: **Circular Motion***
- 각속도: $\omega = \frac{d\theta}{dt}$

*EN: - Angular velocity: $\omega = \frac{d\theta}{dt}$*
- 구심 가속도: $a_c = \frac{v^2}{r} = \omega^2 r$

*EN: - Centripetal acceleration: $a_c = \frac{v^2}{r} = \omega^2 r$*
- 구심력: $F_c = \frac{mv^2}{r}$

*EN: - Centripetal force: $F_c = \frac{mv^2}{r}$*
- 주기: $T = \frac{2\pi r}{v} = \frac{2\pi}{\omega}$

*EN: - Period: $T = \frac{2\pi r}{v} = \frac{2\pi}{\omega}$*

### 동역학 (Dynamics)

*EN: ### Dynamics*

**뉴턴의 법칙 (Newton's Laws)**

*EN: **Newton's Laws***
- 제1법칙: $v = 일정$일 때 $\sum F = 0$

*EN: - First Law: $\sum F = 0$ when $v = constant$*
- 제2법칙: $\sum F = ma$

*EN: - Second Law: $\sum F = ma$*
- 제3법칙: $F_{12} = -F_{21}$

*EN: - Third Law: $F_{12} = -F_{21}$*

**마찰력 (Friction)**

*EN: **Friction***
- 정지 마찰력: $f_s \leq \mu_s N$

*EN: - Static friction: $f_s \leq \mu_s N$*
- 운동 마찰력: $f_k = \mu_k N$

*EN: - Kinetic friction: $f_k = \mu_k N$*

**만유인력 (Universal Gravitation)**

*EN: **Universal Gravitation***
- $F_g = G\frac{m_1m_2}{r^2}$ ($G = 6.674 \times 10^{-11}$ N⋅m²/kg²)

*EN: - $F_g = G\frac{m_1m_2}{r^2}$ where $G = 6.674 \times 10^{-11}$ N⋅m²/kg²*
- 중력 퍼텐셜 에너지: $U_g = -G\frac{m_1m_2}{r}$

*EN: - Gravitational potential energy: $U_g = -G\frac{m_1m_2}{r}$*
- 궤도 속도: $v = \sqrt{\frac{GM}{r}}$

*EN: - Orbital velocity: $v = \sqrt{\frac{GM}{r}}$*
- 탈출 속도: $v_{esc} = \sqrt{\frac{2GM}{r}}$

*EN: - Escape velocity: $v_{esc} = \sqrt{\frac{2GM}{r}}$*

### 에너지와 일 (Energy and Work)

*EN: ### Energy and Work*

**일 (Work)**

*EN: **Work***
- $W = \vec{F} \cdot \vec{d} = Fd\cos\theta$

*EN: - $W = \vec{F} \cdot \vec{d} = Fd\cos\theta$*
- 일-에너지 정리: $W_{net} = \Delta KE$

*EN: - Work-energy theorem: $W_{net} = \Delta KE$*

**운동 에너지 (Kinetic Energy)**

*EN: **Kinetic Energy***
- $KE = \frac{1}{2}mv^2$

*EN: - $KE = \frac{1}{2}mv^2$*

**퍼텐셜 에너지 (Potential Energy)**

*EN: **Potential Energy***
- 중력 (지구 근처): $U_g = mgh$

*EN: - Gravitational (near Earth): $U_g = mgh$*
- 탄성 (스프링): $U_s = \frac{1}{2}kx^2$ (훅의 법칙: $F = -kx$)

*EN: - Elastic (spring): $U_s = \frac{1}{2}kx^2$ (Hooke's Law: $F = -kx$)*

**에너지 보존 (Conservation of Energy)**

*EN: **Conservation of Energy***
- $E_{total} = KE + PE = 일정$

*EN: - $E_{total} = KE + PE = constant$*
- $KE_i + PE_i = KE_f + PE_f$

*EN: - $KE_i + PE_i = KE_f + PE_f$*

**일률 (Power)**

*EN: **Power***
- $P = \frac{W}{t} = \frac{dW}{dt}$

*EN: - $P = \frac{W}{t} = \frac{dW}{dt}$*
- $P = \vec{F} \cdot \vec{v}$

*EN: - $P = \vec{F} \cdot \vec{v}$*

### 운동량 (Momentum)

*EN: ### Momentum*

**선운동량 (Linear Momentum)**

*EN: **Linear Momentum***
- $\vec{p} = m\vec{v}$

*EN: - $\vec{p} = m\vec{v}$*
- $\vec{F} = \frac{d\vec{p}}{dt}$

*EN: - $\vec{F} = \frac{d\vec{p}}{dt}$*
- 충격량: $\vec{J} = \vec{F}\Delta t = \Delta \vec{p}$

*EN: - Impulse: $\vec{J} = \vec{F}\Delta t = \Delta \vec{p}$*

**운동량 보존 (Conservation of Momentum)**

*EN: **Conservation of Momentum***
- $\sum \vec{p}_i = \sum \vec{p}_f$ (고립 계)

*EN: - $\sum \vec{p}_i = \sum \vec{p}_f$ (isolated system)*

**충돌 (Collisions)**

*EN: **Collisions***
- 탄성: $KE_i = KE_f$ 및 $\vec{p}_i = \vec{p}_f$

*EN: - Elastic: $KE_i = KE_f$ and $\vec{p}_i = \vec{p}_f$*
- 비탄성: $\vec{p}_i = \vec{p}_f$ 이나 $KE_i > KE_f$

*EN: - Inelastic: $\vec{p}_i = \vec{p}_f$ but $KE_i > KE_f$*
- 완전 비탄성: 물체가 붙어서 움직임

*EN: - Perfectly inelastic: Objects stick together*

### 회전 운동 (Rotational Motion)

*EN: ### Rotational Motion*

**각운동학 (Angular Kinematics)**

*EN: **Angular Kinematics***
- $\omega = \frac{d\theta}{dt}$, $\alpha = \frac{d\omega}{dt}$

*EN: - $\omega = \frac{d\theta}{dt}$, $\alpha = \frac{d\omega}{dt}$*
- $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$

*EN: - $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$*
- $\omega^2 = \omega_0^2 + 2\alpha(\theta - \theta_0)$

*EN: - $\omega^2 = \omega_0^2 + 2\alpha(\theta - \theta_0)$*

**관성 모멘트 (Moment of Inertia)**

*EN: **Moment of Inertia***
- 점질량: $I = mr^2$

*EN: - Point mass: $I = mr^2$*
- 막대 (중심): $I = \frac{1}{12}ML^2$

*EN: - Rod (center): $I = \frac{1}{12}ML^2$*
- 막대 (끝): $I = \frac{1}{3}ML^2$

*EN: - Rod (end): $I = \frac{1}{3}ML^2$*
- 원판/원기둥 (축): $I = \frac{1}{2}MR^2$

*EN: - Disk/cylinder (axis): $I = \frac{1}{2}MR^2$*
- 구 (속찬): $I = \frac{2}{5}MR^2$

*EN: - Sphere (solid): $I = \frac{2}{5}MR^2$*
- 구 (속빈): $I = \frac{2}{3}MR^2$

*EN: - Sphere (hollow): $I = \frac{2}{3}MR^2$*

**회전 동역학 (Rotational Dynamics)**

*EN: **Rotational Dynamics***
- 토크: $\tau = \vec{r} \times \vec{F} = rF\sin\theta$

*EN: - Torque: $\tau = \vec{r} \times \vec{F} = rF\sin\theta$*
- $\sum \tau = I\alpha$

*EN: - $\sum \tau = I\alpha$*
- 회전 운동 에너지: $KE_{rot} = \frac{1}{2}I\omega^2$

*EN: - Rotational KE: $KE_{rot} = \frac{1}{2}I\omega^2$*

**각운동량 (Angular Momentum)**

*EN: **Angular Momentum***
- $\vec{L} = I\vec{\omega} = \vec{r} \times \vec{p}$

*EN: - $\vec{L} = I\vec{\omega} = \vec{r} \times \vec{p}$*
- $\sum \tau = \frac{d\vec{L}}{dt}$

*EN: - $\sum \tau = \frac{d\vec{L}}{dt}$*
- 보존: $L_i = L_f$ (고립 계)

*EN: - Conservation: $L_i = L_f$ (isolated system)*

**구르기 운동 (Rolling Motion)**

*EN: **Rolling Motion***
- $v_{cm} = R\omega$ (미끄럼 없음)

*EN: - $v_{cm} = R\omega$ (no slipping)*
- $KE_{total} = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2$

*EN: - $KE_{total} = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2$*

### 유체 역학 (Fluid Mechanics)

*EN: ### Fluid Mechanics*

**압력 (Pressure)**

*EN: **Pressure***
- $P = \frac{F}{A}$

*EN: - $P = \frac{F}{A}$*
- 정수압: $P = P_0 + \rho gh$

*EN: - Hydrostatic pressure: $P = P_0 + \rho gh$*
- 대기압: $1 \text{ atm} = 101,325 \text{ Pa}$

*EN: - Atmospheric pressure: $1 \text{ atm} = 101,325 \text{ Pa}$*

**부력 (Buoyancy)**

*EN: **Buoyancy***
- 아르키메데스 원리: $F_b = \rho_{fluid} V_{displaced} g$

*EN: - Archimedes' principle: $F_b = \rho_{fluid} V_{displaced} g$*

**연속 방정식 (Continuity Equation)**

*EN: **Continuity Equation***
- $A_1v_1 = A_2v_2$ (비압축성 유체)

*EN: - $A_1v_1 = A_2v_2$ (incompressible fluid)*

**베르누이 방정식 (Bernoulli's Equation)**

*EN: **Bernoulli's Equation***
- $P_1 + \frac{1}{2}\rho v_1^2 + \rho gh_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho gh_2$

*EN: - $P_1 + \frac{1}{2}\rho v_1^2 + \rho gh_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho gh_2$*

## 🌊 파동과 진동 (Waves and Oscillations)

*EN: ## 🌊 Waves and Oscillations*

### 단순 조화 운동 (Simple Harmonic Motion)

*EN: ### Simple Harmonic Motion*

**일반 단조화 운동 (General SHM)**

*EN: **General SHM***
- $x(t) = A\cos(\omega t + \phi)$

*EN: - $x(t) = A\cos(\omega t + \phi)$*
- $v(t) = -A\omega\sin(\omega t + \phi)$

*EN: - $v(t) = -A\omega\sin(\omega t + \phi)$*
- $a(t) = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x$

*EN: - $a(t) = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x$*

**질량-스프링 시스템 (Mass-Spring System)**

*EN: **Mass-Spring System***
- $\omega = \sqrt{\frac{k}{m}}$

*EN: - $\omega = \sqrt{\frac{k}{m}}$*
- $T = 2\pi\sqrt{\frac{m}{k}}$

*EN: - $T = 2\pi\sqrt{\frac{m}{k}}$*
- $f = \frac{1}{2\pi}\sqrt{\frac{k}{m}}$

*EN: - $f = \frac{1}{2\pi}\sqrt{\frac{k}{m}}$*

**단진자 (Simple Pendulum)**

*EN: **Simple Pendulum***
- $\omega = \sqrt{\frac{g}{L}}$

*EN: - $\omega = \sqrt{\frac{g}{L}}$*
- $T = 2\pi\sqrt{\frac{L}{g}}$ (작은 각도)

*EN: - $T = 2\pi\sqrt{\frac{L}{g}}$ (small angles)*

**단조화 운동의 에너지 (Energy in SHM)**

*EN: **Energy in SHM***
- 전체: $E = \frac{1}{2}kA^2$

*EN: - Total: $E = \frac{1}{2}kA^2$*
- $E = \frac{1}{2}kx^2 + \frac{1}{2}mv^2$

*EN: - $E = \frac{1}{2}kx^2 + \frac{1}{2}mv^2$*

**감쇠 진동 (Damped Oscillations)**

*EN: **Damped Oscillations***
- $x(t) = Ae^{-bt/2m}\cos(\omega't + \phi)$

*EN: - $x(t) = Ae^{-bt/2m}\cos(\omega't + \phi)$*
- $\omega' = \sqrt{\omega_0^2 - \frac{b^2}{4m^2}}$

*EN: - $\omega' = \sqrt{\omega_0^2 - \frac{b^2}{4m^2}}$*

### 파동 성질 (Wave Properties)

*EN: ### Wave Properties*

**파동 방정식 (Wave Equation)**

*EN: **Wave Equation***
- $y(x,t) = A\sin(kx - \omega t + \phi)$

*EN: - $y(x,t) = A\sin(kx - \omega t + \phi)$*
- 파동 속도: $v = \frac{\omega}{k} = \lambda f$

*EN: - Wave speed: $v = \frac{\omega}{k} = \lambda f$*
- 파수: $k = \frac{2\pi}{\lambda}$

*EN: - Wave number: $k = \frac{2\pi}{\lambda}$*
- 각진동수: $\omega = 2\pi f$

*EN: - Angular frequency: $\omega = 2\pi f$*

**파동 속도 (Wave Speed)**

*EN: **Wave Speed***
- 줄: $v = \sqrt{\frac{T}{\mu}}$ ($\mu = \frac{m}{L}$)

*EN: - String: $v = \sqrt{\frac{T}{\mu}}$ where $\mu = \frac{m}{L}$*
- 기체 중 음속: $v = \sqrt{\frac{\gamma RT}{M}}$

*EN: - Sound in gas: $v = \sqrt{\frac{\gamma RT}{M}}$*

**파동 세기 (Wave Intensity)**

*EN: **Wave Intensity***
- $I = \frac{1}{2}\rho v \omega^2 A^2$

*EN: - $I = \frac{1}{2}\rho v \omega^2 A^2$*
- 세기 수준: $\beta = 10\log\left(\frac{I}{I_0}\right)$ dB

*EN: - Intensity level: $\beta = 10\log\left(\frac{I}{I_0}\right)$ dB*

**간섭 (Interference)**

*EN: **Interference***
- 보강: $\Delta L = n\lambda$ ($n = 0, 1, 2, ...$)

*EN: - Constructive: $\Delta L = n\lambda$ where $n = 0, 1, 2, ...$*
- 상쇄: $\Delta L = (n + \frac{1}{2})\lambda$

*EN: - Destructive: $\Delta L = (n + \frac{1}{2})\lambda$*

**정상파 (Standing Waves)**

*EN: **Standing Waves***
- 줄 (양 끝 고정): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$

*EN: - String (both ends fixed): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$*
- 관 (양 끝 열림): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$

*EN: - Pipe (open-open): $\lambda_n = \frac{2L}{n}$, $f_n = n\frac{v}{2L}$*
- 관 (한쪽 열림): $\lambda_n = \frac{4L}{n}$, $f_n = n\frac{v}{4L}$ (n = 1, 3, 5...)

*EN: - Pipe (open-closed): $\lambda_n = \frac{4L}{n}$, $f_n = n\frac{v}{4L}$ (n = 1, 3, 5...)*

### 소리 (Sound)

*EN: ### Sound*

**도플러 효과 (Doppler Effect)**

*EN: **Doppler Effect***
- 관찰자 이동: $f' = f\left(1 \pm \frac{v_o}{v}\right)$ (+ 접근, − 후퇴)

*EN: - Observer moving: $f' = f\left(1 \pm \frac{v_o}{v}\right)$ (+ approaching, − receding)*
- 음원 이동: $f' = f\left(\frac{v}{v \mp v_s}\right)$ (− 접근, + 후퇴)

*EN: - Source moving: $f' = f\left(\frac{v}{v \mp v_s}\right)$ (− approaching, + receding)*
- 일반: $f' = f\frac{v \pm v_o}{v \mp v_s}$

*EN: - General: $f' = f\frac{v \pm v_o}{v \mp v_s}$*

**맥놀이 진동수 (Beat Frequency)**

*EN: **Beat Frequency***
- $f_{beat} = |f_1 - f_2|$

*EN: - $f_{beat} = |f_1 - f_2|$*

## 🔥 열역학

*EN: ## 🔥 Thermodynamics*

### 온도와 열 (Temperature and Heat)

*EN: ### Temperature and Heat*

**온도 척도 (Temperature Scales)**

*EN: **Temperature Scales***
- $T_C = \frac{5}{9}(T_F - 32)$

*EN: - $T_C = \frac{5}{9}(T_F - 32)$*
- $T_K = T_C + 273.15$

*EN: - $T_K = T_C + 273.15$*

**열팽창 (Thermal Expansion)**

*EN: **Thermal Expansion***
- 선형: $\Delta L = \alpha L_0 \Delta T$

*EN: - Linear: $\Delta L = \alpha L_0 \Delta T$*
- 부피: $\Delta V = \beta V_0 \Delta T$ ($\beta \approx 3\alpha$)

*EN: - Volume: $\Delta V = \beta V_0 \Delta T$ where $\beta \approx 3\alpha$*

**열 전달 (Heat Transfer)**

*EN: **Heat Transfer***
- $Q = mc\Delta T$ (비열)

*EN: - $Q = mc\Delta T$ (specific heat)*
- $Q = mL$ (잠열: 용융 또는 기화)

*EN: - $Q = mL$ (latent heat: fusion or vaporization)*

**열 전도 (Heat Conduction)**

*EN: **Heat Conduction***
- $\frac{Q}{t} = kA\frac{T_H - T_C}{L}$ (푸리에 법칙)

*EN: - $\frac{Q}{t} = kA\frac{T_H - T_C}{L}$ (Fourier's law)*

**슈테판-볼츠만 법칙 (Stefan-Boltzmann Law)**

*EN: **Stefan-Boltzmann Law***
- $P = \sigma A e T^4$ ($\sigma = 5.67 \times 10^{-8}$ W/(m²⋅K⁴))

*EN: - $P = \sigma A e T^4$ where $\sigma = 5.67 \times 10^{-8}$ W/(m²⋅K⁴)*

### 기체 법칙 (Gas Laws)

*EN: ### Gas Laws*

**이상 기체 법칙 (Ideal Gas Law)**

*EN: **Ideal Gas Law***
- $PV = nRT$ ($R = 8.314$ J/(mol⋅K))

*EN: - $PV = nRT$ where $R = 8.314$ J/(mol⋅K)*
- $PV = NkT$ ($k = 1.38 \times 10^{-23}$ J/K)

*EN: - $PV = NkT$ where $k = 1.38 \times 10^{-23}$ J/K*

**기체 분자 운동론 (Kinetic Theory)**

*EN: **Kinetic Theory***
- $\langle KE \rangle = \frac{3}{2}kT$

*EN: - $\langle KE \rangle = \frac{3}{2}kT$*
- $v_{rms} = \sqrt{\frac{3kT}{m}} = \sqrt{\frac{3RT}{M}}$

*EN: - $v_{rms} = \sqrt{\frac{3kT}{m}} = \sqrt{\frac{3RT}{M}}$*

### 열역학 제1법칙 (First Law of Thermodynamics)

*EN: ### First Law of Thermodynamics*

**에너지 보존 (Energy Conservation)**

*EN: **Energy Conservation***
- $\Delta U = Q - W$

*EN: - $\Delta U = Q - W$*
- 기체가 한 일: $W = \int P dV$

*EN: - Work by gas: $W = \int P dV$*
- 등압: $W = P\Delta V$

*EN: - Isobaric: $W = P\Delta V$*
- 등온 (이상 기체): $W = nRT\ln\frac{V_f}{V_i}$

*EN: - Isothermal (ideal gas): $W = nRT\ln\frac{V_f}{V_i}$*

**몰 열용량 (Molar Heat Capacity)**

*EN: **Molar Heat Capacity***
- $C_V = \frac{3}{2}R$ (단원자 기체)

*EN: - $C_V = \frac{3}{2}R$ (monatomic gas)*
- $C_P = C_V + R$

*EN: - $C_P = C_V + R$*
- $\gamma = \frac{C_P}{C_V}$

*EN: - $\gamma = \frac{C_P}{C_V}$*

**단열 과정 (Adiabatic Process)**

*EN: **Adiabatic Process***
- $PV^\gamma = 일정$

*EN: - $PV^\gamma = constant$*
- $TV^{\gamma-1} = 일정$

*EN: - $TV^{\gamma-1} = constant$*

### 열역학 제2법칙 (Second Law of Thermodynamics)

*EN: ### Second Law of Thermodynamics*

**엔트로피 (Entropy)**

*EN: **Entropy***
- $\Delta S = \frac{Q_{rev}}{T}$

*EN: - $\Delta S = \frac{Q_{rev}}{T}$*
- 카르노 기관: $\Delta S_{universe} = 0$

*EN: - Carnot engine: $\Delta S_{universe} = 0$*
- 실제 과정: $\Delta S_{universe} > 0$

*EN: - Real process: $\Delta S_{universe} > 0$*

**열기관 (Heat Engines)**

*EN: **Heat Engines***
- 효율: $e = \frac{W}{Q_H} = 1 - \frac{Q_C}{Q_H}$

*EN: - Efficiency: $e = \frac{W}{Q_H} = 1 - \frac{Q_C}{Q_H}$*
- 카르노 효율: $e_{Carnot} = 1 - \frac{T_C}{T_H}$

*EN: - Carnot efficiency: $e_{Carnot} = 1 - \frac{T_C}{T_H}$*

**냉동기 (Refrigerators)**

*EN: **Refrigerators***
- 성능 계수: $K = \frac{Q_C}{W} = \frac{Q_C}{Q_H - Q_C}$

*EN: - COP: $K = \frac{Q_C}{W} = \frac{Q_C}{Q_H - Q_C}$*

## ⚡ 전자기학 (Electromagnetism)

*EN: ## ⚡ Electromagnetism*

### 전기장 (Electric Fields)

*EN: ### Electric Fields*

**쿨롱의 법칙 (Coulomb's Law)**

*EN: **Coulomb's Law***
- $\vec{F} = k\frac{q_1q_2}{r^2}\hat{r}$ ($k = 8.99 \times 10^9$ N⋅m²/C²)

*EN: - $\vec{F} = k\frac{q_1q_2}{r^2}\hat{r}$ where $k = 8.99 \times 10^9$ N⋅m²/C²*
- $k = \frac{1}{4\pi\epsilon_0}$ ($\epsilon_0 = 8.85 \times 10^{-12}$ C²/(N⋅m²))

*EN: - $k = \frac{1}{4\pi\epsilon_0}$ where $\epsilon_0 = 8.85 \times 10^{-12}$ C²/(N⋅m²)*

**전기장 (Electric Field)**

*EN: **Electric Field***
- $\vec{E} = \frac{\vec{F}}{q_0}$

*EN: - $\vec{E} = \frac{\vec{F}}{q_0}$*
- 점전하: $E = k\frac{|q|}{r^2}$

*EN: - Point charge: $E = k\frac{|q|}{r^2}$*
- 무한 직선: $E = \frac{\lambda}{2\pi\epsilon_0 r}$

*EN: - Infinite line: $E = \frac{\lambda}{2\pi\epsilon_0 r}$*
- 무한 평면: $E = \frac{\sigma}{2\epsilon_0}$

*EN: - Infinite sheet: $E = \frac{\sigma}{2\epsilon_0}$*

**가우스의 법칙 (Gauss's Law)**

*EN: **Gauss's Law***
- $\oint \vec{E} \cdot d\vec{A} = \frac{Q_{enc}}{\epsilon_0}$

*EN: - $\oint \vec{E} \cdot d\vec{A} = \frac{Q_{enc}}{\epsilon_0}$*

### 전기 전위 (Electric Potential)

*EN: ### Electric Potential*

**퍼텐셜 에너지 (Potential Energy)**

*EN: **Potential Energy***
- $\Delta U_e = q\Delta V$

*EN: - $\Delta U_e = q\Delta V$*
- 점전하: $U = k\frac{q_1q_2}{r}$

*EN: - Point charge: $U = k\frac{q_1q_2}{r}$*

**전기 전위 (Electric Potential)**

*EN: **Electric Potential***
- $\Delta V = -\int \vec{E} \cdot d\vec{l}$

*EN: - $\Delta V = -\int \vec{E} \cdot d\vec{l}$*
- 점전하: $V = k\frac{q}{r}$

*EN: - Point charge: $V = k\frac{q}{r}$*
- $\vec{E} = -\nabla V$

*EN: - $\vec{E} = -\nabla V$*

### 전기 용량 (Capacitance)

*EN: ### Capacitance*

**정의 (Definition)**

*EN: **Definition***
- $C = \frac{Q}{V}$

*EN: - $C = \frac{Q}{V}$*
- 평행판: $C = \epsilon_0\frac{A}{d}$

*EN: - Parallel plate: $C = \epsilon_0\frac{A}{d}$*
- 유전체 포함: $C = \kappa\epsilon_0\frac{A}{d}$

*EN: - With dielectric: $C = \kappa\epsilon_0\frac{A}{d}$*

**저장된 에너지 (Energy Stored)**

*EN: **Energy Stored***
- $U = \frac{1}{2}CV^2 = \frac{1}{2}QV = \frac{Q^2}{2C}$

*EN: - $U = \frac{1}{2}CV^2 = \frac{1}{2}QV = \frac{Q^2}{2C}$*

**축전기 조합 (Capacitor Combinations)**

*EN: **Capacitor Combinations***
- 직렬: $\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + ...$

*EN: - Series: $\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + ...$*
- 병렬: $C_{eq} = C_1 + C_2 + ...$

*EN: - Parallel: $C_{eq} = C_1 + C_2 + ...$*

### 회로 (Circuits)

*EN: ### Circuits*

**옴의 법칙 (Ohm's Law)**

*EN: **Ohm's Law***
- $V = IR$

*EN: - $V = IR$*
- $R = \rho\frac{L}{A}$

*EN: - $R = \rho\frac{L}{A}$*

**일률 (Power)**

*EN: **Power***
- $P = IV = I^2R = \frac{V^2}{R}$

*EN: - $P = IV = I^2R = \frac{V^2}{R}$*

**저항기 조합 (Resistor Combinations)**

*EN: **Resistor Combinations***
- 직렬: $R_{eq} = R_1 + R_2 + ...$

*EN: - Series: $R_{eq} = R_1 + R_2 + ...$*
- 병렬: $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$

*EN: - Parallel: $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$*

**키르히호프의 법칙 (Kirchhoff's Laws)**

*EN: **Kirchhoff's Laws***
- 접합 규칙: $\sum I_{in} = \sum I_{out}$

*EN: - Junction rule: $\sum I_{in} = \sum I_{out}$*
- 루프 규칙: 닫힌 루프에서 $\sum V = 0$

*EN: - Loop rule: $\sum V = 0$ around closed loop*

**RC 회로 (RC Circuits)**

*EN: **RC Circuits***
- 충전: $Q(t) = Q_0(1 - e^{-t/RC})$

*EN: - Charging: $Q(t) = Q_0(1 - e^{-t/RC})$*
- 방전: $Q(t) = Q_0 e^{-t/RC}$

*EN: - Discharging: $Q(t) = Q_0 e^{-t/RC}$*
- 시간 상수: $\tau = RC$

*EN: - Time constant: $\tau = RC$*

**RL 회로 (RL Circuits)**

*EN: **RL Circuits***
- 전류 증가: $I(t) = \frac{\varepsilon}{R}(1 - e^{-Rt/L})$

*EN: - Current growth: $I(t) = \frac{\varepsilon}{R}(1 - e^{-Rt/L})$*
- 시간 상수: $\tau = \frac{L}{R}$

*EN: - Time constant: $\tau = \frac{L}{R}$*

### 자기학 (Magnetism)

*EN: ### Magnetism*

**로렌츠 힘 (Lorentz Force)**

*EN: **Lorentz Force***
- $\vec{F} = q\vec{v} \times \vec{B}$

*EN: - $\vec{F} = q\vec{v} \times \vec{B}$*
- $F = qvB\sin\theta$

*EN: - $F = qvB\sin\theta$*

**전류에 작용하는 자기력 (Magnetic Force on Current)**

*EN: **Magnetic Force on Current***
- $\vec{F} = I\vec{L} \times \vec{B}$

*EN: - $\vec{F} = I\vec{L} \times \vec{B}$*
- $F = ILB\sin\theta$

*EN: - $F = ILB\sin\theta$*

**비오-사바르 법칙 (Biot-Savart Law)**

*EN: **Biot-Savart Law***
- $d\vec{B} = \frac{\mu_0}{4\pi}\frac{Id\vec{l} \times \hat{r}}{r^2}$

*EN: - $d\vec{B} = \frac{\mu_0}{4\pi}\frac{Id\vec{l} \times \hat{r}}{r^2}$*

**앙페르의 법칙 (Ampère's Law)**

*EN: **Ampère's Law***
- $\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enc}$

*EN: - $\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enc}$*
- $\mu_0 = 4\pi \times 10^{-7}$ T⋅m/A

*EN: - $\mu_0 = 4\pi \times 10^{-7}$ T⋅m/A*

**자기장 원천 (Magnetic Field Sources)**

*EN: **Magnetic Field Sources***
- 긴 직선 도선: $B = \frac{\mu_0 I}{2\pi r}$

*EN: - Long straight wire: $B = \frac{\mu_0 I}{2\pi r}$*
- 루프 중심: $B = \frac{\mu_0 I}{2R}$

*EN: - Center of loop: $B = \frac{\mu_0 I}{2R}$*
- 솔레노이드: $B = \mu_0 nI$ ($n = N/L$)

*EN: - Solenoid: $B = \mu_0 nI$ where $n = N/L$*

### 전자기 유도 (Electromagnetic Induction)

*EN: ### Electromagnetic Induction*

**패러데이의 법칙 (Faraday's Law)**

*EN: **Faraday's Law***
- $\varepsilon = -\frac{d\Phi_B}{dt}$

*EN: - $\varepsilon = -\frac{d\Phi_B}{dt}$*
- $\Phi_B = \int \vec{B} \cdot d\vec{A}$

*EN: - $\Phi_B = \int \vec{B} \cdot d\vec{A}$*

**운동 기전력 (Motional EMF)**

*EN: **Motional EMF***
- $\varepsilon = vBL$

*EN: - $\varepsilon = vBL$*

**인덕턴스 (Inductance)**

*EN: **Inductance***
- 자기 인덕턴스: $\varepsilon = -L\frac{dI}{dt}$

*EN: - Self-inductance: $\varepsilon = -L\frac{dI}{dt}$*
- 상호 인덕턴스: $\varepsilon_2 = -M\frac{dI_1}{dt}$

*EN: - Mutual inductance: $\varepsilon_2 = -M\frac{dI_1}{dt}$*
- 에너지: $U_L = \frac{1}{2}LI^2$

*EN: - Energy: $U_L = \frac{1}{2}LI^2$*

**교류 회로 (AC Circuits)**

*EN: **AC Circuits***
- $V = V_0\sin(\omega t)$

*EN: - $V = V_0\sin(\omega t)$*
- $I = I_0\sin(\omega t - \phi)$

*EN: - $I = I_0\sin(\omega t - \phi)$*
- 임피던스: $Z = \sqrt{R^2 + (X_L - X_C)^2}$

*EN: - Impedance: $Z = \sqrt{R^2 + (X_L - X_C)^2}$*
- $X_L = \omega L$, $X_C = \frac{1}{\omega C}$

*EN: - $X_L = \omega L$, $X_C = \frac{1}{\omega C}$*
- 위상각: $\tan\phi = \frac{X_L - X_C}{R}$

*EN: - Phase angle: $\tan\phi = \frac{X_L - X_C}{R}$*

**전자기파 (Electromagnetic Waves)**

*EN: **Electromagnetic Waves***
- $c = \frac{1}{\sqrt{\mu_0\epsilon_0}} = 3.00 \times 10^8$ m/s

*EN: - $c = \frac{1}{\sqrt{\mu_0\epsilon_0}} = 3.00 \times 10^8$ m/s*
- $c = \lambda f$

*EN: - $c = \lambda f$*
- $E = cB$

*EN: - $E = cB$*

## 💡 광학

*EN: ## 💡 Optics*

### 기하 광학 (Geometric Optics)

*EN: ### Geometric Optics*

**반사 (Reflection)**

*EN: **Reflection***
- 반사 법칙: $\theta_i = \theta_r$

*EN: - Law of reflection: $\theta_i = \theta_r$*

**굴절 (Refraction)**

*EN: **Refraction***
- 스넬의 법칙: $n_1\sin\theta_1 = n_2\sin\theta_2$

*EN: - Snell's law: $n_1\sin\theta_1 = n_2\sin\theta_2$*
- 굴절률: $n = \frac{c}{v}$

*EN: - Index of refraction: $n = \frac{c}{v}$*
- 임계각: $\sin\theta_c = \frac{n_2}{n_1}$ ($\theta > \theta_c$이면 전반사)

*EN: - Critical angle: $\sin\theta_c = \frac{n_2}{n_1}$ (TIR when $\theta > \theta_c$)*

**거울 (Mirrors)**

*EN: **Mirrors***
- 거울 방정식: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$

*EN: - Mirror equation: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$*
- 배율: $m = -\frac{d_i}{d_o} = \frac{h_i}{h_o}$

*EN: - Magnification: $m = -\frac{d_i}{d_o} = \frac{h_i}{h_o}$*
- 구면 거울: $f = \frac{R}{2}$

*EN: - Spherical mirror: $f = \frac{R}{2}$*

**렌즈 (Lenses)**

*EN: **Lenses***
- 박막 렌즈 방정식: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$

*EN: - Thin lens equation: $\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}$*
- 렌즈 제작자 방정식: $\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$

*EN: - Lensmaker's equation: $\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$*

### 파동 광학 (Wave Optics)

*EN: ### Wave Optics*

**이중 슬릿 간섭 (Double-Slit Interference)**

*EN: **Double-Slit Interference***
- 밝은 무늬: $d\sin\theta = m\lambda$ ($m = 0, 1, 2, ...$)

*EN: - Bright fringes: $d\sin\theta = m\lambda$ where $m = 0, 1, 2, ...$*
- 어두운 무늬: $d\sin\theta = (m + \frac{1}{2})\lambda$

*EN: - Dark fringes: $d\sin\theta = (m + \frac{1}{2})\lambda$*
- 무늬 간격: $y = \frac{m\lambda L}{d}$

*EN: - Fringe spacing: $y = \frac{m\lambda L}{d}$*

**단일 슬릿 회절 (Single-Slit Diffraction)**

*EN: **Single-Slit Diffraction***
- 어두운 무늬: $a\sin\theta = m\lambda$ ($m = \pm1, \pm2, ...$)

*EN: - Dark fringes: $a\sin\theta = m\lambda$ where $m = \pm1, \pm2, ...$*
- 첫 번째 극소: $\sin\theta = \frac{\lambda}{a}$

*EN: - First minimum: $\sin\theta = \frac{\lambda}{a}$*

**회절 격자 (Diffraction Grating)**

*EN: **Diffraction Grating***
- $d\sin\theta = m\lambda$

*EN: - $d\sin\theta = m\lambda$*
- 분해능: $R = \frac{\lambda}{\Delta\lambda} = mN$

*EN: - Resolving power: $R = \frac{\lambda}{\Delta\lambda} = mN$*

**얇은 막 간섭 (Thin Film Interference)**

*EN: **Thin Film Interference***
- 보강 간섭 (반사): $2nt = (m + \frac{1}{2})\lambda$

*EN: - Constructive (reflected): $2nt = (m + \frac{1}{2})\lambda$*
- 상쇄 간섭 (반사): $2nt = m\lambda$

*EN: - Destructive (reflected): $2nt = m\lambda$*

**편광 (Polarization)**

*EN: **Polarization***
- 말뤼스의 법칙: $I = I_0\cos^2\theta$

*EN: - Malus's law: $I = I_0\cos^2\theta$*
- 브루스터각: $\tan\theta_B = \frac{n_2}{n_1}$

*EN: - Brewster's angle: $\tan\theta_B = \frac{n_2}{n_1}$*

## 🌌 현대 물리학

*EN: ## 🌌 Modern Physics*

### 특수 상대성 이론 (Special Relativity)

*EN: ### Special Relativity*

**시간 팽창 (Time Dilation)**

*EN: **Time Dilation***
- $\Delta t = \frac{\Delta t_0}{\sqrt{1 - v^2/c^2}} = \gamma \Delta t_0$

*EN: - $\Delta t = \frac{\Delta t_0}{\sqrt{1 - v^2/c^2}} = \gamma \Delta t_0$*
- $\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$

*EN: - $\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$*

**길이 수축 (Length Contraction)**

*EN: **Length Contraction***
- $L = L_0\sqrt{1 - v^2/c^2} = \frac{L_0}{\gamma}$

*EN: - $L = L_0\sqrt{1 - v^2/c^2} = \frac{L_0}{\gamma}$*

**상대론적 운동량 (Relativistic Momentum)**

*EN: **Relativistic Momentum***
- $\vec{p} = \gamma m\vec{v}$

*EN: - $\vec{p} = \gamma m\vec{v}$*

**질량-에너지 등가 (Mass-Energy Equivalence)**

*EN: **Mass-Energy Equivalence***
- $E = mc^2$

*EN: - $E = mc^2$*
- $E^2 = (pc)^2 + (mc^2)^2$

*EN: - $E^2 = (pc)^2 + (mc^2)^2$*
- $E_k = (\gamma - 1)mc^2$

*EN: - $E_k = (\gamma - 1)mc^2$*

**속도 덧셈 (Velocity Addition)**

*EN: **Velocity Addition***
- $v = \frac{v_1 + v_2}{1 + v_1v_2/c^2}$

*EN: - $v = \frac{v_1 + v_2}{1 + v_1v_2/c^2}$*

### 양자 역학 (Quantum Mechanics)

*EN: ### Quantum Mechanics*

**광전 효과 (Photoelectric Effect)**

*EN: **Photoelectric Effect***
- $E_{photon} = hf = \frac{hc}{\lambda}$

*EN: - $E_{photon} = hf = \frac{hc}{\lambda}$*
- $K_{max} = hf - \phi$ ($\phi$는 일함수)

*EN: - $K_{max} = hf - \phi$ where $\phi$ is work function*
- $h = 6.626 \times 10^{-34}$ J⋅s (플랑크 상수)

*EN: - $h = 6.626 \times 10^{-34}$ J⋅s (Planck's constant)*

**드 브로이 파장 (de Broglie Wavelength)**

*EN: **de Broglie Wavelength***
- $\lambda = \frac{h}{p} = \frac{h}{mv}$

*EN: - $\lambda = \frac{h}{p} = \frac{h}{mv}$*

**하이젠베르크 불확정성 원리 (Heisenberg Uncertainty Principle)**

*EN: **Heisenberg Uncertainty Principle***
- $\Delta x \Delta p \geq \frac{\hbar}{2}$ ($\hbar = \frac{h}{2\pi}$)

*EN: - $\Delta x \Delta p \geq \frac{\hbar}{2}$ where $\hbar = \frac{h}{2\pi}$*
- $\Delta E \Delta t \geq \frac{\hbar}{2}$

*EN: - $\Delta E \Delta t \geq \frac{\hbar}{2}$*

**슈뢰딩거 방정식 (Schrödinger Equation)**

*EN: **Schrödinger Equation***
- 시간 독립: $-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + U(x)\psi = E\psi$

*EN: - Time-independent: $-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + U(x)\psi = E\psi$*

**보어 모형 (Bohr Model)**

*EN: **Bohr Model***
- 허용 궤도: $L = n\hbar$ ($n = 1, 2, 3, ...$)

*EN: - Allowed orbits: $L = n\hbar$ where $n = 1, 2, 3, ...$*
- 에너지 준위: $E_n = -\frac{13.6 \text{ eV}}{n^2}$ (수소)

*EN: - Energy levels: $E_n = -\frac{13.6 \text{ eV}}{n^2}$ (hydrogen)*
- 광자 방출: $E_{photon} = E_i - E_f = hf$

*EN: - Photon emission: $E_{photon} = E_i - E_f = hf$*

**양자 수 (Quantum Numbers)**

*EN: **Quantum Numbers***
- 주 양자수: $n = 1, 2, 3, ...$

*EN: - Principal: $n = 1, 2, 3, ...$*
- 각운동량: $l = 0, 1, 2, ..., n-1$

*EN: - Angular momentum: $l = 0, 1, 2, ..., n-1$*
- 자기: $m_l = -l, -l+1, ..., 0, ..., l-1, l$

*EN: - Magnetic: $m_l = -l, -l+1, ..., 0, ..., l-1, l$*
- 스핀: $m_s = \pm\frac{1}{2}$

*EN: - Spin: $m_s = \pm\frac{1}{2}$*

### 핵물리학 (Nuclear Physics)

*EN: ### Nuclear Physics*

**핵 구성 (Nuclear Composition)**

*EN: **Nuclear Composition***
- 질량수: $A = Z + N$

*EN: - Mass number: $A = Z + N$*
- $Z$ = 원자 번호 (양성자 수)

*EN: - $Z$ = atomic number (protons)*
- $N$ = 중성자 수

*EN: - $N$ = neutron number*

**결합 에너지 (Binding Energy)**

*EN: **Binding Energy***
- $E_b = (Zm_p + Nm_n - m_{nucleus})c^2$

*EN: - $E_b = (Zm_p + Nm_n - m_{nucleus})c^2$*
- 핵자당 결합 에너지: $\frac{E_b}{A}$

*EN: - Binding energy per nucleon: $\frac{E_b}{A}$*

**방사성 붕괴 (Radioactive Decay)**

*EN: **Radioactive Decay***
- $N(t) = N_0 e^{-\lambda t}$

*EN: - $N(t) = N_0 e^{-\lambda t}$*
- 방사능: $R = \lambda N = R_0 e^{-\lambda t}$

*EN: - Activity: $R = \lambda N = R_0 e^{-\lambda t}$*
- 반감기: $t_{1/2} = \frac{\ln 2}{\lambda} = \frac{0.693}{\lambda}$

*EN: - Half-life: $t_{1/2} = \frac{\ln 2}{\lambda} = \frac{0.693}{\lambda}$*

**붕괴 유형 (Decay Types)**

*EN: **Decay Types***
- 알파: $^A_ZX \rightarrow ^{A-4}_{Z-2}Y + ^4_2He$

*EN: - Alpha: $^A_ZX \rightarrow ^{A-4}_{Z-2}Y + ^4_2He$*
- 베타 마이너스: $^A_ZX \rightarrow ^{A}_{Z+1}Y + e^- + \bar{\nu}_e$

*EN: - Beta minus: $^A_ZX \rightarrow ^{A}_{Z+1}Y + e^- + \bar{\nu}_e$*
- 베타 플러스: $^A_ZX \rightarrow ^{A}_{Z-1}Y + e^+ + \nu_e$

*EN: - Beta plus: $^A_ZX \rightarrow ^{A}_{Z-1}Y + e^+ + \nu_e$*
- 감마: $^A_Z X^* \rightarrow ^A_ZX + \gamma$

*EN: - Gamma: $^A_Z X^* \rightarrow ^A_ZX + \gamma$*

**핵 반응 (Nuclear Reactions)**

*EN: **Nuclear Reactions***
- $Q = (m_{reactants} - m_{products})c^2$

*EN: - $Q = (m_{reactants} - m_{products})c^2$*
- 핵분열: 무거운 핵이 분열

*EN: - Fission: Heavy nucleus splits*
- 핵융합: 가벼운 핵들이 결합

*EN: - Fusion: Light nuclei combine*
