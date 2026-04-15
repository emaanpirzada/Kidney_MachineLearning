# Kidney_MachineLearning

## Usage instructions
All commands use the linux operating system. 

Run these commands inside the Kidney_MachineLearning directory to create the necessary folder structure: 

```
mkdir Data
mkdir Data/TCGA_Transcriptome
mkdir Data/TCGA_Clinical
```

To download transcriptome data: 

```
wget -P Data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.star_fpkm-uq.tsv.gz
wget -P Data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.star_fpkm-uq.tsv.gz
wget -P Data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.star_fpkm-uq.tsv.gz
gunzip Data/TCGA_Transcriptome/*.gz
```

To download clinical data: 

```
wget -P Data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.clinical.tsv.gz
wget -P Data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.clinical.tsv.gz
wget -P Data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.clinical.tsv.gz
gunzip Data/TCGA_Clinical/*.gz
```

## Data Availability
The transcriptomic and clinical data used in this project are publicly available from the Genomic Data Commons (GDC), part of The Cancer Genome Atlas (TCGA).

The following datasets were used:

TCGA-KICH (Kidney Chromophobe)
TCGA-KIRC (Kidney Renal Clear Cell Carcinoma)
TCGA-KIRP (Kidney Renal Papillary Cell Carcinoma)

Data can be accessed either through the links below or via the command-line tools described in the Usage section.

Transcriptome:
[KICH](https://xenabrowser.net/datapages/?dataset=TCGA-KICH.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

[KIRP](https://xenabrowser.net/datapages/?dataset=TCGA-KIRP.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

[KIRC](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

Clinical:   
[KICH](https://xenabrowser.net/datapages/?dataset=TCGA-KICH.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

[KIRP](https://xenabrowser.net/datapages/?dataset=TCGA-KIRP.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

[KIRC](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)


 
