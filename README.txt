DATASET FILES FOR REPRODUCIBILITY
=====================================

This folder contains the data subset used in the paper: 'Harrensing Transformer Knowledge: A Novel Approach for Biomedical Abbreviation Disambiguation'.

1. MeDAL_subset_with_folds.csv:
   - Contains the full subset from the data with instances used in the study.
   - The 'fold' column indicates which of the 10 cross-validation folds each instance belongs to (0-9).

2. MeDAL_subset_instance_ids.txt:
   - A lightweight text file containing only the unique instance IDs (corresponding to original row numbers) that make up our subset.
   - This file can be used to reconstruct the exact subset from the original full dataset.
