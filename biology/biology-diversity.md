```mermaid
flowchart LR
    Start([Diversity of Life]):::green
    Start --> Viruses["Viruses<br/>Non-cellular infectious agents<br/>Require host cells to reproduce"]:::lightgreen
    Start --> Prokaryotes["Prokaryotes<br/>Bacteria and Archaea<br/>Single-celled, no nucleus"]:::lightgreen
    Start --> Protists["Protists<br/>Diverse eukaryotic organisms<br/>Not plants, animals, or fungi"]:::lightgreen
    Start --> Fungi["Fungi<br/>Decomposers and symbionts<br/>Chitin cell walls, absorptive nutrition"]:::lightgreen
    
    Protists --> ProtistGroups["Protist Groups<br/>Diverse eukaryotic organisms<br/>Not plants, animals, or fungi"]:::palegreen
    
    ProtistGroups --> Algae["Algae<br/>Photosynthetic protists<br/>Aquatic primary producers"]:::mintgreen
    ProtistGroups --> Protozoa["Protozoa<br/>Animal-like protists<br/>Heterotrophic, motile"]:::mintgreen
    ProtistGroups --> SlimeMolds["Slime Molds<br/>Fungus-like protists<br/>Decomposers"]:::mintgreen
    
    Algae --> GreenAlgae["Green Algae<br/>Chlorophyll a and b<br/>Ancestors of land plants"]:::lightmint
    Algae --> RedAlgae["Red Algae<br/>Phycobilins<br/>Deep water, coralline algae"]:::lightmint
    Algae --> BrownAlgae["Brown Algae<br/>Fucoxanthin<br/>Kelp and seaweeds"]:::lightmint
    Algae --> Diatoms["Diatoms<br/>Silica cell walls<br/>Marine phytoplankton"]:::lightmint
    
    Protozoa --> Amoeboids["Amoeboids<br/>Pseudopods for movement<br/>Amoeba proteus"]:::lightmint
    Protozoa --> Ciliates["Ciliates<br/>Cilia for movement<br/>Paramecium"]:::lightmint
    Protozoa --> Flagellates["Flagellates<br/>Flagella for movement<br/>Trypanosoma, Giardia"]:::lightmint
    Protozoa --> Apicomplexans["Apicomplexans<br/>Parasitic protists<br/>Plasmodium (malaria)"]:::lightmint
    Fungi --> FungiStructure["Fungal Structure<br/>Hyphae and mycelium<br/>Chitin cell walls"]:::palegreen
    Fungi --> FungiReproduction["Fungal Reproduction<br/>Spores<br/>Sexual and asexual"]:::palegreen
    Fungi --> FungiEcology["Fungal Ecology<br/>Decomposers and symbionts<br/>Nutrient recycling"]:::palegreen
    Fungi --> FungiGroups["Fungal Groups<br/>Chytrids, zygomycetes, ascomycetes, basidiomycetes<br/>Diverse phyla"]:::palegreen
    
    FungiStructure --> Hyphae["Hyphae<br/>Filamentous structures<br/>Absorptive feeding"]:::mintgreen
    FungiStructure --> Mycelium["Mycelium<br/>Network of hyphae<br/>Extensive underground"]:::mintgreen
    FungiStructure --> Septa["Septa<br/>Cross-walls in hyphae<br/>Compartmentalization"]:::mintgreen
    
    FungiReproduction --> AsexualSpores["Asexual Spores<br/>Conidia, sporangiospores<br/>Rapid dispersal"]:::mintgreen
    FungiReproduction --> SexualReproduction["Sexual Reproduction<br/>Plasmogamy and karyogamy<br/>Genetic recombination"]:::mintgreen
    
    SexualReproduction --> Plasmogamy["Plasmogamy<br/>Cytoplasm fusion<br/>Forms dikaryotic stage"]:::lightmint
    SexualReproduction --> Karyogamy["Karyogamy<br/>Nuclear fusion<br/>Forms diploid zygote"]:::lightmint
    SexualReproduction --> Meiosis["Meiosis<br/>Produces haploid spores<br/>Returns to haploid state"]:::lightmint
    
    FungiEcology --> Decomposers["Decomposers<br/>Break down organic matter<br/>Nutrient recycling"]:::mintgreen
    FungiEcology --> MycorrhizaeFungi["Mycorrhizae<br/>Root-fungus mutualism<br/>Nutrient exchange"]:::mintgreen
    FungiEcology --> LichensFungi["Lichens<br/>Fungus-algae symbiosis<br/>Pioneer species"]:::mintgreen
    
    FungiGroups --> Ascomycetes["Ascomycetes<br/>Sac fungi<br/>Yeasts, morels, truffles"]:::mintgreen
    FungiGroups --> Basidiomycetes["Basidiomycetes<br/>Club fungi<br/>Mushrooms, puffballs, rusts"]:::mintgreen
    FungiGroups --> Zygomycetes["Zygomycetes<br/>Bread molds<br/>Rhizopus"]:::mintgreen
    Start --> PlantDiversity["Plant Diversity<br/>Evolution of land plants<br/>From bryophytes to angiosperms"]:::lightgreen
    Start --> AnimalDiversity["Animal Diversity<br/>Evolution of animal phyla<br/>From sponges to vertebrates"]:::lightgreen
    Start --> Phylogeny["Phylogeny<br/>Evolutionary relationships<br/>Tree of life organization"]:::lightgreen
    
    Viruses --> VirusStructure["Virus Structure<br/>Nucleic acid in protein coat<br/>Enveloped or non-enveloped"]:::palegreen
    Viruses --> ViralReplication["Viral Replication<br/>Lytic and lysogenic cycles<br/>Hijacks host machinery"]:::palegreen
    Viruses --> VirusClassification["Virus Classification<br/>DNA vs RNA, single vs double stranded<br/>Baltimore classification"]:::palegreen
    
    VirusStructure --> Capsid["Capsid<br/>Protein coat<br/>Protects genetic material"]:::mintgreen
    VirusStructure --> Envelope["Viral Envelope<br/>Lipid bilayer from host<br/>Glycoprotein spikes"]:::mintgreen
    VirusStructure --> NucleicAcid["Viral Nucleic Acid<br/>DNA or RNA<br/>Single or double stranded"]:::mintgreen
    
    Capsid --> HelicalCapsid["Helical Capsid<br/>Rod-shaped<br/>Tobacco mosaic virus"]:::lightmint
    Capsid --> IcosahedralCapsid["Icosahedral Capsid<br/>20-sided symmetry<br/>Poliovirus, adenovirus"]:::lightmint
    
    ViralReplication --> LyticCycle["Lytic Cycle<br/>Destroys host cell<br/>Rapid reproduction"]:::mintgreen
    ViralReplication --> LysogenicCycle["Lysogenic Cycle<br/>Integrates into host genome<br/>Dormant prophage"]:::mintgreen
    
    LyticCycle --> Attachment["Attachment<br/>Viral proteins bind host receptors<br/>Host specificity"]:::lightmint
    LyticCycle --> Penetration["Penetration<br/>Injects nucleic acid<br/>Or endocytosis"]:::lightmint
    LyticCycle --> Replication["Viral Replication<br/>Uses host machinery<br/>Produces viral components"]:::lightmint
    LyticCycle --> Assembly["Assembly<br/>Viral components combine<br/>Forms new virions"]:::lightmint
    LyticCycle --> Release["Release<br/>Cell lysis<br/>New viruses infect other cells"]:::lightmint
    
    LysogenicCycle --> Integration["Integration<br/>Viral DNA into host chromosome<br/>Becomes prophage"]:::lightmint
    LysogenicCycle --> Induction["Induction<br/>Prophage excision<br/>Enters lytic cycle"]:::lightmint
    
    VirusClassification --> DNAViruses["DNA Viruses<br/>Herpes, pox, adenoviruses<br/>Replicate in nucleus"]:::mintgreen
    VirusClassification --> RNAViruses["RNA Viruses<br/>Influenza, HIV, coronaviruses<br/>Replicate in cytoplasm"]:::mintgreen
    VirusClassification --> Retroviruses["Retroviruses<br/>RNA to DNA via reverse transcriptase<br/>HIV example"]:::mintgreen
    
    Prokaryotes --> BacteriaStruct["Bacterial Structure<br/>Cell wall, capsule, flagella<br/>Diverse shapes and arrangements"]:::palegreen
    Prokaryotes --> ArchaeaDomain["Archaea Domain<br/>Extremophiles<br/>Distinct from bacteria"]:::palegreen
    Prokaryotes --> BacterialMetabolism["Bacterial Metabolism<br/>Diverse energy strategies<br/>Chemotrophs, phototrophs"]:::palegreen
    Prokaryotes --> BacterialReproduction["Bacterial Reproduction<br/>Binary fission<br/>Horizontal gene transfer"]:::palegreen
    
    BacteriaStruct --> BacterialShapes["Bacterial Shapes<br/>Cocci, bacilli, spirilla<br/>Morphological diversity"]:::mintgreen
    BacteriaStruct --> CellWallBact["Bacterial Cell Wall<br/>Peptidoglycan<br/>Gram-positive vs gram-negative"]:::mintgreen
    BacteriaStruct --> PiliAndFimbriae["Pili and Fimbriae<br/>Attachment structures<br/>Conjugation and adhesion"]:::mintgreen
    
    BacterialShapes --> Cocci["Cocci<br/>Spherical<br/>Streptococcus, Staphylococcus"]:::lightmint
    BacterialShapes --> Bacilli["Bacilli<br/>Rod-shaped<br/>E. coli, Bacillus"]:::lightmint
    BacterialShapes --> Spirilla["Spirilla and Spirochetes<br/>Spiral-shaped<br/>Vibrio, Treponema"]:::lightmint
    
    ArchaeaDomain --> Methanogens["Methanogens<br/>Produce methane<br/>Anaerobic environments"]:::mintgreen
    ArchaeaDomain --> Halophiles["Halophiles<br/>Extreme salt tolerance<br/>Salt lakes, Dead Sea"]:::mintgreen
    ArchaeaDomain --> Thermophiles["Thermophiles<br/>High temperature tolerance<br/>Hot springs, deep-sea vents"]:::mintgreen
    ArchaeaDomain --> ArchaealMembranes["Archaeal Membranes<br/>Ether linkages<br/>Different from bacteria"]:::mintgreen
    
    BacterialMetabolism --> Photoautotrophs["Photoautotrophs<br/>Light energy, CO2 fixation<br/>Cyanobacteria"]:::mintgreen
    BacterialMetabolism --> Chemoautotrophs["Chemoautotrophs<br/>Inorganic chemical energy<br/>Nitrifying bacteria"]:::mintgreen
    BacterialMetabolism --> Heterotrophs["Heterotrophs<br/>Organic compounds<br/>Decomposers, pathogens"]:::mintgreen
    
    BacterialReproduction --> BinaryFission["Binary Fission<br/>Asexual division<br/>Rapid population growth"]:::mintgreen
    BacterialReproduction --> Conjugation["Conjugation<br/>DNA transfer via pilus<br/>Horizontal gene transfer"]:::mintgreen
    BacterialReproduction --> Transformation["Transformation<br/>Uptake of environmental DNA<br/>Genetic recombination"]:::mintgreen
    BacterialReproduction --> Transduction["Transduction<br/>Viral-mediated DNA transfer<br/>Bacteriophage vectors"]:::mintgreen
    
    PlantDiversity --> Bryophytes["Bryophytes<br/>Mosses, liverworts, hornworts<br/>No vascular tissue, require water"]:::palegreen
    PlantDiversity --> SeedlessVascular["Seedless Vascular Plants<br/>Ferns and relatives<br/>Vascular tissue, no seeds"]:::palegreen
    PlantDiversity --> Gymnosperms["Gymnosperms<br/>Conifers and relatives<br/>Naked seeds in cones"]:::palegreen
    PlantDiversity --> Angiosperms["Angiosperms<br/>Flowering plants<br/>Seeds enclosed in fruits"]:::palegreen
    
    Bryophytes --> Mosses["Mosses<br/>Gametophyte dominant<br/>Rhizoids for attachment"]:::mintgreen
    Bryophytes --> Liverworts["Liverworts<br/>Flattened thallus<br/>Moist habitats"]:::mintgreen
    Bryophytes --> Hornworts["Hornworts<br/>Horn-shaped sporophyte<br/>Continuous spore production"]:::mintgreen
    Bryophytes --> BryophyteReproduction["Bryophyte Reproduction<br/>Requires water for fertilization<br/>Flagellated sperm"]:::mintgreen
    
    SeedlessVascular --> Ferns["Ferns<br/>Dominant sporophyte<br/>Large fronds"]:::mintgreen
    SeedlessVascular --> ClubMosses["Club Mosses<br/>Lycopods<br/>Scale-like leaves"]:::mintgreen
    SeedlessVascular --> Horsetails["Horsetails<br/>Jointed stems<br/>Silica in cell walls"]:::mintgreen
    SeedlessVascular --> FernReproduction["Fern Reproduction<br/>Spores on underside of fronds<br/>Sori and indusia"]:::mintgreen
    
    Gymnosperms --> Conifers["Conifers<br/>Pines, firs, spruces<br/>Needle-like leaves"]:::mintgreen
    Gymnosperms --> Cycads["Cycads<br/>Palm-like appearance<br/>Tropical and subtropical"]:::mintgreen
    Gymnosperms --> Ginkgo["Ginkgo<br/>Single living species<br/>Fan-shaped leaves"]:::mintgreen
    Gymnosperms --> Gnetophytes["Gnetophytes<br/>Unusual group<br/>Welwitschia, Ephedra"]:::mintgreen
    
    Conifers --> ConeStructure["Cone Structure<br/>Male and female cones<br/>Wind pollination"]:::lightmint
    Conifers --> NeedleAdaptations["Needle Adaptations<br/>Reduced water loss<br/>Cold and dry climates"]:::lightmint
    
    Angiosperms --> Monocots["Monocots<br/>One cotyledon<br/>Parallel leaf veins, scattered vascular bundles"]:::mintgreen
    Angiosperms --> Dicots["Eudicots (Dicots)<br/>Two cotyledons<br/>Netted leaf veins, ring vascular bundles"]:::mintgreen
    Angiosperms --> FlowerEvolution["Flower Evolution<br/>Coevolution with pollinators<br/>Rapid diversification"]:::mintgreen
    
    Monocots --> MonocotExamples["Monocot Examples<br/>Grasses, lilies, orchids<br/>Palms, bamboo"]:::lightmint
    Monocots --> MonocotCharacters["Monocot Characteristics<br/>Fibrous roots, floral parts in 3s<br/>No secondary growth"]:::lightmint
    
    Dicots --> DicotsExamples["Eudicot Examples<br/>Roses, oaks, sunflowers<br/>Beans, tomatoes"]:::lightmint
    Dicots --> DicotsCharacters["Eudicot Characteristics<br/>Taproot, floral parts in 4s or 5s<br/>Secondary growth common"]:::lightmint
    
    AnimalDiversity --> Invertebrates["Invertebrates<br/>Animals without backbone<br/>95% of animal species"]:::palegreen
    AnimalDiversity --> Vertebrates["Vertebrates<br/>Animals with backbone<br/>Fish, amphibians, reptiles, birds, mammals"]:::palegreen
    AnimalDiversity --> AnimalCharacteristics["Animal Characteristics<br/>Multicellular, heterotrophic<br/>Nervous tissue, muscle tissue"]:::palegreen
    
    Invertebrates --> Sponges["Sponges - Porifera<br/>Simplest animals<br/>Filter feeders"]:::mintgreen
    Invertebrates --> Cnidarians["Cnidarians<br/>Jellyfish, corals, anemones<br/>Radial symmetry, stinging cells"]:::mintgreen
    Invertebrates --> Flatworms["Flatworms - Platyhelminthes<br/>Bilateral symmetry<br/>No body cavity"]:::mintgreen
    Invertebrates --> Mollusks["Mollusks<br/>Snails, clams, squid<br/>Muscular foot and mantle"]:::mintgreen
    Invertebrates --> Annelids["Annelids<br/>Segmented worms<br/>Earthworms, leeches"]:::mintgreen
    Invertebrates --> Arthropods["Arthropods<br/>Insects, crustaceans, arachnids<br/>Exoskeleton, jointed appendages"]:::mintgreen
    Invertebrates --> Echinoderms["Echinoderms<br/>Sea stars, urchins<br/>Radial symmetry as adults"]:::mintgreen
    
    Sponges --> SpongeFeedingStructure["Sponge Feeding<br/>Choanocytes (collar cells)<br/>Filter water through pores"]:::lightmint
    Sponges --> SpongeSkeleton["Sponge Skeleton<br/>Spicules or spongin<br/>Structural support"]:::lightmint
    
    Cnidarians --> Cnidocytes["Cnidocytes<br/>Stinging cells<br/>Nematocysts for prey capture"]:::lightmint
    Cnidarians --> PolypMedusa["Polyp and Medusa<br/>Two body forms<br/>Sessile and motile"]:::lightmint
    Cnidarians --> GastrovascularCavity["Gastrovascular Cavity<br/>Single opening<br/>Digestion and circulation"]:::lightmint
    
    Mollusks --> Gastropods["Gastropods<br/>Snails and slugs<br/>Torsion, single shell or none"]:::lightmint
    Mollusks --> Bivalves["Bivalves<br/>Clams, oysters, mussels<br/>Two-part hinged shell"]:::lightmint
    Mollusks --> Cephalopods["Cephalopods<br/>Squid, octopus, cuttlefish<br/>Highly developed nervous system"]:::lightmint
    
    Arthropods --> InsectsClass["Insects<br/>Three body parts, six legs<br/>Most diverse animal group"]:::lightmint
    Arthropods --> Crustaceans["Crustaceans<br/>Crabs, lobsters, shrimp<br/>Two pairs antennae"]:::lightmint
    Arthropods --> Arachnids["Arachnids<br/>Spiders, scorpions, ticks<br/>Eight legs, two body parts"]:::lightmint
    Arthropods --> ArthropodExoskeleton["Arthropod Exoskeleton<br/>Chitin cuticle<br/>Molting for growth"]:::lightmint
    
    Vertebrates --> Fishes["Fishes<br/>Aquatic vertebrates<br/>Cartilaginous and bony fish"]:::mintgreen
    Vertebrates --> Amphibians["Amphibians<br/>Frogs, salamanders<br/>Dual life - water and land"]:::mintgreen
    Vertebrates --> Reptiles["Reptiles<br/>Snakes, lizards, turtles<br/>Amniotic egg, scales"]:::mintgreen
    Vertebrates --> Birds["Birds<br/>Feathers and flight<br/>Endothermic, hollow bones"]:::mintgreen
    Vertebrates --> Mammals["Mammals<br/>Hair and mammary glands<br/>Endothermic, diverse habitats"]:::mintgreen
    
    Fishes --> Jawless["Jawless Fish<br/>Lampreys, hagfish<br/>Most primitive vertebrates"]:::lightmint
    Fishes --> Cartilaginous["Cartilaginous Fish<br/>Sharks, rays<br/>Cartilage skeleton"]:::lightmint
    Fishes --> BonyFish["Bony Fish<br/>Most diverse vertebrates<br/>Swim bladder, operculum"]:::lightmint
    
    Amphibians --> AmphibianMetamorphosis["Amphibian Metamorphosis<br/>Aquatic larva to terrestrial adult<br/>Tadpole to frog"]:::lightmint
    Amphibians --> PermeableSkin["Permeable Skin<br/>Cutaneous respiration<br/>Requires moist environment"]:::lightmint
    
    Reptiles --> AmnioticEgg["Amniotic Egg<br/>Self-contained aquatic environment<br/>Enables terrestrial reproduction"]:::lightmint
    Reptiles --> Scales["Scales<br/>Keratinized skin<br/>Reduces water loss"]:::lightmint
    Reptiles --> Ectothermic["Ectothermic<br/>External temperature regulation<br/>Behavioral thermoregulation"]:::lightmint
    
    Birds --> Feathers["Feathers<br/>Modified scales<br/>Flight, insulation, display"]:::lightmint
    Birds --> HollowBones["Hollow Bones<br/>Pneumatic structure<br/>Reduces weight for flight"]:::lightmint
    Birds --> HighMetabolism["High Metabolism<br/>Endothermic<br/>Four-chambered heart"]:::lightmint
    
    Mammals --> MammaryGlands["Mammary Glands<br/>Milk production<br/>Nourish young"]:::lightmint
    Mammals --> Hair["Hair<br/>Insulation<br/>Diverse forms"]:::lightmint
    Mammals --> MammalGroups["Mammal Groups<br/>Monotremes, marsupials, placentals<br/>Different reproductive strategies"]:::lightmint
    
    MammalGroups --> Monotremes["Monotremes<br/>Egg-laying mammals<br/>Platypus, echidnas"]:::lightmint
    MammalGroups --> Marsupials["Marsupials<br/>Pouched mammals<br/>Kangaroos, opossums"]:::lightmint
    MammalGroups --> Placentals["Placental Mammals<br/>Most diverse group<br/>Extended development in uterus"]:::lightmint
    
    Phylogeny --> Systematics["Systematics<br/>Classification and naming<br/>Taxonomy and phylogenetics"]:::palegreen
    Phylogeny --> PhylogeneticTrees["Phylogenetic Trees<br/>Diagrams of evolutionary history<br/>Shows branching patterns"]:::palegreen
    Phylogeny --> Cladistics["Cladistics<br/>Classification by shared derived traits<br/>Identifies clades or monophyletic groups"]:::palegreen
    Phylogeny --> ThreeDomains["Three Domains of Life<br/>Bacteria, Archaea, Eukarya<br/>Highest level classification"]:::palegreen
    
    Systematics --> Taxonomy["Taxonomy<br/>Science of naming and classifying<br/>Hierarchical system"]:::mintgreen
    Systematics --> BinomialNomenclature["Binomial Nomenclature<br/>Two-part scientific name<br/>Genus and species"]:::mintgreen
    Systematics --> TaxonomicHierarchy["Taxonomic Hierarchy<br/>Domain, Kingdom, Phylum, Class, Order, Family, Genus, Species<br/>Eight major ranks"]:::mintgreen
    
    PhylogeneticTrees --> Nodes["Nodes<br/>Branching points<br/>Common ancestors"]:::mintgreen
    PhylogeneticTrees --> Branches["Branches<br/>Evolutionary lineages<br/>Represent time or change"]:::mintgreen
    PhylogeneticTrees --> SisterGroups["Sister Groups<br/>Share most recent common ancestor<br/>Most closely related"]:::mintgreen
    PhylogeneticTrees --> Outgroup["Outgroup<br/>Reference for comparison<br/>Diverged earlier"]:::mintgreen
    
    Cladistics --> DerivedTraits["Derived Traits (Synapomorphies)<br/>Shared by clade<br/>Inherited from common ancestor"]:::mintgreen
    Cladistics --> AncestralTraits["Ancestral Traits (Plesiomorphies)<br/>Present before divergence<br/>Not useful for grouping"]:::mintgreen
    Cladistics --> Cladogram["Cladogram<br/>Branching diagram<br/>Based on shared derived traits"]:::mintgreen
    Cladistics --> MonophyleticGroup["Monophyletic Group (Clade)<br/>Ancestor and all descendants<br/>Natural evolutionary group"]:::mintgreen
    
    ThreeDomains --> BacteriaDomain["Bacteria Domain<br/>Prokaryotic<br/>Peptidoglycan cell walls"]:::mintgreen
    ThreeDomains --> ArchaeaDomainPhylo["Archaea Domain<br/>Prokaryotic<br/>Unique membrane lipids"]:::mintgreen
    ThreeDomains --> EukaryaDomain["Eukarya Domain<br/>Eukaryotic cells<br/>Protists, fungi, plants, animals"]:::mintgreen
    
    EukaryaDomain --> ProtistKingdom["Protist Kingdom<br/>Paraphyletic group<br/>Diverse eukaryotes"]:::lightmint
    EukaryaDomain --> FungiKingdom["Fungi Kingdom<br/>Absorptive heterotrophs<br/>Chitin cell walls"]:::lightmint
    EukaryaDomain --> PlantKingdom["Plant Kingdom<br/>Photosynthetic autotrophs<br/>Cellulose cell walls"]:::lightmint
    EukaryaDomain --> AnimalKingdom["Animal Kingdom<br/>Ingestive heterotrophs<br/>No cell walls"]:::lightmint
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
    classDef lightmint fill:#bbf7d0,stroke:#86efac,stroke-width:1px,color:#000
```