# Multiple_Sclerosis_XGBoost_ANN-1.0


**Multiple Sclerosis Dataset using Artificial Neural Networks (ANN)**
This repository contains a dataset for Multiple Sclerosis (MS) and an implementation of an Artificial Neural Network (ANN) model for classification.

Dataset
The dataset used in this project is specifically curated for Multiple Sclerosis. It consists of a collection of features extracted from medical images and clinical data of MS patients. The dataset is split into two files:

ms_data.csv: This file contains the features extracted from the medical images and clinical data. Each row represents a sample, and each column represents a specific feature.
ms_labels.csv: This file contains the corresponding labels for each sample in the dataset. Each row represents a sample, and there is a single column for the label.
Please note that due to privacy concerns, the actual medical images are not included in this dataset. Only the extracted features are provided.

Artificial Neural Network (ANN) Model
The ANN model is implemented using Python and the Keras library. It consists of multiple layers of interconnected neurons that can learn patterns and relationships in the input data. The ANN model is trained on the provided Multiple Sclerosis dataset to classify samples into different classes.

The implementation of the ANN model is provided in the ms_classification.py file. This file contains the code for loading the dataset, preprocessing the data, creating the ANN model, training the model, and evaluating its performance.

Requirements
To run the code and train the ANN model, you need to have the following dependencies installed:

Python 3.x
Keras library
NumPy
Pandas
Matplotlib
You can install these dependencies using pip:


pip install keras numpy pandas matplotlib
Usage
Clone or download this repository to your local machine.
Place the ms_data.csv and ms_labels.csv files in the same directory as the ms_classification.py file.
Open a terminal or command prompt and navigate to the directory containing the files.
Run the following command to train and evaluate the ANN model:

python ms_classification.py
The script will load the dataset, preprocess the data, create and train the ANN model, and output the evaluation metrics.
Contributing
If you want to contribute to this project, you can fork this repository, make your changes, and submit a pull request. Your contributions are greatly appreciated.



