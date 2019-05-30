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
HG002 | HG002_novogene_wes_20g_rep1_1.fq.gz | HG002_novogene_wes_20g_rep1_2.fq.gz | md5 | 20G
HG002 | HG002_novogene_wes_20g_rep2_1.fq.gz | HG002_novogene_wes_20g_rep2_2.fq.gz | md5 | 20G
HG002 | HG002_novogene_wes_12g_1.fq.gz | HG002_novogene_wes_12g_2.fq.gz | md5 | 12G
HG002 | HG002_novogene_wes_6g_1.fq.gz | HG002_novogene_wes_6g_2.fq.gz | md5 | 6G


- ### Whole Genome Sequencing

**Sequencing strategy**: Illumina NovaSeq, PE150

sample source | left reads | right reads | md5sum | data size
---|:--:|:--:|:--:|:--
HG002 | HG002_novogene_wes_20g_1.fq.gz | HG002_novogene_wgs_20g_2.fq.gz | md5 | 20G
Novogene | Novogene_wgs_90g_l1_1.fq.gz Novogene_wgs_90g_l2_1.fq.gz Novogene_wgs_90g_l3_1.fq.gz Novogene_wgs_90g_l4_1.fq.gz | Novogene_wgs_90g_l1_2.fq.gz Novogene_wgs_90g_l2_2.fq.gz Novogene_wgs_90g_l3_2.fq.gz Novogene_wgs_90g_l4_2.fq.gz | md5 | 90G
Novogene | Novogene_wgs_120g_l1_1.fq.gz Novogene_wgs_120g_l2_1.fq.gz Novogene_wgs_120g_l3_1.fq.gz Novogene_wgs_120g_l4_1.fq.gz | Novogene_wgs_120g_l1_2.fq.gz Novogene_wgs_120g_l2_2.fq.gz Novogene_wgs_120g_l3_2.fq.gz Novogene_wgs_120g_l4_2.fq.gz | md5 | 120G
Novogene | Novogene_wgs_150g_l1_1.fq.gz Novogene_wgs_150g_l2_1.fq.gz Novogene_wgs_150g_l3_1.fq.gz Novogene_wgs_150g_l4_1.fq.gz | Novogene_wgs_150g_l1_2.fq.gz Novogene_wgs_150g_l2_2.fq.gz Novogene_wgs_150g_l3_2.fq.gz Novogene_wgs_150g_l4_2.fq.gz | md5 | 150G



## 2. Transcriptome Sequencing

Transcriptome or RNA sequencing can be ultilized to analysis many classes of RNA molecules, such as mRNA, non coding RNA, small RNA or RNAs from a single cell. To get a better view of data quality, we also sequence with ERCC spike-in control mixtures, which are used to evaluation gene expression measurement of new technique.

- ### mRNA Sequencing

species | left reads | right reads | md5sum | spike-in | data size
---|:--:|:--:|:--:|:--:|:--
Human | Novogene_human_mrnaseq_rep1_1.fq.gz | Novogene_human_mrnaseq_rep1_2.fq.gz | md5 | Y | 6G
Human | Novogene_human_mrnaseq_rep2_1.fq.gz | Novogene_human_mrnaseq_rep2_2.fq.gz | md5 | Y | 6G
Human | Novogene_human_mrnaseq_rep3_1.fq.gz | Novogene_human_mrnaseq_rep3_2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep1_1.fq.gz | Novogene_arabidopsis_mrnaseq_rep1_2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep2_1.fq.gz | Novogene_arabidopsis_mrnaseq_rep2_2.fq.gz | md5 | Y | 6G
Arabidopsis | Novogene_arabidopsis_mrnaseq_rep3_1.fq.gz | Novogene_arabidopsis_mrnaseq_rep3_2.fq.gz | md5 | Y | 6G

- ### Whole RNA Sequencing
species | left reads | right reads | md5sum | spike-in | data size
---|:--:|:--:|:--:|:--:|:--
Human | Novogene_human_wholernaseq_1.fq.gz | Novogene_human_wholernaseq_2.fq.gz | md5 | N | 12G
Arabidopsis | Novogene_arabidopsis_wholernaseq_1.fq.gz | Novogene_arabidopsis_wholernaseq_2.fq.gz | md5 | N | 12G

- ### Single Cell RNA Sequencing

```
To be continued ...
```


## 3. PacBio Sequencing

- ### Isoform Sequencing (Iso-Seq)
```
To be continued ...
```
- ### Pacbio Genome Sequencing
```
To be continued ...
```


## 4. 10X Genomics
- ### 10X Single Cell Gene Expression
```
To be continued ...
```
- ### 10X Linked-Reads Genome Sequencing
```
To be continued ...
```


## Citations
- [GIAB - Genome in a Bottle](https://www.nist.gov/programs-projects/genome-bottle)
- [ERCC - External RNA Controls Consortium](https://jimb.stanford.edu/ercc)


## About Novogene ([EN](https://en.novogene.com) | [CN](http://www.novogene.com))

Novogene is a leading provider of genomic services and solutions with cutting edge NGS and bioinformatics expertise and **the largest sequencing capacity** in the world. Novogene utilizes scientific excellence, a commitment to customer service and unsurpassed data quality to help our clients realize their research goals. The company has become a world-leader in NGS services, with 1,800 employees and multiple locations across the globe. Novogene’s depth of experience has resulted in the ownership of 49 NGS-related patents, as well as the publishing of **over 1850 customer research papers**, often in well-respected publications such as *Nature* and *Science*.
