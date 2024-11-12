# Andean Natural Selection at PRKAA1 Data Deposit

This data deposit can also be found at: https://zenodo.org/records/14081450

## Overview

This repository contains data files and scripts related to the study titled "Natural selection at PRKAA1 variant in Andeans is associated with improved ventilation and sleep phenotypes in highlanders and lowlanders." This study explores genetic selection on the PRKAA1 gene in Andean populations and investigates how it impacts physiological responses to high altitude. The data includes genotype-phenotype associations, whole-genome sequences, and selection scans that contribute to understanding how PRKAA1 variants support adaptation to high-altitude environments.

## Repository Structure

### Main Directory

- **README.md**: This document.

### Subdirectories and Files

1. **SNP Genotyping**

   - **prkaa1 association results.xlsx**: Contains statistical results for associations between PRKAA1 SNPs and respiratory and sleep-related phenotypes.
   - **prkaa1 genotype and cdp phenotype.csv**: Dataset with PRKAA1 genotypes linked to phenotypic data, particularly ventilation and sleep metrics, in Cerro de Pasco, Peru.
   - **summary table.xlsx**: Summary statistics for SNP association tests, including sample sizes and effect sizes for each phenotype.

2. **Large Genome Summary Statistics**

   - FHS

     : Data from the Framingham Heart Study (FHS), a cohort of European descent.

     - **dbgap variables.xlsx**: Description of phenotype and covariate variables in FHS.
     - **fhs stats.xlsx**: Summary statistics for PRKAA1 SNPs in FHS, including sleep-related phenotypes.
     - **prkaa1 variant.csv**: Genotype data for PRKAA1 SNPs in FHS participants.

   - HCHS

     : Data from the Hispanic Community Health Study/Study of Latinos (HCHS), focusing on the Latino population.

     - **HCHS top results annotated.xlsx**: Annotated top results from association tests with PRKAA1 variants.
     - **HCHS variable explained.xlsx**: Explanation of phenotype variables in the HCHS dataset.
     - **prkaa1 variant.csv**: Genotype data for PRKAA1 SNPs in HCHS participants.

3. **Luciferase**

   - **prkaa1 luciferase.csv**: Contains results from luciferase assays assessing transcriptional activity related to PRKAA1 variants. These assays were conducted in HEK293T cells to determine the regulatory effect of the rs10035235 variant.

4. **Selection Scan**

   - **selection scan results part1.csv.gz** & **selection scan results part2.csv.gz**: Compressed CSV files with selection scan results for PRKAA1 across the Andean genome. These files contain scores and metrics derived from the Composite of Multiple Signals (CMS) test to identify regions under selection.

5. **Whole Genome Sequencing**

   - **andean_prkaa1_region.vcf**: A VCF file of high-coverage whole-genome sequences from Andean individuals, focused on the PRKAA1 region. Used in selection scans to assess allele frequencies and LD (linkage disequilibrium) patterns.

## Data Use and Citation

Please cite the original manuscript when using this data for publications, presentations, or analyses. Data access is intended for research purposes only and requires proper attribution.

For further information or questions about the data, please contact the repository authors: Wanjun Gu (wanjun.gu@ucsf.edu) and Elijah Lawrence (elijah.lawrence@duke.edu) or the corresponding author Dr. Tatum Simonson (tsimonson@ucsd.edu).
