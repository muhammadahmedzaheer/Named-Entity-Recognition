# Named Entity Recognition with BERT and RoBERTa

## Project Overview

This project involves building a Named Entity Recognition (NER) model using BERT with and without Conditional Random Fields (CRF) and RoBERTa. The goal is to identify and classify entities within a text, such as names, dates, and other predefined categories. The project leverages the power of BERT for token classification and enhances it with CRF for sequence labeling.

## Dataset

The dataset used in this project is a labeled NER dataset in CSV format, containing words, part-of-speech (POS) tags, and NER tags. The dataset is split into training and testing sets for model training and evaluation.

## Project Structure

The project is structured as follows:

- `notebooks`: Contains Jupyter notebooks for exploratory data analysis and model training.
- `requirements`: Dependencies needed to run this project.

## Installation

To run this project, ensure you have Python 3.7 or higher installed. You can install the required packages using the following command:
```
pip install -r requirements.txt
```

## Usage
1. Data Preprocessing: First, ensure your dataset is loaded into the notebook.
2. Model Training: The model training script initializes the BERT model with CRF and trains it on the preprocessed dataset.
3. Evaluation: After training, the model is evaluated on the test set to measure its performance.
4. Results: The project includes scripts for visualizing the results, such as the distribution of named entity tags and the confusion matrix.

## Results
The model's performance is evaluated using metrics like accuracy and F1 score. The results demonstrate the effectiveness of combining BERT with CRF for NER tasks. This project highlights the capabilities of using advanced models like BERT and CRF for named entity recognition. The model can be further improved by fine-tuning and experimenting with different hyperparameters.

## Acknowledgements
Hugging Face for providing the transformer models and tokenizers.
