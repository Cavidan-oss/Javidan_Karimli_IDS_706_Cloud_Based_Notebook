[![CI Pipeline](https://github.com/Cavidan-oss/Javidan_Karimli_IDS_706_Cloud_Based_Notebook/actions/workflows/main.yaml/badge.svg)](https://github.com/Cavidan-oss/Javidan_Karimli_IDS_706_Cloud_Based_Notebook/actions/workflows/main.yaml)

# Cloud Host Notebook with the analysis of Olympics Data

This project explores cloud-hosted data analysis using Jupyter notebooks. The goal is to perform data processing, analysis, and verification of datasets in cloud. This projected aimed to make analysis of the olympic games. For reading more about the .ipynb file in [Google Colab](https://colab.research.google.com/drive/1rBMpix_ahFG6xEcpPpAkGfdfrdVo6DkP?usp=sharing)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Setup](#setup)
3. [Dependencies](#dependencies)
4. [Notebook Structure](#notebook-structure)
5. [Usage](#usage)
6. [Testing](#testing)


## Project Overview
This project analyzes and manipulates data using Python and Jupyter notebooks, providing insights and verifying results. You can interact with the notebook to understand data transformations and explore different stages of analysis.

## Setup
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Cavidan-oss/Javidan_Karimli_IDS_706_Cloud_Based_Notebook
   cd https://github.com/Cavidan-oss/Javidan_Karimli_IDS_706_Cloud_Based_Notebook
   ```


2. Install the dependencies:
   ```bash
    make install
   ```

## Dependencies
This project requires the following packages (list might vary based on your setup):

- Jupyter Notebook
- nbval
- pytest
- pandas
- numpy
- matplotlib 

Make sure to have these packages installed either by using `requirements.txt` or by manually installing them with:
```bash
make install
```

## Notebook Structure
The notebook `Javidan_Karimli_IDS_706_CloudHostedDataAnalysis.ipynb` is organized into multiple sections:

1. **Data Loading**: Loads and preprocesses the dataset.
2. **Data Transformation and Cleaning**: Includes all transformation steps applied to the dataset.
3. **Data Analysis**: Analyzes the processed data and extracts insights.
4. **Testing**: Contains code for validating the integrity and correctness of the analysis.

## Usage
1. **Go to the Google Colab and upload there or open Jupyter Notebook using this**:
   ```bash
   jupyter notebook
   ```

2. **Run the notebook**:
   In Jupyter, open `Javidan_Karimli_IDS_706_CloudHostedDataAnalysis.ipynb` and run the cells in sequence.

3. **Tag Specific Cells for Testing**:
   If you want to test specific cells, assign a tag like `test-me` in the cell toolbar.

## Testing
We use `pytest-nbval` to run tests on the notebook. You can run the tests using the following command:

```bash
make test_file
```
This will execute only the cells tagged with `test-me`, ensuring that specific sections of your notebook are verified.


## Linting and Formatting

```bash
make lint
```

```bash
make format
```
