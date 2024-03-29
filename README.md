## Overview
This repository provides analysis of peak widths of 10X Chromium 3' end data across 28 libraries from 
[Tabula Muris](https://doi.org/10.1038/s41586-018-0590-4) at a set of cleavage sites curated for minimal 
internal priming upstream of the cleavage site. The results of this analysis are reported in
[*Fansler et al., bioRxiv, 2023*](https://www.biorxiv.org/content/10.1101/2021.11.22.469635v2).

## Organization
The **input count data** is provide in two forms:
  - **raw**: `muris.coverage.partial.tsv.gz`
  - **clean**: `tmuris.coverage.partial.clean800.tsv.gz`

The analysis reported in [*Fansler et al., bioRxiv, 2023*](https://www.biorxiv.org/content/10.1101/2021.11.22.469635v2)
is found in the `empirical_quantiles.ipynb` IPython notebook.

Additional notebooks are included as alternative model-based approaches, but were not used in the publication.

## Software enviroment
The `environment.yaml` file provides a record of software versions used to run the notebooks. This 
was originally executed on macOS and is only expected to be recreatable on macOS systems.
