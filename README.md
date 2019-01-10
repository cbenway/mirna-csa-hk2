# mirna-csa-hk2
## Integrative analysis of miRNA:mRNA interactome in CsA-induced nephrotoxicity
Previously, we published an integrative analysis of miRNA:mRNA interactions in a cell model of cyclosporine A induced nephrotoxicity (C. Benway, J. Iacomini, American Journal of Transplantation, in press, [doi: 10.1111/ajt.14503](https://www.ncbi.nlm.nih.gov/pubmed/28925592)):
>Calcineurin inhibitors induce nephrotoxicity through poorly understood mechanisms thereby limiting their use in transplantation and other diseases. Here we define a microRNA (miRNA)-messenger RNA (mRNA) interaction map that facilitates exploration into the role of miRNAs in cyclosporine-induced nephrotoxicity (CIN) and the gene pathways they regulate. Using photoactivatable ribonucleoside-enhanced crosslinking and immunoprecipitation (PAR-CLIP), we isolated RNAs associated with Argonaute 2 in the RNA-induced silencing complex (RISC) of cyclosporine A (CsA) treated and control human proximal tubule cells and identified mRNAs undergoing active targeting by miRNAs. CsA causes specific changes in miRNAs and mRNAs associated with RISC, thereby altering post-transcriptional regulation of gene expression. Pathway enrichment analysis identified canonical pathways regulated by miRNAs specifically following CsA treatment. RNA-seq performed on total RNA indicated that only a fraction of total miRNAs and mRNAs are actively targeted in the RISC, indicating that PAR-CLIP more accurately defines meaningful targeting interactions. Our data also revealed a role for miRNAs in calcineurin-independent regulation of JNK and p38 MAPKs caused by targeting of MAP3K1. Together, our data provide a novel resource and unique insights into molecular pathways regulated by miRNAs in CIN. The gene pathways and miRNAs defined may represent novel targets to reduce calcineurin induced nephrotoxicity.

The purpose of this repository is to explore various bioinformatics tools available to analyze PAR-CLIP miRNA:mRNA interactome data integrated with corresponding miRNA and mRNA expression data. We will use our published HK-2 cell data in order to reproduce the findings and expand our analysis using a network approach (data accessible at NCBI GEO database (Edgar et al., 2002), accession [GSE98670](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE98670)). 

## List of data files
- [hsa_mature_dna.fasta](https://github.com/cbenway/mirna-csa-hk2/blob/master/hsa_mature_dna.fasta) - FASTA file of all mature miRNA sequences in DNA format from mirBase 21 (2015). For use with [SeedVicious v1.1](https://seedvicious.essex.ac.uk/) prediction of miRNA target sites.

