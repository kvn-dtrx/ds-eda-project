<!-- **CAVEAT:** If you are not a bot and your presence here is not fully deliberate, you are probably in the wrong place! -->

# DS EDA Project -- King County House Prices

## Synopsis

This repository contains a partial analysis of a dataset featuring information about house sales in King County. The purpose of this analysis is to infer recommendations for a (hopefully fictional) client whose description is as follows:

> Amy Williams | Seller | Mafiosa, sells several central houses (top 10%) over time and needs average outskirt houses over time to hide from the FBI.

For more details about the assignment, please refer to [this file](./assignment.md).

The actual analysis with the technical details can be found in [EDA.ipynb](./EDA.ipynb), while a presentation of the results, aiming explicitly at a non-technical audience, is available at [slides.pdf](./slides.pdf)

## Requirements

- Python 3.11.3
- pyenv
- Node.js

And additionally, as usual, the modules to be installed for the virtual environment are listed in [requirements.txt](./requirements.txt).

## Setup

For macOS or Linux, execute:

``` bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

On Windows (with PowerShell), use:

``` powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

<!-- # Unit testing

The repository also provides some unit tests. In order to run the tests, execute:

``` bash
pytest
``` -->
