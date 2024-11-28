# Improving Story Points Estimation Using Ensemble Machine Learning

This project aims to develop and implement a machine learning-based model for story point estimation using the ensemble stacking technique, combining RoBERTa and BiLSTM models.

## Table of Contents

- [Setup Environment](#setup-environment)
- [Preprocessing](#preprocessing)
- [RoBERTa Model](#roberta-model)
- [BiLSTM Model](#bilstm-model)
- [Stacking](#stacking)
- [Usage](#usage)

## Setup Environment

1. Install Anaconda
2. Create the environment:
    ```sh
    conda env create -f ml_sp_env.yml
    ```
3. Execute additional requirements in [info.ipynb](info.ipynb)

## Preprocessing

Run the preprocessing steps in [preprocess.ipynb](preprocess.ipynb) to prepare the datasets for training and evaluation.

## RoBERTa Model

The RoBERTa model is implemented in [roberta-base.ipynb](roberta-base.ipynb). Follow the notebook to train and evaluate the RoBERTa model.

## BiLSTM Model

The BiLSTM model is implemented in [bilstm-base.ipynb](bilstm-base.ipynb). Follow the notebook to train and evaluate the BiLSTM model.

## Stacking

The stacking approach is implemented in [stacking.ipynb](stacking.ipynb). This notebook combines the predictions from the RoBERTa and BiLSTM models to improve the overall performance.

## Usage

1. Preprocess the data using [preprocess.ipynb](preprocess.ipynb).
2. Train and evaluate the RoBERTa model using [roberta-base.ipynb](roberta-base.ipynb).
3. Train and evaluate the BiLSTM model using [bilstm-base.ipynb](bilstm-base.ipynb).
4. Perform stacking using [stacking.ipynb](stacking.ipynb).
