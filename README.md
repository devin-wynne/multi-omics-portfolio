# Multi Omics Portfolio
This repository shows the code and workflow I used for a project integrating RNA-seq and ChIP-seq data to explore the role of SCMH1 in PRC1 and gene expression.

1.RNA-Seq
   *Quality control with FastQC
   *Adapter/quality trimming
   *Alignment (e.g., STAR)
   *Gene-level quantification
   *Differential expression analysis (DESeq2)
   Visualization: PCA, heatmaps, Venn diagrams

2.ChIP-Seq
   *Quality control with FastQC
   *Alignment (Bowtie2/BWA)
   *Peak calling with MACS2
   *Peak annotation
   *Signal tracks + QC metrics

3. RNA-seq + ChIP-seq Integration:
  *Matched differentially expressed genes with nearby ChIP-seq peaks
*Generated integrated plots (included in figures/)
   

All analyses were performed in R with additional preprocessing on Linux (FASTQ trimming, alignment, duplication removal, etc.)
