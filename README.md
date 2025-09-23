# FigureYa-Actions

Workflows and scripts from the [FigureYa](https://github.com/ying-ge/FigureYa) project that can be run directly on GitHub Actions, without requiring local data dependencies.

## Overview

This repository contains automation workflows and utility scripts designed to streamline usage and continuous integration for FigureYa modules. All included folders and scripts are intended for reproducible, cloud-native execution using GitHub Actions.

- **Automated Sync:**  
  All modules listed in `all_included.txt` from the main FigureYa repo are automatically synchronized here using GitHub Actions. This ensures the latest visualization modules and related scripts are always available.

- **No Local Data Required:**  
  All workflows are designed to be self-contained and require no manual data or code dependencies outside this repository.

## How to Use

1. Browse the available folders and scripts in this repository.
2. Refer to the included [workflows](.github/workflows/) for automation examples.
3. Check `all_included.txt` in the main FigureYa repository for the list of maintained modules.

## Academic Citation

If you use this code in your work or research, we kindly request that you cite our publication:

> Xiaofan Lu, et al. (2025). FigureYa: A Standardized Visualization Framework for Enhancing Biomedical Data Interpretation and Research Efficiency. *iMetaMed*. https://doi.org/10.1002/imm3.70005

---

For questions, suggestions, or contributions, please open an issue or pull request.
