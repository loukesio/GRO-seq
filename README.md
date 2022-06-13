![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)
[![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)

Before running GROseq pipeline you will need to obtain genome(fasta), bowtie index (.bt2), chromosome sizes (.chrom.sizes) and annotation.

# GRO-seq

GRO-seq allows us to profile the distribution of nascent RNAs across the genome and analyse the activity of RNA polII.

## 1. Remove/Trim a 3’ adapter, Cutadapt
install cutadapt using the instruction from this [page.](https://cutadapt.readthedocs.io/en/stable/guide.html)

```r
cutadapt -a AACCGGTT -o output.fastq input.fastq
```
## 2. Remove rRNAs using STAR 
install STAR from thing github [repository.](https://github.com/alexdobin/STAR) 

## 3. Using Tallymer and Genome tools
http://genometools.org/

### References 

[1] https://github.com/vari-bbc/GROseq_scripts/blob/main/GROP_20190515_GroSeq.Rmd <br>
[2] https://github.com/vari-bbc/GROseq_scripts/blob/main/GROP_20190515_GroSeq.sh <br>
[3] https://nf-co.re/nascent <br>
[4] https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02349-4 <br>
[5] https://github.com/Danko-Lab/tutorials/blob/master/PRO-seq.md <br>
[6] https://scientiasalut.gencat.cat/bitstream/handle/11351/6516/proapoptotic_gene_interferon_regulatory_factor_1_mediates_antiproliferative_outcome_paired_box_2_gene_tamoxifen_2020_material_suplementari.pdf?sequence=2&isAllowed=y
