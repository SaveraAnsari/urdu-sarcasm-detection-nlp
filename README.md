# Urdu Sarcasm Detection using NLP

This project implements binary sarcasm detection for Urdu text as part of the DS5007 Natural Language Processing assignment.

## Models
- TF-IDF with traditional machine learning classifiers
- Two-branch BiLSTM with Urdu fastText embeddings
- Twitter XLM-RoBERTa fine-tuning
- Ensemble learning

## Experiments
- Exploratory Data Analysis
- Urdu text preprocessing
- Emoji and linguistic feature analysis
- Ablation studies
- Error analysis

## Evaluation
Models are evaluated using accuracy, precision, recall, Macro-F1, and confusion matrices.

## Reproducibility
1. Open the notebook in Google Colab.
2. Install the dependencies listed in `requirements.txt`.
3. Mount Google Drive and configure the dataset path.
4. Run the notebook cells in order.
5. Review the generated evaluation results.

Random seeds and experiment configurations are recorded in the notebook.

**Note:** The dataset and trained model files must be made available separately if they are not included in this repository.
