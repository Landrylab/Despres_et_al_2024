# Despres_et_al_2024
Jupyter notebooks used for data analysis and figure generation of Despres et al 2024. Raw sequence files can be downloaded from the NCBI SRA https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1061126

## Software used:
- FastQC v0.11.5
- Trimmomatic v0.39
- PANDAseq 2.11
- vsearch v2.7.1_linux_x86_64
- Python 3.7.9

## Python  package versions:
- pandas 1.2.1
- numpy 1.19.2
- matplotlib 3.3.2
- scipy 1.5.2
- biopython 1.78
- seaborn 0.11.1

### DMS_validation
Contains files and code used to perform DMS library QC. Generates initial abundance values for the DMS 5-FC selection assay.

### 5FC_selection
Contains files and code used to identify LOF alleles from the DMS assay.
- DMS_analysis_5FC.ipynb: Goes from raw sequencing data to variant abundance.
- variant_abundance.ipynb: Computes DMS scores and generates figures S2, S3, S4, S5

### single_colony_genotyping
Contains files and code used to analyze the single colony sequencing data. Generates figures 2a-c S6, S7, S8, S9

### haploid_validations.ipynb
Analyze growth curve data for haploid parental strains used in the validation assays. Generates figure S10.

### haploid_validations.ipynb
Analyze haploinsufficiency dose-response growth curve data and generate figure S13.

### DHFR_PCA_data.ipynb
Analyze DHFR-PCA growth curve data and generate figure S16bc
