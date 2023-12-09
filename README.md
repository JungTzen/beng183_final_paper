# BENG 183 Final Paper

# CONTENTS
##scRNA-sequencing and spatial transcriptomics
##Pros and Cons
##Similarities and differences
##Real-world Uses


# scRNA-sequencing and Spatial Transcriptomics
Single cell RNA sequencing (scRNA-seq) is a recent development in genomic analysis. It focuses on the transcriptomes of individual cells. It allows scientists to get a glimpse into the similarities and differences within a population of cells. Popular tools for scRNA-seq analysis are scanpy and Seurat

Spatial transcriptomics is a molecular profiling method used to help scientists measure gene activity in tissue and map where the activity occurs at. The tool we will be focusing on will be MERFISH (Multiplexed error-robust fluorescence in situ hybridization) which is a very popular tool for handling spatial transcriptomics.

# Pros and Cons
## scRNA-seq
Pros: Widely-Used Versatility Efficiency (More genes per sequence)
Cons: Lack of Spatial Information Data Integration challenges Gene dropout due to technical limitations Lower resolution

## Spatial Transcriptomics
Pros: Spatial Resolution Higher resolution Improved sensitivity
Cons: Specialized equipment Library Prep Complexity Cost Limited amount of genes

# Similarities and Differences
## Similarities
Both expression analysis Both have single-cell resolution Both offer quantitative gene expression measurement

## Differences
Methodologies 
scRNA-seq: Involves isolating RNA from single cells, converting it to cDNA, sequencing 
ST: Uses spatially barcoded oligos/probes to capture spatial information by imaging tissue sections or samples 
Additional Spatial Data 
Use cases 
Gene Dropout Rates

# Real World Uses
By integrating scRNA-seq and spatial transcriptomics, researchers can gain a more holistic understanding of biological systems, combining the depth of single-cell analysis with the critical context of spatial distribution.

# Advanced Cancer Research:
Spatial Transcriptomics has been incredibly helpful in understanding the spatial heterogeneity of tumors. It has helped us characterize tertiary lymphoid structures, also known as TLSs which are formations at sites with persistent inflamatory stimiluation (like tumors). By using ST scientists have able to understand the spatial organization of immune cells and thier role in anti-tumor responses. On the flip side of the coin, RNA-seq helps us understand the gene expression profiles of cancel cells which further helps us in our understanding of molecular mechanisms driving cancer progression. 

# Developmental biology:
Development biology spans many different specific subfields of biology (both from an anatomical view or a disease-centric view. Spatial transcriptomics serves as a valuable tool in furthering our understanding of this field as  it provides a visual/spatial view of how tissues and cells change over the course of development. ST helps in understanding how different cells contribute to the growth and formation of comlplex biological structures. This is an incredible tool which enhances the prelimainary genetic compository information that RNA-seq provides. 

# Drug Development and Response Monitoring:
Regarding drug development and responnse monitoring, spatial transcriptomics has played a vital role in understand the spatial heterogenity of dru responses at the cellular level. An example of ths is the graph-based domain adoption model called SpaRx. This model uses pharmacogenomics profiles to interpret single-cell spatial transcriptomics data. Ultimately, the model allows scientists to identify spatially localized cellular resistance and hence optimize treatment for individual patients. SpaRx has demonstrated high accuracy in characterizing spatial therapeutic variability, uncovering the molecular mechanisms underpinning drug resistance, and identifying personalized drug targets and effective drug combinations​. RNA sequencing also plays a crucial role in identifiyign drug targets and understnad the molecular mechanisms behind the interactions of drugs.

# Immunological Research:
Spatial transcriptomics helps us map the spatial distribution of immune cells in tissues and understand thier interactions relating to immune responses. Interestingly, many of ST's contributions to immunological research can be connected to cancer biology. An example of this is how ST was used to understand melanoma in a zebrafish model. The researchers focused on BRAF V600E-driven melanomas, utilizing ST to capture the complex spatial patterns within the tumor and its interaction with various surrounding tissues. The study highlighted the transcriptional distinctiveness of the tumor-microenvironment interface, a crucial area for understanding tumor invasion and growth. 

# Sources
Hunter, M.V., Moncada, R., Weiss, J.M. et al. Spatially resolved transcriptomics reveals the architecture of the tumor-microenvironment interface. Nat Commun 12, 6278 (2021). https://doi.org/10.1038/s41467-021-26614-z
Jeffrey R. Moffitt et al.,Molecular, spatial, and functional single-cell profiling of the hypothalamic preoptic region.Science362,eaau5324(2018).DOI:10.1126/science.aau5324
https://www.hhmi.org/news/new-method-allows-precise-measurement-transcriptome-single-cells
Park, Y.M., Lin, DC. Moving closer towards a comprehensive view of tumor biology and microarchitecture using spatial transcriptomics. Nat Commun 14, 7017 (2023). https://doi.org/10.1038/s41467-023-42960-6
https://www.genengnews.com/sponsored/getting-hooked-on-merfish-a-core-labs-journey-into-spatial-genomics/
Tang Z, Liu X, Li Z, Zhang T, Yang B, Su J, Song Q. SpaRx: Elucidate single-cell spatial heterogeneity of drug responses for personalized treatment. bioRxiv [Preprint]. 2023 Aug 6:2023.08.03.551911. doi: 10.1101/2023.08.03.551911. Update in: Brief Bioinform. 2023 Sep 22;24(6): PMID: 37577665; PMCID: PMC10418183.
Xiaoyu Wei et al.,Single-cell Stereo-seq reveals induced progenitor cells involved in axolotl brain regeneration.Science377,eabp9444(2022).DOI:10.1126/science.abp9444
https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-022-01075-1
https://vizgen.com/technology/
https://www.illumina.com/techniques/sequencing/rna-sequencing/ultra-low-input-single-cell-rna-seq.html
