# Comparative Genomic Analysis and Phylogenetic Inference using Python

## Project Overview
This project integrates large-scale genomic data processing, statistical filtering, and phylogenetic analysis using Python. The dataset—sourced from NCBI GenBank and RefSeq—was curated to include high-quality bacterial, archaeal, and eukaryotic genomes based on completeness and reference status. The analysis pipeline explores genome size and GC content distributions and infers phylogenetic relationships among mammalian and microbial species.

## Key Features
- **Data Wrangling:** Processed over 200,000 genome entries using Python `pandas` with regex-based filtering to select high-quality genomes.
- **Statistical Analysis:** Examined GC content and genome size variation across taxonomic groups.
- **Phylogenetic Analysis:** Constructed and visualized phylogenetic trees using BioPython and R (`msa`, `phangorn`), including evolutionary model selection and bootstrap support.
- **Integration:** Combined Python and R workflows to validate phylogenetic relationships and ensure reproducibility.

## Data Files
- `tree_nodes.csv`, `taxonomy.csv`, `taxonomy_key.csv` – curated genomic datasets
- `mammal_tree.nwk` – phylogenetic tree in Newick format
- `task 8.pdf` – project report

## Skills & Tools
- **Languages & Libraries:** Python (pandas, matplotlib, BioPython), R (msa, phangorn)
- **Data Science & Bioinformatics:** Data cleaning, exploratory analysis, statistical filtering, visualization, phylogenetic inference
- **Workflow & Collaboration:** Jupyter Notebook, Git

## Usage
1. Clone the repository:
   ```bash
   git clone <repo-url>