```mermaid
flowchart LR
    Start([Genetics & Molecular Biology]):::green
    Start --> DNA["DNA Structure<br/>Double helix, nucleotide polymer<br/>Stores genetic information"]:::lightgreen
    Start --> GeneExpression["Gene Expression<br/>DNA to RNA to protein<br/>Central dogma of molecular biology"]:::lightgreen
    Start --> Inheritance["Mendelian Inheritance<br/>Patterns of trait transmission<br/>Dominant and recessive alleles"]:::lightgreen
    Start --> ChromosomeTheory["Chromosome Theory<br/>Genes located on chromosomes<br/>Explains inheritance patterns"]:::lightgreen
    Start --> MolecularGenetics["Molecular Genetics<br/>Gene regulation and mutations<br/>DNA technology and applications"]:::lightgreen
    
    DNA --> Nucleotides["Nucleotides<br/>Building blocks of DNA/RNA<br/>Sugar, phosphate, nitrogenous base"]:::palegreen
    DNA --> BasePairing["Base Pairing<br/>A-T and G-C complementarity<br/>Enables replication and transcription"]:::palegreen
    DNA --> DoubleHelix["Double Helix Structure<br/>Antiparallel strands<br/>Right-handed coil"]:::palegreen
    DNA --> ChromatinStructure["Chromatin Structure<br/>DNA-histone complexes<br/>Nucleosomes and higher-order organization"]:::palegreen
    DNA --> Replication["DNA Replication<br/>Copying DNA before division<br/>Semi-conservative process"]:::palegreen
    
    Nucleotides --> Purines["Purines<br/>Adenine and Guanine<br/>Two-ring nitrogenous bases"]:::mintgreen
    Nucleotides --> Pyrimidines["Pyrimidines<br/>Cytosine, Thymine, Uracil<br/>Single-ring nitrogenous bases"]:::mintgreen
    Nucleotides --> DeoxyriboseSugar["Deoxyribose Sugar<br/>5-carbon sugar in DNA<br/>Lacks hydroxyl at 2' position"]:::mintgreen
    Nucleotides --> PhosphateBackbone["Phosphate Backbone<br/>Phosphodiester bonds<br/>Links 3' and 5' carbons"]:::mintgreen
    
    DoubleHelix --> MajorGroove["Major Groove<br/>Wider groove<br/>Protein binding site"]:::mintgreen
    DoubleHelix --> MinorGroove["Minor Groove<br/>Narrower groove<br/>Additional protein access"]:::mintgreen
    DoubleHelix --> AntiparallelStrands["Antiparallel Orientation<br/>5' to 3' and 3' to 5'<br/>Opposite strand directions"]:::mintgreen
    
    ChromatinStructure --> Nucleosome["Nucleosome<br/>DNA wrapped around histones<br/>147 base pairs per turn"]:::mintgreen
    ChromatinStructure --> HistoneOctamer["Histone Octamer<br/>8 histone proteins (H2A, H2B, H3, H4)<br/>Core of nucleosome"]:::mintgreen
    ChromatinStructure --> Euchromatin["Euchromatin<br/>Open, accessible chromatin<br/>Transcriptionally active"]:::mintgreen
    ChromatinStructure --> Heterochromatin["Heterochromatin<br/>Condensed, compact chromatin<br/>Transcriptionally silent"]:::mintgreen
    
    Replication --> ReplicationFork["Replication Fork<br/>Y-shaped DNA structure<br/>Bidirectional synthesis"]:::mintgreen
    Replication --> Helicase["Helicase<br/>Unwinds DNA double helix<br/>Creates replication fork"]:::mintgreen
    Replication --> Polymerase["DNA Polymerase<br/>Synthesizes new DNA strands<br/>Adds nucleotides in 5' to 3' direction"]:::mintgreen
    Replication --> Ligase["DNA Ligase<br/>Joins Okazaki fragments<br/>Seals nicks in DNA backbone"]:::mintgreen
    Replication --> Primase["Primase<br/>Synthesizes RNA primers<br/>Required for polymerase initiation"]:::mintgreen
    
    ReplicationFork --> LeadingStrand["Leading Strand<br/>Continuous synthesis<br/>5' to 3' toward fork"]:::lightmint
    ReplicationFork --> LaggingStrand["Lagging Strand<br/>Discontinuous synthesis<br/>Okazaki fragments"]:::lightmint
    ReplicationFork --> SSBProteins["SSB Proteins<br/>Single-strand binding<br/>Prevents reannealing"]:::lightmint
    
    Polymerase --> PolIII["DNA Polymerase III<br/>Main replication enzyme<br/>High processivity"]:::lightmint
    Polymerase --> PolI["DNA Polymerase I<br/>Removes RNA primers<br/>Fills gaps"]:::lightmint
    Polymerase --> Proofreading["3' to 5' Exonuclease<br/>Proofreading activity<br/>Error correction"]:::lightmint
    
    Ligase --> PhosphodiesterBond["Phosphodiester Bond<br/>Covalent linkage<br/>Joins DNA fragments"]:::lightmint
    
    GeneExpression --> Transcription["Transcription<br/>DNA to RNA synthesis<br/>Creates messenger RNA"]:::palegreen
    GeneExpression --> Translation["Translation<br/>RNA to protein synthesis<br/>Ribosomes read mRNA"]:::palegreen
    GeneExpression --> GeneRegulation["Gene Regulation<br/>Control of gene expression<br/>Responds to environmental signals"]:::palegreen
    
    Transcription --> Initiation["Transcription Initiation<br/>RNA polymerase binds promoter<br/>DNA unwinding begins"]:::mintgreen
    Transcription --> Elongation["Transcription Elongation<br/>RNA synthesis 5' to 3'<br/>Template strand read 3' to 5'"]:::mintgreen
    Transcription --> Termination["Transcription Termination<br/>RNA release<br/>Rho-dependent or independent"]:::mintgreen
    Transcription --> RNAPolymerase["RNA Polymerase<br/>Synthesizes RNA from DNA template<br/>Recognizes promoter sequences"]:::mintgreen
    Transcription --> mRNA["Messenger RNA<br/>Carries genetic code to ribosomes<br/>Template for protein synthesis"]:::mintgreen
    Transcription --> RNAProcessing["RNA Processing<br/>Splicing, capping, poly-A tail<br/>Prepares mRNA for translation"]:::mintgreen
    
    RNAPolymerase --> RNAP_II["RNA Polymerase II<br/>Transcribes mRNA<br/>Requires transcription factors"]:::lightmint
    RNAPolymerase --> PromoterRecognition["Promoter Recognition<br/>TATA box binding<br/>Transcription start site"]:::lightmint
    
    RNAProcessing --> FivePrimeCap["5' Cap<br/>7-methylguanosine<br/>Protects from degradation"]:::lightmint
    RNAProcessing --> Splicing["RNA Splicing<br/>Removes introns<br/>Joins exons"]:::lightmint
    RNAProcessing --> PolyATail["Poly-A Tail<br/>~200 adenines at 3' end<br/>Stability and translation"]:::lightmint
    
    Splicing --> Spliceosome["Spliceosome<br/>snRNPs and proteins<br/>Catalyzes splicing"]:::lightmint
    Splicing --> AlternativeSplicing["Alternative Splicing<br/>Different exon combinations<br/>Multiple proteins from one gene"]:::lightmint
    Splicing --> IntronExon["Introns and Exons<br/>Introns removed, exons kept<br/>Defines coding sequence"]:::lightmint
    
    Translation --> TranslationInitiation["Translation Initiation<br/>Ribosome assembly at start codon<br/>AUG methionine"]:::mintgreen
    Translation --> TranslationElongation["Translation Elongation<br/>Peptide bond formation<br/>tRNA cycling"]:::mintgreen
    Translation --> TranslationTermination["Translation Termination<br/>Stop codon recognition<br/>Protein release"]:::mintgreen
    Translation --> Ribosome["Ribosomes<br/>Protein synthesis machinery<br/>rRNA and protein complex"]:::mintgreen
    Translation --> tRNA["Transfer RNA<br/>Brings amino acids to ribosome<br/>Anticodon matches mRNA codon"]:::mintgreen
    Translation --> GeneticCode["Genetic Code<br/>Codon to amino acid mapping<br/>Universal among organisms"]:::mintgreen
    
    Ribosome --> LargeSubunit["Large Subunit (60S)<br/>Peptidyl transferase activity<br/>Catalyzes peptide bonds"]:::lightmint
    Ribosome --> SmallSubunit["Small Subunit (40S)<br/>mRNA binding<br/>Decoding center"]:::lightmint
    Ribosome --> RibosomalSites["A, P, E Sites<br/>Aminoacyl, Peptidyl, Exit<br/>tRNA binding positions"]:::lightmint
    
    tRNA --> Anticodon["Anticodon Loop<br/>Three nucleotides<br/>Complementary to mRNA codon"]:::lightmint
    tRNA --> AminoacylSynthetase["Aminoacyl-tRNA Synthetase<br/>Charges tRNA<br/>Attaches correct amino acid"]:::lightmint
    tRNA --> CloverleafStructure["Cloverleaf Structure<br/>Secondary structure<br/>Four major arms"]:::lightmint
    
    GeneticCode --> Codons["Codons<br/>Three-nucleotide sequences<br/>64 possible combinations"]:::lightmint
    GeneticCode --> StartCodon["Start Codon (AUG)<br/>Methionine<br/>Translation initiation signal"]:::lightmint
    GeneticCode --> StopCodons["Stop Codons<br/>UAA, UAG, UGA<br/>Terminate translation"]:::lightmint
    GeneticCode --> Degeneracy["Codon Degeneracy<br/>Multiple codons per amino acid<br/>Wobble pairing at third position"]:::lightmint
    
    TranslationElongation --> EFTu["Elongation Factor Tu<br/>Delivers aminoacyl-tRNA<br/>GTP-dependent"]:::lightmint
    TranslationElongation --> Translocation["Translocation<br/>Ribosome moves 3 nucleotides<br/>EF-G dependent"]:::lightmint
    TranslationElongation --> PeptideBond["Peptide Bond Formation<br/>Amino acid linkage<br/>Ribosomal peptidyl transferase"]:::lightmint
    
    GeneRegulation --> Operons["Operons<br/>Gene clusters in prokaryotes<br/>Lac and trp operons"]:::mintgreen
    GeneRegulation --> TranscriptionFactors["Transcription Factors<br/>Proteins controlling transcription<br/>Activators and repressors"]:::mintgreen
    GeneRegulation --> Epigenetics["Epigenetics<br/>Heritable changes without DNA sequence change<br/>DNA methylation and histone modification"]:::mintgreen
    GeneRegulation --> EnhancersSilencers["Enhancers and Silencers<br/>Regulatory DNA sequences<br/>Long-range control"]:::mintgreen
    
    Operons --> LacOperon["Lac Operon<br/>Inducible system<br/>Lactose metabolism"]:::lightmint
    Operons --> TrpOperon["Trp Operon<br/>Repressible system<br/>Tryptophan synthesis"]:::lightmint
    Operons --> OperatorRegion["Operator Region<br/>Repressor binding site<br/>Controls RNA polymerase access"]:::lightmint
    
    LacOperon --> LacRepressor["Lac Repressor<br/>Blocks transcription<br/>Inactivated by allolactose"]:::lightmint
    LacOperon --> CAPcAMP["CAP-cAMP Complex<br/>Positive regulation<br/>Enhances RNA polymerase binding"]:::lightmint
    
    TranscriptionFactors --> Activators["Activator Proteins<br/>Increase transcription<br/>Bind enhancers"]:::lightmint
    TranscriptionFactors --> Repressors["Repressor Proteins<br/>Decrease transcription<br/>Bind silencers or operators"]:::lightmint
    TranscriptionFactors --> CoactivatorsCorepressors["Coactivators/Corepressors<br/>Assist transcription factors<br/>Chromatin remodeling"]:::lightmint
    
    Epigenetics --> DNAMethylation["DNA Methylation<br/>Adds methyl groups to cytosine<br/>Gene silencing"]:::lightmint
    Epigenetics --> HistoneModification["Histone Modifications<br/>Acetylation, methylation, phosphorylation<br/>Affects chromatin structure"]:::lightmint
    Epigenetics --> ChromatinRemodeling["Chromatin Remodeling<br/>ATP-dependent complexes<br/>Alter nucleosome positioning"]:::lightmint
    Epigenetics --> Imprinting["Genomic Imprinting<br/>Parent-specific expression<br/>Monoallelic expression"]:::lightmint
    
    Inheritance --> MendelLaws["Mendel's Laws<br/>Segregation and independent assortment<br/>Foundation of genetics"]:::palegreen
    Inheritance --> Punnett["Punnett Squares<br/>Predicts offspring genotypes<br/>Visual tool for crosses"]:::palegreen
    Inheritance --> Linkage["Gene Linkage<br/>Genes on same chromosome<br/>Inherited together unless crossing over"]:::palegreen
    Inheritance --> SexLinked["Sex-Linked Inheritance<br/>Genes on sex chromosomes<br/>Different patterns in males and females"]:::palegreen
    Inheritance --> NonMendelian["Non-Mendelian Inheritance<br/>Complex patterns<br/>Incomplete dominance, codominance, polygenic"]:::palegreen
    
    MendelLaws --> Segregation["Law of Segregation<br/>Alleles separate in gametes<br/>Each gamete gets one allele"]:::mintgreen
    MendelLaws --> IndependentAssortment["Law of Independent Assortment<br/>Genes assort independently<br/>Applies to unlinked genes"]:::mintgreen
    
    Punnett --> MonohybridCross["Monohybrid Cross<br/>One trait examined<br/>3:1 ratio for F2"]:::mintgreen
    Punnett --> DihybridCross["Dihybrid Cross<br/>Two traits examined<br/>9:3:3:1 ratio for F2"]:::mintgreen
    Punnett --> TestCross["Test Cross<br/>Unknown genotype × homozygous recessive<br/>Reveals genotype"]:::mintgreen
    
    Linkage --> RecombinationFrequency["Recombination Frequency<br/>Distance between genes<br/>Measured in map units (cM)"]:::mintgreen
    Linkage --> GeneticMapping["Genetic Mapping<br/>Chromosome maps<br/>Gene order and distance"]:::mintgreen
    Linkage --> CrossingOverRate["Crossing Over Rate<br/>1% recombination = 1 map unit<br/>Proportional to distance"]:::mintgreen
    
    SexLinked --> XLinked["X-Linked Traits<br/>Genes on X chromosome<br/>Males hemizygous"]:::mintgreen
    SexLinked --> YLinked["Y-Linked Traits<br/>Genes on Y chromosome<br/>Male-to-male transmission"]:::mintgreen
    SexLinked --> DosageCompensation["Dosage Compensation<br/>X-inactivation in females<br/>Barr body formation"]:::mintgreen
    
    NonMendelian --> IncompleteDominance["Incomplete Dominance<br/>Blended phenotype<br/>Heterozygote intermediate"]:::mintgreen
    NonMendelian --> Codominance["Codominance<br/>Both alleles expressed<br/>ABO blood groups"]:::mintgreen
    NonMendelian --> PolygenicInheritance["Polygenic Inheritance<br/>Multiple genes affect one trait<br/>Continuous variation"]:::mintgreen
    NonMendelian --> Pleiotropy["Pleiotropy<br/>One gene affects multiple traits<br/>Sickle cell example"]:::mintgreen
    
    MolecularGenetics --> Mutations["Mutations<br/>Changes in DNA sequence<br/>Source of genetic variation"]:::palegreen
    MolecularGenetics --> Biotechnology["Biotechnology<br/>DNA manipulation techniques<br/>PCR, cloning, sequencing"]:::palegreen
    MolecularGenetics --> CRISPR["CRISPR-Cas9<br/>Gene editing technology<br/>Precise DNA modification"]:::palegreen
    
    Mutations --> PointMutations["Point Mutations<br/>Single nucleotide changes<br/>Silent, missense, nonsense"]:::mintgreen
    Mutations --> Frameshift["Frameshift Mutations<br/>Insertions or deletions<br/>Shifts reading frame"]:::mintgreen
    Mutations --> ChromosomalMutations["Chromosomal Mutations<br/>Large-scale changes<br/>Deletions, duplications, inversions, translocations"]:::mintgreen
    
    PointMutations --> SilentMutation["Silent Mutation<br/>No amino acid change<br/>Codon degeneracy"]:::lightmint
    PointMutations --> MissenseMutation["Missense Mutation<br/>Different amino acid<br/>May alter protein function"]:::lightmint
    PointMutations --> NonsenseMutation["Nonsense Mutation<br/>Creates stop codon<br/>Truncated protein"]:::lightmint
    
    Biotechnology --> PCR["Polymerase Chain Reaction<br/>DNA amplification<br/>Exponential replication"]:::mintgreen
    Biotechnology --> GelElectrophoresis["Gel Electrophoresis<br/>Separates DNA by size<br/>Visualization technique"]:::mintgreen
    Biotechnology --> DNASequencing["DNA Sequencing<br/>Determines nucleotide order<br/>Sanger and next-gen methods"]:::mintgreen
    Biotechnology --> Cloning["DNA Cloning<br/>Recombinant DNA technology<br/>Plasmid vectors"]:::mintgreen
    
    PCR --> TaqPolymerase["Taq Polymerase<br/>Heat-stable enzyme<br/>From Thermus aquaticus"]:::lightmint
    PCR --> PCRCycles["PCR Cycles<br/>Denaturation, annealing, extension<br/>30-40 cycles"]:::lightmint
    PCR --> Primers["PCR Primers<br/>Short DNA sequences<br/>Define amplification region"]:::lightmint
    
    DNASequencing --> SangerSequencing["Sanger Sequencing<br/>Chain termination method<br/>Gold standard for accuracy"]:::lightmint
    DNASequencing --> NextGenSequencing["Next-Gen Sequencing<br/>Massively parallel<br/>High throughput, low cost"]:::lightmint
    
    Cloning --> RestrictionEnzymes["Restriction Enzymes<br/>Cut DNA at specific sequences<br/>Create sticky or blunt ends"]:::lightmint
    Cloning --> Plasmids["Plasmid Vectors<br/>Circular DNA molecules<br/>Carry foreign DNA into cells"]:::lightmint
    Cloning --> Transformation["Transformation<br/>Introducing DNA into cells<br/>Heat shock or electroporation"]:::lightmint
    
    CRISPR --> Cas9Enzyme["Cas9 Enzyme<br/>Molecular scissors<br/>Cuts DNA at target site"]:::mintgreen
    CRISPR --> GuideRNA["Guide RNA<br/>Directs Cas9 to target<br/>~20 nucleotide sequence"]:::mintgreen
    CRISPR --> HDRvsNHEJ["HDR vs NHEJ<br/>Homology-directed repair or non-homologous end joining<br/>Precise or error-prone repair"]:::mintgreen
    
    Cas9Enzyme --> PAMSequence["PAM Sequence<br/>Protospacer adjacent motif<br/>Required for Cas9 recognition"]:::lightmint
    Cas9Enzyme --> DoubleStrandBreak["Double-Strand Break<br/>Both DNA strands cut<br/>Triggers repair mechanisms"]:::lightmint
    
    classDef green fill:#15803d,stroke:#14532d,stroke-width:3px,color:#fff
    classDef lightgreen fill:#22c55e,stroke:#16a34a,stroke-width:2px,color:#fff
    classDef palegreen fill:#4ade80,stroke:#22c55e,stroke-width:2px,color:#000
    classDef mintgreen fill:#86efac,stroke:#4ade80,stroke-width:1px,color:#000
    classDef lightmint fill:#bbf7d0,stroke:#86efac,stroke-width:1px,color:#000
```