```mermaid
flowchart LR
    Start([Plant & Animal Biology]):::green
    Start --> PlantStructure["Plant Structure<br/>Roots, stems, leaves<br/>Adaptations for photosynthesis"]:::lightgreen
    Start --> PlantReproduction["Plant Reproduction<br/>Sexual and asexual methods<br/>Flowers, seeds, fruits"]:::lightgreen
    Start --> AnimalSystems["Animal Organ Systems<br/>Coordinated organs perform functions<br/>Circulatory, nervous, digestive, etc."]:::lightgreen
    Start --> Homeostasis["Homeostasis<br/>Maintaining internal stability<br/>Negative feedback mechanisms"]:::lightgreen
    
    Homeostasis --> NegativeFeedback["Negative Feedback<br/>Counteracts change<br/>Most common regulatory mechanism"]:::palegreen
    Homeostasis --> Thermoregulation["Thermoregulation<br/>Temperature control<br/>Endotherms vs ectotherms"]:::palegreen
    Homeostasis --> Osmoregulation["Osmoregulation<br/>Water and salt balance<br/>Kidneys regulate"]:::palegreen
    Homeostasis --> GlucoseRegulation["Glucose Regulation<br/>Blood sugar homeostasis<br/>Insulin and glucagon"]:::palegreen
    
    NegativeFeedback --> SetPoint["Set Point<br/>Target value<br/>Body maintains around this"]:::mintgreen
    NegativeFeedback --> Sensor["Sensor (Receptor)<br/>Detects deviation<br/>Signals control center"]:::mintgreen
    NegativeFeedback --> ControlCenter["Control Center<br/>Processes information<br/>Initiates response"]:::mintgreen
    NegativeFeedback --> Effector["Effector<br/>Carries out response<br/>Restores set point"]:::mintgreen
    
    Thermoregulation --> Endotherms["Endotherms<br/>Generate internal heat<br/>Birds and mammals"]:::mintgreen
    Thermoregulation --> Ectotherms["Ectotherms<br/>Rely on external heat<br/>Reptiles, amphibians, fish"]:::mintgreen
    Thermoregulation --> CoolingMechanisms["Cooling Mechanisms<br/>Sweating, panting, vasodilation<br/>Dissipate heat"]:::mintgreen
    Thermoregulation --> WarmingMechanisms["Warming Mechanisms<br/>Shivering, vasoconstriction<br/>Conserve and generate heat"]:::mintgreen
    
    Osmoregulation --> KidneyFunction["Kidney Function<br/>Filter blood, produce urine<br/>Nephron is functional unit"]:::mintgreen
    Osmoregulation --> ADH["ADH (Antidiuretic Hormone)<br/>Increases water reabsorption<br/>Concentrates urine"]:::mintgreen
    Osmoregulation --> Aldosterone["Aldosterone<br/>Increases Na+ reabsorption<br/>Water follows sodium"]:::mintgreen
    
    KidneyFunction --> Filtration["Glomerular Filtration<br/>Blood pressure drives<br/>Filters into Bowman's capsule"]:::lightmint
    KidneyFunction --> Reabsorption["Tubular Reabsorption<br/>Reclaim useful substances<br/>Water, glucose, ions"]:::lightmint
    KidneyFunction --> Secretion["Tubular Secretion<br/>Active transport of wastes<br/>Into tubule"]:::lightmint
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
    classDef lightmint fill:#bbf7d0,stroke:#86efac,stroke-width:1px,color:#000
    
    PlantStructure --> Roots["Roots<br/>Anchor and absorb water/nutrients<br/>Root hairs increase surface area"]:::palegreen
    PlantStructure --> Stems["Stems<br/>Support and transport<br/>Xylem and phloem tissues"]:::palegreen
    PlantStructure --> Leaves["Leaves<br/>Primary photosynthetic organs<br/>Stomata regulate gas exchange"]:::palegreen
    PlantStructure --> VascularTissue["Vascular Tissue<br/>Transport systems<br/>Xylem and phloem"]:::palegreen
    
    Roots --> RootTypes["Root Types<br/>Taproot vs fibrous<br/>Different anchoring strategies"]:::mintgreen
    Roots --> RootHairs["Root Hairs<br/>Extensions of epidermal cells<br/>Increase absorption surface area"]:::mintgreen
    Roots --> RootZones["Root Zones<br/>Cap, meristem, elongation, maturation<br/>Growth and differentiation regions"]:::mintgreen
    Roots --> Mycorrhizae["Mycorrhizae<br/>Root-fungus symbiosis<br/>Enhanced nutrient uptake"]:::mintgreen
    
    RootTypes --> Taproot["Taproot System<br/>Single main root<br/>Dicots, deep penetration"]:::lightmint
    RootTypes --> FibrousRoot["Fibrous Root System<br/>Many thin roots<br/>Monocots, wide spread"]:::lightmint
    
    Stems --> StemFunctions["Stem Functions<br/>Support, transport, storage<br/>Photosynthesis in some"]:::mintgreen
    Stems --> StemModifications["Stem Modifications<br/>Stolons, rhizomes, tubers<br/>Adaptation and storage"]:::mintgreen
    Stems --> ApicalMeristem["Apical Meristem<br/>Tip growth region<br/>Primary growth lengthens stem"]:::mintgreen
    
    Leaves --> LeafAnatomy["Leaf Anatomy<br/>Epidermis, mesophyll, veins<br/>Specialized for photosynthesis"]:::mintgreen
    Leaves --> Stomata["Stomata<br/>Gas exchange pores<br/>Guard cells regulate opening"]:::mintgreen
    Leaves --> Transpiration["Transpiration<br/>Water loss through stomata<br/>Drives water uptake"]:::mintgreen
    Leaves --> LeafModifications["Leaf Modifications<br/>Spines, tendrils, storage<br/>Adaptations to environment"]:::mintgreen
    
    LeafAnatomy --> Epidermis["Epidermis<br/>Protective outer layer<br/>Cuticle reduces water loss"]:::lightmint
    LeafAnatomy --> PalisadeMesophyll["Palisade Mesophyll<br/>Upper layer, tightly packed<br/>Main photosynthesis site"]:::lightmint
    LeafAnatomy --> SpongyMesophyll["Spongy Mesophyll<br/>Lower layer, air spaces<br/>Gas exchange"]:::lightmint
    LeafAnatomy --> Veins["Leaf Veins<br/>Vascular bundles<br/>Transport water and sugars"]:::lightmint
    
    Stomata --> GuardCells["Guard Cells<br/>Regulate stomatal opening<br/>Respond to light, CO2, water"]:::lightmint
    Stomata --> StomatalRegulation["Stomatal Regulation<br/>Balance gas exchange and water loss<br/>Abscisic acid in drought"]:::lightmint
    
    VascularTissue --> Xylem["Xylem<br/>Water and mineral transport<br/>Dead cells, one-way flow upward"]:::mintgreen
    VascularTissue --> Phloem["Phloem<br/>Sugar transport<br/>Living cells, bidirectional flow"]:::mintgreen
    
    Xylem --> Tracheids["Tracheids<br/>Elongated cells with pits<br/>Found in all vascular plants"]:::lightmint
    Xylem --> VesselElements["Vessel Elements<br/>Wider, perforated cells<br/>More efficient, in angiosperms"]:::lightmint
    Xylem --> TranspirationPull["Transpiration Pull<br/>Cohesion-tension mechanism<br/>Negative pressure draws water"]:::lightmint
    
    Phloem --> SieveTubeElements["Sieve Tube Elements<br/>Conducting cells<br/>No nucleus at maturity"]:::lightmint
    Phloem --> CompanionCells["Companion Cells<br/>Support sieve tubes<br/>Metabolic functions"]:::lightmint
    Phloem --> TranslocationMechanism["Translocation<br/>Pressure-flow hypothesis<br/>Source to sink movement"]:::lightmint
    
    PlantReproduction --> FlowerStructure["Flower Structure<br/>Reproductive organs<br/>Stamens and carpels"]:::palegreen
    PlantReproduction --> Pollination["Pollination<br/>Pollen transfer<br/>Wind, animals, water vectors"]:::palegreen
    PlantReproduction --> SeedDevelopment["Seed Development<br/>Embryo and endosperm formation<br/>Protected for dispersal"]:::palegreen
    PlantReproduction --> FruitDevelopment["Fruit Development<br/>Ovary matures<br/>Protects and disperses seeds"]:::palegreen
    PlantReproduction --> AlternationGenerations["Alternation of Generations<br/>Sporophyte and gametophyte<br/>Diploid and haploid phases"]:::palegreen
    
    FlowerStructure --> Sepals["Sepals<br/>Protective outer whorl<br/>Enclose bud"]:::mintgreen
    FlowerStructure --> Petals["Petals<br/>Colorful attractants<br/>Signal pollinators"]:::mintgreen
    FlowerStructure --> Stamens["Stamens<br/>Male reproductive organs<br/>Anther and filament"]:::mintgreen
    FlowerStructure --> Carpel["Carpel (Pistil)<br/>Female reproductive organ<br/>Stigma, style, ovary"]:::mintgreen
    
    Stamens --> Anther["Anther<br/>Pollen production site<br/>Contains pollen sacs"]:::lightmint
    Stamens --> PollenGrain["Pollen Grain<br/>Male gametophyte<br/>Contains sperm cells"]:::lightmint
    
    Carpel --> Stigma["Stigma<br/>Pollen landing site<br/>Sticky surface"]:::lightmint
    Carpel --> Style["Style<br/>Connects stigma to ovary<br/>Pollen tube pathway"]:::lightmint
    Carpel --> Ovary["Ovary<br/>Contains ovules<br/>Becomes fruit"]:::lightmint
    Carpel --> Ovule["Ovule<br/>Female gametophyte location<br/>Becomes seed"]:::lightmint
    
    Pollination --> WindPollination["Wind Pollination<br/>Abiotic vector<br/>Large pollen quantities, grasses"]:::mintgreen
    Pollination --> AnimalPollination["Animal Pollination<br/>Insects, birds, bats<br/>Coevolution with flowers"]:::mintgreen
    Pollination --> SelfPollination["Self-Pollination<br/>Within same flower<br/>Ensures reproduction"]:::mintgreen
    Pollination --> CrossPollination["Cross-Pollination<br/>Between different plants<br/>Increases genetic diversity"]:::mintgreen
    
    AnimalPollination --> InsectPollination["Insect Pollination<br/>Bees, butterflies, beetles<br/>Color and scent attraction"]:::lightmint
    AnimalPollination --> BirdPollination["Bird Pollination<br/>Hummingbirds<br/>Red flowers, tubular shape"]:::lightmint
    AnimalPollination --> BatPollination["Bat Pollination<br/>Nocturnal<br/>Night-blooming, strong scent"]:::lightmint
    
    SeedDevelopment --> Fertilization["Double Fertilization<br/>Unique to angiosperms<br/>Embryo and endosperm"]:::mintgreen
    SeedDevelopment --> EmbryoSac["Embryo Sac<br/>Female gametophyte<br/>Contains egg cell"]:::mintgreen
    SeedDevelopment --> Endosperm["Endosperm<br/>Nutrient tissue<br/>Feeds developing embryo"]:::mintgreen
    SeedDevelopment --> SeedCoat["Seed Coat<br/>Protective layer<br/>From ovule integuments"]:::mintgreen
    
    Fertilization --> DoubleFertilization["Double Fertilization Process<br/>One sperm + egg = zygote (2n)<br/>One sperm + polar nuclei = endosperm (3n)"]:::lightmint
    
    FruitDevelopment --> SimpleFruit["Simple Fruit<br/>From single ovary<br/>Apple, peach, tomato"]:::mintgreen
    FruitDevelopment --> AggregateFruit["Aggregate Fruit<br/>From multiple ovaries in one flower<br/>Raspberry, strawberry"]:::mintgreen
    FruitDevelopment --> MultipleFruit["Multiple Fruit<br/>From multiple flowers<br/>Pineapple, fig"]:::mintgreen
    FruitDevelopment --> SeedDispersal["Seed Dispersal<br/>Wind, water, animals<br/>Reduces competition"]:::mintgreen
    
    AlternationGenerations --> SporophyteGeneration["Sporophyte Generation<br/>Diploid (2n)<br/>Produces spores by meiosis"]:::mintgreen
    AlternationGenerations --> GametophyteGeneration["Gametophyte Generation<br/>Haploid (n)<br/>Produces gametes by mitosis"]:::mintgreen
    AlternationGenerations --> DominantGeneration["Dominant Generation<br/>Varies by plant type<br/>Sporophyte dominant in seed plants"]:::mintgreen
    
    AnimalSystems --> Circulatory["Circulatory System<br/>Transport of materials<br/>Heart, blood vessels, blood"]:::palegreen
    AnimalSystems --> Respiratory["Respiratory System<br/>Gas exchange<br/>Oxygen in, carbon dioxide out"]:::palegreen
    
    Respiratory --> Lungs["Lungs<br/>Primary gas exchange organs<br/>Alveoli provide surface area"]:::mintgreen
    Respiratory --> BreathingMechanism["Breathing Mechanism<br/>Diaphragm and intercostals<br/>Negative pressure ventilation"]:::mintgreen
    Respiratory --> GasExchange["Gas Exchange<br/>Diffusion across alveolar membrane<br/>O2 and CO2 gradients"]:::mintgreen
    
    Lungs --> Alveoli["Alveoli<br/>Tiny air sacs<br/>Huge surface area for exchange"]:::lightmint
    Lungs --> Bronchi["Bronchi and Bronchioles<br/>Branching airways<br/>Conduct air to alveoli"]:::lightmint
    Lungs --> Surfactant["Surfactant<br/>Reduces surface tension<br/>Prevents alveolar collapse"]:::lightmint
    
    BreathingMechanism --> Inhalation["Inhalation<br/>Diaphragm contracts, descends<br/>Air flows in"]:::lightmint
    BreathingMechanism --> Exhalation["Exhalation<br/>Diaphragm relaxes, ascends<br/>Air flows out"]:::lightmint
    
    GasExchange --> OxygenDiffusion["Oxygen Diffusion<br/>Alveoli to blood<br/>Binds to hemoglobin"]:::lightmint
    GasExchange --> CO2Diffusion["CO2 Diffusion<br/>Blood to alveoli<br/>Expelled from body"]:::lightmint
    AnimalSystems --> Digestive["Digestive System<br/>Food breakdown and absorption<br/>Mechanical and chemical digestion"]:::palegreen
    
    Digestive --> Mouth["Mouth<br/>Mechanical breakdown<br/>Saliva begins starch digestion"]:::mintgreen
    Digestive --> Esophagus["Esophagus<br/>Transports food<br/>Peristalsis moves bolus"]:::mintgreen
    Digestive --> Stomach["Stomach<br/>Churning and acid digestion<br/>Gastric juice, pepsin"]:::mintgreen
    Digestive --> SmallIntestine["Small Intestine<br/>Main absorption site<br/>Duodenum, jejunum, ileum"]:::mintgreen
    Digestive --> LargeIntestine["Large Intestine<br/>Water absorption<br/>Forms feces"]:::mintgreen
    Digestive --> Liver["Liver<br/>Produces bile<br/>Detoxification, metabolism"]:::mintgreen
    Digestive --> Pancreas["Pancreas<br/>Digestive enzymes<br/>Bicarbonate neutralizes acid"]:::mintgreen
    
    Mouth --> SalivaryAmylase["Salivary Amylase<br/>Breaks down starch<br/>Chemical digestion starts"]:::lightmint
    
    Stomach --> GastricJuice["Gastric Juice<br/>HCl and pepsin<br/>Protein digestion"]:::lightmint
    Stomach --> ChymeFormation["Chyme Formation<br/>Acidic, partially digested food<br/>Released to small intestine"]:::lightmint
    
    SmallIntestine --> Villi["Villi and Microvilli<br/>Finger-like projections<br/>Increase absorption surface"]:::lightmint
    SmallIntestine --> EnzymaticDigestion["Enzymatic Digestion<br/>Pancreatic and intestinal enzymes<br/>Complete breakdown"]:::lightmint
    SmallIntestine --> NutrientAbsorption["Nutrient Absorption<br/>Into bloodstream and lymph<br/>Amino acids, sugars, fatty acids"]:::lightmint
    
    Liver --> BileProduction["Bile Production<br/>Emulsifies fats<br/>Stored in gallbladder"]:::lightmint
    
    Pancreas --> PancreaticEnzymes["Pancreatic Enzymes<br/>Amylase, lipase, proteases<br/>Digest carbs, fats, proteins"]:::lightmint
    AnimalSystems --> Nervous["Nervous System<br/>Rapid communication<br/>Brain, spinal cord, nerves"]:::palegreen
    AnimalSystems --> Endocrine["Endocrine System<br/>Hormonal regulation<br/>Slower, longer-lasting signals"]:::palegreen
    
    Endocrine --> Hormones["Hormones<br/>Chemical messengers in blood<br/>Target specific cells"]:::mintgreen
    Endocrine --> PituitaryGland["Pituitary Gland<br/>Master gland<br/>Controls other endocrine glands"]:::mintgreen
    Endocrine --> ThyroidGland["Thyroid Gland<br/>Metabolism regulation<br/>Thyroxine hormone"]:::mintgreen
    Endocrine --> PancreasEndocrine["Pancreas (Endocrine)<br/>Blood sugar regulation<br/>Insulin and glucagon"]:::mintgreen
    Endocrine --> AdrenalGlands["Adrenal Glands<br/>Stress response<br/>Cortisol and adrenaline"]:::mintgreen
    
    Hormones --> SteroidHormones["Steroid Hormones<br/>Lipid-soluble<br/>Enter nucleus, affect transcription"]:::lightmint
    Hormones --> PeptideHormones["Peptide Hormones<br/>Water-soluble<br/>Bind surface receptors, second messengers"]:::lightmint
    
    PancreasEndocrine --> Insulin["Insulin<br/>Lowers blood glucose<br/>Promotes uptake into cells"]:::lightmint
    PancreasEndocrine --> Glucagon["Glucagon<br/>Raises blood glucose<br/>Stimulates glycogen breakdown"]:::lightmint
    
    AnimalSystems --> Immune["Immune System<br/>Defense against pathogens<br/>Innate and adaptive immunity"]:::palegreen
    
    Circulatory --> HeartStruct["Heart Structure<br/>Muscular pump<br/>Chambers and valves"]:::mintgreen
    Circulatory --> BloodVessels["Blood Vessels<br/>Arteries, veins, capillaries<br/>Transport network"]:::mintgreen
    Circulatory --> BloodComponents["Blood Components<br/>Plasma, RBCs, WBCs, platelets<br/>Transport and defense functions"]:::mintgreen
    Circulatory --> CardiacCycle["Cardiac Cycle<br/>Systole and diastole<br/>Rhythmic contraction"]:::mintgreen
    
    HeartStruct --> FourChambers["Four Chambers<br/>Two atria, two ventricles<br/>Separation of oxygenated/deoxygenated"]:::lightmint
    HeartStruct --> Valves["Heart Valves<br/>Prevent backflow<br/>AV valves and semilunar valves"]:::lightmint
    HeartStruct --> MyocardiumContraction["Myocardium<br/>Cardiac muscle tissue<br/>Contracts rhythmically"]:::lightmint
    
    Valves --> AtrioventricularValves["AV Valves<br/>Tricuspid and mitral<br/>Between atria and ventricles"]:::lightmint
    Valves --> SemilunarValves["Semilunar Valves<br/>Pulmonary and aortic<br/>Exit ventricles"]:::lightmint
    
    BloodVessels --> Arteries["Arteries<br/>Carry blood from heart<br/>Thick walls, high pressure"]:::lightmint
    BloodVessels --> Veins["Veins<br/>Carry blood to heart<br/>Thin walls, valves prevent backflow"]:::lightmint
    BloodVessels --> Capillaries["Capillaries<br/>Exchange sites<br/>One cell thick, extensive network"]:::lightmint
    
    Arteries --> Aorta["Aorta<br/>Largest artery<br/>Distributes to systemic circulation"]:::lightmint
    Arteries --> PulmonaryArtery["Pulmonary Artery<br/>Carries deoxygenated blood<br/>To lungs"]:::lightmint
    
    BloodComponents --> Plasma["Plasma<br/>Liquid component (55%)<br/>Water, proteins, nutrients, wastes"]:::lightmint
    BloodComponents --> RedBloodCells["Red Blood Cells (Erythrocytes)<br/>Oxygen transport<br/>Hemoglobin protein"]:::lightmint
    BloodComponents --> WhiteBloodCells["White Blood Cells (Leukocytes)<br/>Immune defense<br/>Various types"]:::lightmint
    BloodComponents --> Platelets["Platelets (Thrombocytes)<br/>Blood clotting<br/>Cell fragments"]:::lightmint
    
    RedBloodCells --> Hemoglobin["Hemoglobin<br/>Iron-containing protein<br/>Binds oxygen"]:::lightmint
    
    CardiacCycle --> Systole["Systole<br/>Contraction phase<br/>Pumps blood out"]:::lightmint
    CardiacCycle --> Diastole["Diastole<br/>Relaxation phase<br/>Chambers fill with blood"]:::lightmint
    CardiacCycle --> HeartRate["Heart Rate<br/>Beats per minute<br/>Regulated by autonomic nervous system"]:::lightmint
    
    Nervous --> Neurons["Neurons<br/>Nerve cells<br/>Electrical and chemical signaling"]:::mintgreen
    Nervous --> ActionPotential["Action Potential<br/>Electrical signal propagation<br/>All-or-none response"]:::mintgreen
    Nervous --> Synapse["Synapse<br/>Junction between neurons<br/>Chemical or electrical transmission"]:::mintgreen
    Nervous --> Brain["Brain<br/>Central control center<br/>Integration and processing"]:::mintgreen
    Nervous --> SensoryReceptors["Sensory Receptors<br/>Detect stimuli<br/>Convert to neural signals"]:::mintgreen
    Nervous --> MotorControl["Motor Control<br/>Movement coordination<br/>Voluntary and involuntary"]:::mintgreen
    
    Neurons --> NeuronStructure["Neuron Structure<br/>Dendrites, cell body, axon<br/>Specialized for signaling"]:::lightmint
    Neurons --> NeuronTypes["Neuron Types<br/>Sensory, motor, interneurons<br/>Different functions"]:::lightmint
    
    ActionPotential --> RestingPotential["Resting Potential<br/>-70 mV<br/>Na+/K+ pump maintains"]:::lightmint
    ActionPotential --> Depolarization["Depolarization<br/>Na+ channels open<br/>Membrane potential rises"]:::lightmint
    ActionPotential --> Repolarization["Repolarization<br/>K+ channels open<br/>Returns to resting state"]:::lightmint
    ActionPotential --> MyelinSheath["Myelin Sheath<br/>Insulates axon<br/>Saltatory conduction"]:::lightmint
    
    Synapse --> Neurotransmitters["Neurotransmitters<br/>Chemical messengers<br/>Acetylcholine, dopamine, serotonin"]:::lightmint
    Synapse --> SynapticCleft["Synaptic Cleft<br/>Gap between neurons<br/>Neurotransmitter diffusion"]:::lightmint
    Synapse --> Receptors["Neurotransmitter Receptors<br/>Postsynaptic membrane<br/>Bind and trigger response"]:::lightmint
    
    Brain --> Cerebrum["Cerebrum<br/>Higher functions<br/>Thought, memory, voluntary movement"]:::lightmint
    Brain --> Cerebellum["Cerebellum<br/>Coordination and balance<br/>Motor control refinement"]:::lightmint
    Brain --> Brainstem["Brainstem<br/>Basic life functions<br/>Breathing, heart rate"]:::lightmint
    
    SensoryReceptors --> Photoreceptors["Photoreceptors<br/>Light detection<br/>Rods and cones in retina"]:::lightmint
    SensoryReceptors --> Mechanoreceptors["Mechanoreceptors<br/>Touch, pressure, sound<br/>Hair cells in ear"]:::lightmint
    SensoryReceptors --> Chemoreceptors["Chemoreceptors<br/>Taste and smell<br/>Chemical detection"]:::lightmint
    
    MotorControl --> SomaticNervous["Somatic Nervous System<br/>Voluntary movement<br/>Skeletal muscle control"]:::lightmint
    MotorControl --> AutonomicNervous["Autonomic Nervous System<br/>Involuntary functions<br/>Sympathetic and parasympathetic"]:::lightmint
    
    Immune --> InnateImmunity["Innate Immunity<br/>Non-specific defenses<br/>Barriers, phagocytes, inflammation"]:::mintgreen
    Immune --> AdaptiveImmunity["Adaptive Immunity<br/>Specific pathogen recognition<br/>B and T lymphocytes"]:::mintgreen
    Immune --> Antibodies["Antibodies<br/>Proteins recognizing antigens<br/>Produced by B cells"]:::mintgreen
    
    InnateImmunity --> PhysicalBarriers["Physical Barriers<br/>Skin and mucous membranes<br/>First line of defense"]:::lightmint
    InnateImmunity --> Phagocytes["Phagocytes<br/>Engulf pathogens<br/>Macrophages and neutrophils"]:::lightmint
    InnateImmunity --> InflammatoryResponse["Inflammatory Response<br/>Redness, swelling, heat, pain<br/>Recruits immune cells"]:::lightmint
    InnateImmunity --> InterferonsNK["Interferons and NK Cells<br/>Antiviral response<br/>Interfere with replication"]:::lightmint
    
    AdaptiveImmunity --> BCells["B Cells<br/>Produce antibodies<br/>Humoral immunity"]:::lightmint
    AdaptiveImmunity --> TCells["T Cells<br/>Cell-mediated immunity<br/>Helper T and Cytotoxic T cells"]:::lightmint
    AdaptiveImmunity --> MemoryCells["Memory Cells<br/>Long-lived lymphocytes<br/>Rapid secondary response"]:::lightmint
    AdaptiveImmunity --> AntigenPresentation["Antigen Presentation<br/>MHC molecules display antigens<br/>Activates T cells"]:::lightmint
    
    BCells --> PlasmaCell["Plasma Cells<br/>Differentiated B cells<br/>Secrete large amounts of antibodies"]:::lightmint
    
    TCells --> HelperTCells["Helper T Cells (CD4+)<br/>Coordinate immune response<br/>Activate B cells and cytotoxic T cells"]:::lightmint
    TCells --> CytotoxicTCells["Cytotoxic T Cells (CD8+)<br/>Kill infected cells<br/>Release perforin and granzymes"]:::lightmint
    
    Antibodies --> AntibodyStructure["Antibody Structure<br/>Y-shaped protein<br/>Variable and constant regions"]:::lightmint
    Antibodies --> AntigenBinding["Antigen Binding<br/>Specific recognition<br/>Lock-and-key fit"]:::lightmint
    Antibodies --> AntibodyFunctions["Antibody Functions<br/>Neutralization, opsonization, complement activation<br/>Multiple mechanisms"]:::lightmint
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
```