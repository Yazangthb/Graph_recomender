# IGMC Implementation Notebook

This repository contains a notebook for implementing **Inductive Graph-based Matrix Completion (IGMC)**, a method designed for matrix completion tasks such as collaborative filtering in recommendation systems using graph neural networks.

---

## **Overview**

This notebook provides the following:

- **Environment Setup**:  
  - Installation and configuration of dependencies for PyTorch Geometric and related libraries.  
  - Cloning the IGMC repository for data preprocessing and model implementation.  

- **Data Preparation**:  
  - Downloading and preprocessing datasets using scripts from the IGMC repository.  

- **Model Training and Evaluation**:  
  - Building and fine-tuning the IGMC model on the prepared datasets.  
  - Evaluating model performance using standard metrics.  

---

## **Prerequisites**

- **Python**: Version 3.7 or later.  
- **GPU**: A CUDA-compatible GPU is recommended for faster training.  

### **Required Python Packages**
- Core libraries: `torch`, `torch-geometric`, `torch-scatter`, `torch-sparse`, `torch-cluster`
- Additional utilities: `aiohttp`, `numpy`, `scipy`

---

## **Notebook Structure**

### **1. Environment Setup**
- Installs the required libraries.  
- Removes incompatible pre-existing versions of PyTorch Geometric dependencies.  
- Clones the IGMC GitHub repository.  

### **2. Data Preprocessing**
- Uses scripts from the IGMC repository to download and preprocess datasets.  

### **3. Model Implementation**
- Loads the IGMC model from the repository.  
- Configures training hyperparameters.  

### **4. Training and Evaluation**
- Trains the IGMC model on the prepared dataset.  
- Evaluates its performance on a test set using metrics such as RMSE or MAE.  

---

## **How to Use**

1. Clone this repository and open the notebook in **Jupyter Notebook** or **Google Colab**.  
2. Follow the cells step-by-step to:
   - Install dependencies.
   - Prepare datasets.
   - Train the model.  
3. Adjust the training hyperparameters as needed to experiment with the model's performance.

---

## **References**

- **Original IGMC Repository**: [GitHub - IGMC](https://github.com)
