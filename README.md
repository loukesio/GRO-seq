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

