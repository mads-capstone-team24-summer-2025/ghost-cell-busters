# Scripts for Dataset Download and Management

This directory contains scripts for downloading and managing datasets used in the project. The scripts handle downloading, extracting, and organizing datasets from various sources, ensuring they are ready for analysis.

## Script Overview

Each script in this directory is designed to:

- Download a specific dataset from its source.
- Extract the dataset contents to the appropriate location.
- Delete the original compressed files after extraction to save space.

## Usage

- Run the desired script to download and prepare a dataset (If your terminal or command line is in the ghost-cell-busters folder please run the commands below, but if you have navigated to the scripts folder, you can run the commands without the `scripts/` prefix), Please try to maintain the following order for running the scripts:

    ```bash
    python scripts/GSE176078_asset.py
    ```

    ```bash
    python scripts/GSE161529_asset.py
    ```

    ```bash
    python scripts/GSE180286_asset.py
    ```

    ```bash
    python scripts/Gencode_asset.py
    ```

    ```bash
    python scripts/Interactions_asset.py
    ```

    ```bash
    python scripts/Clinical_trial_asset.py
    ```