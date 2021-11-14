# RAD-seq
Lake Trout

Takes the data from raw reads into vcf and beyond.


1) Start out by examining read quality with [FASTQC](https://github.com/Asrix/RAD-seq/blob/main/FASTQC)

2) Demultiplex the data with the scripts here [Demultiplex](https://github.com/Asrix/RAD-seq/blob/main/Demultiplex)

3) Examine the quality again with [FASTQC](https://github.com/Asrix/RAD-seq/blob/main/FASTQC)

  3b) Count the number of reads (Yes, these are in the multiqc) with [Count](https://github.com/Asrix/RAD-seq/blob/main/Count)

4) Align the sequences to your reference genomce (and index it) with [BWA mem alignment](https://github.com/Asrix/RAD-seq/blob/main/BWA%20mem%20alignment)

    4b) SAMTOOLS for interesting stats

5) Run [STACKS](https://github.com/Asrix/RAD-seq/blob/main/STACKS)

6) Check your library replicates with [STACKS](https://github.com/Asrix/RAD-seq/blob/main/Library-replicate-comparisons), optional [VCF_filtering](https://github.com/Asrix/RAD-seq/blob/main/VCF_filtering) (don't get rid of any individuals!),  a [PCA](https://github.com/Asrix/RAD-seq/blob/main/Library-rep-PCA)

If these look good:

7) Combine your [library replicates](https://github.com/Asrix/RAD-seq/blob/main/Combining-replicates)

8) Realign [BWA mem](https://github.com/Asrix/RAD-seq/blob/main/BWA%20mem%20alignment)

9) STACKS [STACKS](https://github.com/Asrix/RAD-seq/blob/main/STACKS)

10) Filter the [VCF](https://github.com/Asrix/RAD-seq/blob/main/VCF_filtering)

11) [PCAs](https://github.com/Asrix/RAD-seq/blob/main/PCA)

12) Population statistics

13) STRUCTURE


Data exploration:
  1) Try STACKS denovo
