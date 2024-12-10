# Banking Customer Intent Classification Project
This project leverages the BANKING77 dataset for intent classification of banking customers. Two models are explored: DistilBERT, a lightweight pre-trained language model, and FastText, a traditional machine learning model, to compare their performance on this task.

# Project Structure

```plaintext
├── DistilBERT.ipynb   # Training code for the DistilBERT model
├── FastText.ipynb     # Training code for the FastText model
├── train.csv          # Training dataset
├── test.csv           # Testing dataset
└── README.md          # Project documentation
```

# Model and Task Overview
## DistilBERT
Key Features: Lightweight transformer-based pre-trained model with contextual understanding.

Use Case: Effective for complex and long text classification tasks.

### FastText
Key Features: Lightweight, fast, and resource-efficient traditional machine learning model.

Use Case: Suitable for short text or resource-constrained environments.

# Usage Instructions
Install the required dependencies:

```
pip install transformers fasttext pandas scikit-learn
```
Run DistilBERT.ipynb or FastText.ipynb.
