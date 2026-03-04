# 수학 방정식 참고자료

*EN: # Mathematics Equations Reference*

> **네비게이션:** [허브](../math.md) | [수학 Notes](math-note.md) | [용어집](math-terminology.md) | [미적분](../math/math-calculus.md) | [선형대수](../math/math-linear-algebra.md) | [Diff. Eq.](../math/math-differential-equations.md) | [Prob. & Stats](../math/math-probability-statistics.md)

*EN: > \*\*Navigation:\*\* [Hub](../math.md) | [Math Notes](math-note.md) | [Terminology](math-terminology.md) | [Calculus](../math/math-calculus.md) | [Linear Algebra](../math/math-linear-algebra.md) | [Diff. Eq.](../math/math-differential-equations.md) | [Prob. & Stats](../math/math-probability-statistics.md)*

## 📐 미적분

*EN: ## 📐 Calculus*

### 극한과 연속 (Limits & Continuity)

*EN: ### Limits & Continuity*

**극한의 정의 (Limit Definition)**

*EN: **Limit Definition***
- $\lim_{x \to a} f(x) = L$ if for every $\epsilon > 0$, there exists $\delta > 0$ such that $|f(x) - L| < \epsilon$ whenever $0 < |x - a| < \delta$

*EN: - $\lim_{x \to a} f(x) = L$ if for every $\epsilon > 0$, there exists $\delta > 0$ such that $|f(x) - L| < \epsilon$ whenever $0 < |x - a| < \delta$*

**극한 법칙 (Limit Laws)**

*EN: **Limit Laws***
- 합: $\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$

*EN: - Sum: $\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$*
- 곱: $\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$

*EN: - Product: $\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$*
- 몫: $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$ ($\lim_{x \to a} g(x) \neq 0$인 경우)

*EN: - Quotient: $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$ if $\lim_{x \to a} g(x) \neq 0$*

**특수 극한 (Special Limits)**

*EN: **Special Limits***
- $\lim_{x \to 0} \frac{\sin x}{x} = 1$

*EN: - $\lim_{x \to 0} \frac{\sin x}{x} = 1$*
- $\lim_{x \to 0} \frac{1 - \cos x}{x} = 0$

*EN: - $\lim_{x \to 0} \frac{1 - \cos x}{x} = 0$*
- $\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e$

*EN: - $\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e$*

**연속성 (Continuity)**

*EN: **Continuity***
- $f$가 $a$에서 연속이면: $\lim_{x \to a} f(x) = f(a)$

*EN: - $f$ is continuous at $a$ if $\lim_{x \to a} f(x) = f(a)$*

**중간값 정리 (Intermediate Value Theorem, IVT)**

*EN: **Intermediate Value Theorem (IVT)***
- $f$가 $[a,b]$에서 연속이고 $N$이 $f(a)$와 $f(b)$ 사이의 값이면, $f(c) = N$인 $c \in (a,b)$가 존재

*EN: - If $f$ is continuous on $[a,b]$ and $N$ is between $f(a)$ and $f(b)$, then there exists $c \in (a,b)$ such that $f(c) = N$*

### 미분 (Derivatives)

*EN: ### Derivatives*

**차분 몫 (Difference Quotient)**

*EN: **Difference Quotient***
- $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

*EN: - $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$*

**기본 도함수 (Basic Derivatives)**

*EN: **Basic Derivatives***
- 거듭제곱 법칙: $\frac{d}{dx}[x^n] = nx^{n-1}$

*EN: - Power rule: $\frac{d}{dx}[x^n] = nx^{n-1}$*
- 상수: $\frac{d}{dx}[c] = 0$

*EN: - Constant: $\frac{d}{dx}[c] = 0$*
- 지수: $\frac{d}{dx}[e^x] = e^x$, $\frac{d}{dx}[a^x] = a^x \ln a$

*EN: - Exponential: $\frac{d}{dx}[e^x] = e^x$, $\frac{d}{dx}[a^x] = a^x \ln a$*
- 로그: $\frac{d}{dx}[\ln x] = \frac{1}{x}$, $\frac{d}{dx}[\log_a x] = \frac{1}{x \ln a}$

*EN: - Logarithm: $\frac{d}{dx}[\ln x] = \frac{1}{x}$, $\frac{d}{dx}[\log_a x] = \frac{1}{x \ln a}$*

**삼각함수 도함수 (Trigonometric Derivatives)**

*EN: **Trigonometric Derivatives***
- $\frac{d}{dx}[\sin x] = \cos x$

*EN: - $\frac{d}{dx}[\sin x] = \cos x$*
- $\frac{d}{dx}[\cos x] = -\sin x$

*EN: - $\frac{d}{dx}[\cos x] = -\sin x$*
- $\frac{d}{dx}[\tan x] = \sec^2 x$

*EN: - $\frac{d}{dx}[\tan x] = \sec^2 x$*
- $\frac{d}{dx}[\cot x] = -\csc^2 x$

*EN: - $\frac{d}{dx}[\cot x] = -\csc^2 x$*
- $\frac{d}{dx}[\sec x] = \sec x \tan x$

*EN: - $\frac{d}{dx}[\sec x] = \sec x \tan x$*
- $\frac{d}{dx}[\csc x] = -\csc x \cot x$

*EN: - $\frac{d}{dx}[\csc x] = -\csc x \cot x$*

**역삼각함수 도함수 (Inverse Trigonometric Derivatives)**

*EN: **Inverse Trigonometric Derivatives***
- $\frac{d}{dx}[\sin^{-1} x] = \frac{1}{\sqrt{1-x^2}}$

*EN: - $\frac{d}{dx}[\sin^{-1} x] = \frac{1}{\sqrt{1-x^2}}$*
- $\frac{d}{dx}[\cos^{-1} x] = -\frac{1}{\sqrt{1-x^2}}$

*EN: - $\frac{d}{dx}[\cos^{-1} x] = -\frac{1}{\sqrt{1-x^2}}$*
- $\frac{d}{dx}[\tan^{-1} x] = \frac{1}{1+x^2}$

*EN: - $\frac{d}{dx}[\tan^{-1} x] = \frac{1}{1+x^2}$*

**미분 법칙 (Differentiation Rules)**

*EN: **Differentiation Rules***
- 합의 법칙: $(f + g)' = f' + g'$

*EN: - Sum rule: $(f + g)' = f' + g'$*
- 곱의 법칙: $(fg)' = f'g + fg'$

*EN: - Product rule: $(fg)' = f'g + fg'$*
- 몫의 법칙: $\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$

*EN: - Quotient rule: $\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$*
- 연쇄 법칙: $(f \circ g)'(x) = f'(g(x)) \cdot g'(x)$

*EN: - Chain rule: $(f \circ g)'(x) = f'(g(x)) \cdot g'(x)$*

**음함수 미분 (Implicit Differentiation)**

*EN: **Implicit Differentiation***
- $y$를 $x$의 함수로 보고 양변을 $x$에 대해 미분

*EN: - Differentiate both sides with respect to $x$, treating $y$ as a function of $x$*

**평균값 정리 (Mean Value Theorem, MVT)**

*EN: **Mean Value Theorem (MVT)***
- $f$가 $[a,b]$에서 연속이고 $(a,b)$에서 미분 가능하면, $f'(c) = \frac{f(b) - f(a)}{b - a}$인 $c \in (a,b)$가 존재

*EN: - If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then there exists $c \in (a,b)$ such that $f'(c) = \frac{f(b) - f(a)}{b - a}$*

### 적분 (Integration)

*EN: ### Integration*

**미적분학의 기본 정리 (Fundamental Theorem of Calculus, FTC)**

*EN: **Fundamental Theorem of Calculus (FTC)***
- 제1부분: $F(x) = \int_a^x f(t)\,dt$이면 $F'(x) = f(x)$

*EN: - Part 1: If $F(x) = \int_a^x f(t)\,dt$, then $F'(x) = f(x)$*
- 제2부분: $\int_a^b f(x)\,dx = F(b) - F(a)$ ($F' = f$)

*EN: - Part 2: $\int_a^b f(x)\,dx = F(b) - F(a)$ where $F' = f$*

**기본 적분 (Basic Integrals)**

*EN: **Basic Integrals***
- 거듭제곱: $\int x^n\,dx = \frac{x^{n+1}}{n+1} + C$ ($n \neq -1$인 경우)

*EN: - Power rule: $\int x^n\,dx = \frac{x^{n+1}}{n+1} + C$ (for $n \neq -1$)*
- $\int \frac{1}{x}\,dx = \ln|x| + C$

*EN: - $\int \frac{1}{x}\,dx = \ln|x| + C$*
- $\int e^x\,dx = e^x + C$

*EN: - $\int e^x\,dx = e^x + C$*
- $\int a^x\,dx = \frac{a^x}{\ln a} + C$

*EN: - $\int a^x\,dx = \frac{a^x}{\ln a} + C$*

**삼각함수 적분 (Trigonometric Integrals)**

*EN: **Trigonometric Integrals***
- $\int \sin x\,dx = -\cos x + C$

*EN: - $\int \sin x\,dx = -\cos x + C$*
- $\int \cos x\,dx = \sin x + C$

*EN: - $\int \cos x\,dx = \sin x + C$*
- $\int \tan x\,dx = -\ln|\cos x| + C = \ln|\sec x| + C$

*EN: - $\int \tan x\,dx = -\ln|\cos x| + C = \ln|\sec x| + C$*
- $\int \sec^2 x\,dx = \tan x + C$

*EN: - $\int \sec^2 x\,dx = \tan x + C$*
- $\int \sec x \tan x\,dx = \sec x + C$

*EN: - $\int \sec x \tan x\,dx = \sec x + C$*
- $\int \frac{1}{\sqrt{1-x^2}}\,dx = \sin^{-1} x + C$

*EN: - $\int \frac{1}{\sqrt{1-x^2}}\,dx = \sin^{-1} x + C$*
- $\int \frac{1}{1+x^2}\,dx = \tan^{-1} x + C$

*EN: - $\int \frac{1}{1+x^2}\,dx = \tan^{-1} x + C$*

**적분 기법 (Integration Techniques)**

*EN: **Integration Techniques***

*치환 적분 (u-치환)*

*EN: *Substitution (u-substitution)**
- $\int f(g(x))g'(x)\,dx = \int f(u)\,du$ ($u = g(x)$)

*EN: - $\int f(g(x))g'(x)\,dx = \int f(u)\,du$ where $u = g(x)$*

*부분 적분 (Integration by Parts)*

*EN: *Integration by Parts**
- $\int u\,dv = uv - \int v\,du$

*EN: - $\int u\,dv = uv - \int v\,du$*

*부분 분수 (Partial Fractions)*

*EN: *Partial Fractions**
- $\deg(P) < \deg(Q)$인 경우 $\frac{P(x)}{Q(x)}$를 분해

*EN: - Decompose $\frac{P(x)}{Q(x)}$ where $\deg(P) < \deg(Q)$*

*삼각 치환 (Trigonometric Substitution)*

*EN: *Trigonometric Substitution**
- $\sqrt{a^2 - x^2}$: $x = a\sin\theta$ 사용

*EN: - $\sqrt{a^2 - x^2}$: use $x = a\sin\theta$*
- $\sqrt{a^2 + x^2}$: $x = a\tan\theta$ 사용

*EN: - $\sqrt{a^2 + x^2}$: use $x = a\tan\theta$*
- $\sqrt{x^2 - a^2}$: $x = a\sec\theta$ 사용

*EN: - $\sqrt{x^2 - a^2}$: use $x = a\sec\theta$*

**적분의 응용 (Applications of Integration)**

*EN: **Applications of Integration***
- 곡선 사이의 넓이: $A = \int_a^b [f(x) - g(x)]\,dx$

*EN: - Area between curves: $A = \int_a^b [f(x) - g(x)]\,dx$*
- 부피 (원판법): $V = \pi \int_a^b [f(x)]^2\,dx$

*EN: - Volume (disk method): $V = \pi \int_a^b [f(x)]^2\,dx$*
- 부피 (원통껍질법): $V = 2\pi \int_a^b x f(x)\,dx$

*EN: - Volume (shell method): $V = 2\pi \int_a^b x f(x)\,dx$*
- 호의 길이: $L = \int_a^b \sqrt{1 + [f'(x)]^2}\,dx$

*EN: - Arc length: $L = \int_a^b \sqrt{1 + [f'(x)]^2}\,dx$*
- 표면적: $S = 2\pi \int_a^b f(x)\sqrt{1 + [f'(x)]^2}\,dx$

*EN: - Surface area: $S = 2\pi \int_a^b f(x)\sqrt{1 + [f'(x)]^2}\,dx$*

### 수열과 급수 (Sequences & Series)

*EN: ### Sequences & Series*

**수열 (Sequences)**

*EN: **Sequences***
- 수렴: $\lim_{n \to \infty} a_n = L$

*EN: - Convergence: $\lim_{n \to \infty} a_n = L$*
- 유계: 모든 $n$에 대해 $|a_n| \leq M$

*EN: - Bounded: $|a_n| \leq M$ for all $n$*
- 단조: 증가 또는 감소

*EN: - Monotonic: increasing or decreasing*

**급수 (Series)**

*EN: **Series***
- $\sum_{n=1}^{\infty} a_n = \lim_{N \to \infty} \sum_{n=1}^N a_n$

*EN: - $\sum_{n=1}^{\infty} a_n = \lim_{N \to \infty} \sum_{n=1}^N a_n$*
- 등비급수: $\sum_{n=0}^{\infty} ar^n = \frac{a}{1-r}$ ($|r| < 1$인 경우)

*EN: - Geometric series: $\sum_{n=0}^{\infty} ar^n = \frac{a}{1-r}$ if $|r| < 1$*
- 조화급수: $\sum_{n=1}^{\infty} \frac{1}{n}$ 발산

*EN: - Harmonic series: $\sum_{n=1}^{\infty} \frac{1}{n}$ diverges*
- p-급수: $\sum_{n=1}^{\infty} \frac{1}{n^p}$는 $p > 1$이면 수렴

*EN: - p-series: $\sum_{n=1}^{\infty} \frac{1}{n^p}$ converges if $p > 1$*

**수렴 판정법 (Convergence Tests)**

*EN: **Convergence Tests***
- **발산 판정법**: $\lim_{n \to \infty} a_n \neq 0$이면 $\sum a_n$ 발산

*EN: - **Divergence test**: If $\lim_{n \to \infty} a_n \neq 0$, then $\sum a_n$ diverges*
- **적분 판정법**: $\sum a_n$과 $\int_1^{\infty} f(x)\,dx$는 모두 수렴하거나 모두 발산 ($f$가 양수, 연속, 감소인 경우)

*EN: - **Integral test**: $\sum a_n$ and $\int_1^{\infty} f(x)\,dx$ both converge or both diverge (if $f$ is positive, continuous, decreasing)*
- **비교 판정법**: $0 \leq a_n \leq b_n$이고 $\sum b_n$ 수렴이면 $\sum a_n$ 수렴

*EN: - **Comparison test**: If $0 \leq a_n \leq b_n$ and $\sum b_n$ converges, then $\sum a_n$ converges*
- **극한 비교 판정법**: $\lim_{n \to \infty} \frac{a_n}{b_n} = c > 0$이면 $\sum a_n$과 $\sum b_n$은 같은 수렴성을 가짐

*EN: - **Limit comparison test**: If $\lim_{n \to \infty} \frac{a_n}{b_n} = c > 0$, then $\sum a_n$ and $\sum b_n$ behave the same*
- **비율 판정법**: $L = \lim_{n \to \infty} \left|\frac{a_{n+1}}{a_n}\right|$

*EN: - **Ratio test**: $L = \lim_{n \to \infty} \left|\frac{a_{n+1}}{a_n}\right|$*
  - $L < 1$이면 절대수렴

*EN:   - If $L < 1$: converges absolutely*
  - $L > 1$이면 발산

*EN:   - If $L > 1$: diverges*
  - $L = 1$이면 판정 불능

*EN:   - If $L = 1$: test inconclusive*
- **근 판정법**: $L = \lim_{n \to \infty} \sqrt[n]{|a_n|}$

*EN: - **Root test**: $L = \lim_{n \to \infty} \sqrt[n]{|a_n|}$*
  - $L < 1$이면 절대수렴

*EN:   - If $L < 1$: converges absolutely*
  - $L > 1$이면 발산

*EN:   - If $L > 1$: diverges*
- **교대급수 판정법**: $a_n > 0$이고 $a_n$ 감소이며 $\lim_{n \to \infty} a_n = 0$이면 $\sum (-1)^n a_n$ 수렴

*EN: - **Alternating series test**: If $a_n > 0$, $a_n$ decreasing, and $\lim_{n \to \infty} a_n = 0$, then $\sum (-1)^n a_n$ converges*

**거듭제곱 급수 (Power Series)**

*EN: **Power Series***
- $\sum_{n=0}^{\infty} c_n(x-a)^n$

*EN: - $\sum_{n=0}^{\infty} c_n(x-a)^n$*
- 수렴 반경: $R = \frac{1}{\lim_{n \to \infty} \sqrt[n]{|c_n|}}$ 또는 $R = \lim_{n \to \infty} \left|\frac{c_n}{c_{n+1}}\right|$

*EN: - Radius of convergence: $R = \frac{1}{\lim_{n \to \infty} \sqrt[n]{|c_n|}}$ or $R = \lim_{n \to \infty} \left|\frac{c_n}{c_{n+1}}\right|$*
- 수렴 구간: $(a-R, a+R)$ (끝점은 별도 확인)

*EN: - Interval of convergence: $(a-R, a+R)$ (check endpoints separately)*

**테일러 급수 (Taylor Series)**

*EN: **Taylor Series***
- $f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$

*EN: - $f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$*
- 매클로린 급수: $a = 0$에서 중심을 둔 테일러 급수

*EN: - Maclaurin series: Taylor series centered at $a = 0$*

**주요 매클로린 급수 (Common Maclaurin Series)**

*EN: **Common Maclaurin Series***
- $e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$

*EN: - $e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$*
- $\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n+1}}{(2n+1)!}$

*EN: - $\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n+1}}{(2n+1)!}$*
- $\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}$

*EN: - $\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}$*
- $\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n$ ($|x| < 1$인 경우)

*EN: - $\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n$ for $|x| < 1$*
- $\ln(1+x) = \sum_{n=1}^{\infty} \frac{(-1)^{n+1} x^n}{n}$ ($|x| < 1$인 경우)

*EN: - $\ln(1+x) = \sum_{n=1}^{\infty} \frac{(-1)^{n+1} x^n}{n}$ for $|x| < 1$*

### 다변수 미적분 (Multivariable Calculus)

*EN: ### Multivariable Calculus*

**편미분 (Partial Derivatives)**

*EN: **Partial Derivatives***
- $\frac{\partial f}{\partial x} = \lim_{h \to 0} \frac{f(x+h, y) - f(x, y)}{h}$

*EN: - $\frac{\partial f}{\partial x} = \lim_{h \to 0} \frac{f(x+h, y) - f(x, y)}{h}$*

**기울기 벡터 (Gradient)**

*EN: **Gradient***
- $\nabla f = \left\langle \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z} \right\rangle$

*EN: - $\nabla f = \left\langle \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z} \right\rangle$*

**방향 도함수 (Directional Derivative)**

*EN: **Directional Derivative***
- $D_{\mathbf{u}}f = \nabla f \cdot \mathbf{u}$ ($\mathbf{u}$는 단위 벡터)

*EN: - $D_{\mathbf{u}}f = \nabla f \cdot \mathbf{u}$ where $\mathbf{u}$ is a unit vector*

**연쇄 법칙 (다변수) (Chain Rule, Multivariable)**

*EN: **Chain Rule (Multivariable)***
- $\frac{dz}{dt} = \frac{\partial z}{\partial x}\frac{dx}{dt} + \frac{\partial z}{\partial y}\frac{dy}{dt}$

*EN: - $\frac{dz}{dt} = \frac{\partial z}{\partial x}\frac{dx}{dt} + \frac{\partial z}{\partial y}\frac{dy}{dt}$*

**최적화 (Optimization)**

*EN: **Optimization***
- 임계점: $\nabla f = \mathbf{0}$

*EN: - Critical points: $\nabla f = \mathbf{0}$*
- 이계 도함수 판정법: 헤시안 행렬식 $D = f_{xx}f_{yy} - (f_{xy})^2$ 사용

*EN: - Second derivative test: Use Hessian determinant $D = f_{xx}f_{yy} - (f_{xy})^2$*
  - $D > 0$이고 $f_{xx} > 0$: 극소

*EN:   - $D > 0$ and $f_{xx} > 0$: local minimum*
  - $D > 0$이고 $f_{xx} < 0$: 극대

*EN:   - $D > 0$ and $f_{xx} < 0$: local maximum*
  - $D < 0$: 안장점

*EN:   - $D < 0$: saddle point*

**라그랑주 승수법 (Lagrange Multipliers)**

*EN: **Lagrange Multipliers***
- $g(x,y,z) = k$ 조건에서 $f(x,y,z)$ 최적화:

*EN: - To optimize $f(x,y,z)$ subject to $g(x,y,z) = k$:*
- $\nabla f = \lambda \nabla g$와 $g(x,y,z) = k$ 풀기

*EN: - Solve $\nabla f = \lambda \nabla g$ and $g(x,y,z) = k$*

**이중 적분 (Double Integrals)**

*EN: **Double Integrals***
- $\iint_R f(x,y)\,dA = \int_a^b \int_{g_1(x)}^{g_2(x)} f(x,y)\,dy\,dx$

*EN: - $\iint_R f(x,y)\,dA = \int_a^b \int_{g_1(x)}^{g_2(x)} f(x,y)\,dy\,dx$*
- 극좌표: $\iint_R f(x,y)\,dA = \int_{\alpha}^{\beta} \int_{r_1(\theta)}^{r_2(\theta)} f(r\cos\theta, r\sin\theta) r\,dr\,d\theta$

*EN: - Polar coordinates: $\iint_R f(x,y)\,dA = \int_{\alpha}^{\beta} \int_{r_1(\theta)}^{r_2(\theta)} f(r\cos\theta, r\sin\theta) r\,dr\,d\theta$*

**삼중 적분 (Triple Integrals)**

*EN: **Triple Integrals***
- $\iiint_E f(x,y,z)\,dV$

*EN: - $\iiint_E f(x,y,z)\,dV$*
- 원통 좌표: $dV = r\,dr\,d\theta\,dz$

*EN: - Cylindrical: $dV = r\,dr\,d\theta\,dz$*
- 구면 좌표: $dV = \rho^2 \sin\phi\,d\rho\,d\phi\,d\theta$

*EN: - Spherical: $dV = \rho^2 \sin\phi\,d\rho\,d\phi\,d\theta$*

**변수 변환 (Change of Variables)**

*EN: **Change of Variables***
- 야코비안: $J = \frac{\partial(x,y)}{\partial(u,v)} = \begin{vmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial v} \\ \frac{\partial y}{\partial u} & \frac{\partial y}{\partial v} \end{vmatrix}$

*EN: - Jacobian: $J = \frac{\partial(x,y)}{\partial(u,v)} = \begin{vmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial v} \\ \frac{\partial y}{\partial u} & \frac{\partial y}{\partial v} \end{vmatrix}$*
- $\iint_R f(x,y)\,dx\,dy = \iint_S f(x(u,v), y(u,v)) |J|\,du\,dv$

*EN: - $\iint_R f(x,y)\,dx\,dy = \iint_S f(x(u,v), y(u,v)) |J|\,du\,dv$*

### 벡터 미적분 (Vector Calculus)

*EN: ### Vector Calculus*

**선 적분 (Line Integrals)**

*EN: **Line Integrals***
- 스칼라장: $\int_C f\,ds = \int_a^b f(\mathbf{r}(t))|\mathbf{r}'(t)|\,dt$

*EN: - Scalar field: $\int_C f\,ds = \int_a^b f(\mathbf{r}(t))|\mathbf{r}'(t)|\,dt$*
- 벡터장: $\int_C \mathbf{F} \cdot d\mathbf{r} = \int_a^b \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt$

*EN: - Vector field: $\int_C \mathbf{F} \cdot d\mathbf{r} = \int_a^b \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt$*

**보존 벡터장 (Conservative Vector Fields)**

*EN: **Conservative Vector Fields***
- 어떤 스칼라 함수 $f$에 대해 $\mathbf{F} = \nabla f$이면 $\mathbf{F}$는 보존적

*EN: - $\mathbf{F}$ is conservative if $\mathbf{F} = \nabla f$ for some scalar function $f$*
- 판정: $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x}$ (2차원)

*EN: - Test: $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x}$ (in 2D)*
- 보존적인 경우: $\int_C \mathbf{F} \cdot d\mathbf{r} = f(\mathbf{r}(b)) - f(\mathbf{r}(a))$ (경로 독립)

*EN: - If conservative: $\int_C \mathbf{F} \cdot d\mathbf{r} = f(\mathbf{r}(b)) - f(\mathbf{r}(a))$ (path independent)*

**그린 정리 (Green's Theorem)**

*EN: **Green's Theorem***
- $\oint_C (P\,dx + Q\,dy) = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)\,dA$

*EN: - $\oint_C (P\,dx + Q\,dy) = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)\,dA$*

**회전과 발산 (Curl and Divergence)**

*EN: **Curl and Divergence***
- 회전: $\nabla \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ P & Q & R \end{vmatrix}$

*EN: - Curl: $\nabla \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ P & Q & R \end{vmatrix}$*
- 발산: $\nabla \cdot \mathbf{F} = \frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}$

*EN: - Divergence: $\nabla \cdot \mathbf{F} = \frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}$*

**면 적분 (Surface Integrals)**

*EN: **Surface Integrals***
- $\iint_S f\,dS = \iint_D f(\mathbf{r}(u,v))|\mathbf{r}_u \times \mathbf{r}_v|\,dA$

*EN: - $\iint_S f\,dS = \iint_D f(\mathbf{r}(u,v))|\mathbf{r}_u \times \mathbf{r}_v|\,dA$*
- 선속: $\iint_S \mathbf{F} \cdot d\mathbf{S} = \iint_S \mathbf{F} \cdot \mathbf{n}\,dS$

*EN: - Flux: $\iint_S \mathbf{F} \cdot d\mathbf{S} = \iint_S \mathbf{F} \cdot \mathbf{n}\,dS$*

**스토크스 정리 (Stokes' Theorem)**

*EN: **Stokes' Theorem***
- $\oint_C \mathbf{F} \cdot d\mathbf{r} = \iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S}$

*EN: - $\oint_C \mathbf{F} \cdot d\mathbf{r} = \iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S}$*

**발산 정리 (Divergence Theorem)**

*EN: **Divergence Theorem***
- $\iiint_E (\nabla \cdot \mathbf{F})\,dV = \iint_S \mathbf{F} \cdot d\mathbf{S}$

*EN: - $\iiint_E (\nabla \cdot \mathbf{F})\,dV = \iint_S \mathbf{F} \cdot d\mathbf{S}$*

## 🔢 선형대수

*EN: ## 🔢 Linear Algebra*

### 벡터 (Vectors)

*EN: ### Vectors*

**내적 (Dot Product)**

*EN: **Dot Product***
- $\mathbf{u} \cdot \mathbf{v} = u_1v_1 + u_2v_2 + u_3v_3 = |\mathbf{u}||\mathbf{v}|\cos\theta$

*EN: - $\mathbf{u} \cdot \mathbf{v} = u_1v_1 + u_2v_2 + u_3v_3 = |\mathbf{u}||\mathbf{v}|\cos\theta$*

**외적 (Cross Product)**

*EN: **Cross Product***
- $\mathbf{u} \times \mathbf{v} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ u_1 & u_2 & u_3 \\ v_1 & v_2 & v_3 \end{vmatrix}$

*EN: - $\mathbf{u} \times \mathbf{v} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ u_1 & u_2 & u_3 \\ v_1 & v_2 & v_3 \end{vmatrix}$*
- $|\mathbf{u} \times \mathbf{v}| = |\mathbf{u}||\mathbf{v}|\sin\theta$

*EN: - $|\mathbf{u} \times \mathbf{v}| = |\mathbf{u}||\mathbf{v}|\sin\theta$*

**스칼라 정사영과 벡터 정사영 (Scalar and Vector Projections)**

*EN: **Scalar and Vector Projections***
- 스칼라 정사영: $\text{comp}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|}$

*EN: - Scalar projection: $\text{comp}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|}$*
- 벡터 정사영: $\text{proj}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|^2}\mathbf{v}$

*EN: - Vector projection: $\text{proj}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|^2}\mathbf{v}$*

### 행렬 (Matrices)

*EN: ### Matrices*

**행렬 곱셈 (Matrix Multiplication)**

*EN: **Matrix Multiplication***
- $(AB)_{ij} = \sum_{k=1}^n a_{ik}b_{kj}$

*EN: - $(AB)_{ij} = \sum_{k=1}^n a_{ik}b_{kj}$*

**역행렬 (Matrix Inverse)**

*EN: **Matrix Inverse***
- $A^{-1}A = AA^{-1} = I$

*EN: - $A^{-1}A = AA^{-1} = I$*
- $A^{-1} = \frac{1}{\det(A)}\text{adj}(A)$ (2×2 및 3×3인 경우)

*EN: - $A^{-1} = \frac{1}{\det(A)}\text{adj}(A)$ (for 2×2 and 3×3)*

**행렬식 (Determinants)**

*EN: **Determinants***
- 2×2: $\det\begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc$

*EN: - 2×2: $\det\begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc$*
- 3×3: 여인수 전개 사용

*EN: - 3×3: Use cofactor expansion*

**성질 (Properties)**

*EN: **Properties***
- $\det(AB) = \det(A)\det(B)$

*EN: - $\det(AB) = \det(A)\det(B)$*
- $\det(A^T) = \det(A)$

*EN: - $\det(A^T) = \det(A)$*
- $\det(A^{-1}) = \frac{1}{\det(A)}$

*EN: - $\det(A^{-1}) = \frac{1}{\det(A)}$*

### 연립 일차방정식 (Systems of Linear Equations)

*EN: ### Systems of Linear Equations*

**가우스 소거법 (Gaussian Elimination)**

*EN: **Gaussian Elimination***
- 첨가 행렬 $[A|\mathbf{b}]$를 행 사다리꼴(REF)로 변환

*EN: - Reduce augmented matrix $[A|\mathbf{b}]$ to row echelon form (REF)*

**가우스-조르단 소거법 (Gauss-Jordan Elimination)**

*EN: **Gauss-Jordan Elimination***
- 기약 행 사다리꼴(RREF)로 변환

*EN: - Reduce to reduced row echelon form (RREF)*

**행렬 방정식 (Matrix Equation)**

*EN: **Matrix Equation***
- $A\mathbf{x} = \mathbf{b}$

*EN: - $A\mathbf{x} = \mathbf{b}$*
- 해: $\mathbf{x} = A^{-1}\mathbf{b}$ ($A$가 가역인 경우)

*EN: - Solution: $\mathbf{x} = A^{-1}\mathbf{b}$ (if $A$ is invertible)*

**크래머 공식 (Cramer's Rule)**

*EN: **Cramer's Rule***
- $x_i = \frac{\det(A_i)}{\det(A)}$ ($A_i$는 $i$번째 열을 $\mathbf{b}$로 대체한 행렬)

*EN: - $x_i = \frac{\det(A_i)}{\det(A)}$ where $A_i$ is $A$ with column $i$ replaced by $\mathbf{b}$*

### 고유값과 고유벡터 (Eigenvalues & Eigenvectors)

*EN: ### Eigenvalues & Eigenvectors*

**특성 방정식 (Characteristic Equation)**

*EN: **Characteristic Equation***
- $\det(A - \lambda I) = 0$

*EN: - $\det(A - \lambda I) = 0$*

**고유값과 고유벡터 (Eigenvalues and Eigenvectors)**

*EN: **Eigenvalues and Eigenvectors***
- $A\mathbf{v} = \lambda\mathbf{v}$ ($\lambda$: 고유값, $\mathbf{v}$: 고유벡터)

*EN: - $A\mathbf{v} = \lambda\mathbf{v}$ where $\lambda$ is eigenvalue and $\mathbf{v}$ is eigenvector*

**대각화 (Diagonalization)**

*EN: **Diagonalization***
- $A = PDP^{-1}$ ($D$는 고유값의 대각 행렬, $P$는 고유벡터 행렬)

*EN: - $A = PDP^{-1}$ where $D$ is diagonal matrix of eigenvalues and $P$ is matrix of eigenvectors*

### 벡터 공간 (Vector Spaces)

*EN: ### Vector Spaces*

**생성 (Span)**

*EN: **Span***
- $\text{span}(\mathbf{v}_1, \ldots, \mathbf{v}_n) = \{c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n : c_i \in \mathbb{R}\}$

*EN: - $\text{span}(\mathbf{v}_1, \ldots, \mathbf{v}_n) = \{c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n : c_i \in \mathbb{R}\}$*

**일차 독립 (Linear Independence)**

*EN: **Linear Independence***
- $c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n = \mathbf{0}$이 $c_1 = \cdots = c_n = 0$만을 의미할 때 벡터들은 일차 독립

*EN: - Vectors are linearly independent if $c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n = \mathbf{0}$ implies $c_1 = \cdots = c_n = 0$*

**차원 정리 (Rank-Nullity Theorem)**

*EN: **Rank-Nullity Theorem***
- $\dim(\text{Col } A) + \dim(\text{Nul } A) = n$ (열의 개수)

*EN: - $\dim(\text{Col } A) + \dim(\text{Nul } A) = n$ (number of columns)*

### 내적 공간 (Inner Product Spaces)

*EN: ### Inner Product Spaces*

**내적 (Inner Product)**

*EN: **Inner Product***
- $\langle \mathbf{u}, \mathbf{v} \rangle = \mathbf{u}^T\mathbf{v}$ (표준 내적)

*EN: - $\langle \mathbf{u}, \mathbf{v} \rangle = \mathbf{u}^T\mathbf{v}$ (standard inner product)*

**노름 (Norm)**

*EN: **Norm***
- $\|\mathbf{v}\| = \sqrt{\langle \mathbf{v}, \mathbf{v} \rangle}$

*EN: - $\|\mathbf{v}\| = \sqrt{\langle \mathbf{v}, \mathbf{v} \rangle}$*

**그람-슈미트 과정 (Gram-Schmidt Process)**

*EN: **Gram-Schmidt Process***
- 벡터 직교화: $\mathbf{v}_k = \mathbf{u}_k - \sum_{j=1}^{k-1} \frac{\langle \mathbf{u}_k, \mathbf{v}_j \rangle}{\langle \mathbf{v}_j, \mathbf{v}_j \rangle}\mathbf{v}_j$

*EN: - Orthogonalize vectors: $\mathbf{v}_k = \mathbf{u}_k - \sum_{j=1}^{k-1} \frac{\langle \mathbf{u}_k, \mathbf{v}_j \rangle}{\langle \mathbf{v}_j, \mathbf{v}_j \rangle}\mathbf{v}_j$*

**QR 분해 (QR Factorization)**

*EN: **QR Factorization***
- $A = QR$ ($Q$는 정규 직교 열, $R$은 상삼각 행렬)

*EN: - $A = QR$ where $Q$ has orthonormal columns and $R$ is upper triangular*

## 📊 미분방정식 (Differential Equations)

*EN: ## 📊 Differential Equations*

### 1계 상미분방정식 (First Order ODEs)

*EN: ### First Order ODEs*

**분리 가능 (Separable)**

*EN: **Separable***
- $\frac{dy}{dx} = g(x)h(y)$

*EN: - $\frac{dy}{dx} = g(x)h(y)$*
- 해: $\int \frac{1}{h(y)}\,dy = \int g(x)\,dx$

*EN: - Solution: $\int \frac{1}{h(y)}\,dy = \int g(x)\,dx$*

**선형 (Linear)**

*EN: **Linear***
- $\frac{dy}{dx} + P(x)y = Q(x)$

*EN: - $\frac{dy}{dx} + P(x)y = Q(x)$*
- 적분 인자: $\mu(x) = e^{\int P(x)\,dx}$

*EN: - Integrating factor: $\mu(x) = e^{\int P(x)\,dx}$*
- 해: $y = \frac{1}{\mu(x)}\left[\int \mu(x)Q(x)\,dx + C\right]$

*EN: - Solution: $y = \frac{1}{\mu(x)}\left[\int \mu(x)Q(x)\,dx + C\right]$*

**완전 (Exact)**

*EN: **Exact***
- $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$이면 $M(x,y)\,dx + N(x,y)\,dy = 0$은 완전미분방정식

*EN: - $M(x,y)\,dx + N(x,y)\,dy = 0$ is exact if $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$*
- 해: $\frac{\partial F}{\partial x} = M$이고 $\frac{\partial F}{\partial y} = N$인 $F(x,y)$ 구하기

*EN: - Solution: Find $F(x,y)$ such that $\frac{\partial F}{\partial x} = M$ and $\frac{\partial F}{\partial y} = N$*

**베르누이 (Bernoulli)**

*EN: **Bernoulli***
- $\frac{dy}{dx} + P(x)y = Q(x)y^n$

*EN: - $\frac{dy}{dx} + P(x)y = Q(x)y^n$*
- 치환: $v = y^{1-n}$

*EN: - Substitution: $v = y^{1-n}$*

### 2계 상미분방정식 (Second Order ODEs)

*EN: ### Second Order ODEs*

**상수 계수 동차 (Homogeneous with Constant Coefficients)**

*EN: **Homogeneous with Constant Coefficients***
- $ay'' + by' + cy = 0$

*EN: - $ay'' + by' + cy = 0$*
- 특성방정식: $ar^2 + br + c = 0$

*EN: - Characteristic equation: $ar^2 + br + c = 0$*
- 근의 종류에 따른 해:

*EN: - Solutions depend on roots:*
  - 서로 다른 실근: $y = c_1e^{r_1x} + c_2e^{r_2x}$

*EN:   - Real distinct: $y = c_1e^{r_1x} + c_2e^{r_2x}$*
  - 중근: $y = c_1e^{rx} + c_2xe^{rx}$

*EN:   - Repeated root: $y = c_1e^{rx} + c_2xe^{rx}$*
  - 복소수 근: $r = \alpha \pm \beta i$, $y = e^{\alpha x}(c_1\cos\beta x + c_2\sin\beta x)$

*EN:   - Complex: $r = \alpha \pm \beta i$, $y = e^{\alpha x}(c_1\cos\beta x + c_2\sin\beta x)$*

**비동차 (Non-homogeneous)**

*EN: **Non-homogeneous***
- $ay'' + by' + cy = f(x)$

*EN: - $ay'' + by' + cy = f(x)$*
- 일반해: $y = y_h + y_p$

*EN: - General solution: $y = y_h + y_p$*
- **미정계수법 (Method of undetermined coefficients)**: $f(x)$에 따라 $y_p$의 형태 추정

*EN: - **Method of undetermined coefficients**: Guess form of $y_p$ based on $f(x)$*
- **매개변수 변환법 (Variation of parameters)**: $y_p = u_1(x)y_1 + u_2(x)y_2$

*EN: - **Variation of parameters**: $y_p = u_1(x)y_1 + u_2(x)y_2$*
  - 론스키안: $W = y_1y_2' - y_1'y_2$

*EN:   - Wronskian: $W = y_1y_2' - y_1'y_2$*
  - $u_1' = -\frac{y_2f}{aW}$, $u_2' = \frac{y_1f}{aW}$

*EN:   - $u_1' = -\frac{y_2f}{aW}$, $u_2' = \frac{y_1f}{aW}$*

### 라플라스 변환 (Laplace Transform)

*EN: ### Laplace Transform*

**정의 (Definition)**

*EN: **Definition***
- $\mathcal{L}\{f(t)\} = F(s) = \int_0^{\infty} e^{-st}f(t)\,dt$

*EN: - $\mathcal{L}\{f(t)\} = F(s) = \int_0^{\infty} e^{-st}f(t)\,dt$*

**주요 변환 (Common Transforms)**

*EN: **Common Transforms***
- $\mathcal{L}\{1\} = \frac{1}{s}$

*EN: - $\mathcal{L}\{1\} = \frac{1}{s}$*
- $\mathcal{L}\{t^n\} = \frac{n!}{s^{n+1}}$

*EN: - $\mathcal{L}\{t^n\} = \frac{n!}{s^{n+1}}$*
- $\mathcal{L}\{e^{at}\} = \frac{1}{s-a}$

*EN: - $\mathcal{L}\{e^{at}\} = \frac{1}{s-a}$*
- $\mathcal{L}\{\sin(bt)\} = \frac{b}{s^2 + b^2}$

*EN: - $\mathcal{L}\{\sin(bt)\} = \frac{b}{s^2 + b^2}$*
- $\mathcal{L}\{\cos(bt)\} = \frac{s}{s^2 + b^2}$

*EN: - $\mathcal{L}\{\cos(bt)\} = \frac{s}{s^2 + b^2}$*

**성질 (Properties)**

*EN: **Properties***
- 선형성: $\mathcal{L}\{af + bg\} = a\mathcal{L}\{f\} + b\mathcal{L}\{g\}$

*EN: - Linearity: $\mathcal{L}\{af + bg\} = a\mathcal{L}\{f\} + b\mathcal{L}\{g\}$*
- 1계 도함수: $\mathcal{L}\{f'\} = s\mathcal{L}\{f\} - f(0)$

*EN: - First derivative: $\mathcal{L}\{f'\} = s\mathcal{L}\{f\} - f(0)$*
- 2계 도함수: $\mathcal{L}\{f''\} = s^2\mathcal{L}\{f\} - sf(0) - f'(0)$

*EN: - Second derivative: $\mathcal{L}\{f''\} = s^2\mathcal{L}\{f\} - sf(0) - f'(0)$*
- 이동: $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$

*EN: - Shifting: $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$*

### 편미분방정식 (Partial Differential Equations)

*EN: ### Partial Differential Equations*

**열 방정식 (Heat Equation)**

*EN: **Heat Equation***
- $\frac{\partial u}{\partial t} = \alpha^2 \frac{\partial^2 u}{\partial x^2}$

*EN: - $\frac{\partial u}{\partial t} = \alpha^2 \frac{\partial^2 u}{\partial x^2}$*

**파동 방정식 (Wave Equation)**

*EN: **Wave Equation***
- $\frac{\partial^2 u}{\partial t^2} = c^2 \frac{\partial^2 u}{\partial x^2}$

*EN: - $\frac{\partial^2 u}{\partial t^2} = c^2 \frac{\partial^2 u}{\partial x^2}$*

**라플라스 방정식 (Laplace's Equation)**

*EN: **Laplace's Equation***
- $\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0$

*EN: - $\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0$*

**변수 분리법 (Separation of Variables)**

*EN: **Separation of Variables***
- $u(x,t) = X(x)T(t)$로 가정

*EN: - Assume $u(x,t) = X(x)T(t)$*
- 대입 후 변수 분리

*EN: - Substitute and separate variables*

## 📈 확률 & 통계

*EN: ## 📈 Probability & Statistics*

### 확률

*EN: ### Probability*

**기본 확률 (Basic Probability)**

*EN: **Basic Probability***
- $0 \leq P(A) \leq 1$

*EN: - $0 \leq P(A) \leq 1$*
- $P(A^c) = 1 - P(A)$

*EN: - $P(A^c) = 1 - P(A)$*
- $P(A \cup B) = P(A) + P(B) - P(A \cap B)$

*EN: - $P(A \cup B) = P(A) + P(B) - P(A \cap B)$*

**조건부 확률 (Conditional Probability)**

*EN: **Conditional Probability***
- $P(A|B) = \frac{P(A \cap B)}{P(B)}$

*EN: - $P(A|B) = \frac{P(A \cap B)}{P(B)}$*

**독립 (Independence)**

*EN: **Independence***
- $P(A \cap B) = P(A)P(B)$

*EN: - $P(A \cap B) = P(A)P(B)$*

**베이즈 정리 (Bayes' Theorem)**

*EN: **Bayes' Theorem***
- $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

*EN: - $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$*

**전체 확률의 법칙 (Law of Total Probability)**

*EN: **Law of Total Probability***
- $P(B) = \sum_{i=1}^n P(B|A_i)P(A_i)$

*EN: - $P(B) = \sum_{i=1}^n P(B|A_i)P(A_i)$*

### 경우의 수 (Counting)

*EN: ### Counting*

**순열 (Permutations)**

*EN: **Permutations***
- $P(n,r) = \frac{n!}{(n-r)!}$

*EN: - $P(n,r) = \frac{n!}{(n-r)!}$*

**조합 (Combinations)**

*EN: **Combinations***
- $C(n,r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}$

*EN: - $C(n,r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}$*

### 확률 변수 (Random Variables)

*EN: ### Random Variables*

**기댓값 (Expected Value)**

*EN: **Expected Value***
- 이산: $E[X] = \sum_x x \cdot P(X=x)$

*EN: - Discrete: $E[X] = \sum_x x \cdot P(X=x)$*
- 연속: $E[X] = \int_{-\infty}^{\infty} x f(x)\,dx$

*EN: - Continuous: $E[X] = \int_{-\infty}^{\infty} x f(x)\,dx$*

**분산 (Variance)**

*EN: **Variance***
- $\text{Var}(X) = E[(X-\mu)^2] = E[X^2] - (E[X])^2$

*EN: - $\text{Var}(X) = E[(X-\mu)^2] = E[X^2] - (E[X])^2$*

**표준 편차 (Standard Deviation)**

*EN: **Standard Deviation***
- $\sigma = \sqrt{\text{Var}(X)}$

*EN: - $\sigma = \sqrt{\text{Var}(X)}$*

### 이산 분포 (Discrete Distributions)

*EN: ### Discrete Distributions*

**이항 분포 (Binomial)**

*EN: **Binomial***
- $P(X = k) = \binom{n}{k}p^k(1-p)^{n-k}$

*EN: - $P(X = k) = \binom{n}{k}p^k(1-p)^{n-k}$*
- $E[X] = np$, $\text{Var}(X) = np(1-p)$

*EN: - $E[X] = np$, $\text{Var}(X) = np(1-p)$*

**기하 분포 (Geometric)**

*EN: **Geometric***
- $P(X = k) = (1-p)^{k-1}p$

*EN: - $P(X = k) = (1-p)^{k-1}p$*
- $E[X] = \frac{1}{p}$, $\text{Var}(X) = \frac{1-p}{p^2}$

*EN: - $E[X] = \frac{1}{p}$, $\text{Var}(X) = \frac{1-p}{p^2}$*

**포아송 분포 (Poisson)**

*EN: **Poisson***
- $P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}$

*EN: - $P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}$*
- $E[X] = \lambda$, $\text{Var}(X) = \lambda$

*EN: - $E[X] = \lambda$, $\text{Var}(X) = \lambda$*

### 연속 분포 (Continuous Distributions)

*EN: ### Continuous Distributions*

**균등 분포 (Uniform)**

*EN: **Uniform***
- $f(x) = \frac{1}{b-a}$ ($a \leq x \leq b$인 경우)

*EN: - $f(x) = \frac{1}{b-a}$ for $a \leq x \leq b$*
- $E[X] = \frac{a+b}{2}$, $\text{Var}(X) = \frac{(b-a)^2}{12}$

*EN: - $E[X] = \frac{a+b}{2}$, $\text{Var}(X) = \frac{(b-a)^2}{12}$*

**정규 분포 (Normal)**

*EN: **Normal***
- $f(x) = \frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$

*EN: - $f(x) = \frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$*
- $E[X] = \mu$, $\text{Var}(X) = \sigma^2$

*EN: - $E[X] = \mu$, $\text{Var}(X) = \sigma^2$*
- 표준 정규: $Z = \frac{X-\mu}{\sigma}$

*EN: - Standard normal: $Z = \frac{X-\mu}{\sigma}$*

**지수 분포 (Exponential)**

*EN: **Exponential***
- $f(x) = \lambda e^{-\lambda x}$ ($x \geq 0$인 경우)

*EN: - $f(x) = \lambda e^{-\lambda x}$ for $x \geq 0$*
- $E[X] = \frac{1}{\lambda}$, $\text{Var}(X) = \frac{1}{\lambda^2}$

*EN: - $E[X] = \frac{1}{\lambda}$, $\text{Var}(X) = \frac{1}{\lambda^2}$*

### 통계적 추론 (Statistical Inference)

*EN: ### Statistical Inference*

**표본 평균 (Sample Mean)**

*EN: **Sample Mean***
- $\bar{X} = \frac{1}{n}\sum_{i=1}^n X_i$

*EN: - $\bar{X} = \frac{1}{n}\sum_{i=1}^n X_i$*
- $E[\bar{X}] = \mu$, $\text{Var}(\bar{X}) = \frac{\sigma^2}{n}$

*EN: - $E[\bar{X}] = \mu$, $\text{Var}(\bar{X}) = \frac{\sigma^2}{n}$*

**중심 극한 정리 (Central Limit Theorem)**

*EN: **Central Limit Theorem***
- 큰 $n$에 대해 $\bar{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right)$

*EN: - $\bar{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right)$ for large $n$*

**평균의 신뢰 구간 (Confidence Interval for Mean)**

*EN: **Confidence Interval for Mean***
- $\bar{x} \pm z_{\alpha/2}\frac{\sigma}{\sqrt{n}}$ ($\sigma$를 알고 있는 경우)

*EN: - $\bar{x} \pm z_{\alpha/2}\frac{\sigma}{\sqrt{n}}$ (known $\sigma$)*
- $\bar{x} \pm t_{\alpha/2,n-1}\frac{s}{\sqrt{n}}$ ($\sigma$를 모르는 경우)

*EN: - $\bar{x} \pm t_{\alpha/2,n-1}\frac{s}{\sqrt{n}}$ (unknown $\sigma$)*

**가설 검정 (Hypothesis Testing)**

*EN: **Hypothesis Testing***
- 검정 통계량: $z = \frac{\bar{x} - \mu_0}{\sigma/\sqrt{n}}$ 또는 $t = \frac{\bar{x} - \mu_0}{s/\sqrt{n}}$

*EN: - Test statistic: $z = \frac{\bar{x} - \mu_0}{\sigma/\sqrt{n}}$ or $t = \frac{\bar{x} - \mu_0}{s/\sqrt{n}}$*
- p-값: $H_0$가 참일 때 관측값 이상의 극단값이 나타날 확률

*EN: - p-value: probability of observing result at least as extreme given $H_0$ is true*
- p-값 $< \alpha$이면 $H_0$ 기각

*EN: - Reject $H_0$ if p-value $< \alpha$*

### 회귀 (Regression)

*EN: ### Regression*

**단순 선형 회귀 (Simple Linear Regression)**

*EN: **Simple Linear Regression***
- 모형: $Y = \beta_0 + \beta_1 X + \epsilon$

*EN: - Model: $Y = \beta_0 + \beta_1 X + \epsilon$*
- 추정량: $\hat{\beta}_1 = \frac{\sum(x_i - \bar{x})(y_i - \bar{y})}{\sum(x_i - \bar{x})^2}$, $\hat{\beta}_0 = \bar{y} - \hat{\beta}_1\bar{x}$

*EN: - Estimates: $\hat{\beta}_1 = \frac{\sum(x_i - \bar{x})(y_i - \bar{y})}{\sum(x_i - \bar{x})^2}$, $\hat{\beta}_0 = \bar{y} - \hat{\beta}_1\bar{x}$*
- $R^2 = 1 - \frac{SS_{\text{res}}}{SS_{\text{tot}}}$

*EN: - $R^2 = 1 - \frac{SS_{\text{res}}}{SS_{\text{tot}}}$*

## 🎲 이산 수학 (Discrete Mathematics)

*EN: ## 🎲 Discrete Mathematics*

### 논리

*EN: ### Logic*

**논리 연산자 (Logical Operators)**

*EN: **Logical Operators***
- 부정: $\neg p$

*EN: - Negation: $\neg p$*
- 논리곱: $p \wedge q$ (그리고)

*EN: - Conjunction: $p \wedge q$ (and)*
- 논리합: $p \vee q$ (또는)

*EN: - Disjunction: $p \vee q$ (or)*
- 함의: $p \to q$ (p이면 q)

*EN: - Implication: $p \to q$ (if p then q)*
- 쌍조건: $p \leftrightarrow q$ (필요충분조건)

*EN: - Biconditional: $p \leftrightarrow q$ (if and only if)*

**드 모르간 법칙 (De Morgan's Laws)**

*EN: **De Morgan's Laws***
- $\neg(p \wedge q) \equiv \neg p \vee \neg q$

*EN: - $\neg(p \wedge q) \equiv \neg p \vee \neg q$*
- $\neg(p \vee q) \equiv \neg p \wedge \neg q$

*EN: - $\neg(p \vee q) \equiv \neg p \wedge \neg q$*

### 집합론 (Set Theory)

*EN: ### Set Theory*

**집합 연산 (Set Operations)**

*EN: **Set Operations***
- 합집합: $A \cup B = \{x : x \in A \text{ 또는 } x \in B\}$

*EN: - Union: $A \cup B = \{x : x \in A \text{ or } x \in B\}$*
- 교집합: $A \cap B = \{x : x \in A \text{ 그리고 } x \in B\}$

*EN: - Intersection: $A \cap B = \{x : x \in A \text{ and } x \in B\}$*
- 차집합: $A - B = \{x : x \in A \text{ 그리고 } x \notin B\}$

*EN: - Difference: $A - B = \{x : x \in A \text{ and } x \notin B\}$*
- 여집합: $A^c = \{x : x \notin A\}$

*EN: - Complement: $A^c = \{x : x \notin A\}$*

**기수 (Cardinality)**

*EN: **Cardinality***
- $|A \cup B| = |A| + |B| - |A \cap B|$

*EN: - $|A \cup B| = |A| + |B| - |A \cap B|$*
- $|A \times B| = |A| \cdot |B|$

*EN: - $|A \times B| = |A| \cdot |B|$*

### 조합론 (Combinatorics)

*EN: ### Combinatorics*

**이항 정리 (Binomial Theorem)**

*EN: **Binomial Theorem***
- $(x+y)^n = \sum_{k=0}^n \binom{n}{k}x^{n-k}y^k$

*EN: - $(x+y)^n = \sum_{k=0}^n \binom{n}{k}x^{n-k}y^k$*

**비둘기집 원리 (Pigeonhole Principle)**

*EN: **Pigeonhole Principle***
- $n+1$개의 물건을 $n$개의 상자에 넣으면, 최소 한 상자에는 물건이 2개 이상 들어감

*EN: - If $n+1$ objects are placed into $n$ boxes, at least one box contains at least 2 objects*

**포함-배제 원리 (Inclusion-Exclusion Principle)**

*EN: **Inclusion-Exclusion Principle***
- $|A_1 \cup A_2 \cup \cdots \cup A_n| = \sum |A_i| - \sum |A_i \cap A_j| + \sum |A_i \cap A_j \cap A_k| - \cdots$

*EN: - $|A_1 \cup A_2 \cup \cdots \cup A_n| = \sum |A_i| - \sum |A_i \cap A_j| + \sum |A_i \cap A_j \cap A_k| - \cdots$*

### 그래프 이론 (Graph Theory)

*EN: ### Graph Theory*

**악수 보조정리 (Handshaking Lemma)**

*EN: **Handshaking Lemma***
- $\sum_{v \in V} \deg(v) = 2|E|$

*EN: - $\sum_{v \in V} \deg(v) = 2|E|$*

**오일러 공식 — 평면 그래프 (Euler's Formula for Planar Graphs)**

*EN: **Euler's Formula (Planar Graphs)***
- $v - e + f = 2$ ($v$: 꼭짓점, $e$: 변, $f$: 면)

*EN: - $v - e + f = 2$ where $v$ = vertices, $e$ = edges, $f$ = faces*

**그래프 채색 (Graph Coloring)**

*EN: **Graph Coloring***
- 채색수 $\chi(G)$: 꼭짓점을 색칠하는 데 필요한 최소 색의 수

*EN: - Chromatic number $\chi(G)$: minimum colors needed to color vertices*

### 정수론 (Number Theory)

*EN: ### Number Theory*

**나눗셈 알고리즘 (Division Algorithm)**

*EN: **Division Algorithm***
- $a = bq + r$ ($0 \leq r < b$)

*EN: - $a = bq + r$ where $0 \leq r < b$*

**유클리드 알고리즘 — 최대공약수 (Euclidean Algorithm, GCD)**

*EN: **Euclidean Algorithm (GCD)***
- 나머지가 0이 될 때까지 $\gcd(a,b) = \gcd(b, a \bmod b)$ 반복 적용

*EN: - Repeatedly apply $\gcd(a,b) = \gcd(b, a \bmod b)$ until remainder is 0*

**베주의 항등식 (Bézout's Identity)**

*EN: **Bézout's Identity***
- $d = \gcd(a,b)$이면, $ax + by = d$를 만족하는 정수 $x, y$가 존재

*EN: - If $d = \gcd(a,b)$, then there exist integers $x,y$ such that $ax + by = d$*

**산술의 기본 정리 (Fundamental Theorem of Arithmetic)**

*EN: **Fundamental Theorem of Arithmetic***
- $n > 1$인 모든 정수는 소수의 곱으로 유일하게 표현됨

*EN: - Every integer $n > 1$ can be uniquely written as a product of primes*

**페르마의 소정리 (Fermat's Little Theorem)**

*EN: **Fermat's Little Theorem***
- $p$가 소수이고 $\gcd(a,p) = 1$이면, $a^{p-1} \equiv 1 \pmod{p}$

*EN: - If $p$ is prime and $\gcd(a,p) = 1$, then $a^{p-1} \equiv 1 \pmod{p}$*

**오일러의 정리 (Euler's Theorem)**

*EN: **Euler's Theorem***
- $\gcd(a,n) = 1$이면, $a^{\phi(n)} \equiv 1 \pmod{n}$

*EN: - If $\gcd(a,n) = 1$, then $a^{\phi(n)} \equiv 1 \pmod{n}$*

**중국인의 나머지 정리 (Chinese Remainder Theorem)**

*EN: **Chinese Remainder Theorem***
- $m_i$가 쌍마다 서로소이면, $x \equiv a_i \pmod{m_i}$ 연립합동식은 $M = \prod m_i$를 법으로 하는 유일한 해를 가짐

*EN: - System $x \equiv a_i \pmod{m_i}$ has unique solution modulo $M = \prod m_i$ if $m_i$ are pairwise coprime*
