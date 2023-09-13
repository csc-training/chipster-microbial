# Microbial Community Analysis with Chipster

## Websites and teaching materials

[Chipster website](https://chipster.csc.fi/)

[Chipster web app](https://chipster.rahtiapp.fi/)

[Lecture videos (May 2021)](https://www.youtube.com/playlist?list=PLjiXAZO27elBjPaknlze6BkxebpEuj9KL)

[Day 1 exercise sheet](https://csc-training.github.io/chipster-microbial/MiSeq/Exercises_MiSeq_day1.html)

[Day 2 exercise sheet](https://csc-training.github.io/chipster-microbial/MiSeq/Exercises_MiSeq_day2.html)

---

## Course description

This online course introduces the participants to microbiome analysis methods, tools, and file formats. It covers the whole workflow from quality control and filtering to quantification and statistical analysis using Mothur and Phyloseq tools integrated in the user-friendly Chipster platform. Please note that this course focuses on microbiome analysis of amplicon sequencing data (as opposed to metagenomics where all the genes are sequenced).

The course consists of lectures and practical exercises. The lectures will be available as short videos, and the participants are requested to view them prior to the course. This gives you more time to reflect on the concepts so that you can use the course days more efficiently. The lectures are summarized and questions answered during the course.

---

## Learning outcomes

After this course, you will be able to
- preprocess amplicon sequencing data for microbial community analysis
- compare the structure of microbial communities using ordinations and multivariate statistics

---

## Prerequisites and content level

The free and user-friendly Chipster software is used in the exercises, so no previous knowledge of Unix or R is required.

The content level of the course is intermediate and the course is intended for life scientists who are planning to use 16S or other amplicon sequencing in their microbiome research. This course is suitable also for those researchers who do not plan to analyze data themselves, but who need to understand the concepts in order to discuss with bioinformaticians.

---

## Agenda

**Day 1**

- Checking the quality of reads with MultiQC
- Preprocessing 
    - combining paired reads to contigs
    - screening sequences for length and ambiguous bases
    - removing identical sequences
- Alignment
    - aligning sequences to the Silva reference alignment
    - screening aligned sequences for alignment position and homopolymers
    - filtering alignments for empty columns and overhangs
    - removing new identical sequences
- Preclustering, removing chimeric sequences

**Day 2**

- Data tidying and analysis
- Creating and importing phyloseq input files
    - including taxonomic assignments and OTU clustering
    - data inspection and tidying using phyloseq
    - removing unwanted taxa
    - filtering singletons and doubletons
    - prevalence filtering
- Data transformation, ordination and conversion
    - CLR, Hellinger and % relative abundance
    - nMDS and db-RDA
    - DESeq2 format conversion and variance-stabilising transformation
- Relative abundance plots
- Community comparisons using PERMANOVA, PERMDISP and DESeq2
