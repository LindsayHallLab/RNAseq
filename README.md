# RNAseq
Alignment free approach for RNAseq data analysis
This repository contains script to run kallisto on multi samples
Step1. ./run_rnaseqmapping_slurm lib.txt reads1.txt reads2.txt outputLocation ~/path/to/ref/kallisto.idx
Step2. Merge the kallisto raw counts for each sample and create the counts table, see example table
Step3. Create a experiment table, see example table 
Step4. Run DESeq2 using the R script 
