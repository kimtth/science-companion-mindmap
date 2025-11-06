```mermaid
flowchart LR
    Start([Thermodynamics]):::blue
    Start --> Temperature["Temperature & Heat<br/>Thermal energy and transfer<br/>Distinguishes hot from cold"]:::lightblue
    Start --> FirstLaw["First Law of Thermodynamics<br/>Energy conservation for thermal systems<br/>ΔU = Q - W relationship"]:::lightblue
    Start --> SecondLaw["Second Law of Thermodynamics<br/>Entropy always increases<br/>Defines direction of processes"]:::lightblue
    Start --> HeatEngines["Heat Engines<br/>Convert thermal to mechanical energy<br/>Limited by Carnot efficiency"]:::lightblue
    
    Temperature --> KineticTheory["Kinetic Theory<br/>Temperature from molecular motion<br/>Links macro and micro properties"]:::paleblue
    Temperature --> HeatTransfer["Heat Transfer<br/>Conduction, convection, radiation<br/>Three modes of thermal energy flow"]:::paleblue
    Temperature --> ThermalExpansion["Thermal Expansion<br/>Size changes with temperature<br/>Important in engineering design"]:::paleblue
    Temperature --> TempScales["Temperature Scales<br/>Celsius, Kelvin, Fahrenheit<br/>Different measurement systems"]:::paleblue
    Temperature --> SpecificHeat["Specific Heat<br/>Heat capacity per unit mass<br/>Q = mcΔT"]:::paleblue
    Temperature --> PhaseChanges["Phase Changes<br/>Solid, liquid, gas transitions<br/>Latent heat"]:::paleblue
    
    KineticTheory --> KTAvgKE["Avg KE = (3/2)kT<br/>Average molecular kinetic energy<br/>Directly proportional to temp"]:::skyblue
    KineticTheory --> KTRMSSpeed["RMS Speed v_rms = √(3kT/m)<br/>Root-mean-square molecular speed<br/>Depends on temperature and mass"]:::skyblue
    KineticTheory --> KTIdealGas["PV = nRT = NkT<br/>Ideal gas law from kinetic theory<br/>Connects macroscopic variables"]:::skyblue
    KineticTheory --> KTMicroMacro["Micro to Macro Connection<br/>Links particle motion to bulk properties<br/>Foundation of statistical mechanics"]:::skyblue
    KineticTheory --> KTMaxwellDist["Maxwell Speed Distribution<br/>Distribution of molecular speeds<br/>Bell-shaped but asymmetric"]:::skyblue
    
    HeatTransfer --> HTConduction["Conduction<br/>Heat flow through materials<br/>No bulk motion of medium"]:::skyblue
    HeatTransfer --> HTConvection["Convection<br/>Heat transfer by fluid motion<br/>Natural or forced circulation"]:::skyblue
    HeatTransfer --> HTRadiation["Radiation<br/>Electromagnetic wave transfer<br/>No medium needed"]:::skyblue
    HeatTransfer --> HTThermalCond["Thermal Conductivity<br/>Material property k<br/>Metals have high k values"]:::skyblue
    
    HTConduction --> HTFourierLaw["Fourier's Law: Q/t = -kA(dT/dx)<br/>Heat flow rate equation<br/>Proportional to temp gradient"]:::skyblue
    HTConduction --> HTThermalRes["Thermal Resistance R = L/(kA)<br/>Analogous to electrical resistance<br/>Higher R means less heat flow"]:::skyblue
    HTConduction --> HTSeries["Series: R_total = ΣR_i<br/>Multiple layers add resistances<br/>Insulation design principle"]:::skyblue
    
    HTRadiation --> HTStefanBoltz["Stefan-Boltzmann: P = σAεT⁴<br/>Radiated power law<br/>σ = 5.67×10⁻⁸ W/(m²·K⁴)"]:::skyblue
    HTRadiation --> HTNetRadiation["Net: P = σAε(T₁⁴ - T₂⁴)<br/>Net heat exchange between bodies<br/>Depends on temp difference"]:::skyblue
    HTRadiation --> HTEmissivity["Emissivity ε (0 to 1)<br/>Surface property for radiation<br/>Black body has ε = 1"]:::skyblue
    
    ThermalExpansion --> TELinear["Linear: ΔL = αL₀ΔT<br/>Length change with temperature<br/>α is coefficient of linear expansion"]:::skyblue
    ThermalExpansion --> TEVolume["Volume: ΔV = βV₀ΔT<br/>Volume change with temperature<br/>β ≈ 3α for solids"]:::skyblue
    ThermalExpansion --> TECoefficients["α (linear), β ≈ 3α<br/>Material-dependent coefficients<br/>Metals expand more than ceramics"]:::skyblue
    ThermalExpansion --> TEBimetallic["Bimetallic Strips<br/>Two metals with different α<br/>Used in thermostats"]:::skyblue
    ThermalExpansion --> TELiquids["Liquid Expansion<br/>Liquids expand more than solids<br/>No fixed shape considerations"]:::skyblue
    
    TELiquids --> TEWaterAnomaly["Water Anomaly (4°C density max)<br/>Water contracts 0-4°C<br/>Ice floats because less dense"]:::skyblue
    TELiquids --> TEAppExpansion["Apparent vs Real Expansion<br/>Container also expands<br/>Measured vs actual expansion differ"]:::skyblue
    
    TempScales --> TSCelsius["Celsius (0°C, 100°C)<br/>Water freezing and boiling<br/>Common in science"]:::skyblue
    TempScales --> TSKelvin["Kelvin (273.15 K, 373.15 K)<br/>Absolute temperature scale<br/>Starts at absolute zero"]:::skyblue
    TempScales --> TSFahrenheit["Fahrenheit (32°F, 212°F)<br/>Used in USA<br/>F = 9/5 C + 32"]:::skyblue
    TempScales --> TSConversion["T(K) = T(°C) + 273.15<br/>Kelvin-Celsius conversion<br/>Zero Kelvin = -273.15°C"]:::skyblue
    TempScales --> TSAbsoluteZero["Absolute Zero: 0 K = -273.15°C<br/>Theoretical lowest temperature<br/>All molecular motion ceases"]:::skyblue
    
    SpecificHeat --> SHCapacity["C = mc (Heat Capacity)<br/>Total heat capacity of object<br/>Extensive property"]:::skyblue
    SpecificHeat --> SHEquation["Q = mcΔT<br/>Heat for temperature change<br/>No phase change"]:::skyblue
    SpecificHeat --> SHMolar["Molar Specific Heats C_v, C_p<br/>At constant volume or pressure<br/>C_p > C_v for gases"]:::skyblue
    SpecificHeat --> SHRatio["γ = C_p / C_v<br/>Heat capacity ratio<br/>1.67 monatomic, 1.4 diatomic"]:::skyblue
    SpecificHeat --> SHCalorimetry["Calorimetry: Q_lost = Q_gained<br/>Energy conservation in mixing<br/>Find unknown specific heats"]:::skyblue
    
    SHMolar --> SHMonatomic["Monatomic: C_v = (3/2)R<br/>Only translational KE<br/>He, Ne, Ar"]:::skyblue
    SHMolar --> SHDiatomic["Diatomic: C_v = (5/2)R<br/>Translation + rotation<br/>N₂, O₂, H₂"]:::skyblue
    SHMolar --> SHMayerRelation["C_p - C_v = R<br/>Relates molar heat capacities<br/>From PV = nRT"]:::skyblue
    
    PhaseChanges --> PCLatentHeat["Latent Heat Q = mL<br/>Energy for phase change<br/>Temperature stays constant"]:::skyblue
    PhaseChanges --> PCFusion["L_f (Fusion/Melting)<br/>Solid to liquid<br/>Water: 334 kJ/kg"]:::skyblue
    PhaseChanges --> PCVaporization["L_v (Vaporization/Boiling)<br/>Liquid to gas<br/>Water: 2260 kJ/kg"]:::skyblue
    PhaseChanges --> PCPhaseDiagram["Phase Diagram (P-T)<br/>Shows phases vs conditions<br/>Triple point and critical point"]:::skyblue
    PhaseChanges --> PCTriplePoint["Triple Point<br/>All three phases coexist<br/>Water: 0.01°C, 611 Pa"]:::skyblue
    PhaseChanges --> PCCriticalPoint["Critical Point<br/>Liquid-gas distinction vanishes<br/>Above this: supercritical fluid"]:::skyblue
    
    PCPhaseDiagram --> PCPhaseLines["Solid-Liquid-Gas Lines<br/>Boundaries between phases<br/>Sublimation, melting, vaporization curves"]:::skyblue
    PCPhaseDiagram --> PCClausiusClapeyron["Clausius-Clapeyron Equation<br/>Relates vapor pressure to temp<br/>ln(P) vs 1/T is linear"]:::skyblue
    
    FirstLaw --> InternalEnergy["Internal Energy<br/>Total microscopic energy<br/>Sum of kinetic and potential energies"]:::paleblue
    FirstLaw --> Work["Thermodynamic Work<br/>Energy transfer by volume change<br/>W = PΔV for gases"]:::paleblue
    FirstLaw --> Heat["Heat Transfer<br/>Energy flow due to temperature difference<br/>Measured in joules or calories"]:::paleblue
    FirstLaw --> FirstLawEq["ΔU = Q - W<br/>First law equation<br/>Energy conservation"]:::paleblue
    FirstLaw --> ThermoProcesses["Thermodynamic Processes<br/>Isothermal, adiabatic, isochoric, isobaric<br/>Different constraints"]:::paleblue
    FirstLaw --> PVDiagrams["P-V Diagrams<br/>Visual representation of processes<br/>Area under curve = work"]:::paleblue
    
    InternalEnergy --> IEIdealGas["Ideal Gas: U = nC_vT<br/>Depends only on temperature<br/>State function"]:::skyblue
    InternalEnergy --> IEMonatomic["Monatomic: U = (3/2)nRT<br/>Only translational KE<br/>Noble gases"]:::skyblue
    InternalEnergy --> IEDiatomic["Diatomic: U = (5/2)nRT<br/>Translation + rotation<br/>Most atmospheric gases"]:::skyblue
    InternalEnergy --> IEStateFunction["State Function (path independent)<br/>Depends only on current state<br/>Not on how state was reached"]:::skyblue
    InternalEnergy --> IEMicroscopic["Sum of Molecular KE + PE<br/>All particle energies combined<br/>Microscopic interpretation"]:::skyblue
    
    Work --> WorkExpansion["Expansion: W > 0 (gas does work)<br/>Gas pushes piston out<br/>Energy leaves system"]:::skyblue
    Work --> WorkCompression["Compression: W < 0 (work on gas)<br/>Piston pushes gas in<br/>Energy enters system"]:::skyblue
    Work --> WorkIntegral["W = ∫P dV (area under P-V curve)<br/>General work expression<br/>Depends on process path"]:::skyblue
    Work --> WorkIsobaric["Isobaric: W = PΔV<br/>Constant pressure process<br/>Simplest work calculation"]:::skyblue
    Work --> WorkIsochoric["Isochoric: W = 0<br/>Constant volume process<br/>No volume change, no work"]:::skyblue
    
    WorkIntegral --> WorkIsothermal["Isothermal: W = nRT ln(V_f/V_i)<br/>Constant temperature expansion<br/>For ideal gas"]:::skyblue
    WorkIntegral --> WorkAdiabatic["Adiabatic: W = (P_iV_i - P_fV_f)/(γ-1)<br/>No heat transfer<br/>All ΔU from work"]:::skyblue
    
    Heat --> HeatSign["Q > 0 (into system), Q < 0 (out)<br/>Sign convention for heat<br/>Positive when absorbed"]:::skyblue
    Heat --> HeatPathDep["Path Dependent (not state function)<br/>Depends on process route<br/>Unlike internal energy"]:::skyblue
    Heat --> HeatTransferMech["Transfer by conduction/convection/radiation<br/>Three mechanisms<br/>From high to low temp"]:::skyblue
    Heat --> HeatCapacityProcess["C_p (constant P), C_v (constant V)<br/>Different heat capacities<br/>Depends on constraints"]:::skyblue
    
    FirstLawEq --> FLEConservation["Energy Conservation<br/>Total energy constant<br/>Energy transforms, not destroyed"]:::skyblue
    FirstLawEq --> FLESignConvention["Q in (+), W by gas (+)<br/>Sign convention matters<br/>Consistent with thermodynamics texts"]:::skyblue
    FirstLawEq --> FLEIsolated["Isolated: ΔU = 0<br/>No heat or work exchange<br/>Internal energy constant"]:::skyblue
    FirstLawEq --> FLECyclic["Cyclic: ΔU = 0, Q = W<br/>Returns to initial state<br/>Net heat equals net work"]:::skyblue
    
    ThermoProcesses --> TPIsothermal["Isothermal (ΔT = 0)<br/>Constant temperature<br/>Slow process with heat bath"]:::skyblue
    ThermoProcesses --> TPAdiabatic["Adiabatic (Q = 0)<br/>No heat exchange<br/>Thermally insulated or very fast"]:::skyblue
    ThermoProcesses --> TPIsochoric["Isochoric (ΔV = 0)<br/>Constant volume<br/>Rigid container"]:::skyblue
    ThermoProcesses --> TPIsobaric["Isobaric (ΔP = 0)<br/>Constant pressure<br/>Movable piston with constant weight"]:::skyblue
    
    TPIsothermal --> TPIsoEq["ΔU = 0, Q = W, PV = const<br/>Internal energy unchanged<br/>All heat becomes work"]:::skyblue
    TPIsothermal --> TPIsoReversible["Reversible Isothermal Expansion<br/>Infinitely slow process<br/>Maximum work output"]:::skyblue
    
    TPAdiabatic --> TPAdiaEq["ΔU = -W, PV^γ = const<br/>Work from internal energy<br/>Adiabat equation"]:::skyblue
    TPAdiabatic --> TPAdiaTempDrop["Expansion → Temperature Drop<br/>Gas cools when expanding<br/>Compression heats gas"]:::skyblue
    TPAdiabatic --> TPAdiaInsulated["Thermally Insulated System<br/>No heat transfer allowed<br/>Or process too fast"]:::skyblue
    
    TPIsochoric --> TPIsoVEq["W = 0, Q = ΔU = nC_vΔT<br/>All heat changes internal energy<br/>No work done"]:::skyblue
    TPIsochoric --> TPIsoVRigid["Rigid Container<br/>Volume cannot change<br/>Heating increases pressure"]:::skyblue
    
    TPIsobaric --> TPIsoPEq["W = PΔV, Q = nC_pΔT<br/>Work and heat both nonzero<br/>C_p used for constant pressure"]:::skyblue
    TPIsoPEq --> TPIsoPExpansion["Constant Pressure Expansion<br/>Common in piston-cylinder<br/>Atmospheric pressure applications"]:::skyblue
    
    PVDiagrams --> PVWork["Work = Area Under Curve<br/>Geometric interpretation<br/>Positive for expansion"]:::skyblue
    PVDiagrams --> PVCycles["Cyclic Processes (closed loops)<br/>Returns to starting point<br/>Net work = enclosed area"]:::skyblue
    PVDiagrams --> PVClockwise["Clockwise: Net Work Out<br/>Engine cycle<br/>Produces work"]:::skyblue
    PVDiagrams --> PVCounterclockwise["Counterclockwise: Net Work In<br/>Refrigerator cycle<br/>Requires work input"]:::skyblue
    PVDiagrams --> PVIsotherms["Isotherms (hyperbolas)<br/>PV = const curves<br/>Rectangular hyperbola shape"]:::skyblue
    PVDiagrams --> PVAdiabats["Adiabats (steeper than isotherms)<br/>PV^γ = const curves<br/>γ > 1 makes steeper"]:::skyblue
    
    SecondLaw --> Entropy["Entropy<br/>Measure of disorder<br/>Increases in spontaneous processes"]:::paleblue
    SecondLaw --> Irreversibility["Irreversibility<br/>Real processes cannot be reversed<br/>Due to entropy increase"]:::paleblue
    SecondLaw --> Carnot["Carnot Cycle<br/>Ideal reversible cycle<br/>Maximum theoretical efficiency"]:::paleblue
    SecondLaw --> SecondLawStatements["Various Statements<br/>Kelvin-Planck, Clausius, Entropy<br/>Equivalent formulations"]:::paleblue
    SecondLaw --> StatMech["Statistical Mechanics<br/>Microscopic foundation of entropy<br/>S = k ln Ω"]:::paleblue
    
    Entropy --> EntDefinition["ΔS = Q_rev / T<br/>Entropy change for reversible process<br/>Heat over absolute temperature"]:::skyblue
    Entropy --> EntStateFunction["State Function<br/>Path independent<br/>Depends only on initial and final states"]:::skyblue
    Entropy --> EntUniverseIncrease["ΔS_universe ≥ 0<br/>Second law statement<br/>Equality for reversible only"]:::skyblue
    Entropy --> EntReversible["Reversible: ΔS = 0<br/>Total entropy unchanged<br/>Idealized limit"]:::skyblue
    Entropy --> EntIrreversible["Irreversible: ΔS > 0<br/>Entropy always increases<br/>All real processes"]:::skyblue
    Entropy --> EntCalculations["Entropy Calculations<br/>Different formulas for different processes<br/>Integral of dQ/T"]:::skyblue
    
    EntCalculations --> EntIsothermal["Isothermal: ΔS = Q/T = nR ln(V_f/V_i)<br/>Constant temperature entropy change<br/>For ideal gas expansion"]:::skyblue
    EntCalculations --> EntTempChange["Temp Change: ΔS = nC ln(T_f/T_i)<br/>Entropy from temperature change<br/>C = C_v or C_p depending on process"]:::skyblue
    EntCalculations --> EntPhaseChange["Phase Change: ΔS = Q/T = mL/T<br/>Entropy of melting or boiling<br/>Large entropy increase for vaporization"]:::skyblue
    EntCalculations --> EntMixing["Mixing: Entropy of Mixing<br/>Irreversible entropy increase<br/>Gases or liquids spontaneously mix"]:::skyblue
    
    Irreversibility --> IrrFriction["Friction<br/>Converts ordered motion to heat<br/>Increases entropy"]:::skyblue
    Irreversibility --> IrrHeatFlow["Spontaneous Heat Flow<br/>Always hot to cold<br/>Cannot reverse without work"]:::skyblue
    Irreversibility --> IrrInelastic["Inelastic Collisions<br/>KE converted to internal energy<br/>Cannot spontaneously reverse"]:::skyblue
    Irreversibility --> IrrDiffusion["Diffusion<br/>Particles spread out<br/>Increases disorder"]:::skyblue
    Irreversibility --> IrrTimeArrow["Arrow of Time<br/>Entropy defines time direction<br/>Past lower entropy than future"]:::skyblue
    Irreversibility --> IrrLostWork["Lost Work/Exergy Destruction<br/>Irreversibility reduces useful work<br/>Cannot achieve Carnot efficiency"]:::skyblue
    
    Carnot --> CarnotSteps["Four Reversible Steps<br/>Two isothermal, two adiabatic<br/>Forms closed cycle"]:::skyblue
    Carnot --> CarnotEfficiency["η_Carnot = 1 - T_C/T_H<br/>Maximum possible efficiency<br/>Only depends on temperatures"]:::skyblue
    Carnot --> CarnotMaximum["Maximum Theoretical Efficiency<br/>No real engine can exceed<br/>Benchmark for all heat engines"]:::skyblue
    Carnot --> CarnotIdeal["Ideal (No Real Engine Achieves)<br/>Requires reversible processes<br/>Infinite time, no friction"]:::skyblue
    
    CarnotSteps --> CarnotIsoExpansion["1. Isothermal Expansion (T_H)<br/>Absorb heat Q_H from hot reservoir<br/>Gas expands, does work"]:::skyblue
    CarnotSteps --> CarnotAdiaExpansion["2. Adiabatic Expansion<br/>Gas continues to expand<br/>Temperature drops to T_C"]:::skyblue
    CarnotSteps --> CarnotIsoCompression["3. Isothermal Compression (T_C)<br/>Reject heat Q_C to cold reservoir<br/>Work done on gas"]:::skyblue
    CarnotSteps --> CarnotAdiaCompression["4. Adiabatic Compression<br/>Gas compressed further<br/>Temperature rises back to T_H"]:::skyblue
    
    CarnotEfficiency --> CarnotKelvinScale["Defines Kelvin Temperature Scale<br/>Thermodynamic temperature definition<br/>Independent of substance"]:::skyblue
    CarnotEfficiency --> CarnotCOP["Refrigerator COP = T_C/(T_H - T_C)<br/>Maximum cooling efficiency<br/>Inverse of engine efficiency"]:::skyblue
    
    SecondLawStatements --> SLKelvinPlanck["Kelvin-Planck Statement<br/>No 100% efficient heat engine<br/>Engine formulation"]:::skyblue
    SecondLawStatements --> SLClausius["Clausius Statement<br/>No spontaneous heat flow cold→hot<br/>Refrigerator formulation"]:::skyblue
    SecondLawStatements --> SLEntropy["Entropy Statement<br/>ΔS_universe ≥ 0<br/>Most general formulation"]:::skyblue
    
    SLKelvinPlanck --> SLKPNo100["No 100% efficient heat engine<br/>Cannot convert all heat to work<br/>Some must be rejected"]:::skyblue
    SLKPNo100 --> SLKPMustReject["Must reject heat to cold reservoir<br/>Energy conservation satisfied<br/>But can't be 100% useful"]:::skyblue
    
    SLClausius --> SLCNoSpontaneous["No spontaneous heat flow cold→hot<br/>Requires work input<br/>Refrigerators need power"]:::skyblue
    SLCNoSpontaneous --> SLCRequiresWork["Requires work input<br/>To pump heat uphill<br/>Cannot happen naturally"]:::skyblue
    
    StatMech --> SMBoltzmann["S = k ln Ω (Boltzmann)<br/>Entropy from microstates<br/>k = 1.38×10⁻²³ J/K"]:::skyblue
    StatMech --> SMMicrostates["Ω = Number of Microstates<br/>Ways to arrange particles<br/>Each with same energy"]:::skyblue
    StatMech --> SMProbability["High Entropy = High Probability<br/>More microstates, more likely<br/>Systems evolve to likely states"]:::skyblue
    StatMech --> SMDisorder["Entropy as Disorder/Randomness<br/>Ordered states have low entropy<br/>Disordered states high entropy"]:::skyblue
    StatMech --> SMThirdLaw["Third Law: S → 0 as T → 0<br/>Perfect crystal at 0 K<br/>Only one microstate"]:::skyblue
    
    HeatEngines --> Efficiency["Efficiency η = W/Q_H<br/>Work output over heat input<br/>Always less than 1"]:::paleblue
    HeatEngines --> Refrigerators["Refrigerators<br/>Move heat from cold to hot<br/>Requires work input"]:::paleblue
    HeatEngines --> HeatPumps["Heat Pumps<br/>Heating devices<br/>Reverse of heat engine"]:::paleblue
    HeatEngines --> EngineCycles["Real Engine Cycles<br/>Otto, Diesel, Brayton, Rankine<br/>Practical implementations"]:::paleblue
    HeatEngines --> PowerPlants["Power Generation<br/>Thermal power plants<br/>Convert heat to electricity"]:::paleblue
    
    Efficiency --> EffDef["η = W_out / Q_H = (Q_H - Q_C) / Q_H<br/>Efficiency definition<br/>Fraction of heat converted to work"]:::skyblue
    Efficiency --> EffPercent["Always < 100%<br/>Second law limitation<br/>Cannot convert all heat to work"]:::skyblue
    Efficiency --> EffCarnotMax["η_max = η_Carnot = 1 - T_C/T_H<br/>Maximum possible efficiency<br/>Only function of temperatures"]:::skyblue
    Efficiency --> EffRealEngines["Real Engines: η < η_Carnot<br/>Irreversibilities reduce efficiency<br/>Friction, heat loss, finite time"]:::skyblue
    Efficiency --> EffImprovements["Improving Efficiency<br/>Increase T_H, decrease T_C<br/>Reduce irreversibilities"]:::skyblue
    
    EffImprovements --> EffHighTemp["Increase T_H (high pressure steam)<br/>Superheated steam<br/>Higher inlet temperature"]:::skyblue
    EffImprovements --> EffLowTemp["Decrease T_C (cooling)<br/>Lower exhaust temperature<br/>Better condensers"]:::skyblue
    EffImprovements --> EffReduceLoss["Reduce friction/heat loss<br/>Better insulation<br/>Lubrication"]:::skyblue
    EffImprovements --> EffCombined["Combined Cycle (gas + steam)<br/>Use exhaust heat<br/>60% efficiency possible"]:::skyblue
    
    Refrigerators --> RefCOP["COP = Q_C / W<br/>Coefficient of performance<br/>Heat removed per work input"]:::skyblue
    Refrigerators --> RefCarnotCOP["COP_Carnot = T_C / (T_H - T_C)<br/>Maximum COP<br/>Higher when temp difference smaller"]:::skyblue
    Refrigerators --> RefHeatRemoval["Removes Heat from Cold Space<br/>Maintains low temperature<br/>Rejects to warm environment"]:::skyblue
    Refrigerators --> RefCycle["Vapor-Compression Cycle<br/>Most common refrigeration<br/>Uses phase change"]:::skyblue
    Refrigerators --> RefComponents["Refrigerator Components<br/>Evaporator, compressor, condenser, valve<br/>Four main parts"]:::skyblue
    
    RefCycle --> RefEvaporator["Evaporator (absorbs heat)<br/>Low pressure, liquid evaporates<br/>Inside cold space"]:::skyblue
    RefCycle --> RefCompressor["Compressor (work input)<br/>Increases pressure and temperature<br/>Requires electric power"]:::skyblue
    RefCycle --> RefCondenser["Condenser (rejects heat)<br/>High pressure, vapor condenses<br/>Outside in warm air"]:::skyblue
    RefCycle --> RefExpansion["Expansion Valve<br/>Lowers pressure<br/>Creates cold liquid"]:::skyblue
    
    RefComponents --> RefRefrigerant["Refrigerant (phase change fluid)<br/>Freon, R-134a, ammonia<br/>Low boiling point"]:::skyblue
    RefComponents --> RefInsulation["Insulation (minimize heat leak)<br/>Reduces cooling load<br/>Improves efficiency"]:::skyblue
    RefComponents --> RefCoils["Coils for heat exchange<br/>Large surface area<br/>Efficient heat transfer"]:::skyblue
    
    HeatPumps --> HPHeating["Heating Mode: COP_HP = Q_H / W<br/>Heat delivered per work<br/>COP > 1 possible"]:::skyblue
    HeatPumps --> HPCarnotCOP["COP_HP,Carnot = T_H / (T_H - T_C)<br/>Maximum heating COP<br/>Typically 3-5 in practice"]:::skyblue
    HeatPumps --> HPReversible["Reversible (heating/cooling)<br/>Can switch modes<br/>Heating in winter, cooling in summer"]:::skyblue
    HeatPumps --> HPEfficiency["COP_HP = COP_ref + 1<br/>Heating COP higher than cooling<br/>Relationship between modes"]:::skyblue
    HeatPumps --> HPGroundSource["Ground-Source Heat Pumps<br/>Use stable ground temperature<br/>Geothermal heat pump"]:::skyblue
    HeatPumps --> HPAirSource["Air-Source Heat Pumps<br/>Use ambient air<br/>More common but less efficient"]:::skyblue
    
    HPGroundSource --> HPGSEfficient["Higher efficiency (stable ground temp)<br/>Ground stays 10-15°C year-round<br/>Less temp difference"]:::skyblue
    HPGroundSource --> HPGSCostly["Higher installation cost<br/>Requires buried pipes<br/>Excavation needed"]:::skyblue
    
    HPAirSource --> HPASVariable["Variable efficiency (weather dependent)<br/>Performance varies with season<br/>Struggles in extreme cold"]:::skyblue
    HPASVariable --> HPASLowTemp["Less efficient at very low temps<br/>Below -15°C problematic<br/>May need backup heat"]:::skyblue
    
    EngineCycles --> ECOtto["Otto Cycle (gasoline)<br/>Spark ignition engines<br/>Cars, motorcycles"]:::skyblue
    EngineCycles --> ECDiesel["Diesel Cycle<br/>Compression ignition<br/>Trucks, heavy machinery"]:::skyblue
    EngineCycles --> ECBrayton["Brayton Cycle (jet engines)<br/>Gas turbines<br/>Aircraft, power generation"]:::skyblue
    EngineCycles --> ECRankine["Rankine Cycle (steam turbines)<br/>Steam power plants<br/>Coal, nuclear plants"]:::skyblue
    
    ECOtto --> ECOttoSteps["1. Intake 2. Compression 3. Ignition 4. Exhaust<br/>Four-stroke cycle<br/>Two crankshaft revolutions"]:::skyblue
    ECOtto --> ECOttoCompRatio["Compression Ratio r = V_max/V_min<br/>Typically 8:1 to 12:1<br/>Limited by knocking"]:::skyblue
    ECOtto --> ECOttoEff["η_Otto = 1 - 1/r^(γ-1)<br/>Efficiency increases with r<br/>Typical 25-30%"]:::skyblue
    
    ECDiesel --> ECDieselHighComp["Higher compression ratio than Otto<br/>14:1 to 25:1<br/>No spark plug needed"]:::skyblue
    ECDiesel --> ECDieselEff["Higher efficiency, more torque<br/>30-40% efficiency<br/>Better fuel economy"]:::skyblue
    
    ECBrayton --> ECBraytonTurbine["Compressor → Combustion → Turbine<br/>Continuous combustion<br/>High power-to-weight ratio"]:::skyblue
    ECBrayton --> ECBraytonOpenCycle["Open cycle (continuous flow)<br/>Air intake and exhaust<br/>Not a closed loop"]:::skyblue
    
    PowerPlants --> PPCoal["Coal/Natural Gas Plants<br/>Fossil fuel combustion<br/>Most common worldwide"]:::skyblue
    PowerPlants --> PPNuclear["Nuclear Power<br/>Fission heat source<br/>No CO₂ emissions"]:::skyblue
    PowerPlants --> PPGeothermal["Geothermal<br/>Earth's internal heat<br/>Renewable baseload power"]:::skyblue
    PowerPlants --> PPSolar["Solar Thermal<br/>Concentrated solar power<br/>Molten salt storage"]:::skyblue
    
    PPCoal --> PPCoalRankine["Uses Rankine steam cycle<br/>Boiler → turbine → condenser<br/>Closed loop"]:::skyblue
    PPCoal --> PPCoalEff["Typical efficiency 33-40%<br/>Supercritical plants higher<br/>Limited by T_H and T_C"]:::skyblue
    
    PPNuclear --> PPNucFission["Fission heat → steam → turbine<br/>Nuclear reactor as heat source<br/>Same cycle as coal"]:::skyblue
    PPNucFission --> PPNucSafety["Controlled chain reaction<br/>Control rods absorb neutrons<br/>Prevent runaway"]:::skyblue
    
    classDef blue fill:#1e40af,stroke:#1e3a8a,stroke-width:3px,color:#fff
    classDef lightblue fill:#3b82f6,stroke:#2563eb,stroke-width:2px,color:#fff
    classDef paleblue fill:#60a5fa,stroke:#3b82f6,stroke-width:2px,color:#000
    classDef skyblue fill:#93c5fd,stroke:#60a5fa,stroke-width:1px,color:#000
```