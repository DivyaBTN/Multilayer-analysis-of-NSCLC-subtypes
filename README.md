# Multilayer NSCLC Subtype Analysis

## Overview
This repository presents a systems-level multilayer analysis of non-small cell lung cancer (NSCLC) subtypes, focusing on lung adenocarcinoma (LUAD) and lung squamous cell carcinoma (LUSC). The study integrates genomic alterations, clinical outcomes, pathway-level changes, and protein-level structural analysis to understand subtype-specific mechanisms in NSCLC.

## Objectives
- To characterize somatic mutation patterns in NSCLC subtypes
- To identify frequently mutated and clinically relevant genes
- To evaluate the association between genomic alterations and patient survival
- To investigate disrupted signaling pathways in NSCLC
- To perform protein motif analysis and molecular docking for functional and structural insights

## Data Sources
- TCGA LUAD and LUSC datasets accessed via cBioPortal for Cancer Genomics
- Associated clinical data obtained from cBioPortal

## Data Layers and Methods

### 1. Genomic Analysis
- Retrieval of somatic mutation data for LUAD and LUSC from cBioPortal
- Identification of top mutated genes
- Visualization of mutation landscapes using oncoprints and Circos plots
- Analysis of mutation distribution across chromosomes
- Mutual exclusivity and co-occurrence analysis of key genes

### 2. Clinical Analysis
- Kaplan–Meier survival analysis
- Assessment of the impact of selected gene mutations on patient survival

### 3. Pathway and Systems-Level Analysis
- Pathway enrichment analysis using Reactome
- Investigation of altered signaling pathways, including STK11- and PTEN-related pathways
- Systems-level interpretation of genomic alterations

### 4. Protein-Level Structural Analysis
- Motif analysis of selected cancer-relevant proteins (e.g., EPS8, EGFR, AKT, FOXO3A)
- Molecular docking studies to explore protein–ligand interactions (e.g., EPS8 with small-molecule inhibitors)
- Functional interpretation of docking results in the context of NSCLC biology

## Tools and Resources
- cBioPortal for Cancer Genomics
- R for mutation analysis, visualization, and survival analysis
- ReactomePA for pathway enrichment analysis
- Structural bioinformatics and molecular docking tools

- ## Repository Structure
'''data/        # Input datasets and processed data
scripts/     # R scripts and analysis code
results/     # Tables and intermediate outputs
figures/     # Plots including oncoprints, Circos plots, and survival curves
docking/     # Motif analysis and molecular docking files
docs/        # Additional documentation'''

## Key Outcomes
- Identification of subtype-specific mutation patterns in LUAD and LUSC
- Visualization of chromosomal mutation distribution using Circos plots
- Detection of clinically relevant genomic alterations associated with survival
- Identification of disrupted signaling pathways in NSCLC
- Structural and functional insights from protein motif analysis and docking studies

## Project Status
> This repository contains the finalized analysis and results for the project.

## Future Scope
- Integration of transcriptomic data
- Expansion to multi-omics analysis
- Validation using independent datasets

## Author
**Doddaboina Divya**  
M.Tech Biotechnology
