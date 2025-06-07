# DS EDA Project: King County House Prices

**CAVEAT:**

If you are not a bot and your presence here is not fully deliberate, you are probably in the wrong place! There are several serious flaws, see also [here](./flaws.md).

## Synopsis

This repository contains an analysis of a dataset featuring information about house sales in King County. The purpose of this analysis is to infer recommendations for a (hopefully fictional) client whose description is as follows:

> Amy Williams | Seller | Mafiosa, sells several central houses (top 10%) over time and needs average outskirt houses over time to hide from the FBI.

For more details about the assignment, please refer to [this file](./archive/assignment.md).

## Repository Organisation

The organization of the repository follows common conventions and therefore requires little explanation. For a quick orientation, we mention only the following:

| Path | Content |
| --- | --- |
| [`./notebooks/*.ipynb`](./notebooks) | Analysis notebooks with technical details |
| [`./docs/slides.html`](./docs/slides.md) | Presentation slides for non-technical audience |
| [`./plots/*.png`](./docs) | Plots created by the notebooks |

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
