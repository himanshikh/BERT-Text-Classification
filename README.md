# BERT Fine-Tuning for Text Classification

This project demonstrates how to fine-tune **BERT (Bidirectional Encoder 
Representations from Transformers)** for a **binary text classification** 
task using **PyTorch**.

---

## Project Overview
The goal is to classify sentences into predefined labels (e.g., 
positive/negative sentiment) using transfer learning with a pretrained 
BERT model (`bert-base-uncased`).

---

## Steps Implemented
1. Data preprocessing from `train_10k.txt` and `val_1k.txt`
2. Tokenization using HuggingFace’s BERT tokenizer
3. Sequence padding and attention mask creation
4. Model setup and fine-tuning using `BertForSequenceClassification`
5. Evaluation and visualization of results

---

## Tech Stack
- Python 
- PyTorch
- Transformers (HuggingFace)
- scikit-learn
- Keras
- Matplotlib

---

## Example Results
| Metric | Value |
|:--|:--|
| Training Accuracy | ~XX% |
| Validation Accuracy | ~XX% |

*(You can update these values after running your notebook.)*

---

## How to Run
```bash
# Clone this repository
git clone https://github.com/<your-username>/BERT-Text-Classification.git
cd BERT-Text-Classification

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebook/Assignment1_AI_ML.ipynb

