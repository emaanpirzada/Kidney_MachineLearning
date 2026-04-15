# Kidney_MachineLearning

## Data availability

To download transcriptome data: 

```
wget -P data/TCGA_transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.star_fpkm-uq.tsv.gz
wget -P data/TCGA_transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.star_fpkm-uq.tsv.gz
wget -P data/TCGA_transcriptome/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.star_fpkm-uq.tsv.gz
gunzip data/TCGA_transcriptome/*.gz
```

To download clinical data: 

```
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRC.clinical.tsv.gz
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KIRP.clinical.tsv.gz
wget -P data/TCGA_Clinical/ https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-KICH.clinical.tsv.gz
gunzip data/TCGA_Clinical/*.gz
```
 
