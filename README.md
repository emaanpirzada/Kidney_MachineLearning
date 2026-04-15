# Kidney_MachineLearning

## Data availability
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
 
