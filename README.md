# QIDS

Quantum-Classical Encoding Analysis for Intrusion Detection
This project explores different quantum embedding techniques and their effects on classification tasks for intrusion detection. The notebook implements various quantum encoding methods using PennyLane and compares their performance.

## Features:

- Implements four quantum embedding techniques:
  - Amplitude embedding
  - Angle embedding
  - IQP embedding
  - QAOA embedding
- Uses a hybrid quantum-classical model with:
  - Quantum circuit for feature encoding and processing
  - Classical neural network for post-processing
- Compares model performance using metrics such as accuracy, sensitivity, precision, F1 score, and recall

## Requirements:

- PennyLane
- TensorFlow
- XGBoost
- Scikit-learn
- Pandas
- NumPy

## Usage:

- Mount your Google Drive to access the dataset.
- Load and preprocess the data from the CSV file.
- Select the top features using XGBoost feature importance.
- Choose an embedding technique by uncommenting the relevant code block.
- Run the training loop to train the hybrid quantum-classical model.
- Evaluate the model performance using the provided metrics.

## References

If you are interested in the detailed methodology and results of this quantum-classical hybrid intrusion detection approach, please refer to the original research paper:

<a id="1">[1]</a>
Adam Kadi, Aymene Selamnia, Zakaria Abou El Houda, et al.
An In-Depth Comparative Study of Quantum-Classical Encoding Methods for Network Intrusion Detection
TechRxiv. December 11, 2024.
DOI: 10.36227/techrxiv.173388214.48550690/v1
