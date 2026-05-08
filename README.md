# Natural Language Processing - CSCB817

A collection of NLP algorithm implementations and exercises covering fundamental concepts in natural language processing.

## Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| NLP Library | NLTK |

## Topics Covered

| Topic | Description | Key Concepts |
|-------|-------------|--------------|
| **Language Modelling** | Bigram probability model | N-grams, conditional probability, smoothing |
| **Text Classification** | Naive Bayes classifier | Bayesian inference, document classification |
| **Spelling Correction** | Autocorrect implementation | Edit distance, candidate generation |
| **Min Edit Distance** | Levenshtein distance | Dynamic programming, string similarity |
| **Latent Semantic Analysis** | LSA implementation | Dimensionality reduction, semantic similarity |

## Prerequisites

- [Python](https://www.python.org/) (3.6 or higher)
- pip (Python package manager)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nikolaykolibarov/natural-language-processing-CSCB817.git
   cd natural-language-processing-CSCB817
   ```

2. **Install dependencies**
   ```bash
   pip install nltk
   ```

3. **Download NLTK data** (if needed)
   ```python
   import nltk
   nltk.download('punkt')
   ```

## Project Structure

```
natural-language-processing-CSCB817/
│
├── language-modelling/
│   ├── bigram.py              # Bigram language model
│   └── sentences.txt          # Training corpus
│
├── text-classification/
│   ├── classifier.py          # Naive Bayes classifier
│   ├── train/                 # Training data
│   └── test/                  # Test data
│
├── spelling-correction/
│   ├── spelling-correction.py # Spelling corrector
│   └── corpus.txt             # Dictionary corpus
│
├── min-edit-distance/
│   └── levenshtein.py         # Levenshtein distance algorithm
│
└── latent-semantic-analysis/
    ├── lsa.py                 # LSA implementation
    └── data/                  # LSA datasets
```

## Running the Examples

### Language Modelling
```bash
cd language-modelling
python bigram.py
```

### Text Classification
```bash
cd text-classification
python classifier.py
```

### Spelling Correction
```bash
cd spelling-correction
python spelling-correction.py
```

### Min Edit Distance
```bash
cd min-edit-distance
python levenshtein.py
```

### Latent Semantic Analysis
```bash
cd latent-semantic-analysis
python lsa.py
```

## Algorithms Overview

### Bigram Language Model
Calculates the probability of a sentence using bigram (two-word) sequences with add-one smoothing.

### Naive Bayes Classifier
Implements text classification using Bayesian probability to categorize documents.

### Levenshtein Distance
Computes the minimum number of single-character edits (insertions, deletions, substitutions) needed to transform one string into another.

### Spelling Correction
Uses edit distance and corpus frequency to suggest corrections for misspelled words.

### Latent Semantic Analysis
Applies singular value decomposition (SVD) to discover latent semantic relationships between terms and documents.

## License

MIT

---

> **Note:** This project contains solutions for the "CSCB817 - Natural Language Processing" course at New Bulgarian University. It is intended for educational and demonstration purposes only.
