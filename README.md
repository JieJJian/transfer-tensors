# transfer-tensors

Data and code for analyzing football transfer fees with Bayesian tensor factorization, identifying patterns across selling countries, buying leagues, player positions, and seasons.

## Download and use

1. Open [transfer-tensors.zip](transfer-tensors.zip) and download the archive using GitHub's download button.
2. Extract the archive to create a `transfer-tensors` folder.
3. Open the `README.md` inside that folder for installation, data definitions, and reproduction commands.

The research files are stored inside the ZIP. GitHub does not automatically extract them into this repository's file listing.

## Package contents

| Folder inside the ZIP | Contents |
|---|---|
| `tensor_data/v1/` | Transfer-fee tensors, observation masks, dimension labels, readable data tables, and preprocessing code |
| `raw_sources/` | The exact source archives used to build the data |
| `sports_prg/` | Bayesian tensor model and evaluation code |
| `model_results/` | Saved models, forecast arrays, and verified results |
| `figures/` and `scripts/` | Component figure, plotted values, and reproduction scripts |

The annual tensor covers 107 selling countries and territories, seven receiving leagues, four position groups, and 12 seasons from 2009/10 through 2020/21. Observation masks distinguish usable values from incomplete or unknown fee totals.

## Sources and method

- [Dmitrii Antipov's football-transfers-data](https://github.com/d2ski/football-transfers-data) supplies the primary transfer records.
- [Ewen Henderson's transfers](https://github.com/ewenme/transfers) supplies collection-coverage comparisons.
- [Jian and Schein (2026)](https://arxiv.org/abs/2606.17267v1) introduce the underlying tensor factorization method.

The archive includes exact source revisions, attribution, and checksums in `DATA_PROVENANCE.md`, `references.bib`, and the data manifests.

## Licensing and data status

The original project code is covered by [LICENSE-CODE](LICENSE-CODE). This license does not cover third-party data or the cited paper.

The redistribution basis for the source-derived data remains to be documented. See [DATA_RIGHTS.md](DATA_RIGHTS.md) for the current status.
