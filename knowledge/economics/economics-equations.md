# Economics Equations & Formulas

## 📈 Microeconomics

### Supply and Demand
- **Demand function**: $Q_d = a - bP$ (linear) or $Q_d = AP^{-\epsilon}$ (constant elasticity)
- **Supply function**: $Q_s = c + dP$
- **Equilibrium**: $Q_d = Q_s$; solve for $P^*$ and $Q^*$
- **Consumer surplus**: $CS = \int_0^{Q^*} D(Q)\,dQ - P^*Q^*$
- **Producer surplus**: $PS = P^*Q^* - \int_0^{Q^*} S(Q)\,dQ$
- **Total surplus**: $TS = CS + PS$ (maximized at competitive equilibrium)

### Elasticity
- **Price elasticity of demand**: $E_d = \frac{\% \Delta Q_d}{\% \Delta P} = \frac{dQ}{dP} \cdot \frac{P}{Q}$
  - $|E_d| > 1$: elastic; $|E_d| < 1$: inelastic; $|E_d| = 1$: unit elastic
- **Income elasticity**: $E_I = \frac{\% \Delta Q}{\% \Delta I}$
  - Normal good: $E_I > 0$; Inferior good: $E_I < 0$; Luxury: $E_I > 1$
- **Cross-price elasticity**: $E_{xy} = \frac{\% \Delta Q_x}{\% \Delta P_y}$
  - Substitutes: $E_{xy} > 0$; Complements: $E_{xy} < 0$

### Consumer Theory
- **Budget constraint**: $P_x X + P_y Y = I$ (income)
- **Marginal rate of substitution**: $MRS = \frac{MU_x}{MU_y} = \frac{P_x}{P_y}$ (at optimum)
- **Utility maximization**: $\max U(x,y)$ subject to $P_x x + P_y y \leq I$
- **Lagrangian**: $\mathcal{L} = U(x,y) + \lambda(I - P_x x - P_y y)$

### Production and Cost
- **Production function**: $Q = f(L, K)$ (labor, capital)
- **Cobb-Douglas**: $Q = AL^\alpha K^\beta$
  - Returns to scale: $\alpha + \beta > 1$ (increasing), $= 1$ (constant), $< 1$ (decreasing)
- **Marginal product**: $MP_L = \frac{\partial Q}{\partial L}$; $MP_K = \frac{\partial Q}{\partial K}$
- **Total cost**: $TC = FC + VC$
- **Average cost**: $AC = \frac{TC}{Q}$; $AVC = \frac{VC}{Q}$; $AFC = \frac{FC}{Q}$
- **Marginal cost**: $MC = \frac{dTC}{dQ} = \frac{dVC}{dQ}$
- **Profit**: $\pi = TR - TC = PQ - TC$
- **Profit maximization**: $MR = MC$

### Market Structures
- **Perfect competition**: $P = MC = MR$; zero economic profit in long run
- **Monopoly**: $MR = MC$; $MR = P\left(1 + \frac{1}{E_d}\right)$; deadweight loss
- **Monopolistic competition**: Short-run profit; long-run $P = ATC$
- **Oligopoly (Cournot)**: Each firm: $\frac{\partial \pi_i}{\partial q_i} = 0$; Nash equilibrium

## 📊 Macroeconomics

### National Income Accounting
- **GDP (expenditure)**: $Y = C + I + G + NX$
  - $C$ = consumption, $I$ = investment, $G$ = government, $NX$ = net exports
- **GDP (income)**: $Y = W + R + i + \pi$ (wages, rent, interest, profit)
- **Real vs Nominal**: $\text{Real GDP} = \frac{\text{Nominal GDP}}{\text{GDP Deflator}} \times 100$
- **GDP growth rate**: $g = \frac{Y_t - Y_{t-1}}{Y_{t-1}} \times 100\%$
- **GDP per capita**: $\frac{Y}{N}$ (GDP / population)

### Inflation
- **CPI**: $\text{CPI} = \frac{\text{Cost of basket (current)}}{\text{Cost of basket (base)}} \times 100$
- **Inflation rate**: $\pi = \frac{\text{CPI}_t - \text{CPI}_{t-1}}{\text{CPI}_{t-1}} \times 100\%$
- **Real interest rate (Fisher)**: $r \approx i - \pi$ (nominal rate − inflation)
  - Exact: $(1+r) = \frac{1+i}{1+\pi}$
- **Quantity theory of money**: $MV = PY$
  - $M$ = money supply, $V$ = velocity, $P$ = price level, $Y$ = real output

### Unemployment
- **Unemployment rate**: $u = \frac{U}{L} \times 100\%$ ($L$ = labor force = employed + unemployed)
- **Labor force participation**: $\frac{L}{\text{Working-age population}} \times 100\%$
- **Okun's Law**: $\Delta u \approx -\frac{1}{2}(\Delta Y\% - 3\%)$
  - 1% above trend growth ≈ 0.5% reduction in unemployment

### Multiplier Effect
- **Simple spending multiplier**: $k = \frac{1}{1 - MPC}$ where $MPC$ = marginal propensity to consume
  - $\Delta Y = k \cdot \Delta G$ (or $\Delta I$)
- **Tax multiplier**: $k_{tax} = \frac{-MPC}{1 - MPC}$
- **Balanced budget multiplier**: $k_{BB} = 1$ (equal increase in $G$ and $T$)
- **With taxes**: $k = \frac{1}{1 - MPC(1-t)}$ ($t$ = tax rate)

### IS-LM Model
- **IS curve** (goods market): $Y = C(Y-T) + I(r) + G$; downward sloping in $(Y, r)$
- **LM curve** (money market): $\frac{M}{P} = L(r, Y)$; upward sloping in $(Y, r)$
- **Equilibrium**: Intersection of IS and LM
- **Fiscal policy**: Shifts IS (government spending, taxes)
- **Monetary policy**: Shifts LM (money supply)

### Solow Growth Model
- **Production**: $Y = AF(K, L)$ (A = technology)
- **Per worker**: $y = Af(k)$ where $k = K/L$
- **Capital accumulation**: $\Delta k = sf(k) - (\delta + n + g)k$
  - $s$ = savings rate, $\delta$ = depreciation, $n$ = population growth, $g$ = tech growth
- **Steady state**: $sf(k^*) = (\delta + n + g)k^*$
- **Golden rule**: $f'(k^*) = \delta + n + g$ (maximizes consumption)

### Phillips Curve
- **Short-run**: $\pi = \pi^e - \beta(u - u_n) + \nu$
  - $\pi^e$ = expected inflation, $u_n$ = natural rate, $\nu$ = supply shock
- **Long-run**: Vertical at $u = u_n$ (no trade-off)

## 💰 Finance

### Time Value of Money
- **Future value**: $FV = PV(1 + r)^n$
- **Present value**: $PV = \frac{FV}{(1 + r)^n}$
- **Annuity (PV)**: $PV = PMT \cdot \frac{1 - (1+r)^{-n}}{r}$
- **Annuity (FV)**: $FV = PMT \cdot \frac{(1+r)^n - 1}{r}$
- **Perpetuity**: $PV = \frac{PMT}{r}$
- **Growing perpetuity**: $PV = \frac{PMT}{r - g}$ (if $r > g$)

### Compound Interest
- **Discrete**: $A = P\left(1 + \frac{r}{n}\right)^{nt}$
  - $P$ = principal, $r$ = annual rate, $n$ = compounding frequency, $t$ = years
- **Continuous**: $A = Pe^{rt}$
- **Rule of 72**: Doubling time $\approx \frac{72}{r\%}$ years
- **Effective annual rate**: $EAR = \left(1 + \frac{r}{n}\right)^n - 1$

### Bond Valuation
- **Bond price**: $P = \sum_{t=1}^{n} \frac{C}{(1+r)^t} + \frac{F}{(1+r)^n}$
  - $C$ = coupon payment, $F$ = face value, $r$ = yield to maturity
- **Current yield**: $\frac{C}{P}$
- **Duration**: Weighted average time of cash flows

### Stock Valuation
- **Dividend discount**: $P_0 = \frac{D_1}{r - g}$ (Gordon growth model; $r > g$)
  - $D_1$ = next dividend, $r$ = required return, $g$ = growth rate
- **P/E ratio**: $\frac{\text{Price}}{\text{Earnings per share}}$
- **CAPM**: $E(R_i) = R_f + \beta_i[E(R_m) - R_f]$
  - $R_f$ = risk-free rate, $\beta$ = systematic risk, $R_m$ = market return

### Portfolio Theory
- **Expected return**: $E(R_p) = \sum w_i E(R_i)$
- **Portfolio variance (2 assets)**: $\sigma_p^2 = w_1^2\sigma_1^2 + w_2^2\sigma_2^2 + 2w_1w_2\sigma_1\sigma_2\rho_{12}$
- **Sharpe ratio**: $S = \frac{E(R_p) - R_f}{\sigma_p}$ (risk-adjusted return)
- **Diversification**: $\rho < 1$ reduces portfolio risk

## 🏦 Monetary Economics

- **Money multiplier**: $m = \frac{1}{rr}$ ($rr$ = reserve ratio)
  - $\Delta M = m \cdot \Delta \text{Reserves}$
- **Taylor Rule**: $i = r^* + \pi + 0.5(\pi - \pi^*) + 0.5(y - y^*)$
  - Target rate based on inflation gap and output gap
- **Exchange rate (PPP)**: $e = \frac{P_{domestic}}{P_{foreign}}$
- **Interest rate parity**: $(1+i_d) = \frac{F}{S}(1+i_f)$ ($F$ = forward, $S$ = spot)

## 📉 Game Theory

- **Nash Equilibrium**: No player can improve by unilaterally changing strategy
- **Dominant strategy**: Best regardless of others' choices
- **Prisoner's Dilemma**: Individual rationality → suboptimal collective outcome
- **Expected payoff**: $E(\pi) = \sum p_i \cdot \pi_i$
