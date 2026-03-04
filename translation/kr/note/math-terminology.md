# 수학 용어집

*EN: # Mathematics Terminology*

> **네비게이션:** [허브](../math.md) | [수학 Notes](math-note.md) | [방정식](math-equations.md) | [미적분](../math/math-calculus.md) | [선형대수](../math/math-linear-algebra.md) | [Diff. Eq.](../math/math-differential-equations.md) | [Prob. & Stats](../math/math-probability-statistics.md) | [이산](../math/math-discrete.md) | [논리](../math/math-logic-foundations.md)

*EN: > \*\*Navigation:\*\* [Hub](../math.md) | [Math Notes](math-note.md) | [Equations](math-equations.md) | [Calculus](../math/math-calculus.md) | [Linear Algebra](../math/math-linear-algebra.md) | [Diff. Eq.](../math/math-differential-equations.md) | [Prob. & Stats](../math/math-probability-statistics.md) | [Discrete](../math/math-discrete.md) | [Logic](../math/math-logic-foundations.md)*

## 수학 마인드맵의 핵심 개념

*EN: ## Core Concepts from Mathematics Mindmaps*

### 미적분

*EN: ### Calculus*
- **극한**: 함수의 입력이 특정 점에 접근할 때 수렴하는 값

*EN: - \*\*Limit\*\*: Value that a function approaches as the input approaches a point*
- **연속성**: 함수에 단절, 점프, 구멍이 없는 성질

*EN: - \*\*Continuity\*\*: Property of a function having no breaks, jumps, or holes*
- **도함수**: 함수의 변화율; 접선의 기울기

*EN: - \*\*Derivative\*\*: Rate of change of a function; slope of tangent line*
- **미분**: 도함수를 구하는 과정

*EN: - \*\*Differentiation\*\*: Process of finding a derivative*
- **적분**: 누적 합; 곡선 아래의 넓이

*EN: - \*\*Integral\*\*: Accumulated sum; area under a curve*
- **적분법**: 적분을 구하는 과정

*EN: - \*\*Integration\*\*: Process of finding an integral*
- **정적분**: 특정 상한과 하한이 있는 적분

*EN: - \*\*Definite Integral\*\*: Integral with specified upper and lower bounds*
- **부정적분**: 역도함수; 경계가 없는 적분

*EN: - \*\*Indefinite Integral\*\*: Antiderivative; integral without bounds*
- **미적분의 기본정리**: 미분과 적분을 연결

*EN: - \*\*Fundamental Theorem of Calculus\*\*: Links differentiation and integration*
- **연쇄법칙**: 합성함수를 미분하는 방법

*EN: - \*\*Chain Rule\*\*: Method for differentiating composite functions*
- **곱의 법칙**: 함수의 곱을 미분하는 규칙

*EN: - \*\*Product Rule\*\*: Rule for differentiating products of functions*
- **몫의 법칙**: 함수의 몫을 미분하는 규칙

*EN: - \*\*Quotient Rule\*\*: Rule for differentiating quotients of functions*
- **음함수 미분**: 음함수로 정의된 함수의 도함수 구하기

*EN: - \*\*Implicit Differentiation\*\*: Finding derivatives of implicitly defined functions*
- **관련 변화율**: 연관된 양의 변화율에 관한 문제

*EN: - \*\*Related Rates\*\*: Problems involving rates of change of related quantities*
- **최적화**: 함수의 최댓값 또는 최솟값 구하기

*EN: - \*\*Optimization\*\*: Finding maximum or minimum values of functions*
- **임계점**: 도함수가 0이거나 정의되지 않는 점

*EN: - \*\*Critical Point\*\*: Point where derivative is zero or undefined*
- **변곡점**: 오목성이 바뀌는 점

*EN: - \*\*Inflection Point\*\*: Point where concavity changes*

#### 극한과 연속

*EN: #### Limits and Continuity*
- **극한의 정의**: lim(x→a) f(x) = L; f(x)가 x→a일 때 L에 수렴

*EN: - \*\*Limit Definition\*\*: lim(x→a) f(x) = L if f(x) approaches L as x approaches a*
- **엡실론-델타 정의**: 엄밀한 공식; 모든 ε > 0에 대해 δ > 0이 존재

*EN: - \*\*Epsilon-Delta Definition\*\*: Rigorous formulation; for every ε > 0, exists δ > 0*
- **단측 극한**: 좌극한(x→a⁻)과 우극한(x→a⁺)

*EN: - \*\*One-Sided Limit\*\*: Left-hand limit (x→a⁻) and right-hand limit (x→a⁺)*
- **무한 극한**: lim(x→∞) 또는 수직 점근선

*EN: - \*\*Infinite Limit\*\*: lim(x→∞) or vertical asymptotes*
- **극한의 성질**: 극한을 결합하는 합, 곱, 몫의 법칙

*EN: - \*\*Limit Properties\*\*: Sum, product, quotient rules for combining limits*
- **제거가능 불연속**: 그래프의 구멍; 극한은 존재하지만 f(a)가 미정의 또는 다른 값

*EN: - \*\*Removable Discontinuity\*\*: Hole in graph; limit exists but f(a) undefined or different*
- **점프 불연속**: 좌극한과 우극한이 존재하지만 서로 다른 경우

*EN: - \*\*Jump Discontinuity\*\*: Left and right limits exist but are different*
- **무한 불연속**: 수직 점근선

*EN: - \*\*Infinite Discontinuity\*\*: Vertical asymptote*
- **중간값 정리**: 연속함수는 f(a)와 f(b) 사이의 모든 값을 취함

*EN: - \*\*Intermediate Value Theorem\*\*: Continuous function takes all values between f(a) and f(b)*
- **극값 정리**: 닫힌 구간에서의 연속함수는 최댓값과 최솟값을 가짐

*EN: - \*\*Extreme Value Theorem\*\*: Continuous function on closed interval has maximum and minimum*

#### 미분법

*EN: #### Differentiation*
- **도함수의 정의**: f'(x) = lim(h→0) [f(x+h) - f(x)]/h

*EN: - \*\*Derivative Definition\*\*: f'(x) = lim(h→0) [f(x+h) - f(x)]/h*
- **기하학적 의미**: 한 점에서 접선의 기울기

*EN: - \*\*Geometric Meaning\*\*: Slope of tangent line at a point*
- **거듭제곱 규칙**: d/dx(xⁿ) = nxⁿ⁻¹

*EN: - \*\*Power Rule\*\*: d/dx(xⁿ) = nxⁿ⁻¹*
- **곱의 법칙**: (uv)' = u'v + uv'

*EN: - \*\*Product Rule\*\*: (uv)' = u'v + uv'*
- **몫의 법칙**: (u/v)' = (u'v - uv')/v²

*EN: - \*\*Quotient Rule\*\*: (u/v)' = (u'v - uv')/v²*
- **연쇄법칙**: d/dx f(g(x)) = f'(g(x)) · g'(x)

*EN: - \*\*Chain Rule\*\*: d/dx f(g(x)) = f'(g(x)) · g'(x)*
- **로그 미분법**: ln을 이용해 미분 전에 단순화

*EN: - \*\*Logarithmic Differentiation\*\*: Use ln to simplify before differentiating*
- **고계 도함수**: f'', f''', fⁿ

*EN: - \*\*Higher Order Derivatives\*\*: f'', f''', fⁿ*
- **접선**: y - y₀ = m(x - x₀), m = f'(x₀)

*EN: - \*\*Tangent Line\*\*: y - y₀ = m(x - x₀) where m = f'(x₀)*
- **일계 도함수 판정법**: 증가/감소 및 극값 결정

*EN: - \*\*First Derivative Test\*\*: Determines increasing/decreasing and local extrema*
- **이계 도함수 판정법**: 오목성 및 변곡점 결정

*EN: - \*\*Second Derivative Test\*\*: Determines concavity and inflection points*
- **평균값 정리**: f'(c) = [f(b) - f(a)]/(b - a), (a,b) 내의 어떤 c에 대해

*EN: - \*\*Mean Value Theorem\*\*: f'(c) = [f(b) - f(a)]/(b - a) for some c in (a,b)*
- **로피탈의 정리**: 0/0 또는 ∞/∞ 꼴의 부정형에 적용

*EN: - \*\*L'Hôpital's Rule\*\*: For indeterminate forms 0/0 or ∞/∞*

#### 적분법

*EN: #### Integration*
- **역도함수**: F'(x) = f(x)인 함수 F

*EN: - \*\*Antiderivative\*\*: Function F where F'(x) = f(x)*
- **부정적분**: ∫f(x)dx = F(x) + C

*EN: - \*\*Indefinite Integral\*\*: ∫f(x)dx = F(x) + C*
- **정적분**: ∫ᵃᵇ f(x)dx; 곡선 아래의 넓이

*EN: - \*\*Definite Integral\*\*: ∫ᵃᵇ f(x)dx; represents area under curve*
- **기본정리 제1부**: d/dx ∫ᵃˣ f(t)dt = f(x)

*EN: - \*\*Fundamental Theorem Part 1\*\*: d/dx ∫ᵃˣ f(t)dt = f(x)*
- **기본정리 제2부**: ∫ᵃᵇ f(x)dx = F(b) - F(a)

*EN: - \*\*Fundamental Theorem Part 2\*\*: ∫ᵃᵇ f(x)dx = F(b) - F(a)*
- **치환 적분법**: ∫f(g(x))g'(x)dx = ∫f(u)du, u = g(x)

*EN: - \*\*u-Substitution\*\*: ∫f(g(x))g'(x)dx = ∫f(u)du where u = g(x)*
- **부분 적분법**: ∫udv = uv - ∫vdu

*EN: - \*\*Integration by Parts\*\*: ∫udv = uv - ∫vdu*
- **부분분수 분해**: 적분을 위해 유리함수 분해

*EN: - \*\*Partial Fractions\*\*: Decompose rational functions for integration*
- **삼각 치환법**: 삼각 항등식을 이용해 근호 처리

*EN: - \*\*Trigonometric Substitution\*\*: Handle radicals using trig identities*
- **누적 함수**: A(x) = ∫ᵃˣ f(t)dt

*EN: - \*\*Accumulation Function\*\*: A(x) = ∫ᵃˣ f(t)dt*
- **두 곡선 사이의 넓이**: ∫[f(x) - g(x)]dx

*EN: - \*\*Area Between Curves\*\*: ∫[f(x) - g(x)]dx*
- **회전체의 부피**: 원판법, 세탁기법, 껍질법

*EN: - \*\*Volume of Revolution\*\*: Disk, washer, and shell methods*
- **호의 길이**: ∫√(1 + [f'(x)]²)dx

*EN: - \*\*Arc Length\*\*: ∫√(1 + [f'(x)]²)dx*
- **일**: W = ∫F(x)dx

*EN: - \*\*Work\*\*: W = ∫F(x)dx*
- **이상적분**: 무한한 한계 또는 불연속

*EN: - \*\*Improper Integral\*\*: Infinite limits or discontinuities*

#### 수열과 급수

*EN: #### Sequences and Series*
- **수열**: 순서 있는 목록 aₙ

*EN: - \*\*Sequence\*\*: Ordered list aₙ*
- **수렴**: lim(n→∞) aₙ이 존재하고 유한한 경우

*EN: - \*\*Convergence\*\*: lim(n→∞) aₙ exists and is finite*
- **무한급수**: ∑(n=1~∞) aₙ

*EN: - \*\*Infinite Series\*\*: ∑(n=1 to ∞) aₙ*
- **등비급수**: ∑arⁿ = a/(1-r), |r| < 1인 경우

*EN: - \*\*Geometric Series\*\*: ∑arⁿ = a/(1-r) if |r| < 1*
- **비교 판정법**: 알려진 수렴/발산 급수와 비교

*EN: - \*\*Comparison Test\*\*: Compare with known convergent/divergent series*
- **비율 판정법**: lim |aₙ₊₁/aₙ|; 1보다 작으면 수렴, 크면 발산

*EN: - \*\*Ratio Test\*\*: lim |aₙ₊₁/aₙ|; converges if < 1, diverges if > 1*
- **근 판정법**: lim |aₙ|^(1/n); 1보다 작으면 수렴, 크면 발산

*EN: - \*\*Root Test\*\*: lim |aₙ|^(1/n); converges if < 1, diverges if > 1*
- **적분 판정법**: 급수를 이상적분과 비교

*EN: - \*\*Integral Test\*\*: Compare series to improper integral*
- **교대급수 판정법**: 교대급수의 라이프니츠 기준

*EN: - \*\*Alternating Series Test\*\*: Leibniz criterion for alternating series*
- **거듭제곱급수**: ∑cₙ(x-a)ⁿ; 함수를 무한 다항식으로 표현

*EN: - \*\*Power Series\*\*: ∑cₙ(x-a)ⁿ; function represented as infinite polynomial*
- **수렴반경**: 거듭제곱급수가 수렴하는 구간

*EN: - \*\*Radius of Convergence\*\*: Interval where power series converges*
- **테일러 급수**: f(x) = ∑[fⁿ(a)/n!](x-a)ⁿ; 다항식 근사

*EN: - \*\*Taylor Series\*\*: f(x) = ∑[fⁿ(a)/n!](x-a)ⁿ; polynomial approximation*
- **맥클로린 급수**: a = 0에서의 테일러 급수

*EN: - \*\*Maclaurin Series\*\*: Taylor series at a = 0*
- **주요 급수**: eˣ, sin(x), cos(x), ln(1+x)

*EN: - \*\*Common Series\*\*: eˣ, sin(x), cos(x), ln(1+x)*

#### 다변수 미적분

*EN: #### Multivariable Calculus*
- **다변수 함수**: 여러 독립변수를 가진 f(x,y,z)

*EN: - \*\*Functions of Several Variables\*\*: f(x,y,z) with multiple independent variables*
- **편미분**: ∂f/∂x; 한 변수에 대한 도함수, 나머지는 상수 취급

*EN: - \*\*Partial Derivative\*\*: ∂f/∂x; derivative with respect to one variable, others constant*
- **고계 편미분**: fₓₓ, fₓᵧ, fᵧᵧ; 혼합 편미분

*EN: - \*\*Higher Order Partials\*\*: fₓₓ, fₓᵧ, fᵧᵧ; mixed partials*
- **클레로 정리**: 연속이면 fₓᵧ = fᵧₓ

*EN: - \*\*Clairaut's Theorem\*\*: fₓᵧ = fᵧₓ if continuous*
- **기울기 벡터**: ∇f = ⟨∂f/∂x, ∂f/∂y⟩; 최대 증가 방향을 가리킴

*EN: - \*\*Gradient Vector\*\*: ∇f = ⟨∂f/∂x, ∂f/∂y⟩; points in direction of maximum increase*
- **방향 도함수**: Dᵤf = ∇f · u; 방향 u에서의 변화율

*EN: - \*\*Directional Derivative\*\*: Dᵤf = ∇f · u; rate of change in direction u*
- **연쇄법칙 (다변수)**: 여러 변수의 합성함수에 대한 규칙

*EN: - \*\*Chain Rule (Multivariable)\*\*: For composite functions of several variables*
- **접평면**: 한 점에서의 선형 근사

*EN: - \*\*Tangent Plane\*\*: Linear approximation at a point*
- **임계점**: ∇f = 0인 점

*EN: - \*\*Critical Points\*\*: Where ∇f = 0*
- **헤시안 행렬**: 이계 편미분의 행렬

*EN: - \*\*Hessian Matrix\*\*: Matrix of second partial derivatives*
- **이계 도함수 판정법**: 분류를 위해 헤시안 행렬식 D 사용

*EN: - \*\*Second Derivative Test\*\*: Uses Hessian determinant D for classification*
- **라그랑주 승수법**: 제약 최적화 방법; ∇f = λ∇g

*EN: - \*\*Lagrange Multipliers\*\*: Method for constrained optimization; ∇f = λ∇g*
- **이중 적분**: ∬ f(x,y)dA; 곡면 아래의 부피

*EN: - \*\*Double Integral\*\*: ∬ f(x,y)dA; volume under surface*
- **삼중 적분**: ∭ f(x,y,z)dV; 영역의 질량 또는 전하량

*EN: - \*\*Triple Integral\*\*: ∭ f(x,y,z)dV; mass or charge in region*
- **반복 적분**: ∫∫f(x,y)dxdy; 중첩된 적분으로 계산

*EN: - \*\*Iterated Integral\*\*: ∫∫f(x,y)dxdy; computed as nested integrals*
- **극좌표**: (r,θ); 원형 영역에 유용

*EN: - \*\*Polar Coordinates\*\*: (r,θ); useful for circular regions*
- **원기둥 좌표**: (r,θ,z); 원기둥에 유용

*EN: - \*\*Cylindrical Coordinates\*\*: (r,θ,z); useful for cylinders*
- **구면 좌표**: (ρ,θ,φ); 구에 유용

*EN: - \*\*Spherical Coordinates\*\*: (ρ,θ,φ); useful for spheres*
- **야코비안**: det(∂(x,y)/∂(u,v)); 변수 변환에 사용

*EN: - \*\*Jacobian\*\*: det(∂(x,y)/∂(u,v)); for change of variables*

#### 벡터 미적분

*EN: #### Vector Calculus*
- **벡터장**: F(x,y,z) = ⟨P,Q,R⟩; 각 점에 벡터 할당

*EN: - \*\*Vector Field\*\*: F(x,y,z) = ⟨P,Q,R⟩; assigns vector to each point*
- **회전(컬)**: ∇ × F; 벡터장의 회전 측정

*EN: - \*\*Curl\*\*: ∇ × F; measures rotation of vector field*
- **발산**: ∇ · F; 외부로 흐르는 경향 측정

*EN: - \*\*Divergence\*\*: ∇ · F; measures tendency to flow outward*
- **보존장**: 어떤 퍼텐셜 함수 f에 대해 ∇f = F

*EN: - \*\*Conservative Field\*\*: ∇f = F for some potential function f*
- **경로 독립성**: 보존장에서 ∫F·dr은 경로와 무관

*EN: - \*\*Path Independence\*\*: ∫F·dr independent of path for conservative fields*
- **퍼텐셜 함수**: ∇f = F를 만족하는 f

*EN: - \*\*Potential Function\*\*: f such that ∇f = F*
- **선적분**: ∫ᶜ F·dr; 힘장이 하는 일

*EN: - \*\*Line Integral\*\*: ∫ᶜ F·dr; work done by force field*
- **면적분**: ∬ₛ F·dS; 곡면을 통과하는 플럭스

*EN: - \*\*Surface Integral\*\*: ∬ₛ F·dS; flux through surface*
- **그린의 정리**: ∮ᶜ F·dr = ∬ᴰ (∂Q/∂x - ∂P/∂y)dA

*EN: - \*\*Green's Theorem\*\*: ∮ᶜ F·dr = ∬ᴰ (∂Q/∂x - ∂P/∂y)dA*
- **스토크스 정리**: ∮ᶜ F·dr = ∬ₛ (∇×F)·dS

*EN: - \*\*Stokes' Theorem\*\*: ∮ᶜ F·dr = ∬ₛ (∇×F)·dS*
- **발산 정리**: ∬ₛ F·dS = ∭ᴱ (∇·F)dV; 가우스 정리

*EN: - \*\*Divergence Theorem\*\*: ∬ₛ F·dS = ∭ᴱ (∇·F)dV; Gauss's theorem*

### 선형대수

*EN: ### Linear Algebra*
- **벡터**: 크기와 방향을 가진 수학적 대상

*EN: - \*\*Vector\*\*: Mathematical object with magnitude and direction*
- **스칼라**: 방향이 없는 단일 수치

*EN: - \*\*Scalar\*\*: Single numerical value without direction*
- **행렬**: 수의 직사각형 배열

*EN: - \*\*Matrix\*\*: Rectangular array of numbers*
- **선형변환**: 벡터 덧셈과 스칼라 곱을 보존하는 함수

*EN: - \*\*Linear Transformation\*\*: Function preserving vector addition and scalar multiplication*
- **벡터 공간**: 덧셈과 스칼라 곱이 정의된 벡터의 집합

*EN: - \*\*Vector Space\*\*: Set of vectors with defined addition and scalar multiplication*
- **기저**: 벡터 공간을 생성하는 선형 독립 벡터의 집합

*EN: - \*\*Basis\*\*: Set of linearly independent vectors spanning a vector space*
- **차원**: 기저의 벡터 수

*EN: - \*\*Dimension\*\*: Number of vectors in a basis*
- **선형 독립**: 어떤 벡터도 나머지의 선형 결합이 아닌 벡터들

*EN: - \*\*Linear Independence\*\*: Vectors where no vector is a linear combination of others*
- **선형 결합**: 벡터의 스칼라 배수의 합

*EN: - \*\*Linear Combination\*\*: Sum of scalar multiples of vectors*
- **생성**: 벡터 집합의 모든 선형 결합의 집합

*EN: - \*\*Span\*\*: Set of all linear combinations of a set of vectors*
- **부분 공간**: 벡터 공간의 부분집합으로 그 자체가 벡터 공간

*EN: - \*\*Subspace\*\*: Subset of vector space that is itself a vector space*
- **내적**: 점곱의 일반화

*EN: - \*\*Inner Product\*\*: Generalization of dot product*
- **점곱**: 두 벡터의 스칼라 곱

*EN: - \*\*Dot Product\*\*: Scalar product of two vectors*
- **외적**: 두 입력 벡터에 수직인 벡터 곱

*EN: - \*\*Cross Product\*\*: Vector product perpendicular to two input vectors*
- **노름**: 벡터 길이 또는 크기의 측도

*EN: - \*\*Norm\*\*: Measure of vector length or magnitude*
- **직교**: 수직; 내적이 0

*EN: - \*\*Orthogonal\*\*: Perpendicular; inner product equals zero*
- **정규직교**: 단위 길이를 갖는 직교 벡터

*EN: - \*\*Orthonormal\*\*: Orthogonal vectors with unit length*
- **행렬 곱셈**: 행렬을 결합하여 새로운 행렬 생성

*EN: - \*\*Matrix Multiplication\*\*: Combining matrices to produce a new matrix*
- **행렬식**: 행렬의 성질을 담은 스칼라 값

*EN: - \*\*Determinant\*\*: Scalar value encoding properties of a matrix*
- **역행렬**: 다른 행렬의 변환을 되돌리는 행렬

*EN: - \*\*Inverse Matrix\*\*: Matrix that undoes another matrix's transformation*
- **전치**: 행과 열을 교환하여 얻은 행렬

*EN: - \*\*Transpose\*\*: Matrix obtained by swapping rows and columns*
- **고유값**: 고유벡터 v에 대해 Av = λv를 만족하는 스칼라 λ

*EN: - \*\*Eigenvalue\*\*: Scalar λ where Av = λv for eigenvector v*
- **고유벡터**: 변환에 의해 방향이 변하지 않는 영벡터가 아닌 벡터

*EN: - \*\*Eigenvector\*\*: Non-zero vector whose direction is unchanged by transformation*
- **대각화**: 고유벡터를 이용해 행렬을 대각 형태로 표현

*EN: - \*\*Diagonalization\*\*: Expressing matrix in diagonal form using eigenvectors*
- **계수**: 선형 독립인 행 또는 열 벡터의 최대 수

*EN: - \*\*Rank\*\*: Maximum number of linearly independent row or column vectors*
- **영공간**: 행렬에 의해 0으로 매핑되는 벡터의 집합

*EN: - \*\*Null Space\*\*: Set of vectors mapped to zero by a matrix*

### 미분방정식

*EN: ### Differential Equations*
- **미분방정식**: 미지 함수의 도함수를 포함한 방정식

*EN: - \*\*Differential Equation\*\*: Equation involving derivatives of unknown function*
- **상미분방정식 (ODE)**: 독립변수가 하나인 미분방정식

*EN: - \*\*Ordinary Differential Equation (ODE)\*\*: DE with one independent variable*
- **편미분방정식 (PDE)**: 독립변수가 여러 개인 미분방정식

*EN: - \*\*Partial Differential Equation (PDE)\*\*: DE with multiple independent variables*
- **계수**: 방정식에 나타나는 가장 높은 차수의 도함수

*EN: - \*\*Order\*\*: Highest derivative appearing in the equation*
- **차수**: 최고계 도함수의 거듭제곱

*EN: - \*\*Degree\*\*: Power of highest-order derivative*
- **선형 미분방정식**: 미지 함수와 그 도함수에 선형인 방정식

*EN: - \*\*Linear DE\*\*: Equation linear in the unknown function and its derivatives*
- **비선형 미분방정식**: 미지 함수에 선형이 아닌 방정식

*EN: - \*\*Nonlinear DE\*\*: Equation not linear in the unknown function*
- **초기값 문제 (IVP)**: 초기 조건이 주어진 미분방정식

*EN: - \*\*Initial Value Problem (IVP)\*\*: DE with specified initial conditions*
- **경계값 문제 (BVP)**: 여러 점에서 조건이 주어진 미분방정식

*EN: - \*\*Boundary Value Problem (BVP)\*\*: DE with conditions at multiple points*
- **분리가능 방정식**: 함수의 곱으로 쓸 수 있는 ODE

*EN: - \*\*Separable Equation\*\*: ODE that can be written as product of functions*
- **동차 방정식**: 우변이 0인 방정식

*EN: - \*\*Homogeneous Equation\*\*: Equation equal to zero*
- **특수해**: 초기/경계 조건을 만족하는 특정 해

*EN: - \*\*Particular Solution\*\*: Specific solution satisfying initial/boundary conditions*
- **일반해**: 모든 해의 집합

*EN: - \*\*General Solution\*\*: Family of all solutions*
- **특성 방정식**: 미분방정식에서 유도된 대수 방정식

*EN: - \*\*Characteristic Equation\*\*: Algebraic equation derived from DE*
- **라플라스 변환**: 미분방정식을 풀기 위한 적분 변환

*EN: - \*\*Laplace Transform\*\*: Integral transform used to solve DEs*
- **푸리에 급수**: 함수를 사인과 코사인의 합으로 표현

*EN: - \*\*Fourier Series\*\*: Representation of function as sum of sines and cosines*
- **변수분리법**: 편미분방정식을 푸는 기법

*EN: - \*\*Method of Separation of Variables\*\*: Technique for solving PDEs*
- **열 방정식**: 시간에 따른 열 분포를 나타내는 PDE

*EN: - \*\*Heat Equation\*\*: PDE describing heat distribution over time*
- **파동 방정식**: 파동 전파를 나타내는 PDE

*EN: - \*\*Wave Equation\*\*: PDE describing wave propagation*
- **라플라스 방정식**: 라플라시안이 0인 PDE

*EN: - \*\*Laplace's Equation\*\*: PDE where Laplacian equals zero*

### 확률 & 통계

*EN: ### Probability & Statistics*
- **확률**: 사건이 발생할 가능성의 측도

*EN: - \*\*Probability\*\*: Measure of likelihood of an event occurring*
- **확률변수**: 값이 임의의 현상에 의존하는 변수

*EN: - \*\*Random Variable\*\*: Variable whose value depends on random phenomena*
- **이산형 확률변수**: 셀 수 있는 값을 취하는 변수

*EN: - \*\*Discrete Random Variable\*\*: Variable taking countable values*
- **연속형 확률변수**: 구간 내의 값을 취하는 변수

*EN: - \*\*Continuous Random Variable\*\*: Variable taking values in an interval*
- **확률분포**: 결과의 확률을 나타내는 함수

*EN: - \*\*Probability Distribution\*\*: Function describing probabilities of outcomes*
- **확률밀도함수 (PDF)**: 연속분포를 위한 함수

*EN: - \*\*Probability Density Function (PDF)\*\*: Function for continuous distributions*
- **확률질량함수 (PMF)**: 이산분포를 위한 함수

*EN: - \*\*Probability Mass Function (PMF)\*\*: Function for discrete distributions*
- **누적분포함수 (CDF)**: 변수가 특정 값 이하일 확률

*EN: - \*\*Cumulative Distribution Function (CDF)\*\*: Probability that variable ≤ value*
- **기댓값 (평균)**: 확률변수의 평균값

*EN: - \*\*Expected Value (Mean)\*\*: Average value of random variable*
- **분산**: 평균 주위의 퍼짐 정도

*EN: - \*\*Variance\*\*: Measure of spread around the mean*
- **표준편차**: 분산의 제곱근

*EN: - \*\*Standard Deviation\*\*: Square root of variance*
- **정규분포**: 종 모양의 연속 확률분포

*EN: - \*\*Normal Distribution\*\*: Bell-shaped continuous probability distribution*
- **이항분포**: n번의 시행에서 성공 횟수의 분포

*EN: - \*\*Binomial Distribution\*\*: Distribution of number of successes in n trials*
- **포아송 분포**: 일정 구간에서 사건 발생 횟수의 분포

*EN: - \*\*Poisson Distribution\*\*: Distribution of number of events in fixed interval*
- **균등분포**: 모든 결과가 동등하게 가능한 분포

*EN: - \*\*Uniform Distribution\*\*: Distribution where all outcomes equally likely*
- **중심극한정리**: 독립적인 변수들의 합은 정규분포에 수렴

*EN: - \*\*Central Limit Theorem\*\*: Sum of independent variables approaches normal distribution*
- **대수의 법칙**: 표본 평균이 기댓값에 수렴

*EN: - \*\*Law of Large Numbers\*\*: Sample average converges to expected value*
- **독립**: 한 사건의 발생이 다른 사건에 영향을 주지 않는 경우

*EN: - \*\*Independence\*\*: Events where occurrence of one doesn't affect the other*
- **조건부 확률**: 다른 사건이 발생했을 때 특정 사건의 확률

*EN: - \*\*Conditional Probability\*\*: Probability of event given another event occurred*
- **베이즈 정리**: 조건부 확률 간의 관계

*EN: - \*\*Bayes' Theorem\*\*: Relates conditional probabilities*
- **통계적 추론**: 데이터로부터 결론 도출

*EN: - \*\*Statistical Inference\*\*: Drawing conclusions from data*
- **가설 검정**: 모집단 모수에 대한 주장 검정

*EN: - \*\*Hypothesis Testing\*\*: Testing claims about population parameters*
- **신뢰 구간**: 모집단 모수를 포함할 가능성이 높은 범위

*EN: - \*\*Confidence Interval\*\*: Range likely to contain population parameter*
- **회귀분석**: 변수들 사이의 관계 모델링

*EN: - \*\*Regression\*\*: Modeling relationship between variables*
- **상관**: 변수 간 선형 관계의 측도

*EN: - \*\*Correlation\*\*: Measure of linear relationship between variables*
- **p-값**: 귀무가설이 참일 때 관측 데이터를 얻을 확률

*EN: - \*\*p-value\*\*: Probability of observing data assuming null hypothesis is true*

### 이산 수학

*EN: ### Discrete Mathematics*
- **논리**: 추론과 논증에 대한 연구

*EN: - \*\*Logic\*\*: Study of reasoning and argumentation*
- **명제**: 참이거나 거짓인 진술

*EN: - \*\*Proposition\*\*: Statement that is either true or false*
- **진리표**: 논리 표현의 진리값을 나타내는 표

*EN: - \*\*Truth Table\*\*: Table showing truth values for logical expressions*
- **논리 연산자**: AND, OR, NOT, IMPLIES, IFF

*EN: - \*\*Logical Operators\*\*: AND, OR, NOT, IMPLIES, IFF*
- **증명**: 명제의 참을 확립하는 논리적 논거

*EN: - \*\*Proof\*\*: Logical argument establishing truth of statement*
- **직접 증명**: 가정으로부터 논리적 단계를 거쳐 명제 증명

*EN: - \*\*Direct Proof\*\*: Proving statement by logical steps from assumptions*
- **귀류법**: 부정이 모순을 야기한다고 가정

*EN: - \*\*Proof by Contradiction\*\*: Assuming negation leads to contradiction*
- **수학적 귀납법**: 자연수에 관한 명제를 증명하는 기법

*EN: - \*\*Mathematical Induction\*\*: Proof technique for statements about natural numbers*
- **집합**: 별개의 대상들의 모임

*EN: - \*\*Set\*\*: Collection of distinct objects*
- **부분집합**: 모든 원소가 다른 집합에 속하는 집합

*EN: - \*\*Subset\*\*: Set where all elements are in another set*
- **합집합**: 여러 집합의 모든 원소를 담은 집합

*EN: - \*\*Union\*\*: Set containing all elements from multiple sets*
- **교집합**: 공통 원소만 담은 집합

*EN: - \*\*Intersection\*\*: Set containing only common elements*
- **여집합**: 집합에 속하지 않는 원소들

*EN: - \*\*Complement\*\*: Elements not in a set*
- **카테시안 곱**: 두 집합의 모든 순서쌍의 집합

*EN: - \*\*Cartesian Product\*\*: Set of all ordered pairs from two sets*
- **조합론**: 세기와 배열에 대한 연구

*EN: - \*\*Combinatorics\*\*: Study of counting and arrangement*
- **순열**: 대상의 순서 있는 배열

*EN: - \*\*Permutation\*\*: Ordered arrangement of objects*
- **조합**: 순서가 상관없는 대상의 선택

*EN: - \*\*Combination\*\*: Selection of objects where order doesn't matter*
- **이항 계수**: n개에서 k개를 선택하는 방법의 수

*EN: - \*\*Binomial Coefficient\*\*: Number of ways to choose k items from n*
- **그래프**: 간선으로 연결된 꼭짓점의 구조

*EN: - \*\*Graph\*\*: Structure of vertices connected by edges*
- **꼭짓점**: 그래프의 노드

*EN: - \*\*Vertex\*\*: Node in a graph*
- **간선**: 꼭짓점 사이의 연결

*EN: - \*\*Edge\*\*: Connection between vertices*
- **경로**: 꼭짓점을 연결하는 간선의 수열

*EN: - \*\*Path\*\*: Sequence of edges connecting vertices*
- **사이클**: 같은 꼭짓점에서 시작하고 끝나는 경로

*EN: - \*\*Cycle\*\*: Path that starts and ends at same vertex*
- **트리**: 사이클이 없는 연결 그래프

*EN: - \*\*Tree\*\*: Connected graph with no cycles*
- **알고리즘**: 문제를 단계적으로 해결하는 절차

*EN: - \*\*Algorithm\*\*: Step-by-step procedure for solving a problem*
- **복잡도**: 알고리즘이 필요로 하는 자원의 측도 (시간 또는 공간)

*EN: - \*\*Complexity\*\*: Measure of resources required by algorithm (time or space)*
- **빅오 표기법**: 알고리즘 성장률의 점근적 상한

*EN: - \*\*Big O Notation\*\*: Asymptotic upper bound on algorithm's growth rate*
- **재귀**: 자기 자신을 이용하여 정의되는 과정

*EN: - \*\*Recursion\*\*: Process defined in terms of itself*

### 논리 & 기초

*EN: ### Logic & Foundations*
- **집합론**: 집합과 그 성질에 대한 연구

*EN: - \*\*Set Theory\*\*: Study of sets and their properties*
- **공리**: 증명 없이 참으로 받아들여지는 진술

*EN: - \*\*Axiom\*\*: Statement accepted as true without proof*
- **정리**: 참으로 증명된 진술

*EN: - \*\*Theorem\*\*: Statement that has been proven true*
- **보조정리**: 더 큰 결과를 증명하기 위한 예비 정리

*EN: - \*\*Lemma\*\*: Preliminary theorem used to prove larger result*
- **따름정리**: 정리로부터 쉽게 도출되는 결과

*EN: - \*\*Corollary\*\*: Result that follows easily from a theorem*
- **기수**: 집합의 크기 또는 원소의 수

*EN: - \*\*Cardinality\*\*: Size or number of elements in a set*
- **가산**: 자연수와 일대일 대응이 가능한 집합

*EN: - \*\*Countable\*\*: Set that can be put in one-to-one correspondence with natural numbers*
- **불가산**: 셀 수 없는 집합 (예: 실수)

*EN: - \*\*Uncountable\*\*: Set that cannot be counted (e.g., real numbers)*
- **함수**: 각 입력에 정확히 하나의 출력을 할당하는 관계

*EN: - \*\*Function\*\*: Relation assigning each input exactly one output*
- **전단사 함수**: 일대일이며 전사인 함수

*EN: - \*\*Bijection\*\*: One-to-one and onto function*
- **단사 함수 (일대일)**: 서로 다른 입력이 서로 다른 출력을 가지는 함수

*EN: - \*\*Injection (One-to-One)\*\*: Function where different inputs have different outputs*
- **전사 함수 (전사)**: 모든 출력에 대응되는 함수

*EN: - \*\*Surjection (Onto)\*\*: Function where every output is mapped to*
- **정수론**: 정수의 성질에 대한 연구

*EN: - \*\*Number Theory\*\*: Study of properties of integers*
- **소수**: 1보다 큰 정수로 1과 자신만으로 나누어지는 수

*EN: - \*\*Prime Number\*\*: Integer greater than 1 divisible only by 1 and itself*
- **합성수**: 1보다 크고 소수가 아닌 정수

*EN: - \*\*Composite Number\*\*: Integer greater than 1 that is not prime*
- **최대공약수 (GCD)**: 두 수를 나누는 가장 큰 정수

*EN: - \*\*Greatest Common Divisor (GCD)\*\*: Largest integer dividing two numbers*
- **최소공배수 (LCM)**: 두 수로 나누어지는 가장 작은 정수

*EN: - \*\*Least Common Multiple (LCM)\*\*: Smallest integer divisible by two numbers*
- **모듈러 산술**: 나머지를 이용한 연산

*EN: - \*\*Modular Arithmetic\*\*: Arithmetic with remainders*
- **합동**: a ≡ b (mod n)은 n이 (a - b)를 나눔을 의미

*EN: - \*\*Congruence\*\*: a ≡ b (mod n) means n divides (a - b)*
- **유클리드 호제법**: GCD를 구하는 방법

*EN: - \*\*Euclidean Algorithm\*\*: Method for computing GCD*
- **수학적 귀납법**: 자연수 명제에 대한 증명 기법

*EN: - \*\*Mathematical Induction\*\*: Proof technique for natural number statements*
- **정렬 원리**: 자연수의 공집합이 아닌 모든 집합은 최솟값을 가짐

*EN: - \*\*Well-Ordering Principle\*\*: Every non-empty set of natural numbers has a least element*
- **형식 체계**: 정리를 유도하기 위한 공리와 규칙의 집합

*EN: - \*\*Formal System\*\*: Set of axioms and rules for deriving theorems*
- **공리적 체계**: 공리에 기반한 수학적 이론

*EN: - \*\*Axiomatic System\*\*: Mathematical theory based on axioms*

## 수학적 구조

*EN: ## Mathematical Structures*

### 대수적 구조

*EN: ### Algebraic Structures*
- **군**: 결합적 이항 연산, 항등원, 역원을 갖는 집합

*EN: - \*\*Group\*\*: Set with associative binary operation, identity, and inverses*
- **환**: 두 연산 (덧셈과 곱셈)을 갖는 집합

*EN: - \*\*Ring\*\*: Set with two operations (addition and multiplication)*
- **체**: 곱셈이 가환이며 역원을 갖는 환

*EN: - \*\*Field\*\*: Ring where multiplication is commutative with inverses*

### 위상적 구조

*EN: ### Topological Structures*
- **위상수학**: 연속 변환 하에서 보존되는 성질에 대한 연구

*EN: - \*\*Topology\*\*: Study of properties preserved under continuous deformations*
- **열린집합**: 모든 점이 집합 내에 포함된 근방을 갖는 집합

*EN: - \*\*Open Set\*\*: Set where every point has a neighborhood contained in the set*
- **닫힌집합**: 모든 극한점을 포함하는 집합

*EN: - \*\*Closed Set\*\*: Set containing all its limit points*
- **컴팩트 집합**: 모든 열린 덮개가 유한 부분 덮개를 갖는 집합

*EN: - \*\*Compact Set\*\*: Set where every open cover has a finite subcover*
- **연결 집합**: 서로소인 열린집합으로 분리할 수 없는 집합

*EN: - \*\*Connected Set\*\*: Set that cannot be divided into disjoint open sets*

## 선형대수

*EN: ## Linear Algebra*

### 벡터

*EN: ### Vectors*
- **벡터**: 수의 순서 있는 목록; 크기와 방향

*EN: - \*\*Vector\*\*: Ordered list of numbers; magnitude and direction*
- **열벡터**: n×1 행렬

*EN: - \*\*Column Vector\*\*: n×1 matrix*
- **행벡터**: 1×n 행렬

*EN: - \*\*Row Vector\*\*: 1×n matrix*
- **영벡터**: 모든 성분이 0

*EN: - \*\*Zero Vector\*\*: All components zero*
- **단위벡터**: 크기 = 1; 보통 î, ĵ, k̂

*EN: - \*\*Unit Vector\*\*: Magnitude = 1; often î, ĵ, k̂*
- **위치벡터**: 원점에서 점까지

*EN: - \*\*Position Vector\*\*: From origin to point*
- **벡터 덧셈**: 성분별 연산; 평행사변형 법칙

*EN: - \*\*Vector Addition\*\*: Component-wise; parallelogram law*
- **스칼라 곱셈**: 크기를 조정

*EN: - \*\*Scalar Multiplication\*\*: Scales magnitude*
- **선형 결합**: c₁v₁ + c₂v₂ + ... + cₙvₙ

*EN: - \*\*Linear Combination\*\*: c₁v₁ + c₂v₂ + ... + cₙvₙ*

### 벡터 연산

*EN: ### Vector Operations*
- **점곱**: u·v = u₁v₁ + u₂v₂ + ... + uₙvₙ = |u||v|cos θ

*EN: - \*\*Dot Product\*\*: u·v = u₁v₁ + u₂v₂ + ... + uₙvₙ = |u||v|cos θ*
- **외적**: u×v; 두 벡터에 수직; |u×v| = |u||v|sin θ; 오른손 법칙

*EN: - \*\*Cross Product\*\*: u×v; perpendicular to both; |u×v| = |u||v|sin θ; right-hand rule*
- **노름/크기**: ||v|| = √(v·v) = √(v₁² + v₂² + ... + vₙ²)

*EN: - \*\*Norm/Magnitude\*\*: ||v|| = √(v·v) = √(v₁² + v₂² + ... + vₙ²)*
- **거리**: d(u,v) = ||u - v||

*EN: - \*\*Distance\*\*: d(u,v) = ||u - v||*
- **각도**: cos θ = (u·v)/(||u|| ||v||)

*EN: - \*\*Angle\*\*: cos θ = (u·v)/(||u|| ||v||)*
- **직교**: u·v = 0; 수직

*EN: - \*\*Orthogonal\*\*: u·v = 0; perpendicular*
- **정사영**: proj_u v = [(v·u)/(u·u)]u

*EN: - \*\*Projection\*\*: proj_u v = [(v·u)/(u·u)]u*

### 행렬

*EN: ### Matrices*
- **행렬**: 수의 직사각형 배열; m×n (행 × 열)

*EN: - \*\*Matrix\*\*: Rectangular array of numbers; m×n (rows × columns)*
- **정사각 행렬**: m = n

*EN: - \*\*Square Matrix\*\*: m = n*
- **단위 행렬 (I)**: 대각선이 1이고 나머지는 0; AI = IA = A

*EN: - \*\*Identity Matrix (I)\*\*: Diagonal 1s, rest 0s; AI = IA = A*
- **대각 행렬**: 주대각선에만 0이 아닌 값

*EN: - \*\*Diagonal Matrix\*\*: Non-zero only on main diagonal*
- **영행렬**: 모든 원소가 0

*EN: - \*\*Zero Matrix\*\*: All entries 0*
- **전치 (Aᵀ)**: 행이 열이 됨; (Aᵀ)ᵀ = A

*EN: - \*\*Transpose (Aᵀ)\*\*: Rows become columns; (Aᵀ)ᵀ = A*
- **대칭 행렬**: A = Aᵀ

*EN: - \*\*Symmetric\*\*: A = Aᵀ*
- **반대칭 행렬**: A = -Aᵀ

*EN: - \*\*Skew-Symmetric\*\*: A = -Aᵀ*
- **상삼각 행렬**: 대각선 아래가 0

*EN: - \*\*Upper Triangular\*\*: Zeros below diagonal*
- **하삼각 행렬**: 대각선 위가 0

*EN: - \*\*Lower Triangular\*\*: Zeros above diagonal*

### 행렬 연산

*EN: ### Matrix Operations*
- **덧셈**: A + B; 같은 차원; 원소별 연산

*EN: - \*\*Addition\*\*: A + B; same dimensions; component-wise*
- **스칼라 곱셈**: cA; 각 원소에 곱셈

*EN: - \*\*Scalar Multiplication\*\*: cA; multiply each entry*
- **행렬 곱셈**: (AB)ᵢⱼ = Σₖ aᵢₖbₖⱼ; (m×n)(n×p) = m×p

*EN: - \*\*Matrix Multiplication\*\*: (AB)ᵢⱼ = Σₖ aᵢₖbₖⱼ; (m×n)(n×p) = m×p*
- **비가환적**: 일반적으로 AB ≠ BA

*EN: - \*\*Not Commutative\*\*: AB ≠ BA in general*
- **결합 법칙**: (AB)C = A(BC)

*EN: - \*\*Associative\*\*: (AB)C = A(BC)*
- **분배 법칙**: A(B+C) = AB + AC

*EN: - \*\*Distributive\*\*: A(B+C) = AB + AC*
- **전치 성질**: (AB)ᵀ = BᵀAᵀ

*EN: - \*\*Transpose Properties\*\*: (AB)ᵀ = BᵀAᵀ*

### 행렬식

*EN: ### Determinants*
- **행렬식 (det A 또는 |A|)**: 정사각 행렬에서 계산되는 스칼라

*EN: - \*\*Determinant (det A or |A|)\*\*: Scalar from square matrix*
- **2×2**: |[a,b],[c,d]| = ad - bc

*EN: - \*\*2×2\*\*: |[a,b],[c,d]| = ad - bc*
- **3×3**: 행/열에 따른 여인수 전개

*EN: - \*\*3×3\*\*: Cofactor expansion along row/column*
- **성질**:

*EN: - \*\*Properties\*\*:*
  - det(AB) = det(A)det(B)

*EN:   - det(AB) = det(A)det(B)*
  - det(Aᵀ) = det(A)

*EN:   - det(Aᵀ) = det(A)*
  - det(A⁻¹) = 1/det(A)

*EN:   - det(A⁻¹) = 1/det(A)*
  - n×n 행렬에 대해 det(cA) = cⁿdet(A)

*EN:   - det(cA) = cⁿdet(A) for n×n matrix*
- **행 연산**: 행 교환은 부호 변경; 행 스케일링은 행렬식에 곱; 행 덧셈은 행렬식 불변

*EN: - \*\*Row Operations\*\*: Row swap changes sign; row scaling multiplies det; row addition doesn't change det*
- **특이 행렬**: det(A) = 0; 역행렬 없음

*EN: - \*\*Singular Matrix\*\*: det(A) = 0; not invertible*
- **크래머 공식**: 행렬식을 이용한 Ax = b 풀기

*EN: - \*\*Cramer's Rule\*\*: Solve Ax = b using determinants*

### 역행렬

*EN: ### Matrix Inverse*
- **역행렬 (A⁻¹)**: AA⁻¹ = A⁻¹A = I

*EN: - \*\*Inverse (A⁻¹)\*\*: AA⁻¹ = A⁻¹A = I*
- **존재 조건**: det(A) ≠ 0 (비특이 행렬)

*EN: - \*\*Exists if\*\*: det(A) ≠ 0 (nonsingular)*
- **2×2 역행렬**: A = [a,b],[c,d]일 때 A⁻¹ = (1/det(A))[d,-b],[-c,a]

*EN: - \*\*2×2 Inverse\*\*: A⁻¹ = (1/det(A))[d,-b],[-c,a] for A=[a,b],[c,d]*
- **성질**:

*EN: - \*\*Properties\*\*:*
  - (A⁻¹)⁻¹ = A

*EN:   - (A⁻¹)⁻¹ = A*
  - (AB)⁻¹ = B⁻¹A⁻¹

*EN:   - (AB)⁻¹ = B⁻¹A⁻¹*
  - (Aᵀ)⁻¹ = (A⁻¹)ᵀ

*EN:   - (Aᵀ)⁻¹ = (A⁻¹)ᵀ*

### 연립 선형방정식

*EN: ### Systems of Linear Equations*
- **행렬 형태**: Ax = b

*EN: - \*\*Matrix Form\*\*: Ax = b*
- **첨가 행렬**: [A|b]

*EN: - \*\*Augmented Matrix\*\*: [A|b]*
- **행 사다리꼴 (REF)**: 선행 원소가 오른쪽으로 내려감; 영행은 아래에

*EN: - \*\*Row Echelon Form (REF)\*\*: Leading entries descend rightward; zero rows at bottom*
- **기약 행 사다리꼴 (RREF)**: REF + 선행 1 + 선행 1 위아래 0

*EN: - \*\*Reduced Row Echelon Form (RREF)\*\*: REF + leading 1s + zeros above/below leading 1s*
- **가우스 소거법**: REF로 변환하는 행 연산

*EN: - \*\*Gaussian Elimination\*\*: Row operations to REF*
- **가우스-조던 소거법**: RREF로 변환하는 행 연산

*EN: - \*\*Gauss-Jordan Elimination\*\*: Row operations to RREF*
- **해의 종류**: 유일해 (하나), 무한히 많은 해 (자유변수 존재), 해 없음 (불일치)

*EN: - \*\*Solution Types\*\*: Unique (one), infinite (free variables), no solution (inconsistent)*
- **계수**: REF의 영이 아닌 행의 수; 열/행 공간의 차원

*EN: - \*\*Rank\*\*: Number of non-zero rows in REF; dimension of column/row space*
- **영차원**: 영공간의 차원; n - 계수

*EN: - \*\*Nullity\*\*: Dimension of null space; n - rank*

### 벡터 공간

*EN: ### Vector Spaces*
- **벡터 공간 (V)**: 공리를 만족하는 덧셈과 스칼라 곱이 있는 집합

*EN: - \*\*Vector Space (V)\*\*: Set with addition and scalar multiplication satisfying axioms*
- **부분공간**: 그 자체가 벡터 공간인 부분집합; 연산에 닫혀 있음; 영벡터 포함

*EN: - \*\*Subspace\*\*: Subset that is itself a vector space; closed under operations; contains zero vector*
- **생성**: 모든 선형 결합의 집합; span{v₁,...,vₙ}

*EN: - \*\*Span\*\*: Set of all linear combinations; span{v₁,...,vₙ}*
- **선형 독립**: 어떤 벡터도 나머지의 선형 결합이 아님; c₁v₁+...+cₙvₙ=0이면 모든 c=0

*EN: - \*\*Linear Independence\*\*: No vector is a linear combination of others; c₁v₁+...+cₙvₙ=0 implies all c=0*
- **선형 종속**: 적어도 하나의 벡터가 나머지의 선형 결합

*EN: - \*\*Linear Dependence\*\*: At least one vector is a combination of others*
- **기저**: 선형 독립인 생성 집합

*EN: - \*\*Basis\*\*: Linearly independent spanning set*
- **차원**: 기저의 벡터 수

*EN: - \*\*Dimension\*\*: Number of vectors in basis*
- **표준 기저**: e₁=(1,0,...,0), e₂=(0,1,0,...) 등

*EN: - \*\*Standard Basis\*\*: e₁=(1,0,...,0), e₂=(0,1,0,...), etc.*

### 고유값과 고유벡터

*EN: ### Eigenvalues and Eigenvectors*
- **고유벡터 (v)**: 스칼라 λ에 대해 Av = λv를 만족하는 영이 아닌 v

*EN: - \*\*Eigenvector (v)\*\*: Av = λv for scalar λ; non-zero v*
- **고유값 (λ)**: Av = λv에서의 스칼라

*EN: - \*\*Eigenvalue (λ)\*\*: Scalar in Av = λv*
- **특성 방정식**: det(A - λI) = 0

*EN: - \*\*Characteristic Equation\*\*: det(A - λI) = 0*
- **특성 다항식**: det(A - λI)

*EN: - \*\*Characteristic Polynomial\*\*: det(A - λI)*
- **대수적 중복도**: 근으로서의 λ의 중복도

*EN: - \*\*Algebraic Multiplicity\*\*: Multiplicity of λ as root*
- **기하학적 중복도**: 고유공간의 차원

*EN: - \*\*Geometric Multiplicity\*\*: Dimension of eigenspace*
- **고유공간**: (A - λI)의 영공간; λ에 대한 모든 고유벡터와 영벡터

*EN: - \*\*Eigenspace\*\*: Null space of (A - λI); all eigenvectors for λ plus zero vector*
- **대각합**: tr(A) = 대각 원소의 합 = 고유값의 합

*EN: - \*\*Trace\*\*: tr(A) = sum of diagonal entries = sum of eigenvalues*
- **행렬식**: det(A) = 고유값의 곱

*EN: - \*\*Determinant\*\*: det(A) = product of eigenvalues*

### 대각화

*EN: ### Diagonalization*
- **대각화 가능**: A = PDP⁻¹, D는 대각, P의 열이 고유벡터

*EN: - \*\*Diagonalizable\*\*: A = PDP⁻¹ where D diagonal, P has eigenvectors as columns*
- **조건**: n×n 행렬에 대해 선형 독립인 고유벡터 n개

*EN: - \*\*Conditions\*\*: n linearly independent eigenvectors for n×n matrix*
- **거듭제곱**: Aⁿ = PDⁿP⁻¹; 계산이 쉬움

*EN: - \*\*Powers\*\*: Aⁿ = PDⁿP⁻¹; easy to compute*
- **스펙트럼 정리**: 실대칭 행렬은 직교 대각화 가능

*EN: - \*\*Spectral Theorem\*\*: Real symmetric matrix is orthogonally diagonalizable*

### 선형변환

*EN: ### Linear Transformations*
- **선형변환 (T)**: T(u+v) = T(u)+T(v); T(cu) = cT(u)

*EN: - \*\*Linear Transformation (T)\*\*: T(u+v) = T(u)+T(v); T(cu) = cT(u)*
- **행렬 표현**: T(x) = Ax

*EN: - \*\*Matrix Representation\*\*: T(x) = Ax*
- **핵 (영공간)**: {x : T(x) = 0}

*EN: - \*\*Kernel (Null Space)\*\*: {x : T(x) = 0}*
- **치역 (열공간)**: {T(x) : x ∈ V}

*EN: - \*\*Range (Column Space)\*\*: {T(x) : x ∈ V}*
- **계수-영차원 정리**: dim(V) = rank(T) + nullity(T)

*EN: - \*\*Rank-Nullity Theorem\*\*: dim(V) = rank(T) + nullity(T)*
- **단사 (일대일)**: T(x) = T(y)이면 x = y; 핵 = {0}

*EN: - \*\*One-to-One (Injective)\*\*: T(x) = T(y) implies x = y; kernel = {0}*
- **전사**: 치역 = 공역

*EN: - \*\*Onto (Surjective)\*\*: Range = codomain*
- **동형사상**: 전단사 선형변환

*EN: - \*\*Isomorphism\*\*: Bijective linear transformation*

### 내적 공간

*EN: ### Inner Product Spaces*
- **내적**: 점곱의 일반화; ⟨u,v⟩

*EN: - \*\*Inner Product\*\*: Generalization of dot product; ⟨u,v⟩*
- **성질**: ⟨u,v⟩ = ⟨v,u⟩; ⟨cu,v⟩ = c⟨u,v⟩; ⟨u+v,w⟩ = ⟨u,w⟩+⟨v,w⟩; ⟨u,u⟩ ≥ 0

*EN: - \*\*Properties\*\*: ⟨u,v⟩ = ⟨v,u⟩; ⟨cu,v⟩ = c⟨u,v⟩; ⟨u+v,w⟩ = ⟨u,w⟩+⟨v,w⟩; ⟨u,u⟩ ≥ 0*
- **내적으로부터의 노름**: ||v|| = √⟨v,v⟩

*EN: - \*\*Norm from Inner Product\*\*: ||v|| = √⟨v,v⟩*
- **코시-슈바르츠 부등식**: |⟨u,v⟩| ≤ ||u|| ||v||

*EN: - \*\*Cauchy-Schwarz Inequality\*\*: |⟨u,v⟩| ≤ ||u|| ||v||*
- **삼각 부등식**: ||u+v|| ≤ ||u|| + ||v||

*EN: - \*\*Triangle Inequality\*\*: ||u+v|| ≤ ||u|| + ||v||*
- **직교**: ⟨u,v⟩ = 0

*EN: - \*\*Orthogonal\*\*: ⟨u,v⟩ = 0*
- **정규직교**: 직교이며 각 노름이 1

*EN: - \*\*Orthonormal\*\*: Orthogonal and each has norm 1*
- **그람-슈미트 과정**: 기저를 정규직교 기저로 변환

*EN: - \*\*Gram-Schmidt Process\*\*: Convert basis to orthonormal basis*

### 특수 행렬

*EN: ### Special Matrices*
- **직교 행렬 (Q)**: QᵀQ = QQᵀ = I; 열/행이 정규직교; 길이와 각도 보존

*EN: - \*\*Orthogonal Matrix (Q)\*\*: QᵀQ = QQᵀ = I; columns/rows are orthonormal; preserves lengths/angles*
- **에르미트 행렬**: A = A* (켤레전치); 실수 고유값

*EN: - \*\*Hermitian Matrix\*\*: A = A\* (conjugate transpose); real eigenvalues*
- **유니터리 행렬 (U)**: U*U = I; 직교 행렬의 복소수 유사체

*EN: - \*\*Unitary Matrix (U)\*\*: U\*U = I; complex analog of orthogonal*
- **양의 정부호**: 모든 x ≠ 0에 대해 xᵀAx > 0; 모든 고유값이 양수

*EN: - \*\*Positive Definite\*\*: xᵀAx > 0 for all x ≠ 0; all eigenvalues positive*
- **사영 행렬**: P² = P; 부분공간으로 정사영

*EN: - \*\*Projection Matrix\*\*: P² = P; projects onto subspace*
- **회전 행렬**: 직교; det = 1; 벡터를 회전

*EN: - \*\*Rotation Matrix\*\*: Orthogonal; det = 1; rotates vectors*


## 미분방정식

*EN: ## Differential Equations*

### 상미분방정식 (ODE)

*EN: ### Ordinary Differential Equations (ODEs)*
- **ODE**: 한 변수의 미지함수의 도함수를 포함하는 방정식

*EN: - \*\*ODE\*\*: Equation with derivatives of unknown function of one variable*
- **차수**: 등장하는 도함수 중 최고 차수

*EN: - \*\*Order\*\*: Highest derivative present*
- **급수**: 최고 도함수의 거듭제곱 (다항식인 경우)

*EN: - \*\*Degree\*\*: Power of highest derivative (when polynomial)*
- **선형 ODE**: y와 그 도함수에 대해 선형; y 또는 y'의 곱/거듭제곱 없음

*EN: - \*\*Linear ODE\*\*: Linear in y and its derivatives; no products/powers of y or y'*
- **비선형**: y², (y')², yy', sin(y) 등을 포함

*EN: - \*\*Nonlinear\*\*: Contains y², (y')², yy', sin(y), etc.*
- **일반 해**: 임의 상수를 포함 (n階의 경우 n개의 상수)

*EN: - \*\*General Solution\*\*: Contains arbitrary constants (n constants for nth order)*
- **특수 해**: 초기 조건을 만족하는 특정 해

*EN: - \*\*Particular Solution\*\*: Specific solution satisfying initial conditions*
- **초기값 문제 (IVP)**: ODE + 초기 조건

*EN: - \*\*Initial Value Problem (IVP)\*\*: ODE + initial conditions*
- **경계값 문제 (BVP)**: ODE + 서로 다른 점에서의 조건

*EN: - \*\*Boundary Value Problem (BVP)\*\*: ODE + conditions at different points*

### 일계 ODE

*EN: ### First-Order ODEs*
- **분리가능**: dy/dx = g(x)h(y); 분리 후 적분

*EN: - \*\*Separable\*\*: dy/dx = g(x)h(y); separate and integrate*
- **일계 선형**: dy/dx + P(x)y = Q(x)

*EN: - \*\*Linear First-Order\*\*: dy/dx + P(x)y = Q(x)*
  - **적분인수**: μ(x) = e^{∫P(x)dx}

*EN:   - \*\*Integrating Factor\*\*: μ(x) = e^{∫P(x)dx}*
  - **해**: y = (1/μ)∫μQ dx

*EN:   - \*\*Solution\*\*: y = (1/μ)∫μQ dx*
- **완전 방정식**: M(x,y)dx + N(x,y)dy = 0 이고 ∂M/∂y = ∂N/∂x

*EN: - \*\*Exact Equation\*\*: M(x,y)dx + N(x,y)dy = 0 where ∂M/∂y = ∂N/∂x*
  - **해**: ∫M dx + ∫(N에서 x를 포함하지 않는 항) dy = C

*EN:   - \*\*Solution\*\*: ∫M dx + ∫(terms of N not containing x) dy = C*
- **동차 방정식**: dy/dx = F(y/x); v = y/x로 치환

*EN: - \*\*Homogeneous\*\*: dy/dx = F(y/x); substitute v = y/x*
- **베르누이 방정식**: dy/dx + P(x)y = Q(x)y^n; v = y^{1-n}으로 치환

*EN: - \*\*Bernoulli\*\*: dy/dx + P(x)y = Q(x)y^n; substitute v = y^{1-n}*

### 이계 선형 ODE

*EN: ### Second-Order Linear ODEs*
- **표준형**: y'' + p(x)y' + q(x)y = r(x)

*EN: - \*\*Standard Form\*\*: y'' + p(x)y' + q(x)y = r(x)*
- **동차**: r(x) = 0

*EN: - \*\*Homogeneous\*\*: r(x) = 0*
- **비동차**: r(x) ≠ 0

*EN: - \*\*Nonhomogeneous\*\*: r(x) ≠ 0*
- **일반 해**: y = y_h + y_p (동차해 + 특수해)

*EN: - \*\*General Solution\*\*: y = y_h + y_p (homogeneous + particular)*
- **중첩**: y₁, y₂가 동차 방정식의 해이면 c₁y₁ + c₂y₂도 해

*EN: - \*\*Superposition\*\*: If y₁, y₂ solve homogeneous, so does c₁y₁ + c₂y₂*

### 상수계수 ODE

*EN: ### Constant Coefficient ODEs*
- **특성 방정식**: ay'' + by' + cy = 0에 대한 ar² + br + c = 0

*EN: - \*\*Characteristic Equation\*\*: ar² + br + c = 0 for ay'' + by' + cy = 0*
- **서로 다른 실수 근 (r₁, r₂)**: y_h = c₁e^{r₁x} + c₂e^{r₂x}

*EN: - \*\*Distinct Real Roots (r₁, r₂)\*\*: y_h = c₁e^{r₁x} + c₂e^{r₂x}*
- **중복 근 (r)**: y_h = (c₁ + c₂x)e^{rx}

*EN: - \*\*Repeated Root (r)\*\*: y_h = (c₁ + c₂x)e^{rx}*
- **복소 근 (α ± βi)**: y_h = e^{αx}(c₁cos(βx) + c₂sin(βx))

*EN: - \*\*Complex Roots (α ± βi)\*\*: y_h = e^{αx}(c₁cos(βx) + c₂sin(βx))*

### 미결정 계수법

*EN: ### Method of Undetermined Coefficients*
- **적용 대상**: 상수계수; r(x) = 다항식, 지수함수, 사인, 코사인 또는 이들의 조합

*EN: - \*\*Applies to\*\*: Constant coefficients; r(x) = polynomial, exponential, sine, cosine, or combinations*
- **추측 형태**: r(x)의 유형에 맞춤

*EN: - \*\*Guess Form\*\*: Match type of r(x)*
  - 다항식: 동일한 차수의 다항식

*EN:   - Polynomial: Polynomial same degree*
  - e^{ax}: Ae^{ax}

*EN:   - e^{ax}: Ae^{ax}*
  - sin(bx), cos(bx): Asin(bx) + Bcos(bx)

*EN:   - sin(bx), cos(bx): Asin(bx) + Bcos(bx)*
- **수정 규칙**: 추측이 동차 방정식의 해이면 x를 곱함 (필요시 반복)

*EN: - \*\*Modification Rule\*\*: If guess solves homogeneous, multiply by x (repeat if needed)*

### 매개변수 변분법

*EN: ### Variation of Parameters*
- **적용**: y'' + p(x)y' + q(x)y = r(x)이고 y_h = c₁y₁ + c₂y₂가 알려진 경우

*EN: - \*\*For\*\*: y'' + p(x)y' + q(x)y = r(x) with known y_h = c₁y₁ + c₂y₂*
- **특수 해**: y_p = u₁y₁ + u₂y₂

*EN: - \*\*Particular Solution\*\*: y_p = u₁y₁ + u₂y₂*
- **공식**: u₁' = -y₂r/W, u₂' = y₁r/W where W = Wronskian = y₁y₂' - y₂y₁'

*EN: - \*\*Formulas\*\*: u₁' = -y₂r/W, u₂' = y₁r/W where W = Wronskian = y₁y₂' - y₂y₁'*

### 라플라스 변환

*EN: ### Laplace Transforms*
- **정의**: ℒ{f(t)} = F(s) = ∫₀^∞ e^{-st}f(t)dt

*EN: - \*\*Definition\*\*: ℒ{f(t)} = F(s) = ∫₀^∞ e^{-st}f(t)dt*
- **기본 변환**:

*EN: - \*\*Basic Transforms\*\*:*
  - ℒ{1} = 1/s

*EN:   - ℒ{1} = 1/s*
  - ℒ{e^{at}} = 1/(s-a)

*EN:   - ℒ{e^{at}} = 1/(s-a)*
  - ℒ{t^n} = n!/s^{n+1}

*EN:   - ℒ{t^n} = n!/s^{n+1}*
  - ℒ{sin(at)} = a/(s²+a²)

*EN:   - ℒ{sin(at)} = a/(s²+a²)*
  - ℒ{cos(at)} = s/(s²+a²)

*EN:   - ℒ{cos(at)} = s/(s²+a²)*
- **성질**:

*EN: - \*\*Properties\*\*:*
  - 선형성: ℒ{af+bg} = aℒ{f} + bℒ{g}

*EN:   - Linearity: ℒ{af+bg} = aℒ{f} + bℒ{g}*
  - 일계 도함수: ℒ{f'} = sF(s) - f(0)

*EN:   - First Derivative: ℒ{f'} = sF(s) - f(0)*
  - 이계 도함수: ℒ{f''} = s²F(s) - sf(0) - f'(0)

*EN:   - Second Derivative: ℒ{f''} = s²F(s) - sf(0) - f'(0)*
  - 이동: ℒ{e^{at}f(t)} = F(s-a)

*EN:   - Shifting: ℒ{e^{at}f(t)} = F(s-a)*
- **역변환**: ℒ^{-1}{F(s)} = f(t)

*EN: - \*\*Inverse Transform\*\*: ℒ^{-1}{F(s)} = f(t)*
- **합성곱**: ℒ{f*g} = F(s)G(s), (f*g)(t) = ∫₀^t f(τ)g(t-τ)dτ

*EN: - \*\*Convolution\*\*: ℒ{f\*g} = F(s)G(s) where (f\*g)(t) = ∫₀^t f(τ)g(t-τ)dτ*
- **단위 계단**: u_c(t) = t<c이면 0, t≥c이면 1; ℒ{u_c(t)f(t-c)} = e^{-cs}F(s)

*EN: - \*\*Unit Step\*\*: u_c(t) = 0 for t<c, 1 for t≥c; ℒ{u_c(t)f(t-c)} = e^{-cs}F(s)*

### 거듭제곱급수 해

*EN: ### Power Series Solutions*
- **정규점**: x₀ 근방에서 y를 거듭제곱급수로 전개 가능

*EN: - \*\*Ordinary Point\*\*: Can expand y as power series around x₀*
- **특이점**: 전개 불가; p(x) 또는 q(x) 정의되지 않음

*EN: - \*\*Singular Point\*\*: Cannot expand; p(x) or q(x) undefined*
- **정규 특이점**: x-x₀가 특이성을 유한하게 나눔

*EN: - \*\*Regular Singular Point\*\*: x-x₀ divides singularities finitely*
- **방법**: y = Σ aₙ(x-x₀)^n 가정; 대입; 계수 비교

*EN: - \*\*Method\*\*: Assume y = Σ aₙ(x-x₀)^n; substitute; equate coefficients*
- **수렴반경**: 가장 가까운 특이점까지의 거리

*EN: - \*\*Radius of Convergence\*\*: Distance to nearest singularity*

### ODE 연립

*EN: ### Systems of ODEs*
- **일계 연립**: x' = Ax + f(t), x, f는 벡터, A는 행렬

*EN: - \*\*First-Order System\*\*: x' = Ax + f(t) where x, f vectors, A matrix*
- **동차**: f = 0

*EN: - \*\*Homogeneous\*\*: f = 0*
- **고유값 방법**: x = ve^{λt}; A의 고유값/고유벡터 구하기

*EN: - \*\*Eigenvalue Method\*\*: x = ve^{λt}; find eigenvalues/eigenvectors of A*
- **서로 다른 실수 고유값**: x = c₁v₁e^{λ₁t} + c₂v₂e^{λ₂t}

*EN: - \*\*Real Distinct Eigenvalues\*\*: x = c₁v₁e^{λ₁t} + c₂v₂e^{λ₂t}*
- **복소 고유값 (α±βi)**: e^{(α+βi)t}v의 실수부/허수부

*EN: - \*\*Complex Eigenvalues (α±βi)\*\*: Real/imaginary parts of e^{(α+βi)t}v*
- **중복 고유값**: 일반화된 고유벡터 사용

*EN: - \*\*Repeated Eigenvalues\*\*: Generalized eigenvectors*

### 편미분방정식 (PDE)

*EN: ### Partial Differential Equations (PDEs)*
- **PDE**: 여러 독립변수를 포함; 편미분

*EN: - \*\*PDE\*\*: Multiple independent variables; partial derivatives*
- **차수**: 최고 편미분의 차수

*EN: - \*\*Order\*\*: Highest partial derivative*
- **선형**: u와 모든 편미분에 대해 선형

*EN: - \*\*Linear\*\*: Linear in u and all partial derivatives*
- **동차**: = 0

*EN: - \*\*Homogeneous\*\*: = 0*
- **열방정식**: u_t = α²u_xx; 확산

*EN: - \*\*Heat Equation\*\*: u_t = α²u_xx; diffusion*
- **파동방정식**: u_tt = c²u_xx; 진동

*EN: - \*\*Wave Equation\*\*: u_tt = c²u_xx; vibrations*
- **라플라스 방정식**: u_xx + u_yy = 0; 정상 상태

*EN: - \*\*Laplace's Equation\*\*: u_xx + u_yy = 0; steady-state*
- **변수 분리법**: u(x,t) = X(x)T(t); 대입 후 분리

*EN: - \*\*Separation of Variables\*\*: u(x,t) = X(x)T(t); substitute; separate*
- **푸리에 급수 해**: 계수를 갖는 분리된 해들의 결합

*EN: - \*\*Fourier Series Solution\*\*: Combine separated solutions with coefficients*

### 수치 방법

*EN: ### Numerical Methods*
- **오일러 방법**: yₙ₊₁ = yₙ + hf(xₙ,yₙ); 일차 정확도

*EN: - \*\*Euler's Method\*\*: yₙ₊₁ = yₙ + hf(xₙ,yₙ); first-order accuracy*
- **개선된 오일러 (훈)**: 예측-수정; 이차 정확도

*EN: - \*\*Improved Euler (Heun)\*\*: Predictor-corrector; second-order*
- **룽게-쿠타 (RK4)**: 사차 정확도; 많이 사용; 정확함

*EN: - \*\*Runge-Kutta (RK4)\*\*: Fourth-order; widely used; accurate*
- **간격 크기 (h)**: 작을수록 정확하지만 계산량 증가

*EN: - \*\*Step Size (h)\*\*: Smaller = more accurate but more computation*
- **안정성**: 오차를 증폭시키지 않는 방법

*EN: - \*\*Stability\*\*: Method doesn't amplify errors*

## 확률 & 통계

*EN: ## Probability & Statistics*

### 확률 기초

*EN: ### Probability Basics*
- **표본 공간 (S)**: 모든 가능한 결과의 집합

*EN: - \*\*Sample Space (S)\*\*: Set of all possible outcomes*
- **사건 (E)**: 표본 공간의 부분집합

*EN: - \*\*Event (E)\*\*: Subset of sample space*
- **확률 P(E)**: 0 ≤ P(E) ≤ 1; P(S) = 1; P(∅) = 0

*EN: - \*\*Probability P(E)\*\*: 0 ≤ P(E) ≤ 1; P(S) = 1; P(∅) = 0*
- **여사건**: P(E^c) = 1 - P(E)

*EN: - \*\*Complement\*\*: P(E^c) = 1 - P(E)*
- **덧셈 법칙**: P(A∪B) = P(A) + P(B) - P(A∩B)

*EN: - \*\*Addition Rule\*\*: P(A∪B) = P(A) + P(B) - P(A∩B)*
- **상호 배타**: P(A∩B) = 0; 그러면 P(A∪B) = P(A) + P(B)

*EN: - \*\*Mutually Exclusive\*\*: P(A∩B) = 0; then P(A∪B) = P(A) + P(B)*
- **조건부 확률**: P(A|B) = P(A∩B)/P(B)

*EN: - \*\*Conditional Probability\*\*: P(A|B) = P(A∩B)/P(B)*
- **독립성**: P(A∩B) = P(A)P(B); P(A|B) = P(A)

*EN: - \*\*Independence\*\*: P(A∩B) = P(A)P(B); P(A|B) = P(A)*
- **곱셈 법칙**: P(A∩B) = P(A)P(B|A)

*EN: - \*\*Multiplication Rule\*\*: P(A∩B) = P(A)P(B|A)*

### 베이즈 정리

*EN: ### Bayes' Theorem*
- **공식**: P(A|B) = P(B|A)P(A)/P(B)

*EN: - \*\*Formula\*\*: P(A|B) = P(B|A)P(A)/P(B)*
- **전확률 법칙**: P(B) = ΣP(B|Aᵢ)P(Aᵢ), {Aᵢ}는 분할

*EN: - \*\*Law of Total Probability\*\*: P(B) = ΣP(B|Aᵢ)P(Aᵢ) for partition {Aᵢ}*
- **사후 확률**: 증거가 주어졌을 때 믿음 갱신

*EN: - \*\*Posterior Probability\*\*: Update belief given evidence*

### 경우의 수

*EN: ### Counting*
- **덧셈 원리**: A 또는 B이면 수를 더함

*EN: - \*\*Addition Principle\*\*: If A or B, add counts*
- **곱셈 원리**: A와 B가 순서대로 이면 수를 곱함

*EN: - \*\*Multiplication Principle\*\*: If A and B in sequence, multiply*
- **순열**: 순서 있는 배열; P(n,r) = n!/(n-r)!

*EN: - \*\*Permutation\*\*: Ordered arrangements; P(n,r) = n!/(n-r)!*
- **조합**: 순서 없는 선택; C(n,r) = n!/[r!(n-r)!]

*EN: - \*\*Combination\*\*: Unordered selections; C(n,r) = n!/[r!(n-r)!]*
- **이항계수**: C(n,k) = (n 중에서 k 선택)

*EN: - \*\*Binomial Coefficient\*\*: C(n,k) = (n choose k)*

### 확률변수

*EN: ### Random Variables*
- **확률변수 (RV)**: 표본 공간에서 실수로의 함수

*EN: - \*\*Random Variable (RV)\*\*: Function from sample space to real numbers*
- **이산형 확률변수**: 셀 수 있는 값; 확률 질량 함수 P(X=x)

*EN: - \*\*Discrete RV\*\*: Countable values; PMF P(X=x)*
- **연속형 확률변수**: 셀 수 없는 값; PDF f(x); P(a<X<b) = ∫ₐ^b f(x)dx

*EN: - \*\*Continuous RV\*\*: Uncountable; PDF f(x); P(a<X<b) = ∫ₐ^b f(x)dx*
- **누적 분포 함수 (CDF)**: F(x) = P(X≤x)

*EN: - \*\*Cumulative Distribution Function (CDF)\*\*: F(x) = P(X≤x)*
- **기댓값**: E[X] = Σx·P(X=x) 또는 ∫x f(x)dx

*EN: - \*\*Expected Value\*\*: E[X] = Σx·P(X=x) or ∫x f(x)dx*
- **분산**: Var(X) = E[(X-μ)²] = E[X²] - (E[X])²

*EN: - \*\*Variance\*\*: Var(X) = E[(X-μ)²] = E[X²] - (E[X])²*
- **표준편차**: σ = √Var(X)

*EN: - \*\*Standard Deviation\*\*: σ = √Var(X)*

### 이산형 분포

*EN: ### Discrete Distributions*
- **베르누이**: 1회 시행; p = P(성공)

*EN: - \*\*Bernoulli\*\*: One trial; p = P(success)*
- **이항**: n회 독립 시행; P(X=k) = C(n,k)p^k(1-p)^{n-k}; E[X]=np; Var=np(1-p)

*EN: - \*\*Binomial\*\*: n independent trials; P(X=k) = C(n,k)p^k(1-p)^{n-k}; E[X]=np; Var=np(1-p)*
- **기하**: 첫 번째 성공까지의 시행 수; P(X=k) = (1-p)^{k-1}p; E[X]=1/p

*EN: - \*\*Geometric\*\*: Trials until first success; P(X=k) = (1-p)^{k-1}p; E[X]=1/p*
- **푸아송**: 구간 내 사건; P(X=k) = (λ^k e^{-λ})/k!; E[X]=Var[X]=λ

*EN: - \*\*Poisson\*\*: Events in interval; P(X=k) = (λ^k e^{-λ})/k!; E[X]=Var[X]=λ*
- **초기하**: 비복원 추출

*EN: - \*\*Hypergeometric\*\*: Sampling without replacement*

### 연속형 분포

*EN: ### Continuous Distributions*
- **균등**: f(x) = 1/(b-a), [a,b]; E[X]=(a+b)/2; Var=(b-a)²/12

*EN: - \*\*Uniform\*\*: f(x) = 1/(b-a) on [a,b]; E[X]=(a+b)/2; Var=(b-a)²/12*
- **지수**: f(x) = λe^{-λx}; 무기억성; E[X]=1/λ; Var=1/λ²

*EN: - \*\*Exponential\*\*: f(x) = λe^{-λx}; memoryless; E[X]=1/λ; Var=1/λ²*
- **정규 (가우시안)**: f(x) = (1/σ√(2π))e^{-(x-μ)²/(2σ²)}; E[X]=μ; Var=σ²

*EN: - \*\*Normal (Gaussian)\*\*: f(x) = (1/σ√(2π))e^{-(x-μ)²/(2σ²)}; E[X]=μ; Var=σ²*
  - **표준 정규 (Z)**: μ=0, σ=1; Z = (X-μ)/σ

*EN:   - \*\*Standard Normal (Z)\*\*: μ=0, σ=1; Z = (X-μ)/σ*
  - **68-95-99.7 규칙**: ±1σ, ±2σ, ±3σ

*EN:   - \*\*68-95-99.7 Rule\*\*: ±1σ, ±2σ, ±3σ*
- **카이제곱 (χ²)**: 정규 분포의 제곱합; df = 자유도

*EN: - \*\*Chi-Square (χ²)\*\*: Sum of squared normals; df = degrees of freedom*
- **t분포**: 대칭; 정규보다 꼬리가 두터움; df 증가 시 정규 분포에 근사

*EN: - \*\*t-Distribution\*\*: Symmetric; heavier tails than normal; approaches normal as df increases*
- **F분포**: 카이제곱 비율; 분산분석에 사용

*EN: - \*\*F-Distribution\*\*: Ratio of chi-squares; for ANOVA*

### 중심극한정리 (CLT)

*EN: ### Central Limit Theorem (CLT)*
- **진술**: n → ∞일 때 표본 평균 X̄는 모집단 분포와 상관없이 정규 분포에 근사

*EN: - \*\*Statement\*\*: Sample mean X̄ approaches normal as n → ∞, regardless of population distribution*
- **매개변수**: E[X̄] = μ; Var(X̄) = σ²/n; 표준오차 = σ/√n

*EN: - \*\*Parameters\*\*: E[X̄] = μ; Var(X̄) = σ²/n; SE = σ/√n*
- **경험 법칙**: 일반적으로 n ≥ 30이면 충분

*EN: - \*\*Rule of Thumb\*\*: n ≥ 30 often sufficient*

### 통계적 추론

*EN: ### Statistical Inference*
- **모집단**: 관심 대상인 모든 개체

*EN: - \*\*Population\*\*: All individuals of interest*
- **표본**: 관측된 부분 집합

*EN: - \*\*Sample\*\*: Subset observed*
- **모수**: 모집단 특성 (μ, σ, p)

*EN: - \*\*Parameter\*\*: Population characteristic (μ, σ, p)*
- **통계량**: 표본 특성 (x̄, s, p̂)

*EN: - \*\*Statistic\*\*: Sample characteristic (x̄, s, p̂)*
- **점추정**: 단일값 추정

*EN: - \*\*Point Estimate\*\*: Single value estimate*
- **구간추정**: 신뢰수준을 가진 범위

*EN: - \*\*Interval Estimate\*\*: Range with confidence level*
- **신뢰구간**: x̄ ± z*(σ/√n) 또는 x̄ ± t*(s/√n)

*EN: - \*\*Confidence Interval\*\*: x̄ ± z\*(σ/√n) or x̄ ± t\*(s/√n)*
- **신뢰수준 (1-α)**: 90%, 95%, 99%가 일반적

*EN: - \*\*Confidence Level (1-α)\*\*: 90%, 95%, 99% common*

### 가설 검정

*EN: ### Hypothesis Testing*
- **귀무가설 (H₀)**: 현 상태 유지; 참으로 가정

*EN: - \*\*Null Hypothesis (H₀)\*\*: Status quo; assume true*
- **대립가설 (H₁ 또는 Hₐ)**: 우리가 추정하는 것

*EN: - \*\*Alternative Hypothesis (H₁ or Hₐ)\*\*: What we suspect*
- **검정 통계량**: z, t, χ², F 등

*EN: - \*\*Test Statistic\*\*: z, t, χ², F, etc.*
- **p값**: P(데이터 또는 더 극단적인 결과 | H₀ 참)

*EN: - \*\*p-value\*\*: P(data or more extreme | H₀ true)*
- **유의수준 (α)**: 기준; 0.05가 일반적

*EN: - \*\*Significance Level (α)\*\*: Threshold; 0.05 common*
- **결정**: p < α이면 H₀ 기각

*EN: - \*\*Decision\*\*: Reject H₀ if p < α*
- **1종 오류 (α)**: 참인 H₀ 기각; 위양성

*EN: - \*\*Type I Error (α)\*\*: Reject true H₀; false positive*
- **2종 오류 (β)**: 거짓인 H₀ 기각 실패; 위음성

*EN: - \*\*Type II Error (β)\*\*: Fail to reject false H₀; false negative*
- **검정력 (1-β)**: 거짓인 H₀를 기각할 확률

*EN: - \*\*Power (1-β)\*\*: Probability of rejecting false H₀*
- **단측 vs 양측**: 방향성 vs 비방향성 H₁

*EN: - \*\*One-Tailed vs Two-Tailed\*\*: Directional vs non-directional H₁*

### 주요 검정법

*EN: ### Common Tests*
- **z 검정**: 모집단 σ 알려짐; 대표본

*EN: - \*\*z-Test\*\*: Population σ known; large n*
- **t 검정**: 모집단 σ 미지; 소표본

*EN: - \*\*t-Test\*\*: Population σ unknown; small n*
  - 일표본: 평균과 특정 값 비교

*EN:   - One-Sample: Compare mean to value*
  - 이표본: 두 평균 비교 (대응 또는 독립)

*EN:   - Two-Sample: Compare two means (paired or independent)*
- **χ² 검정**: 적합도 검정; 분할표에서의 독립성 검정

*EN: - \*\*χ² Test\*\*: Goodness-of-fit; independence in contingency table*
- **분산분석 (F 검정)**: 3개 이상 평균 비교

*EN: - \*\*ANOVA (F-test)\*\*: Compare ≥3 means*
- **상관 검정**: ρ ≠ 0인지?

*EN: - \*\*Correlation Test\*\*: Is ρ ≠ 0?*
- **회귀 검정**: β ≠ 0인지?

*EN: - \*\*Regression Test\*\*: Is β ≠ 0?*

### 회귀와 상관

*EN: ### Regression and Correlation*
- **선형 회귀**: y = β₀ + β₁x + ε

*EN: - \*\*Linear Regression\*\*: y = β₀ + β₁x + ε*
- **최소 제곱법**: Σ(yᵢ - ŷᵢ)² 최소화

*EN: - \*\*Least Squares\*\*: Minimize Σ(yᵢ - ŷᵢ)²*
- **기울기**: β₁ = r(s_y/s_x)

*EN: - \*\*Slope\*\*: β₁ = r(s_y/s_x)*
- **절편**: β₀ = ȳ - β₁x̄

*EN: - \*\*Intercept\*\*: β₀ = ȳ - β₁x̄*
- **상관계수 (r)**: -1 ≤ r ≤ 1; 선형 연관도 측정

*EN: - \*\*Correlation Coefficient (r)\*\*: -1 ≤ r ≤ 1; measures linear association*
  - r > 0: 양의 상관; r < 0: 음의 상관; r = 0: 선형 관계 없음

*EN:   - r > 0: Positive; r < 0: Negative; r = 0: No linear relationship*
- **결정계수 (R²)**: r²; 설명된 분산의 비율

*EN: - \*\*Coefficient of Determination (R²)\*\*: r²; proportion of variance explained*
- **잔차**: eᵢ = yᵢ - ŷᵢ; 오차

*EN: - \*\*Residual\*\*: eᵢ = yᵢ - ŷᵢ; error*
- **가정**: 선형성, 독립성, 등분산성, 정규성 (LINE)

*EN: - \*\*Assumptions\*\*: Linearity, independence, homoscedasticity, normality (LINE)*

### 분산 분석 (ANOVA)

*EN: ### ANOVA*
- **일원 분산분석**: 3개 이상 집단의 평균 비교

*EN: - \*\*One-Way ANOVA\*\*: Compare means of ≥3 groups*
- **귀무가설**: μ₁ = μ₂ = ... = μₖ

*EN: - \*\*H₀\*\*: μ₁ = μ₂ = ... = μₖ*
- **F통계량**: F = MS_between / MS_within

*EN: - \*\*F-statistic\*\*: F = MS_between / MS_within*
- **총제곱합 (SST)**: SS_between + SS_within

*EN: - \*\*SST\*\*: Total sum of squares = SS_between + SS_within*
- **자유도**: df_between = k-1; df_within = n-k; df_total = n-1

*EN: - \*\*Degrees of Freedom\*\*: df_between = k-1; df_within = n-k; df_total = n-1*
- **사후 검정**: H₀ 기각 후 어느 평균이 다른지 결정 (Tukey, Bonferroni)

*EN: - \*\*Post-Hoc Tests\*\*: If reject H₀, determine which means differ (Tukey, Bonferroni)*

### 베이즈 통계

*EN: ### Bayesian Statistics*
- **사전 확률**: 데이터 이전 P(θ)

*EN: - \*\*Prior\*\*: P(θ) before data*
- **우도**: P(데이터|θ)

*EN: - \*\*Likelihood\*\*: P(data|θ)*
- **사후 확률**: P(θ|데이터) ∝ P(데이터|θ)P(θ)

*EN: - \*\*Posterior\*\*: P(θ|data) ∝ P(data|θ)P(θ)*
- **신뢰 구간 (베이즈)**: 신뢰구간의 베이즈 유사체

*EN: - \*\*Credible Interval\*\*: Bayesian analog of confidence interval*
- **켤레 사전 확률**: 사후 분포가 사전 분포와 같은 계열

*EN: - \*\*Conjugate Prior\*\*: Posterior same family as prior*

### 머신러닝 기초

*EN: ### Machine Learning Foundations*
- **지도 학습**: 레이블된 데이터; 출력 예측

*EN: - \*\*Supervised Learning\*\*: Labeled data; predict output*
  - 분류: 이산 출력

*EN:   - Classification: Discrete output*
  - 회귀: 연속 출력

*EN:   - Regression: Continuous output*
- **비지도 학습**: 레이블 없음; 패턴 발견

*EN: - \*\*Unsupervised Learning\*\*: Unlabeled; find patterns*
  - 군집화: 유사한 데이터 그룹화

*EN:   - Clustering: Group similar data*
  - 차원 축소: 특성 수 축소

*EN:   - Dimensionality Reduction: Reduce features*
- **훈련/테스트 분리**: 일반화 성능 평가

*EN: - \*\*Training/Test Split\*\*: Evaluate generalization*
- **교차 검증**: 다중 훈련/테스트 분리; 평균 성능

*EN: - \*\*Cross-Validation\*\*: Multiple train/test splits; average performance*
- **과적합**: 모델이 너무 복잡; 노이즈에 맞춤

*EN: - \*\*Overfitting\*\*: Model too complex; fits noise*
- **과소적합**: 모델이 너무 단순; 패턴을 못 잡음

*EN: - \*\*Underfitting\*\*: Model too simple; misses patterns*
- **편향-분산 트레이드오프**: 복잡도의 균형

*EN: - \*\*Bias-Variance Tradeoff\*\*: Balance complexity*

## 이산 수학

*EN: ## Discrete Mathematics*

### 논리

*EN: ### Logic*
- **명제**: 참 또는 거짓인 진술

*EN: - \*\*Proposition\*\*: Statement that is true or false*
- **논리 접속사**: ∧ (그리고), ∨ (또는), ¬ (부정), → (함의), ↔ (동치)

*EN: - \*\*Logical Connectives\*\*: ∧ (and), ∨ (or), ¬ (not), → (implies), ↔ (iff)*
- **진리표**: 모든 경우에 대한 진리값 표시

*EN: - \*\*Truth Table\*\*: Shows truth values for all combinations*
- **항진명제**: 항상 참 (예: P ∨ ¬P)

*EN: - \*\*Tautology\*\*: Always true (e.g., P ∨ ¬P)*
- **모순명제**: 항상 거짓 (예: P ∧ ¬P)

*EN: - \*\*Contradiction\*\*: Always false (e.g., P ∧ ¬P)*
- **논리적 동치**: 동일한 진리표; P ≡ Q

*EN: - \*\*Logical Equivalence\*\*: Same truth table; P ≡ Q*
- **드 모르간 법칙**: ¬(P∧Q) ≡ ¬P∨¬Q; ¬(P∨Q) ≡ ¬P∧¬Q

*EN: - \*\*De Morgan's Laws\*\*: ¬(P∧Q) ≡ ¬P∨¬Q; ¬(P∨Q) ≡ ¬P∧¬Q*
- **대우**: P→Q ≡ ¬Q→¬P

*EN: - \*\*Contrapositive\*\*: P→Q ≡ ¬Q→¬P*
- **역**: P→Q 대 Q→P (동치 아님)

*EN: - \*\*Converse\*\*: P→Q vs Q→P (not equivalent)*
- **한정사**: ∀ (모든), ∃ (어떤)

*EN: - \*\*Quantifiers\*\*: ∀ (for all), ∃ (there exists)*

### 집합 이론

*EN: ### Set Theory*
- **집합**: 구별되는 대상들의 모임

*EN: - \*\*Set\*\*: Collection of distinct objects*
- **원소**: a ∈ A; a는 A에 속함

*EN: - \*\*Element\*\*: a ∈ A; a belongs to A*
- **부분집합**: A ⊆ B; A의 모든 원소가 B에 있음

*EN: - \*\*Subset\*\*: A ⊆ B; all elements of A in B*
- **진부분집합**: A ⊂ B; A ⊆ B이고 A ≠ B

*EN: - \*\*Proper Subset\*\*: A ⊂ B; A ⊆ B and A ≠ B*
- **공집합**: ∅ 또는 {}

*EN: - \*\*Empty Set\*\*: ∅ or {}*
- **전체집합**: U; 논의 중인 모든 대상

*EN: - \*\*Universal Set\*\*: U; all objects under consideration*
- **합집합**: A ∪ B = {x : x ∈ A 또는 x ∈ B}

*EN: - \*\*Union\*\*: A ∪ B = {x : x ∈ A or x ∈ B}*
- **교집합**: A ∩ B = {x : x ∈ A 그리고 x ∈ B}

*EN: - \*\*Intersection\*\*: A ∩ B = {x : x ∈ A and x ∈ B}*
- **여집합**: A^c = {x : x ∉ A}

*EN: - \*\*Complement\*\*: A^c = {x : x ∉ A}*
- **차집합**: A - B = {x : x ∈ A 그리고 x ∉ B}

*EN: - \*\*Difference\*\*: A - B = {x : x ∈ A and x ∉ B}*
- **곱집합**: A × B = {(a,b) : a ∈ A, b ∈ B}

*EN: - \*\*Cartesian Product\*\*: A × B = {(a,b) : a ∈ A, b ∈ B}*
- **멱집합**: P(A) = A의 모든 부분집합; |P(A)| = 2^{|A|}

*EN: - \*\*Power Set\*\*: P(A) = all subsets of A; |P(A)| = 2^{|A|}*
- **기수**: |A|; 원소의 수

*EN: - \*\*Cardinality\*\*: |A|; number of elements*

### 함수와 관계

*EN: ### Functions and Relations*
- **관계**: A × B의 부분집합

*EN: - \*\*Relation\*\*: Subset of A × B*
- **함수**: 각 입력이 정확히 하나의 출력을 가짐

*EN: - \*\*Function\*\*: Each input has exactly one output*
- **단사 (일대일)**: f(a) = f(b)이면 a = b

*EN: - \*\*Injective (One-to-One)\*\*: f(a) = f(b) implies a = b*
- **전사**: 공역의 모든 원소가 상

*EN: - \*\*Surjective (Onto)\*\*: Every element of codomain is image*
- **전단사**: 단사이며 전사; 역함수 가짐

*EN: - \*\*Bijective\*\*: Both injective and surjective; has inverse*
- **정의역**: 입력의 집합

*EN: - \*\*Domain\*\*: Set of inputs*
- **공역**: 가능한 출력의 집합

*EN: - \*\*Codomain\*\*: Set of possible outputs*
- **치역**: 실제 출력; 공역의 부분집합

*EN: - \*\*Range\*\*: Actual outputs; subset of codomain*
- **합성**: (g∘f)(x) = g(f(x))

*EN: - \*\*Composition\*\*: (g∘f)(x) = g(f(x))*
- **역함수**: f⁻¹(y) = x이면 f(x) = y; 전단사이면 존재

*EN: - \*\*Inverse\*\*: f⁻¹(y) = x if f(x) = y; exists if bijective*

### 조합론

*EN: ### Combinatorics*
- **중복 순열**: n^r; 복원 추출로 n에서 r개 선택

*EN: - \*\*Permutation with Repetition\*\*: n^r; r items from n with replacement*
- **원형 순열**: (n-1)!; n개 대상을 원형으로 배열

*EN: - \*\*Circular Permutation\*\*: (n-1)!; arrange n objects in circle*
- **중복 조합**: n!/(n₁!n₂!...nₖ!), 반복이 있는 경우

*EN: - \*\*Distinguishable Permutations\*\*: n!/(n₁!n₂!...nₖ!) with repetition*
- **막대-별 계수법**: n개의 동일 객체를 k개 칸에 분배: C(n+k-1, k-1)

*EN: - \*\*Stars and Bars\*\*: Distribute n identical objects into k bins: C(n+k-1, k-1)*
- **포함-배제 원리**: |A∪B| = |A| + |B| - |A∩B|

*EN: - \*\*Inclusion-Exclusion\*\*: |A∪B| = |A| + |B| - |A∩B|*
- **비둘기집 원리**: n+1개 객체를 n개 구멍에 → 적어도 한 구멍에 ≥2개

*EN: - \*\*Pigeonhole Principle\*\*: n+1 objects in n holes → at least one hole has ≥2 objects*
- **이항 정리**: (x+y)^n = Σ C(n,k)x^{n-k}y^k

*EN: - \*\*Binomial Theorem\*\*: (x+y)^n = Σ C(n,k)x^{n-k}y^k*

### 그래프 이론

*EN: ### Graph Theory*
- **그래프 G=(V,E)**: 꼭짓점 V, 간선 E

*EN: - \*\*Graph G=(V,E)\*\*: Vertices V, Edges E*
- **방향 그래프**: 간선에 방향이 있음

*EN: - \*\*Directed Graph\*\*: Edges have direction*
- **무향 그래프**: 간선이 양방향

*EN: - \*\*Undirected Graph\*\*: Edges bidirectional*
- **차수**: 꼭짓점에 연결된 간선의 수

*EN: - \*\*Degree\*\*: Number of edges at vertex*
- **경로**: 간선으로 연결된 꼭짓점의 수열

*EN: - \*\*Path\*\*: Sequence of vertices connected by edges*
- **사이클**: 같은 꼭짓점에서 시작하고 끝나는 경로

*EN: - \*\*Cycle\*\*: Path starting and ending at same vertex*
- **연결**: 임의의 두 꼭짓점 사이에 경로가 존재

*EN: - \*\*Connected\*\*: Path exists between any two vertices*
- **트리**: 연결된 비순환 그래프; |E| = |V| - 1

*EN: - \*\*Tree\*\*: Connected acyclic graph; |E| = |V| - 1*
- **숲**: 트리의 서로소 합집합

*EN: - \*\*Forest\*\*: Disjoint union of trees*
- **완전 그래프 K_n**: 모든 꼭짓점 쌍 사이에 간선이 있음

*EN: - \*\*Complete Graph K_n\*\*: Edge between every pair of vertices*
- **이분 그래프**: 꼭짓점이 두 집합으로 분할; 간선은 집합 간에만 존재

*EN: - \*\*Bipartite\*\*: Vertices partitioned into two sets; edges only between sets*
- **평면 그래프**: 간선 교차 없이 그릴 수 있음

*EN: - \*\*Planar\*\*: Can draw without edge crossings*
- **오일러 경로**: 모든 간선을 정확히 한 번 사용

*EN: - \*\*Euler Path\*\*: Uses every edge exactly once*
- **오일러 회로**: 사이클인 오일러 경로; 모든 차수가 짝수이면 존재

*EN: - \*\*Euler Circuit\*\*: Euler path that is cycle; exists iff all degrees even*
- **해밀턴 경로**: 모든 꼭짓점을 정확히 한 번 방문

*EN: - \*\*Hamiltonian Path\*\*: Visits every vertex exactly once*
- **해밀턴 사이클**: 사이클인 해밀턴 경로

*EN: - \*\*Hamiltonian Cycle\*\*: Hamiltonian path that is cycle*

### 알고리즘

*EN: ### Algorithms*
- **알고리즘**: 단계별 절차

*EN: - \*\*Algorithm\*\*: Step-by-step procedure*
- **빅O 표기법**: 성장률의 상한

*EN: - \*\*Big O Notation\*\*: Upper bound on growth rate*
  - O(1): 상수

*EN:   - O(1): Constant*
  - O(log n): 로그

*EN:   - O(log n): Logarithmic*
  - O(n): 선형

*EN:   - O(n): Linear*
  - O(n log n): 선형로그

*EN:   - O(n log n): Linearithmic*
  - O(n²): 이차

*EN:   - O(n²): Quadratic*
  - O(2^n): 지수

*EN:   - O(2^n): Exponential*
- **정렬**: 버블, 선택, 삽입, 병합, 퀵, 힙

*EN: - \*\*Sorting\*\*: Bubble, Selection, Insertion, Merge, Quick, Heap*
- **탐색**: 선형 O(n), 이진 O(log n)

*EN: - \*\*Searching\*\*: Linear O(n), Binary O(log n)*
- **탐욕 알고리즘**: 국소 최적 선택

*EN: - \*\*Greedy Algorithm\*\*: Makes locally optimal choice*
- **동적 프로그래밍**: 부분 문제로 분해; 메모이제이션

*EN: - \*\*Dynamic Programming\*\*: Break into subproblems; memoization*
- **분할 정복**: 분할, 해결, 합병

*EN: - \*\*Divide and Conquer\*\*: Split, solve, combine*

## 논리 & 기초

*EN: ## Logic & Foundations*

### 정수론

*EN: ### Number Theory*
- **가분성**: a|b이면 정수 k에 대해 b = ka

*EN: - \*\*Divisibility\*\*: a|b if b = ka for integer k*
- **소수**: p > 1; 약수가 1과 p뿐

*EN: - \*\*Prime\*\*: p > 1; only divisors 1 and p*
- **합성수**: 1보다 크고 소수가 아닌 수

*EN: - \*\*Composite\*\*: >1 and not prime*
- **산술의 기본 정리**: 1보다 큰 모든 정수는 고유한 소인수분해를 가짐

*EN: - \*\*Fundamental Theorem of Arithmetic\*\*: Every integer >1 has unique prime factorization*
- **최대공약수 (gcd(a,b))**: 최대공약수

*EN: - \*\*GCD (gcd(a,b))\*\*: Greatest common divisor*
- **최소공배수 (lcm(a,b))**: 최소공배수

*EN: - \*\*LCM (lcm(a,b))\*\*: Least common multiple*
- **유클리드 알고리즘**: gcd(a,b) = gcd(b, a mod b)

*EN: - \*\*Euclidean Algorithm\*\*: gcd(a,b) = gcd(b, a mod b)*
- **서로소**: gcd(a,b) = 1

*EN: - \*\*Relatively Prime\*\*: gcd(a,b) = 1*
- **모듈러 산술**: m|(a-b)이면 a ≡ b (mod m)

*EN: - \*\*Modular Arithmetic\*\*: a ≡ b (mod m) if m|(a-b)*
- **합동류**: [a]_m = {b : b ≡ a (mod m)}

*EN: - \*\*Congruence Classes\*\*: [a]_m = {b : b ≡ a (mod m)}*
- **페르마 소정리**: p가 소수이면 a^p ≡ a (mod p)

*EN: - \*\*Fermat's Little Theorem\*\*: If p prime, a^p ≡ a (mod p)*
- **오일러 토션트 함수 φ(n)**: n이하의 정수 중 n과 서로소인 수의 개수

*EN: - \*\*Euler's Totient Function φ(n)\*\*: Count of integers ≤n relatively prime to n*

### 수학적 귀납법

*EN: ### Mathematical Induction*
- **원리**: P(1) 증명; P(k) → P(k+1) 증명; 모든 n ≥ 1에 대해 P(n) 결론

*EN: - \*\*Principle\*\*: Prove P(1); prove P(k) → P(k+1); conclude P(n) for all n ≥ 1*
- **강한 귀납법**: P(k+1)을 증명하기 위해 P(1),...,P(k) 가정

*EN: - \*\*Strong Induction\*\*: Assume P(1),...,P(k) to prove P(k+1)*
- **기저 경우**: 가장 작은 값 검증

*EN: - \*\*Base Case\*\*: Verify smallest value*
- **귀납 가정**: k에 대해 참이라고 가정

*EN: - \*\*Inductive Hypothesis\*\*: Assume true for k*
- **귀납 단계**: k+1에 대해 참임을 보임

*EN: - \*\*Inductive Step\*\*: Show true for k+1*

### 형식 체계

*EN: ### Formal Systems*
- **공리**: 증명 없이 참으로 가정하는 진술

*EN: - \*\*Axioms\*\*: Statements assumed true without proof*
- **정리**: 공리로부터 증명된 진술

*EN: - \*\*Theorem\*\*: Proved statement from axioms*
- **보조 정리**: 더 큰 증명을 돕는 작은 결과

*EN: - \*\*Lemma\*\*: Minor result aiding larger proof*
- **따름 정리**: 정리로부터 쉽게 따르는 결과

*EN: - \*\*Corollary\*\*: Result following easily from theorem*
- **증명**: 진실을 확립하는 논리적 논증

*EN: - \*\*Proof\*\*: Logical argument establishing truth*
  - 직접 증명: 전제를 가정하고 결론 도출

*EN:   - Direct: Assume premises, derive conclusion*
  - 간접 증명 (귀류법): ¬결론을 가정하고 모순 도출

*EN:   - Indirect (Contradiction): Assume ¬conclusion, derive contradiction*
  - 대우 증명: P → Q에 대해 ¬Q → ¬P 증명

*EN:   - Contrapositive: Prove ¬Q → ¬P for P → Q*
  - 구성적 증명: 예를 제시

*EN:   - Constructive: Exhibit example*
  - 존재 증명: 구성 없이 존재함을 보임

*EN:   - Existence: Show something exists without constructing*
- **반례**: 진술이 거짓임을 보임

*EN: - \*\*Counterexample\*\*: Shows statement false*

### 계산가능성

*EN: ### Computability*
- **튜링 기계**: 계산의 추상적 모델

*EN: - \*\*Turing Machine\*\*: Abstract model of computation*
- **결정가능**: 소속 여부를 결정하는 알고리즘이 존재

*EN: - \*\*Decidable\*\*: Algorithm exists to determine membership*
- **결정불가**: 알고리즘이 없음 (예: 정지 문제)

*EN: - \*\*Undecidable\*\*: No algorithm exists (e.g., Halting Problem)*
- **계산가능 함수**: 튜링 기계로 계산 가능

*EN: - \*\*Computable Function\*\*: Can be computed by Turing machine*
- **재귀적으로 열거가능**: 원소를 나열할 수 있음; 비원소에서는 정지하지 않을 수 있음

*EN: - \*\*Recursively Enumerable\*\*: Can list members; may not halt on non-members*

