# eos4tcc-model-validation

# Model Validation and Evaluation for hERG Channel Blockade Prediction

This repository contains code and data used for model validation and evaluation in the context of hERG channel blockade prediction. The provided models and datasets aim to assess the performance and reliability of predictive models in identifying small molecule-induced blockade of the hERG ion channel.

## Folder Structure

- **data:** Contains various datasets used for model training, validation, and evaluation, including reference libraries, predicted probabilities, and curated molecule data.
- **models:** Stores information and artifacts related to the predictive models used for hERG channel blockade prediction i.e eos4tcc-model.
- **notebooks:** Includes Jupyter notebook for model bias evaluation. The data folder within this directory contains specific datasets used in this notebook.
- **src:** Contains Python scripts and modules, including `smiles_processing.py`, which provides functions for processing SMILES strings.

## Usage

1. Clone the repository to your local machine using `git clone`.
2. Navigate to the appropriate directory containing the notebook(00_model_bias.ipynb).
3. Install the required dependencies listed in `requirements.txt` using `pip install -r requirements.txt`.
4. Execute the provided Jupyter notebook to perform model bias evaluation.
5. Follow the instructions within each notebook to load datasets, run experiments, and analyze results.

## Datasets

- **reference_library.csv:** Contains a reference library of molecules used for model training and validation.
- **module_predictions.csv:** Predictions obtained from the Ersilia Model Hub on the reference library dataset.
- **molecule_data.csv:** Dataset of molecules used for model evaluation, including standardized SMILES representations and associated properties.
- **curated_predictions.csv:** Curated predictions with associated scores, aleatoric, and episodic uncertainties.

## Licenses

The repository includes appropriate licenses for the code, datasets, and any third-party dependencies used in the project.

## Contributing

Contributions to the project are welcome. Please refer to the contribution guidelines provided in the README.md file for more information.




