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
The transcriptomic data used in this project is publicly available from the Genomic Data Commons (GDC). We used the following datasets: TCGA-KICH (Kidney Chromophobe), TCGA-KIRC (Kidney Renal Clear Cell Carcinoma), TCGA-KIRP (Kidney Renal Papillary Cell Carcinoma). In addition, Clinical data for the same cohorts (TCGA-KICH, TCGA-KIRC, and TCGA-KIRP) were also obtained from the Genomic Data Commons (GDC). For more information about all of this data you can follow the links below. 

Transcriptome:
[KICH](https://xenabrowser.net/datapages/?dataset=TCGA-KICH.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
[KIRP](https://xenabrowser.net/datapages/?dataset=TCGA-KIRP.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
[KIRC](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.star_fpkm-uq.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

Clinical:   
[KICH](https://xenabrowser.net/datapages/?dataset=TCGA-KICH.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
[KIRP](https://xenabrowser.net/datapages/?dataset=TCGA-KIRP.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
[KIRC](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)


 
