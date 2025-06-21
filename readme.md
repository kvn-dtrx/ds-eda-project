# DS EDA Project: King County House Prices

## Synopsis

This repository contains an analysis of a dataset featuring information about house sales in King County. The purpose of this analysis is to infer recommendations for a (hopefully fictional) client whose description reads follows:

> Amy Williams | Seller | Mafiosa, sells several central houses (top 10%) over time and needs average outskirt houses over time to hide from the FBI.

For more details about the assignment, please refer to [this file](./archive/assignment.md).

We define measures centrality, exceptionality, privacy

TODO: The data set is retrieved from the neue fische database. It is very similar to <https://www.kaggle.com/datasets/harlfoxem/housesalesprediction> but contains possibly contaminations deliberatively injected by the instructors for exercise purposes.

## Repository Organisation

The organization of the repository follows common conventions and therefore requires little explanation. For a quick orientation, we mention only the following:

| Path | Content |
| --- | --- |
| [`./notebooks/*.ipynb`](./notebooks) | Analysis notebooks with technical details |
| [`./docs/presentation.html`](./docs/presentation.md) | Presentation slides for non-technical audience |

## Installation

### Requirements

- Python 3.11.3
- pyenv

### Setup

1. Navigate to a working directory of your choice, then clone the repository and enter it:

   ``` shell
   git clone https://github.com/kvn-dtrx/ds-eda-project_king-county-house-prices.git &&
       cd ds-eda-project_king-county-house-prices
   ```

2. Choose the right setup option based on your operating system:

   - `make unix`: macOS/Linux.
   - `make win`: Windows (PowerShell).

   If you prefer to run the commands manually yourself or want to inspect what a `make` target does first, use the `-n` flag for a dry run. This prints the commands without executing them:

   ``` shell
   make -n <target>
   ```

3. Activate the virtual environment:

   - On macOS/Linux, run:

     ```shell
     source .venv/bin/activate
     ```

   - On Windows (PowerShell), run:

     ``` powershell
     .\.venv\Scripts\Activate.ps1
     ```

## Colophon

**Authors:** [kvn-dtrx](https://github.com/kvn-dtrx)

**Template:** This repository was created from the [Neue Fische DS EDA Project Template](https://github.com/neuefische/ds-eda-project-template).

**License:** [MIT License](licence.txt)
