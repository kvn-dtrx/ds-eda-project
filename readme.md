# DS EDA Project: King County House Prices

## Synopsis

This repository contains an analysis of a dataset featuring information about house sales in King County. The dataset is retrieved from the neue fische database. It is very similar to <https://www.kaggle.com/datasets/harlfoxem/housesalesprediction> but contains possibly contaminations deliberatively injected by the instructors for exercise purposes.

The purpose of this analysis is to infer recommendations for a (hopefully fictional) client whose description reads follows:

> Amy Williams | Seller | Mafiosa, sells several central houses (top 10%) over time and needs average outskirt houses over time to hide from the FBI.

For more details about the assignment, please refer to [this file](./archive/assignment.md).

We introduce statistical measures for centrality, exceptionality and privacy in order to derive recommendations for the client supported by quantifiable evidence.

## Repository Organisation

The organisation of the repository follows common conventions and therefore requires little explanation. Let us only mention that our analysis notebooks (with technical details) are subordinated to [`notebooks/`](./notebooks/) and that our presentation slides for a non-technical audience can be found in [`docs/`](./docs/).

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

**Template:** This repository was instantiated from the [Neue Fische DS EDA Project Template](https://github.com/neuefische/ds-eda-project-template).

**License:** [MIT License](license.txt)
