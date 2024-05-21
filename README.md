# Accelerating Cleantech Advancements through NLP-Powered Text Mining and Knowledge Extraction


Welcome to our Project! This repository contains the data and code used for analyzing various aspects of clean technology media, patent documents, and related evaluations.

## Table of Contents
- [Project Structure](#project-structure)
- [Data](#data)
  - [Sentence](#sentence)
  - [Word](#word)
    - [Media](#media)
    - [Patent](#patent)
    - [Original](#original)
  - [CSV Files](#csv-files)
- [Notebooks](#notebooks)
- [Getting Started](#getting-started)

## Project Structure

The project is organized as follows:


## Data

### Sentence
This directory is reserved for sentence embedded data extracted from various sources.

### Word
This directory contains trained word-level model, categorized into two main sources:
- **Media**: 
  - `Text`: Text model from media sources.
  - `Title`: Titles from media sources.
- **Patent**:
  - `Text`: Text model from patent documents.
  - `Title`: Titles from patent documents.

### Original
The `Original` directory holds the raw datasets in various formats:
- `bq-results-20240124-055833-1706076079048.json`: Raw JSON results from a query.
- `cleantech_media_dataset_v2_2024-02-23.csv`: Version 2 of the clean technology media dataset.
- `cleantech_rag_evaluation_data_2024-02-23.csv`: Evaluation data for clean technology research and guidance.

### lang
Contains all the language extracted google patents.

## Archive
Contains older file versions.

## Notebooks

- `CleanTech_Stage1.ipynb`: Notebook for initial data processing and analysis.
- `CleanTech_Stage1_EDA_Visualization.ipynb`: Exploratory Data Analysis (EDA) and visualization for Stage 1.
- `CleanTech_Stage2.ipynb`: Notebook for advanced data processing and analysis.
- `CleanTech_Stage2_EDA_Visualization.ipynb`: EDA and visualization for Stage 2.

If the GitHub preview doesn't work, you can view the notebooks using [nbviewer](https://nbviewer.org/):
- [CleanTech_Stage1.ipynb](https://nbviewer.org/github/MarStorman/NLP_CleanTech/blob/main/CleanTech_Stage1.ipynb)
- [CleanTech_Stage1_EDA_Visualization.ipynb](https://nbviewer.org/github/MarStorman/NLP_CleanTech/blob/main/CleanTech_Stage1_EDA_Visualization.ipynb)
- [CleanTech_Stage2.ipynb](https://nbviewer.org/github/MarStorman/NLP_CleanTech/blob/task2/CleanTech_Stage2.ipynb)
- [CleanTech_Stage2_EDA_Visualization.ipynb](https://nbviewer.org/github/MarStorman/NLP_CleanTech/blob/task2/CleanTech_Stage2_EDA_Visualization.ipynb)

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MarStorman/NLP_CleanTech.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd NLP_CleanTech
    ```
4. **Open the Jupyter notebooks** to explore and run the analyses:
    ```bash
    jupyter notebook
    ```