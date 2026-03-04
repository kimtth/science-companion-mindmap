# 일반 수학 개요

*EN: # General Mathematics Overview*

> **네비게이션:** [허브](../math.md) | [미적분](../math/math-calculus.md) | [선형대수](../math/math-linear-algebra.md) | [미분 방정식](../math/math-differential-equations.md) | [확률 & 통계](../math/math-probability-statistics.md) | [이산 수학](../math/math-discrete.md) | [논리 & 수학기초](../math/math-logic-foundations.md) | [방정식](math-equations.md) | [용어집](math-terminology.md)

*EN: > \*\*Navigation:\*\* [Hub](../math.md) | [Calculus](../math/math-calculus.md) | [Linear Algebra](../math/math-linear-algebra.md) | [Differential Equations](../math/math-differential-equations.md) | [Probability & Statistics](../math/math-probability-statistics.md) | [Discrete Math](../math/math-discrete.md) | [Logic & Foundations](../math/math-logic-foundations.md) | [Equations](math-equations.md) | [Terminology](math-terminology.md)*

## 📋 목차

*EN: ## 📋 Table of Contents*
1. [미적분](#1-미적분)

*EN: 1. [Calculus](#1-calculus)*
2. [선형대수](#2-선형대수)

*EN: 2. [Linear Algebra](#2-linear-algebra)*
3. [미분 방정식](#3-미분-방정식)

*EN: 3. [Differential Equations](#3-differential-equations)*
4. [확률 & 통계](#4-확률--통계)

*EN: 4. [Probability & Statistics](#4-probability--statistics)*
5. [이산 수학](#5-이산-수학)

*EN: 5. [Discrete Mathematics](#5-discrete-mathematics)*
6. [수리논리 & 수학기초](#6-수리논리--수학기초)

*EN: 6. [Mathematical Logic & Foundations](#6-mathematical-logic--foundations)*

---

## 🎯 목적

*EN: ## 🎯 Purpose*
이 마인드맵은 미적분과 선형대수부터 확률, 통계, 이산 수학에 이르는 기본 개념을 포함하는 대학 수준 수학의 포괄적인 개요를 제공합니다. 수학적 아이디어들 간의 계층적 관계와 그 응용을 이해하기 위한 시각적·개념적 가이드 역할을 합니다.

*EN: This mindmap provides a comprehensive overview of college-level mathematics, covering fundamental concepts from calculus and linear algebra to probability, statistics, and discrete mathematics. It serves as a visual and conceptual guide for understanding the hierarchical relationships between mathematical ideas and their applications.*

## 📚 주요 주제

*EN: ## 📚 Main Topics*

### 1. 미적분

*EN: ### 1. Calculus*
연속 변화의 수학 - 변화율, 누적, 최적화를 이해하는 학문. 미적분은 현대 과학과 공학의 기반입니다:

*EN: The mathematics of continuous change - understanding rates, accumulation, and optimization. Calculus is the foundation of modern science and engineering:*

**극한과 연속성**

*EN: \*\*Limits & Continuity\*\**
- **극한의 엡실론-델타 정의**: ε-δ 기호를 사용하는 엄격한 형식적 정의

*EN: - \*\*Epsilon-delta definition of limits\*\*: Rigorous formal definition using ε-δ notation*
  - 모든 ε > 0에 대해: 0 < |x - a| < δ일 때 |f(x) - L| < ε인 δ > 0가 존재

*EN:   - For every ε > 0, there exists δ > 0 such that |f(x) - L| < ε when 0 < |x - a| < δ*
  - "값에 접근한다"는 직관적 개념을 형식화

*EN:   - Formalizes the intuitive notion of "approaching a value"*
  - 미적분학 전체의 기초

*EN:   - Foundation for all of calculus*
- **극한 법칙과 성질**: 극한을 계산하는 대수적 규칙

*EN: - \*\*Limit laws and properties\*\*: Algebraic rules for computing limits*
  - 합, 차, 곱, 몫 규칙

*EN:   - Sum, difference, product, quotient rules*
  - 다항함수, 유리함수의 극한

*EN:   - Limits of polynomials, rational functions*
  - 어려운 극한을 위한 샌드위치 정리

*EN:   - Squeeze theorem for difficult limits*
- **연속성의 정의와 정리**: x→a일 때 lim f(x) = f(a)이면 함수가 연속

*EN: - \*\*Continuity definitions and theorems\*\*: Function continuous if lim f(x) = f(a) as x→a*
  - 함수가 해당 점에서 정의되고, 극한이 존재하고, 두 값이 같아야 함

*EN:   - Requires function defined at point, limit exists, and they're equal*
  - 연속 함수는 구간을 보존

*EN:   - Continuous functions preserve intervals*
  - 연속 함수의 합, 곱, 합성도 연속

*EN:   - Sums, products, compositions of continuous functions are continuous*
- **중간값 정리**: 연속 함수는 f(a)와 f(b) 사이의 모든 값을 취함

*EN: - \*\*Intermediate Value Theorem\*\*: Continuous function takes all values between f(a) and f(b)*
  - 근의 존재를 보장

*EN:   - Guarantees existence of roots*
  - 방정식에 해가 있음을 증명하는 데 사용

*EN:   - Used to prove equations have solutions*
- **불연속의 유형**: 점프, 제거 가능, 무한

*EN: - \*\*Types of discontinuities\*\*: Jump, removable, infinite*
  - 점프: 좌우 극한은 존재하지만 서로 다름

*EN:   - Jump: left and right limits exist but differ*
  - 제거 가능: 극한은 존재하지만 함수값과 다름

*EN:   - Removable: limit exists but doesn't equal function value*
  - 무한: 함수가 ±∞에 접근

*EN:   - Infinite: function approaches ±∞*

**미분법**

*EN: \*\*Differentiation\*\**
- **극한을 이용한 정의**: f'(x) = lim[h→0] (f(x+h) - f(x))/h

*EN: - \*\*Definition using limits\*\*: f'(x) = lim[h→0] (f(x+h) - f(x))/h*
  - 순간 변화율 측정

*EN:   - Measures instantaneous rate of change*
  - 한 점에서 접선의 기울기

*EN:   - Slope of tangent line at a point*
  - 속도는 위치의 도함수

*EN:   - Velocity is derivative of position*
- **멱 규칙, 곱 규칙, 멫 규칙, 연쇄 규칙**: 미분 단축법

*EN: - \*\*Power rule, product rule, quotient rule, chain rule\*\*: Differentiation shortcuts*
  - 멱: d/dx(x^n) = nx^(n-1)

*EN:   - Power: d/dx(x^n) = nx^(n-1)*
  - 곱: (uv)' = u'v + uv'

*EN:   - Product: (uv)' = u'v + uv'*
  - 멫: (u/v)' = (u'v - uv')/v²

*EN:   - Quotient: (u/v)' = (u'v - uv')/v²*
  - 연쇄: d/dx f(g(x)) = f'(g(x))·g'(x)

*EN:   - Chain: d/dx f(g(x)) = f'(g(x))·g'(x)*
- **음함수 미분법**: y에 대해 풀지 않은 방정식의 미분

*EN: - \*\*Implicit differentiation\*\*: Differentiating equations not solved for y*
  - x² + y² = 1과 같은 관계에 사용

*EN:   - Used for relations like x² + y² = 1*
  - y를 x의 함수로 보고 연쇄 규칙 적용

*EN:   - Treat y as function of x and use chain rule*
- **고차 도함수**: f'', f''', f^(n)

*EN: - \*\*Higher-order derivatives\*\*: f'', f''', f^(n)*
  - 2차 도함수는 볼록(acceleration)을 측정

*EN:   - Second derivative measures concavity (acceleration)*
  - 최적화와 곡선 분석에 사용

*EN:   - Used for optimization and curve analysis*
- **응용**: 접선, 최적화, 연관 변화율, 곡선 스케치

*EN: - \*\*Applications\*\*: tangent lines, optimization, related rates, curve sketching*
  - 최적화: f'(x) = 0을 사용하여 최댓값/최졯값 찾기

*EN:   - Optimization: find max/min using f'(x) = 0*
  - 연관 변화율: 관련된 양들의 변화율 연결

*EN:   - Related rates: connect rates of change of related quantities*
  - 곡선 스케치: 증감소, 볼록, 변곡점

*EN:   - Curve sketching: increasing/decreasing, concavity, inflection points*
- **평균값 정리**: (a,b)에서 어녤 c에 대해 f'(c) = (f(b) - f(a))/(b - a)

*EN: - \*\*Mean Value Theorem\*\*: f'(c) = (f(b) - f(a))/(b - a) for some c in (a,b)*
  - 순간 변화율이 평균 변화율과 같아지는 점의 존재를 보장

*EN:   - Guarantees instantaneous rate equals average rate somewhere*
  - 많은 미적분 정리의 기초

*EN:   - Foundation for many calculus theorems*

**적분법**

*EN: \*\*Integration\*\**
- **리만 합과 정적분**: 넓이를 근사하는 사각형의 합

*EN: - \*\*Riemann sums and definite integrals\*\*: Sum of rectangles approximating area*
  - ∫[a,b] f(x)dx = lim[n→∞] Σf(x_i)Δx

*EN:   - ∫[a,b] f(x)dx = lim[n→∞] Σf(x_i)Δx*
  - 무한소 양의 누적

*EN:   - Accumulation of infinitesimal quantities*
  - 곡선 아래의 정확한 넓이

*EN:   - Exact area under curve*
- **미적분학의 기본 정리 (1부, 2부)**: 도함수와 적분을 연결

*EN: - \*\*Fundamental Theorem of Calculus (both parts)\*\*: Links derivatives and integrals*
  - 1부: d/dx ∫[a,x] f(t)dt = f(x)

*EN:   - Part 1: d/dx ∫[a,x] f(t)dt = f(x)*
  - 2부: ∫[a,b] f(x)dx = F(b) - F(a), 단 F' = f

*EN:   - Part 2: ∫[a,b] f(x)dx = F(b) - F(a) where F' = f*
  - 적분은 미분의 역연산

*EN:   - Integration reverses differentiation*
- **적분법**: 부정적분을 계산하는 방법

*EN: - \*\*Integration techniques\*\*: Methods for computing antiderivatives*
  - 치환적분 (u-치환): 연쇄 규칙의 역연산

*EN:   - Substitution (u-substitution): reverses chain rule*
  - 부분적분법: ∫udv = uv - ∫vdu (곱 규칙의 역연산)

*EN:   - Integration by parts: ∫udv = uv - ∫vdu (reverses product rule)*
  - 부분분수 분해: 유리함수 분해

*EN:   - Partial fractions: decompose rational functions*
  - 삼각치환: √(a²-x²), √(a²+x²), √(x²-a²) 형태

*EN:   - Trigonometric substitution: for √(a²-x²), √(a²+x²), √(x²-a²)*
- **이상 적분**: 무한 범위 또는 무한 불연속점

*EN: - \*\*Improper integrals\*\*: Infinite limits or infinite discontinuities*
  - ∫[a,∞) f(x)dx = lim[b→∞] ∫[a,b] f(x)dx

*EN:   - ∫[a,∞) f(x)dx = lim[b→∞] ∫[a,b] f(x)dx*
  - 수렴 vs 발산

*EN:   - Convergence vs divergence*
- **응용**: 넓이, 부피, 호의 길이, 일

*EN: - \*\*Applications\*\*: area, volume, arc length, work*
  - 곡선 사이 넓이: ∫(f(x) - g(x))dx

*EN:   - Area between curves: ∫(f(x) - g(x))dx*
  - 부피: 원판 법 (πr²), 와셔 법, 원통껍질 법 (2πrh)

*EN:   - Volume: disk method (πr²), washer method, shell method (2πrh)*
  - 호의 길이: ∫√(1 + (f'(x))²)dx

*EN:   - Arc length: ∫√(1 + (f'(x))²)dx*
  - 일: ∫F(x)dx (힘 × 거리)

*EN:   - Work: ∫F(x)dx (force times distance)*

**수열과 급수**

*EN: \*\*Sequences & Series\*\**
- **수열 수렴**: lim[n→∞] a_n = L

*EN: - \*\*Sequence convergence\*\*: lim[n→∞] a_n = L*
  - 유계이고 단조로운 수열은 수렴

*EN:   - Bounded and monotonic sequences converge*
  - 수열을 위한 샌드위치 정리

*EN:   - Squeeze theorem for sequences*
- **무한 급수**: n=1부터 ∞까지 Σa_n

*EN: - \*\*Infinite series\*\*: Σa_n from n=1 to ∞*
  - 등비급수: |r| < 1이면 Σar^n이 a/(1-r)로 수렴

*EN:   - Geometric: Σar^n converges if |r| < 1 to a/(1-r)*
  - p-급수: p > 1이면 Σ1/n^p 수렴

*EN:   - p-series: Σ1/n^p converges if p > 1*
  - 교대급수: 항이 교대로 부호가 바뀜

*EN:   - Alternating series: terms alternate sign*
- **수렴 판정법**: 급수의 수렴 여부 판정

*EN: - \*\*Convergence tests\*\*: Determining if series converges*
  - 비 절댓값 판정법: lim|a_(n+1)/a_n| < 1 ⟹ 수렴

*EN:   - Ratio test: lim|a_(n+1)/a_n| < 1 ⟹ converges*
  - 근 판정법: lim|a_n|^(1/n) < 1 ⟹ 수렴

*EN:   - Root test: lim|a_n|^(1/n) < 1 ⟹ converges*
  - 적분 판정법: ∫f(x)dx와 비교

*EN:   - Integral test: compare with ∫f(x)dx*
  - 비교 판정법: 알려진 급수와 비교

*EN:   - Comparison: compare with known series*
  - 극한 비교 판정법: lim(a_n/b_n) 검토

*EN:   - Limit comparison: examine lim(a_n/b_n)*
- **멱급수와 테일러/매클로린 급수**: Σc_n(x-a)^n

*EN: - \*\*Power series and Taylor/Maclaurin series\*\*: Σc_n(x-a)^n*
  - 테일러: 함수를 무한 다항식으로 표현

*EN:   - Taylor: represents function as infinite polynomial*
  - 매클로린: x=0을 중심으로 한 테일러 급수

*EN:   - Maclaurin: Taylor series centered at 0*
  - e^x = Σx^n/n!, sin(x) = Σ(-1)^n x^(2n+1)/(2n+1)!

*EN:   - e^x = Σx^n/n!, sin(x) = Σ(-1)^n x^(2n+1)/(2n+1)!*
- **수렴 반지름과 구간**: 멱급수가 수렴하는 범위

*EN: - \*\*Radius and interval of convergence\*\*: Where power series converges*
  - 비 판정법으로 반지름 R 계산

*EN:   - Use ratio test to find radius R*
  - 끝점은 따로 확인

*EN:   - Check endpoints separately*
  - |x-a| < R일 때 급수 절대 수렴

*EN:   - Series converges absolutely for |x-a| < R*

**다변수 미적분**

*EN: \*\*Multivariable Calculus\*\**
- **편미분과 기울기**: 한 변수에 대한 변화율

*EN: - \*\*Partial derivatives and gradients\*\*: Rate of change with respect to one variable*
  - ∂f/∂x: 다른 변수를 상수로 취급한 도함수

*EN:   - ∂f/∂x: derivative treating other variables as constants*
  - 기울기 ∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z): 모든 편미분의 벡터

*EN:   - Gradient ∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z): vector of all partial derivatives*
  - 가장 가파른 상승 방향을 가리킴

*EN:   - Points in direction of steepest ascent*
- **방향 도함수**: 임의의 방향으로의 변화율

*EN: - \*\*Directional derivatives\*\*: Rate of change in any direction*
  - D_u f = ∇f · u (u는 단위 벡터)

*EN:   - D_u f = ∇f · u where u is unit vector*
  - 편미분을 일반화

*EN:   - Generalizes partial derivatives*
- **다변수 함수의 연쇄 규칙**: 다변수 함수의 합성

*EN: - \*\*Chain rule for multivariable functions\*\*: Composition of multivariable functions*
  - ∂z/∂s = (∂z/∂x)(∂x/∂s) + (∂z/∂y)(∂y/∂s)

*EN:   - ∂z/∂s = (∂z/∂x)(∂x/∂s) + (∂z/∂y)(∂y/∂s)*
  - 고차원에서의 음함수 미분에 필수

*EN:   - Essential for implicit differentiation in higher dimensions*
- **최적화**: 최댓값과 최솟값 찾기

*EN: - \*\*Optimization\*\*: Finding maxima and minima*
  - 임계점: ∇f = 0 또는 미정의인 점

*EN:   - Critical points: where ∇f = 0 or undefined*
  - 헤시안 행렬을 이용한 2차 도함수 검정

*EN:   - Second derivative test using Hessian matrix*
  - 최대점, 최소점, 안장점으로 분류

*EN:   - Classify as max, min, or saddle point*
- **라그랑주 승수**: 제약 조건이 있는 최적화

*EN: - \*\*Lagrange multipliers\*\*: Optimization with constraints*
  - g(x,y) = c 조건 하에서 f(x,y)의 극값 찾기

*EN:   - Find extrema of f(x,y) subject to g(x,y) = c*
  - ∇f = λ∇g와 제약 조건 동시에 풀기

*EN:   - Solve ∇f = λ∇g and constraint simultaneously*
  - λ는 라그랑주 승수

*EN:   - λ is Lagrange multiplier*
- **이중 및 삼중 적분**: 영역에 대한 积分

*EN: - \*\*Double and triple integrals\*\*: Integration over regions*
  - ∬_R f(x,y)dA: 2D 영역에 대한 누적

*EN:   - ∬_R f(x,y)dA: accumulation over 2D region*
  - ∭_V f(x,y,z)dV: 3D 영역에 대한 누적

*EN:   - ∭_V f(x,y,z)dV: accumulation over 3D region*
  - 반복 적분, 푸비니 정리

*EN:   - Iterated integrals, Fubini's theorem*
- **변수 변환 (야코비안)**: 좌표계 변환

*EN: - \*\*Change of variables (Jacobian)\*\*: Transforming coordinate systems*
  - 야코비안 행렬식 |∂(x,y)/∂(u,v)|이 넓이를 조정

*EN:   - Jacobian determinant |∂(x,y)/∂(u,v)| scales area*
  - 극좌표: dA = r dr dθ

*EN:   - Polar: dA = r dr dθ*
  - 3D를 위한 원통좌표, 구면좌표

*EN:   - Cylindrical, spherical coordinates for 3D*

**벡터 미적분**

*EN: \*\*Vector Calculus\*\**
- **벡터장**: 각 점 F(x,y,z)에 벡터를 할당하는 함수

*EN: - \*\*Vector fields\*\*: Function assigning vector to each point F(x,y,z)*
  - 속도장, 힘장, 전기/자기장

*EN:   - Velocity fields, force fields, electric/magnetic fields*
  - 기울기장은 보존적 (경로 독립)

*EN:   - Gradient fields are conservative (path-independent)*
- **선적분과 경로 독립성**: 곡선을 따른 적분

*EN: - \*\*Line integrals and path independence\*\*: Integral along curve*
  - ∫_C F·dr: 경로를 따라 힘장이 한 일

*EN:   - ∫_C F·dr: work done by force field along path*
  - 보존장: ∫_C F·dr은 끝점에만 의존

*EN:   - Conservative fields: ∫_C F·dr depends only on endpoints*
  - 퍼텐셜 함수 φ: F = ∇φ

*EN:   - Potential function φ: F = ∇φ*
- **면적분**: 곡면에 대한 적분

*EN: - \*\*Surface integrals\*\*: Integral over surface*
  - ∬_S F·dS: 곡면을 통과하는 유량

*EN:   - ∬_S F·dS: flux through surface*
  - 곡면을 가로지르는 흐름 측정

*EN:   - Measures flow across surface*
- **그린 정리**: 선적분과 이중 적분의 관계

*EN: - \*\*Green's Theorem\*\*: Relates line integral to double integral*
  - ∮_C F·dr = ∬_R (∂Q/∂x - ∂P/∂y)dA

*EN:   - ∮_C F·dr = ∬_R (∂Q/∂x - ∂P/∂y)dA*
  - 순환은 영역에 대한 회전의 적분과 같음

*EN:   - Circulation equals curl integrated over region*
- **스토크스 정리**: 면적분과 선적분의 관계

*EN: - \*\*Stokes' Theorem\*\*: Relates surface integral to line integral*
  - ∬_S (curl F)·dS = ∮_C F·dr

*EN:   - ∬_S (curl F)·dS = ∮_C F·dr*
  - 그린 정리를 3D로 일반화

*EN:   - Generalizes Green's theorem to 3D*
- **발산 정리**: 부피 적분과 면적분의 관계

*EN: - \*\*Divergence Theorem\*\*: Relates volume integral to surface integral*
  - ∭_V (div F)dV = ∬_S F·dS

*EN:   - ∭_V (div F)dV = ∬_S F·dS*
  - 부피에서 나가는 유량은 내부의 발산과 같음

*EN:   - Flux out of volume equals divergence inside*
  - 가우스 정리, 맥스웰 방정식의 기초

*EN:   - Gauss's theorem, fundamental for Maxwell's equations*

**개념적 통찰**:

*EN: \*\*Conceptual Insights\*\*:*
- 극한은 "값에 접근한다"는 개념을 형식화

*EN: - Limits formalize the notion of "approaching" a value*
- 도함수는 순간 변화율을 측정

*EN: - Derivative measures instantaneous rate of change*
- 적분은 누적을 나타내며 미분의 역연산

*EN: - Integral represents accumulation and reverses differentiation*
- 기본 정리는 도함수와 적분을 연결

*EN: - Fundamental Theorem connects derivatives and integrals*
- 다변수 미적분은 개념을 고차원으로 확장

*EN: - Multivariable calculus extends ideas to higher dimensions*
- 벡터 미적분은 전기, 자기, 유체 흐름을 통합

*EN: - Vector calculus unifies electricity, magnetism, and fluid flow*

**핵심 응용**: 물리학 (운동, 힘, 장), 공학 (최적화, 유체역학), 경제학 (한계 분석, 탄력성), 컴퓨터 그래픽, 머신러닝 (경사 하강법)

*EN: \*\*Key Applications\*\*: Physics (motion, forces, fields), engineering (optimization, fluid dynamics), economics (marginal analysis, elasticity), computer graphics, machine learning (gradient descent)*

### 2. 선형대수

*EN: ### 2. Linear Algebra*
벡터 공간과 선형 변환의 연구 - 현대 수학과 응용의 근간. 선형대수는 다차원 시스템을 기술하는 언어를 제공한다:

*EN: The study of vector spaces and linear transformations - fundamental to modern mathematics and applications. Linear algebra provides the language for describing multidimensional systems:*

**벡터**

*EN: **Vectors***
- **벡터 연산과 기하적 해석**: 덧셈, 스칼라 곱

*EN: - **Vector operations and geometric interpretation**: Addition, scalar multiplication*
  - 벡터는 방향이 있는 양(크기와 방향)을 나타낸다

*EN:   - Vectors represent directed quantities (magnitude and direction)*
  - 덧셈의 평행사변형 법칙

*EN:   - Parallelogram law for addition*
  - 스칼라 곱은 크기를 변화시킨다

*EN:   - Scaling by scalars changes magnitude*
- **내적과 직교성**: a·b = |a||b|cosθ

*EN: - **Dot product and orthogonality**: a·b = |a||b|cosθ*
  - 한 벡터의 다른 벡터로의 정사영을 측정한다

*EN:   - Measures projection of one vector onto another*
  - a·b = 0일 때 직교(수직)

*EN:   - Orthogonal (perpendicular) when a·b = 0*
  - 각도와 정사영 계산에 사용

*EN:   - Used to compute angles, projections*
- **외적과 행렬식 (2×2, 3×3)**: a×b는 두 벡터 모두에 수직

*EN: - **Cross product and determinants (2×2, 3×3)**: a×b perpendicular to both*
  - |a×b| = |a||b|sinθ (평행사변형의 넓이)

*EN:   - |a×b| = |a||b|sinθ (area of parallelogram)*
  - 오른손 법칙으로 방향 결정

*EN:   - Right-hand rule determines direction*
  - 3D(와 7D)에서만 정의됨

*EN:   - Only defined in 3D (and 7D)*
- **벡터 투영**: 한 벡터의 다른 벡터 방향 성분

*EN: - **Vector projections**: Component of vector along another*
  - proj_b(a) = (a·b/|b|²)b

*EN:   - proj_b(a) = (a·b/|b|²)b*
  - 벡터를 평행 성분과 수직 성분으로 분해

*EN:   - Decomposes vector into parallel and perpendicular parts*
- **기하학 및 물리학 응용**: 위치, 속도, 힘

*EN: - **Applications in geometry and physics**: Position, velocity, force*
  - 변위, 속도, 가속도 벡터

*EN:   - Displacement, velocity, acceleration vectors*
  - 힘 벡터, 토크 = r×F

*EN:   - Force vectors, torque = r×F*
  - 일 = F·d

*EN:   - Work = F·d*

**행렬**

*EN: **Matrices***
- **행렬 연산**: 덧셈, 곱셈, 전치

*EN: - **Matrix operations**: addition, multiplication, transpose*
  - 덧셈: 원소별 계산, 같은 크기의 행렬이어야 함

*EN:   - Addition: element-wise, matrices must have same dimensions*
  - 곱셈: (AB)_ij = Σ A_ik B_kj (행·열 방식)

*EN:   - Multiplication: (AB)_ij = Σ A_ik B_kj (row-by-column)*
  - 교환 불가: 일반적으로 AB ≠ BA

*EN:   - Not commutative: AB ≠ BA in general*
  - 전치: (A^T)_ij = A_ji (대각선 기준으로 뒤집기)

*EN:   - Transpose: (A^T)_ij = A_ji (flip across diagonal)*
- **특수 행렬**: 단위, 대각, 삼각, 대칭 행렬

*EN: - **Special matrices**: identity, diagonal, triangular, symmetric*
  - 단위행렬 I: 대각선이 1, IA = AI = A

*EN:   - Identity I: diagonal of 1s, IA = AI = A*
  - 대각행렬: 대각선 성분만 0이 아님

*EN:   - Diagonal: non-zero only on diagonal*
  - 삼각행렬: 위·아래 삼각 부분이 0

*EN:   - Triangular: upper or lower triangle is zero*
  - 대칭행렬: A^T = A (고유값에 중요)

*EN:   - Symmetric: A^T = A (important for eigenvalues)*
- **기본 행 연산**: 연립방정식 풀기 도구

*EN: - **Elementary row operations**: Tools for solving systems*
  - 행 교환, 스칼라 곱, 행 덧셈

*EN:   - Row swapping, scalar multiplication, row addition*
  - 해집합을 바꾸지 않음

*EN:   - Don't change solution set*
  - 기본 행렬의 곱셈에 대응

*EN:   - Correspond to multiplication by elementary matrices*
- **행 사다리꼴과 기약 행 사다리꼴**: 단순화된 행렬 형태

*EN: - **Row echelon and reduced row echelon form**: Simplified matrix forms*
  - REF: 선도원소가 오른쪽 아래로 내려감

*EN:   - REF: leading entries step down to right*
  - RREF: 선도원소가 1이며, 그 열에서 유일한 원소

*EN:   - RREF: leading entries are 1, only entry in column*
  - 가우스 소거법은 REF를 만든다

*EN:   - Gaussian elimination produces REF*
  - 가우스-조던 소거법은 RREF를 만든다

*EN:   - Gauss-Jordan produces RREF*
- **역행렬과 가역 조건**: AA^(-1) = I를 만족하는 A^(-1)

*EN: - **Matrix inverses and invertibility conditions**: A^(-1) such that AA^(-1) = I*
  - det(A) ≠ 0일 때만 존재 (정칙행렬)

*EN:   - Exists only if det(A) ≠ 0 (non-singular)*
  - x = A^(-1)b로 Ax = b를 풀 수 있음

*EN:   - Can solve Ax = b by x = A^(-1)b*
  - (AB)^(-1) = B^(-1)A^(-1)

*EN:   - (AB)^(-1) = B^(-1)A^(-1)*

**연립 선형 방정식**

*EN: **Systems of Linear Equations***
- **가우스 소거법**: REF로의 전진 소거

*EN: - **Gaussian elimination**: Forward elimination to REF*
  - 체계적으로 변수를 제거

*EN:   - Systematically eliminate variables*
  - 해를 구하기 위해 후진 대입

*EN:   - Back substitution to find solutions*
- **가우스-조던 소거법**: RREF까지 계속 진행

*EN: - **Gauss-Jordan elimination**: Continue to RREF*
  - 해를 직접 읽을 수 있음

*EN:   - Solutions can be read directly*
  - 역행렬 구하기에 유용

*EN:   - Useful for finding inverses*
- **행렬 방정식 Ax = b**: 연립방정식의 간결한 표현

*EN: - **Matrix equations Ax = b**: Compact representation of linear system*
  - 각 행이 하나의 방정식

*EN:   - Each row is an equation*
  - 해집합: 유일해, 무한해, 또는 해 없음

*EN:   - Solution set: unique, infinite, or no solutions*
- **동차 및 비동차 연립방정식**: b = 0 대 b ≠ 0

*EN: - **Homogeneous and non-homogeneous systems**: b = 0 vs b ≠ 0*
  - 동차방정식은 항상 자명해 x = 0을 가짐

*EN:   - Homogeneous always has trivial solution x = 0*
  - det(A) = 0이면 비자명해 존재

*EN:   - Non-trivial solutions when det(A) = 0*
  - 일반해 = 특수해 + 동차방정식의 해

*EN:   - General solution = particular + homogeneous solutions*
- **계수와 영공간 차원**: rank(A) + nullity(A) = n

*EN: - **Rank and nullity**: rank(A) + nullity(A) = n*
  - 계수: 열공간의 차원 (피벗 열의 수)

*EN:   - Rank: dimension of column space (number of pivot columns)*
  - 영공간 차원: 영공간의 차원

*EN:   - Nullity: dimension of null space*
  - 계수-영공간 정리

*EN:   - Rank-nullity theorem*

**행렬식**

*EN: **Determinants***
- **여인수 전개**: det(A)의 재귀적 계산

*EN: - **Cofactor expansion**: Recursive computation of det(A)*
  - 임의의 행 또는 열을 따라 전개

*EN:   - Along any row or column*
  - det(A) = Σ a_ij C_ij

*EN:   - det(A) = Σ a_ij C_ij*
  - 여인수 C_ij = (-1)^(i+j) M_ij

*EN:   - Cofactor C_ij = (-1)^(i+j) M_ij*
- **행렬식의 성질**: det(AB) = det(A)det(B)

*EN: - **Properties of determinants**: det(AB) = det(A)det(B)*
  - det(A^T) = det(A)

*EN:   - det(A^T) = det(A)*
  - 행 교환은 부호를 바꿈

*EN:   - Row swap changes sign*
  - 스칼라 곱: det(cA) = c^n det(A)

*EN:   - Scalar multiplication: det(cA) = c^n det(A)*
- **크라머 공식**: 행렬식을 이용해 Ax = b를 풂

*EN: - **Cramer's rule**: Solve Ax = b using determinants*
  - x_i = det(A_i)/det(A)

*EN:   - x_i = det(A_i)/det(A)*
  - A_i는 i번째 열을 b로 교체한 행렬

*EN:   - A_i has column i replaced by b*
  - 큰 연립방정식에는 비효율적

*EN:   - Inefficient for large systems*
- **기하적 해석 (넓이/부피)**: |det(A)|는 스케일 인수

*EN: - **Geometric interpretation (area/volume)**: |det(A)| = scale factor*
  - 2×2: 열로 이루어진 평행사변형의 넓이

*EN:   - 2×2: area of parallelogram formed by columns*
  - 3×3: 평행육면체의 부피

*EN:   - 3×3: volume of parallelepiped*
  - 변환이 부피를 얼마나 변화시키는지 측정

*EN:   - Measures how transformation changes volumes*

**고유값 & 고유벡터**

*EN: **Eigenvalues & Eigenvectors***
- **특성 방정식**: det(A - λI) = 0

*EN: - **Characteristic equation**: det(A - λI) = 0*
  - 고유값 λ에 대한 다항 방정식

*EN:   - Polynomial equation for eigenvalues λ*
  - n×n 행렬은 중복도 포함 n개의 고유값을 가짐

*EN:   - n×n matrix has n eigenvalues (counting multiplicity)*
- **고유공간**: (A - λI)의 영공간

*EN: - **Eigenspaces**: Null space of (A - λI)*
  - 고유값 λ에 대응하는 모든 고유벡터

*EN:   - All eigenvectors for eigenvalue λ*
  - 영벡터 포함

*EN:   - Plus zero vector*
- **대각화**: A = PDP^(-1)

*EN: - **Diagonalization**: A = PDP^(-1)*
  - P의 열은 고유벡터

*EN:   - P has eigenvectors as columns*
  - D는 고유값의 대각행렬

*EN:   - D is diagonal matrix of eigenvalues*
  - n개의 선형독립 고유벡터가 있을 때만 가능

*EN:   - Only possible if n linearly independent eigenvectors exist*
- **닮음 행렬**: B = P^(-1)AP

*EN: - **Similar matrices**: B = P^(-1)AP*
  - 동일한 고유값

*EN:   - Same eigenvalues*
  - 서로 다른 기저에서 같은 변환을 나타냄

*EN:   - Represent same transformation in different bases*
- **응용**: 미분방정식, 마르코프 연쇄

*EN: - **Applications**: differential equations, Markov chains*
  - ODE 연립방정식의 해: x' = Ax

*EN:   - Solutions to systems of ODEs: x' = Ax*
  - 마르코프 과정의 정상 상태

*EN:   - Steady-state of Markov processes*
  - 구글 페이지랭크 알고리즘

*EN:   - Google PageRank algorithm*
  - 주성분 분석 (PCA)

*EN:   - Principal Component Analysis (PCA)*

**벡터 공간**

*EN: **Vector Spaces***
- **부분공간과 생성**: 덧셈과 스칼라 곱에 대해 닫혀 있음

*EN: - **Subspaces and span**: Closed under addition and scalar multiplication*
  - 영벡터를 포함해야 함

*EN:   - Must contain zero vector*
  - 생성: 벡터들의 모든 선형 결합

*EN:   - Span: all linear combinations of vectors*
  - 열공간, 행공간, 영공간은 부분공간

*EN:   - Column space, row space, null space are subspaces*
- **선형 독립**: 어떤 벡터도 다른 벡터들의 선형 결합이 아님

*EN: - **Linear independence**: No vector is combination of others*
  - Σc_i v_i = 0이면 모든 c_i = 0

*EN:   - Σc_i v_i = 0 only if all c_i = 0*
  - 생성 집합에서 최대 독립 집합이 기저

*EN:   - Maximum independent set in span is basis*
- **기저와 차원**: 최소 생성 집합

*EN: - **Basis and dimension**: Minimal spanning set*
  - 선형독립이며 공간을 생성

*EN:   - Linearly independent and spans space*
  - 모든 기저의 크기가 같음 = 차원

*EN:   - All bases have same size = dimension*
  - 표준 기저: e_1, e_2, ..., e_n

*EN:   - Standard basis: e_1, e_2, ..., e_n*
- **행공간, 열공간, 영공간**: 기본 부분공간들

*EN: - **Row space, column space, null space**: Fundamental subspaces*
  - 행공간: 행들의 생성 = Col(A^T)

*EN:   - Row space: span of rows = Col(A^T)*
  - 열공간: 열들의 생성, 변환의 치역

*EN:   - Column space: span of columns, range of transformation*
  - 영공간: Ax = 0의 해, 변환의 핵

*EN:   - Null space: solutions to Ax = 0, kernel of transformation*
- **계수-영공간 정리**: rank(A) + nullity(A) = n

*EN: - **Rank-nullity theorem**: rank(A) + nullity(A) = n*
  - 선형 변환에 대한 차원 공식

*EN:   - Dimension formula for linear transformations*
  - dim(치역) + dim(핵) = dim(정의역)

*EN:   - dim(range) + dim(kernel) = dim(domain)*

**선형 변환**

*EN: **Linear Transformations***
- **정의와 성질**: T(cu + dv) = cT(u) + dT(v)

*EN: - **Definition and properties**: T(cu + dv) = cT(u) + dT(v)*
  - 벡터 공간 구조를 보존

*EN:   - Preserves vector space structure*
  - 예시: 회전, 반사, 정사영, 스케일링

*EN:   - Examples: rotations, reflections, projections, scaling*
- **행렬 표현**: [T(v)]_B = [T]_B [v]_B

*EN: - **Matrix representation**: [T(v)]_B = [T]_B [v]_B*
  - 모든 선형 변환은 행렬 표현을 가짐

*EN:   - Every linear transformation has matrix representation*
  - 행렬의 열은 기저 벡터의 상(像)

*EN:   - Matrix columns are images of basis vectors*
- **핵과 치역**: ker(T) = {v : T(v) = 0}, range(T) = {T(v) : v ∈ V}

*EN: - **Kernel and range**: ker(T) = {v : T(v) = 0}, range(T) = {T(v) : v in V}*
  - 핵(kernel)은 영으로 사상되는 것을 나타냄

*EN:   - Kernel measures what gets mapped to zero*
  - 치역은 모든 출력의 집합

*EN:   - Range is set of all outputs*
  - 둘 다 부분공간

*EN:   - Both are subspaces*
- **동형사상**: 일대일이고 전사인 선형 변환

*EN: - **Isomorphisms**: One-to-one and onto linear transformations*
  - 벡터 공간 구조를 완전히 보존

*EN:   - Preserves vector space structure perfectly

*EN:   - Preserves vector space structure perfectly*
  - 역변환이 존재

*EN:   - Inverse transformation exists*
  - 공간이 "본질적으로 동일"

*EN:   - Spaces are "essentially the same"*
- **기저 변환**: 기저 사이에서 좌표 변환

*EN: - **Change of basis**: Converting coordinates between bases*
  - 기저 변환 행렬 [id]_{B→C}

*EN:   - Change of basis matrix [id]_{B→C}*
  - [v]_C = P [v]_B (P는 기저 벡터 포함)

*EN:   - [v]_C = P [v]_B where P has basis vectors*

**내적 공간**

*EN: **Inner Product Spaces***
- **내적과 노름**: 내적의 일반화

*EN: - **Inner products and norms**: Generalizes dot product*
  - <u,v>는 양의 정치성, 선형성, 대칭성을 만족

*EN:   - <u,v> satisfies positivity, linearity, symmetry*
  - 노름: ||v|| = √<v,v> (길이)

*EN:   - Norm: ||v|| = √<v,v> (length)*
  - 각도와 직교성을 정의

*EN:   - Defines angles and orthogonality*
- **직교 및 정규 직교 기저**: <e_i, e_j> = δ_ij

*EN: - **Orthogonal and orthonormal bases**: <e_i, e_j> = δ_ij*
  - 직교: 수직인 벡터들

*EN:   - Orthogonal: perpendicular vectors*
  - 정규 직교: 직교이며 단위 길이

*EN:   - Orthonormal: orthogonal with unit length*
  - 좌표: [v]_B = <v, e_i>

*EN:   - Coordinates: [v]_B = <v, e_i>*
- **그람-슈미트 직교화**: 기저를 정규 직교 기저로 변환

*EN: - **Gram-Schmidt orthogonalization**: Convert basis to orthonormal*
  - 반복적으로 정사영을 빼기

*EN:   - Subtract projections iteratively*
  - v_k⊥ = v_k - Σproj_{u_j}(v_k)

*EN:   - v_k⊥ = v_k - Σproj_{u_j}(v_k)*
  - 정규화: u_k = v_k⊥/||v_k⊥||

*EN:   - Normalize: u_k = v_k⊥/||v_k⊥||*
- **QR 분해**: A = QR

*EN: - **QR factorization**: A = QR*
  - Q는 정규 직교 열(그람-슈미트에서)

*EN:   - Q has orthonormal columns (from Gram-Schmidt)*
  - R은 상삼각 행렬

*EN:   - R is upper triangular*
  - 최소 제곱 풀기에 유용

*EN:   - Useful for solving least squares*
- **최소 제곱 근사**: Ax = b에 해가 없을 때 최적 근사

*EN: - **Least squares approximation**: Best fit when Ax = b has no solution*
  - ||Ax - b||² 최소화

*EN:   - Minimize ||Ax - b||²*
  - 해: x̂ = (A^T A)^(-1) A^T b

*EN:   - Solution: x̂ = (A^T A)^(-1) A^T b*
  - 정규 방정식: A^T Ax = A^T b

*EN:   - Normal equations: A^T Ax = A^T b*
  - 선형 회귀에서 사용

*EN:   - Used in linear regression*
- **스펙트럼 정리**: 대칭 행렬은 직교 대각화 가능

*EN: - **Spectral theorem**: Symmetric matrices are orthogonally diagonalizable*
  - A = QDQ^T (Q는 직교 행렬)

*EN:   - A = QDQ^T where Q is orthogonal*
  - 고유값은 실수

*EN:   - Eigenvalues are real*
  - 서로 다른 고유값의 고유벡터는 직교

*EN:   - Eigenvectors for distinct eigenvalues are orthogonal*

**개념적 통찰**:

*EN: **Conceptual Insights**:*
- 벡터는 n차원 공간에서 방향이 있는 양을 나타낸다

*EN: - Vectors represent directed quantities in n-dimensional space*
- 행렬은 벡터 공간 사이의 선형 변환을 부호화한다

*EN: - Matrices encode linear transformations between vector spaces*
- Ax=b를 푸는 것은 수많은 응용에서 핵심이다

*EN: - Solving Ax=b is central to countless applications*
- 고유값은 변환 하에서 불변 방향을 드러낸다

*EN: - Eigenvalues reveal invariant directions under transformation*
- 직교성은 거리와 오차를 최소화한다

*EN: - Orthogonality minimizes distance and error*
- 추상적 벡터 공간은 기하학, 함수 공간 등을 통합한다

*EN: - Abstract vector spaces unify geometry, function spaces, and more*

**핵심 응용**: Computer graphics (3D transformations), data science (PCA, dimensionality reduction), quantum mechanics (state vectors), machine learning (neural networks), Google PageRank, image compression, cryptography

*EN: \*\*Key Applications\*\*: Computer graphics (3D transformations), data science (PCA, dimensionality reduction), quantum mechanics (state vectors), machine learning (neural networks), Google PageRank, image compression, cryptography*

### 3. 미분 방정식

*EN: ### 3. Differential Equations*
양의 변화를 기술하는 방정식 - 동적 시스템의 언어. 미분방정식은 개체군 성장부터 양자역학까지 모든 것을 모델링한다:

*EN: Equations describing how quantities change - the language of dynamic systems. Differential equations model everything from population growth to quantum mechanics:*

**1계 상미분방정식**

*EN: **First Order ODEs***
- **분리 가능 방정식**: dy/dx = f(x)g(y)

*EN: - **Separable equations**: dy/dx = f(x)g(y)*
  - g(y)dy = f(x)dx로 재배치

*EN:   - Rearrange to g(y)dy = f(x)dx*
  - 양변 적분

*EN:   - Integrate both sides*
  - 가장 흔한 기초 유형

*EN:   - Most common elementary type*
- **적분 인수를 사용한 1계 선형 방정식**: dy/dx + P(x)y = Q(x)

*EN: - **Linear first order equations with integrating factors**: dy/dx + P(x)y = Q(x)*
  - μ(x) = e^(∫P(x)dx)를 곱함

*EN:   - Multiply by μ(x) = e^(∫P(x)dx)*
  - 좌변이 d/dx[μy]가 됨

*EN:   - Left side becomes d/dx[μy]*
  - 적분 후 μ로 나눔

*EN:   - Integrate and divide by μ*
- **완전 방정식과 완전성 검정**: M(x,y)dx + N(x,y)dy = 0

*EN: - **Exact equations and exactness test**: M(x,y)dx + N(x,y)dy = 0*
  - ∂M/∂y = ∂N/∂x이면 완전

*EN:   - Exact if ∂M/∂y = ∂N/∂x*
  - 해는 dφ = Mdx + Ndy인 φ(x,y) = C

*EN:   - Solution is φ(x,y) = C where dφ = Mdx + Ndy*
  - M 또는 N을 적분하여 φ를 구함

*EN:   - Find φ by integrating M or N*
- **베르누이 방정식**: dy/dx + P(x)y = Q(x)y^n

*EN: - **Bernoulli equations**: dy/dx + P(x)y = Q(x)y^n*
  - 비선형이지만 선형화 가능

*EN:   - Nonlinear but can be linearized*
  - 치환 v = y^(1-n)으로 선형 방정식으로 변환

*EN:   - Substitution v = y^(1-n) transforms to linear*
- **치환을 이용한 동차 방정식**: M과 N이 같은 차수

*EN: - **Homogeneous equations with substitution**: M and N are same degree*
  - v = y/x 치환으로 분리 가능 방정식이 됨

*EN:   - Substitution v = y/x reduces to separable*
  - dy/dx = f(y/x)

*EN:   - dy/dx = f(y/x)*
- **초기값 문제**: y(x_0) = y_0 지정

*EN: - **Initial value problems**: Specify y(x_0) = y_0*
  - 일반해에서 유일해를 결정

*EN:   - Determines unique solution from general solution*
  - 초기 조건으로 C를 결정

*EN:   - C is determined by initial condition*
- **존재성과 유일성 (피카르 정리)**: 유일해를 위한 조건

*EN: - **Existence and uniqueness (Picard's theorem)**: Conditions for unique solution*
  - 연속인 f와 립시츠 조건이 유일해를 보장

*EN:   - Continuous f and Lipschitz condition guarantee unique solution*
  - 그렇지 않으면 존재하지 않거나 유일하지 않을 수 있음

*EN:   - May not exist or be unique otherwise*
- **방향장과 기울기장**: 해의 시각적 표현

*EN: - **Direction fields and slope fields**: Visual representation of solutions*
  - 기울기 f(x,y)인 작은 선분을 그림

*EN:   - Plot small line segments with slope f(x,y)*
  - 해가 장의 흐름을 따름

*EN:   - Solutions follow flow of field*
  - 풀지 않고도 정성적 이해 가능

*EN:   - Qualitative understanding without solving*

**2계 상미분방정식**

*EN: **Second Order ODEs***
- **상수 계수 동차 방정식**: ay'' + by' + cy = 0

*EN: - **Homogeneous equations with constant coefficients**: ay'' + by' + cy = 0*
  - y = e^(rx) 형태의 해를 시도

*EN:   - Try solution y = e^(rx)*
  - 특성 방정식으로 이어짐

*EN:   - Leads to characteristic equation*
- **특성 방정식**: ar² + br + c = 0

*EN: - **Characteristic equation**: ar² + br + c = 0*
  - 실수 서로 다른 근: y = c_1 e^(r_1 x) + c_2 e^(r_2 x)

*EN:   - Real distinct roots: y = c_1 e^(r_1 x) + c_2 e^(r_2 x)*
  - 중복근: y = (c_1 + c_2 x) e^(rx)

*EN:   - Repeated root: y = (c_1 + c_2 x) e^(rx)*
  - 복소근 r = α ± βi: y = e^(αx)(c_1 cos(βx) + c_2 sin(βx))

*EN:   - Complex roots r = α ± βi: y = e^(αx)(c_1 cos(βx) + c_2 sin(βx))*
- **오일러-코시 방정식**: x²y'' + axy' + by = 0

*EN: - **Euler-Cauchy equations**: x²y'' + axy' + by = 0*
  - y = x^r 형태를 시도

*EN:   - Try y = x^r*
  - r에 대한 지표 방정식

*EN:   - Indicial equation for r*
  - 변수 계수이지만 풀 수 있음

*EN:   - Variable coefficients but solvable*
- **비동차 방정식**: ay'' + by' + cy = f(x)

*EN: - **Non-homogeneous equations**: ay'' + by' + cy = f(x)*
  - 일반해 = 동차해 + 특수해

*EN:   - General solution = homogeneous + particular*
  - y = y_h + y_p

*EN:   - y = y_h + y_p*
- **미정 계수법**: y_p의 형태를 추측

*EN: - **Method of undetermined coefficients**: Guess form of y_p*
  - 다항식, 지수함수, sin/cos 우변에 적용

*EN:   - For polynomial, exponential, sin/cos right-hand sides*
  - f(x) 형태를 바탕으로 추측

*EN:   - Guess based on f(x) form*
  - 추측이 동차 방정식의 해이면 수정

*EN:   - Modify if guess solves homogeneous equation*
- **론스키 행렬을 이용한 매개변수 변분법**: y_p의 일반적 방법

*EN: - **Variation of parameters with Wronskian**: General method for y_p*
  - y_p = u_1 y_1 + u_2 y_2 (공식으로 u_i 결정)

*EN:   - y_p = u_1 y_1 + u_2 y_2 where u_i determined by formulas*
  - 론스키 행렬 W = y_1 y_2' - y_2 y_1'

*EN:   - Wronskian W = y_1 y_2' - y_2 y_1'*
  - 임의의 f(x)에 적용 가능

*EN:   - Works for any f(x)*

**고계 상미분방정식 & 연립방정식**

*EN: **Higher Order ODEs & Systems***
- **상수 계수 방정식**: 2계 방법의 확장

*EN: - **Constant coefficient equations**: Extend second-order methods*
  - 특성 방정식은 고차 다항식

*EN:   - Characteristic equation is higher degree polynomial*
  - 같은 경우: 서로 다른 근, 중복근, 복소근

*EN:   - Same cases: distinct, repeated, complex roots*
- **행렬 형태의 연립 상미분방정식**: x' = Ax

*EN: - **Systems of ODEs in matrix form**: x' = Ax*
  - 함수 벡터 x = [x_1, ..., x_n]^T

*EN:   - Vector of functions x = [x_1, ..., x_n]^T*
  - A는 계수 행렬

*EN:   - A is coefficient matrix*
  - 연립 방정식의 간결한 표현

*EN:   - Compact representation of coupled equations*
- **해를 위한 고유값 방법**: x = e^(λt) v

*EN: - **Eigenvalue method for solutions**: x = e^(λt) v*
  - A의 고유값이 지수 성장률을 결정

*EN:   - Eigenvalues of A determine exponential growth rates*
  - 고유벡터가 방향을 결정

*EN:   - Eigenvectors determine directions*
  - 일반해는 선형 결합

*EN:   - General solution is linear combination*
- **위상 초상화와 안정성 분석**: 해의 행동 시각화

*EN: - **Phase portraits and stability analysis**: Visualize solution behavior*
  - 2D 연립방정식의 위상 평면

*EN:   - Phase plane for 2D systems*
  - 평형점 분류: 안정, 불안정, 안장점

*EN:   - Classify equilibria: stable, unstable, saddle*
  - 고유값이 안정성을 결정

*EN:   - Eigenvalues determine stability*

**라플라스 변환**

*EN: **Laplace Transform***
- **정의와 성질**: L{f(t)} = ∫_0^∞ e^(-st) f(t) dt

*EN: - **Definition and properties**: L{f(t)} = ∫_0^∞ e^(-st) f(t) dt*
  - 미분방정식을 대수 방정식으로 변환

*EN:   - Converts differential equations to algebraic equations*
  - 선형성: L{af + bg} = aL{f} + bL{g}

*EN:   - Linearity: L{af + bg} = aL{f} + bL{g}*
  - 불연속 강제 함수에 유용

*EN:   - Useful for discontinuous forcing functions*
- **도함수의 변환**: L{f'} = sL{f} - f(0)

*EN: - **Transforms of derivatives**: L{f'} = sL{f} - f(0)*
  - L{f''} = s²L{f} - sf(0) - f'(0)

*EN:   - L{f''} = s²L{f} - sf(0) - f'(0)*
  - 차수를 낮추고, 초기 조건을 통합

*EN:   - Reduces order, incorporates initial conditions*
- **이동 정리**: 제1이동과 제2이동

*EN: - **Shifting theorems**: First and second shifting*
  - 제1이동: L{e^(at)f(t)} = F(s-a)

*EN:   - First: L{e^(at)f(t)} = F(s-a)*
  - 제2이동: L{u(t-a)f(t-a)} = e^(-as)F(s) (단위 계단)

*EN:   - Second: L{u(t-a)f(t-a)} = e^(-as)F(s) (unit step)*
- **부분 분수를 이용한 역 라플라스 변환**: F(s)에서 f(t) 찾기

*EN: - **Inverse Laplace transform with partial fractions**: Find f(t) from F(s)*
  - 유리함수 분해

*EN:   - Decompose rational functions*
  - 표준 변환 표 사용

*EN:   - Use table of standard transforms*
- **라플라스 변환으로 초기값 문제 풀기**: 변환, 대수적 풀기, 역변환

*EN: - **Solving IVPs with Laplace transforms**: Transform, solve algebraically, inverse*
  - 초기 조건이 자동으로 통합됨

*EN:   - Initial conditions automatically incorporated*
  - 구간별 함수에 특히 유용

*EN:   - Particularly useful for piecewise functions*

**급수 해법**

*EN: **Series Solutions***
- **일반점에서의 거듭제곱 급수 방법**: y = Σa_n(x-x_0)^n

*EN: - **Power series method at ordinary points**: y = Σa_n(x-x_0)^n*
  - 상미분방정식에 대입

*EN:   - Substitute into ODE*
  - 계수를 맞추어 점화식 구하기

*EN:   - Match coefficients to find recurrence relation*
  - 계수가 해석적일 때 적용 가능

*EN:   - Works when coefficients are analytic*
- **특이점에서의 프로베니우스 방법**: y = Σa_n x^(n+r)

*EN: - **Frobenius method at singular points**: y = Σa_n x^(n+r)*
  - 정규 특이점에 적용

*EN:   - For regular singular points*
  - 지표 방정식이 r을 결정

*EN:   - Indicial equation determines r*
  - 로그 항이 나타날 수 있음

*EN:   - May have logarithmic terms*
- **지표 방정식**: 지수 r을 결정

*EN: - **Indicial equation**: Determines exponent r*
  - 근의 차이가 정수가 아니면 두 해 존재

*EN:   - Two solutions if roots differ by non-integer*
  - 중복근이거나 차이가 정수인 경우 특별 처리

*EN:   - Special cases for repeated or differing-by-integer roots*

**편미분 방정식**

*EN: **Partial Differential Equations***
- **1계 편미분방정식과 특성 곡선법**: du/dt + c du/dx = 0

*EN: - **First order PDEs and method of characteristics**: du/dt + c du/dx = 0*
  - 특성 곡선을 따라 편미분방정식을 상미분방정식으로 변환

*EN:   - Transform PDE to ODEs along characteristic curves*
  - 해가 특성 곡선을 따라 상수

*EN:   - Solution constant along characteristics*
- **2계 분류**: 판별식에 따른 분류

*EN: - **Second order classification**: Based on discriminant*
  - 타원형: B²-AC < 0 (정상 상태, 라플라스 방정식)

*EN:   - Elliptic: B²-AC < 0 (steady state, Laplace equation)*
  - 포물형: B²-AC = 0 (확산, 열 방정식)

*EN:   - Parabolic: B²-AC = 0 (diffusion, heat equation)*
  - 쌍곡형: B²-AC > 0 (파동 전파, 파동 방정식)

*EN:   - Hyperbolic: B²-AC > 0 (wave propagation, wave equation)*
- **열 방정식 (포물형)**: ∂u/∂t = α ∂²u/∂x²

*EN: - **Heat equation (parabolic)**: ∂u/∂t = α ∂²u/∂x²*
  - 확산, 열 흐름 모델링

*EN:   - Models diffusion, heat flow*
  - 시간이 지남에 따라 해가 부드러워짐

*EN:   - Solutions smooth out over time*
  - 초기값 문제

*EN:   - Initial value problem*
- **파동 방정식 (쌍곡형)**: ∂²u/∂t² = c² ∂²u/∂x²

*EN: - **Wave equation (hyperbolic)**: ∂²u/∂t² = c² ∂²u/∂x²*
  - 진동, 전자기파 모델링

*EN:   - Models vibrations, electromagnetic waves*
  - 달랑베르 해: u = f(x-ct) + g(x+ct)

*EN:   - d'Alembert solution: u = f(x-ct) + g(x+ct)*
  - 속도 c로 전파됨

*EN:   - Propagates at speed c*
- **라플라스 방정식 (타원형)**: ∇²u = ∂²u/∂x² + ∂²u/∂y² = 0

*EN: - **Laplace equation (elliptic)**: ∇²u = ∂²u/∂x² + ∂²u/∂y² = 0*
  - 정상 상태 온도, 정전기학 모델링

*EN:   - Models steady-state temperature, electrostatics*
  - 경계값 문제

*EN:   - Boundary value problem*
  - 최대 원리: 경계에서 최대값

*EN:   - Maximum principle: max on boundary*
- **변수 분리**: u(x,t) = X(x)T(t)로 가정

*EN: - **Separation of variables**: Assume u(x,t) = X(x)T(t)*
  - 편미분방정식을 상미분방정식으로 변환

*EN:   - Converts PDE to ODEs*
  - 공간 부분에 대한 고유값 문제

*EN:   - Eigenvalue problems for spatial part*
  - 일반해에 푸리에 급수 사용

*EN:   - Fourier series for general solution*
- **경계 조건**: 디리클레, 노이만, 로빈

*EN: - **Boundary conditions**: Dirichlet, Neumann, Robin*
  - 디리클레: 경계에서 u 지정

*EN:   - Dirichlet: u specified on boundary*
  - 노이만: 경계에서 ∂u/∂n 지정

*EN:   - Neumann: ∂u/∂n specified on boundary*
  - 로빈: u와 ∂u/∂n의 선형 결합

*EN:   - Robin: linear combination of u and ∂u/∂n*
- **푸리에 급수 해법**: 급수로 해를 표현

*EN: - **Fourier series solutions**: Represent solution as series*
  - u(x,t) = ΣA_n sin(nπx/L) e^(-αn²π²t/L²)

*EN:   - u(x,t) = ΣA_n sin(nπx/L) e^(-αn²π²t/L²)*
  - 경계 조건을 만족

*EN:   - Satisfies boundary conditions*
  - 계수는 초기 조건에서 결정

*EN:   - Coefficients from initial condition*

**수치 방법**

*EN: **Numerical Methods***
- **오일러 방법 (O(h) 오차)**: y_(n+1) = y_n + h f(t_n, y_n)

*EN: - **Euler's method (O(h) error)**: y_(n+1) = y_n + h f(t_n, y_n)*
  - 가장 간단한 방법

*EN:   - Simplest method*
  - 1차 정확도

*EN:   - First-order accurate*
  - 불안정할 수 있음

*EN:   - Can be unstable*
- **개선된 오일러/훈 방법 (O(h²) 오차)**: 예측-수정 방법

*EN: - **Improved Euler/Heun's method (O(h²) error)**: Predictor-corrector*
  - 오일러 방법으로 예측

*EN:   - Predict with Euler*
  - 평균 기울기로 수정

*EN:   - Correct with average slope*
  - 2차 정확도

*EN:   - Second-order accurate*
- **룽게-쿠타 방법 (RK4, O(h⁴) 오차)**: 황금 표준

*EN: - **Runge-Kutta methods (RK4 with O(h⁴) error)**: Gold standard*
  - 여러 점에서 기울기의 가중 평균

*EN:   - Weighted average of slopes at multiple points*
  - 4차가 가장 일반적

*EN:   - Fourth-order most common*
  - 매우 정확하고 안정적

*EN:   - Very accurate, stable*
- **다단계 방법**: 이전 여러 점 사용

*EN: - **Multistep methods**: Use multiple previous points*
  - 아담스-배시포스 (양함수)

*EN:   - Adams-Bashforth (explicit)*
  - 아담스-몰턴 (음함수)

*EN:   - Adams-Moulton (implicit)*
  - 단일 단계보다 효율적

*EN:   - More efficient than single-step*
- **안정성과 강성 방정식**: 수치적 안정성 분석

*EN: - **Stability and stiff equations**: Numerical stability analysis*
  - 강성: 다중 시간 척도, 매우 다른 변화율

*EN:   - Stiff: multiple time scales, very different rates*
  - 음함수 방법이 강성 방정식에 더 적합

*EN:   - Implicit methods better for stiff equations*
  - A-안정성이 중요

*EN:   - A-stability important*

**응용**

*EN: **Applications***
- 물리학: 뉴턴 법칙, 스프링-질량 시스템, 진자

*EN: - Physics: Newton's laws, spring-mass systems, pendulums*
- 공학: RLC 회로, 보 처짐

*EN: - Engineering: RLC circuits, beam deflection*
- 생물학: 개체군 역학, 로트카-볼테라, SIR 모델

*EN: - Biology: population dynamics, Lotka-Volterra, SIR models*
- 경제학: 성장 모델, 수요-공급 역학

*EN: - Economics: growth models, supply-demand dynamics*

**개념적 통찰**:

*EN: **Conceptual Insights**:*
- 상미분방정식은 독립 변수가 하나인 시스템(보통 시간)을 모델링한다

*EN: - ODEs model systems with one independent variable (usually time)*
- 편미분방정식은 여러 변수(공간과 시간)에 의존하는 시스템을 모델링한다

*EN: - PDEs model systems depending on multiple variables (space and time)*
- 해는 시간에 따른 시스템 행동을 기술한다

*EN: - Solutions describe system behavior over time*
- 초기/경계 조건이 유일해를 결정한다

*EN: - Initial/boundary conditions determine unique solutions*
- 선형 방정식은 중첩을 허용하지만, 비선형은 그렇지 않다

*EN: - Linear equations allow superposition; nonlinear don't*
- 해석적 해는 드물고, 수치 방법이 필수적이다

*EN: - Analytical solutions rare; numerical methods essential*

**핵심 응용**: 물리학 (Newton's laws, Maxwell's equations, Schrödinger equation), engineering (control systems, signal processing), biology (epidemiology, ecology), chemistry (reaction kinetics), economics (option pricing, growth models)

*EN: \*\*Key Applications\*\*: Physics (Newton's laws, Maxwell's equations, Schrödinger equation), engineering (control systems, signal processing), biology (epidemiology, ecology), chemistry (reaction kinetics), economics (option pricing, growth models)*

### 4. 확률 & 통계

*EN: ### 4. Probability & Statistics*
불확실성과 데이터 분석의 수학 - 무작위성을 정량화하고 추론하는 학문. 확률과 통계는 현대 데이터 과학과 과학 연구에 필수적이다:

*EN: The mathematics of uncertainty and data analysis - quantifying randomness and making inferences. Probability and statistics are essential for modern data science and scientific research:*

**확률론**

*EN: **Probability Theory***
- **표본 공간, 사건, 공리**: 확률의 기초

*EN: - **Sample spaces, events, and axioms**: Foundation of probability*
  - 표본 공간 Ω: 가능한 모든 결과의 집합

*EN:   - Sample space Ω: set of all possible outcomes*
  - 사건: 표본 공간의 부분 집합

*EN:   - Event: subset of sample space*
  - 공리: 0 ≤ P(A) ≤ 1, P(Ω) = 1, 서로소이면 P(A∪B) = P(A) + P(B)

*EN:   - Axioms: 0 ≤ P(A) ≤ 1, P(Ω) = 1, P(A∪B) = P(A) + P(B) if disjoint*
- **합집합, 교집합, 여사건**: 사건에 대한 집합 연산

*EN: - **Union, intersection, complement**: Set operations on events*
  - 합집합 A∪B: A 또는 B가 발생

*EN:   - Union A∪B: A or B occurs*
  - 교집합 A∩B: A와 B가 모두 발생

*EN:   - Intersection A∩B: both A and B occur*
  - 여사건 A^c: A가 발생하지 않음

*EN:   - Complement A^c: A does not occur*
  - 드 모르간 법칙

*EN:   - De Morgan's laws*
- **조건부 확률 P(A|B)**: B가 발생했을 때 A의 확률

*EN: - **Conditional probability P(A|B)**: Probability of A given B occurred*
  - P(A|B) = P(A∩B)/P(B)

*EN:   - P(A|B) = P(A∩B)/P(B)*
  - 새로운 정보로 확률을 갱신

*EN:   - Updates probability with new information*
  - 추론의 근본

*EN:   - Fundamental for inference*
- **베이즈 정리**: P(A|B) = P(B|A)P(A)/P(B)

*EN: - **Bayes' Theorem**: P(A|B) = P(B|A)P(A)/P(B)*
  - 조건부 확률을 역으로 계산

*EN:   - Reverse conditional probabilities*
  - 베이즈 통계학의 기초

*EN:   - Foundation of Bayesian statistics*
  - 증거로 사전 확률을 갱신

*EN:   - Update prior beliefs with evidence*
- **전 확률 법칙**: P(B) = ΣP(B|A_i)P(A_i)

*EN: - **Law of Total Probability**: P(B) = ΣP(B|A_i)P(A_i)*
  - 표본 공간의 분할

*EN:   - Partition sample space*
  - 시나리오에 대한 가중 평균

*EN:   - Weighted average over scenarios*
- **독립성**: P(A∩B) = P(A)P(B)

*EN: - **Independence**: P(A∩B) = P(A)P(B)*
  - B를 알아도 A의 확률이 변하지 않음

*EN:   - Knowing B doesn't change probability of A*
  - 조건부 독립이 실제로 중요

*EN:   - Conditional independence important in practice*
- **계수 원리**: 순열, 조합, 포함-배제

*EN: - **Counting principles**: permutations, combinations, inclusion-exclusion*
  - 순열: 순서 있는 배열 P(n,r) = n!/(n-r)!

*EN:   - Permutations: ordered arrangements P(n,r) = n!/(n-r)!*
  - 조합: 순서 없는 선택 C(n,r) = n!/[r!(n-r)!]

*EN:   - Combinations: unordered selections C(n,r) = n!/[r!(n-r)!]*
  - 포함-배제: P(A∪B) = P(A) + P(B) - P(A∩B)

*EN:   - Inclusion-exclusion: P(A∪B) = P(A) + P(B) - P(A∩B)*
- **수형도**: 순차적 사건의 시각적 표현

*EN: - **Tree diagrams**: Visual representation of sequential events*
  - 가지는 조건부 확률을 보여줌

*EN:   - Branches show conditional probabilities*
  - 경로를 따라 곱하기

*EN:   - Multiply along paths*
  - 시나리오에 걸쳐 더하기

*EN:   - Add across scenarios*

**확률 변수**

*EN: **Random Variables***
- **이산 대 연속 확률 변수**: 셀 수 있는 값 대 셀 수 없는 값

*EN: - **Discrete vs continuous random variables**: Countable vs uncountable values*
  - 이산: X는 고립된 값(0, 1, 2, ...)을 취함

*EN:   - Discrete: X takes isolated values (0, 1, 2, ...)*
  - 연속: X는 구간에서 값을 취함

*EN:   - Continuous: X takes values in intervals*
  - 서로 다른 확률 체계

*EN:   - Different probability frameworks*
- **확률 질량 함수 (PMF)**: 이산의 경우 p(x) = P(X=x)

*EN: - **Probability mass function (PMF)**: p(x) = P(X=x) for discrete*
  - 정확한 확률을 제공

*EN:   - Gives exact probabilities*
  - Σp(x) = 1

*EN:   - Σp(x) = 1*
  - 막대 그래프 표현

*EN:   - Bar chart representation*
- **확률 밀도 함수 (PDF)**: 연속의 경우 f(x)

*EN: - **Probability density function (PDF)**: f(x) for continuous*
  - P(a ≤ X ≤ b) = ∫_a^b f(x)dx

*EN:   - P(a ≤ X ≤ b) = ∫_a^b f(x)dx*
  - f(x) ≥ 0, ∫_{-∞}^∞ f(x)dx = 1

*EN:   - f(x) ≥ 0, ∫_{-∞}^∞ f(x)dx = 1*
  - f(x)는 확률이 아님 (1을 초과할 수 있음)

*EN:   - f(x) is not a probability (can exceed 1)*
- **누적 분포 함수 (CDF)**: F(x) = P(X ≤ x)

*EN: - **Cumulative distribution function (CDF)**: F(x) = P(X ≤ x)*
  - 단조 감소하지 않고, 우연속

*EN:   - Non-decreasing, right-continuous*
  - F(-∞) = 0, F(∞) = 1

*EN:   - F(-∞) = 0, F(∞) = 1*
  - P(a < X ≤ b) = F(b) - F(a)

*EN:   - P(a < X ≤ b) = F(b) - F(a)*
  - 연속의 경우 F'(x) = f(x)

*EN:   - F'(x) = f(x) for continuous*
- **기댓값 E[X]**: 장기 평균

*EN: - **Expected value E[X]**: Long-run average*
  - 이산: E[X] = Σx·p(x)

*EN:   - Discrete: E[X] = Σx·p(x)*
  - 연속: E[X] = ∫x·f(x)dx

*EN:   - Continuous: E[X] = ∫x·f(x)dx*
  - 분포의 질량 중심

*EN:   - Center of mass of distribution*
  - 선형성: E[aX+b] = aE[X]+b

*EN:   - Linearity: E[aX+b] = aE[X]+b*
- **분산 Var(X)와 표준 편차 σ**: 퍼짐의 척도

*EN: - **Variance Var(X) and standard deviation σ**: Measure of spread*
  - Var(X) = E[(X-μ)²] = E[X²] - (E[X])²

*EN:   - Var(X) = E[(X-μ)²] = E[X²] - (E[X])²*
  - 표준 편차 σ = √Var(X)

*EN:   - Standard deviation σ = √Var(X)*
  - X와 같은 단위

*EN:   - Units same as X*
  - Var(aX+b) = a²Var(X)

*EN:   - Var(aX+b) = a²Var(X)*
- **무의식적 통계학자의 법칙**: E[g(X)] = Σg(x)p(x)

*EN: - **Law of Unconscious Statistician**: E[g(X)] = Σg(x)p(x)*
  - 분포를 구하지 않고 함수의 기댓값 계산

*EN:   - Compute expectation of function without finding its distribution*
  - E[X²] = Σx²p(x)

*EN:   - E[X²] = Σx²p(x)*

**이산 분포**

*EN: **Discrete Distributions***
- **베르누이 분포**: 단일 시행

*EN: - **Bernoulli**: single trial*
  - P(X=1) = p, P(X=0) = 1-p

*EN:   - P(X=1) = p, P(X=0) = 1-p*
  - 성공/실패 모델링

*EN:   - Models success/failure*
  - E[X] = p, Var(X) = p(1-p)

*EN:   - E[X] = p, Var(X) = p(1-p)*
- **이항 분포**: n번 시행, P(X=k) = C(n,k)p^k(1-p)^(n-k)

*EN: - **Binomial**: n trials, P(X=k) = C(n,k)p^k(1-p)^(n-k)*
  - n번의 독립 베르누이 시행에서 성공 횟수

*EN:   - Number of successes in n independent Bernoulli trials*
  - E[X] = np, Var(X) = np(1-p)

*EN:   - E[X] = np, Var(X) = np(1-p)*
  - n개의 독립 Bernoulli(p)의 합

*EN:   - Sum of n independent Bernoulli(p)*
- **기하 분포**: 처음 성공, 무기억성

*EN: - **Geometric**: first success, memoryless property*
  - 첫 번째 성공까지 시행 횟수

*EN:   - Number of trials until first success*
  - P(X=k) = (1-p)^(k-1)p

*EN:   - P(X=k) = (1-p)^(k-1)p*
  - E[X] = 1/p, Var(X) = (1-p)/p²

*EN:   - E[X] = 1/p, Var(X) = (1-p)/p²*
  - 무기억성: P(X>n+k|X>n) = P(X>k)

*EN:   - Memoryless: P(X>n+k|X>n) = P(X>k)*
- **포아송 분포**: 비율 λ, P(X=k) = e^(-λ)λ^k/k!

*EN: - **Poisson**: λ rate, P(X=k) = e^(-λ)λ^k/k!*
  - 고정된 시간/공간에서 사건 수

*EN:   - Number of events in fixed time/space*
  - n이 크고, p가 작고, np=λ일 때 이항 분포를 근사

*EN:   - Approximates binomial when n large, p small, np=λ*
  - E[X] = Var(X) = λ

*EN:   - E[X] = Var(X) = λ*
  - 희귀 사건 모델링

*EN:   - Models rare events*

**연속 분포**

*EN: **Continuous Distributions***
- **균일 분포**: 일정한 PDF

*EN: - **Uniform**: constant PDF*
  - f(x) = 1/(b-a), x ∈ [a,b]

*EN:   - f(x) = 1/(b-a) for x in [a,b]*
  - E[X] = (a+b)/2, Var(X) = (b-a)²/12

*EN:   - E[X] = (a+b)/2, Var(X) = (b-a)²/12*
  - 같은 길이의 모든 구간이 동등하게 확률적

*EN:   - All intervals of same length equally likely*
- **지수 분포**: 무기억성, λe^(-λx)

*EN: - **Exponential**: memoryless, λe^(-λx)*
  - 포아송 과정에서 사건까지의 시간

*EN:   - Time until event in Poisson process*
  - CDF: F(x) = 1 - e^(-λx)

*EN:   - CDF: F(x) = 1 - e^(-λx)*
  - E[X] = 1/λ, Var(X) = 1/λ²

*EN:   - E[X] = 1/λ, Var(X) = 1/λ²*
  - 기하 분포의 연속 유사체로 무기억성

*EN:   - Memoryless continuous analog of geometric*
- **정규 분포**: N(μ,σ²), 종형 곡선

*EN: - **Normal**: N(μ,σ²), bell curve*
  - f(x) = (1/√(2πσ²))e^(-(x-μ)²/(2σ²))

*EN:   - f(x) = (1/√(2πσ²))e^(-(x-μ)²/(2σ²))*
  - 평균 μ에 대해 대칭

*EN:   - Symmetric around mean μ*
  - 68-95-99.7 규칙 (μ±σ, μ±2σ, μ±3σ)

*EN:   - 68-95-99.7 rule (μ±σ, μ±2σ, μ±3σ)*
  - 통계학에서 가장 중요한 분포

*EN:   - Most important distribution in statistics*
- **표준 정규 분포 Z ~ N(0,1)**: 표준화된 정규 분포

*EN: - **Standard normal Z ~ N(0,1)**: Standardized normal*
  - Z = (X-μ)/σ

*EN:   - Z = (X-μ)/σ*
  - 확률에 대한 표 조회

*EN:   - Table lookups for probabilities*
  - 모든 정규 분포를 표준화로 환원 가능

*EN:   - All normal distributions reduce to standard*
- **중심 극한 정리**: 표본 평균이 정규 분포에 수렴

*EN: - **Central Limit Theorem**: Sample means approach normal*
  - ΣX_i/n → N(μ, σ²/n), n→∞

*EN:   - ΣX_i/n → N(μ, σ²/n) as n→∞*
  - 정규 분포의 편재성을 설명

*EN:   - Explains ubiquity of normal distribution*
  - 유한 분산을 가진 모든 분포에 적용

*EN:   - Works for any distribution (with finite variance)*
  - 통계적 추론의 기초

*EN:   - Foundation of statistical inference*
- **카이 제곱 χ²**: 정규 제곱의 합

*EN: - **Chi-square χ²**: Sum of squared normals*
  - χ²_k = Z_1² + ... + Z_k²

*EN:   - χ²_k = Z_1² + ... + Z_k²*
  - 적합도 검정, 독립성 검정에 사용

*EN:   - Used in goodness-of-fit, independence tests*
  - 비대칭, 양수 값만

*EN:   - Asymmetric, positive values only*
- **스튜던트 t 분포**: 소표본에 사용

*EN: - **Student's t-distribution**: For small samples*
  - 대칭, 정규 분포보다 두꺼운 꼬리

*EN:   - Symmetric, heavier tails than normal*
  - df→∞일 때 정규 분포에 수렴

*EN:   - Approaches normal as df→∞*
  - σ를 모를 때 사용

*EN:   - Used when σ unknown*
- **F 분포**: 카이 제곱의 비율

*EN: - **F-distribution**: Ratio of chi-squares*
  - 분산 분석, 회귀 분석에 사용

*EN:   - Used in ANOVA, regression*
  - F = (χ²_1/df_1)/(χ²_2/df_2)

*EN:   - F = (χ²_1/df_1)/(χ²_2/df_2)*
  - 항상 양수

*EN:   - Always positive*

**다변량 분포**

*EN: **Multivariate Distributions***
- **결합 PDF/PMF**: 여러 확률 변수에 대한 확률

*EN: - **Joint PDF/PMF**: Probability for multiple random variables*
  - f(x,y)는 (x,y)에서의 확률 밀도를 제공

*EN:   - f(x,y) gives probability density at (x,y)*
  - ∬ f(x,y)dxdy = 1

*EN:   - ∬ f(x,y)dxdy = 1*
  - P((X,Y) ∈ region) = ∬_region f(x,y)dxdy

*EN:   - P((X,Y) in region) = ∬_region f(x,y)dxdy*
- **주변 분포**: 하나의 변수 분포

*EN: - **Marginal distributions**: Distribution of one variable*
  - f_X(x) = ∫f(x,y)dy (다른 변수를 적분으로 제거)

*EN:   - f_X(x) = ∫f(x,y)dy (integrate out other variables)*
  - 결합 분포에서 개별 분포를 복원

*EN:   - Recover individual distributions from joint*
- **공분산과 상관 계수 ρ**: 선형 관계 측정

*EN: - **Covariance and correlation ρ**: Measure linear relationship*
  - Cov(X,Y) = E[(X-E[X])(Y-E[Y])] = E[XY] - E[X]E[Y]

*EN:   - Cov(X,Y) = E[(X-E[X])(Y-E[Y])] = E[XY] - E[X]E[Y]*
  - 상관 계수 ρ = Cov(X,Y)/(σ_Xσ_Y)

*EN:   - Correlation ρ = Cov(X,Y)/(σ_Xσ_Y)*
  - -1 ≤ ρ ≤ 1, ρ=0은 무상관

*EN:   - -1 ≤ ρ ≤ 1, ρ=0 means uncorrelated*
  - 독립 ⇒ 무상관, 역은 성립하지 않음

*EN:   - Independence ⇒ uncorrelated, but not converse*
- **다변량 정규 분포**: 정규 분포를 다차원으로 일반화

*EN: - **Multivariate normal**: Generalizes normal to multiple dimensions*
  - 평균 벡터와 공분산 행렬로 특성화

*EN:   - Characterized by mean vector and covariance matrix*
  - 주변 분포는 정규 분포

*EN:   - Marginals are normal*
  - 선형 결합은 정규 분포

*EN:   - Linear combinations are normal*
- **공분산 행렬**: Σ_ij = Cov(X_i, X_j)

*EN: - **Covariance matrix**: Σ_ij = Cov(X_i, X_j)*
  - 대칭, 양의 준정치

*EN:   - Symmetric, positive semi-definite*
  - 대각 원소는 분산

*EN:   - Diagonal entries are variances*
  - 다변량 정규 분포의 모양을 결정

*EN:   - Determines shape of multivariate normal*

**기술 통계**

*EN: **Descriptive Statistics***
- **집중 경향**: 평균, 중앙값, 최빈값

*EN: - **Central tendency**: mean, median, mode*
  - 평균: 산술 평균, 이상값에 민감

*EN:   - Mean: arithmetic average, sensitive to outliers*
  - 중앙값: 중간 값, 이상값에 강건

*EN:   - Median: middle value, robust to outliers*
  - 최빈값: 가장 빈번한 값

*EN:   - Mode: most frequent value*
- **분산도**: 범위, 분산, 사분위 범위

*EN: - **Dispersion**: range, variance, IQR*
  - 범위: 최대 - 최소

*EN:   - Range: max - min*
  - 분산: 평균에서 제곱 편차의 평균

*EN:   - Variance: average squared deviation from mean*
  - IQR: Q3 - Q1, 데이터의 중간 50%

*EN:   - IQR: Q3 - Q1, middle 50% of data*
- **표본 평균과 표본 분산 s²**: 데이터로부터의 추정치

*EN: - **Sample mean and sample variance s²**: Estimates from data*
  - 표본 평균 x̄ = Σx_i/n

*EN:   - Sample mean x̄ = Σx_i/n*
  - 표본 분산 s² = Σ(x_i - x̄)²/(n-1)

*EN:   - Sample variance s² = Σ(x_i - x̄)²/(n-1)*
  - n-1로 나눔 (베셀 보정): 불편 추정치

*EN:   - Divide by n-1 (Bessel's correction) for unbiased estimate*
- **분포 모양**: 왜도, 첨도

*EN: - **Distribution shape**: skewness, kurtosis*
  - 왜도: 비대칭 (양수 = 오른쪽 꼬리)

*EN:   - Skewness: asymmetry (positive = right tail)*
  - 첨도: 꼬리 두께

*EN:   - Kurtosis: tail heaviness*
  - 정규 분포: 왜도=0, 첨도=3

*EN:   - Normal has skewness=0, kurtosis=3*

**통계적 추론 - 추정**

*EN: **Statistical Inference - Estimation***
- **점 추정**: 불편성, 일치성, 효율성

*EN: - **Point estimation**: unbiased, consistent, efficient*
  - 불편성: E[θ̂] = θ

*EN:   - Unbiased: E[θ̂] = θ*
  - 일치성: n→∞일 때 θ̂ → θ

*EN:   - Consistent: θ̂ → θ as n→∞*
  - 효율성: 불편 추정치 중 최소 분산

*EN:   - Efficient: minimum variance among unbiased estimators*
- **최대 우도 추정 (MLE)**: 우도 함수를 최대화

*EN: - **Maximum Likelihood Estimation (MLE)**: Maximize likelihood function*
  - L(θ) = ∏p(x_i|θ)

*EN:   - L(θ) = ∏p(x_i|θ)*
  - 보통 로그 우도를 최대화

*EN:   - Usually maximize log-likelihood*
  - 점근적으로 효율적이고 정규 분포

*EN:   - Asymptotically efficient and normal*
- **적률 방법**: 표본 적률과 모집단 적률을 일치

*EN: - **Method of moments**: Match sample and population moments*
  - 표본 평균 = E[X]로 설정하여 매개변수 풀기

*EN:   - Set sample mean = E[X], solve for parameters*
  - 간단하지만 MLE보다 덜 효율적

*EN:   - Simple but less efficient than MLE*
- **신뢰 구간 (1-α 신뢰 수준)**: 매개변수의 범위

*EN: - **Confidence intervals with confidence level (1-α)**: Range for parameter*
  - 해석: (1-α)×100%의 구간이 진짜 매개변수를 포함

*EN:   - Interpretation: (1-α)×100% of intervals contain true parameter*
  - 매개변수가 구간 내에 있을 확률이 아님

*EN:   - NOT probability that parameter is in interval*
  - 더 넓은 구간이 더 높은 신뢰도

*EN:   - Wider intervals have higher confidence*
- **평균에 대한 신뢰 구간**: x̄ ± t(α/2) · s/√n

*EN: - **CI for mean**: x̄ ± t(α/2) · s/√n*
  - 자유도 n-1인 t 분포

*EN:   - t-distribution with n-1 degrees of freedom*
  - 큰 n이거나 σ를 알 때는 z 사용

*EN:   - Use z for large n or known σ*
  - 오차 한계는 √n에 반비례

*EN:   - Margin of error decreases with √n*
- **비율에 대한 신뢰 구간**: p̂ ± z(α/2) √(p̂(1-p̂)/n)

*EN: - **CI for proportion**: p̂ ± z(α/2) √(p̂(1-p̂)/n)*
  - p̂ = x/n (표본 비율)

*EN:   - p̂ = x/n (sample proportion)*
  - np̂, n(1-p̂) ≥ 10 필요

*EN:   - Requires np̂, n(1-p̂) ≥ 10*

**가설 검정**

*EN: **Hypothesis Testing***
- **귀무 가설 H₀ 대 대립 가설 H₁**: 경쟁하는 주장

*EN: - **Null hypothesis H₀ vs alternative H₁**: Competing claims*
  - H₀: 현 상태, 효과 없음

*EN:   - H₀: status quo, no effect*
  - H₁: 보여주고자 하는 것

*EN:   - H₁: what we want to show*
  - H₀를 기각하는 데 증명 책임

*EN:   - Burden of proof on rejecting H₀*
- **검정 통계량과 p값**: H₀에 대한 증거

*EN: - **Test statistic and p-value**: Evidence against H₀*
  - 검정 통계량: 데이터에서 표준화된 측도

*EN:   - Test statistic: standardized measure from data*
  - p값: H₀이 참일 때 관측 데이터(또는 더 극단적)가 나올 확률

*EN:   - p-value: probability of observing data (or more extreme) if H₀ true*
  - 작은 p값이 H₀에 대한 증거

*EN:   - Small p-value is evidence against H₀*
- **유의 수준 α (보통 0.05)**: 기각 임계값

*EN: - **Significance level α (typically 0.05)**: Threshold for rejection*
  - p값 < α이면 H₀ 기각

*EN:   - Reject H₀ if p-value < α*
  - 데이터를 보기 전에 사전 결정

*EN:   - Predetermined before seeing data*
  - 일반: 0.10, 0.05, 0.01

*EN:   - Common: 0.10, 0.05, 0.01*
- **1종 오류 (위양성, α) 및 2종 오류 (위음성, β)**: 결정 오류

*EN: - **Type I error (false positive, α) and Type II error (false negative, β)**: Decision errors*
  - 1종: 참인 H₀ 기각 (확률 = α)

*EN:   - Type I: reject true H₀ (probability = α)*
  - 2종: 거짓인 H₀를 기각하지 못함 (확률 = β)

*EN:   - Type II: fail to reject false H₀ (probability = β)*
  - 두 종류 사이의 상충 관계

*EN:   - Trade-off between types*
- **검정력 = 1 - β**: 실제 효과를 감지할 확률

*EN: - **Power = 1 - β**: Probability of detecting true effect*
  - 표본 크기, 효과 크기에 따라 증가

*EN:   - Increases with sample size, effect size*
  - 더 작은 α에 따라 감소

*EN:   - Decreases with smaller α*
- **Z 검정, t 검정 (단일 표본, 이중 표본, 대응 표본)**: 평균 검정

*EN: - **Z-test, t-test (one-sample, two-sample, paired)**: Testing means*
  - Z 검정: σ를 알거나 n이 클 때

*EN:   - Z-test: σ known or large n*
  - t 검정: σ를 모르고 n이 작거나 보통일 때

*EN:   - t-test: σ unknown, small to moderate n*
  - 단일 표본: μ = μ₀인지 검정

*EN:   - One-sample: test if μ = μ₀*
  - 이중 표본: μ₁ = μ₂인지 검정

*EN:   - Two-sample: test if μ₁ = μ₂*
  - 대응 표본: 평균 차이 = 0인지 검정

*EN:   - Paired: test if mean difference = 0*
- **카이 제곱 검정**: 적합도, 독립성

*EN: - **Chi-square tests**: goodness of fit, independence*
  - 적합도: 데이터가 분포에 맞는가?

*EN:   - Goodness of fit: does data fit distribution?*
  - 독립성: 교차표에서 변수들이 독립인가?

*EN:   - Independence: are variables independent in contingency table?*
  - χ² = Σ(O-E)²/E

*EN:   - χ² = Σ(O-E)²/E*

**회귀 분석**

*EN: **Regression Analysis***
- **단순 선형 회귀**: Y = β₀ + β₁X + ε

*EN: - **Simple linear regression**: Y = β₀ + β₁X + ε*
  - 변수 간의 선형 관계 모델링

*EN:   - Models linear relationship between variables*
  - β₀: 절편, β₁: 기울기

*EN:   - β₀: intercept, β₁: slope*
  - ε: 무작위 오차, E[ε]=0

*EN:   - ε: random error, E[ε]=0*
- **최소 제곱법**: Σ(y_i - ŷ_i)² 최소화

*EN: - **Least squares method**: Minimize Σ(y_i - ŷ_i)²*
  - β̂₁ = Σ(x_i-x̄)(y_i-ȳ)/Σ(x_i-x̄)²

*EN:   - β̂₁ = Σ(x_i-x̄)(y_i-ȳ)/Σ(x_i-x̄)²*
  - β̂₀ = ȳ - β̂₁x̄

*EN:   - β̂₀ = ȳ - β̂₁x̄*
  - 최량 선형 불편 추정량 (BLUE)

*EN:   - Best linear unbiased estimator (BLUE)*
- **R² 결정 계수**: 설명된 분산의 비율

*EN: - **R² coefficient of determination**: Proportion of variance explained*
  - R² = 1 - SS_res/SS_tot

*EN:   - R² = 1 - SS_res/SS_tot*
  - 0 ≤ R² ≤ 1

*EN:   - 0 ≤ R² ≤ 1*
  - R² = 1: 완벽한 적합, R² = 0: 선형 관계 없음

*EN:   - R² = 1: perfect fit, R² = 0: no linear relationship*
- **잔차 분석**: 모델 가정 확인

*EN: - **Residual analysis**: Check model assumptions*
  - 잔차 e_i = y_i - ŷ_i

*EN:   - Residuals e_i = y_i - ŷ_i*
  - 정규 분포, 평균 0, 등분산이어야 함

*EN:   - Should be normally distributed, mean 0, constant variance*
  - 잔차 대 적합값 그래프

*EN:   - Plot residuals vs fitted values*
- **다중 회귀**: Y = β₀ + β₁X₁ + ... + βₚXₚ + ε

*EN: - **Multiple regression**: Y = β₀ + β₁X₁ + ... + βₚXₚ + ε*
  - 여러 예측 변수

*EN:   - Multiple predictor variables*
  - 행렬 공식: β̂ = (X^TX)^(-1)X^Ty

*EN:   - Matrix formulation: β̂ = (X^TX)^(-1)X^Ty*
  - 수정된 R²는 예측 변수의 수를 고려

*EN:   - Adjusted R² accounts for number of predictors*
- **이진 결과에 대한 로지스틱 회귀**: log(p/(1-p)) = β₀ + β₁X

*EN: - **Logistic regression for binary outcomes**: log(p/(1-p)) = β₀ + β₁X*
  - Y는 이진 (0/1)

*EN:   - Y is binary (0/1)*
  - 성공 확률 모델링

*EN:   - Models probability of success*
  - p = e^(β₀+β₁X)/(1 + e^(β₀+β₁X))

*EN:   - p = e^(β₀+β₁X)/(1 + e^(β₀+β₁X))*

**분산 분석 (ANOVA)**

*EN: **ANOVA***
- **일원 및 이원 분산 분석**: 그룹 간 평균 비교

*EN: - **One-way and two-way ANOVA**: Compare means across groups*
  - 일원: 단일 요인 (예: 처리)

*EN:   - One-way: one factor (e.g., treatment)*
  - 이원: 두 요인 (예: 처리와 성별)

*EN:   - Two-way: two factors (e.g., treatment and gender)*
  - 그룹 평균이 같은지 검정

*EN:   - Tests if group means are equal*
- **F 통계량**: 그룹 간 분산 대 그룹 내 분산의 비

*EN: - **F-statistic**: Ratio of between-group to within-group variance*
  - F = MS_between/MS_within

*EN:   - F = MS_between/MS_within*
  - 큰 F는 차이의 증거

*EN:   - Large F is evidence of differences*
  - H₀ 하에서 F 분포 따름

*EN:   - Follows F-distribution under H₀*
- **다중 평균 비교**: 사후 검정

*EN: - **Comparing multiple means**: Post-hoc tests*
  - 본페로니, Tukey HSD 보정

*EN:   - Bonferroni, Tukey HSD corrections*
  - 가족별 오류율 통제

*EN:   - Control family-wise error rate*

**고급 주제**

*EN: **Advanced Topics***
- **베이즈 통계**: 사전분포, 우도, 사후분포

*EN: - **Bayesian statistics**: prior, likelihood, posterior*
  - 사전분포: 모수에 대한 초기 믿음

*EN:   - Prior: initial belief about parameter*
  - 우도: 모수가 주어졌을 때 데이터

*EN:   - Likelihood: data given parameter*
  - 사후분포 ∝ 우도 × 사전분포 (베이즈 정리)

*EN:   - Posterior ∝ likelihood × prior (Bayes' theorem)*
  - 데이터로 믿음 갱신

*EN:   - Update beliefs with data*
- **켤레 사전분포**: 사전분포와 사후분포가 같은 족

*EN: - **Conjugate priors**: Prior and posterior in same family*
  - 베타-이항, 정규-정규, 감마-포아송

*EN:   - Beta-Binomial, Normal-Normal, Gamma-Poisson*
  - 계산 단순화

*EN:   - Simplifies computation*
- **비모수적 방법**: 분포 가정 없음

*EN: - **Non-parametric methods**: No distribution assumptions*
  - 윌콕슨 검정: t 검정의 대안

*EN:   - Wilcoxon: alternative to t-test*
  - 크러스칼-월리스: ANOVA의 대안

*EN:   - Kruskal-Wallis: alternative to ANOVA*
  - 부트스트랩: 분포 추정을 위해 데이터 재표본

*EN:   - Bootstrap: resample data to estimate distributions*
- **시계열**: ARIMA, 정상성

*EN: - **Time series**: ARIMA, stationarity*
  - 자기상관: 지연 값과의 상관

*EN:   - Autocorrelation: correlation with lagged values*
  - 정상성: 시간에 따라 평균, 분산이 일정

*EN:   - Stationarity: mean, variance constant over time*
  - ARIMA: 자기회귀 적분 이동평균

*EN:   - ARIMA: AutoRegressive Integrated Moving Average*
- **생존 분석**: 카플란-마이어, 콕스 회귀

*EN: - **Survival analysis**: Kaplan-Meier, Cox regression*
  - 사건까지의 시간 (사망, 고장)

*EN:   - Time until event (death, failure)*
  - 중도절단: 불완전한 관측

*EN:   - Censoring: incomplete observations*
  - 카플란-마이어: 비모수적 생존 곡선

*EN:   - Kaplan-Meier: non-parametric survival curve*
  - 콕스: 비례 위험 모델

*EN:   - Cox: proportional hazards model*

**개념적 통찰**:

*EN: **Conceptual Insights**:*
- 확률은 공리를 사용하여 불확실성을 수량화한다

*EN: - Probability quantifies uncertainty using axioms*
- 확률 변수는 결과를 숫자로 변환한다

*EN: - Random variables map outcomes to numbers*
- 기댓값은 장기 평균이다

*EN: - Expected value is long-run average*
- 중심 극한 정리는 정규 분포가 어디서나 나타나는 이유를 설명한다

*EN: - Central Limit Theorem explains why normal distribution is ubiquitous*
- 통계적 추론은 표본을 사용하여 모집단을 이해한다

*EN: - Statistical inference uses samples to learn about populations*
- p값은 귀무 가설에 반하는 증거를 수량화한다

*EN: - p-values quantify evidence against null hypothesis*
- 베이즈 방법은 사전 지식을 통합한다

*EN: - Bayesian methods incorporate prior knowledge*

**핵심 응용**: Data science (machine learning, A/B testing), finance (risk management, portfolio optimization), medicine (clinical trials, epidemiology), physics (quantum mechanics, statistical mechanics), insurance (actuarial science), quality control, polling

*EN: \*\*Key Applications\*\*: Data science (machine learning, A/B testing), finance (risk management, portfolio optimization), medicine (clinical trials, epidemiology), physics (quantum mechanics, statistical mechanics), insurance (actuarial science), quality control, polling*

### 5. 이산 수학

*EN: ### 5. Discrete Mathematics*
이산 구조의 수학 - 컴퓨터 과학과 알고리즘적 사고의 토대. 이산 수학은 연속적인 양이 아닌 셀 수 있는 개별 객체를 다룬다:

*EN: The mathematics of discrete structures - foundational to computer science and algorithmic thinking. Discrete math deals with countable, distinct objects rather than continuous quantities:*

**논리 & 증명**

*EN: **Logic & Proofs***
- **명제 논리**: ¬, ∧, ∨, →, ↔

*EN: - **Propositional logic**: ¬, ∧, ∨, →, ↔*
  - 명제: 참 또는 거짓인 진술

*EN:   - Propositions: statements that are true or false*
  - 부정 ¬, 논리곱 ∧ (and), 논리합 ∨ (or)

*EN:   - Negation ¬, conjunction ∧ (and), disjunction ∨ (or)*
  - 함의 → (if-then), 쌍조건 ↔ (if and only if)

*EN:   - Implication → (if-then), biconditional ↔ (if and only if)*
  - 모든 수학적 추론의 토대

*EN:   - Foundation for all mathematical reasoning*
- **진리표**: 논리 공식의 체계적 평가

*EN: - **Truth tables**: Systematic evaluation of logical formulas*
  - 모든 진리값 조합 목록

*EN:   - List all possible combinations of truth values*
  - 각 조합에 대한 출력 결정

*EN:   - Determine output for each combination*
  - 논리적 동치 검증

*EN:   - Verify logical equivalences*
- **논리적 동치와 항진명제**: 항상 참인 공식

*EN: - **Logical equivalence and tautologies**: Always-true formulas*
  - 항진명제: 모든 진리 할당에서 참

*EN:   - Tautology: true for all truth assignments*
  - 모순: 항상 거짓

*EN:   - Contradiction: always false*
  - 동치: 같은 진리표

*EN:   - Equivalence: same truth table*
- **드 모르간의 법칙**: ¬(p∧q) ≡ ¬p∨¬q, ¬(p∨q) ≡ ¬p∧¬q

*EN: - **De Morgan's Laws**: ¬(p∧q) ≡ ¬p∨¬q, ¬(p∨q) ≡ ¬p∧¬q*
  - and/or에 부정 분배

*EN:   - Distribute negation over and/or*
  - 논리 단순화의 기본

*EN:   - Fundamental for simplifying logic*
- **양화사 ∀, ∃가 있는 술어 논리**: 변수를 포함한 논리

*EN: - **Predicate logic with quantifiers ∀, ∃**: Logic with variables*
  - 전칭 ∀x P(x): "모든 x에 대해 P(x)가 참"

*EN:   - Universal ∀x P(x): "for all x, P(x) is true"*
  - 존재 ∃x P(x): "P(x)가 되는 x가 존재한다"

*EN:   - Existential ∃x P(x): "there exists x such that P(x)"*
  - 명제 논리보다 더 표현력이 강함

*EN:   - More expressive than propositional logic*
- **증명 기법**: 직접 증명, 대우, 귀류법, 귀납법, 경우 분류

*EN: - **Proof techniques**: direct, contrapositive, contradiction, induction, cases*
  - 직접: 가정을 전제하여 결론 유도

*EN:   - Direct: assume hypothesis, derive conclusion*
  - 대우: p→q 대신 ¬q→¬p 증명

*EN:   - Contrapositive: prove ¬q→¬p instead of p→q*
  - 귀류법: ¬(결론)을 가정하여 모순 유도

*EN:   - Contradiction: assume ¬(conclusion), derive contradiction*
  - 경우 분류: 완전한 경우들로 분리

*EN:   - Cases: break into exhaustive cases*
- **수학적 귀납법**: 기저 단계, 귀납 단계, 강한 귀납법

*EN: - **Mathematical induction**: base case, inductive step, strong induction*
  - P(1)을 증명한 후, P(k)→P(k+1) 증명

*EN:   - Prove P(1), then P(k)→P(k+1)*
  - 모든 n≥1에 대해 P(n) 결론

*EN:   - Concludes P(n) for all n≥ 1*
  - 강한 귀납법: P(1),...,P(k)를 가정하여 P(k+1) 증명

*EN:   - Strong: assume P(1),...,P(k) to prove P(k+1)*

**집합 이론**

*EN: **Set Theory***
- **집합 표기법과 원소 관계**: {원소들}, x ∈ A

*EN: - **Set notation and membership**: {elements}, x ∈ A*
  - 집합: 서로 다른 객체들의 모음

*EN:   - Set: collection of distinct objects*
  - 원소 ∈은 "~의 원소"를 의미

*EN:   - Element ∈ means "is a member of"*
  - 공집합 ∅

*EN:   - Empty set ∅*
- **부분집합과 멱집합**: A ⊆ B, P(A)

*EN: - **Subsets and power sets**: A ⊆ B, P(A)*
  - A ⊆ B: A의 모든 원소가 B에 있음

*EN:   - A ⊆ B: every element of A is in B*
  - 멱집합 P(A): A의 모든 부분집합의 집합

*EN:   - Power set P(A): set of all subsets of A*
  - |P(A)| = 2^|A|

*EN:   - |P(A)| = 2^|A|*
- **집합 연산**: 합집합, 교집합, 여집합, 차집합, 카르테시안 곱

*EN: - **Set operations**: union, intersection, complement, difference, Cartesian product*
  - 합집합 A∪B: A 또는 B에 있는 원소

*EN:   - Union A∪B: elements in A or B*
  - 교집합 A∩B: 둘 다에 있는 원소

*EN:   - Intersection A∩B: elements in both*
  - 여집합 A^c: A에 없는 원소

*EN:   - Complement A^c: elements not in A*
  - 차집합 A\B: A에는 있지만 B에는 없는 원소

*EN:   - Difference A\B: elements in A but not B*
  - 카르테시안 곱 A×B: 순서쌍 (a,b)

*EN:   - Cartesian product A×B: ordered pairs (a,b)*
- **벤 다이어그램**: 집합의 시각적 표현

*EN: - **Venn diagrams**: Visual representation of sets*
  - 겹치는 원은 관계를 나타냄

*EN:   - Overlapping circles show relationships*
  - 연산 이해에 유용

*EN:   - Useful for understanding operations*
- **카디널리티**: |A| = 원소의 수

*EN: - **Cardinality**: |A| = number of elements*
  - 유한 대 무한 카디널리티

*EN:   - Finite vs infinite cardinality*
  - 다양한 크기의 무한

*EN:   - Different sizes of infinity*
- **이진 관계**: R ⊆ A×B

*EN: - **Binary relations**: R ⊆ A×B*
  - 반사적: 모든 x에 대해 xRx

*EN:   - Reflexive: xRx for all x*
  - 대칭적: xRy ⇒ yRx

*EN:   - Symmetric: xRy ⇒ yRx*
  - 추이적: xRy이고 yRz이면 xRz

*EN:   - Transitive: xRy and yRz ⇒ xRz*
  - 반대칭: xRy이고 yRx이면 x=y

*EN:   - Antisymmetric: xRy and yRx ⇒ x=y*
- **동치 관계와 동치류**: 집합 분할

*EN: - **Equivalence relations and equivalence classes**: Partition sets*
  - 동치: 반사적, 대칭적, 추이적

*EN:   - Equivalence: reflexive, symmetric, transitive*
  - 동치류 [x]: xRy가 되는 모든 y

*EN:   - Equivalence class [x]: all y with xRy*
  - 집합을 분리된 클래스로 분할

*EN:   - Partitions set into disjoint classes*
- **추이적 관계, 부분 순서, 하세 다이어그램**: 비교 불가능한 원소가 있는 순서

*EN: - **Partial orders, posets, Hasse diagrams**: Ordering with incomparables*
  - 부분 순서: 반사적, 반대칭, 추이적

*EN:   - Partial order: reflexive, antisymmetric, transitive*
  - 포셋: 부분 순서가 있는 집합

*EN:   - Poset: set with partial order*
  - 하세 다이어그램: 시각적 표현

*EN:   - Hasse diagram: visual representation*
- **함수**: 단사, 전사, 전단사, 역함수, 합성

*EN: - **Functions**: injective, surjective, bijective, inverse, composition*
  - 단사 (1-1): 서로 다른 입력 → 서로 다른 출력

*EN:   - Injective (1-1): distinct inputs → distinct outputs*
  - 전사 (onto): 모든 출력이 도달됨

*EN:   - Surjective (onto): every output is hit*
  - 전단사: 단사이면서 전사

*EN:   - Bijective: both injective and surjective*
  - 역함수 f^(-1): 함수를 반전

*EN:   - Inverse f^(-1): reverses function*
  - 합성 f∘g: g를 먼저 적용 후 f 적용

*EN:   - Composition f∘g: apply g then f*

**조합론**

*EN: **Combinatorics***
- **덧셈 및 곱셈 원리**: 기본 계산 규칙

*EN: - **Addition and multiplication principles**: Basic counting rules*
  - 덧셈: 상호 배타적 선택, 개수 더하기

*EN:   - Addition: mutually exclusive choices, add counts*
  - 곱셈: 독립적 선택, 개수 곱하기

*EN:   - Multiplication: independent choices, multiply counts*
  - 모든 계산의 토대

*EN:   - Foundation for all counting*
- **비둘기 집 원리**: n+1개를 n개의 구멍에 넣으면 ⇒ 어떤 구멍에는 ≥2개

*EN: - **Pigeonhole principle**: n+1 items in n holes ⇒ some hole has ≥2 items*
  - 존재를 보장하며, 구성은 보장하지 않음

*EN:   - Guarantees existence, not construction*
  - 일반화: kn+1개 ⇒ 어떤 구멍에는 ≥k+1개

*EN:   - Generalized: kn+1 items ⇒ some hole has ≥k+1*
- **순열**: P(n,r) = n!/(n-r)!

*EN: - **Permutations**: P(n,r) = n!/(n-r)!*
  - n개에서 r개를 고른 순서 있는 배열

*EN:   - Ordered arrangements of r items from n*
  - 순서가 중요

*EN:   - Order matters*
  - P(n,n) = n!

*EN:   - P(n,n) = n!*
- **조합**: C(n,r) = n!/[r!(n-r)!]

*EN: - **Combinations**: C(n,r) = n!/[r!(n-r)!]*
  - n개에서 r개를 고른 순서 없는 선택

*EN:   - Unordered selections of r items from n*
  - 순서가 중요하지 않음

*EN:   - Order doesn't matter*
  - C(n,r) = C(n,n-r)

*EN:   - C(n,r) = C(n,n-r)*
- **원형 순열**: 원 배치의 경우 (n-1)!/2

*EN: - **Circular permutations**: (n-1)!/2 for arrangements in circle*
  - 회전은 동일

*EN:   - Rotations are equivalent*
  - 반사도 동일할 수 있음

*EN:   - Reflections may also be equivalent*
- **중복 순열 및 중복 조합**: 변형된 공식

*EN: - **Permutations and combinations with repetition**: Modified formulas*
  - 중복 순열: n^r

*EN:   - Permutations with repetition: n^r*
  - 중복 조합: C(n+r-1,r)

*EN:   - Combinations with repetition: C(n+r-1,r)*
- **파스칼의 삼각형**: C(n,r)을 삼각형으로 배열

*EN: - **Pascal's triangle**: C(n,r) arranged in triangle*
  - 각 항목 = 위 두 항목의 합

*EN:   - Each entry = sum of two above*
  - C(n,r) = C(n-1,r-1) + C(n-1,r)

*EN:   - C(n,r) = C(n-1,r-1) + C(n-1,r)*
- **이항 정리**: (x+y)^n = ΣC(n,k)x^k y^(n-k)

*EN: - **Binomial theorem**: (x+y)^n = ΣC(n,k)x^k y^(n-k)*
  - 거듭제곱의 전개

*EN:   - Expansion of powers*
  - 계수는 이항 계수

*EN:   - Coefficients are binomial coefficients*
- **생성 함수**: 일반 생성 함수와 지수 생성 함수

*EN: - **Generating functions**: ordinary and exponential*
  - 수열을 멱급수로 인코딩

*EN:   - Encode sequences as power series*
  - 함수에 대한 연산 ↔ 수열에 대한 연산

*EN:   - Operations on functions ↔ operations on sequences*
  - 점화식 풀이에 강력한 도구

*EN:   - Powerful tool for solving recurrences*
- **점화 관계**: 선형 점화식, 특성 방정식

*EN: - **Recurrence relations**: linear recurrence, characteristic equation*
  - a_n = f(a_(n-1), a_(n-2), ...)

*EN:   - a_n = f(a_(n-1), a_(n-2), ...)*
  - 선형: a_n = c_1 a_(n-1) + c_2 a_(n-2) + ...

*EN:   - Linear: a_n = c_1 a_(n-1) + c_2 a_(n-2) + ...*
  - 특성 방정식으로 닫힌 형식 도출

*EN:   - Characteristic equation gives closed form*
- **피보나치 수열**: F_n = F_(n-1) + F_(n-2), F_0=0, F_1=1

*EN: - **Fibonacci sequence**: F_n = F_(n-1) + F_(n-2), F_0=0, F_1=1*
  - 점화식의 전형적인 예

*EN:   - Classic example of recurrence*
  - 수학과 자연 전반에 걸쳐 나타남

*EN:   - Appears throughout mathematics and nature*
  - 닫힌 형식: F_n = (φ^n - ψ^n)/√5, φ=(1+√5)/2

*EN:   - Closed form: F_n = (φ^n - ψ^n)/√5 where φ=(1+√5)/2*

**그래프 이론**

*EN: **Graph Theory***
- **그래프 G = (V,E)**: 꼭짓점과 간선

*EN: - **Graphs G = (V,E)**: vertices and edges*
  - V: 꼭짓점(노드)의 집합

*EN:   - V: set of vertices (nodes)*
  - E: 간선(연결)의 집합

*EN:   - E: set of edges (connections)*
  - 쌍 관계를 모델링

*EN:   - Models pairwise relationships*
- **인접성과 차수**: deg(v) = v에 연결된 간선의 수

*EN: - **Adjacency and degree**: deg(v) = number of edges incident to v*
  - 인접 꼭짓점: 간선으로 연결된

*EN:   - Adjacent vertices: connected by edge*
  - 차수: 이웃의 수

*EN:   - Degree: number of neighbors*
  - 고립 꼭짓점: 차수 0

*EN:   - Isolated vertex: degree 0*
- **핸드셰이킹 보조정리**: Σdeg(v) = 2|E|

*EN: - **Handshaking lemma**: Σdeg(v) = 2|E|*
  - 차수의 합 = 간선 수의 두 배

*EN:   - Sum of degrees = twice number of edges*
  - 홀수 차수 꼭짓점의 수는 짝수

*EN:   - Even number of odd-degree vertices*
- **그래프 표현**: 인접 행렬, 인접 리스트

*EN: - **Graph representation**: adjacency matrix, adjacency list*
  - 행렬: 간선 (i,j)가 있으면 A_ij = 1, O(n²) 공간

*EN:   - Matrix: A_ij = 1 if edge (i,j), O(n²) space*
  - 리스트: 각 꼭짓점에 대해 이웃 목록, O(n+m) 공간

*EN:   - List: for each vertex, list neighbors, O(n+m) space*
  - 공간과 쿼리 시간 사이의 상충 관계

*EN:   - Trade-off between space and query time*
- **유형**: 무방향, 방향(유향 그래프), 가중치, 단순, 다중 그래프

*EN: - **Types**: undirected, directed (digraph), weighted, simple, multigraph*
  - 무방향: 간선에 방향이 없음

*EN:   - Undirected: edges have no direction*
  - 방향: 간선에 방향이 있음 (화살표)

*EN:   - Directed: edges have direction (arrows)*
  - 가중치: 간선에 값이 있음

*EN:   - Weighted: edges have values*
  - 단순: 루프나 다중 간선 없음

*EN:   - Simple: no loops or multiple edges*
  - 다중 그래프: 꼭짓점 간에 여러 간선 허용

*EN:   - Multigraph: allows multiple edges between vertices*
- **경로와 순환**: 간선으로 연결된 꼭짓점의 수열

*EN: - **Paths and cycles**: Sequence of vertices connected by edges*
  - 경로: 꼭짓점이 모두 구별됨 (첫=마지막 제외)

*EN:   - Path: vertices all distinct (except possibly first=last)*
  - 순환: 닫힌 경로 (처음 = 마지막)

*EN:   - Cycle: closed path (first = last)*
  - 길이: 간선의 수

*EN:   - Length: number of edges*
- **연결 그래프**: 모든 꼭짓점 쌍 사이에 경로 존在

*EN: - **Connected graphs**: Path exists between every pair of vertices*
  - 비연결: 별도의 컴포넌트

*EN:   - Disconnected: separate components*
  - 강하게 연결됨 (유향 그래프): 양방향 유향 경로

*EN:   - Strongly connected (digraphs): directed path both ways*
- **오일러 경로/회로 (모든 간선 한 번)**: 모든 간선을 정확히 한 번 통과

*EN: - **Euler paths/circuits (all edges once)**: Traverse every edge exactly once*
  - 오일러 경로 ↔ 홀수 차수 꼭짓점이 0개 또는 2개

*EN:   - Euler path exists ↔ 0 or 2 odd-degree vertices*
  - 오일러 회로 ↔ 모든 꼭짓점의 차수가 짝수

*EN:   - Euler circuit exists ↔ all vertices even degree*
  - 쾨니히스베르크 다리 문제

*EN:   - Königsberg bridge problem*
- **해밀턴 경로/순환 (모든 꼭짓점 한 번)**: 모든 꼭짓점을 정확히 한 번 방문

*EN: - **Hamiltonian paths/cycles (all vertices once)**: Visit every vertex exactly once*
  - 단순한 특성화 없음 (NP-완전)

*EN:   - No simple characterization (NP-complete)*
  - 외판원 문제

*EN:   - Traveling salesman problem*
- **트리**: 연결된 비순환 그래프, |E| = |V| - 1

*EN: - **Trees**: connected acyclic graphs, |E| = |V| - 1*
  - 순환 없음

*EN:   - No cycles*
  - 임의의 두 꼭짓점 사이에 유일한 경로

*EN:   - Unique path between any two vertices*
  - n개의 꼭짓점에 n-1개의 간선

*EN:   - n-1 edges for n vertices*
  - 계층적 구조

*EN:   - Hierarchical structure*
- **이진 트리**: 완전, 포화

*EN: - **Binary trees**: full, complete*
  - 각 노드는 ≤2개의 자식

*EN:   - Each node has ≤2 children*
  - 포화: 모든 노드가 0 또는 2개의 자식

*EN:   - Full: every node has 0 or 2 children*
  - 완전: 마지막 레벨을 제외하고 모든 레벨이 가득 참

*EN:   - Complete: all levels full except possibly last*
- **트리 순회**: 전위, 중위, 후위

*EN: - **Tree traversal**: preorder, inorder, postorder*
  - 전위: 루트, 왼쪽, 오른쪽

*EN:   - Preorder: root, left, right*
  - 중위: 왼쪽, 루트, 오른쪽 (BST에서 정렬됨)

*EN:   - Inorder: left, root, right (sorted for BST)*
  - 후위: 왼쪽, 오른쪽, 루트

*EN:   - Postorder: left, right, root*
- **신장 트리와 최소 신장 트리**: 모든 꼭짓점 연결

*EN: - **Spanning trees and minimum spanning trees**: Connect all vertices*
  - 신장 트리: 트리인 부분 그래프

*EN:   - Spanning tree: subgraph that's a tree*
  - MST: 최소 합계 가중치의 신장 트리

*EN:   - MST: spanning tree with minimum total weight*
  - 간선 가중치가 모두 다르면 유일

*EN:   - Unique if all edge weights distinct*
- **크루스칼 및 프림 알고리즘**: MST 찾기

*EN: - **Kruskal's and Prim's algorithms**: Finding MST*
  - 크루스칼: 간선 정렬, 순환을 만들지 않으면 추가

*EN:   - Kruskal: sort edges, add if doesn't create cycle*
  - 프림: 시작 꼭짓점에서 트리 성장

*EN:   - Prim: grow tree from starting vertex*
  - 적절한 자료 구조로 O(E log V)

*EN:   - Both O(E log V) with good data structures*
- **그래프 순회**: BFS (너비 우선), DFS (깊이 우선)

*EN: - **Graph traversal**: BFS (breadth-first), DFS (depth-first)*
  - BFS: 시작점으로부터 거리 순으로 탐색 (큐)

*EN:   - BFS: explore by distance from start (queue)*
  - DFS: 가능한 한 깊이 먼저 탐색 (스택)

*EN:   - DFS: explore as far as possible first (stack)*
  - BFS는 가중치 없는 최단 경로 탐색

*EN:   - BFS finds shortest unweighted paths*
- **다익스트라 최단 경로 알고리즘**: 가중치 최단 경로

*EN: - **Dijkstra's algorithm for shortest path**: Weighted shortest path*
  - 단일 출발점 최단 경로

*EN:   - Single-source shortest paths*
  - 탐욕 알고리즘

*EN:   - Greedy algorithm*
  - 우선순위 큐로 O(E log V)

*EN:   - O(E log V) with priority queue*
  - 음수가 아닌 가중치 필요

*EN:   - Requires non-negative weights*
- **플로이드-워셜 모든 쌍 최단 경로**: 모든 꼭짓점 쌍

*EN: - **Floyd-Warshall for all pairs shortest paths**: Every pair of vertices*
  - 동적 프로그래밍

*EN:   - Dynamic programming*
  - O(V³) 시간

*EN:   - O(V³) time*
  - 음수 가중치 처리 (음수 순환 없는 경우)

*EN:   - Works with negative weights (no negative cycles)*
- **그래프 채색과 채색 수**: 꼭짓점에 색 배정

*EN: - **Graph coloring and chromatic number**: Assign colors to vertices*
  - 인접 꼭짓점은 다른 색

*EN:   - Adjacent vertices get different colors*
  - 채색 수 χ(G): 필요한 최소 색 수

*EN:   - Chromatic number χ(G): minimum colors needed*
  - 응용: 스케줄링, 레지스터 할당

*EN:   - Applications: scheduling, register allocation*
- **4색 정리**: 모든 평면 그래프는 4색으로 채색 가능

*EN: - **Four color theorem**: Any planar graph can be colored with 4 colors*
  - 컴퓨터를 이용하여 증명

*EN:   - Proved using computers*
  - 가장 유명한 정리 중 하나

*EN:   - One of most famous theorems*
- **평면 그래프와 오일러 공식**: v - e + f = 2

*EN: - **Planar graphs and Euler's formula**: v - e + f = 2*
  - 평면: 간선 교차 없이 그릴 수 있음

*EN:   - Planar: can be drawn without edge crossings*
  - v 꼭짓점, e 간선, f 면(영역)

*EN:   - v vertices, e edges, f faces (regions)*
  - K_5와 K_{3,3}은 평면이 아님

*EN:   - K_5 and K_{3,3} not planar*

**알고리즘**

*EN: **Algorithms***
- **계산 복잡도**: Big O, Ω, Θ 표기법

*EN: - **Computational complexity**: Big O, Ω, Θ notation*
  - Big O: 상한 (최악의 경우)

*EN:   - Big O: upper bound (worst case)*
  - Big Ω: 하한 (최선의 경우)

*EN:   - Big Ω: lower bound (best case)*
  - Big Θ: 엄밀한 한계 (평균적인 경우)

*EN:   - Big Θ: tight bound (average case)*
  - 입력 크기 → ∞에서 성장률 설명

*EN:   - Describes growth rate as input size → ∞*
- **복잡도 분류**: P, NP, NP-완전

*EN: - **Complexity classes**: P, NP, NP-complete*
  - P: 다항 시간에 풀 수 있음

*EN:   - P: solvable in polynomial time*
  - NP: 다항 시간에 검증 가능

*EN:   - NP: verifiable in polynomial time*
  - NP-완전: NP에서 가장 어려운 문제

*EN:   - NP-complete: hardest problems in NP*
  - P vs NP: CS에서 가장 큰 미해결 문제

*EN:   - P vs NP: biggest open problem in CS*
- **정렬**: 버블 정렬 O(n²), 병합 정렬 O(n log n), 퀵 정렬

*EN: - **Sorting**: bubble sort O(n²), merge sort O(n log n), quick sort*
  - 버블: 순서가 맞지 않으면 인접 원소 반복 교환

*EN:   - Bubble: repeatedly swap adjacent if out of order*
  - 병합: 분할 정복, 안정 정렬

*EN:   - Merge: divide-and-conquer, stable*
  - 퀵: 피벗 기준 분할, 평균 O(n log n)

*EN:   - Quick: partition around pivot, average O(n log n)*
  - 비교 정렬 하한: Ω(n log n)

*EN:   - Lower bound for comparison sorts: Ω(n log n)*
- **탐색**: 이진 탐색 O(log n)

*EN: - **Searching**: binary search O(log n)*
  - 이진: 단계마다 탐색 공간을 절반으로 줄임

*EN:   - Binary: halve search space each step*
  - 정렬된 배열 필요

*EN:   - Requires sorted array*
  - 로그 시간은 매우 빠름

*EN:   - Logarithmic is very fast*
- **분할 정복**: 부분 문제로 분해 후 해 결합

*EN: - **Divide and conquer**: Break into subproblems, combine solutions*
  - 병합 정렬, 퀵 정렬

*EN:   - Merge sort, quick sort*
  - 이진 탐색

*EN:   - Binary search*
  - 점화 관계: 마스터 정리

*EN:   - Recurrence relations: Master theorem*
- **탐욕 알고리즘**: 활동 선택, 허프만 코딩

*EN: - **Greedy algorithms**: activity selection, Huffman coding*
  - 각 단계에서 지역 최적 선택

*EN:   - Make locally optimal choice at each step*
  - 활동 선택: 가장 일찍 끝나는 활동 선택

*EN:   - Activity selection: choose earliest ending activity*
  - 허프만: 압축을 위한 최적 접두사 없는 코드

*EN:   - Huffman: optimal prefix-free codes for compression*
  - 항상 최적이지 않지만 자주 적용 가능

*EN:   - Not always optimal, but often works*
- **동적 프로그래밍**: 0/1 배낭 문제, 최장 공통 부분 수열, 메모이제이션

*EN: - **Dynamic programming**: 0/1 knapsack, longest common subsequence, memoization*
  - 부분 문제의 해 저장

*EN:   - Store solutions to subproblems*
  - 재계산 방지

*EN:   - Avoid recomputation*
  - 메모이제이션 (하향식) 대 탑재 (상향식)

*EN:   - Memoization (top-down) vs tabulation (bottom-up)*
  - 최적 부분 구조와 중복 부분 문제 필요

*EN:   - Optimal substructure and overlapping subproblems required*

**개념적 통찰**:

*EN: **Conceptual Insights**:*
- 논리는 수학적 추론을 위한 엄격한 틀을 제공한다

*EN: - Logic provides rigorous framework for mathematical reasoning*
- 증명 기법은 계산을 넘어선 진실을 확립한다

*EN: - Proof techniques establish truth beyond computation*
- 조합론은 배열과 선택을 계산한다

*EN: - Combinatorics counts arrangements and selections*
- 그래프는 객체 간의 관계를 모델링한다

*EN: - Graphs model relationships between objects*
- 알고리즘은 계산 문제를 효율적으로 해결한다

*EN: - Algorithms solve computational problems efficiently*
- 복잡도 이론은 문제의 난이도를 분류한다

*EN: - Complexity theory classifies problem difficulty*
- P vs NP는 중심 미해결 문제이다

*EN: - P vs NP is central unsolved problem*

**핵심 응용**: 컴퓨터 과학 (알고리즘, 자료 구조, 데이터베이스), 암호학 (RSA, 블록체인), 네트워크 분석 (소셜 네트워크, 인터넷 라우팅), 최적화 (스케줄링, 자원 할당), 인공 지능 (탐색, 계획), 회로 설계, 코딩 이론

*EN: **Key Applications**: Computer science (algorithms, data structures, databases), cryptography (RSA, blockchain), network analysis (social networks, internet routing), optimization (scheduling, resource allocation), artificial intelligence (search, planning), circuit design, coding theory*

### 6. 수리논리학 & 수학기초

*EN: ### 6. Mathematical Logic & Foundations*
수학 자체의 기초 - 공리, 증명, 형식 체계의 한계. 논리와 기초는 무엇을 증명할 수 있는지, 그리고 수학이 실제로 무엇인지를 다룬다:

*EN: The foundations of mathematics itself - axioms, proofs, and the limits of formal systems. Logic and foundations examine what can be proven and what mathematics really is:*

**집합 이론 - 공리적**

*EN: **Set Theory - Axiomatic***
- **소박한 집합 이론과 러셀의 역설**: 무제한 집합 형성은 모순을 초래

*EN: - **Naive set theory and Russell's paradox**: Unrestricted set formation leads to contradiction*
  - 러셀의 역설: R = {x : x ∉ x}, R ∈ R인가?

*EN:   - Russell's paradox: R = {x : x ∉ x}, does R ∈ R?*
  - 공리적 기초의 필요성을 보여줌

*EN:   - Shows need for axiomatic foundation*
  - 임의의 집합 정의를 허용할 수 없음

*EN:   - Can't allow arbitrary set definitions*
- **ZFC 공리**: 선택 공리가 있는 체르멜로-프렝켈

*EN: - **ZFC axioms**: Zermelo-Fraenkel with Choice*
  - 외연성: 같은 원소를 가지면 집합이 같음

*EN:   - Extensionality: sets equal if same elements*
  - 쌍원소: {a, b}가 존재

*EN:   - Pairing: {a, b} exists*
  - 합집합: ∪A가 존재

*EN:   - Union: ∪A exists*
  - 멱집합: P(A)가 존재

*EN:   - Power set: P(A) exists*
  - 무한: ℕ이 존재

*EN:   - Infinity: ℕ exists*
  - 치환: 함수에 의한 집합의 상은 집합

*EN:   - Replacement: image of set under function is set*
  - 정칙성: 무한 하강 원소 사슬 없음

*EN:   - Foundation: no infinite descending membership chains*
  - 선택 공리: 모음의 각 집합에서 선택 가능

*EN:   - Axiom of choice: can choose from each set in collection*
- **선택 공리의 동치**: 조른의 보조정리, 정렬 정리

*EN: - **Equivalents to axiom of choice**: Zorn's lemma, well-ordering theorem*
  - 조른: 모든 사슬에 상한이 있으면 ⇒ 극대 원소 존재

*EN:   - Zorn: every chain has upper bound ⇒ maximal element exists*
  - 정렬: 모든 집합은 정렬될 수 있음

*EN:   - Well-ordering: every set can be well-ordered*
  - 모두 AC와 논리적으로 동치

*EN:   - All logically equivalent to AC*
- **기수**: 유한 및 무한 (ℵ₀, ℵ₁, ...)

*EN: - **Cardinal numbers**: finite and infinite (ℵ₀, ℵ₁, ...)*
  - 집합의 "크기" 측정

*EN:   - Measure "size" of sets*
  - 전단사 함수가 존재하면 두 집합의 기수가 같음

*EN:   - Two sets same cardinality if bijection exists*
  - 무한 기수를 위한 알레프 수

*EN:   - Aleph numbers for infinite cardinals*
- **가산 무한 ℵ₀ = |ℕ|**: 가장 작은 무한 기수

*EN: - **Countable infinity ℵ₀ = |ℕ|**: Smallest infinite cardinal*
  - ℤ, ℚ는 가산

*EN:   - ℤ, ℚ are countable*
  - 가산 개의 가산 집합의 합집합은 가산

*EN:   - Union of countably many countable sets is countable*
- **연속체 |ℝ| = 2^ℵ₀**: 실수의 크기

*EN: - **Continuum |ℝ| = 2^ℵ₀**: Size of real numbers*
  - 칸토어의 대각 논법: ℝ은 불가산

*EN:   - Cantor's diagonal argument: ℝ uncountable*
  - ℵ₀보다 엄밀히 큼

*EN:   - Strictly larger than ℵ₀*
- **연속체 가설**: ℵ₀와 2^ℵ₀ 사이의 기수가 존재하는가?

*EN: - **Continuum hypothesis**: Is there a cardinality between ℵ₀ and 2^ℵ₀?*
  - CH: 2^ℵ₀ = ℵ₁ (중간 크기 없음)

*EN:   - CH: 2^ℵ₀ = ℵ₁ (no intermediate size)*
  - ZFC와 독립 (괴델, 코헨)

*EN:   - Independent of ZFC (Gödel, Cohen)*
- **칸토어 정리**: |A| < |P(A)|

*EN: - **Cantor's theorem**: |A| < |P(A)|*
  - 멱집합은 항상 엄밀히 더 큼

*EN:   - Power set always strictly larger*
  - 무한히 많은 무한 기수

*EN:   - Infinitely many infinite cardinals*
  - 가장 큰 기수는 없음

*EN:   - No largest cardinal*
- **서수와 초한 귀납법**: 정렬 위치

*EN: - **Ordinal numbers and transfinite induction**: Well-ordered position*
  - 자연수를 무한 너머로 확장

*EN:   - Extends natural numbers beyond infinity*
  - ω = 첫 번째 무한 서수

*EN:   - ω = first infinite ordinal*
  - ω+1, ω+2, ..., ω·2, ..., ω², ..., ωω, ...

*EN:   - ω+1, ω+2, ..., ω·2, ..., ω², ..., ωω, ...*
  - 초한 귀납법은 수학적 귀납법을 일반화한다

*EN:   - Transfinite induction generalizes mathematical induction*

**정수론**

*EN: **Number Theory***
- **나눗셈과 나눗셈 알고리즘**: a = bq + r, 0 ≤ r < b

*EN: - **Divisibility and division algorithm**: a = bq + r, 0 ≤ r < b*
  - a가 b를 나눔: a|b는 어떤 k에 대해 b = ak를 의미

*EN:   - a divides b: a|b means b = ak for some k*
  - 나눗셈 알고리즘: 유일한 몫과 나머지

*EN:   - Division algorithm: unique quotient and remainder*
- **최대 공약수 (GCD)와 유클리드 알고리즘**: 가장 큰 공약수

*EN: - **Greatest common divisor (GCD) and Euclidean algorithm**: Largest common divisor*
  - gcd(a,b) = d|a이고 d|b인 가장 큰 d

*EN:   - gcd(a,b) = largest d with d|a and d|b*
  - 유클리드 알고리즘: gcd(a,b) = gcd(b, a mod b)

*EN:   - Euclidean algorithm: gcd(a,b) = gcd(b, a mod b)*
  - O(log min(a,b)) 단계에서 종료

*EN:   - Terminates in O(log min(a,b)) steps*
- **베주의 항등식**: gcd(a,b) = ax + by

*EN: - **Bézout's identity**: gcd(a,b) = ax + by*
  - GCD는 a와 b의 선형 결합

*EN:   - GCD is linear combination of a and b*
  - x, y는 확장 유클리드 알고리즘으로 구함

*EN:   - x, y found by extended Euclidean algorithm*
  - 선형 디오판토스 방정식 풀이의 기반

*EN:   - Basis for solving linear Diophantine equations*
- **최소 공배수 (LCM)**: 가장 작은 공배수

*EN: - **Least common multiple (LCM)**: Smallest common multiple*
  - lcm(a,b) = ab/gcd(a,b)

*EN:   - lcm(a,b) = ab/gcd(a,b)*
  - lcm(a,b)·gcd(a,b) = ab

*EN:   - lcm(a,b)·gcd(a,b) = ab*
- **소수와 산술의 기본 정리**: 유일 인수분해

*EN: - **Prime numbers and fundamental theorem of arithmetic**: Unique factorization*
  - 소수: 1과 p만을 약수로 가지는 p > 1

*EN:   - Prime: p > 1 with only divisors 1 and p*
  - 1보다 큰 모든 정수는 소수로 유일하게 인수분해됨

*EN:   - Every n > 1 factors uniquely into primes*
  - 정수론의 기반

*EN:   - Foundation of number theory*
- **소수의 무한성 (유클리드 증명)**: 무한히 많은 소수 존재

*EN: - **Infinitude of primes (Euclid's proof)**: Infinitely many primes exist*
  - 유한하다고 가정하고 곱한 후 1을 더함

*EN:   - Assume finitely many, multiply and add 1*
  - 모순: 새 소수 또는 기존 소수가 1을 나눔

*EN:   - Contradiction: new prime or existing prime divides 1*
- **소수 정리**: π(x) ~ x/ln(x)

*EN: - **Prime number theorem**: π(x) ~ x/ln(x)*
  - π(x) = x 이하의 소수 개수

*EN:   - π(x) = number of primes ≤ x*
  - 소수의 점근 밀도

*EN:   - Asymptotic density of primes*
  - 아다마르와 드 라 발레 푸생이 독립 증명 (1896)

*EN:   - Proved independently by Hadamard and de la Vallée Poussin (1896)*
- **에라토스테네스의 체**: 소수 찾기 알고리즘

*EN: - **Sieve of Eratosthenes**: Algorithm to find primes*
  - 각 소수의 배수를 지움

*EN:   - Cross out multiples of each prime*
  - 남은 수가 소수

*EN:   - Remaining numbers are prime*
  - 고대 알고리즘 (기원전 200년)

*EN:   - Ancient algorithm (200 BC)*
- **모듈러 산술과 합동 a ≡ b (mod n)**: mod n 산술

*EN: - **Modular arithmetic and congruence a ≡ b (mod n)**: Arithmetic mod n*
  - n|(a-b)이면 a ≡ b (mod n)

*EN:   - a ≡ b (mod n) if n|(a-b)*
  - 동치류를 형성

*EN:   - Forms equivalence classes*
  - 덧셈, 곱셈에 대해 잘 정의됨

*EN:   - Addition, multiplication well-defined*
- **페르마의 소정리**: a^(p-1) ≡ 1 (mod p), p가 소수이고 p∤a일 때

*EN: - **Fermat's Little Theorem**: a^(p-1) ≡ 1 (mod p) if p prime, p∤a*
  - 군론의 라그랑주 정리의 결론

*EN:   - Consequence of Lagrange's theorem from group theory*
  - 소수성 검정의 기반

*EN:   - Basis for primality testing*
  - RSA에 사용됨

*EN:   - Used in RSA*
- **오일러 정리와 오일러 totient φ(n)**: 페르마의 일반화

*EN: - **Euler's theorem and Euler's totient φ(n)**: Generalization of Fermat*
  - φ(n) = n과 서로소인 n 이하의 정수 수

*EN:   - φ(n) = number of integers ≤ n coprime to n*
  - gcd(a,n) = 1이면 a^φ(n) ≡ 1 (mod n)

*EN:   - a^φ(n) ≡ 1 (mod n) if gcd(a,n) = 1*
  - 소수 p에 대해 φ(p) = p-1

*EN:   - φ(p) = p-1 for prime p*
- **중국인의 나머지 정리**: 연립 합동 방정식 풀기

*EN: - **Chinese Remainder Theorem**: Solve system of congruences*
  - n_i이 쌍마다 서로소이면, x ≡ a_i (mod n_i) 시스템은 ∏n_i를 mod로 유일한 해를 가짐

*EN:   - If n_i pairwise coprime, system x ≡ a_i (mod n_i) has unique solution mod ∏n_i*
  - 구성적 알고리즘

*EN:   - Constructive algorithm*
  - RSA 및 오류 수정 코드에 사용

*EN:   - Used in RSA and error-correcting codes*
- **RSA 암호화**: 공개키 암호화

*EN: - **RSA cryptography**: Public-key encryption*
  - 인수분해의 어려움에 기반

*EN:   - Based on difficulty of factoring*
  - 공개키 (n,e), 개인키 (n,d)

*EN:   - Public key (n,e), private key (n,d)*
  - 암호화: c = m^e mod n, 복호화: m = c^d mod n

*EN:   - Encrypt: c = m^e mod n, Decrypt: m = c^d mod n*
- **디오판토스 방정식**: 선형, 피타고라스 삼원수

*EN: - **Diophantine equations**: linear, Pythagorean triples*
  - 다항 방정식의 정수 해

*EN:   - Integer solutions to polynomial equations*
  - 선형: ax + by = c는 gcd(a,b)|c인 경우에만 풀 수 있음

*EN:   - Linear: ax + by = c solvable iff gcd(a,b)|c*
  - 피타고라스 삼원수: x²+y²=z², 예: (3,4,5)

*EN:   - Pythagorean triples: x²+y²=z², e.g., (3,4,5)*
- **페르마의 마지막 정리**: n>2일 때 x^n + y^n = z^n은 정수 해 없음

*EN: - **Fermat's Last Theorem**: x^n + y^n = z^n has no integer solutions for n>2*
  - 페르마가 추측 (1637)

*EN:   - Conjectured by Fermat (1637)*
  - 앤드루 와일스가 증명 (1995)

*EN:   - Proved by Andrew Wiles (1995)*
  - 가장 유명한 정리 중 하나

*EN:   - One of most famous theorems*

**수학적 귀납법**

*EN: **Mathematical Induction***
- **귀납법의 원리**: 기저 단계 + 귀납 단계

*EN: - **Principle of induction**: base case + inductive step*
  - P(1)이 참임을 증명

*EN:   - Prove P(1) is true*
  - 모든 k≥1에 대해 P(k) ⇒ P(k+1) 증명

*EN:   - Prove P(k) ⇒ P(k+1) for all k≥1*
  - 모든 n≥1에 대해 P(n)이 참임을 결론

*EN:   - Conclude P(n) true for all n≥1*
- **귀납 가정**: P(k+1)을 증명할 때 P(k) 가정

*EN: - **Inductive hypothesis**: Assume P(k) when proving P(k+1)*
  - 기저에서 모든 경우로의 다리

*EN:   - Bridge from base to all cases*
  - 귀납적 증명의 핵심 단계

*EN:   - Critical step in inductive proofs*
- **강한 귀납법**: P(k+1)을 증명하기 위해 P(1),...,P(k) 가정

*EN: - **Strong induction**: Assume P(1),...,P(k) to prove P(k+1)*
  - 더 강력한 가정

*EN:   - More powerful assumption*
  - 약한 귀납법보다 더 쉬울 때가 있음

*EN:   - Sometimes easier than weak induction*
  - 약한 귀납법과 논리적으로 동치

*EN:   - Logically equivalent to weak induction*
- **트리와 리스트에 대한 구조적 귀납법**: 재귀적 구조에 대한 귀납법

*EN: - **Structural induction on trees and lists**: Induction on recursive structures*
  - 기저: 빈 리스트 또는 잎 노드

*EN:   - Base: empty list or leaf*
  - 귀납: 부분 구조에 대해 가정

*EN:   - Inductive: assume for substructures*
  - 재귀적 정의에 자연스러움

*EN:   - Natural for recursive definitions*
- **정렬 원칙**: ℕ의 모든 공집합이 아닌 부분집합은 최솟값을 가짐

*EN: - **Well-ordering principle**: Every non-empty subset of ℕ has a minimum*
  - 자연수의 기본 성질

*EN:   - Fundamental property of natural numbers*
  - 최소 반례에 의한 증명 가능

*EN:   - Enables proof by minimal counterexample*
- **귀납법과 정렬 원칙의 동치**: 다른 형식화, 같은 효력

*EN: - **Equivalence between induction and well-ordering**: Different formulations, same power*
  - 서로 증명 가능

*EN:   - Can prove each from the other*
  - 둘 다 자연수를 특성화

*EN:   - Both characterize natural numbers*

**형식 체계**

*EN: **Formal Systems***
- **공리적 방법**: 공리, 연역 규칙, 정리

*EN: - **Axiomatic method**: axioms, deduction rules, theorems*
  - 공리: 참으로 가정된 진술

*EN:   - Axioms: assumed true statements*
  - 연역 규칙: 새로운 진술을 도출하는 방법

*EN:   - Deduction rules: how to derive new statements*
  - 정리: 도출된 진술

*EN:   - Theorems: derived statements*
  - 현대 수학의 기반

*EN:   - Foundation of modern mathematics*
- **예시**: 유클리드 기하학, 비유클리드 기하학

*EN: - **Examples**: Euclidean geometry, non-Euclidean geometry*
  - 유클리드 공리 (평행선 공리 포함)

*EN:   - Euclid's axioms (including parallel postulate)*
  - 쌍곡: 평행선 공리 불성립

*EN:   - Hyperbolic: parallel postulate fails*
  - 서로 다른 기하학들은 일관성이 있음

*EN:   - Different geometries are consistent*
- **증명론**: 형식적 증명, 일관성, 완전성

*EN: - **Proof theory**: formal proofs, consistency, completeness*
  - 형식적 증명: 공식들의 수열

*EN:   - Formal proof: sequence of formulas*
  - 일관성: 모순 없음

*EN:   - Consistency: no contradictions*
  - 완전성: 모든 진리가 증명 가능

*EN:   - Completeness: all truths are provable*
- **일관성 증명**: 체계에 모순이 없음을 보임

*EN: - **Consistency proofs**: Show system has no contradictions*
  - 상대적 일관성: A가 일관이면 B도 일관

*EN:   - Relative consistency: if A consistent, so is B*
  - 절대적 일관성은 더 어려움

*EN:   - Absolute consistency harder*
- **괴델의 완전성 정리 (1930)**: 1차 논리는 완전

*EN: - **Gödel's completeness theorem (1930)**: First-order logic complete*
  - 모든 유효한 공식은 증명 가능

*EN:   - Every valid formula is provable*
  - 의미론적 진리 = 통사론적 증명 가능성

*EN:   - Semantic truth = syntactic provability*
  - 1차 논리에만 해당

*EN:   - For first-order logic only*
- **모델 이론**: 해석, 모델, 건전성

*EN: - **Model theory**: interpretation, models, soundness*
  - 모델: 공리를 만족하는 구조

*EN:   - Model: structure satisfying axioms*
  - 해석: 의미 부여

*EN:   - Interpretation: assignment of meaning*
  - 건전성: 증명 가능 ⇒ 모든 모델에서 참

*EN:   - Soundness: provable ⇒ true in all models*
- **괴델의 불완전성 정리**: 형식 체계의 한계

*EN: - **Gödel's incompleteness theorems**: Limits of formal systems*
  - 1번째: 충분히 강한 체계에서 증명 불가능한 진리가 존재

*EN:   - First: unprovable truths exist in sufficiently strong systems*
    - 산술을 포함하는 모든 일관 체계에는 참이지만 증명 불가능한 진술이 있음

*EN:     - Any consistent system containing arithmetic has true but unprovable statements*
    - "이 진술은 증명 불가능하다"

*EN:     - "This statement is not provable"*
  - 2번째: 체계는 자신의 일관성을 증명할 수 없음

*EN:   - Second: system cannot prove its own consistency*
    - 일관성을 증명하려면 체계 밖으로 나가야 함

*EN:     - Must go outside system to prove consistency*
  - 수학과 논리에 혁명적

*EN:   - Revolutionary for mathematics and logic*
- **수학과 계산에 대한 함의**: 근본적 한계

*EN: - **Implications for mathematics and computation**: Fundamental limitations*
  - 모든 수학 문제에 대한 완전한 알고리즘 해법이 없음

*EN:   - No complete algorithmic solution to all math problems*
  - 형식적 검증의 한계

*EN:   - Limits of formal verification*
  - 철학: 수학은 단순히 기계적이지 않음

*EN:   - Philosophy: mathematics not just mechanical*
- **계산 가능성 이론**: 튜링 기계, 처치-튜링 논제, 결정 가능성, 정지 문제

*EN: - **Computability theory**: Turing machines, Church-Turing thesis, decidability, halting problem*
  - 튜링 기계: 이상적인 컴퓨터

*EN:   - Turing machine: idealized computer*
  - 처치-튜링 논제: 효과적 계산 = 튜링 계산

*EN:   - Church-Turing thesis: effective computation = Turing computation*
  - 결정 가능: 풀기 위한 알고리즘 존재

*EN:   - Decidable: algorithm exists to solve*
  - 정지 문제: 프로그램이 멈추는지 결정할 수 없음

*EN:   - Halting problem: can't determine if program halts*
  - 일부 문제는 결정 불가능

*EN:   - Some problems are undecidable*
- **재귀 함수와 재귀 집합**: 계산 가능한 함수와 집합

*EN: - **Recursive functions and recursive sets**: Computable functions and sets*
  - 재귀 함수: 알고리즘에 의해 계산 가능

*EN:   - Recursive function: can be computed by algorithm*
  - 재귀 집합: 원소 여부가 결정 가능

*EN:   - Recursive set: membership is decidable*
  - 재귀적 열거 가능: 원소를 나열 가능

*EN:   - Recursively enumerable: can list elements*

**개념적 통찰**:

*EN: **Conceptual Insights**:*
- 집합 이론은 모든 수학의 기초를 제공한다

*EN: - Set theory provides foundation for all mathematics*
- 선택 공리는 다른 ZFC 공리에 독립적이다

*EN: - Axiom of choice is independent of other ZFC axioms*
- 다양한 크기의 무한이 존재한다 (가산 대 불가산)

*EN: - Different sizes of infinity exist (countable vs uncountable)*
- 정수론은 정수의 성질을 연구한다

*EN: - Number theory studies properties of integers*
- 모듈러 산술은 암호학의 기반을 형성한다

*EN: - Modular arithmetic forms foundation of cryptography*
- 수학적 귀납법은 모든 자연수에 대한 진술을 증명한다

*EN: - Mathematical induction proves statements for all natural numbers*
- 괴델의 정리는 형식 체계의 한계를 보여준다

*EN: - Gödel's theorems show limits of formal systems*
- 일부 수학적 진리는 체계 안에서 증명될 수 없다

*EN: - Some mathematical truths cannot be proven within a system*
- 정지 문제는 계산이 근본적 한계를 가짐을 증명한다

*EN: - Halting problem proves computation has fundamental limits*

**핵심 응용**: 수학적 기초 (수학 철학), 암호학 (RSA, 타원 곡선), 컴퓨터 과학 (계산 가능성, 복잡도 이론), 논리 프로그래밍, 형식적 검증, 자동화된 정리 증명, 이론 컴퓨터 과학

*EN: **Key Applications**: Mathematical foundations (philosophy of mathematics), cryptography (RSA, elliptic curves), computer science (computability, complexity theory), logic programming, formal verification, automated theorem proving, theoretical computer science*

## 🔗 상호 연결

*EN: ## 🔗 Interconnections*
- 미적분과 선형대수는 모든 응용 수학의 기초이다

*EN: - Calculus and linear algebra are foundational for all applied mathematics*
- 미분 방정식은 과학과 공학에서의 변화를 모델링한다

*EN: - Differential equations model change in science and engineering*
- 확률/통계는 데이터 과학과 불확실성을 뒷받침한다

*EN: - Probability/statistics underpin data science and uncertainty*
- 이산 수학과 논리는 컴퓨터 과학에 필수적이다

*EN: - Discrete math and logic are essential for computer science*
- 수리논리학은 증명에 엄밀성과 구조를 제공한다

*EN: - Mathematical logic provides rigor and structure for proofs*

## 💡 학습 경로

*EN: ## 💡 Learning Path*
1. **미적분**과 **선형대수**로 시작

*EN: 1. Start with **Calculus** and **Linear Algebra***
2. **미분 방정식**으로 이동

*EN: 2. Move to **Differential Equations***
3. **확률 & 통계** 학습

*EN: 3. Study **Probability & Statistics***
4. **이산 수학** 탐구

*EN: 4. Explore **Discrete Mathematics***
5. **수리논리학 & 수학기초**로 마무리

*EN: 5. Finish with **Mathematical Logic & Foundations***

## 🎓 왜 중요한가

*EN: ## 🎓 Why This Matters*
수학은 과학, 기술, 공학의 언어이다. 수학은 다음을 가능하게 한다:

*EN: Mathematics is the language of science, technology, and engineering. It enables:*
- 실세계 문제 모델링과 해결

*EN: - Modeling and solving real-world problems*
- 데이터 분석과 예측

*EN: - Data analysis and prediction*
- 알고리즘과 컴퓨터 시스템 설계

*EN: - Design of algorithms and computer systems*
- 물리 법칙과 추상적 구조의 이해

*EN: - Understanding of physical laws and abstract structures*
- 비판적 사고와 논리적 추론

*EN: - Critical thinking and logical reasoning*

---

## 🔢 핵심 개념 & 방정식

*EN: ## 🔢 Key Concepts & Equations*

### 미적분

*EN: ### Calculus*
- **극한**: $\lim_{x \to a} f(x)$

*EN: - **Limit**: $\lim_{x \to a} f(x)$*
- **도함수**: $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

*EN: - **Derivative**: $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$*
- **적분**: $\int_a^b f(x) dx$

*EN: - **Integral**: $\int_a^b f(x) dx$*
- **미적분의 기본 정리**: $\frac{d}{dx} \int_a^x f(t) dt = f(x)$

*EN: - **Fundamental Theorem**: $\frac{d}{dx} \int_a^x f(t) dt = f(x)$*
- **연쇄 법칙**: $\frac{d}{dx} f(g(x)) = f'(g(x))g'(x)$

*EN: - **Chain Rule**: $\frac{d}{dx} f(g(x)) = f'(g(x))g'(x)$*
- **테일러 급수**: $f(x) = \sum_{n=0}^\infty \frac{f^{(n)}(a)}{n!}(x-a)^n$

*EN: - **Taylor Series**: $f(x) = \sum_{n=0}^\infty \frac{f^{(n)}(a)}{n!}(x-a)^n$*

### 선형대수

*EN: ### Linear Algebra*
- **행렬 곱셈**: $AB_{ij} = \sum_k A_{ik}B_{kj}$

*EN: - **Matrix Multiplication**: $AB_{ij} = \sum_k A_{ik}B_{kj}$*
- **행렬식**: $|A|$

*EN: - **Determinant**: $|A|$*
- **역행렬**: $A^{-1}$, $|A| \neq 0$인 경우

*EN: - **Inverse**: $A^{-1}$ if $|A| \neq 0$*
- **고유값 방정식**: $Av = \lambda v$

*EN: - **Eigenvalue Equation**: $Av = \lambda v$*
- **내적**: $\vec{a} \cdot \vec{b} = \sum a_i b_i$

*EN: - **Dot Product**: $\vec{a} \cdot \vec{b} = \sum a_i b_i$*
- **외적**: $\vec{a} \times \vec{b}$

*EN: - **Cross Product**: $\vec{a} \times \vec{b}$*

### 미분 방정식

*EN: ### Differential Equations*
- **1계 상미분방정식**: $\frac{dy}{dx} + P(x)y = Q(x)$

*EN: - **First Order ODE**: $\frac{dy}{dx} + P(x)y = Q(x)$*
- **변수 분리법**: $\frac{dy}{dx} = f(x)g(y)$

*EN: - **Separation of Variables**: $\frac{dy}{dx} = f(x)g(y)$*
- **특성 방정식**: $ay'' + by' + cy = 0$

*EN: - **Characteristic Equation**: $ay'' + by' + cy = 0$*
- **라플라스 변환**: $F(s) = \int_0^\infty e^{-st}f(t)dt$

*EN: - **Laplace Transform**: $F(s) = \int_0^\infty e^{-st}f(t)dt$*

### 확률 & 통계

*EN: ### Probability & Statistics*
- **확률**: $P(A) = \frac{\text{유리한 결과의 수}}{\text{전체 결과}}$

*EN: - **Probability**: $P(A) = \frac{\text{Number of favorable outcomes}}{\text{Total outcomes}}$*
- **기댓값**: $E[X] = \sum x_i P(x_i)$

*EN: - **Expected Value**: $E[X] = \sum x_i P(x_i)$*
- **분산**: $Var(X) = E[(X - E[X])^2]$

*EN: - **Variance**: $Var(X) = E[(X - E[X])^2]$*
- **정규 분포**: $f(x) = \frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$

*EN: - **Normal Distribution**: $f(x) = \frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$*
- **베이즈 정리**: $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

*EN: - **Bayes' Theorem**: $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$*

### 이산 수학

*EN: ### Discrete Mathematics*
- **논리**: $p \rightarrow q$, $\neg p$, $p \wedge q$, $p \vee q$

*EN: - **Logic**: $p \rightarrow q$, $\neg p$, $p \wedge q$, $p \vee q$*
- **귀납법에 의한 증명**: 기저 단계, 귀납 단계

*EN: - **Proof by Induction**: Base case, inductive step*
- **순열**: $n!$

*EN: - **Permutations**: $n!$*
- **조합**: $\binom{n}{k} = \frac{n!}{k!(n-k)!}$

*EN: - **Combinations**: $\binom{n}{k} = \frac{n!}{k!(n-k)!}$*
- **그래프**: $G = (V, E)$

*EN: - **Graph**: $G = (V, E)$*
- **오일러 공식**: $V - E + F = 2$ (평면 그래프의 경우)

*EN: - **Euler's Formula**: $V - E + F = 2$ (for planar graphs)*

### 수리논리학 & 수학기초

*EN: ### Mathematical Logic & Foundations*
- **집합**: $A = \{x | x \text{가 성질 } P\text{를 가짐}\}$

*EN: - **Set**: $A = \{x | x \text{ has property } P\}$*
- **함수**: $f: A \rightarrow B$

*EN: - **Function**: $f: A \rightarrow B$*
- **기수**: $|A|$

*EN: - **Cardinality**: $|A|$*
- **모듈러 산술**: $a \equiv b \pmod{n}$

*EN: - **Modular Arithmetic**: $a \equiv b \pmod{n}$*
- **페아노 공리**: 자연수의 기초

*EN: - **Peano Axioms**: Foundation for natural numbers*

---

## 📊 주요 상수 & Symbols

*EN: ## 📊 Important Constants & Symbols*
- $\pi \approx 3.14159$

*EN: - $\pi \approx 3.14159$*
- $e \approx 2.71828$

*EN: - $e \approx 2.71828$*
- $i = \sqrt{-1}$

*EN: - $i = \sqrt{-1}$*
- $\infty$: 무한대

*EN: - $\infty$: Infinity*
- $\emptyset$: 공집합

*EN: - $\emptyset$: Empty set*
- $\forall$: 임의의 (모든)

*EN: - $\forall$: For all*
- $\exists$: 존재한다

*EN: - $\exists$: There exists*
- $\sum$: 합산

*EN: - $\sum$: Summation*
- $\int$: 적분

*EN: - $\int$: Integral*
- $\partial$: 편미분

*EN: - $\partial$: Partial derivative*
- $\nabla$: 그래디언트

*EN: - $\nabla$: Gradient*
- $\Delta$: 변화/차이

*EN: - $\Delta$: Change/difference*
- $\lim$: 극한

*EN: - $\lim$: Limit*

---

## 🔗 Further Reading

*EN: ## 🔗 Further Reading*
- 미적분: Stewart, Spivak

*EN: - Calculus: Stewart, Spivak*
- 선형대수: Strang, Axler

*EN: - Linear Algebra: Strang, Axler*
- 미분방정식: Boyce & DiPrima

*EN: - Differential Equations: Boyce & DiPrima*
- 확률/통계: Ross, Freedman

*EN: - Probability/Statistics: Ross, Freedman*
- 이산 수학: Rosen

*EN: - Discrete Math: Rosen*
- 논리/기초: Enderton, Suppes

*EN: - Logic/Foundations: Enderton, Suppes*
