#**tools for bioinformatics**  

##**Neoantigen Discovery pipeline**  
###**1. Ginga-2018-EPFL-IGEM**
[Neoantigen Discovery pipeline-Ginga](http://2018.igem.org/Team:EPFL/Software),Ginga is the first step of the CAPOEIRA to bring one step closer personalised oncology. Ginga is a pipeline base on state of the art genomic tools that are seemlesly integrated in a single streamline pipeline. Ginga translates whole exome sequencing (WES) data from patients into a library of specific neoantigens with the goal to create a personalised therapy that its effective at targeting uniquely the cancer cells.  

###**2. KarchinLab**  
[KarchinLab](https://github.com/KarchinLab)  

###**3. peptide-extractor**
[peptide-extractor](https://github.com/Adrodoc/peptide-extractor),A command line tool for transforming the output of the Ensembl Variant Effect Predictor ProteinSeqs Plugin into NetMHC-readable peptide fragments that are affected by mutation.  


###**4. https://services.healthtech.dtu.dk/**
bioinformatic services provied by DTU Health Tech.  

###**5. CIBMTR - Center for International Blood and Marrow Transplant Research**  
[CIBMTR](https://github.com/nmdp-bioinformatics),Center for International Blood and Marrow Transplant Research.  

###**6. Immune Epitope Database Analysis Resource**  
*The tools contained fall into the following categories:*  

1. T Cell Epitope Prediction Tools
This set of tools includes MHC class I & II binding predictions, as well as peptide processing predictions and immunogenicity predictions.

2. B Cell Epitope Prediction Tools
The tools here are intended to predict regions of proteins that are likely to be recognized as epitopes in the context of a B cell response.

3. Analysis Tools
The epitope analysis tools are intended for the detailed analysis of a known epitope sequence or group of sequences.

###**7. Hammer Lab**  
[Hammer Lab](https://github.com/hammerlab),a lab working to understand and improve the immune response to cancer.  

###**8. IMSEQ - IMmunogenetic SEQuence Analysis**  
[IMSEQ](http://www.imtools.org/),IMmunogenetic SEQuence Analysis is a fast, PCR and sequencing error aware tool to analyze high throughput data from recombined T-cell receptor or immunoglobolin gene sequencing experiments. It derives immune repertoires from sequencing data in FASTA / FASTQ format.  

###**9. melanoma-reanalysis**  
Online Materials: Somatic Mutations, Neoepitope Homology and Inflammation in Melanomas Treated with CTLA-4 Blockade. [detail](http://hammerlab.org/)

###**10. IgGeneUsage**
[IgGeneUsage](http://bioconductor.org/packages/release/bioc/html/IgGeneUsage.html),Differential gene usage in immune repertoires.Decoding the properties of immune repertoires is key in understanding the response of adaptive immunity to challenges such as viral infection. One important task in immune repertoire profiling is the detection of biases in Ig gene usage between biological conditions. IgGeneUsage is a computational tool for the analysis of differential gene usage in immune repertoires. It employs Bayesian hierarchical models to fit complex gene usage data from immune repertoire sequencing experiments and quantifies Ig gene usage biases as probabilities.  

###**11. LymphoSeq**
[LymphoSeq](http://bioconductor.org/packages/devel/bioc/vignettes/LymphoSeq/inst/doc/LymphoSeq.html),Application of high-throughput sequencing of T and B lymphocyte antigen receptors has great potential for improving the monitoring of lymphoid malignancies, assessing immune reconstitution after hematopoietic stem cell transplantation, and characterizing the composition of lymphocyte repertoires (Warren, E. H. et al. Blood 2013;122:19–22). LymhoSeq is an R package designed to import, analyze, and visualize antigen receptor sequencing from Adaptive Biotechnologies’ ImmunoSEQ assay. The package is also adaptable to the analysis of T and B cell receptor sequencing processed using other platforms such as MiXCR or IMGT/HighV-QUEST. This vignette has been written to highlight some of the features of LymphoSeq and guide the user through a typical workflow.  

###**12. TRUST4**
[TRUST4](https://github.com/liulab-dfci/TRUST4),Ultrasensitive detection of TCR hypervariable-region sequences in solid-tissue RNA–seq data,TCR and BCR assembly from RNA-seq data.

###**13. OpenVax**  
[OpenVax](https://github.com/openvax),OpenVax is a group at the Icahn School of Medicine at Mount Sinai. We’re developing an open source personalized cancer vaccine pipeline.  

###**14. clonotypeR**  
[clonotypeR](https://clonotyper.branchable.com/),Quantitative analysis of antigen receptor sequences. clonotypeR is a Bioconductor package and accompanying scripts to identify and analyse clonotypes from high-throughput T cell receptors sequence libraries. clonotypeR is suited to process and organise very large number of clonotypes, in the order of millions, typically produced by Roche 454 instruments, and to prepare these sequences for differential expression analysis with the typical transcriptomics tools as well as for statistical analysis using existing R packages. If you need to try alternative solutions, you can have a look at IMGTHighV-QUEST, Decombinator, MiTCR, MIGEC, MiXCR, LymAnalyzer, tcR, TraCeR, VDJviz, or VDJtools. See also the OMICtool website for a longer list of repertoire tools.  

###**15. repseqio**  
[repseqio](https://github.com/repseqio/repseqio),Utils for manipulations with RepSeq data. and the related RepSeq sample preparation protocols is [here](https://github.com/repseqio/protocols). 

###**16. Orchestrating Single-Cell Analysis with Bioconductor**  
[Orchestrating Single-Cell Analysis with Bioconductor](https://osca.bioconductor.org/),a book that teaches users some common workflows for the analysis of single-cell RNA-seq data (scRNA-seq). This book will teach you how to make use of cutting-edge Bioconductor tools to process, analyze, visualize, and explore scRNA-seq data. 


###**17. Consequence calling**  
The [BCFtools/csq](https://samtools.github.io/bcftools/howtos/csq-calling.html) command is a very fast program for haplotype-aware consequence calling which can take into account known phase. It avoids the common pitfall of existing predictors which analyze variants as isolated events and correctly predicts consequences for adjacent variants which alter the same codon or frame-shifting indels followed by a frame-restoring indels. List of plugins at [here](https://samtools.github.io/bcftools/howtos/plugins.html).

##**Microsatellite instability**

###**1. Microsatellite instability in github**
[MSI in github](https://github.com/search?p=1&q=Microsatellite+instability&type=Repositories&utf8=%E2%9C%93),repositories about microsatellite instability in github.

###**2. lobSTR**
[lobSTR](http://lobstr.teamerlich.org/) is a tool for profiling Short Tandem Repeats (STRs) from high throughput sequencing data.

###**3. MSIsensor**  

###**4. MSIseq**  
[MSIseq](https://rdrr.io/cran/MSIseq/man/NGStrainclass.html),A decision tree classifier for detecting microsatellite instability (MSI) in somatic mutation data from whole exome sequencing. MSI is detected based on different mutation rates in all sites as well as in simple sequence repeats. This mechanism can also be applied to sequence data of targeted gene panels with shorter sequence length.  




##**Tumor Evolution**  
###**1. ClonEvol**
[ClonEvol](https://github.com/hdng/clonevol/): clonal ordering and visualization in cancer sequencing.Inferring and visualizing clonal evolution in multi-sample cancer sequencing.  

###**2. fishplot**  
[fishplot](https://github.com/flywind2/fishplot),An R package for visualizing changes in the subclonal architecture of tumors.  

###**3. citup**  
[CITUP (Clonality Inference in Tumors Using Phylogeny)](https://github.com/flywind2/citup) is a bioinformatics tool that can be used to infer tumor heterogeneity using multiple samples from a single patient. Given mutational frequencies for each sample, CITUP uses an optimization based algorithm to find the evolutionary tree best explaining the data.  

###**4. sciclone**  
[sciclone](https://github.com/genome/sciclone),An R package for inferring the subclonal architecture of tumors.  

###**5. Clonality**  
[Clonality](http://bioconductor.org/packages/release/bioc/html/Clonality.html),Statistical tests for clonality versus independence of tumors from the same patient based on their LOH or genomewide copy number profiles.  





##**R packages about bioinformatics**  
### 1. TCGAmutations
### 2. dupRadar  
Assessment of duplication rate in RNA-SEQ datasets.  
### 3. basecallQC  
### 4. SVM2CRM  
svm for cis-regulatory elements detections.  
### 5. ReQON  
recalibrating Quality of nucleotide.  
### 6. DNABarcodes  
### 7. deconstructSigs  
### 8. OmicsCore/SeqProcess  
### 9. mixtools package  
### 10. Hmisc--'binconf' function  
### 11. ASCAT copy number R package  
Allele-Specific Copy Number Analysis of Tumors.  
### 12. Heatmaps  
Flexible plotting of Fuctional Genomics data and Sequence features.  
### 13. hiReadsProcessor/idiogram  
### 14. htSeqTools  
### 15. iCNV/NGScopy/SeqCNA/TitanCNA  
### 16. TissueEnrich  
### 17. BiocOncoTK
[BiocOncoTK](http://www.bioconductor.org/packages/release/bioc/html/BiocOncoTK.html),Bioconductor components for general cancer genomics.Provide a central interface to various tools for genome-scale analysis of cancer studies. Some example as follows:  
1. BiocOncoTK -- cancer oriented components for Bioconductor  
2. curatedMSIData overview  
3. Mapping TCGA tumor codes to NCIT  
  
### 18. CancerMutaionAnalysis  
### 19. molbiol-tools.ca/Java.htm -- PerlPrimer
### 20. CrispRVariant  
### 21. CancerSubtypes  
### 22. bamSignals  
### 23. CINdex--gene break detection  
### 24. GenRank  
### 25. genotypeeval/genebreak  
### 26. hapFabia--indentical by descent  
### 27. M3C/MADSEQ  
### 28. ReportingTools  
### 29. SeqArray  
### 30. SeqVarTools  
### 31. ImageMagick  
### 32. mutSignatures--mutSig in R  
### 33. tximport  
### 34. iChorCNA  
### 35. oncoCNV  
### 36. TEQC  
### 37. absolute  
### 38. CLONET  
### 39. FACETS  
FACETS,a tool for purity determined.  
### 40. SVAtools  
### 41. microbiomeutilities  
This package is in experimental stage and should be used only for testing/trial purposes. I will keep improving this with time and feedback.

This is mainly a wrapper tool R package. Apart for some simple scripts for data visualization, this package has a single function called microbiome_pipeline for carrying out preliminary QC, Alpha Diversity, Ordination and Composition analysis of OTU tables. The output is a HTML report for convenient investigating of the data.  
### 42. SomaticSignatures  
[SomaticSignatures](http://www.bioconductor.org/packages/3.3/bioc/vignettes/SomaticSignatures/inst/doc/SomaticSignatures-vignette.html),Inferring Somatic Signatures from Single Nucleotide Variant Calls  
### 43. ggbio  
[ggbio](http://www.bioconductor.org/packages/release/bioc/html/ggbio.html),Visualization tools for genomic data.The ggbio package extends and specializes the grammar of graphics for biological data. The graphics are designed to answer common scientific questions, in particular those often asked of high throughput genomics data. All core Bioconductor data structures are supported, where appropriate. The package supports detailed views of particular genomic regions, as well as genome-wide overviews. Supported overviews include ideograms and grand linear views. High-level plots include sequence fragment length, edge-linked interval to data view, mismatch pileup, and several splicing summaries.  
### 44. SEER2R-package  


### 45. TitanCNA-https://gavinhalab.org/projects/  
OpenGenomics  

### 46. Driver Gene  
[C3 (Consensus Cancer driver gene Caller)](http://drivergene.rwebox.com/c3/),is the first integrated and user-friendly pipeline that calls driver genes from different strategies using somatic variant information and quantitatively evaluates the calling results. C3 integrates six popular driver gene detection strategies i.e., frequency-based, machine learning-based, functional bias-based, clustering-based, statistics model-based and network-based. C3 applies a consensus integration method Robust RankAggregation (RRA) to obtain the reliable drivers. C3 also provides the intuitively annotation and visualization of the output driver genes using Cancer Gene Census (CGC), Network of Cancer Genes (NCG), Online Mendelian Inheritance in Man(OMIM), Gene Ontology(GO), and KEGG pathway.  

### 47. EMDomics
[EMDomics: Earth Mover's Distance for Differential Analysis of Genomics Data](https://rdrr.io/bioc/EMDomics/),The EMDomics algorithm is used to perform a supervised multi-class analysis to measure the magnitude and statistical significance of observed continuous genomics data between groups. Usually the data will be gene expression values from array-based or sequence-based experiments, but data from other types of experiments can also be analyzed (e.g. copy number variation). Traditional methods like Significance Analysis of Microarrays (SAM) and Linear Models for Microarray Data (LIMMA) use significance tests based on summary statistics (mean and standard deviation) of the distributions. This approach lacks power to identify expression differences between groups that show high levels of intra-group heterogeneity. The Earth Mover's Distance (EMD) algorithm instead computes the "work" needed to transform one distribution into another, thus providing a metric of the overall difference in shape between two distributions. Permutation of sample labels is used to generate q-values for the observed EMD scores. This package also incorporates the Komolgorov-Smirnov (K-S) test and the Cramer von Mises test (CVM), which are both common distribution comparison tests.  

### 48. logicFS
[logicFS](http://www.bioconductor.org/packages/release/bioc/html/logicFS.html),Identification of interactions between binary variables using Logic Regression. Can, e.g., be used to find interesting SNP interactions. Contains also a bagging version of logic regression for classification.  

### 49. KnowSeq 
[KnowSeq](http://www.bioconductor.org/packages/release/bioc/html/KnowSeq.html),KnowSeq proposes a whole pipeline that comprises the most relevant steps in the RNA-seq gene expression analysis, with the main goal of extracting biological knowledge from raw data (Differential Expressed Genes, Gene Ontology enrichment, pathway visualization and related diseases). In this sense, KnowSeq allows aligning raw data from the original fastq or sra files, by using the most renowned aligners such as tophat2, hisat2, salmon and kallisto. Nowadays, there is no package that only from the information of the samples to align -included in a text file-, automatically performs the download and alignment of all of the samples. Furthermore, the package includes functions to: calculate the gene expression values; remove batch effect; calculate the Differentially Expressed Genes (DEGs); plot different graphs; and perform the DEGs enrichment with the GO information, pathways visualization and related diseases information retrieval. Moreover, KnowSeq is the only package that allows applying both a machine learning and DEGs enrichment processes just after the DEGs extraction. This idea emerged with the aim of proposing a complete tool to the research community containing all the necessary steps to carry out complete studies in a simple and fast way. [Author: Daniel Castillo-Secilla, Juan Manuel Galvez, Francisco Manuel Ortuno, Luis Javier Herrera and Ignacio Rojas.]  

### 50. gbm: Generalized Boosted Regression Models
[GBM](https://cran.r-project.org/web/packages/gbm/),An implementation of extensions to Freund and Schapire's AdaBoost algorithm and Friedman's gradient boosting machine. Includes regression methods for least squares, absolute loss, t-distribution loss, quantile regression, logistic, multinomial logistic, Poisson, Cox proportional hazards partial likelihood, AdaBoost exponential loss, Huberized hinge loss, and Learning to Rank measures (LambdaMart). Originally developed by Greg Ridgeway.



##**Single-Cell**
###**1.  scAlign
[scAlign](http://www.bioconductor.org/packages/release/bioc/html/scAlign.html),An alignment and integration method for single cell genomics.




## **database**
### **1. TSGene--Tumor suppressor gene database**  
[TSGene](https://bioinfo.uth.edu/TSGene/index.html?csrt=8233095850201184389)



## **甲基化**
### **1. methsurv**
[methsurv](https://biit.cs.ut.ee/methsurv/),A web tool to perform multivariable survival analysis using DNA methylation data.  
### **2. UALCAN**
[ualcan](http://ualcan.path.uab.edu/),UALCAN is a comprehensive, user-friendly, and interactive web resource for analyzing cancer OMICS data. It is built on PERL-CGI with high quality graphics using javascript and CSS. UALCAN is designed to, a) provide easy access to publicly available cancer OMICS data (TCGA and MET500), b) allow users to identify biomarkers or to perform in silico validation of potential genes of interest, c) provide graphs and plots depicting gene expression and patient survival information based on gene expression, d) evaluate gene expression in molecular subtypes of breast and prostate cancer, e) evaluate epigenetic regulation of gene expression by promoter methylation and correlate with gene expression, f) perform pan-cancer gene expression analysis, and g) Provide additional information about the selected genes/targets by linking to HPRD, GeneCards, Pubmed, TargetScan, The human protein atlas, DRUGBANK, Open Targets and the GTEx. These resources allow researchers to gather valuable information and data about the genes/targets of interest.  






## **Precision Medicine**  
### **1. Personal Cancer Genome Reporter (PCGR)**  
[PCGR](https://github.com/flywind2/pcgr),Personal Cancer Genome Reporter (PCGR)  

### **Real Time Genomics**  
**rtg-tools**  
RTG Tools: Utilities for accurate VCF comparison and manipulation  
**rtg-core**  
RTG Core: Software for alignment and analysis of next-gen sequencing data.  
**rplot**  
A Java 2D plotting library inspired by gnuplot  
[Author: Daniel Castillo-Secilla, Juan Manuel Galvez, Francisco Manuel Ortuno, Luis Javier Herrera and Ignacio Rojas.]: 


### **Pan-Cancer Analysis of Whole Genomes**
[Pan-Cancer Analysis of Whole Genomes](https://www.nature.com/immersive/d42859-020-00001-y/index.html),A collection of research and related content from the ICGC/TCGA consortium on whole‑genome sequencing and integrative analysis of cancer  

[REINDEER](https://github.com/kamimrcht/REINDEER),REINDEER REad Index for abuNDancE quERy.