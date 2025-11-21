# Mathematics Terminology

## Core Concepts from Mathematics Mindmaps

### Calculus
- **Limit**: Value that a function approaches as the input approaches a point
- **Continuity**: Property of a function having no breaks, jumps, or holes
- **Derivative**: Rate of change of a function; slope of tangent line
- **Differentiation**: Process of finding a derivative
- **Integral**: Accumulated sum; area under a curve
- **Integration**: Process of finding an integral
- **Definite Integral**: Integral with specified upper and lower bounds
- **Indefinite Integral**: Antiderivative; integral without bounds
- **Fundamental Theorem of Calculus**: Links differentiation and integration
- **Chain Rule**: Method for differentiating composite functions
- **Product Rule**: Rule for differentiating products of functions
- **Quotient Rule**: Rule for differentiating quotients of functions
- **Implicit Differentiation**: Finding derivatives of implicitly defined functions
- **Related Rates**: Problems involving rates of change of related quantities
- **Optimization**: Finding maximum or minimum values of functions
- **Critical Point**: Point where derivative is zero or undefined
- **Inflection Point**: Point where concavity changes

#### Limits and Continuity
- **Limit Definition**: lim(x→a) f(x) = L if f(x) approaches L as x approaches a
- **Epsilon-Delta Definition**: Rigorous formulation; for every ε > 0, exists δ > 0
- **One-Sided Limit**: Left-hand limit (x→a⁻) and right-hand limit (x→a⁺)
- **Infinite Limit**: lim(x→∞) or vertical asymptotes
- **Limit Properties**: Sum, product, quotient rules for combining limits
- **Removable Discontinuity**: Hole in graph; limit exists but f(a) undefined or different
- **Jump Discontinuity**: Left and right limits exist but are different
- **Infinite Discontinuity**: Vertical asymptote
- **Intermediate Value Theorem**: Continuous function takes all values between f(a) and f(b)
- **Extreme Value Theorem**: Continuous function on closed interval has maximum and minimum

#### Differentiation
- **Derivative Definition**: f'(x) = lim(h→0) [f(x+h) - f(x)]/h
- **Geometric Meaning**: Slope of tangent line at a point
- **Power Rule**: d/dx(xⁿ) = nxⁿ⁻¹
- **Product Rule**: (uv)' = u'v + uv'
- **Quotient Rule**: (u/v)' = (u'v - uv')/v²
- **Chain Rule**: d/dx f(g(x)) = f'(g(x)) · g'(x)
- **Logarithmic Differentiation**: Use ln to simplify before differentiating
- **Higher Order Derivatives**: f'', f''', fⁿ
- **Tangent Line**: y - y₀ = m(x - x₀) where m = f'(x₀)
- **First Derivative Test**: Determines increasing/decreasing and local extrema
- **Second Derivative Test**: Determines concavity and inflection points
- **Mean Value Theorem**: f'(c) = [f(b) - f(a)]/(b - a) for some c in (a,b)
- **L'Hôpital's Rule**: For indeterminate forms 0/0 or ∞/∞

#### Integration
- **Antiderivative**: Function F where F'(x) = f(x)
- **Indefinite Integral**: ∫f(x)dx = F(x) + C
- **Definite Integral**: ∫ᵃᵇ f(x)dx; represents area under curve
- **Fundamental Theorem Part 1**: d/dx ∫ᵃˣ f(t)dt = f(x)
- **Fundamental Theorem Part 2**: ∫ᵃᵇ f(x)dx = F(b) - F(a)
- **u-Substitution**: ∫f(g(x))g'(x)dx = ∫f(u)du where u = g(x)
- **Integration by Parts**: ∫udv = uv - ∫vdu
- **Partial Fractions**: Decompose rational functions for integration
- **Trigonometric Substitution**: Handle radicals using trig identities
- **Accumulation Function**: A(x) = ∫ᵃˣ f(t)dt
- **Area Between Curves**: ∫[f(x) - g(x)]dx
- **Volume of Revolution**: Disk, washer, and shell methods
- **Arc Length**: ∫√(1 + [f'(x)]²)dx
- **Work**: W = ∫F(x)dx
- **Improper Integral**: Infinite limits or discontinuities

#### Sequences and Series
- **Sequence**: Ordered list aₙ
- **Convergence**: lim(n→∞) aₙ exists and is finite
- **Infinite Series**: ∑(n=1 to ∞) aₙ
- **Geometric Series**: ∑arⁿ = a/(1-r) if |r| < 1
- **Comparison Test**: Compare with known convergent/divergent series
- **Ratio Test**: lim |aₙ₊₁/aₙ|; converges if < 1, diverges if > 1
- **Root Test**: lim |aₙ|^(1/n); converges if < 1, diverges if > 1
- **Integral Test**: Compare series to improper integral
- **Alternating Series Test**: Leibniz criterion for alternating series
- **Power Series**: ∑cₙ(x-a)ⁿ; function represented as infinite polynomial
- **Radius of Convergence**: Interval where power series converges
- **Taylor Series**: f(x) = ∑[fⁿ(a)/n!](x-a)ⁿ; polynomial approximation
- **Maclaurin Series**: Taylor series at a = 0
- **Common Series**: eˣ, sin(x), cos(x), ln(1+x)

#### Multivariable Calculus
- **Functions of Several Variables**: f(x,y,z) with multiple independent variables
- **Partial Derivative**: ∂f/∂x; derivative with respect to one variable, others constant
- **Higher Order Partials**: fₓₓ, fₓᵧ, fᵧᵧ; mixed partials
- **Clairaut's Theorem**: fₓᵧ = fᵧₓ if continuous
- **Gradient Vector**: ∇f = ⟨∂f/∂x, ∂f/∂y⟩; points in direction of maximum increase
- **Directional Derivative**: Dᵤf = ∇f · u; rate of change in direction u
- **Chain Rule (Multivariable)**: For composite functions of several variables
- **Tangent Plane**: Linear approximation at a point
- **Critical Points**: Where ∇f = 0
- **Hessian Matrix**: Matrix of second partial derivatives
- **Second Derivative Test**: Uses Hessian determinant D for classification
- **Lagrange Multipliers**: Method for constrained optimization; ∇f = λ∇g
- **Double Integral**: ∬ f(x,y)dA; volume under surface
- **Triple Integral**: ∭ f(x,y,z)dV; mass or charge in region
- **Iterated Integral**: ∫∫f(x,y)dxdy; computed as nested integrals
- **Polar Coordinates**: (r,θ); useful for circular regions
- **Cylindrical Coordinates**: (r,θ,z); useful for cylinders
- **Spherical Coordinates**: (ρ,θ,φ); useful for spheres
- **Jacobian**: det(∂(x,y)/∂(u,v)); for change of variables

#### Vector Calculus
- **Vector Field**: F(x,y,z) = ⟨P,Q,R⟩; assigns vector to each point
- **Curl**: ∇ × F; measures rotation of vector field
- **Divergence**: ∇ · F; measures tendency to flow outward
- **Conservative Field**: ∇f = F for some potential function f
- **Path Independence**: ∫F·dr independent of path for conservative fields
- **Potential Function**: f such that ∇f = F
- **Line Integral**: ∫ᶜ F·dr; work done by force field
- **Surface Integral**: ∬ₛ F·dS; flux through surface
- **Green's Theorem**: ∮ᶜ F·dr = ∬ᴰ (∂Q/∂x - ∂P/∂y)dA
- **Stokes' Theorem**: ∮ᶜ F·dr = ∬ₛ (∇×F)·dS
- **Divergence Theorem**: ∬ₛ F·dS = ∭ᴱ (∇·F)dV; Gauss's theorem

### Linear Algebra
- **Vector**: Mathematical object with magnitude and direction
- **Scalar**: Single numerical value without direction
- **Matrix**: Rectangular array of numbers
- **Linear Transformation**: Function preserving vector addition and scalar multiplication
- **Vector Space**: Set of vectors with defined addition and scalar multiplication
- **Basis**: Set of linearly independent vectors spanning a vector space
- **Dimension**: Number of vectors in a basis
- **Linear Independence**: Vectors where no vector is a linear combination of others
- **Linear Combination**: Sum of scalar multiples of vectors
- **Span**: Set of all linear combinations of a set of vectors
- **Subspace**: Subset of vector space that is itself a vector space
- **Inner Product**: Generalization of dot product
- **Dot Product**: Scalar product of two vectors
- **Cross Product**: Vector product perpendicular to two input vectors
- **Norm**: Measure of vector length or magnitude
- **Orthogonal**: Perpendicular; inner product equals zero
- **Orthonormal**: Orthogonal vectors with unit length
- **Matrix Multiplication**: Combining matrices to produce a new matrix
- **Determinant**: Scalar value encoding properties of a matrix
- **Inverse Matrix**: Matrix that undoes another matrix's transformation
- **Transpose**: Matrix obtained by swapping rows and columns
- **Eigenvalue**: Scalar λ where Av = λv for eigenvector v
- **Eigenvector**: Non-zero vector whose direction is unchanged by transformation
- **Diagonalization**: Expressing matrix in diagonal form using eigenvectors
- **Rank**: Maximum number of linearly independent row or column vectors
- **Null Space**: Set of vectors mapped to zero by a matrix

### Differential Equations
- **Differential Equation**: Equation involving derivatives of unknown function
- **Ordinary Differential Equation (ODE)**: DE with one independent variable
- **Partial Differential Equation (PDE)**: DE with multiple independent variables
- **Order**: Highest derivative appearing in the equation
- **Degree**: Power of highest-order derivative
- **Linear DE**: Equation linear in the unknown function and its derivatives
- **Nonlinear DE**: Equation not linear in the unknown function
- **Initial Value Problem (IVP)**: DE with specified initial conditions
- **Boundary Value Problem (BVP)**: DE with conditions at multiple points
- **Separable Equation**: ODE that can be written as product of functions
- **Homogeneous Equation**: Equation equal to zero
- **Particular Solution**: Specific solution satisfying initial/boundary conditions
- **General Solution**: Family of all solutions
- **Characteristic Equation**: Algebraic equation derived from DE
- **Laplace Transform**: Integral transform used to solve DEs
- **Fourier Series**: Representation of function as sum of sines and cosines
- **Method of Separation of Variables**: Technique for solving PDEs
- **Heat Equation**: PDE describing heat distribution over time
- **Wave Equation**: PDE describing wave propagation
- **Laplace's Equation**: PDE where Laplacian equals zero

### Probability & Statistics
- **Probability**: Measure of likelihood of an event occurring
- **Random Variable**: Variable whose value depends on random phenomena
- **Discrete Random Variable**: Variable taking countable values
- **Continuous Random Variable**: Variable taking values in an interval
- **Probability Distribution**: Function describing probabilities of outcomes
- **Probability Density Function (PDF)**: Function for continuous distributions
- **Probability Mass Function (PMF)**: Function for discrete distributions
- **Cumulative Distribution Function (CDF)**: Probability that variable ≤ value
- **Expected Value (Mean)**: Average value of random variable
- **Variance**: Measure of spread around the mean
- **Standard Deviation**: Square root of variance
- **Normal Distribution**: Bell-shaped continuous probability distribution
- **Binomial Distribution**: Distribution of number of successes in n trials
- **Poisson Distribution**: Distribution of number of events in fixed interval
- **Uniform Distribution**: Distribution where all outcomes equally likely
- **Central Limit Theorem**: Sum of independent variables approaches normal distribution
- **Law of Large Numbers**: Sample average converges to expected value
- **Independence**: Events where occurrence of one doesn't affect the other
- **Conditional Probability**: Probability of event given another event occurred
- **Bayes' Theorem**: Relates conditional probabilities
- **Statistical Inference**: Drawing conclusions from data
- **Hypothesis Testing**: Testing claims about population parameters
- **Confidence Interval**: Range likely to contain population parameter
- **Regression**: Modeling relationship between variables
- **Correlation**: Measure of linear relationship between variables
- **p-value**: Probability of observing data assuming null hypothesis is true

### Discrete Mathematics
- **Logic**: Study of reasoning and argumentation
- **Proposition**: Statement that is either true or false
- **Truth Table**: Table showing truth values for logical expressions
- **Logical Operators**: AND, OR, NOT, IMPLIES, IFF
- **Proof**: Logical argument establishing truth of statement
- **Direct Proof**: Proving statement by logical steps from assumptions
- **Proof by Contradiction**: Assuming negation leads to contradiction
- **Mathematical Induction**: Proof technique for statements about natural numbers
- **Set**: Collection of distinct objects
- **Subset**: Set where all elements are in another set
- **Union**: Set containing all elements from multiple sets
- **Intersection**: Set containing only common elements
- **Complement**: Elements not in a set
- **Cartesian Product**: Set of all ordered pairs from two sets
- **Combinatorics**: Study of counting and arrangement
- **Permutation**: Ordered arrangement of objects
- **Combination**: Selection of objects where order doesn't matter
- **Binomial Coefficient**: Number of ways to choose k items from n
- **Graph**: Structure of vertices connected by edges
- **Vertex**: Node in a graph
- **Edge**: Connection between vertices
- **Path**: Sequence of edges connecting vertices
- **Cycle**: Path that starts and ends at same vertex
- **Tree**: Connected graph with no cycles
- **Algorithm**: Step-by-step procedure for solving a problem
- **Complexity**: Measure of resources required by algorithm (time or space)
- **Big O Notation**: Asymptotic upper bound on algorithm's growth rate
- **Recursion**: Process defined in terms of itself

### Logic & Foundations
- **Set Theory**: Study of sets and their properties
- **Axiom**: Statement accepted as true without proof
- **Theorem**: Statement that has been proven true
- **Lemma**: Preliminary theorem used to prove larger result
- **Corollary**: Result that follows easily from a theorem
- **Cardinality**: Size or number of elements in a set
- **Countable**: Set that can be put in one-to-one correspondence with natural numbers
- **Uncountable**: Set that cannot be counted (e.g., real numbers)
- **Function**: Relation assigning each input exactly one output
- **Bijection**: One-to-one and onto function
- **Injection (One-to-One)**: Function where different inputs have different outputs
- **Surjection (Onto)**: Function where every output is mapped to
- **Number Theory**: Study of properties of integers
- **Prime Number**: Integer greater than 1 divisible only by 1 and itself
- **Composite Number**: Integer greater than 1 that is not prime
- **Greatest Common Divisor (GCD)**: Largest integer dividing two numbers
- **Least Common Multiple (LCM)**: Smallest integer divisible by two numbers
- **Modular Arithmetic**: Arithmetic with remainders
- **Congruence**: a ≡ b (mod n) means n divides (a - b)
- **Euclidean Algorithm**: Method for computing GCD
- **Mathematical Induction**: Proof technique for natural number statements
- **Well-Ordering Principle**: Every non-empty set of natural numbers has a least element
- **Formal System**: Set of axioms and rules for deriving theorems
- **Axiomatic System**: Mathematical theory based on axioms

## Mathematical Structures

### Algebraic Structures
- **Group**: Set with associative binary operation, identity, and inverses
- **Ring**: Set with two operations (addition and multiplication)
- **Field**: Ring where multiplication is commutative with inverses

### Topological Structures
- **Topology**: Study of properties preserved under continuous deformations
- **Open Set**: Set where every point has a neighborhood contained in the set
- **Closed Set**: Set containing all its limit points
- **Compact Set**: Set where every open cover has a finite subcover
- **Connected Set**: Set that cannot be divided into disjoint open sets

## Linear Algebra

### Vectors
- **Vector**: Ordered list of numbers; magnitude and direction
- **Column Vector**: n×1 matrix
- **Row Vector**: 1×n matrix
- **Zero Vector**: All components zero
- **Unit Vector**: Magnitude = 1; often î, ĵ, k̂
- **Position Vector**: From origin to point
- **Vector Addition**: Component-wise; parallelogram law
- **Scalar Multiplication**: Scales magnitude
- **Linear Combination**: c₁v₁ + c₂v₂ + ... + cₙvₙ

### Vector Operations
- **Dot Product**: u·v = u₁v₁ + u₂v₂ + ... + uₙvₙ = |u||v|cos θ
- **Cross Product**: u×v; perpendicular to both; |u×v| = |u||v|sin θ; right-hand rule
- **Norm/Magnitude**: ||v|| = √(v·v) = √(v₁² + v₂² + ... + vₙ²)
- **Distance**: d(u,v) = ||u - v||
- **Angle**: cos θ = (u·v)/(||u|| ||v||)
- **Orthogonal**: u·v = 0; perpendicular
- **Projection**: proj_u v = [(v·u)/(u·u)]u

### Matrices
- **Matrix**: Rectangular array of numbers; m×n (rows × columns)
- **Square Matrix**: m = n
- **Identity Matrix (I)**: Diagonal 1s, rest 0s; AI = IA = A
- **Diagonal Matrix**: Non-zero only on main diagonal
- **Zero Matrix**: All entries 0
- **Transpose (Aᵀ)**: Rows become columns; (Aᵀ)ᵀ = A
- **Symmetric**: A = Aᵀ
- **Skew-Symmetric**: A = -Aᵀ
- **Upper Triangular**: Zeros below diagonal
- **Lower Triangular**: Zeros above diagonal

### Matrix Operations
- **Addition**: A + B; same dimensions; component-wise
- **Scalar Multiplication**: cA; multiply each entry
- **Matrix Multiplication**: (AB)ᵢⱼ = Σₖ aᵢₖbₖⱼ; (m×n)(n×p) = m×p
- **Not Commutative**: AB ≠ BA in general
- **Associative**: (AB)C = A(BC)
- **Distributive**: A(B+C) = AB + AC
- **Transpose Properties**: (AB)ᵀ = BᵀAᵀ

### Determinants
- **Determinant (det A or |A|)**: Scalar from square matrix
- **2×2**: |[a,b],[c,d]| = ad - bc
- **3×3**: Cofactor expansion along row/column
- **Properties**:
  - det(AB) = det(A)det(B)
  - det(Aᵀ) = det(A)
  - det(A⁻¹) = 1/det(A)
  - det(cA) = cⁿdet(A) for n×n matrix
- **Row Operations**: Row swap changes sign; row scaling multiplies det; row addition doesn't change det
- **Singular Matrix**: det(A) = 0; not invertible
- **Cramer's Rule**: Solve Ax = b using determinants

### Matrix Inverse
- **Inverse (A⁻¹)**: AA⁻¹ = A⁻¹A = I
- **Exists if**: det(A) ≠ 0 (nonsingular)
- **2×2 Inverse**: A⁻¹ = (1/det(A))[d,-b],[-c,a] for A=[a,b],[c,d]
- **Properties**:
  - (A⁻¹)⁻¹ = A
  - (AB)⁻¹ = B⁻¹A⁻¹
  - (Aᵀ)⁻¹ = (A⁻¹)ᵀ

### Systems of Linear Equations
- **Matrix Form**: Ax = b
- **Augmented Matrix**: [A|b]
- **Row Echelon Form (REF)**: Leading entries descend rightward; zero rows at bottom
- **Reduced Row Echelon Form (RREF)**: REF + leading 1s + zeros above/below leading 1s
- **Gaussian Elimination**: Row operations to REF
- **Gauss-Jordan Elimination**: Row operations to RREF
- **Solution Types**: Unique (one), infinite (free variables), no solution (inconsistent)
- **Rank**: Number of non-zero rows in REF; dimension of column/row space
- **Nullity**: Dimension of null space; n - rank

### Vector Spaces
- **Vector Space (V)**: Set with addition and scalar multiplication satisfying axioms
- **Subspace**: Subset that is itself a vector space; closed under operations; contains zero vector
- **Span**: Set of all linear combinations; span{v₁,...,vₙ}
- **Linear Independence**: No vector is a linear combination of others; c₁v₁+...+cₙvₙ=0 implies all c=0
- **Linear Dependence**: At least one vector is a combination of others
- **Basis**: Linearly independent spanning set
- **Dimension**: Number of vectors in basis
- **Standard Basis**: e₁=(1,0,...,0), e₂=(0,1,0,...), etc.

### Eigenvalues and Eigenvectors
- **Eigenvector (v)**: Av = λv for scalar λ; non-zero v
- **Eigenvalue (λ)**: Scalar in Av = λv
- **Characteristic Equation**: det(A - λI) = 0
- **Characteristic Polynomial**: det(A - λI)
- **Algebraic Multiplicity**: Multiplicity of λ as root
- **Geometric Multiplicity**: Dimension of eigenspace
- **Eigenspace**: Null space of (A - λI); all eigenvectors for λ plus zero vector
- **Trace**: tr(A) = sum of diagonal entries = sum of eigenvalues
- **Determinant**: det(A) = product of eigenvalues

### Diagonalization
- **Diagonalizable**: A = PDP⁻¹ where D diagonal, P has eigenvectors as columns
- **Conditions**: n linearly independent eigenvectors for n×n matrix
- **Powers**: Aⁿ = PDⁿP⁻¹; easy to compute
- **Spectral Theorem**: Real symmetric matrix is orthogonally diagonalizable

### Linear Transformations
- **Linear Transformation (T)**: T(u+v) = T(u)+T(v); T(cu) = cT(u)
- **Matrix Representation**: T(x) = Ax
- **Kernel (Null Space)**: {x : T(x) = 0}
- **Range (Column Space)**: {T(x) : x ∈ V}
- **Rank-Nullity Theorem**: dim(V) = rank(T) + nullity(T)
- **One-to-One (Injective)**: T(x) = T(y) implies x = y; kernel = {0}
- **Onto (Surjective)**: Range = codomain
- **Isomorphism**: Bijective linear transformation

### Inner Product Spaces
- **Inner Product**: Generalization of dot product; ⟨u,v⟩
- **Properties**: ⟨u,v⟩ = ⟨v,u⟩; ⟨cu,v⟩ = c⟨u,v⟩; ⟨u+v,w⟩ = ⟨u,w⟩+⟨v,w⟩; ⟨u,u⟩ ≥ 0
- **Norm from Inner Product**: ||v|| = √⟨v,v⟩
- **Cauchy-Schwarz Inequality**: |⟨u,v⟩| ≤ ||u|| ||v||
- **Triangle Inequality**: ||u+v|| ≤ ||u|| + ||v||
- **Orthogonal**: ⟨u,v⟩ = 0
- **Orthonormal**: Orthogonal and each has norm 1
- **Gram-Schmidt Process**: Convert basis to orthonormal basis

### Special Matrices
- **Orthogonal Matrix (Q)**: QᵀQ = QQᵀ = I; columns/rows are orthonormal; preserves lengths/angles
- **Hermitian Matrix**: A = A* (conjugate transpose); real eigenvalues
- **Unitary Matrix (U)**: U*U = I; complex analog of orthogonal
- **Positive Definite**: xᵀAx > 0 for all x ≠ 0; all eigenvalues positive
- **Projection Matrix**: P² = P; projects onto subspace
- **Rotation Matrix**: Orthogonal; det = 1; rotates vectors


## Differential Equations

### Ordinary Differential Equations (ODEs)
- **ODE**: Equation with derivatives of unknown function of one variable
- **Order**: Highest derivative present
- **Degree**: Power of highest derivative (when polynomial)
- **Linear ODE**: Linear in y and its derivatives; no products/powers of y or y'
- **Nonlinear**: Contains y², (y')², yy', sin(y), etc.
- **General Solution**: Contains arbitrary constants (n constants for nth order)
- **Particular Solution**: Specific solution satisfying initial conditions
- **Initial Value Problem (IVP)**: ODE + initial conditions
- **Boundary Value Problem (BVP)**: ODE + conditions at different points

### First-Order ODEs
- **Separable**: dy/dx = g(x)h(y); separate and integrate
- **Linear First-Order**: dy/dx + P(x)y = Q(x)
  - **Integrating Factor**: μ(x) = e^{∫P(x)dx}
  - **Solution**: y = (1/μ)∫μQ dx
- **Exact Equation**: M(x,y)dx + N(x,y)dy = 0 where ∂M/∂y = ∂N/∂x
  - **Solution**: ∫M dx + ∫(terms of N not containing x) dy = C
- **Homogeneous**: dy/dx = F(y/x); substitute v = y/x
- **Bernoulli**: dy/dx + P(x)y = Q(x)y^n; substitute v = y^{1-n}

### Second-Order Linear ODEs
- **Standard Form**: y'' + p(x)y' + q(x)y = r(x)
- **Homogeneous**: r(x) = 0
- **Nonhomogeneous**: r(x) ≠ 0
- **General Solution**: y = y_h + y_p (homogeneous + particular)
- **Superposition**: If y₁, y₂ solve homogeneous, so does c₁y₁ + c₂y₂

### Constant Coefficient ODEs
- **Characteristic Equation**: ar² + br + c = 0 for ay'' + by' + cy = 0
- **Distinct Real Roots (r₁, r₂)**: y_h = c₁e^{r₁x} + c₂e^{r₂x}
- **Repeated Root (r)**: y_h = (c₁ + c₂x)e^{rx}
- **Complex Roots (α ± βi)**: y_h = e^{αx}(c₁cos(βx) + c₂sin(βx))

### Method of Undetermined Coefficients
- **Applies to**: Constant coefficients; r(x) = polynomial, exponential, sine, cosine, or combinations
- **Guess Form**: Match type of r(x)
  - Polynomial: Polynomial same degree
  - e^{ax}: Ae^{ax}
  - sin(bx), cos(bx): Asin(bx) + Bcos(bx)
- **Modification Rule**: If guess solves homogeneous, multiply by x (repeat if needed)

### Variation of Parameters
- **For**: y'' + p(x)y' + q(x)y = r(x) with known y_h = c₁y₁ + c₂y₂
- **Particular Solution**: y_p = u₁y₁ + u₂y₂
- **Formulas**: u₁' = -y₂r/W, u₂' = y₁r/W where W = Wronskian = y₁y₂' - y₂y₁'

### Laplace Transforms
- **Definition**: ℒ{f(t)} = F(s) = ∫₀^∞ e^{-st}f(t)dt
- **Basic Transforms**:
  - ℒ{1} = 1/s
  - ℒ{e^{at}} = 1/(s-a)
  - ℒ{t^n} = n!/s^{n+1}
  - ℒ{sin(at)} = a/(s²+a²)
  - ℒ{cos(at)} = s/(s²+a²)
- **Properties**:
  - Linearity: ℒ{af+bg} = aℒ{f} + bℒ{g}
  - First Derivative: ℒ{f'} = sF(s) - f(0)
  - Second Derivative: ℒ{f''} = s²F(s) - sf(0) - f'(0)
  - Shifting: ℒ{e^{at}f(t)} = F(s-a)
- **Inverse Transform**: ℒ^{-1}{F(s)} = f(t)
- **Convolution**: ℒ{f*g} = F(s)G(s) where (f*g)(t) = ∫₀^t f(τ)g(t-τ)dτ
- **Unit Step**: u_c(t) = 0 for t<c, 1 for t≥c; ℒ{u_c(t)f(t-c)} = e^{-cs}F(s)

### Power Series Solutions
- **Ordinary Point**: Can expand y as power series around x₀
- **Singular Point**: Cannot expand; p(x) or q(x) undefined
- **Regular Singular Point**: x-x₀ divides singularities finitely
- **Method**: Assume y = Σ aₙ(x-x₀)^n; substitute; equate coefficients
- **Radius of Convergence**: Distance to nearest singularity

### Systems of ODEs
- **First-Order System**: x' = Ax + f(t) where x, f vectors, A matrix
- **Homogeneous**: f = 0
- **Eigenvalue Method**: x = ve^{λt}; find eigenvalues/eigenvectors of A
- **Real Distinct Eigenvalues**: x = c₁v₁e^{λ₁t} + c₂v₂e^{λ₂t}
- **Complex Eigenvalues (α±βi)**: Real/imaginary parts of e^{(α+βi)t}v
- **Repeated Eigenvalues**: Generalized eigenvectors

### Partial Differential Equations (PDEs)
- **PDE**: Multiple independent variables; partial derivatives
- **Order**: Highest partial derivative
- **Linear**: Linear in u and all partial derivatives
- **Homogeneous**: = 0
- **Heat Equation**: u_t = α²u_xx; diffusion
- **Wave Equation**: u_tt = c²u_xx; vibrations
- **Laplace's Equation**: u_xx + u_yy = 0; steady-state
- **Separation of Variables**: u(x,t) = X(x)T(t); substitute; separate
- **Fourier Series Solution**: Combine separated solutions with coefficients

### Numerical Methods
- **Euler's Method**: yₙ₊₁ = yₙ + hf(xₙ,yₙ); first-order accuracy
- **Improved Euler (Heun)**: Predictor-corrector; second-order
- **Runge-Kutta (RK4)**: Fourth-order; widely used; accurate
- **Step Size (h)**: Smaller = more accurate but more computation
- **Stability**: Method doesn't amplify errors

## Probability & Statistics

### Probability Basics
- **Sample Space (S)**: Set of all possible outcomes
- **Event (E)**: Subset of sample space
- **Probability P(E)**: 0 ≤ P(E) ≤ 1; P(S) = 1; P(∅) = 0
- **Complement**: P(E^c) = 1 - P(E)
- **Addition Rule**: P(A∪B) = P(A) + P(B) - P(A∩B)
- **Mutually Exclusive**: P(A∩B) = 0; then P(A∪B) = P(A) + P(B)
- **Conditional Probability**: P(A|B) = P(A∩B)/P(B)
- **Independence**: P(A∩B) = P(A)P(B); P(A|B) = P(A)
- **Multiplication Rule**: P(A∩B) = P(A)P(B|A)

### Bayes' Theorem
- **Formula**: P(A|B) = P(B|A)P(A)/P(B)
- **Law of Total Probability**: P(B) = ΣP(B|Aᵢ)P(Aᵢ) for partition {Aᵢ}
- **Posterior Probability**: Update belief given evidence

### Counting
- **Addition Principle**: If A or B, add counts
- **Multiplication Principle**: If A and B in sequence, multiply
- **Permutation**: Ordered arrangements; P(n,r) = n!/(n-r)!
- **Combination**: Unordered selections; C(n,r) = n!/[r!(n-r)!]
- **Binomial Coefficient**: C(n,k) = (n choose k)

### Random Variables
- **Random Variable (RV)**: Function from sample space to real numbers
- **Discrete RV**: Countable values; PMF P(X=x)
- **Continuous RV**: Uncountable; PDF f(x); P(a<X<b) = ∫ₐ^b f(x)dx
- **Cumulative Distribution Function (CDF)**: F(x) = P(X≤x)
- **Expected Value**: E[X] = Σx·P(X=x) or ∫x f(x)dx
- **Variance**: Var(X) = E[(X-μ)²] = E[X²] - (E[X])²
- **Standard Deviation**: σ = √Var(X)

### Discrete Distributions
- **Bernoulli**: One trial; p = P(success)
- **Binomial**: n independent trials; P(X=k) = C(n,k)p^k(1-p)^{n-k}; E[X]=np; Var=np(1-p)
- **Geometric**: Trials until first success; P(X=k) = (1-p)^{k-1}p; E[X]=1/p
- **Poisson**: Events in interval; P(X=k) = (λ^k e^{-λ})/k!; E[X]=Var[X]=λ
- **Hypergeometric**: Sampling without replacement

### Continuous Distributions
- **Uniform**: f(x) = 1/(b-a) on [a,b]; E[X]=(a+b)/2; Var=(b-a)²/12
- **Exponential**: f(x) = λe^{-λx}; memoryless; E[X]=1/λ; Var=1/λ²
- **Normal (Gaussian)**: f(x) = (1/σ√(2π))e^{-(x-μ)²/(2σ²)}; E[X]=μ; Var=σ²
  - **Standard Normal (Z)**: μ=0, σ=1; Z = (X-μ)/σ
  - **68-95-99.7 Rule**: ±1σ, ±2σ, ±3σ
- **Chi-Square (χ²)**: Sum of squared normals; df = degrees of freedom
- **t-Distribution**: Symmetric; heavier tails than normal; approaches normal as df increases
- **F-Distribution**: Ratio of chi-squares; for ANOVA

### Central Limit Theorem (CLT)
- **Statement**: Sample mean X̄ approaches normal as n → ∞, regardless of population distribution
- **Parameters**: E[X̄] = μ; Var(X̄) = σ²/n; SE = σ/√n
- **Rule of Thumb**: n ≥ 30 often sufficient

### Statistical Inference
- **Population**: All individuals of interest
- **Sample**: Subset observed
- **Parameter**: Population characteristic (μ, σ, p)
- **Statistic**: Sample characteristic (x̄, s, p̂)
- **Point Estimate**: Single value estimate
- **Interval Estimate**: Range with confidence level
- **Confidence Interval**: x̄ ± z*(σ/√n) or x̄ ± t*(s/√n)
- **Confidence Level (1-α)**: 90%, 95%, 99% common

### Hypothesis Testing
- **Null Hypothesis (H₀)**: Status quo; assume true
- **Alternative Hypothesis (H₁ or Hₐ)**: What we suspect
- **Test Statistic**: z, t, χ², F, etc.
- **p-value**: P(data or more extreme | H₀ true)
- **Significance Level (α)**: Threshold; 0.05 common
- **Decision**: Reject H₀ if p < α
- **Type I Error (α)**: Reject true H₀; false positive
- **Type II Error (β)**: Fail to reject false H₀; false negative
- **Power (1-β)**: Probability of rejecting false H₀
- **One-Tailed vs Two-Tailed**: Directional vs non-directional H₁

### Common Tests
- **z-Test**: Population σ known; large n
- **t-Test**: Population σ unknown; small n
  - One-Sample: Compare mean to value
  - Two-Sample: Compare two means (paired or independent)
- **χ² Test**: Goodness-of-fit; independence in contingency table
- **ANOVA (F-test)**: Compare ≥3 means
- **Correlation Test**: Is ρ ≠ 0?
- **Regression Test**: Is β ≠ 0?

### Regression and Correlation
- **Linear Regression**: y = β₀ + β₁x + ε
- **Least Squares**: Minimize Σ(yᵢ - ŷᵢ)²
- **Slope**: β₁ = r(s_y/s_x)
- **Intercept**: β₀ = ȳ - β₁x̄
- **Correlation Coefficient (r)**: -1 ≤ r ≤ 1; measures linear association
  - r > 0: Positive; r < 0: Negative; r = 0: No linear relationship
- **Coefficient of Determination (R²)**: r²; proportion of variance explained
- **Residual**: eᵢ = yᵢ - ŷᵢ; error
- **Assumptions**: Linearity, independence, homoscedasticity, normality (LINE)

### ANOVA
- **One-Way ANOVA**: Compare means of ≥3 groups
- **H₀**: μ₁ = μ₂ = ... = μₖ
- **F-statistic**: F = MS_between / MS_within
- **SST**: Total sum of squares = SS_between + SS_within
- **Degrees of Freedom**: df_between = k-1; df_within = n-k; df_total = n-1
- **Post-Hoc Tests**: If reject H₀, determine which means differ (Tukey, Bonferroni)

### Bayesian Statistics
- **Prior**: P(θ) before data
- **Likelihood**: P(data|θ)
- **Posterior**: P(θ|data) ∝ P(data|θ)P(θ)
- **Credible Interval**: Bayesian analog of confidence interval
- **Conjugate Prior**: Posterior same family as prior

### Machine Learning Foundations
- **Supervised Learning**: Labeled data; predict output
  - Classification: Discrete output
  - Regression: Continuous output
- **Unsupervised Learning**: Unlabeled; find patterns
  - Clustering: Group similar data
  - Dimensionality Reduction: Reduce features
- **Training/Test Split**: Evaluate generalization
- **Cross-Validation**: Multiple train/test splits; average performance
- **Overfitting**: Model too complex; fits noise
- **Underfitting**: Model too simple; misses patterns
- **Bias-Variance Tradeoff**: Balance complexity

## Discrete Mathematics

### Logic
- **Proposition**: Statement that is true or false
- **Logical Connectives**: ∧ (and), ∨ (or), ¬ (not), → (implies), ↔ (iff)
- **Truth Table**: Shows truth values for all combinations
- **Tautology**: Always true (e.g., P ∨ ¬P)
- **Contradiction**: Always false (e.g., P ∧ ¬P)
- **Logical Equivalence**: Same truth table; P ≡ Q
- **De Morgan's Laws**: ¬(P∧Q) ≡ ¬P∨¬Q; ¬(P∨Q) ≡ ¬P∧¬Q
- **Contrapositive**: P→Q ≡ ¬Q→¬P
- **Converse**: P→Q vs Q→P (not equivalent)
- **Quantifiers**: ∀ (for all), ∃ (there exists)

### Set Theory
- **Set**: Collection of distinct objects
- **Element**: a ∈ A; a belongs to A
- **Subset**: A ⊆ B; all elements of A in B
- **Proper Subset**: A ⊂ B; A ⊆ B and A ≠ B
- **Empty Set**: ∅ or {}
- **Universal Set**: U; all objects under consideration
- **Union**: A ∪ B = {x : x ∈ A or x ∈ B}
- **Intersection**: A ∩ B = {x : x ∈ A and x ∈ B}
- **Complement**: A^c = {x : x ∉ A}
- **Difference**: A - B = {x : x ∈ A and x ∉ B}
- **Cartesian Product**: A × B = {(a,b) : a ∈ A, b ∈ B}
- **Power Set**: P(A) = all subsets of A; |P(A)| = 2^{|A|}
- **Cardinality**: |A|; number of elements

### Functions and Relations
- **Relation**: Subset of A × B
- **Function**: Each input has exactly one output
- **Injective (One-to-One)**: f(a) = f(b) implies a = b
- **Surjective (Onto)**: Every element of codomain is image
- **Bijective**: Both injective and surjective; has inverse
- **Domain**: Set of inputs
- **Codomain**: Set of possible outputs
- **Range**: Actual outputs; subset of codomain
- **Composition**: (g∘f)(x) = g(f(x))
- **Inverse**: f⁻¹(y) = x if f(x) = y; exists if bijective

### Combinatorics
- **Permutation with Repetition**: n^r; r items from n with replacement
- **Circular Permutation**: (n-1)!; arrange n objects in circle
- **Distinguishable Permutations**: n!/(n₁!n₂!...nₖ!) with repetition
- **Stars and Bars**: Distribute n identical objects into k bins: C(n+k-1, k-1)
- **Inclusion-Exclusion**: |A∪B| = |A| + |B| - |A∩B|
- **Pigeonhole Principle**: n+1 objects in n holes → at least one hole has ≥2 objects
- **Binomial Theorem**: (x+y)^n = Σ C(n,k)x^{n-k}y^k

### Graph Theory
- **Graph G=(V,E)**: Vertices V, Edges E
- **Directed Graph**: Edges have direction
- **Undirected Graph**: Edges bidirectional
- **Degree**: Number of edges at vertex
- **Path**: Sequence of vertices connected by edges
- **Cycle**: Path starting and ending at same vertex
- **Connected**: Path exists between any two vertices
- **Tree**: Connected acyclic graph; |E| = |V| - 1
- **Forest**: Disjoint union of trees
- **Complete Graph K_n**: Edge between every pair of vertices
- **Bipartite**: Vertices partitioned into two sets; edges only between sets
- **Planar**: Can draw without edge crossings
- **Euler Path**: Uses every edge exactly once
- **Euler Circuit**: Euler path that is cycle; exists iff all degrees even
- **Hamiltonian Path**: Visits every vertex exactly once
- **Hamiltonian Cycle**: Hamiltonian path that is cycle

### Algorithms
- **Algorithm**: Step-by-step procedure
- **Big O Notation**: Upper bound on growth rate
  - O(1): Constant
  - O(log n): Logarithmic
  - O(n): Linear
  - O(n log n): Linearithmic
  - O(n²): Quadratic
  - O(2^n): Exponential
- **Sorting**: Bubble, Selection, Insertion, Merge, Quick, Heap
- **Searching**: Linear O(n), Binary O(log n)
- **Greedy Algorithm**: Makes locally optimal choice
- **Dynamic Programming**: Break into subproblems; memoization
- **Divide and Conquer**: Split, solve, combine

## Logic & Foundations

### Number Theory
- **Divisibility**: a|b if b = ka for integer k
- **Prime**: p > 1; only divisors 1 and p
- **Composite**: >1 and not prime
- **Fundamental Theorem of Arithmetic**: Every integer >1 has unique prime factorization
- **GCD (gcd(a,b))**: Greatest common divisor
- **LCM (lcm(a,b))**: Least common multiple
- **Euclidean Algorithm**: gcd(a,b) = gcd(b, a mod b)
- **Relatively Prime**: gcd(a,b) = 1
- **Modular Arithmetic**: a ≡ b (mod m) if m|(a-b)
- **Congruence Classes**: [a]_m = {b : b ≡ a (mod m)}
- **Fermat's Little Theorem**: If p prime, a^p ≡ a (mod p)
- **Euler's Totient Function φ(n)**: Count of integers ≤n relatively prime to n

### Mathematical Induction
- **Principle**: Prove P(1); prove P(k) → P(k+1); conclude P(n) for all n ≥ 1
- **Strong Induction**: Assume P(1),...,P(k) to prove P(k+1)
- **Base Case**: Verify smallest value
- **Inductive Hypothesis**: Assume true for k
- **Inductive Step**: Show true for k+1

### Formal Systems
- **Axioms**: Statements assumed true without proof
- **Theorem**: Proved statement from axioms
- **Lemma**: Minor result aiding larger proof
- **Corollary**: Result following easily from theorem
- **Proof**: Logical argument establishing truth
  - Direct: Assume premises, derive conclusion
  - Indirect (Contradiction): Assume ¬conclusion, derive contradiction
  - Contrapositive: Prove ¬Q → ¬P for P → Q
  - Constructive: Exhibit example
  - Existence: Show something exists without constructing
- **Counterexample**: Shows statement false

### Computability
- **Turing Machine**: Abstract model of computation
- **Decidable**: Algorithm exists to determine membership
- **Undecidable**: No algorithm exists (e.g., Halting Problem)
- **Computable Function**: Can be computed by Turing machine
- **Recursively Enumerable**: Can list members; may not halt on non-members

