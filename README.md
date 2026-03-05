# NLP Analysis of Customer Reviews
### Course: Project: Data Analysis (DLBDSEDA02)
**Author:** Rei Zaimi | **Matriculation Nr:** 10220314

---

## Overview
This project applies NLP techniques to analyze 23,486 women's clothing reviews. The goal is to extract the most frequently discussed topics from unstructured text data, simulating a real-world use case of analyzing citizen complaints for a municipality.

---

## Dataset
- **Source:** Women's E-Commerce Clothing Reviews (`raw_reviews.csv`)
- **Size:** 23,486 reviews
- **Key columns:** Review Text, Rating, Age, Division Name, Department Name

---

## Project Structure
```
├── Data Analysis.ipynb   # Main notebook with full analysis
├── raw_reviews.csv       # Dataset
└── README.md             # Project documentation
```

---

## NLP Pipeline
1. **Text Cleaning** — lowercase, remove punctuation, URLs, numbers
2. **Tokenization** — split text into individual words
3. **Stopword Removal** — remove common uninformative words
4. **Lemmatization** — reduce words to base form

---

## Techniques Used
| Step | Technique | Library |
|------|-----------|---------|
| Vectorization | Bag of Words (BoW) | scikit-learn |
| Vectorization | TF-IDF | scikit-learn |
| Topic Extraction | LDA | scikit-learn |
| Topic Extraction | NMF | scikit-learn |

---

## How to Run
```bash
# 1. Clone the repository
git clone https://github.com/ReiZaimi/data_analysis_report_ReiZaimi

# 2. Open the notebook
jupyter notebook "Data Analysis.ipynb"
```

---

## Dependencies
Install all required packages with:
```bash
pip install pandas nltk scikit-learn jupyter
```
