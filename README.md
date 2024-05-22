# SURD: Synergistic-Unique-Redundant Decomposition of causality

_A Python repository for decomposing causality into its synergistic, unique, and redundant components for complex and chaotic systems._

## Introduction
SURD (Synergistic-Unique-Redundant Decomposition) is a causal inference method that measures the increments of information gained about future events based on the
available information from past observations. It further decomposes the causal interactions into redundant, unique, and synergistic contributions according to their nature. The formulation is non-intrusive and requires only pairs of past and future events, facilitating its application in both computational and experimental
investigations. SURD also identifies the amount of causality that remains unaccounted for due to unobserved variables. The approach can be used to detect
causal relationships in systems with multiple variables, dependencies at different time lags, and instantaneous links.

<img width="1209" alt="Screenshot 2024-02-21 at 5 22 41 PM" src="https://github.mit.edu/storage/user/27189/files/77ed0e78-e988-406c-b977-0e927661b168">

## Features

- **Quantification of causality**: SURD measures the increments of information gained about future events from past observations.

- **Decomposition of causality**: It decomposes causal interactions into redundant, unique, and synergistic contributions.

- **Quantification of information leak**: SURD quantifies the amount of causality that remains unaddressed due to unobserved variables.

- **Non-intrusive formulation**: The method is designed to be non-intrusive, requiring only pairs of past and future events for analysis. This facilitates its application across both computational and experimental studies.

- **Probabilistic framework**: SURD provides a probabilistic measure of causality, emphasizing transitional probabilities between states.

- **Dependence on data availability**: The accuracy of the method is contingent on the availability of sufficient data, as it involves estimating probability distributions in high-dimensional spaces.

## Getting started

After cloning the repository, you can set up the environment needed to run the scripts successfully by following the instructions below. Depending on whether you are using `pip` or `conda`, choose the appropriate method to install the required packages.

If you are using `pip`, you can install all the necessary dependencies by running the following command in your terminal:
```sh
pip install -r requirements.txt
```

For those using `conda`, you can create an environment with all the required packages by running:
```sh
conda env create -f environment.yml
```
This command creates a new conda environment and installs the packages as specified in the `environment.yml` file. After installing the dependencies, make sure to activate the newly created conda environment with:
```sh
conda activate surd
```

## Tutorials
SURD has been applied in a large collection of scenarios that have proven challenging for causal inference and demonstrate its application in analyzing the energy cascade in isotropic turbulence. For examples, consult the documentation or see the Jupyter notebooks in the examples folder.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
