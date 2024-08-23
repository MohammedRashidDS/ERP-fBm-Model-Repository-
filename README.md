# ERP-fBm-Model-Repository-

## fbm_predictor.ipynb

The fbm_predictor.ipynb notebook contains the Python code created for the Extended Research Project. It contains the analysis, modelling, and predictions.

## Models

**Models/:** This directory contains pre-trained models to make the Hurst exponent predictions. The file 'model.keras' is the model trained on Fractional Brownian Motion trajectories with varying generalised diffusion coefficients. The file 'baseline_model.keras' is the baseline model trained on Fractional Brownian Motion trajectories with a fixed generalised diffusion coefficient.

## Datasets

**Experimental Dataset/:** This directory contains the endosome trajectory 'traj_rab5.csv''dataset analysed in the Extended Research Project.

**Train-Test Datassts/:** This directory contains the Fractional Brownian Motion trajectories used to train our models. The dataset 'trajectories.csv' was used to train the model whose trajectories have varying generalised diffusion coefficients, and the dataset 'original_trajectories.csv' was used to train the baseline model where the generalised diffusion coefficient is fixed for the trajectories.

**Validation Datasets:/** This directory contains the validation datasets simulating different trajectory scenarios used to validate and test the models
