IGMC Implementation Notebook
This notebook implements Inductive Graph-based Matrix Completion (IGMC), a technique designed for matrix completion tasks, such as collaborative filtering in recommendation systems, using graph neural networks.

Overview
This notebook includes:

Environment Setup:
Installation and configuration of dependencies for PyTorch Geometric and related libraries.
Cloning the IGMC repository for data preprocessing and model implementation.
Data Preparation:
Downloading and preprocessing datasets using scripts provided in the IGMC repository.
Model Training and Evaluation:
Building and fine-tuning the IGMC model on the prepared datasets.
Evaluating the model's performance using standard metrics.
Prerequisites
Python 3.7 or later.
A CUDA-compatible GPU is recommended for faster training.
Ensure the following Python packages are installed:
torch
torch-geometric
torch-scatter
torch-sparse
torch-cluster
Additional utilities like aiohttp, numpy, and scipy.
Notebook Structure
Environment Setup:

Installs required libraries.
Uninstalls pre-existing incompatible versions of PyTorch Geometric dependencies.
Clones the IGMC GitHub repository.
Data Preprocessing:

Leverages the cloned repository for downloading and preprocessing datasets.
Model Implementation:

Loads the IGMC model from the repository.
Configures hyperparameters for training.
Training and Evaluation:

Trains the IGMC model on the prepared dataset.
Evaluates performance on a test set using metrics like RMSE or MAE.
How to Use
Clone this repository and open the notebook in Jupyter or Google Colab.
Follow the cells step-by-step to install dependencies, prepare data, and train the model.
Adjust hyperparameters in the training cells as needed to experiment with the model's performance.
References
Original IGMC repository: GitHub - IGMC
[Medium blog](https://medium.com/stanford-cs224w/graph-neural-network-based-movie-recommender-system-5876b9686df3)
