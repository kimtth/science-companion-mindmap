# General Mathematics Overview

## 🎯 Purpose
This mindmap provides a comprehensive overview of college-level mathematics, covering fundamental concepts from calculus and linear algebra to probability, statistics, and discrete mathematics. It serves as a visual and conceptual guide for understanding the hierarchical relationships between mathematical ideas and their applications.

## 📚 Main Topics

### 1. Calculus
The mathematics of continuous change - understanding rates, accumulation, and optimization. Calculus is the foundation of modern science and engineering:

**Limits & Continuity**
- **Epsilon-delta definition of limits**: Rigorous formal definition using ε-δ notation
  - For every ε > 0, there exists δ > 0 such that |f(x) - L| < ε when 0 < |x - a| < δ
  - Formalizes the intuitive notion of "approaching a value"
  - Foundation for all of calculus
- **Limit laws and properties**: Algebraic rules for computing limits
  - Sum, difference, product, quotient rules
  - Limits of polynomials, rational functions
  - Squeeze theorem for difficult limits
- **Continuity definitions and theorems**: Function continuous if lim f(x) = f(a) as x→a
  - Requires function defined at point, limit exists, and they're equal
  - Continuous functions preserve intervals
  - Sums, products, compositions of continuous functions are continuous
- **Intermediate Value Theorem**: Continuous function takes all values between f(a) and f(b)
  - Guarantees existence of roots
  - Used to prove equations have solutions
- **Types of discontinuities**: Jump, removable, infinite
  - Jump: left and right limits exist but differ
  - Removable: limit exists but doesn't equal function value
  - Infinite: function approaches ±∞

**Differentiation**
- **Definition using limits**: f'(x) = lim[h→0] (f(x+h) - f(x))/h
  - Measures instantaneous rate of change
  - Slope of tangent line at a point
  - Velocity is derivative of position
- **Power rule, product rule, quotient rule, chain rule**: Differentiation shortcuts
  - Power: d/dx(x^n) = nx^(n-1)
  - Product: (uv)' = u'v + uv'
  - Quotient: (u/v)' = (u'v - uv')/v²
  - Chain: d/dx f(g(x)) = f'(g(x))·g'(x)
- **Implicit differentiation**: Differentiating equations not solved for y
  - Used for relations like x² + y² = 1
  - Treat y as function of x and use chain rule
- **Higher-order derivatives**: f'', f''', f^(n)
  - Second derivative measures concavity (acceleration)
  - Used for optimization and curve analysis
- **Applications**: tangent lines, optimization, related rates, curve sketching
  - Optimization: find max/min using f'(x) = 0
  - Related rates: connect rates of change of related quantities
  - Curve sketching: increasing/decreasing, concavity, inflection points
- **Mean Value Theorem**: f'(c) = (f(b) - f(a))/(b - a) for some c in (a,b)
  - Guarantees instantaneous rate equals average rate somewhere
  - Foundation for many calculus theorems

**Integration**
- **Riemann sums and definite integrals**: Sum of rectangles approximating area
  - ∫[a,b] f(x)dx = lim[n→∞] Σf(x_i)Δx
  - Accumulation of infinitesimal quantities
  - Exact area under curve
- **Fundamental Theorem of Calculus (both parts)**: Links derivatives and integrals
  - Part 1: d/dx ∫[a,x] f(t)dt = f(x)
  - Part 2: ∫[a,b] f(x)dx = F(b) - F(a) where F' = f
  - Integration reverses differentiation
- **Integration techniques**: Methods for computing antiderivatives
  - Substitution (u-substitution): reverses chain rule
  - Integration by parts: ∫udv = uv - ∫vdu (reverses product rule)
  - Partial fractions: decompose rational functions
  - Trigonometric substitution: for √(a²-x²), √(a²+x²), √(x²-a²)
- **Improper integrals**: Infinite limits or infinite discontinuities
  - ∫[a,∞) f(x)dx = lim[b→∞] ∫[a,b] f(x)dx
  - Convergence vs divergence
- **Applications**: area, volume, arc length, work
  - Area between curves: ∫(f(x) - g(x))dx
  - Volume: disk method (πr²), washer method, shell method (2πrh)
  - Arc length: ∫√(1 + (f'(x))²)dx
  - Work: ∫F(x)dx (force times distance)

**Sequences & Series**
- **Sequence convergence**: lim[n→∞] a_n = L
  - Bounded and monotonic sequences converge
  - Squeeze theorem for sequences
- **Infinite series**: Σa_n from n=1 to ∞
  - Geometric: Σar^n converges if |r| < 1 to a/(1-r)
  - p-series: Σ1/n^p converges if p > 1
  - Alternating series: terms alternate sign
- **Convergence tests**: Determining if series converges
  - Ratio test: lim|a_(n+1)/a_n| < 1 ⟹ converges
  - Root test: lim|a_n|^(1/n) < 1 ⟹ converges
  - Integral test: compare with ∫f(x)dx
  - Comparison: compare with known series
  - Limit comparison: examine lim(a_n/b_n)
- **Power series and Taylor/Maclaurin series**: Σc_n(x-a)^n
  - Taylor: represents function as infinite polynomial
  - Maclaurin: Taylor series centered at 0
  - e^x = Σx^n/n!, sin(x) = Σ(-1)^n x^(2n+1)/(2n+1)!
- **Radius and interval of convergence**: Where power series converges
  - Use ratio test to find radius R
  - Check endpoints separately
  - Series converges absolutely for |x-a| < R

**Multivariable Calculus**
- **Partial derivatives and gradients**: Rate of change with respect to one variable
  - ∂f/∂x: derivative treating other variables as constants
  - Gradient ∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z): vector of all partial derivatives
  - Points in direction of steepest ascent
- **Directional derivatives**: Rate of change in any direction
  - D_u f = ∇f · u where u is unit vector
  - Generalizes partial derivatives
- **Chain rule for multivariable functions**: Composition of multivariable functions
  - ∂z/∂s = (∂z/∂x)(∂x/∂s) + (∂z/∂y)(∂y/∂s)
  - Essential for implicit differentiation in higher dimensions
- **Optimization**: Finding maxima and minima
  - Critical points: where ∇f = 0 or undefined
  - Second derivative test using Hessian matrix
  - Classify as max, min, or saddle point
- **Lagrange multipliers**: Optimization with constraints
  - Find extrema of f(x,y) subject to g(x,y) = c
  - Solve ∇f = λ∇g and constraint simultaneously
  - λ is Lagrange multiplier
- **Double and triple integrals**: Integration over regions
  - ∬_R f(x,y)dA: accumulation over 2D region
  - ∭_V f(x,y,z)dV: accumulation over 3D region
  - Iterated integrals, Fubini's theorem
- **Change of variables (Jacobian)**: Transforming coordinate systems
  - Jacobian determinant |∂(x,y)/∂(u,v)| scales area
  - Polar: dA = r dr dθ
  - Cylindrical, spherical coordinates for 3D

**Vector Calculus**
- **Vector fields**: Function assigning vector to each point F(x,y,z)
  - Velocity fields, force fields, electric/magnetic fields
  - Gradient fields are conservative (path-independent)
- **Line integrals and path independence**: Integral along curve
  - ∫_C F·dr: work done by force field along path
  - Conservative fields: ∫_C F·dr depends only on endpoints
  - Potential function φ: F = ∇φ
- **Surface integrals**: Integral over surface
  - ∬_S F·dS: flux through surface
  - Measures flow across surface
- **Green's Theorem**: Relates line integral to double integral
  - ∮_C F·dr = ∬_R (∂Q/∂x - ∂P/∂y)dA
  - Circulation equals curl integrated over region
- **Stokes' Theorem**: Relates surface integral to line integral
  - ∬_S (curl F)·dS = ∮_C F·dr
  - Generalizes Green's theorem to 3D
- **Divergence Theorem**: Relates volume integral to surface integral
  - ∭_V (div F)dV = ∬_S F·dS
  - Flux out of volume equals divergence inside
  - Gauss's theorem, fundamental for Maxwell's equations

**Conceptual Insights**:
- Limits formalize the notion of "approaching" a value
- Derivative measures instantaneous rate of change
- Integral represents accumulation and reverses differentiation
- Fundamental Theorem connects derivatives and integrals
- Multivariable calculus extends ideas to higher dimensions
- Vector calculus unifies electricity, magnetism, and fluid flow

**Key Applications**: Physics (motion, forces, fields), engineering (optimization, fluid dynamics), economics (marginal analysis, elasticity), computer graphics, machine learning (gradient descent)

### 2. Linear Algebra
The study of vector spaces and linear transformations - fundamental to modern mathematics and applications. Linear algebra provides the language for describing multidimensional systems:

**Vectors**
- **Vector operations and geometric interpretation**: Addition, scalar multiplication
  - Vectors represent directed quantities (magnitude and direction)
  - Parallelogram law for addition
  - Scaling by scalars changes magnitude
- **Dot product and orthogonality**: a·b = |a||b|cosθ
  - Measures projection of one vector onto another
  - Orthogonal (perpendicular) when a·b = 0
  - Used to compute angles, projections
- **Cross product and determinants (2×2, 3×3)**: a×b perpendicular to both
  - |a×b| = |a||b|sinθ (area of parallelogram)
  - Right-hand rule determines direction
  - Only defined in 3D (and 7D)
- **Vector projections**: Component of vector along another
  - proj_b(a) = (a·b/|b|²)b
  - Decomposes vector into parallel and perpendicular parts
- **Applications in geometry and physics**: Position, velocity, force
  - Displacement, velocity, acceleration vectors
  - Force vectors, torque = r×F
  - Work = F·d

**Matrices**
- **Matrix operations**: addition, multiplication, transpose
  - Addition: element-wise, matrices must have same dimensions
  - Multiplication: (AB)_ij = Σ A_ik B_kj (row-by-column)
  - Not commutative: AB ≠ BA in general
  - Transpose: (A^T)_ij = A_ji (flip across diagonal)
- **Special matrices**: identity, diagonal, triangular, symmetric
  - Identity I: diagonal of 1s, IA = AI = A
  - Diagonal: non-zero only on diagonal
  - Triangular: upper or lower triangle is zero
  - Symmetric: A^T = A (important for eigenvalues)
- **Elementary row operations**: Tools for solving systems
  - Row swapping, scalar multiplication, row addition
  - Don't change solution set
  - Correspond to multiplication by elementary matrices
- **Row echelon and reduced row echelon form**: Simplified matrix forms
  - REF: leading entries step down to right
  - RREF: leading entries are 1, only entry in column
  - Gaussian elimination produces REF
  - Gauss-Jordan produces RREF
- **Matrix inverses and invertibility conditions**: A^(-1) such that AA^(-1) = I
  - Exists only if det(A) ≠ 0 (non-singular)
  - Can solve Ax = b by x = A^(-1)b
  - (AB)^(-1) = B^(-1)A^(-1)

**Systems of Linear Equations**
- **Gaussian elimination**: Forward elimination to REF
  - Systematically eliminate variables
  - Back substitution to find solutions
- **Gauss-Jordan elimination**: Continue to RREF
  - Solutions can be read directly
  - Useful for finding inverses
- **Matrix equations Ax = b**: Compact representation of linear system
  - Each row is an equation
  - Solution set: unique, infinite, or no solutions
- **Homogeneous and non-homogeneous systems**: b = 0 vs b ≠ 0
  - Homogeneous always has trivial solution x = 0
  - Non-trivial solutions when det(A) = 0
  - General solution = particular + homogeneous solutions
- **Rank and nullity**: rank(A) + nullity(A) = n
  - Rank: dimension of column space (number of pivot columns)
  - Nullity: dimension of null space
  - Rank-nullity theorem

**Determinants**
- **Cofactor expansion**: Recursive computation of det(A)
  - Along any row or column
  - det(A) = Σ a_ij C_ij
  - Cofactor C_ij = (-1)^(i+j) M_ij
- **Properties of determinants**: det(AB) = det(A)det(B)
  - det(A^T) = det(A)
  - Row swap changes sign
  - Scalar multiplication: det(cA) = c^n det(A)
- **Cramer's rule**: Solve Ax = b using determinants
  - x_i = det(A_i)/det(A)
  - A_i has column i replaced by b
  - Inefficient for large systems
- **Geometric interpretation (area/volume)**: |det(A)| = scale factor
  - 2×2: area of parallelogram formed by columns
  - 3×3: volume of parallelepiped
  - Measures how transformation changes volumes

**Eigenvalues & Eigenvectors**
- **Characteristic equation**: det(A - λI) = 0
  - Polynomial equation for eigenvalues λ
  - n×n matrix has n eigenvalues (counting multiplicity)
- **Eigenspaces**: Null space of (A - λI)
  - All eigenvectors for eigenvalue λ
  - Plus zero vector
- **Diagonalization**: A = PDP^(-1)
  - P has eigenvectors as columns
  - D is diagonal matrix of eigenvalues
  - Only possible if n linearly independent eigenvectors exist
- **Similar matrices**: B = P^(-1)AP
  - Same eigenvalues
  - Represent same transformation in different bases
- **Applications**: differential equations, Markov chains
  - Solutions to systems of ODEs: x' = Ax
  - Steady-state of Markov processes
  - Google PageRank algorithm
  - Principal Component Analysis (PCA)

**Vector Spaces**
- **Subspaces and span**: Closed under addition and scalar multiplication
  - Must contain zero vector
  - Span: all linear combinations of vectors
  - Column space, row space, null space are subspaces
- **Linear independence**: No vector is combination of others
  - Σc_i v_i = 0 only if all c_i = 0
  - Maximum independent set in span is basis
- **Basis and dimension**: Minimal spanning set
  - Linearly independent and spans space
  - All bases have same size = dimension
  - Standard basis: e_1, e_2, ..., e_n
- **Row space, column space, null space**: Fundamental subspaces
  - Row space: span of rows = Col(A^T)
  - Column space: span of columns, range of transformation
  - Null space: solutions to Ax = 0, kernel of transformation
- **Rank-nullity theorem**: rank(A) + nullity(A) = n
  - Dimension formula for linear transformations
  - dim(range) + dim(kernel) = dim(domain)

**Linear Transformations**
- **Definition and properties**: T(cu + dv) = cT(u) + dT(v)
  - Preserves vector space structure
  - Examples: rotations, reflections, projections, scaling
- **Matrix representation**: [T(v)]_B = [T]_B [v]_B
  - Every linear transformation has matrix representation
  - Matrix columns are images of basis vectors
- **Kernel and range**: ker(T) = {v : T(v) = 0}, range(T) = {T(v) : v in V}
  - Kernel measures what gets mapped to zero
  - Range is set of all outputs
  - Both are subspaces
- **Isomorphisms**: One-to-one and onto linear transformations
  - Preserves vector space structure perfectly
  - Inverse transformation exists
  - Spaces are "essentially the same"
- **Change of basis**: Converting coordinates between bases
  - Change of basis matrix [id]_{B→C}
  - [v]_C = P [v]_B where P has basis vectors

**Inner Product Spaces**
- **Inner products and norms**: Generalizes dot product
  - <u,v> satisfies positivity, linearity, symmetry
  - Norm: ||v|| = √<v,v> (length)
  - Defines angles and orthogonality
- **Orthogonal and orthonormal bases**: <e_i, e_j> = δ_ij
  - Orthogonal: perpendicular vectors
  - Orthonormal: orthogonal with unit length
  - Coordinates: [v]_B = <v, e_i>
- **Gram-Schmidt orthogonalization**: Convert basis to orthonormal
  - Subtract projections iteratively
  - v_k⊥ = v_k - Σproj_{u_j}(v_k)
  - Normalize: u_k = v_k⊥/||v_k⊥||
- **QR factorization**: A = QR
  - Q has orthonormal columns (from Gram-Schmidt)
  - R is upper triangular
  - Useful for solving least squares
- **Least squares approximation**: Best fit when Ax = b has no solution
  - Minimize ||Ax - b||²
  - Solution: x̂ = (A^T A)^(-1) A^T b
  - Normal equations: A^T Ax = A^T b
  - Used in linear regression
- **Spectral theorem**: Symmetric matrices are orthogonally diagonalizable
  - A = QDQ^T where Q is orthogonal
  - Eigenvalues are real
  - Eigenvectors for distinct eigenvalues are orthogonal

**Conceptual Insights**:
- Vectors represent directed quantities in n-dimensional space
- Matrices encode linear transformations between vector spaces
- Solving Ax=b is central to countless applications
- Eigenvalues reveal invariant directions under transformation
- Orthogonality minimizes distance and error
- Abstract vector spaces unify geometry, function spaces, and more

**Key Applications**: Computer graphics (3D transformations), data science (PCA, dimensionality reduction), quantum mechanics (state vectors), machine learning (neural networks), Google PageRank, image compression, cryptography

### 3. Differential Equations
Equations describing how quantities change - the language of dynamic systems. Differential equations model everything from population growth to quantum mechanics:

**First Order ODEs**
- **Separable equations**: dy/dx = f(x)g(y)
  - Rearrange to g(y)dy = f(x)dx
  - Integrate both sides
  - Most common elementary type
- **Linear first order equations with integrating factors**: dy/dx + P(x)y = Q(x)
  - Multiply by μ(x) = e^(∫P(x)dx)
  - Left side becomes d/dx[μy]
  - Integrate and divide by μ
- **Exact equations and exactness test**: M(x,y)dx + N(x,y)dy = 0
  - Exact if ∂M/∂y = ∂N/∂x
  - Solution is φ(x,y) = C where dφ = Mdx + Ndy
  - Find φ by integrating M or N
- **Bernoulli equations**: dy/dx + P(x)y = Q(x)y^n
  - Nonlinear but can be linearized
  - Substitution v = y^(1-n) transforms to linear
- **Homogeneous equations with substitution**: M and N are same degree
  - Substitution v = y/x reduces to separable
  - dy/dx = f(y/x)
- **Initial value problems**: Specify y(x_0) = y_0
  - Determines unique solution from general solution
  - C is determined by initial condition
- **Existence and uniqueness (Picard's theorem)**: Conditions for unique solution
  - Continuous f and Lipschitz condition guarantee unique solution
  - May not exist or be unique otherwise
- **Direction fields and slope fields**: Visual representation of solutions
  - Plot small line segments with slope f(x,y)
  - Solutions follow flow of field
  - Qualitative understanding without solving

**Second Order ODEs**
- **Homogeneous equations with constant coefficients**: ay'' + by' + cy = 0
  - Try solution y = e^(rx)
  - Leads to characteristic equation
- **Characteristic equation**: ar² + br + c = 0
  - Real distinct roots: y = c_1 e^(r_1 x) + c_2 e^(r_2 x)
  - Repeated root: y = (c_1 + c_2 x) e^(rx)
  - Complex roots r = α ± βi: y = e^(αx)(c_1 cos(βx) + c_2 sin(βx))
- **Euler-Cauchy equations**: x²y'' + axy' + by = 0
  - Try y = x^r
  - Indicial equation for r
  - Variable coefficients but solvable
- **Non-homogeneous equations**: ay'' + by' + cy = f(x)
  - General solution = homogeneous + particular
  - y = y_h + y_p
- **Method of undetermined coefficients**: Guess form of y_p
  - For polynomial, exponential, sin/cos right-hand sides
  - Guess based on f(x) form
  - Modify if guess solves homogeneous equation
- **Variation of parameters with Wronskian**: General method for y_p
  - y_p = u_1 y_1 + u_2 y_2 where u_i determined by formulas
  - Wronskian W = y_1 y_2' - y_2 y_1'
  - Works for any f(x)

**Higher Order ODEs & Systems**
- **Constant coefficient equations**: Extend second-order methods
  - Characteristic equation is higher degree polynomial
  - Same cases: distinct, repeated, complex roots
- **Systems of ODEs in matrix form**: x' = Ax
  - Vector of functions x = [x_1, ..., x_n]^T
  - A is coefficient matrix
  - Compact representation of coupled equations
- **Eigenvalue method for solutions**: x = e^(λt) v
  - Eigenvalues of A determine exponential growth rates
  - Eigenvectors determine directions
  - General solution is linear combination
- **Phase portraits and stability analysis**: Visualize solution behavior
  - Phase plane for 2D systems
  - Classify equilibria: stable, unstable, saddle
  - Eigenvalues determine stability

**Laplace Transform**
- **Definition and properties**: L{f(t)} = ∫_0^∞ e^(-st) f(t) dt
  - Converts differential equations to algebraic equations
  - Linearity: L{af + bg} = aL{f} + bL{g}
  - Useful for discontinuous forcing functions
- **Transforms of derivatives**: L{f'} = sL{f} - f(0)
  - L{f''} = s²L{f} - sf(0) - f'(0)
  - Reduces order, incorporates initial conditions
- **Shifting theorems**: First and second shifting
  - First: L{e^(at)f(t)} = F(s-a)
  - Second: L{u(t-a)f(t-a)} = e^(-as)F(s) (unit step)
- **Inverse Laplace transform with partial fractions**: Find f(t) from F(s)
  - Decompose rational functions
  - Use table of standard transforms
- **Solving IVPs with Laplace transforms**: Transform, solve algebraically, inverse
  - Initial conditions automatically incorporated
  - Particularly useful for piecewise functions

**Series Solutions**
- **Power series method at ordinary points**: y = Σa_n(x-x_0)^n
  - Substitute into ODE
  - Match coefficients to find recurrence relation
  - Works when coefficients are analytic
- **Frobenius method at singular points**: y = Σa_n x^(n+r)
  - For regular singular points
  - Indicial equation determines r
  - May have logarithmic terms
- **Indicial equation**: Determines exponent r
  - Two solutions if roots differ by non-integer
  - Special cases for repeated or differing-by-integer roots

**Partial Differential Equations**
- **First order PDEs and method of characteristics**: du/dt + c du/dx = 0
  - Transform PDE to ODEs along characteristic curves
  - Solution constant along characteristics
- **Second order classification**: Based on discriminant
  - Elliptic: B²-AC < 0 (steady state, Laplace equation)
  - Parabolic: B²-AC = 0 (diffusion, heat equation)
  - Hyperbolic: B²-AC > 0 (wave propagation, wave equation)
- **Heat equation (parabolic)**: ∂u/∂t = α ∂²u/∂x²
  - Models diffusion, heat flow
  - Solutions smooth out over time
  - Initial value problem
- **Wave equation (hyperbolic)**: ∂²u/∂t² = c² ∂²u/∂x²
  - Models vibrations, electromagnetic waves
  - d'Alembert solution: u = f(x-ct) + g(x+ct)
  - Propagates at speed c
- **Laplace equation (elliptic)**: ∇²u = ∂²u/∂x² + ∂²u/∂y² = 0
  - Models steady-state temperature, electrostatics
  - Boundary value problem
  - Maximum principle: max on boundary
- **Separation of variables**: Assume u(x,t) = X(x)T(t)
  - Converts PDE to ODEs
  - Eigenvalue problems for spatial part
  - Fourier series for general solution
- **Boundary conditions**: Dirichlet, Neumann, Robin
  - Dirichlet: u specified on boundary
  - Neumann: ∂u/∂n specified on boundary
  - Robin: linear combination of u and ∂u/∂n
- **Fourier series solutions**: Represent solution as series
  - u(x,t) = ΣA_n sin(nπx/L) e^(-αn²π²t/L²)
  - Satisfies boundary conditions
  - Coefficients from initial condition

**Numerical Methods**
- **Euler's method (O(h) error)**: y_(n+1) = y_n + h f(t_n, y_n)
  - Simplest method
  - First-order accurate
  - Can be unstable
- **Improved Euler/Heun's method (O(h²) error)**: Predictor-corrector
  - Predict with Euler
  - Correct with average slope
  - Second-order accurate
- **Runge-Kutta methods (RK4 with O(h⁴) error)**: Gold standard
  - Weighted average of slopes at multiple points
  - Fourth-order most common
  - Very accurate, stable
- **Multistep methods**: Use multiple previous points
  - Adams-Bashforth (explicit)
  - Adams-Moulton (implicit)
  - More efficient than single-step
- **Stability and stiff equations**: Numerical stability analysis
  - Stiff: multiple time scales, very different rates
  - Implicit methods better for stiff equations
  - A-stability important

**Applications**
- Physics: Newton's laws, spring-mass systems, pendulums
- Engineering: RLC circuits, beam deflection
- Biology: population dynamics, Lotka-Volterra, SIR models
- Economics: growth models, supply-demand dynamics

**Conceptual Insights**:
- ODEs model systems with one independent variable (usually time)
- PDEs model systems depending on multiple variables (space and time)
- Solutions describe system behavior over time
- Initial/boundary conditions determine unique solutions
- Linear equations allow superposition; nonlinear don't
- Analytical solutions rare; numerical methods essential

**Key Applications**: Physics (Newton's laws, Maxwell's equations, Schrödinger equation), engineering (control systems, signal processing), biology (epidemiology, ecology), chemistry (reaction kinetics), economics (option pricing, growth models)

### 4. Probability & Statistics
The mathematics of uncertainty and data analysis - quantifying randomness and making inferences. Probability and statistics are essential for modern data science and scientific research:

**Probability Theory**
- **Sample spaces, events, and axioms**: Foundation of probability
  - Sample space Ω: set of all possible outcomes
  - Event: subset of sample space
  - Axioms: 0 ≤ P(A) ≤ 1, P(Ω) = 1, P(A∪B) = P(A) + P(B) if disjoint
- **Union, intersection, complement**: Set operations on events
  - Union A∪B: A or B occurs
  - Intersection A∩B: both A and B occur
  - Complement A^c: A does not occur
  - De Morgan's laws
- **Conditional probability P(A|B)**: Probability of A given B occurred
  - P(A|B) = P(A∩B)/P(B)
  - Updates probability with new information
  - Fundamental for inference
- **Bayes' Theorem**: P(A|B) = P(B|A)P(A)/P(B)
  - Reverse conditional probabilities
  - Foundation of Bayesian statistics
  - Update prior beliefs with evidence
- **Law of Total Probability**: P(B) = ΣP(B|A_i)P(A_i)
  - Partition sample space
  - Weighted average over scenarios
- **Independence**: P(A∩B) = P(A)P(B)
  - Knowing B doesn't change probability of A
  - Conditional independence important in practice
- **Counting principles**: permutations, combinations, inclusion-exclusion
  - Permutations: ordered arrangements P(n,r) = n!/(n-r)!
  - Combinations: unordered selections C(n,r) = n!/[r!(n-r)!]
  - Inclusion-exclusion: P(A∪B) = P(A) + P(B) - P(A∩B)
- **Tree diagrams**: Visual representation of sequential events
  - Branches show conditional probabilities
  - Multiply along paths
  - Add across scenarios

**Random Variables**
- **Discrete vs continuous random variables**: Countable vs uncountable values
  - Discrete: X takes isolated values (0, 1, 2, ...)
  - Continuous: X takes values in intervals
  - Different probability frameworks
- **Probability mass function (PMF)**: p(x) = P(X=x) for discrete
  - Gives exact probabilities
  - Σp(x) = 1
  - Bar chart representation
- **Probability density function (PDF)**: f(x) for continuous
  - P(a ≤ X ≤ b) = ∫_a^b f(x)dx
  - f(x) ≥ 0, ∫_{-∞}^∞ f(x)dx = 1
  - f(x) is not a probability (can exceed 1)
- **Cumulative distribution function (CDF)**: F(x) = P(X ≤ x)
  - Non-decreasing, right-continuous
  - F(-∞) = 0, F(∞) = 1
  - P(a < X ≤ b) = F(b) - F(a)
  - F'(x) = f(x) for continuous
- **Expected value E[X]**: Long-run average
  - Discrete: E[X] = Σx·p(x)
  - Continuous: E[X] = ∫x·f(x)dx
  - Center of mass of distribution
  - Linearity: E[aX+b] = aE[X]+b
- **Variance Var(X) and standard deviation σ**: Measure of spread
  - Var(X) = E[(X-μ)²] = E[X²] - (E[X])²
  - Standard deviation σ = √Var(X)
  - Units same as X
  - Var(aX+b) = a²Var(X)
- **Law of Unconscious Statistician**: E[g(X)] = Σg(x)p(x)
  - Compute expectation of function without finding its distribution
  - E[X²] = Σx²p(x)

**Discrete Distributions**
- **Bernoulli**: single trial
  - P(X=1) = p, P(X=0) = 1-p
  - Models success/failure
  - E[X] = p, Var(X) = p(1-p)
- **Binomial**: n trials, P(X=k) = C(n,k)p^k(1-p)^(n-k)
  - Number of successes in n independent Bernoulli trials
  - E[X] = np, Var(X) = np(1-p)
  - Sum of n independent Bernoulli(p)
- **Geometric**: first success, memoryless property
  - Number of trials until first success
  - P(X=k) = (1-p)^(k-1)p
  - E[X] = 1/p, Var(X) = (1-p)/p²
  - Memoryless: P(X>n+k|X>n) = P(X>k)
- **Poisson**: λ rate, P(X=k) = e^(-λ)λ^k/k!
  - Number of events in fixed time/space
  - Approximates binomial when n large, p small, np=λ
  - E[X] = Var(X) = λ
  - Models rare events

**Continuous Distributions**
- **Uniform**: constant PDF
  - f(x) = 1/(b-a) for x in [a,b]
  - E[X] = (a+b)/2, Var(X) = (b-a)²/12
  - All intervals of same length equally likely
- **Exponential**: memoryless, λe^(-λx)
  - Time until event in Poisson process
  - CDF: F(x) = 1 - e^(-λx)
  - E[X] = 1/λ, Var(X) = 1/λ²
  - Memoryless continuous analog of geometric
- **Normal**: N(μ,σ²), bell curve
  - f(x) = (1/√(2πσ²))e^(-(x-μ)²/(2σ²))
  - Symmetric around mean μ
  - 68-95-99.7 rule (μ±σ, μ±2σ, μ±3σ)
  - Most important distribution in statistics
- **Standard normal Z ~ N(0,1)**: Standardized normal
  - Z = (X-μ)/σ
  - Table lookups for probabilities
  - All normal distributions reduce to standard
- **Central Limit Theorem**: Sample means approach normal
  - ΣX_i/n → N(μ, σ²/n) as n→∞
  - Explains ubiquity of normal distribution
  - Works for any distribution (with finite variance)
  - Foundation of statistical inference
- **Chi-square χ²**: Sum of squared normals
  - χ²_k = Z_1² + ... + Z_k²
  - Used in goodness-of-fit, independence tests
  - Asymmetric, positive values only
- **Student's t-distribution**: For small samples
  - Symmetric, heavier tails than normal
  - Approaches normal as df→∞
  - Used when σ unknown
- **F-distribution**: Ratio of chi-squares
  - Used in ANOVA, regression
  - F = (χ²_1/df_1)/(χ²_2/df_2)
  - Always positive

**Multivariate Distributions**
- **Joint PDF/PMF**: Probability for multiple random variables
  - f(x,y) gives probability density at (x,y)
  - ∬ f(x,y)dxdy = 1
  - P((X,Y) in region) = ∬_region f(x,y)dxdy
- **Marginal distributions**: Distribution of one variable
  - f_X(x) = ∫f(x,y)dy (integrate out other variables)
  - Recover individual distributions from joint
- **Covariance and correlation ρ**: Measure linear relationship
  - Cov(X,Y) = E[(X-E[X])(Y-E[Y])] = E[XY] - E[X]E[Y]
  - Correlation ρ = Cov(X,Y)/(σ_Xσ_Y)
  - -1 ≤ ρ ≤ 1, ρ=0 means uncorrelated
  - Independence ⇒ uncorrelated, but not converse
- **Multivariate normal**: Generalizes normal to multiple dimensions
  - Characterized by mean vector and covariance matrix
  - Marginals are normal
  - Linear combinations are normal
- **Covariance matrix**: Σ_ij = Cov(X_i, X_j)
  - Symmetric, positive semi-definite
  - Diagonal entries are variances
  - Determines shape of multivariate normal

**Descriptive Statistics**
- **Central tendency**: mean, median, mode
  - Mean: arithmetic average, sensitive to outliers
  - Median: middle value, robust to outliers
  - Mode: most frequent value
- **Dispersion**: range, variance, IQR
  - Range: max - min
  - Variance: average squared deviation from mean
  - IQR: Q3 - Q1, middle 50% of data
- **Sample mean and sample variance s²**: Estimates from data
  - Sample mean x̄ = Σx_i/n
  - Sample variance s² = Σ(x_i - x̄)²/(n-1)
  - Divide by n-1 (Bessel's correction) for unbiased estimate
- **Distribution shape**: skewness, kurtosis
  - Skewness: asymmetry (positive = right tail)
  - Kurtosis: tail heaviness
  - Normal has skewness=0, kurtosis=3

**Statistical Inference - Estimation**
- **Point estimation**: unbiased, consistent, efficient
  - Unbiased: E[θ̂] = θ
  - Consistent: θ̂ → θ as n→∞
  - Efficient: minimum variance among unbiased estimators
- **Maximum Likelihood Estimation (MLE)**: Maximize likelihood function
  - L(θ) = ∏p(x_i|θ)
  - Usually maximize log-likelihood
  - Asymptotically efficient and normal
- **Method of moments**: Match sample and population moments
  - Set sample mean = E[X], solve for parameters
  - Simple but less efficient than MLE
- **Confidence intervals with confidence level (1-α)**: Range for parameter
  - Interpretation: (1-α)×100% of intervals contain true parameter
  - NOT probability that parameter is in interval
  - Wider intervals have higher confidence
- **CI for mean**: x̄ ± t(α/2) · s/√n
  - t-distribution with n-1 degrees of freedom
  - Use z for large n or known σ
  - Margin of error decreases with √n
- **CI for proportion**: p̂ ± z(α/2) √(p̂(1-p̂)/n)
  - p̂ = x/n (sample proportion)
  - Requires np̂, n(1-p̂) ≥ 10

**Hypothesis Testing**
- **Null hypothesis H₀ vs alternative H₁**: Competing claims
  - H₀: status quo, no effect
  - H₁: what we want to show
  - Burden of proof on rejecting H₀
- **Test statistic and p-value**: Evidence against H₀
  - Test statistic: standardized measure from data
  - p-value: probability of observing data (or more extreme) if H₀ true
  - Small p-value is evidence against H₀
- **Significance level α (typically 0.05)**: Threshold for rejection
  - Reject H₀ if p-value < α
  - Predetermined before seeing data
  - Common: 0.10, 0.05, 0.01
- **Type I error (false positive, α) and Type II error (false negative, β)**: Decision errors
  - Type I: reject true H₀ (probability = α)
  - Type II: fail to reject false H₀ (probability = β)
  - Trade-off between types
- **Power = 1 - β**: Probability of detecting true effect
  - Increases with sample size, effect size
  - Decreases with smaller α
- **Z-test, t-test (one-sample, two-sample, paired)**: Testing means
  - Z-test: σ known or large n
  - t-test: σ unknown, small to moderate n
  - One-sample: test if μ = μ₀
  - Two-sample: test if μ₁ = μ₂
  - Paired: test if mean difference = 0
- **Chi-square tests**: goodness of fit, independence
  - Goodness of fit: does data fit distribution?
  - Independence: are variables independent in contingency table?
  - χ² = Σ(O-E)²/E

**Regression Analysis**
- **Simple linear regression**: Y = β₀ + β₁X + ε
  - Models linear relationship between variables
  - β₀: intercept, β₁: slope
  - ε: random error, E[ε]=0
- **Least squares method**: Minimize Σ(y_i - ŷ_i)²
  - β̂₁ = Σ(x_i-x̄)(y_i-ȳ)/Σ(x_i-x̄)²
  - β̂₀ = ȳ - β̂₁x̄
  - Best linear unbiased estimator (BLUE)
- **R² coefficient of determination**: Proportion of variance explained
  - R² = 1 - SS_res/SS_tot
  - 0 ≤ R² ≤ 1
  - R² = 1: perfect fit, R² = 0: no linear relationship
- **Residual analysis**: Check model assumptions
  - Residuals e_i = y_i - ŷ_i
  - Should be normally distributed, mean 0, constant variance
  - Plot residuals vs fitted values
- **Multiple regression**: Y = β₀ + β₁X₁ + ... + βₚXₚ + ε
  - Multiple predictor variables
  - Matrix formulation: β̂ = (X^TX)^(-1)X^Ty
  - Adjusted R² accounts for number of predictors
- **Logistic regression for binary outcomes**: log(p/(1-p)) = β₀ + β₁X
  - Y is binary (0/1)
  - Models probability of success
  - p = e^(β₀+β₁X)/(1 + e^(β₀+β₁X))

**ANOVA**
- **One-way and two-way ANOVA**: Compare means across groups
  - One-way: one factor (e.g., treatment)
  - Two-way: two factors (e.g., treatment and gender)
  - Tests if group means are equal
- **F-statistic**: Ratio of between-group to within-group variance
  - F = MS_between/MS_within
  - Large F is evidence of differences
  - Follows F-distribution under H₀
- **Comparing multiple means**: Post-hoc tests
  - Bonferroni, Tukey HSD corrections
  - Control family-wise error rate

**Advanced Topics**
- **Bayesian statistics**: prior, likelihood, posterior
  - Prior: initial belief about parameter
  - Likelihood: data given parameter
  - Posterior ∝ likelihood × prior (Bayes' theorem)
  - Update beliefs with data
- **Conjugate priors**: Prior and posterior in same family
  - Beta-Binomial, Normal-Normal, Gamma-Poisson
  - Simplifies computation
- **Non-parametric methods**: No distribution assumptions
  - Wilcoxon: alternative to t-test
  - Kruskal-Wallis: alternative to ANOVA
  - Bootstrap: resample data to estimate distributions
- **Time series**: ARIMA, stationarity
  - Autocorrelation: correlation with lagged values
  - Stationarity: mean, variance constant over time
  - ARIMA: AutoRegressive Integrated Moving Average
- **Survival analysis**: Kaplan-Meier, Cox regression
  - Time until event (death, failure)
  - Censoring: incomplete observations
  - Kaplan-Meier: non-parametric survival curve
  - Cox: proportional hazards model

**Conceptual Insights**:
- Probability quantifies uncertainty using axioms
- Random variables map outcomes to numbers
- Expected value is long-run average
- Central Limit Theorem explains why normal distribution is ubiquitous
- Statistical inference uses samples to learn about populations
- p-values quantify evidence against null hypothesis
- Bayesian methods incorporate prior knowledge

**Key Applications**: Data science (machine learning, A/B testing), finance (risk management, portfolio optimization), medicine (clinical trials, epidemiology), physics (quantum mechanics, statistical mechanics), insurance (actuarial science), quality control, polling

### 5. Discrete Mathematics
The mathematics of discrete structures - foundational to computer science and algorithmic thinking. Discrete math deals with countable, distinct objects rather than continuous quantities:

**Logic & Proofs**
- **Propositional logic**: ¬, ∧, ∨, →, ↔
  - Propositions: statements that are true or false
  - Negation ¬, conjunction ∧ (and), disjunction ∨ (or)
  - Implication → (if-then), biconditional ↔ (if and only if)
  - Foundation for all mathematical reasoning
- **Truth tables**: Systematic evaluation of logical formulas
  - List all possible combinations of truth values
  - Determine output for each combination
  - Verify logical equivalences
- **Logical equivalence and tautologies**: Always-true formulas
  - Tautology: true for all truth assignments
  - Contradiction: always false
  - Equivalence: same truth table
- **De Morgan's Laws**: ¬(p∧q) ≡ ¬p∨¬q, ¬(p∨q) ≡ ¬p∧¬q
  - Distribute negation over and/or
  - Fundamental for simplifying logic
- **Predicate logic with quantifiers ∀, ∃**: Logic with variables
  - Universal ∀x P(x): "for all x, P(x) is true"
  - Existential ∃x P(x): "there exists x such that P(x)"
  - More expressive than propositional logic
- **Proof techniques**: direct, contrapositive, contradiction, induction, cases
  - Direct: assume hypothesis, derive conclusion
  - Contrapositive: prove ¬q→¬p instead of p→q
  - Contradiction: assume ¬(conclusion), derive contradiction
  - Cases: break into exhaustive cases
- **Mathematical induction**: base case, inductive step, strong induction
  - Prove P(1), then P(k)→P(k+1)
  - Concludes P(n) for all n≥ 1
  - Strong: assume P(1),...,P(k) to prove P(k+1)

**Set Theory**
- **Set notation and membership**: {elements}, x ∈ A
  - Set: collection of distinct objects
  - Element ∈ means "is a member of"
  - Empty set ∅
- **Subsets and power sets**: A ⊆ B, P(A)
  - A ⊆ B: every element of A is in B
  - Power set P(A): set of all subsets of A
  - |P(A)| = 2^|A|
- **Set operations**: union, intersection, complement, difference, Cartesian product
  - Union A∪B: elements in A or B
  - Intersection A∩B: elements in both
  - Complement A^c: elements not in A
  - Difference A\B: elements in A but not B
  - Cartesian product A×B: ordered pairs (a,b)
- **Venn diagrams**: Visual representation of sets
  - Overlapping circles show relationships
  - Useful for understanding operations
- **Cardinality**: |A| = number of elements
  - Finite vs infinite cardinality
  - Different sizes of infinity
- **Binary relations**: R ⊆ A×B
  - Reflexive: xRx for all x
  - Symmetric: xRy ⇒ yRx
  - Transitive: xRy and yRz ⇒ xRz
  - Antisymmetric: xRy and yRx ⇒ x=y
- **Equivalence relations and equivalence classes**: Partition sets
  - Equivalence: reflexive, symmetric, transitive
  - Equivalence class [x]: all y with xRy
  - Partitions set into disjoint classes
- **Partial orders, posets, Hasse diagrams**: Ordering with incomparables
  - Partial order: reflexive, antisymmetric, transitive
  - Poset: set with partial order
  - Hasse diagram: visual representation
- **Functions**: injective, surjective, bijective, inverse, composition
  - Injective (1-1): distinct inputs → distinct outputs
  - Surjective (onto): every output is hit
  - Bijective: both injective and surjective
  - Inverse f^(-1): reverses function
  - Composition f∘g: apply g then f

**Combinatorics**
- **Addition and multiplication principles**: Basic counting rules
  - Addition: mutually exclusive choices, add counts
  - Multiplication: independent choices, multiply counts
  - Foundation for all counting
- **Pigeonhole principle**: n+1 items in n holes ⇒ some hole has ≥2 items
  - Guarantees existence, not construction
  - Generalized: kn+1 items ⇒ some hole has ≥k+1
- **Permutations**: P(n,r) = n!/(n-r)!
  - Ordered arrangements of r items from n
  - Order matters
  - P(n,n) = n!
- **Combinations**: C(n,r) = n!/[r!(n-r)!]
  - Unordered selections of r items from n
  - Order doesn't matter
  - C(n,r) = C(n,n-r)
- **Circular permutations**: (n-1)!/2 for arrangements in circle
  - Rotations are equivalent
  - Reflections may also be equivalent
- **Permutations and combinations with repetition**: Modified formulas
  - Permutations with repetition: n^r
  - Combinations with repetition: C(n+r-1,r)
- **Pascal's triangle**: C(n,r) arranged in triangle
  - Each entry = sum of two above
  - C(n,r) = C(n-1,r-1) + C(n-1,r)
- **Binomial theorem**: (x+y)^n = ΣC(n,k)x^k y^(n-k)
  - Expansion of powers
  - Coefficients are binomial coefficients
- **Generating functions**: ordinary and exponential
  - Encode sequences as power series
  - Operations on functions ↔ operations on sequences
  - Powerful tool for solving recurrences
- **Recurrence relations**: linear recurrence, characteristic equation
  - a_n = f(a_(n-1), a_(n-2), ...)
  - Linear: a_n = c_1 a_(n-1) + c_2 a_(n-2) + ...
  - Characteristic equation gives closed form
- **Fibonacci sequence**: F_n = F_(n-1) + F_(n-2), F_0=0, F_1=1
  - Classic example of recurrence
  - Appears throughout mathematics and nature
  - Closed form: F_n = (φ^n - ψ^n)/√5 where φ=(1+√5)/2

**Graph Theory**
- **Graphs G = (V,E)**: vertices and edges
  - V: set of vertices (nodes)
  - E: set of edges (connections)
  - Models pairwise relationships
- **Adjacency and degree**: deg(v) = number of edges incident to v
  - Adjacent vertices: connected by edge
  - Degree: number of neighbors
  - Isolated vertex: degree 0
- **Handshaking lemma**: Σdeg(v) = 2|E|
  - Sum of degrees = twice number of edges
  - Even number of odd-degree vertices
- **Graph representation**: adjacency matrix, adjacency list
  - Matrix: A_ij = 1 if edge (i,j), O(n²) space
  - List: for each vertex, list neighbors, O(n+m) space
  - Trade-off between space and query time
- **Types**: undirected, directed (digraph), weighted, simple, multigraph
  - Undirected: edges have no direction
  - Directed: edges have direction (arrows)
  - Weighted: edges have values
  - Simple: no loops or multiple edges
  - Multigraph: allows multiple edges between vertices
- **Paths and cycles**: Sequence of vertices connected by edges
  - Path: vertices all distinct (except possibly first=last)
  - Cycle: closed path (first = last)
  - Length: number of edges
- **Connected graphs**: Path exists between every pair of vertices
  - Disconnected: separate components
  - Strongly connected (digraphs): directed path both ways
- **Euler paths/circuits (all edges once)**: Traverse every edge exactly once
  - Euler path exists ↔ 0 or 2 odd-degree vertices
  - Euler circuit exists ↔ all vertices even degree
  - Königsberg bridge problem
- **Hamiltonian paths/cycles (all vertices once)**: Visit every vertex exactly once
  - No simple characterization (NP-complete)
  - Traveling salesman problem
- **Trees**: connected acyclic graphs, |E| = |V| - 1
  - No cycles
  - Unique path between any two vertices
  - n-1 edges for n vertices
  - Hierarchical structure
- **Binary trees**: full, complete
  - Each node has ≤2 children
  - Full: every node has 0 or 2 children
  - Complete: all levels full except possibly last
- **Tree traversal**: preorder, inorder, postorder
  - Preorder: root, left, right
  - Inorder: left, root, right (sorted for BST)
  - Postorder: left, right, root
- **Spanning trees and minimum spanning trees**: Connect all vertices
  - Spanning tree: subgraph that's a tree
  - MST: spanning tree with minimum total weight
  - Unique if all edge weights distinct
- **Kruskal's and Prim's algorithms**: Finding MST
  - Kruskal: sort edges, add if doesn't create cycle
  - Prim: grow tree from starting vertex
  - Both O(E log V) with good data structures
- **Graph traversal**: BFS (breadth-first), DFS (depth-first)
  - BFS: explore by distance from start (queue)
  - DFS: explore as far as possible first (stack)
  - BFS finds shortest unweighted paths
- **Dijkstra's algorithm for shortest path**: Weighted shortest path
  - Single-source shortest paths
  - Greedy algorithm
  - O(E log V) with priority queue
  - Requires non-negative weights
- **Floyd-Warshall for all pairs shortest paths**: Every pair of vertices
  - Dynamic programming
  - O(V³) time
  - Works with negative weights (no negative cycles)
- **Graph coloring and chromatic number**: Assign colors to vertices
  - Adjacent vertices get different colors
  - Chromatic number χ(G): minimum colors needed
  - Applications: scheduling, register allocation
- **Four color theorem**: Any planar graph can be colored with 4 colors
  - Proved using computers
  - One of most famous theorems
- **Planar graphs and Euler's formula**: v - e + f = 2
  - Planar: can be drawn without edge crossings
  - v vertices, e edges, f faces (regions)
  - K_5 and K_{3,3} not planar

**Algorithms**
- **Computational complexity**: Big O, Ω, Θ notation
  - Big O: upper bound (worst case)
  - Big Ω: lower bound (best case)
  - Big Θ: tight bound (average case)
  - Describes growth rate as input size → ∞
- **Complexity classes**: P, NP, NP-complete
  - P: solvable in polynomial time
  - NP: verifiable in polynomial time
  - NP-complete: hardest problems in NP
  - P vs NP: biggest open problem in CS
- **Sorting**: bubble sort O(n²), merge sort O(n log n), quick sort
  - Bubble: repeatedly swap adjacent if out of order
  - Merge: divide-and-conquer, stable
  - Quick: partition around pivot, average O(n log n)
  - Lower bound for comparison sorts: Ω(n log n)
- **Searching**: binary search O(log n)
  - Binary: halve search space each step
  - Requires sorted array
  - Logarithmic is very fast
- **Divide and conquer**: Break into subproblems, combine solutions
  - Merge sort, quick sort
  - Binary search
  - Recurrence relations: Master theorem
- **Greedy algorithms**: activity selection, Huffman coding
  - Make locally optimal choice at each step
  - Activity selection: choose earliest ending activity
  - Huffman: optimal prefix-free codes for compression
  - Not always optimal, but often works
- **Dynamic programming**: 0/1 knapsack, longest common subsequence, memoization
  - Store solutions to subproblems
  - Avoid recomputation
  - Memoization (top-down) vs tabulation (bottom-up)
  - Optimal substructure and overlapping subproblems required

**Conceptual Insights**:
- Logic provides rigorous framework for mathematical reasoning
- Proof techniques establish truth beyond computation
- Combinatorics counts arrangements and selections
- Graphs model relationships between objects
- Algorithms solve computational problems efficiently
- Complexity theory classifies problem difficulty
- P vs NP is central unsolved problem

**Key Applications**: Computer science (algorithms, data structures, databases), cryptography (RSA, blockchain), network analysis (social networks, internet routing), optimization (scheduling, resource allocation), artificial intelligence (search, planning), circuit design, coding theory

### 6. Mathematical Logic & Foundations
The foundations of mathematics itself - axioms, proofs, and the limits of formal systems. Logic and foundations examine what can be proven and what mathematics really is:

**Set Theory - Axiomatic**
- **Naive set theory and Russell's paradox**: Unrestricted set formation leads to contradiction
  - Russell's paradox: R = {x : x ∉ x}, does R ∈ R?
  - Shows need for axiomatic foundation
  - Can't allow arbitrary set definitions
- **ZFC axioms**: Zermelo-Fraenkel with Choice
  - Extensionality: sets equal if same elements
  - Pairing: {a, b} exists
  - Union: ∪A exists
  - Power set: P(A) exists
  - Infinity: ℕ exists
  - Replacement: image of set under function is set
  - Foundation: no infinite descending membership chains
  - Axiom of choice: can choose from each set in collection
- **Equivalents to axiom of choice**: Zorn's lemma, well-ordering theorem
  - Zorn: every chain has upper bound ⇒ maximal element exists
  - Well-ordering: every set can be well-ordered
  - All logically equivalent to AC
- **Cardinal numbers**: finite and infinite (ℵ₀, ℵ₁, ...)
  - Measure "size" of sets
  - Two sets same cardinality if bijection exists
  - Aleph numbers for infinite cardinals
- **Countable infinity ℵ₀ = |ℕ|**: Smallest infinite cardinal
  - ℤ, ℚ are countable
  - Union of countably many countable sets is countable
- **Continuum |ℝ| = 2^ℵ₀**: Size of real numbers
  - Cantor's diagonal argument: ℝ uncountable
  - Strictly larger than ℵ₀
- **Continuum hypothesis**: Is there a cardinality between ℵ₀ and 2^ℵ₀?
  - CH: 2^ℵ₀ = ℵ₁ (no intermediate size)
  - Independent of ZFC (Gödel, Cohen)
- **Cantor's theorem**: |A| < |P(A)|
  - Power set always strictly larger
  - Infinitely many infinite cardinals
  - No largest cardinal
- **Ordinal numbers and transfinite induction**: Well-ordered position
  - Extends natural numbers beyond infinity
  - ω = first infinite ordinal
  - ω+1, ω+2, ..., ω·2, ..., ω², ..., ωω, ...
  - Transfinite induction generalizes mathematical induction

**Number Theory**
- **Divisibility and division algorithm**: a = bq + r, 0 ≤ r < b
  - a divides b: a|b means b = ak for some k
  - Division algorithm: unique quotient and remainder
- **Greatest common divisor (GCD) and Euclidean algorithm**: Largest common divisor
  - gcd(a,b) = largest d with d|a and d|b
  - Euclidean algorithm: gcd(a,b) = gcd(b, a mod b)
  - Terminates in O(log min(a,b)) steps
- **Bézout's identity**: gcd(a,b) = ax + by
  - GCD is linear combination of a and b
  - x, y found by extended Euclidean algorithm
  - Basis for solving linear Diophantine equations
- **Least common multiple (LCM)**: Smallest common multiple
  - lcm(a,b) = ab/gcd(a,b)
  - lcm(a,b)·gcd(a,b) = ab
- **Prime numbers and fundamental theorem of arithmetic**: Unique factorization
  - Prime: p > 1 with only divisors 1 and p
  - Every n > 1 factors uniquely into primes
  - Foundation of number theory
- **Infinitude of primes (Euclid's proof)**: Infinitely many primes exist
  - Assume finitely many, multiply and add 1
  - Contradiction: new prime or existing prime divides 1
- **Prime number theorem**: π(x) ~ x/ln(x)
  - π(x) = number of primes ≤ x
  - Asymptotic density of primes
  - Proved independently by Hadamard and de la Vallée Poussin (1896)
- **Sieve of Eratosthenes**: Algorithm to find primes
  - Cross out multiples of each prime
  - Remaining numbers are prime
  - Ancient algorithm (200 BC)
- **Modular arithmetic and congruence a ≡ b (mod n)**: Arithmetic mod n
  - a ≡ b (mod n) if n|(a-b)
  - Forms equivalence classes
  - Addition, multiplication well-defined
- **Fermat's Little Theorem**: a^(p-1) ≡ 1 (mod p) if p prime, p∤a
  - Consequence of Lagrange's theorem from group theory
  - Basis for primality testing
  - Used in RSA
- **Euler's theorem and Euler's totient φ(n)**: Generalization of Fermat
  - φ(n) = number of integers ≤ n coprime to n
  - a^φ(n) ≡ 1 (mod n) if gcd(a,n) = 1
  - φ(p) = p-1 for prime p
- **Chinese Remainder Theorem**: Solve system of congruences
  - If n_i pairwise coprime, system x ≡ a_i (mod n_i) has unique solution mod ∏n_i
  - Constructive algorithm
  - Used in RSA and error-correcting codes
- **RSA cryptography**: Public-key encryption
  - Based on difficulty of factoring
  - Public key (n,e), private key (n,d)
  - Encrypt: c = m^e mod n, Decrypt: m = c^d mod n
- **Diophantine equations**: linear, Pythagorean triples
  - Integer solutions to polynomial equations
  - Linear: ax + by = c solvable iff gcd(a,b)|c
  - Pythagorean triples: x²+y²=z², e.g., (3,4,5)
- **Fermat's Last Theorem**: x^n + y^n = z^n has no integer solutions for n>2
  - Conjectured by Fermat (1637)
  - Proved by Andrew Wiles (1995)
  - One of most famous theorems

**Mathematical Induction**
- **Principle of induction**: base case + inductive step
  - Prove P(1) is true
  - Prove P(k) ⇒ P(k+1) for all k≥1
  - Conclude P(n) true for all n≥1
- **Inductive hypothesis**: Assume P(k) when proving P(k+1)
  - Bridge from base to all cases
  - Critical step in inductive proofs
- **Strong induction**: Assume P(1),...,P(k) to prove P(k+1)
  - More powerful assumption
  - Sometimes easier than weak induction
  - Logically equivalent to weak induction
- **Structural induction on trees and lists**: Induction on recursive structures
  - Base: empty list or leaf
  - Inductive: assume for substructures
  - Natural for recursive definitions
- **Well-ordering principle**: Every non-empty subset of ℕ has a minimum
  - Fundamental property of natural numbers
  - Enables proof by minimal counterexample
- **Equivalence between induction and well-ordering**: Different formulations, same power
  - Can prove each from the other
  - Both characterize natural numbers

**Formal Systems**
- **Axiomatic method**: axioms, deduction rules, theorems
  - Axioms: assumed true statements
  - Deduction rules: how to derive new statements
  - Theorems: derived statements
  - Foundation of modern mathematics
- **Examples**: Euclidean geometry, non-Euclidean geometry
  - Euclid's axioms (including parallel postulate)
  - Hyperbolic: parallel postulate fails
  - Different geometries are consistent
- **Proof theory**: formal proofs, consistency, completeness
  - Formal proof: sequence of formulas
  - Consistency: no contradictions
  - Completeness: all truths are provable
- **Consistency proofs**: Show system has no contradictions
  - Relative consistency: if A consistent, so is B
  - Absolute consistency harder
- **Gödel's completeness theorem (1930)**: First-order logic complete
  - Every valid formula is provable
  - Semantic truth = syntactic provability
  - For first-order logic only
- **Model theory**: interpretation, models, soundness
  - Model: structure satisfying axioms
  - Interpretation: assignment of meaning
  - Soundness: provable ⇒ true in all models
- **Gödel's incompleteness theorems**: Limits of formal systems
  - First: unprovable truths exist in sufficiently strong systems
    - Any consistent system containing arithmetic has true but unprovable statements
    - "This statement is not provable"
  - Second: system cannot prove its own consistency
    - Must go outside system to prove consistency
  - Revolutionary for mathematics and logic
- **Implications for mathematics and computation**: Fundamental limitations
  - No complete algorithmic solution to all math problems
  - Limits of formal verification
  - Philosophy: mathematics not just mechanical
- **Computability theory**: Turing machines, Church-Turing thesis, decidability, halting problem
  - Turing machine: idealized computer
  - Church-Turing thesis: effective computation = Turing computation
  - Decidable: algorithm exists to solve
  - Halting problem: can't determine if program halts
  - Some problems are undecidable
- **Recursive functions and recursive sets**: Computable functions and sets
  - Recursive function: can be computed by algorithm
  - Recursive set: membership is decidable
  - Recursively enumerable: can list elements

**Conceptual Insights**:
- Set theory provides foundation for all mathematics
- Axiom of choice is independent of other ZFC axioms
- Different sizes of infinity exist (countable vs uncountable)
- Number theory studies properties of integers
- Modular arithmetic forms foundation of cryptography
- Mathematical induction proves statements for all natural numbers
- Gödel's theorems show limits of formal systems
- Some mathematical truths cannot be proven within a system
- Halting problem proves computation has fundamental limits

**Key Applications**: Mathematical foundations (philosophy of mathematics), cryptography (RSA, elliptic curves), computer science (computability, complexity theory), logic programming, formal verification, automated theorem proving, theoretical computer science

## 🔗 Interconnections
- Calculus and linear algebra are foundational for all applied mathematics
- Differential equations model change in science and engineering
- Probability/statistics underpin data science and uncertainty
- Discrete math and logic are essential for computer science
- Mathematical logic provides rigor and structure for proofs

## 💡 Learning Path
1. Start with **Calculus** and **Linear Algebra**
2. Move to **Differential Equations**
3. Study **Probability & Statistics**
4. Explore **Discrete Mathematics**
5. Finish with **Mathematical Logic & Foundations**

## 🎓 Why This Matters
Mathematics is the language of science, technology, and engineering. It enables:
- Modeling and solving real-world problems
- Data analysis and prediction
- Design of algorithms and computer systems
- Understanding of physical laws and abstract structures
- Critical thinking and logical reasoning

---

## 🔢 Key Concepts & Equations

### Calculus
- **Limit**: $\lim_{x \to a} f(x)$
- **Derivative**: $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$
- **Integral**: $\int_a^b f(x) dx$
- **Fundamental Theorem**: $\frac{d}{dx} \int_a^x f(t) dt = f(x)$
- **Chain Rule**: $\frac{d}{dx} f(g(x)) = f'(g(x))g'(x)$
- **Taylor Series**: $f(x) = \sum_{n=0}^\infty \frac{f^{(n)}(a)}{n!}(x-a)^n$

### Linear Algebra
- **Matrix Multiplication**: $AB_{ij} = \sum_k A_{ik}B_{kj}$
- **Determinant**: $|A|$
- **Inverse**: $A^{-1}$ if $|A| \neq 0$
- **Eigenvalue Equation**: $Av = \lambda v$
- **Dot Product**: $\vec{a} \cdot \vec{b} = \sum a_i b_i$
- **Cross Product**: $\vec{a} \times \vec{b}$

### Differential Equations
- **First Order ODE**: $\frac{dy}{dx} + P(x)y = Q(x)$
- **Separation of Variables**: $\frac{dy}{dx} = f(x)g(y)$
- **Characteristic Equation**: $ay'' + by' + cy = 0$
- **Laplace Transform**: $F(s) = \int_0^\infty e^{-st}f(t)dt$

### Probability & Statistics
- **Probability**: $P(A) = \frac{\text{Number of favorable outcomes}}{\text{Total outcomes}}$
- **Expected Value**: $E[X] = \sum x_i P(x_i)$
- **Variance**: $Var(X) = E[(X - E[X])^2]$
- **Normal Distribution**: $f(x) = \frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$
- **Bayes' Theorem**: $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

### Discrete Mathematics
- **Logic**: $p \rightarrow q$, $\neg p$, $p \wedge q$, $p \vee q$
- **Proof by Induction**: Base case, inductive step
- **Permutations**: $n!$
- **Combinations**: $\binom{n}{k} = \frac{n!}{k!(n-k)!}$
- **Graph**: $G = (V, E)$
- **Euler's Formula**: $V - E + F = 2$ (for planar graphs)

### Mathematical Logic & Foundations
- **Set**: $A = \{x | x \text{ has property } P\}$
- **Function**: $f: A \rightarrow B$
- **Cardinality**: $|A|$
- **Modular Arithmetic**: $a \equiv b \pmod{n}$
- **Peano Axioms**: Foundation for natural numbers

---

## 📊 Important Constants & Symbols
- $\pi \approx 3.14159$
- $e \approx 2.71828$
- $i = \sqrt{-1}$
- $\infty$: Infinity
- $\emptyset$: Empty set
- $\forall$: For all
- $\exists$: There exists
- $\sum$: Summation
- $\int$: Integral
- $\partial$: Partial derivative
- $\nabla$: Gradient
- $\Delta$: Change/difference
- $\lim$: Limit

---

## 🔗 Further Reading
- Calculus: Stewart, Spivak
- Linear Algebra: Strang, Axler
- Differential Equations: Boyce & DiPrima
- Probability/Statistics: Ross, Freedman
- Discrete Math: Rosen
- Logic/Foundations: Enderton, Suppes
