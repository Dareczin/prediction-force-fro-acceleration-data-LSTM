# prediction-force-fro-acceleration-data-LSTM
proposed LSTM model to compute force of a strike from imu data

Title: LSTM-Based Prediction of Force from Acceleration Data

Description:

This repository presents a Long Short-Term Memory (LSTM) recurrent neural network model for estimating the force of a strike using data from an Inertial Measurement Unit (IMU). The model is designed to analyze acceleration measurements and predict the corresponding force exerted during the strike.

Installation:

Clone the repository:

Bash
git clone https://github.com/Dareczin/prediction-force-fro-acceleration-data-LSTM.git

Set up the environment:

The specific instructions will depend on your chosen environment management tool (e.g., conda, virtualenv).
Generally, you'll need to create a virtual environment, activate it, and install the required dependencies using a package manager like pip.
Example (using conda):

Bash
conda create -n prediction-env python=3.8  # Adjust Python version as needed
source activate prediction-env
pip install -r requirements.txt

Data:

The repository should include instructions on how to acquire or prepare the IMU data that will be used to train and evaluate the LSTM model. This might involve:

Providing a link to a publicly available dataset.
Describing the format of the data (e.g., CSV, NumPy arrays) and its structure (columns, data types).
Outlining pre-processing steps, if necessary (e.g., normalization, feature engineering).
Model Architecture:

Training:

Prepare the data: Load the IMU data, pre-process it according to the provided instructions, and split it into training, validation, and testing sets.


Evaluation:

Evaluate the model: Load the best-performing model (e.g., from a checkpoint) and assess its performance on the testing set using relevant metrics (e.g., mean squared error, R-squared).
