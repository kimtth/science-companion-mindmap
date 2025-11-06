```mermaid
flowchart LR
    Start([Ecology & Conservation]):::green
    Start --> PopulationEcol["Population Ecology<br/>Population dynamics and growth<br/>Birth, death, immigration, emigration"]:::lightgreen
    Start --> CommunityEcol["Community Ecology<br/>Interspecific interactions<br/>Competition, predation, symbiosis"]:::lightgreen
    Start --> EcosystemEcol["Ecosystem Ecology<br/>Energy flow and nutrient cycling<br/>Integrates biotic and abiotic factors"]:::lightgreen
    Start --> Conservation["Conservation Biology<br/>Protecting biodiversity<br/>Applied ecology for preservation"]:::lightgreen
    
    PopulationEcol --> PopGrowth["Population Growth<br/>Exponential and logistic models<br/>Carrying capacity limits"]:::palegreen
    PopulationEcol --> LifeHistory["Life History Strategies<br/>r-selected vs K-selected<br/>Tradeoffs in reproduction"]:::palegreen
    PopulationEcol --> Demography["Demography<br/>Age structure and survivorship<br/>Predicts population trends"]:::palegreen
    PopulationEcol --> PopulationDensity["Population Density<br/>Number per unit area<br/>Affects competition and mating"]:::palegreen
    
    PopGrowth --> ExponentialGrowth["Exponential Growth<br/>J-shaped curve<br/>dN/dt = rN, unlimited resources"]:::mintgreen
    PopGrowth --> LogisticGrowth["Logistic Growth<br/>S-shaped curve<br/>dN/dt = rN(1-N/K)"]:::mintgreen
    PopGrowth --> CarryingCapacity["Carrying Capacity (K)<br/>Maximum sustainable population<br/>Limited by resources"]:::mintgreen
    PopGrowth --> IntrinsicRate["Intrinsic Rate of Increase (r)<br/>Maximum per capita growth<br/>Birth rate minus death rate"]:::mintgreen
    
    ExponentialGrowth --> JCurve["J-Curve Shape<br/>Rapid acceleration<br/>Ideal conditions only"]:::lightmint
    ExponentialGrowth --> DoublingTime["Doubling Time<br/>Time to double population<br/>70/r approximation"]:::lightmint
    
    LogisticGrowth --> SCurve["S-Curve Shape<br/>Levels off at K<br/>Density-dependent regulation"]:::lightmint
    LogisticGrowth --> DensityDependence["Density-Dependent Factors<br/>Competition, disease, predation<br/>Stronger at high density"]:::lightmint
    LogisticGrowth --> DensityIndependence["Density-Independent Factors<br/>Weather, natural disasters<br/>Affect all densities equally"]:::lightmint
    
    LifeHistory --> RSelected["r-Selected Species<br/>High reproduction rate<br/>Small body, short life, many offspring"]:::mintgreen
    LifeHistory --> KSelected["K-Selected Species<br/>Low reproduction rate<br/>Large body, long life, few offspring"]:::mintgreen
    LifeHistory --> ReproductiveStrategies["Reproductive Strategies<br/>Semelparity vs iteroparity<br/>Trade-offs in energy allocation"]:::mintgreen
    
    RSelected --> Opportunistic["Opportunistic Strategists<br/>Colonize new habitats<br/>Weeds, insects, rodents"]:::lightmint
    RSelected --> HighFecundity["High Fecundity<br/>Many offspring<br/>Low parental investment"]:::lightmint
    
    KSelected --> Equilibrium["Equilibrium Strategists<br/>Stable environments<br/>Elephants, whales, humans"]:::lightmint
    KSelected --> ParentalCare["Parental Care<br/>High investment per offspring<br/>Increased survival rate"]:::lightmint
    
    Demography --> AgeStructure["Age Structure<br/>Proportion in age classes<br/>Pyramids show growth potential"]:::mintgreen
    Demography --> SurvivorshipCurves["Survivorship Curves<br/>Type I, II, III patterns<br/>Mortality over lifespan"]:::mintgreen
    Demography --> LifeTables["Life Tables<br/>Age-specific mortality and reproduction<br/>Statistical prediction tool"]:::mintgreen
    
    SurvivorshipCurves --> TypeI["Type I Curve<br/>Low early mortality<br/>Humans, large mammals"]:::lightmint
    SurvivorshipCurves --> TypeII["Type II Curve<br/>Constant mortality rate<br/>Birds, small mammals"]:::lightmint
    SurvivorshipCurves --> TypeIII["Type III Curve<br/>High early mortality<br/>Fish, invertebrates, plants"]:::lightmint
    
    CommunityEcol --> Competition["Interspecific Competition<br/>Resource competition between species<br/>Competitive exclusion principle"]:::palegreen
    CommunityEcol --> Predation["Predation<br/>Consumer-resource interactions<br/>Population oscillations"]:::palegreen
    CommunityEcol --> Symbiosis["Symbiosis<br/>Close species interactions<br/>Mutualism, commensalism, parasitism"]:::palegreen
    CommunityEcol --> Succession["Ecological Succession<br/>Community change over time<br/>Primary and secondary succession"]:::palegreen
    CommunityEcol --> Biodiversity["Biodiversity<br/>Variety of life<br/>Species, genetic, ecosystem diversity"]:::palegreen
    CommunityEcol --> Niches["Ecological Niches<br/>Species' role in ecosystem<br/>Habitat and resource use"]:::palegreen
    
    Competition --> CompetitiveExclusion["Competitive Exclusion<br/>One species outcompetes<br/>Cannot occupy same niche"]:::mintgreen
    Competition --> ResourcePartitioning["Resource Partitioning<br/>Niche differentiation<br/>Reduces competition"]:::mintgreen
    Competition --> CharacterDisplacement["Character Displacement<br/>Evolutionary divergence<br/>Competing species differ"]:::mintgreen
    
    CompetitiveExclusion --> GausePrinciple["Gause's Principle<br/>Complete competitors cannot coexist<br/>One drives other to extinction"]:::lightmint
    
    ResourcePartitioning --> TemporalPartitioning["Temporal Partitioning<br/>Different activity times<br/>Day vs night foraging"]:::lightmint
    ResourcePartitioning --> SpatialPartitioning["Spatial Partitioning<br/>Different microhabitats<br/>Vertical stratification"]:::lightmint
    ResourcePartitioning --> DietPartitioning["Diet Partitioning<br/>Different food sources<br/>Prey size or type"]:::lightmint
    
    Predation --> PredatorPrey["Predator-Prey Dynamics<br/>Linked population cycles<br/>Lotka-Volterra model"]:::mintgreen
    Predation --> PredatorAdaptations["Predator Adaptations<br/>Hunting strategies<br/>Speed, stealth, cooperation"]:::mintgreen
    Predation --> PreyDefenses["Prey Defenses<br/>Avoid or deter predators<br/>Camouflage, toxins, armor"]:::mintgreen
    
    PredatorPrey --> LotkaVolterra["Lotka-Volterra Equations<br/>Mathematical model<br/>Oscillating populations"]:::lightmint
    PredatorPrey --> TimelagEffects["Time-Lag Effects<br/>Delayed responses<br/>Phase-shifted cycles"]:::lightmint
    
    PreyDefenses --> Crypsis["Crypsis (Camouflage)<br/>Blend with background<br/>Avoid detection"]:::lightmint
    PreyDefenses --> AposematicColoration["Aposematic Coloration<br/>Warning colors<br/>Bright patterns signal toxicity"]:::lightmint
    PreyDefenses --> BatesianMimicry["Batesian Mimicry<br/>Harmless mimics toxic<br/>False warning"]:::lightmint
    PreyDefenses --> MullerianMimicry["Müllerian Mimicry<br/>Multiple toxic species converge<br/>Shared warning signal"]:::lightmint
    
    Symbiosis --> Mutualism["Mutualism<br/>Both species benefit<br/>Pollinators and plants"]:::mintgreen
    Symbiosis --> Commensalism["Commensalism<br/>One benefits, other unaffected<br/>Barnacles on whales"]:::mintgreen
    Symbiosis --> Parasitism["Parasitism<br/>One benefits, other harmed<br/>Host-parasite relationship"]:::mintgreen
    
    Mutualism --> PollinationMutualism["Pollination Mutualisms<br/>Plants and pollinators<br/>Nectar for pollen transfer"]:::lightmint
    Mutualism --> MycorrhizalFungi["Mycorrhizal Fungi<br/>Root-fungus association<br/>Nutrients for carbohydrates"]:::lightmint
    Mutualism --> LichenSymbiosis["Lichens<br/>Algae and fungi<br/>Photosynthesis and structure"]:::lightmint
    
    Parasitism --> Ectoparasites["Ectoparasites<br/>External parasites<br/>Ticks, lice, leeches"]:::lightmint
    Parasitism --> Endoparasites["Endoparasites<br/>Internal parasites<br/>Tapeworms, malaria"]:::lightmint
    Parasitism --> Parasitoids["Parasitoids<br/>Eventually kill host<br/>Wasp larvae in caterpillars"]:::lightmint
    
    Succession --> PrimarySuccession["Primary Succession<br/>From bare rock or soil<br/>No previous life"]:::mintgreen
    Succession --> SecondarySuccession["Secondary Succession<br/>After disturbance<br/>Soil and seeds present"]:::mintgreen
    Succession --> ClimaxCommunity["Climax Community<br/>Stable endpoint<br/>Self-perpetuating"]:::mintgreen
    Succession --> PioneerSpecies["Pioneer Species<br/>First colonizers<br/>Lichens, mosses, grasses"]:::mintgreen
    
    PrimarySuccession --> BareRock["Bare Rock Start<br/>Glacial retreat, lava flows<br/>No organic matter"]:::lightmint
    PrimarySuccession --> SoilFormation["Soil Formation<br/>Weathering and decomposition<br/>Gradual accumulation"]:::lightmint
    
    SecondarySuccession --> Disturbance["Disturbance Events<br/>Fire, logging, farming<br/>Resets community"]:::lightmint
    SecondarySuccession --> FasterRecovery["Faster Recovery<br/>Soil and seed bank intact<br/>Rapid recolonization"]:::lightmint
    
    Biodiversity --> SpeciesRichness["Species Richness<br/>Number of species<br/>Simple count"]:::mintgreen
    Biodiversity --> SpeciesEvenness["Species Evenness<br/>Relative abundance<br/>Distribution of individuals"]:::mintgreen
    Biodiversity --> ShannonIndex["Shannon Diversity Index<br/>Combines richness and evenness<br/>Quantitative measure"]:::mintgreen
    Biodiversity --> LatitudinalGradient["Latitudinal Gradient<br/>Higher diversity at equator<br/>Decreases toward poles"]:::mintgreen
    
    Niches --> FundamentalNiche["Fundamental Niche<br/>Potential range<br/>Without competition"]:::mintgreen
    Niches --> RealizedNiche["Realized Niche<br/>Actual range<br/>With competition and predation"]:::mintgreen
    Niches --> NicheBreadth["Niche Breadth<br/>Generalist vs specialist<br/>Resource use spectrum"]:::mintgreen
    
    EcosystemEcol --> EnergyFlow["Energy Flow<br/>Trophic levels and food webs<br/>~10% efficiency between levels"]:::palegreen
    EcosystemEcol --> NutrientCycling["Nutrient Cycling<br/>Biogeochemical cycles<br/>Carbon, nitrogen, phosphorus cycles"]:::palegreen
    EcosystemEcol --> PrimaryProduction["Primary Production<br/>Energy capture by autotrophs<br/>Foundation of food webs"]:::palegreen
    
    EnergyFlow --> TrophicLevels["Trophic Levels<br/>Feeding positions<br/>Producers, consumers, decomposers"]:::mintgreen
    EnergyFlow --> FoodChains["Food Chains<br/>Linear energy pathways<br/>Simple feeding relationships"]:::mintgreen
    EnergyFlow --> FoodWebs["Food Webs<br/>Complex interconnections<br/>Multiple pathways"]:::mintgreen
    EnergyFlow --> EcologicalPyramids["Ecological Pyramids<br/>Energy, biomass, numbers<br/>Decreasing with trophic level"]:::mintgreen
    
    TrophicLevels --> Producers["Producers (Autotrophs)<br/>Convert light to energy<br/>Plants, algae, cyanobacteria"]:::lightmint
    TrophicLevels --> PrimaryConsumers["Primary Consumers<br/>Herbivores<br/>Eat producers"]:::lightmint
    TrophicLevels --> SecondaryConsumers["Secondary Consumers<br/>Carnivores<br/>Eat herbivores"]:::lightmint
    TrophicLevels --> TertiaryConsumers["Tertiary Consumers<br/>Top carnivores<br/>Apex predators"]:::lightmint
    TrophicLevels --> Decomposers["Decomposers<br/>Bacteria and fungi<br/>Recycle nutrients"]:::lightmint
    
    EcologicalPyramids --> EnergyPyramid["Energy Pyramid<br/>Energy at each level<br/>Always upright, 10% rule"]:::lightmint
    EcologicalPyramids --> BiomassPyramid["Biomass Pyramid<br/>Total mass at each level<br/>Usually upright"]:::lightmint
    EcologicalPyramids --> NumbersPyramid["Numbers Pyramid<br/>Individuals at each level<br/>Can be inverted"]:::lightmint
    
    PrimaryProduction --> GrossPrimaryProduction["Gross Primary Production (GPP)<br/>Total photosynthesis<br/>All energy captured"]:::mintgreen
    PrimaryProduction --> NetPrimaryProduction["Net Primary Production (NPP)<br/>GPP minus respiration<br/>Available to consumers"]:::mintgreen
    PrimaryProduction --> ProductivityFactors["Productivity Factors<br/>Light, water, nutrients, temperature<br/>Limit production"]:::mintgreen
    
    NutrientCycling --> CarbonCycle["Carbon Cycle<br/>Movement of carbon through ecosystems<br/>Photosynthesis and respiration"]:::mintgreen
    NutrientCycling --> NitrogenCycle["Nitrogen Cycle<br/>Nitrogen fixation and recycling<br/>Nitrification and denitrification"]:::mintgreen
    NutrientCycling --> PhosphorusCycle["Phosphorus Cycle<br/>Sedimentary cycle<br/>Weathering and runoff"]:::mintgreen
    NutrientCycling --> WaterCycle["Water Cycle<br/>Evaporation, precipitation, runoff<br/>Distributes water globally"]:::mintgreen
    
    CarbonCycle --> Photosynthesis["Photosynthesis<br/>CO2 fixation<br/>Produces organic compounds"]:::lightmint
    CarbonCycle --> Respiration["Cellular Respiration<br/>Releases CO2<br/>All organisms"]:::lightmint
    CarbonCycle --> Combustion["Combustion<br/>Burning fossil fuels<br/>Rapid CO2 release"]:::lightmint
    CarbonCycle --> CarbonSinks["Carbon Sinks<br/>Forests, oceans, soil<br/>Long-term storage"]:::lightmint
    
    NitrogenCycle --> NitrogenFixation["Nitrogen Fixation<br/>N2 to NH3<br/>Bacteria (Rhizobium)"]:::lightmint
    NitrogenCycle --> Nitrification["Nitrification<br/>NH3 to NO2- to NO3-<br/>Nitrosomonas and Nitrobacter"]:::lightmint
    NitrogenCycle --> Assimilation["Assimilation<br/>Plants absorb NO3-<br/>Incorporate into biomolecules"]:::lightmint
    NitrogenCycle --> Ammonification["Ammonification<br/>Decomposition to NH3<br/>Returns nitrogen to soil"]:::lightmint
    NitrogenCycle --> Denitrification["Denitrification<br/>NO3- to N2<br/>Anaerobic bacteria"]:::lightmint
    
    PhosphorusCycle --> WeatheringP["Weathering<br/>Rock breakdown<br/>Releases phosphate"]:::lightmint
    PhosphorusCycle --> Uptake["Plant Uptake<br/>Absorb PO4 3-<br/>Essential for DNA, ATP"]:::lightmint
    PhosphorusCycle --> Runoff["Runoff<br/>Water transport<br/>To aquatic systems"]:::lightmint
    PhosphorusCycle --> Sedimentation["Sedimentation<br/>Marine deposition<br/>Long-term geological storage"]:::lightmint
    
    WaterCycle --> Evaporation["Evaporation<br/>Liquid to gas<br/>Solar energy driven"]:::lightmint
    WaterCycle --> Transpiration["Transpiration<br/>Plant water release<br/>Through stomata"]:::lightmint
    WaterCycle --> Condensation["Condensation<br/>Gas to liquid<br/>Cloud formation"]:::lightmint
    WaterCycle --> Precipitation["Precipitation<br/>Rain, snow, sleet<br/>Returns water to surface"]:::lightmint
    
    Conservation --> BiodiversityLoss["Biodiversity Loss<br/>Extinction and habitat destruction<br/>Major global concern"]:::palegreen
    Conservation --> Threats["Threats to Biodiversity<br/>Habitat loss, invasive species, pollution<br/>Climate change, overexploitation"]:::palegreen
    Conservation --> ConservationStrategies["Conservation Strategies<br/>Protected areas and restoration<br/>Sustainable management"]:::palegreen
    
    BiodiversityLoss --> MassExtinction["Sixth Mass Extinction<br/>Current biodiversity crisis<br/>Human-caused"]:::mintgreen
    BiodiversityLoss --> ExtinctionRate["Extinction Rate<br/>1000x background rate<br/>Accelerating loss"]:::mintgreen
    BiodiversityLoss --> EndangeredSpecies["Endangered Species<br/>At risk of extinction<br/>IUCN Red List categories"]:::mintgreen
    
    Threats --> HabitatLoss["Habitat Loss<br/>Primary threat<br/>Deforestation, urbanization, agriculture"]:::mintgreen
    Threats --> HabitatFragmentation["Habitat Fragmentation<br/>Isolated patches<br/>Edge effects, reduced connectivity"]:::mintgreen
    Threats --> InvasiveSpecies["Invasive Species<br/>Non-native competitors<br/>Disrupt ecosystems"]:::mintgreen
    Threats --> Pollution["Pollution<br/>Chemical contamination<br/>Air, water, soil degradation"]:::mintgreen
    Threats --> ClimateChange["Climate Change<br/>Global warming<br/>Shifts ranges, phenology"]:::mintgreen
    Threats --> Overexploitation["Overexploitation<br/>Overharvesting<br/>Hunting, fishing, logging"]:::mintgreen
    
    HabitatFragmentation --> EdgeEffects["Edge Effects<br/>Altered microclimate<br/>Increased predation, invasives"]:::lightmint
    HabitatFragmentation --> IslandBiogeography["Island Biogeography Theory<br/>Smaller patches, fewer species<br/>Area and isolation effects"]:::lightmint
    HabitatFragmentation --> Corridors["Wildlife Corridors<br/>Connect habitat patches<br/>Enable movement and gene flow"]:::lightmint
    
    ClimateChange --> RangeShifts["Range Shifts<br/>Species move poleward or upward<br/>Tracking suitable climate"]:::lightmint
    ClimateChange --> PhenologyMismatch["Phenology Mismatch<br/>Timing disruptions<br/>Breeding, migration, flowering"]:::lightmint
    ClimateChange --> OceanAcidification["Ocean Acidification<br/>CO2 absorption<br/>Threatens coral reefs, shellfish"]:::lightmint
    
    ConservationStrategies --> ProtectedAreas["Protected Areas<br/>National parks, reserves<br/>Habitat preservation"]:::mintgreen
    ConservationStrategies --> ExSituConservation["Ex Situ Conservation<br/>Outside natural habitat<br/>Zoos, seed banks"]:::mintgreen
    ConservationStrategies --> InSituConservation["In Situ Conservation<br/>Within natural habitat<br/>Preferred long-term"]:::mintgreen
    ConservationStrategies --> Restoration["Habitat Restoration<br/>Rehabilitate degraded ecosystems<br/>Reintroduce species"]:::mintgreen
    ConservationStrategies --> SustainableUse["Sustainable Use<br/>Balance conservation and human needs<br/>Ecosystem services approach"]:::mintgreen
    
    ProtectedAreas --> BiodiversityHotspots["Biodiversity Hotspots<br/>High species richness and threat<br/>Conservation priorities"]:::lightmint
    ProtectedAreas --> MarineProtectedAreas["Marine Protected Areas<br/>Ocean conservation zones<br/>Fishery management"]:::lightmint
    
    ExSituConservation --> CaptiveBreeding["Captive Breeding<br/>Zoo programs<br/>Genetic diversity management"]:::lightmint
    ExSituConservation --> SeedBanks["Seed Banks<br/>Preserve plant genetic diversity<br/>Svalbard Global Seed Vault"]:::lightmint
    ExSituConservation --> CryopreservationEcol["Cryopreservation<br/>Frozen tissue storage<br/>Genetic material banking"]:::lightmint
    
    Restoration --> ReforestationPrograms["Reforestation<br/>Plant trees<br/>Carbon sequestration, habitat"]:::lightmint
    Restoration --> WetlandRestoration["Wetland Restoration<br/>Restore hydrology<br/>Water purification, flood control"]:::lightmint
    Restoration --> SpeciesReintroduction["Species Reintroduction<br/>Return to former range<br/>Wolf, condor successes"]:::lightmint
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
    classDef lightmint fill:#bbf7d0,stroke:#86efac,stroke-width:1px,color:#000
```