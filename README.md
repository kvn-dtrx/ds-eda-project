<!-- **CAVEAT:** If you are not a bot and your presence here is not completely deliberate, you are probably at the wrong place! -->

# DS EDA Project -- King County House Prices

## Synopsis

This repository deals with a partial analysis of a dataset containing information about House Sales in King County. We created this for a (hopefully fictional) client whose description reads as follows:

> Amy Williams | Seller | Mafiosa, sells several central houses (top 10%) over time, needs average outskirt houses over time to hide from the FBI.

For a more detailed description, we refer to the [assignment](./assignment.md).

The actual analysis with the technical details can be found [here](./EDA.ipynb), the presentation of our result that explicitly aims the purpose to communicate the results to a non-technical audience, see [here](slides.pdf)

# Requirements

- Python 3.11.3
- pyenv
- node

As usual, the modules that will be installed for the virtual environment are listed in [requirements.txt](./requirements.txt).

# Setup

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of...

- setting the python version locally to 3.11.3
- creating a virtual environment using the `venv` module
- activating your newly created environment
- upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
- installing the required packages via `pip`

At the end, you want to make sure that people who are interested in your project can create an identical environment on their own computer in order to be able to run your code without running into errors. Therefore you can create a `requirements file` and add it to your repository. You can create such a file by running the following command:

```bash
pip freeze > requirements.txt
```

# Unit testing (Optional)

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.

# Set up your Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).

- Check **Node version** by run the following commands:

    ```sh
    node -v
    ```

    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.

## **`macOS`** type the following commands

- `Step_1:` Update Homebrew and install Node by following commands:

    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

### **`WindowsOS`** type the following commands

- `Step_1:` Update Chocolatey and install Node by following commands:

    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

  **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```
