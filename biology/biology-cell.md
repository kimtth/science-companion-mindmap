```mermaid
flowchart LR
    Start([Cell Biology]):::green
    Start --> CellStructure["Cell Structure<br/>Organization of cellular components<br/>Defines cell function and capabilities"]:::lightgreen
    Start --> Membrane["Membrane Structure<br/>Lipid bilayer with proteins<br/>Controls what enters and exits cell"]:::lightgreen
    Start --> CellMetabolism["Cell Metabolism<br/>Chemical reactions in cells<br/>Energy production and utilization"]:::lightgreen
    Start --> CellDivision["Cell Division<br/>Process of cell reproduction<br/>Growth, repair, and reproduction"]:::lightgreen
    Start --> CellSignaling["Cell Communication<br/>Signal transduction pathways<br/>Coordinates cellular activities"]:::lightgreen
    
    CellStructure --> Prokaryote["Prokaryotic Cells<br/>No membrane-bound nucleus<br/>Bacteria and archaea"]:::palegreen
    CellStructure --> Eukaryote["Eukaryotic Cells<br/>Membrane-bound organelles<br/>Plants, animals, fungi, protists"]:::palegreen
    
    Prokaryote --> Nucleoid["Nucleoid<br/>DNA region without membrane<br/>Circular chromosome"]:::mintgreen
    Prokaryote --> Plasmids["Plasmids<br/>Small circular DNA<br/>Carry additional genes"]:::mintgreen
    Prokaryote --> CellWallProk["Cell Wall<br/>Peptidoglycan structure<br/>Provides rigidity and protection"]:::mintgreen
    Prokaryote --> Capsule["Capsule<br/>Polysaccharide layer<br/>Protection and adhesion"]:::mintgreen
    Prokaryote --> Pili["Pili<br/>Hair-like appendages<br/>Attachment and conjugation"]:::mintgreen
    Prokaryote --> FlagellaProk["Flagella<br/>Whip-like locomotion<br/>Rotary motor driven"]:::mintgreen
    Prokaryote --> RibosomesProk["70S Ribosomes<br/>Smaller than eukaryotic<br/>Protein synthesis sites"]:::mintgreen
    
    CellWallProk --> Peptidoglycan["Peptidoglycan Layer<br/>Sugar-amino acid polymer<br/>Target of antibiotics"]:::lightmint
    CellWallProk --> GramPositive["Gram-Positive<br/>Thick peptidoglycan layer<br/>Stains purple"]:::lightmint
    CellWallProk --> GramNegative["Gram-Negative<br/>Thin peptidoglycan, outer membrane<br/>Stains pink"]:::lightmint
    
    FlagellaProk --> FlagellarMotor["Flagellar Motor<br/>Proton-driven rotation<br/>Embedded in cell membrane"]:::lightmint
    FlagellaProk --> FlagellinProtein["Flagellin Protein<br/>Structural filament<br/>Helical propeller"]:::lightmint
    
    Plasmids --> RGenes["Resistance Genes<br/>Antibiotic resistance<br/>Horizontal gene transfer"]:::lightmint
    Plasmids --> ConjugationPlasmid["Conjugation Plasmids<br/>F-plasmid type<br/>Enables DNA transfer"]:::lightmint
    
    Eukaryote --> Nucleus["Nucleus<br/>Houses genetic material<br/>Control center of cell"]:::mintgreen
    Eukaryote --> Mitochondria["Mitochondria<br/>Powerhouse of cell<br/>ATP production via cellular respiration"]:::mintgreen
    Eukaryote --> Chloroplast["Chloroplasts<br/>Site of photosynthesis in plants<br/>Converts light to chemical energy"]:::mintgreen
    Eukaryote --> ER["Endoplasmic Reticulum<br/>Protein and lipid synthesis<br/>Rough and smooth types"]:::mintgreen
    Eukaryote --> Golgi["Golgi Apparatus<br/>Modifies and packages proteins<br/>Shipping center of cell"]:::mintgreen
    Eukaryote --> Lysosome["Lysosomes<br/>Digestive organelles<br/>Break down waste and cellular debris"]:::mintgreen
    Eukaryote --> Peroxisome["Peroxisomes<br/>Oxidative reactions<br/>Break down fatty acids and H₂O₂"]:::mintgreen
    Eukaryote --> Vacuole["Vacuoles<br/>Storage and turgor pressure<br/>Large in plant cells"]:::mintgreen
    Eukaryote --> Cytoskeleton["Cytoskeleton<br/>Structural framework<br/>Maintains shape and enables movement"]:::mintgreen
    Eukaryote --> Ribosome["Ribosomes<br/>Protein synthesis sites<br/>Free or attached to ER"]:::mintgreen
    
    Nucleus --> NuclearEnvelope["Nuclear Envelope<br/>Double membrane<br/>Regulates nuclear-cytoplasmic exchange"]:::lightmint
    Nucleus --> Chromatin["Chromatin<br/>DNA-protein complex<br/>Condenses into chromosomes"]:::lightmint
    Nucleus --> Nucleolus["Nucleolus<br/>Ribosome assembly<br/>rRNA synthesis site"]:::lightmint
    Nucleus --> NuclearPores["Nuclear Pores<br/>Selective gateways<br/>Transport proteins and RNA"]:::lightmint
    
    Mitochondria --> MitoMatrix["Mitochondrial Matrix<br/>Inner compartment<br/>Krebs cycle location"]:::lightmint
    Mitochondria --> CristaeSystem["Cristae<br/>Inner membrane folds<br/>Increases surface area for ETC"]:::lightmint
    Mitochondria --> MitoDNA["Mitochondrial DNA<br/>Circular chromosome<br/>Maternal inheritance"]:::lightmint
    Mitochondria --> ATPSynthase["ATP Synthase<br/>Molecular motor<br/>Produces ATP from H⁺ gradient"]:::lightmint
    
    Chloroplast --> Thylakoid["Thylakoids<br/>Membrane sacs<br/>Light reactions occur here"]:::lightmint
    Chloroplast --> Stroma["Stroma<br/>Fluid-filled space<br/>Calvin cycle location"]:::lightmint
    Chloroplast --> ChloroDNA["Chloroplast DNA<br/>Circular chromosome<br/>Encodes some chloroplast proteins"]:::lightmint
    Chloroplast --> Grana["Grana<br/>Stacked thylakoids<br/>Maximize light absorption"]:::lightmint
    
    ER --> RoughER["Rough ER<br/>Studded with ribosomes<br/>Protein synthesis and processing"]:::lightmint
    ER --> SmoothER["Smooth ER<br/>No ribosomes<br/>Lipid synthesis and detoxification"]:::lightmint
    RoughER --> ProteinFolding["Protein Folding<br/>Chaperones assist<br/>Ensures proper 3D structure"]:::lightmint
    RoughER --> Glycosylation["Glycosylation<br/>Adding sugar chains<br/>Protein modification"]:::lightmint
    
    Golgi --> CisGolgi["Cis Face<br/>Receiving side<br/>Accepts vesicles from ER"]:::lightmint
    Golgi --> TransGolgi["Trans Face<br/>Shipping side<br/>Sends vesicles to destinations"]:::lightmint
    Golgi --> GolgiProcessing["Processing<br/>Modifies proteins and lipids<br/>Sorting and tagging"]:::lightmint
    
    Lysosome --> HydrolyticEnzymes["Hydrolytic Enzymes<br/>Acidic pH environment<br/>Break down macromolecules"]:::lightmint
    Lysosome --> Autophagy["Autophagy<br/>Self-digestion<br/>Recycles damaged organelles"]:::lightmint
    Lysosome --> Phagocytosis["Phagocytosis<br/>Cell eating<br/>Engulfs pathogens or debris"]:::lightmint
    
    Cytoskeleton --> Microfilaments["Microfilaments<br/>Actin filaments, 7nm<br/>Cell movement and shape"]:::lightmint
    Cytoskeleton --> IntermediateFilaments["Intermediate Filaments<br/>8-10nm diameter<br/>Mechanical strength"]:::lightmint
    Cytoskeleton --> Microtubules["Microtubules<br/>Tubulin polymers, 25nm<br/>Tracks for motor proteins"]:::lightmint
    
    Microfilaments --> ActinContraction["Actin-Myosin<br/>Muscle contraction<br/>Cytokinesis and motility"]:::lightmint
    Microtubules --> Centrioles["Centrioles<br/>Organize microtubules<br/>Spindle apparatus formation"]:::lightmint
    Microtubules --> Cilia["Cilia and Flagella<br/>Cell movement<br/>9+2 microtubule arrangement"]:::lightmint
    Microtubules --> MotorProteins["Motor Proteins<br/>Kinesin and dynein<br/>Intracellular transport"]:::lightmint
    
    Membrane --> FluidMosaic["Fluid Mosaic Model<br/>Dynamic membrane structure<br/>Proteins float in lipid bilayer"]:::palegreen
    Membrane --> Phospholipids["Phospholipids<br/>Amphipathic molecules<br/>Hydrophilic heads, hydrophobic tails"]:::palegreen
    Membrane --> MembraneProteins["Membrane Proteins<br/>Integral and peripheral<br/>Transport, receptors, enzymes"]:::palegreen
    Membrane --> Cholesterol["Cholesterol<br/>Membrane fluidity regulator<br/>Prevents crystallization"]:::palegreen
    Membrane --> Glycocalyx["Glycocalyx<br/>Carbohydrate coating<br/>Cell recognition and protection"]:::palegreen
    Membrane --> Transport["Membrane Transport<br/>Movement across membrane<br/>Passive and active mechanisms"]:::palegreen
    
    MembraneProteins --> IntegralProteins["Integral Proteins<br/>Embedded in membrane<br/>Transmembrane domains"]:::mintgreen
    MembraneProteins --> PeripheralProteins["Peripheral Proteins<br/>Surface attachment<br/>Easily removed"]:::mintgreen
    MembraneProteins --> ChannelProteins["Channel Proteins<br/>Aqueous pores<br/>Selective ion passage"]:::mintgreen
    MembraneProteins --> CarrierProteins["Carrier Proteins<br/>Conformational change<br/>Specific molecule transport"]:::mintgreen
    
    Transport --> Diffusion["Simple Diffusion<br/>Movement down concentration gradient<br/>No energy required"]:::mintgreen
    Transport --> Osmosis["Osmosis<br/>Water diffusion across membrane<br/>Critical for cell volume regulation"]:::mintgreen
    Transport --> FacilitatedDiff["Facilitated Diffusion<br/>Protein-mediated passive transport<br/>Specific for certain molecules"]:::mintgreen
    Transport --> ActiveTransport["Active Transport<br/>Movement against gradient<br/>Requires ATP energy"]:::mintgreen
    Transport --> Endocytosis["Endocytosis<br/>Engulfing external material<br/>Brings large molecules into cell"]:::mintgreen
    Transport --> Exocytosis["Exocytosis<br/>Expelling material from cell<br/>Secretion of proteins and waste"]:::mintgreen
    
    Diffusion --> SimpleDiffusionGases["Gas Diffusion<br/>O2, CO2, N2<br/>Small nonpolar molecules"]:::lightmint
    Diffusion --> SimpleDiffusionLipid["Lipid-Soluble Molecules<br/>Steroids, fatty acids<br/>Directly through bilayer"]:::lightmint
    
    Osmosis --> Isotonic["Isotonic Solution<br/>Equal solute concentration<br/>No net water movement"]:::lightmint
    Osmosis --> Hypotonic["Hypotonic Solution<br/>Lower solute outside<br/>Water enters cell (swelling)"]:::lightmint
    Osmosis --> Hypertonic["Hypertonic Solution<br/>Higher solute outside<br/>Water leaves cell (shrinking)"]:::lightmint
    Osmosis --> Aquaporins["Aquaporin Channels<br/>Transmembrane water pores<br/>Facilitate rapid osmosis"]:::lightmint
    
    ActiveTransport --> PrimaryActiveTransport["Primary Active Transport<br/>Direct ATP hydrolysis<br/>Ion pumps"]:::lightmint
    ActiveTransport --> SecondaryActiveTransport["Secondary Active Transport<br/>Coupled to ion gradients<br/>Symport and antiport"]:::lightmint
    
    PrimaryActiveTransport --> SodiumPotassiumPump["Na+/K+ ATPase<br/>3 Na+ out, 2 K+ in<br/>Maintains resting potential"]:::lightmint
    PrimaryActiveTransport --> CalciumPump["Ca2+ Pump<br/>SERCA and PMCA types<br/>Regulates calcium signaling"]:::lightmint
    PrimaryActiveTransport --> ProtonPump["Proton Pump<br/>H+ ATPase<br/>Acidifies organelles"]:::lightmint
    
    Endocytosis --> PhagocytosisTransport["Phagocytosis<br/>Cell eating<br/>Engulfs solid particles"]:::lightmint
    Endocytosis --> PinocytosisTransport["Pinocytosis<br/>Cell drinking<br/>Engulfs fluids"]:::lightmint
    Endocytosis --> ReceptorMediatedEndo["Receptor-Mediated Endocytosis<br/>Clathrin-coated pits<br/>Specific ligand uptake"]:::lightmint
    
    CellMetabolism --> CellularResp["Cellular Respiration<br/>Glucose breakdown for ATP<br/>Aerobic energy production"]:::lightgreen
    CellMetabolism --> Photosynthesis["Photosynthesis<br/>Light energy to chemical energy<br/>Produces glucose and oxygen"]:::lightgreen
    CellMetabolism --> Fermentation["Fermentation<br/>Anaerobic glucose breakdown<br/>Produces ATP without oxygen"]:::lightgreen
    
    CellularResp --> Glycolysis["Glycolysis<br/>Glucose to pyruvate<br/>Occurs in cytoplasm, net 2 ATP"]:::palegreen
    CellularResp --> KrebsCycle["Krebs Cycle<br/>Acetyl-CoA oxidation<br/>Produces NADH, FADH₂, CO₂"]:::palegreen
    CellularResp --> ETC["Electron Transport Chain<br/>Oxidative phosphorylation<br/>Produces ~32-34 ATP per glucose"]:::palegreen
    
    Glycolysis --> GlycolysisPhase1["Energy Investment Phase<br/>2 ATP consumed<br/>Glucose to fructose-1,6-bisphosphate"]:::mintgreen
    Glycolysis --> GlycolysisPhase2["Energy Payoff Phase<br/>4 ATP and 2 NADH produced<br/>2 pyruvate generated"]:::mintgreen
    Glycolysis --> GlycolysisNet["Net Products<br/>2 ATP, 2 NADH, 2 pyruvate<br/>Per glucose molecule"]:::mintgreen
    
    KrebsCycle --> AcetylCoAFormation["Acetyl-CoA Formation<br/>Pyruvate oxidation<br/>Links glycolysis to Krebs"]:::mintgreen
    KrebsCycle --> CitricAcidCycle["Citric Acid Cycle Steps<br/>8 enzymatic reactions<br/>Releases CO2, produces NADH/FADH2"]:::mintgreen
    KrebsCycle --> KrebsProducts["Krebs Products<br/>3 NADH, 1 FADH2, 1 GTP<br/>Per acetyl-CoA (×2 per glucose)"]:::mintgreen
    
    ETC --> ComplexI["Complex I<br/>NADH dehydrogenase<br/>Pumps 4 H+ across membrane"]:::mintgreen
    ETC --> ComplexII["Complex II<br/>Succinate dehydrogenase<br/>Feeds electrons from FADH2"]:::mintgreen
    ETC --> ComplexIII["Complex III<br/>Cytochrome bc1 complex<br/>Pumps 4 H+ across membrane"]:::mintgreen
    ETC --> ComplexIV["Complex IV<br/>Cytochrome c oxidase<br/>Reduces O2 to H2O, pumps 2 H+"]:::mintgreen
    ETC --> ATPSynthaseResp["ATP Synthase<br/>Chemiosmosis<br/>H+ gradient drives ATP synthesis"]:::mintgreen
    
    Photosynthesis --> LightReactions["Light Reactions<br/>Convert light to chemical energy<br/>Produces ATP and NADPH"]:::palegreen
    Photosynthesis --> CalvinCycle["Calvin Cycle<br/>Carbon fixation<br/>Uses ATP and NADPH to make glucose"]:::palegreen
    
    LightReactions --> Photosystem["Photosystems I & II<br/>Light-absorbing complexes<br/>Electron excitation and transport"]:::mintgreen
    LightReactions --> Photolysis["Photolysis<br/>Water splitting<br/>Source of electrons and O₂"]:::mintgreen
    
    Photosystem --> PSII["Photosystem II<br/>P680 reaction center<br/>Oxidizes water, generates O2"]:::lightmint
    Photosystem --> PSI["Photosystem I<br/>P700 reaction center<br/>Reduces NADP+ to NADPH"]:::lightmint
    Photosystem --> ElectronTransportThylakoid["Thylakoid Electron Transport<br/>Plastoquinone, cytochrome b6f<br/>Generates proton gradient"]:::lightmint
    
    CalvinCycle --> CarbonFixation["Carbon Fixation<br/>RuBisCO enzyme<br/>CO2 + RuBP → 3-PGA"]:::mintgreen
    CalvinCycle --> ReductionPhase["Reduction Phase<br/>3-PGA to G3P<br/>Consumes ATP and NADPH"]:::mintgreen
    CalvinCycle --> RegenerationPhase["Regeneration Phase<br/>G3P to RuBP<br/>Continues the cycle"]:::mintgreen
    
    Fermentation --> LacticAcidFerm["Lactic Acid Fermentation<br/>Pyruvate to lactate<br/>Muscle cells, bacteria"]:::palegreen
    Fermentation --> AlcoholicFerm["Alcoholic Fermentation<br/>Pyruvate to ethanol + CO2<br/>Yeast, some bacteria"]:::palegreen
    Fermentation --> NADRegeneration["NAD+ Regeneration<br/>Allows glycolysis to continue<br/>Without oxygen"]:::palegreen
    
    CellDivision --> Mitosis["Mitosis<br/>Produces two identical cells<br/>Growth and repair"]:::lightgreen
    CellDivision --> Meiosis["Meiosis<br/>Produces four gametes<br/>Sexual reproduction, halves chromosome number"]:::lightgreen
    CellDivision --> CellCycle["Cell Cycle<br/>G1, S, G2, M phases<br/>Regulated growth and division"]:::lightgreen
    
    CellCycle --> Interphase["Interphase<br/>G1, S, G2 phases<br/>Cell growth and DNA replication"]:::palegreen
    CellCycle --> MPhase["M Phase<br/>Mitosis and cytokinesis<br/>Nuclear and cytoplasmic division"]:::palegreen
    CellCycle --> Checkpoints["Cell Cycle Checkpoints<br/>G1/S, G2/M, spindle<br/>Quality control mechanisms"]:::palegreen
    
    Interphase --> G1Phase["G1 Phase<br/>Cell growth<br/>Organelle synthesis, accumulates materials"]:::mintgreen
    Interphase --> SPhase["S Phase<br/>DNA replication<br/>Chromosome duplication"]:::mintgreen
    Interphase --> G2Phase["G2 Phase<br/>Continued growth<br/>Preparation for mitosis"]:::mintgreen
    Interphase --> G0Phase["G0 Phase<br/>Quiescent state<br/>Non-dividing cells exit cycle"]:::mintgreen
    
    Mitosis --> Prophase["Prophase<br/>Chromatin condenses<br/>Spindle apparatus forms"]:::palegreen
    Mitosis --> Metaphase["Metaphase<br/>Chromosomes align at equator<br/>Spindle attaches to centromeres"]:::palegreen
    Mitosis --> Anaphase["Anaphase<br/>Sister chromatids separate<br/>Move to opposite poles"]:::palegreen
    Mitosis --> Telophase["Telophase<br/>Nuclear envelopes reform<br/>Chromosomes decondense"]:::palegreen
    Mitosis --> Cytokinesis["Cytokinesis<br/>Cytoplasm divides<br/>Two separate daughter cells"]:::palegreen
    
    Prophase --> ChromatinCondensation["Chromatin Condensation<br/>DNA coils tightly<br/>Visible chromosomes"]:::mintgreen
    Prophase --> CentriolesSeparate["Centrioles Separate<br/>Move to opposite poles<br/>Nucleate spindle microtubules"]:::mintgreen
    Prophase --> NuclearEnvelopeBreakdown["Nuclear Envelope Breakdown<br/>Prometaphase transition<br/>Kinetochores accessible"]:::mintgreen
    
    Metaphase --> MetaphasePlate["Metaphase Plate<br/>Chromosomes at cell equator<br/>Maximum condensation"]:::mintgreen
    Metaphase --> SpindleAttachment["Spindle Attachment<br/>Kinetochores bind microtubules<br/>Tension equilibrium"]:::mintgreen
    Metaphase --> SpindleCheckpoint["Spindle Assembly Checkpoint<br/>Monitors attachment<br/>Prevents premature anaphase"]:::mintgreen
    
    Anaphase --> SisterChromatidSeparation["Sister Chromatid Separation<br/>Cohesin cleavage<br/>Independent chromosomes"]:::mintgreen
    Anaphase --> PolewardMovement["Poleward Movement<br/>Motor proteins pull<br/>Microtubule shortening"]:::mintgreen
    Anaphase --> CellElongation["Cell Elongation<br/>Non-kinetochore microtubules<br/>Push poles apart"]:::mintgreen
    
    Cytokinesis --> CleavageFurrow["Cleavage Furrow<br/>Actin-myosin contractile ring<br/>Animal cells"]:::mintgreen
    Cytokinesis --> CellPlateFormation["Cell Plate Formation<br/>Vesicles fuse at midline<br/>Plant cells"]:::mintgreen
    
    Meiosis --> MeiosisI["Meiosis I<br/>Reductional division<br/>Homologous chromosomes separate"]:::palegreen
    Meiosis --> MeiosisII["Meiosis II<br/>Equational division<br/>Sister chromatids separate"]:::palegreen
    Meiosis --> CrossingOver["Crossing Over<br/>Genetic recombination<br/>Occurs in prophase I"]:::palegreen
    
    MeiosisI --> ProphaseI["Prophase I<br/>Synapsis and recombination<br/>Longest meiotic phase"]:::mintgreen
    MeiosisI --> MetaphaseI["Metaphase I<br/>Bivalents at metaphase plate<br/>Random orientation"]:::mintgreen
    MeiosisI --> AnaphaseI["Anaphase I<br/>Homologs separate<br/>Sister chromatids stay together"]:::mintgreen
    MeiosisI --> TelophaseI["Telophase I<br/>Nuclear envelopes reform<br/>Cells are now haploid"]:::mintgreen
    
    ProphaseI --> Leptotene["Leptotene<br/>Chromosome condensation begins<br/>Individual chromatids visible"]:::lightmint
    ProphaseI --> Zygotene["Zygotene<br/>Synapsis begins<br/>Synaptonemal complex forms"]:::lightmint
    ProphaseI --> Pachytene["Pachytene<br/>Crossing over occurs<br/>Homologs fully synapsed"]:::lightmint
    ProphaseI --> Diplotene["Diplotene<br/>Chiasmata visible<br/>Synaptonemal complex dissolves"]:::lightmint
    ProphaseI --> Diakinesis["Diakinesis<br/>Maximum condensation<br/>Prepares for metaphase I"]:::lightmint
    
    MeiosisII --> ProphaseII["Prophase II<br/>Chromosomes recondense<br/>Spindles form"]:::mintgreen
    MeiosisII --> MetaphaseII["Metaphase II<br/>Chromosomes at equator<br/>Similar to mitotic metaphase"]:::mintgreen
    MeiosisII --> AnaphaseII["Anaphase II<br/>Sister chromatids separate<br/>Now individual chromosomes"]:::mintgreen
    MeiosisII --> TelophaseII["Telophase II<br/>Four haploid nuclei<br/>Genetically unique gametes"]:::mintgreen
    Meiosis --> CrossingOver["Crossing Over<br/>Genetic recombination<br/>Increases variation in gametes"]:::palegreen
    
    CellSignaling --> Receptors["Cell Receptors<br/>Detect external signals<br/>Proteins on membrane or inside cell"]:::palegreen
    CellSignaling --> Receptors["Cell Receptors<br/>Receive external signals<br/>Ligand-binding proteins"]:::lightgreen
    CellSignaling --> SignalTransduction["Signal Transduction<br/>Relay signal into cell<br/>Cascade of molecular interactions"]:::lightgreen
    CellSignaling --> Response["Cellular Response<br/>Changes in cell behavior<br/>Gene expression or enzyme activity"]:::lightgreen
    
    Receptors --> GPCR["G Protein-Coupled Receptors<br/>Seven transmembrane domains<br/>Activate G proteins"]:::palegreen
    Receptors --> RTK["Receptor Tyrosine Kinases<br/>Enzyme-linked receptors<br/>Phosphorylate tyrosine residues"]:::palegreen
    Receptors --> IonChannelReceptors["Ion Channel Receptors<br/>Ligand-gated channels<br/>Rapid electrical signaling"]:::palegreen
    Receptors --> IntracellularReceptors["Intracellular Receptors<br/>Nuclear or cytoplasmic<br/>Bind lipid-soluble signals"]:::palegreen
    
    GPCR --> GProteinActivation["G Protein Activation<br/>GDP to GTP exchange<br/>Alpha subunit dissociates"]:::mintgreen
    GPCR --> CyclicAMPPathway["cAMP Pathway<br/>Adenylyl cyclase activation<br/>Activates protein kinase A"]:::mintgreen
    GPCR --> PhospholipaseC["Phospholipase C Pathway<br/>IP3 and DAG production<br/>Ca2+ release and PKC activation"]:::mintgreen
    
    RTK --> Dimerization["Receptor Dimerization<br/>Ligand binding causes pairing<br/>Cross-phosphorylation"]:::mintgreen
    RTK --> RasPathway["Ras-MAPK Pathway<br/>GTPase signaling cascade<br/>Gene expression regulation"]:::mintgreen
    RTK --> PI3KAkt["PI3K-Akt Pathway<br/>Cell survival and growth<br/>Metabolic regulation"]:::mintgreen
    
    SignalTransduction --> SecondMessengers["Second Messengers<br/>Amplify signals<br/>cAMP, Ca2+, IP3, DAG"]:::palegreen
    SignalTransduction --> ProteinKinaseCascades["Protein Kinase Cascades<br/>Sequential phosphorylation<br/>Signal amplification"]:::palegreen
    SignalTransduction --> CalciumSignaling["Calcium Signaling<br/>Ca2+ ions as messengers<br/>Regulates many processes"]:::palegreen
    
    SecondMessengers --> cAMPMessenger["Cyclic AMP<br/>From ATP by adenylyl cyclase<br/>Activates PKA"]:::mintgreen
    SecondMessengers --> CalciumIon["Ca2+ Ion<br/>Released from ER stores<br/>Binds calmodulin"]:::mintgreen
    SecondMessengers --> IP3Messenger["IP3 (Inositol Triphosphate)<br/>Triggers Ca2+ release<br/>From endoplasmic reticulum"]:::mintgreen
    SecondMessengers --> DAGMessenger["DAG (Diacylglycerol)<br/>Remains in membrane<br/>Activates protein kinase C"]:::mintgreen
    
    ProteinKinaseCascades --> MAPKCascade["MAPK Cascade<br/>Raf → MEK → ERK<br/>Controls proliferation"]:::mintgreen
    ProteinKinaseCascades --> PhosphorylationRegulation["Phosphorylation Regulation<br/>Adds/removes phosphate groups<br/>Changes protein activity"]:::mintgreen
    
    Response --> GeneExpression["Gene Expression Changes<br/>Transcription factors activated<br/>Alters protein production"]:::palegreen
    Response --> EnzymeActivity["Enzyme Activity Changes<br/>Metabolic alterations<br/>Immediate cellular effects"]:::palegreen
    Response --> CytoskeletalChanges["Cytoskeletal Rearrangements<br/>Cell shape and motility<br/>Migration and division"]:::palegreen
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
    classDef lightmint fill:#bbf7d0,stroke:#86efac,stroke-width:1px,color:#000
```