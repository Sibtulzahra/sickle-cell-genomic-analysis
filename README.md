# sickle-cell-genomic-analysis
A beginner bioinformatics project analyzing genetic associations, disease-modifier genes, and population representation in sickle cell disease using publicly available genomic and GWAS data.
# 🧬 Genomic Analysis of Sickle Cell Disease

## 📌 Project Overview

This is my first bioinformatics project as a BS Biotechnology student. The project explores the genetic basis of **sickle cell disease (SCD)** and examines genetic variants and modifier genes associated with SCD-related traits.

The analysis focuses primarily on **HBB**, the gene responsible for the primary sickle-cell mutation, and modifier genes including **BCL11A** and the **HBS1L-MYB region**, which are associated with variation in fetal hemoglobin (HbF) and SCD-related phenotypes.

## 🎯 Objectives

* Explore the genetic basis of sickle cell disease.
* Identify important genes and genetic variants associated with SCD.
* Examine publicly available GWAS association data.
* Compare reported genetic associations across populations.
* Investigate the role of genetic modifiers such as **BCL11A** and **HBS1L-MYB**.
* Develop practical experience in genomic data collection, organization, and interpretation.

## 🧬 Biological Background

Sickle cell disease is an inherited blood disorder primarily caused by pathogenic variants in the **HBB** gene, which encodes the beta-globin subunit
## 📊 Results and Visualizations

The collected GWAS records were organized and compared by gene, population, and statistical significance.

### 1. GWAS Association Records by Gene

The selected dataset contained **11 records for BCL11A** and **7 records for the HBS1L-MYB region**.

![Distribution of GWAS Association Records by Gene](figures/gwas%20record%20by%20gene.png)

### 2. Population Representation

The selected GWAS records represented populations including **African American, Sub-Saharan African, Tanzanian, and Cameroonian** populations.

![Population Representation in Selected GWAS Records](figures/population%20representation.png)

### 3. Statistical Significance of GWAS Associations

The reported p-values in the selected records ranged from approximately **2 × 10⁻¹⁰⁰ to 7 × 10⁻⁶**. The figure presents statistical significance using **−log₁₀(p-value)**, where larger values represent smaller p-values.

![Statistical Significance of Selected GWAS Associations](figures/gwas%20significance.png)

## 🔬 Key Findings

* BCL11A and the HBS1L-MYB region were represented in the selected GWAS records as genetic modifier regions relevant to SCD-related traits.
* The dataset included GWAS associations from multiple populations, with African American records being the most represented in this selected dataset.
* The selected associations showed a wide range of statistical significance.
* These results are based on publicly available and selected GWAS records rather than an original patient-level GWAS analysis.

## ⚠️ Limitations

* This project is a secondary analysis of publicly available data.
* The dataset represents a selected collection of GWAS records and is not an exhaustive GWAS dataset.
* Population representation was limited to the populations included in the selected records.
* No patient-level genomic data were analyzed.
* The project does not perform an original genome-wide association study.

## 🚀 Future Work

Future work could include:

* Expanding the GWAS dataset to include additional studies and populations.
* Performing variant annotation using resources such as dbSNP and ClinVar.
* Investigating allele frequencies across populations.
* Using Python or R for reproducible genomic data analysis.
* Exploring additional SCD modifier genes and genetic variants.
* Developing more advanced genomic visualizations and statistical analyses.

## 📚 Data Sources

The project uses publicly available genomic and genetic association resources, including:

* GWAS Catalog
* NCBI
* dbSNP
* ClinVar
* OMIM

## 👩‍🔬 About the Author

**Sibtul Zahra**
BS Biotechnology Student

**Interests:** Bioinformatics, Genomics, Molecular Biotechnology, and Computational Biology.
