# Multi-Omics Portfolio

This repository contains the code and workflow I used for a project integrating **RNA-seq** and **ChIP-seq** data to explore the role of Scmh1 in PRC1 and its effects on gene expression.  

---

## 1. RNA-seq
- Quality control with FastQC  
- Adapter/quality trimming  
- Alignment (STAR)  
- Gene-level quantification  
- Differential expression analysis (DESeq2)  
- Visualization: PCA, heatmaps, Venn diagrams  

## 2. ChIP-seq
- Quality control with FastQC  
- Alignment (Bowtie2/BWA)  
- Peak calling (MACS2)  
- Peak annotation  
- Signal tracks and QC metrics  

## 3. RNA-seq + ChIP-seq Integration
- Matched differentially expressed genes with nearby ChIP-seq peaks  


All plots can be found in `figures/`

---

All analyses were performed in **R**, with preprocessing steps executed on **Linux** (FASTQ trimming, alignment, duplicate removal, etc.).
