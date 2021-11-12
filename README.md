# RAD-seq
Lake Trout

Takes the data from raw reads into vcf and beyond.


1) Start out by examining read quality with [FASTQC](https://github.com/Asrix/RAD-seq/blob/main/FASTQC)

2) Demultiplex the data with the scripts here [Demultiplex](https://github.com/Asrix/RAD-seq/blob/main/Demultiplex)

3a) Examine the quality again with FASTQC
3b) Count the number of reads (Yes, these are in the multiqc) with [Count](https://github.com/Asrix/RAD-seq/blob/main/Count)

4) Align the sequences to your reference genomce (and index it) with [BWA mem alignment](https://github.com/Asrix/RAD-seq/blob/main/BWA%20mem%20alignment)

5) Run STACKS

6) Check your library replicates

5b) Try STACKS denovo
