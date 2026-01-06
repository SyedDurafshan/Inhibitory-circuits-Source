# Inhibitory-circuits-Source
This repository contains materials used for the study:
Syed Durafshan Sakeena, Ravbar Primoz, Simpson Julie H. (2025)
Inhibitory circuits control leg movements during _Drosophila_ grooming
eLife 14: RP106446
https://doi.org/10.7554/eLife.106446.2

Contents

**1. Connectivity analysis code:**
EM_connectivity_matrix_13A-muscle_synergies-Syed-eLife.ipynb (Syed)
   - Computes cosine similarity
   - Plots connectivity matrices

**2. Behavioral data analysis code:**
MS_data_analysis_eLife_rev_GitHub_1p2.ipynb (Syed & Ravbar)

- Analysis of segmented behavioral data
- UMAP visualization colored by behavioral features or cluster (class) membership.
- Segments (individual leg movements) are described by kinematic features and classified into behavioral types (e.g., head grooming, front leg grooming)

Linear mixed-effects model (LMM) fitting is performed in the section labeled
“--- LMM Main Script ---”

Includes tools for:
- Group comparisons for feature–class pairs
- Variability analysis of feature–class pairs

**3. Source data**
CSV files for connectome and behavioral analyses

**Additional related resources**
Source data and code for the **computational model** (Figures 6 and 7) are available at:
https://github.com/PrimozRavbar/Inhibitory-circuits
