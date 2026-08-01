\# Bioinformatics Tools Used in RNA-Seq Analysis



This document summarizes the main bioinformatics software commonly used during an RNA-Seq analysis workflow.



| Tool | Main Function | Input | Output |

|------|---------------|-------|--------|

| FastQC | Evaluate sequencing quality | FASTQ | HTML quality reports |

| Trimmomatic | Remove adapters and low-quality bases | FASTQ | Clean FASTQ files |

| HISAT2 | Align sequencing reads to the reference genome | FASTQ | SAM alignment file |

| SAMtools | Convert, sort and index alignment files | SAM/BAM | Sorted BAM files |

| FeatureCounts | Quantify reads assigned to genes | BAM | Gene count matrix |

| DESeq2 | Differential gene expression analysis | Count matrix | Statistical results |



\## Typical RNA-Seq Pipeline



1\. Quality assessment (FastQC)

2\. Read trimming (Trimmomatic)

3\. Sequence alignment (HISAT2)

4\. Alignment processing (SAMtools)

5\. Gene quantification (FeatureCounts)

6\. Differential expression analysis (DESeq2)



\## Conclusion



These tools form the basis of a standard RNA-Seq bioinformatics workflow and are widely used in genomic research.

