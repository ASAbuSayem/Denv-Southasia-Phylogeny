# Dengue E-gene phylogeny and lineage connectivity across South Asia

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Kaggle](https://img.shields.io/badge/Notebooks-Kaggle-20BEFF?logo=kaggle&logoColor=white)
![Data](https://img.shields.io/badge/Data-NCBI%20GenBank-2a6f97)
![License](https://img.shields.io/badge/License-MIT-green)

A study of dengue virus (DENV-2 and DENV-3) across South Asia. Public GenBank sequences, Nextclade lineages and maximum-likelihood trees of the envelope (E) gene describe how dengue lineages connect neighbouring countries, with a focus on Bangladesh.

Related to the M.Tech thesis on cross-border dengue early warning (Bangladesh and India). Manuscript in preparation.

![Analysis pipeline](figures/pipeline_animated.gif)

## Explore

| Folder | What you find there |
|---|---|
| [`notebooks/`](notebooks) | Kaggle notebooks for the analysis |
| [`data/`](data) | Input tables built from GenBank metadata |
| [`results/`](results) | Tables, trees and figures produced by the notebooks |
| [`figures/`](figures) | Images used on this page |

## Notebooks

| Order | File | Purpose |
|---|---|---|
| 1 | `01_lineage_connectivity.ipynb` | Lineage sharing between countries |
| 2 | `02_esm2_embeddings.ipynb` | Protein language model embeddings of the E protein |
| 3 | `03_e_gene_phylogeny.ipynb` | E-gene extraction, alignment, tree building and tests |

Dataset on Kaggle: https://www.kaggle.com/datasets/sayemchowdhury23/lineage-dengue-dataset

## Author

Md. Abu Sayem, M.Tech CSE (AI/ML), Manav Rachna International Institute of Research and Studies.
Supervisor: Dr. Mamta Dahiya.

## License

Code under the MIT License. Sequence data belong to their original submitters and are available from NCBI GenBank.
