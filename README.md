# NGS-data

## Introduciton

This deposity contains many kinds of sequencing datasets from Novogene. Any researchers, clinicians or collaborators who are interested in NGS can download freely. And we appriciate that you could give us any advice or suggestions.

## 1. Human Genome Sequencing

To compare with benchmark of GIAB, we provide genome sequencing data of HG002, which is one member of Ashkenazim son-father-mother trio, also named NA24385. The "High-confidence" variant calls are available for GRCh37 and GRCh38 under each genome at [NCBI ftp](https://bit.ly/2HNGELT) or ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/release.

- ### Whole Exome Sequencing

**Kit for exome capture**: Agilent SureSelect Human All Exon V6 Kit

**Sequencing strategy**: Illumina NovaSeq, PE150

sample source | left reads | right reads | md5sum | data size
---|:--:|:--:|:--:|:--
HG002 | HG002_novogene_wes_20g_rep1_R1.fq.gz | HG002_novogene_wes_20g_rep1_R2.fq.gz | md5 | 16G
HG002 | HG002_novogene_wes_20g_rep2_R1.fq.gz | HG002_novogene_wes_20g_rep2_R2.fq.gz | md5 | 16G
HG002 | HG002_novogene_wes_12g_R1.fq.gz | HG002_novogene_wes_12g_R2.fq.gz | md5 | 12G
HG002 | HG002_novogene_wes_6g_R1.fq.gz | HG002_novogene_wes_6g_R2.fq.gz | md5 | 6G


- ### Whole Genome Sequencing

**Sequencing strategy**: Illumina NovaSeq, PE150

sample source | left reads | right reads | md5sum | data size
---|:--:|:--:|:--:|:--
HG002 | HG002_novogene_wes_20g_R1.fq.gz | HG002_novogene_wgs_20g_R2.fq.gz | md5 | 20G
Novogene | Novogene_wgs_90g_R1.fq.gz | Novogene_wgs_90g_R2.fq.gz | md5 | 90G
Novogene | Novogene_wgs_120g_R1.fq.gz | Novogene_wgs_120g_R2.fq.gz | md5 | 120G
Novogene | Novogene_wgs_180g_l1_R1.fq.gz Novogene_wgs_180g_l2_R1.fq.gz | Novogene_wgs_180g_l2_R2.fq.gz Novogene_wgs_180g_l2_R2.fq.gz | md5 | 180G



## 2. Transcriptome Sequencing

Transcriptome or RNA sequencing can be ultilized to analysis many classes of RNA molecules, such as mRNA, non coding RNA, small RNA or RNAs from a single cell. To get a better view of data quality, we also sequence with ERCC spike-in control mixtures, which are used to evaluation gene expression measurement of new technique.

- ### mRNA Sequencing

species | left reads | right reads | md5sum | spike-in | data size
---|:--:|:--:|:--:|:--:|:--
Human | Novogene_human_mrnaseq_rep1_R1.fq.gz | Novogene_human_mrnaseq_rep1_R2.fq.gz | md5 | Y | 6G
Human | Novogene_human_mrnaseq_rep2_R1.fq.gz | Novogene_human_mrnaseq_rep2_R2.fq.gz | md5 | Y | 6G
Human | Novogene_human_mrnaseq_rep3_R1.fq.gz | Novogene_human_mrnaseq_rep3_R2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep1_R1.fq.gz | Novogene_arabidopsis_mrnaseq_rep1_R2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep2_R1.fq.gz | Novogene_arabidopsis_mrnaseq_rep2_R2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep3_R1.fq.gz | Novogene_arabidopsis_mrnaseq_rep3_R2.fq.gz | md5 | Y | 6G

- ### Whole RNA Sequencing

species | left reads | right reads | md5sum | spike-in | data size
---|:--:|:--:|:--:|:--:|:--
Human | Novogene_human_wholernaseq_R1.fq.gz | Novogene_human_wholernaseq_R2.fq.gz | md5 | N | 12G

- ### Single Cell RNA Sequencing

species | left reads | right reads | md5sum | spike-in | data size
---|:--:|:--:|:--:|:--:|:--
Arabidopsis | Novogene_arabidopsis_singlecell_R1.fq.gz | Novogene_arabidopsis_singlecell_R2.fq.gz | md5 | N | 12G


## 3. PacBio Sequencing

- ### Isoform Sequencing (Iso-Seq)

species | subread_bam | subread_bam_index | md5sum | data size
---|:--:|:--:|:--:|:--
Human | Novogene_pacbio_isoseq_subreads.bam | Novogene_pacbio_isoseq_subreads.bam.pbi | md5 | 

- ### Pacbio Genome Sequencing

species | subread_bam | subread_bam_index | md5sum | data size
---|:--:|:--:|:--:|:--
XXX | Novogene_pacbio_genome_subreads.bam | Novogene_pacbio_genome_subreads.bam.pbi | md5 | 


## 4. 10X Genomics
- ### 10X Single Cell Gene Expression

species | left reads | right reads | md5sum | data size
---|:--:|:--:|:--:|:--
XXX | Novogene_10x_singlecell_i1_R1.fq.gz Novogene_10x_singlecell_i2_R1.fq.gz Novogene_10x_singlecell_i3_R1.fq.gz Novogene_10x_singlecell_i4_R1.fq.gz | Novogene_10x_singlecell_i1_R2.fq.gz Novogene_10x_singlecell_i2_R2.fq.gz Novogene_10x_singlecell_i3_R2.fq.gz Novogene_10x_singlecell_i4_R2.fq.gz | md5 | 

- ### 10X Linked-Reads Genome Sequencing

species | left reads | right reads | md5sum | data size
---|:--:|:--:|:--:|:--
XXX | Novogene_10x_genome_i1_R1.fq.gz Novogene_10x_genome_i2_R1.fq.gz Novogene_10x_genome_i3_R1.fq.gz Novogene_10x_genome_i4_R1.fq.gz | Novogene_10x_genome_i1_R2.fq.gz Novogene_10x_genome_i2_R2.fq.gz Novogene_10x_genome_i3_R2.fq.gz Novogene_10x_genome_i4_R2.fq.gz | md5 | 


## Citations
- [GIAB - Genome in a Bottle](https://www.nist.gov/programs-projects/genome-bottle)
- [ERCC - External RNA Controls Consortium](https://jimb.stanford.edu/ercc)


## About Novogene ([EN](https://en.novogene.com) | [CN](http://www.novogene.com))

Novogene is a leading provider of genomic services and solutions with cutting edge NGS and bioinformatics expertise and **the largest sequencing capacity** in the world. Novogene utilizes scientific excellence, a commitment to customer service and unsurpassed data quality to help our clients realize their research goals. The company has become a world-leader in NGS services, with 1,800 employees and multiple locations across the globe. Novogene’s depth of experience has resulted in the ownership of 49 NGS-related patents, as well as the publishing of **over 1850 customer research papers**, often in well-respected publications such as *Nature* and *Science*.
