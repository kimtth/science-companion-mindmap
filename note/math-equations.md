# Mathematics Equations Reference

## 📐 Calculus

### Limits & Continuity

**Limit Definition**
- $\lim_{x \to a} f(x) = L$ if for every $\epsilon > 0$, there exists $\delta > 0$ such that $|f(x) - L| < \epsilon$ whenever $0 < |x - a| < \delta$

**Limit Laws**
- Sum: $\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$
- Product: $\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$
- Quotient: $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$ if $\lim_{x \to a} g(x) \neq 0$

**Special Limits**
- $\lim_{x \to 0} \frac{\sin x}{x} = 1$
- $\lim_{x \to 0} \frac{1 - \cos x}{x} = 0$
- $\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e$

**Continuity**
- $f$ is continuous at $a$ if $\lim_{x \to a} f(x) = f(a)$

**Intermediate Value Theorem (IVT)**
- If $f$ is continuous on $[a,b]$ and $N$ is between $f(a)$ and $f(b)$, then there exists $c \in (a,b)$ such that $f(c) = N$

### Derivatives

**Difference Quotient**
- $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

**Basic Derivatives**
- Power rule: $\frac{d}{dx}[x^n] = nx^{n-1}$
- Constant: $\frac{d}{dx}[c] = 0$
- Exponential: $\frac{d}{dx}[e^x] = e^x$, $\frac{d}{dx}[a^x] = a^x \ln a$
- Logarithm: $\frac{d}{dx}[\ln x] = \frac{1}{x}$, $\frac{d}{dx}[\log_a x] = \frac{1}{x \ln a}$

**Trigonometric Derivatives**
- $\frac{d}{dx}[\sin x] = \cos x$
- $\frac{d}{dx}[\cos x] = -\sin x$
- $\frac{d}{dx}[\tan x] = \sec^2 x$
- $\frac{d}{dx}[\cot x] = -\csc^2 x$
- $\frac{d}{dx}[\sec x] = \sec x \tan x$
- $\frac{d}{dx}[\csc x] = -\csc x \cot x$

**Inverse Trigonometric Derivatives**
- $\frac{d}{dx}[\sin^{-1} x] = \frac{1}{\sqrt{1-x^2}}$
- $\frac{d}{dx}[\cos^{-1} x] = -\frac{1}{\sqrt{1-x^2}}$
- $\frac{d}{dx}[\tan^{-1} x] = \frac{1}{1+x^2}$

**Differentiation Rules**
- Sum rule: $(f + g)' = f' + g'$
- Product rule: $(fg)' = f'g + fg'$
- Quotient rule: $\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$
- Chain rule: $(f \circ g)'(x) = f'(g(x)) \cdot g'(x)$

**Implicit Differentiation**
- Differentiate both sides with respect to $x$, treating $y$ as a function of $x$

**Mean Value Theorem (MVT)**
- If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then there exists $c \in (a,b)$ such that $f'(c) = \frac{f(b) - f(a)}{b - a}$

### Integration

**Fundamental Theorem of Calculus (FTC)**
- Part 1: If $F(x) = \int_a^x f(t)\,dt$, then $F'(x) = f(x)$
- Part 2: $\int_a^b f(x)\,dx = F(b) - F(a)$ where $F' = f$

**Basic Integrals**
- Power rule: $\int x^n\,dx = \frac{x^{n+1}}{n+1} + C$ (for $n \neq -1$)
- $\int \frac{1}{x}\,dx = \ln|x| + C$
- $\int e^x\,dx = e^x + C$
- $\int a^x\,dx = \frac{a^x}{\ln a} + C$

**Trigonometric Integrals**
- $\int \sin x\,dx = -\cos x + C$
- $\int \cos x\,dx = \sin x + C$
- $\int \tan x\,dx = -\ln|\cos x| + C = \ln|\sec x| + C$
- $\int \sec^2 x\,dx = \tan x + C$
- $\int \sec x \tan x\,dx = \sec x + C$
- $\int \frac{1}{\sqrt{1-x^2}}\,dx = \sin^{-1} x + C$
- $\int \frac{1}{1+x^2}\,dx = \tan^{-1} x + C$

**Integration Techniques**

*Substitution (u-substitution)*
- $\int f(g(x))g'(x)\,dx = \int f(u)\,du$ where $u = g(x)$

*Integration by Parts*
- $\int u\,dv = uv - \int v\,du$

*Partial Fractions*
- Decompose $\frac{P(x)}{Q(x)}$ where $\deg(P) < \deg(Q)$

*Trigonometric Substitution*
- $\sqrt{a^2 - x^2}$: use $x = a\sin\theta$
- $\sqrt{a^2 + x^2}$: use $x = a\tan\theta$
- $\sqrt{x^2 - a^2}$: use $x = a\sec\theta$

**Applications of Integration**
- Area between curves: $A = \int_a^b [f(x) - g(x)]\,dx$
- Volume (disk method): $V = \pi \int_a^b [f(x)]^2\,dx$
- Volume (shell method): $V = 2\pi \int_a^b x f(x)\,dx$
- Arc length: $L = \int_a^b \sqrt{1 + [f'(x)]^2}\,dx$
- Surface area: $S = 2\pi \int_a^b f(x)\sqrt{1 + [f'(x)]^2}\,dx$

### Sequences & Series

**Sequences**
- Convergence: $\lim_{n \to \infty} a_n = L$
- Bounded: $|a_n| \leq M$ for all $n$
- Monotonic: increasing or decreasing

**Series**
- $\sum_{n=1}^{\infty} a_n = \lim_{N \to \infty} \sum_{n=1}^N a_n$
- Geometric series: $\sum_{n=0}^{\infty} ar^n = \frac{a}{1-r}$ if $|r| < 1$
- Harmonic series: $\sum_{n=1}^{\infty} \frac{1}{n}$ diverges
- p-series: $\sum_{n=1}^{\infty} \frac{1}{n^p}$ converges if $p > 1$

**Convergence Tests**
- **Divergence test**: If $\lim_{n \to \infty} a_n \neq 0$, then $\sum a_n$ diverges
- **Integral test**: $\sum a_n$ and $\int_1^{\infty} f(x)\,dx$ both converge or both diverge (if $f$ is positive, continuous, decreasing)
- **Comparison test**: If $0 \leq a_n \leq b_n$ and $\sum b_n$ converges, then $\sum a_n$ converges
- **Limit comparison test**: If $\lim_{n \to \infty} \frac{a_n}{b_n} = c > 0$, then $\sum a_n$ and $\sum b_n$ behave the same
- **Ratio test**: $L = \lim_{n \to \infty} \left|\frac{a_{n+1}}{a_n}\right|$
  - If $L < 1$: converges absolutely
  - If $L > 1$: diverges
  - If $L = 1$: test inconclusive
- **Root test**: $L = \lim_{n \to \infty} \sqrt[n]{|a_n|}$
  - If $L < 1$: converges absolutely
  - If $L > 1$: diverges
- **Alternating series test**: If $a_n > 0$, $a_n$ decreasing, and $\lim_{n \to \infty} a_n = 0$, then $\sum (-1)^n a_n$ converges

**Power Series**
- $\sum_{n=0}^{\infty} c_n(x-a)^n$
- Radius of convergence: $R = \frac{1}{\lim_{n \to \infty} \sqrt[n]{|c_n|}}$ or $R = \lim_{n \to \infty} \left|\frac{c_n}{c_{n+1}}\right|$
- Interval of convergence: $(a-R, a+R)$ (check endpoints separately)

**Taylor Series**
- $f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$
- Maclaurin series: Taylor series centered at $a = 0$

**Common Maclaurin Series**
- $e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$
- $\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n+1}}{(2n+1)!}$
- $\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}$
- $\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n$ for $|x| < 1$
- $\ln(1+x) = \sum_{n=1}^{\infty} \frac{(-1)^{n+1} x^n}{n}$ for $|x| < 1$

### Multivariable Calculus

**Partial Derivatives**
- $\frac{\partial f}{\partial x} = \lim_{h \to 0} \frac{f(x+h, y) - f(x, y)}{h}$

**Gradient**
- $\nabla f = \left\langle \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z} \right\rangle$

**Directional Derivative**
- $D_{\mathbf{u}}f = \nabla f \cdot \mathbf{u}$ where $\mathbf{u}$ is a unit vector

**Chain Rule (Multivariable)**
- $\frac{dz}{dt} = \frac{\partial z}{\partial x}\frac{dx}{dt} + \frac{\partial z}{\partial y}\frac{dy}{dt}$

**Optimization**
- Critical points: $\nabla f = \mathbf{0}$
- Second derivative test: Use Hessian determinant $D = f_{xx}f_{yy} - (f_{xy})^2$
  - $D > 0$ and $f_{xx} > 0$: local minimum
  - $D > 0$ and $f_{xx} < 0$: local maximum
  - $D < 0$: saddle point

**Lagrange Multipliers**
- To optimize $f(x,y,z)$ subject to $g(x,y,z) = k$:
- Solve $\nabla f = \lambda \nabla g$ and $g(x,y,z) = k$

**Double Integrals**
- $\iint_R f(x,y)\,dA = \int_a^b \int_{g_1(x)}^{g_2(x)} f(x,y)\,dy\,dx$
- Polar coordinates: $\iint_R f(x,y)\,dA = \int_{\alpha}^{\beta} \int_{r_1(\theta)}^{r_2(\theta)} f(r\cos\theta, r\sin\theta) r\,dr\,d\theta$

**Triple Integrals**
- $\iiint_E f(x,y,z)\,dV$
- Cylindrical: $dV = r\,dr\,d\theta\,dz$
- Spherical: $dV = \rho^2 \sin\phi\,d\rho\,d\phi\,d\theta$

**Change of Variables**
- Jacobian: $J = \frac{\partial(x,y)}{\partial(u,v)} = \begin{vmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial v} \\ \frac{\partial y}{\partial u} & \frac{\partial y}{\partial v} \end{vmatrix}$
- $\iint_R f(x,y)\,dx\,dy = \iint_S f(x(u,v), y(u,v)) |J|\,du\,dv$

### Vector Calculus

**Line Integrals**
- Scalar field: $\int_C f\,ds = \int_a^b f(\mathbf{r}(t))|\mathbf{r}'(t)|\,dt$
- Vector field: $\int_C \mathbf{F} \cdot d\mathbf{r} = \int_a^b \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt$

**Conservative Vector Fields**
- $\mathbf{F}$ is conservative if $\mathbf{F} = \nabla f$ for some scalar function $f$
- Test: $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x}$ (in 2D)
- If conservative: $\int_C \mathbf{F} \cdot d\mathbf{r} = f(\mathbf{r}(b)) - f(\mathbf{r}(a))$ (path independent)

**Green's Theorem**
- $\oint_C (P\,dx + Q\,dy) = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)\,dA$

**Curl and Divergence**
- Curl: $\nabla \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ P & Q & R \end{vmatrix}$
- Divergence: $\nabla \cdot \mathbf{F} = \frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}$

**Surface Integrals**
- $\iint_S f\,dS = \iint_D f(\mathbf{r}(u,v))|\mathbf{r}_u \times \mathbf{r}_v|\,dA$
- Flux: $\iint_S \mathbf{F} \cdot d\mathbf{S} = \iint_S \mathbf{F} \cdot \mathbf{n}\,dS$

**Stokes' Theorem**
- $\oint_C \mathbf{F} \cdot d\mathbf{r} = \iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S}$

**Divergence Theorem**
- $\iiint_E (\nabla \cdot \mathbf{F})\,dV = \iint_S \mathbf{F} \cdot d\mathbf{S}$

## 🔢 Linear Algebra

### Vectors

**Dot Product**
- $\mathbf{u} \cdot \mathbf{v} = u_1v_1 + u_2v_2 + u_3v_3 = |\mathbf{u}||\mathbf{v}|\cos\theta$

**Cross Product**
- $\mathbf{u} \times \mathbf{v} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ u_1 & u_2 & u_3 \\ v_1 & v_2 & v_3 \end{vmatrix}$
- $|\mathbf{u} \times \mathbf{v}| = |\mathbf{u}||\mathbf{v}|\sin\theta$

**Scalar and Vector Projections**
- Scalar projection: $\text{comp}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|}$
- Vector projection: $\text{proj}_{\mathbf{v}}\mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{v}|^2}\mathbf{v}$

### Matrices

**Matrix Multiplication**
- $(AB)_{ij} = \sum_{k=1}^n a_{ik}b_{kj}$

**Matrix Inverse**
- $A^{-1}A = AA^{-1} = I$
- $A^{-1} = \frac{1}{\det(A)}\text{adj}(A)$ (for 2×2 and 3×3)

**Determinants**
- 2×2: $\det\begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc$
- 3×3: Use cofactor expansion

**Properties**
- $\det(AB) = \det(A)\det(B)$
- $\det(A^T) = \det(A)$
- $\det(A^{-1}) = \frac{1}{\det(A)}$

### Systems of Linear Equations

**Gaussian Elimination**
- Reduce augmented matrix $[A|\mathbf{b}]$ to row echelon form (REF)

**Gauss-Jordan Elimination**
- Reduce to reduced row echelon form (RREF)

**Matrix Equation**
- $A\mathbf{x} = \mathbf{b}$
- Solution: $\mathbf{x} = A^{-1}\mathbf{b}$ (if $A$ is invertible)

**Cramer's Rule**
- $x_i = \frac{\det(A_i)}{\det(A)}$ where $A_i$ is $A$ with column $i$ replaced by $\mathbf{b}$

### Eigenvalues & Eigenvectors

**Characteristic Equation**
- $\det(A - \lambda I) = 0$

**Eigenvalues and Eigenvectors**
- $A\mathbf{v} = \lambda\mathbf{v}$ where $\lambda$ is eigenvalue and $\mathbf{v}$ is eigenvector

**Diagonalization**
- $A = PDP^{-1}$ where $D$ is diagonal matrix of eigenvalues and $P$ is matrix of eigenvectors

### Vector Spaces

**Span**
- $\text{span}(\mathbf{v}_1, \ldots, \mathbf{v}_n) = \{c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n : c_i \in \mathbb{R}\}$

**Linear Independence**
- Vectors are linearly independent if $c_1\mathbf{v}_1 + \cdots + c_n\mathbf{v}_n = \mathbf{0}$ implies $c_1 = \cdots = c_n = 0$

**Rank-Nullity Theorem**
- $\dim(\text{Col } A) + \dim(\text{Nul } A) = n$ (number of columns)

### Inner Product Spaces

**Inner Product**
- $\langle \mathbf{u}, \mathbf{v} \rangle = \mathbf{u}^T\mathbf{v}$ (standard inner product)

**Norm**
- $\|\mathbf{v}\| = \sqrt{\langle \mathbf{v}, \mathbf{v} \rangle}$

**Gram-Schmidt Process**
- Orthogonalize vectors: $\mathbf{v}_k = \mathbf{u}_k - \sum_{j=1}^{k-1} \frac{\langle \mathbf{u}_k, \mathbf{v}_j \rangle}{\langle \mathbf{v}_j, \mathbf{v}_j \rangle}\mathbf{v}_j$

**QR Factorization**
- $A = QR$ where $Q$ has orthonormal columns and $R$ is upper triangular

## 📊 Differential Equations

### First Order ODEs

**Separable**
- $\frac{dy}{dx} = g(x)h(y)$
- Solution: $\int \frac{1}{h(y)}\,dy = \int g(x)\,dx$

**Linear**
- $\frac{dy}{dx} + P(x)y = Q(x)$
- Integrating factor: $\mu(x) = e^{\int P(x)\,dx}$
- Solution: $y = \frac{1}{\mu(x)}\left[\int \mu(x)Q(x)\,dx + C\right]$

**Exact**
- $M(x,y)\,dx + N(x,y)\,dy = 0$ is exact if $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$
- Solution: Find $F(x,y)$ such that $\frac{\partial F}{\partial x} = M$ and $\frac{\partial F}{\partial y} = N$

**Bernoulli**
- $\frac{dy}{dx} + P(x)y = Q(x)y^n$
- Substitution: $v = y^{1-n}$

### Second Order ODEs

**Homogeneous with Constant Coefficients**
- $ay'' + by' + cy = 0$
- Characteristic equation: $ar^2 + br + c = 0$
- Solutions depend on roots:
  - Real distinct: $y = c_1e^{r_1x} + c_2e^{r_2x}$
  - Repeated root: $y = c_1e^{rx} + c_2xe^{rx}$
  - Complex: $r = \alpha \pm \beta i$, $y = e^{\alpha x}(c_1\cos\beta x + c_2\sin\beta x)$

**Non-homogeneous**
- $ay'' + by' + cy = f(x)$
- General solution: $y = y_h + y_p$
- **Method of undetermined coefficients**: Guess form of $y_p$ based on $f(x)$
- **Variation of parameters**: $y_p = u_1(x)y_1 + u_2(x)y_2$
  - Wronskian: $W = y_1y_2' - y_1'y_2$
  - $u_1' = -\frac{y_2f}{aW}$, $u_2' = \frac{y_1f}{aW}$

### Laplace Transform

**Definition**
- $\mathcal{L}\{f(t)\} = F(s) = \int_0^{\infty} e^{-st}f(t)\,dt$

**Common Transforms**
- $\mathcal{L}\{1\} = \frac{1}{s}$
- $\mathcal{L}\{t^n\} = \frac{n!}{s^{n+1}}$
- $\mathcal{L}\{e^{at}\} = \frac{1}{s-a}$
- $\mathcal{L}\{\sin(bt)\} = \frac{b}{s^2 + b^2}$
- $\mathcal{L}\{\cos(bt)\} = \frac{s}{s^2 + b^2}$

**Properties**
- Linearity: $\mathcal{L}\{af + bg\} = a\mathcal{L}\{f\} + b\mathcal{L}\{g\}$
- First derivative: $\mathcal{L}\{f'\} = s\mathcal{L}\{f\} - f(0)$
- Second derivative: $\mathcal{L}\{f''\} = s^2\mathcal{L}\{f\} - sf(0) - f'(0)$
- Shifting: $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$

### Partial Differential Equations

**Heat Equation**
- $\frac{\partial u}{\partial t} = \alpha^2 \frac{\partial^2 u}{\partial x^2}$

**Wave Equation**
- $\frac{\partial^2 u}{\partial t^2} = c^2 \frac{\partial^2 u}{\partial x^2}$

**Laplace's Equation**
- $\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0$

**Separation of Variables**
- Assume $u(x,t) = X(x)T(t)$
- Substitute and separate variables

## 📈 Probability & Statistics

### Probability

**Basic Probability**
- $0 \leq P(A) \leq 1$
- $P(A^c) = 1 - P(A)$
- $P(A \cup B) = P(A) + P(B) - P(A \cap B)$

**Conditional Probability**
- $P(A|B) = \frac{P(A \cap B)}{P(B)}$

**Independence**
- $P(A \cap B) = P(A)P(B)$

**Bayes' Theorem**
- $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

**Law of Total Probability**
- $P(B) = \sum_{i=1}^n P(B|A_i)P(A_i)$

### Counting

**Permutations**
- $P(n,r) = \frac{n!}{(n-r)!}$

**Combinations**
- $C(n,r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}$

### Random Variables

**Expected Value**
- Discrete: $E[X] = \sum_x x \cdot P(X=x)$
- Continuous: $E[X] = \int_{-\infty}^{\infty} x f(x)\,dx$

**Variance**
- $\text{Var}(X) = E[(X-\mu)^2] = E[X^2] - (E[X])^2$

**Standard Deviation**
- $\sigma = \sqrt{\text{Var}(X)}$

### Discrete Distributions

**Binomial**
- $P(X = k) = \binom{n}{k}p^k(1-p)^{n-k}$
- $E[X] = np$, $\text{Var}(X) = np(1-p)$

**Geometric**
- $P(X = k) = (1-p)^{k-1}p$
- $E[X] = \frac{1}{p}$, $\text{Var}(X) = \frac{1-p}{p^2}$

**Poisson**
- $P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}$
- $E[X] = \lambda$, $\text{Var}(X) = \lambda$

### Continuous Distributions

**Uniform**
- $f(x) = \frac{1}{b-a}$ for $a \leq x \leq b$
- $E[X] = \frac{a+b}{2}$, $\text{Var}(X) = \frac{(b-a)^2}{12}$

**Normal**
- $f(x) = \frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$
- $E[X] = \mu$, $\text{Var}(X) = \sigma^2$
- Standard normal: $Z = \frac{X-\mu}{\sigma}$

**Exponential**
- $f(x) = \lambda e^{-\lambda x}$ for $x \geq 0$
- $E[X] = \frac{1}{\lambda}$, $\text{Var}(X) = \frac{1}{\lambda^2}$

### Statistical Inference

**Sample Mean**
- $\bar{X} = \frac{1}{n}\sum_{i=1}^n X_i$
- $E[\bar{X}] = \mu$, $\text{Var}(\bar{X}) = \frac{\sigma^2}{n}$

**Central Limit Theorem**
- $\bar{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right)$ for large $n$

**Confidence Interval for Mean**
- $\bar{x} \pm z_{\alpha/2}\frac{\sigma}{\sqrt{n}}$ (known $\sigma$)
- $\bar{x} \pm t_{\alpha/2,n-1}\frac{s}{\sqrt{n}}$ (unknown $\sigma$)

**Hypothesis Testing**
- Test statistic: $z = \frac{\bar{x} - \mu_0}{\sigma/\sqrt{n}}$ or $t = \frac{\bar{x} - \mu_0}{s/\sqrt{n}}$
- p-value: probability of observing result at least as extreme given $H_0$ is true
- Reject $H_0$ if p-value $< \alpha$

### Regression

**Simple Linear Regression**
- Model: $Y = \beta_0 + \beta_1 X + \epsilon$
- Estimates: $\hat{\beta}_1 = \frac{\sum(x_i - \bar{x})(y_i - \bar{y})}{\sum(x_i - \bar{x})^2}$, $\hat{\beta}_0 = \bar{y} - \hat{\beta}_1\bar{x}$
- $R^2 = 1 - \frac{SS_{\text{res}}}{SS_{\text{tot}}}$

## 🎲 Discrete Mathematics

### Logic

**Logical Operators**
- Negation: $\neg p$
- Conjunction: $p \wedge q$ (and)
- Disjunction: $p \vee q$ (or)
- Implication: $p \to q$ (if p then q)
- Biconditional: $p \leftrightarrow q$ (if and only if)

**De Morgan's Laws**
- $\neg(p \wedge q) \equiv \neg p \vee \neg q$
- $\neg(p \vee q) \equiv \neg p \wedge \neg q$

### Set Theory

**Set Operations**
- Union: $A \cup B = \{x : x \in A \text{ or } x \in B\}$
- Intersection: $A \cap B = \{x : x \in A \text{ and } x \in B\}$
- Difference: $A - B = \{x : x \in A \text{ and } x \notin B\}$
- Complement: $A^c = \{x : x \notin A\}$

**Cardinality**
- $|A \cup B| = |A| + |B| - |A \cap B|$
- $|A \times B| = |A| \cdot |B|$

### Combinatorics

**Binomial Theorem**
- $(x+y)^n = \sum_{k=0}^n \binom{n}{k}x^{n-k}y^k$

**Pigeonhole Principle**
- If $n+1$ objects are placed into $n$ boxes, at least one box contains at least 2 objects

**Inclusion-Exclusion Principle**
- $|A_1 \cup A_2 \cup \cdots \cup A_n| = \sum |A_i| - \sum |A_i \cap A_j| + \sum |A_i \cap A_j \cap A_k| - \cdots$

### Graph Theory

**Handshaking Lemma**
- $\sum_{v \in V} \deg(v) = 2|E|$

**Euler's Formula (Planar Graphs)**
- $v - e + f = 2$ where $v$ = vertices, $e$ = edges, $f$ = faces

**Graph Coloring**
- Chromatic number $\chi(G)$: minimum colors needed to color vertices

### Number Theory

**Division Algorithm**
- $a = bq + r$ where $0 \leq r < b$

**Euclidean Algorithm (GCD)**
- Repeatedly apply $\gcd(a,b) = \gcd(b, a \bmod b)$ until remainder is 0

**Bézout's Identity**
- If $d = \gcd(a,b)$, then there exist integers $x,y$ such that $ax + by = d$

**Fundamental Theorem of Arithmetic**
- Every integer $n > 1$ can be uniquely written as a product of primes

**Fermat's Little Theorem**
- If $p$ is prime and $\gcd(a,p) = 1$, then $a^{p-1} \equiv 1 \pmod{p}$

**Euler's Theorem**
- If $\gcd(a,n) = 1$, then $a^{\phi(n)} \equiv 1 \pmod{n}$

**Chinese Remainder Theorem**
- System $x \equiv a_i \pmod{m_i}$ has unique solution modulo $M = \prod m_i$ if $m_i$ are pairwise coprime
