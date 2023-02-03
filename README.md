# Flaveria_grafting
A joint project with Cologne Uuniversity
This project is running through these steps:
1. I checked the quality of read files
2. trimmed the fastq files
3. run Trinity to create assemblies, one from C3 homograft root and shoot samples, anr the other from C4 homograft samples
4. Check the quality of assemblies by ExN50 and RNA-seq Read Representation
5. Running Trinonate to annotate the contigs
6. Estimating transcript abundance by RSEM; The goal is to calculate expression values, RPKM, and TPM for downstream analyses (Check the explanations in pipeline file)
7. Identify the transmitted RNAs (check the pipeline file)
