# Readme

This readme provides instructions for installing, loading data, and training the model.

## Dataset

1. Download the dataset from [Kaggle](https://www.kaggle.com/competitions/lyft-motion-prediction-autonomous-vehicles).
2. Place the downloaded dataset at the same filepaths as the notebooks.

## Installation

To install the required files, follow these steps:

1. Activate your virtual environment (venv).
2. Run the following command in your venv:

   ```
   pip install -r requirements.txt
   ```

   This command will install the necessary dependencies.

3. Next, run the following command to install l5kit version 1.5.0 without its dependencies:

   ```
   pip install l5kit==1.5.0 --no-deps
   ```

   This will install the specific version of l5kit needed for the project.

## Running the Notebooks

To run the Python notebooks, follow these steps:

1. Open the notebook named `motion_prediction.ipynb` to execute the baselines using Resnet-50.
2. Alternatively, open the notebook named `motion_prediction_maml` to execute MAML-enhanced Resnet-50.

These notebooks contain the code for training the respective models.