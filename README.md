# Named Entity Recognition (NER) with RNNs and BERT

## Project Overview
This project focuses on building and comparing two Named Entity Recognition (NER) systems using the CoNLL-03 dataset. The goal is to detect entities such as Persons (PER), Organizations (ORG), Locations (LOC), and Miscellaneous (MISC) using the IOB tagging scheme.

## Models
The project implements two distinct approaches for token classification:
1. **RNN-based Model:** A custom architecture using an embedding layer, LSTM layer, and a feed-forward classification head.
2. **Fine-tuned BERT Tagger:** A pre-trained BERT model fine-tuned for token-level classification.

## Dataset
The project uses a processed version of the **CoNLL-03** dataset (`conll03-iob-pos.json.gz`), which includes:
- **Training set:** 14,041 samples
- **Validation set:** 3,250 samples
- **Test set:** 3,453 samples

## Setup & Requirements
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt