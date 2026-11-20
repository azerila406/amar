# Data

The project uses a subset of [NACC data](https://www.naccdata.org/about-nacc-data). The original download date and the collection period for this subset are unknown.

These files are in the `alzheimer/` folder inside `alzheimer(1).zip`.

- `udslong_imputed.csv` for clinical scores and cognitive status
- `mriscanclean.csv` for left and right entorhinal cortex thickness in millimeters
- `combined_adjacency_matrix.csv` for brain region connections, read in Phase 1

The notebooks join the clinical and MRI records by `NACCID`. The analysis uses a valid CDR score and the average of the left and right thickness measurements for each person.
