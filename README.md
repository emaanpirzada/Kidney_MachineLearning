# Kidney_MachineLearning

## Data availability

Create these folders first: 

```
mkdir data
mkdir data/TCGA_Transcriptome
mkdir data/TCGA_Clinical
```

To download transcriptome data: 

```
wget -P data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.star_fpkm-uq.tsv.gz
wget -P data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.star_fpkm-uq.tsv.gz
wget -P data/TCGA_Transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.star_fpkm-uq.tsv.gz
gunzip data/TCGA_Transcriptome/*.gz
```

To download clinical data: 

```
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.clinical.tsv.gz
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.clinical.tsv.gz
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.clinical.tsv.gz
gunzip data/TCGA_Clinical/*.gz
```
 
