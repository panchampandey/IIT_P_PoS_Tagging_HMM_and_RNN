## IIT_P_PoS_Tagging_HMM_and_RNN🧠 PoS Tagging using HMM & RNN
### Institution: IIT Patna
#### Author: Kumar Pancham Prasar (Roll No: 2303RES23)

### 📌 Project Overview
#### This project focuses on Part-of-Speech (PoS) tagging using two different models:

A Hidden Markov Model (HMM) with probabilistic estimations (Part 1)

A Recurrent Neural Network (RNN) for sequence modeling (Part 2)

The assignment explores sequence tagging using a labeled corpus in the Brown Corpus format, where each word is tagged with its corresponding PoS label.

#### 📂 Files Included
File Name	Description
CS663_Assignment_part_1(MODEL_CODE).ipynb	Implementation of HMM with transition, emission, and start probabilities for PoS tagging
CS663_Assignment_part_2.ipynb	Implementation of PoS tagging using RNN and evaluation with 5-fold cross-validation

### 🔍 Part 1: HMM-based PoS Tagging
✅ Dataset Parsing and Tokenization

✅ Computation of:

Start Probabilities

Transition Probabilities

Emission Probabilities

✅ Manual HMM construction using defaultdict and Laplace smoothing

✅ Evaluation using accuracy and tag distribution

### 🔍 Part 2: RNN-based PoS Tagging
✅ Dataset Preparation using word/tag pairs

✅ HMM from nltk.tag.hmm.HiddenMarkovModelTrainer (as base)

✅ 5-Fold Cross-Validation on the dataset

✅ Performance Metrics:

Accuracy

Precision

Recall

F1 Score

✅ Visualization using Confusion Matrix (matplotlib, seaborn)

### 🛠️ Tech Stack
Python

NLTK

NumPy

Scikit-learn

Matplotlib / Seaborn
