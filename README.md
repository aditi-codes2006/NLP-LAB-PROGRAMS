# Natural Language Processing (NLP) – Practical Programs

This repository contains the practical implementations covered in the Natural Language Processing (NLP) course. It includes fundamental NLP techniques, text vectorization, text analytics, deep learning models, and transformer-based applications.

## Student Details

- **Name:** Aditi Mishra
- **Roll Number:** 2401331520016
- **Course:** B.Tech CSE (Artificial Intelligence)
- **Subject:** Natural Language Processing
- **Repository:** NLP Practical Programs

---

## Programs Included

### Unit 1 – NLP Fundamentals (CO1)

| S. No. | Program | CO |
|:---:|---|:---:|
| 1 | Tokenization of Sentences and Words using NLTK and spaCy | CO1 |
| 2 | Stemming and Lemmatization on Sample Text | CO1 |
| 3 | Stop-word Removal from a Document | CO1 |
| 4 | Part-of-Speech (POS) Tagging of a Given Sentence | CO1 |
| 5 | Parsing and Chunking using RegEx and spaCy | CO1 |
| 6 | Named Entity Recognition (NER) using spaCy | CO1 |

### Unit 2 – Text Vectorization, Similarity and Text Analytics (CO2)

| S. No. | Program | CO |
|:---:|---|:---:|
| 7 | Coreference Resolution using neuralcoref (or Similar Libraries) | CO2 |
| 8 | Bag-of-Words (BoW) Vectorization and Representation | CO2 |
| 9 | TF-IDF Implementation and Comparison with BoW | CO2 |
| 10 | N-Gram Model (Uni-gram, Bi-gram, Tri-gram) Generation from Corpus | CO2 |
| 11 | Cosine Similarity Computation between Text Documents | CO2 |
| 12 | Word2Vec Word Embeddings using Gensim on a Custom Corpus | CO2 |
| 13 | GloVe Embeddings Loading and Vector Representation | CO2 |
| 14 | Text Similarity using Word Mover's Distance (WMD) | CO2 |
| 15 | Text Classification using Naïve Bayes/SVM with TF-IDF | CO2 |
| 16 | Sentiment Analysis using TextBlob and VADER | CO2 |
| 17 | Topic Modeling using Latent Dirichlet Allocation (LDA) | CO2 |
| 18 | Topic Modeling using Latent Semantic Analysis (LSA) | CO2 |
| 19 | Opinion Mining on Product/Service Reviews Dataset | CO2 |
| 20 | Information Extraction (IE) from Structured/Unstructured Documents | CO2 |
| 21 | Information Retrieval System with Ranking using TF-IDF | CO2 |
| 22 | Sequence Classification using RNN/LSTM (Keras/TensorFlow) | CO2 |
| 23 | Implementing Attention Mechanism (Basic Custom Model) | CO2 |

### Unit 3 – Advanced NLP and Transformer-Based Applications (CO3)

| S. No. | Program | CO |
|:---:|---|:---:|
| 24 | Fine-Tuning BERT for Text Classification using Hugging Face | CO3 |
| 25 | Sentence Embeddings using BERT and GPT-2 | CO3 |
| 26 | Text Generation using GPT-2 on a Custom Dataset | CO3 |
| 27 | Named Entity Recognition using Transformers (BERT) | CO3 |
| 28 | Machine Translation using MarianMT or T5 (Hugging Face) | CO3 |
| 29 | Text Summarization using BART or T5 | CO3 |
| 30 | Chatbot Development using Pre-trained Transformer (DialoGPT/ChatGPT-Style) | CO3 |
| 31 | Automatic Document Classification and Separation using ML | CO3 |
| 32 | Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection | CO3 |

---

## Technologies and Libraries Used

- **Programming Language:** Python
- **NLP Libraries:** NLTK, spaCy, TextBlob, Gensim
- **Machine Learning:** Scikit-learn
- **Deep Learning:** TensorFlow, Keras
- **Transformer Models:** Hugging Face Transformers, BERT, GPT-2, T5, BART, DialoGPT, MarianMT
- **Text Processing:** Regular Expressions (RegEx)
- **Development Environment:** Google Colab, Jupyter Notebook
- **Version Control:** Git and GitHub

---

## Installation

Install the commonly used libraries using:

```bash
pip install nltk spacy gensim scikit-learn
pip install textblob vaderSentiment
pip install tensorflow transformers datasets
pip install torch
```

Download the spaCy English language model:

```bash
python -m spacy download en_core_web_sm
```

Download the required NLTK datasets:

```python
import nltk

nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('averaged_perceptron_tagger')
```

**Note:** Some practicals may require additional libraries, datasets, pre-trained embeddings, or model-specific resources depending on their implementation.

---

## How to Run

1. Clone or download this repository.
2. Open the required `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Install the necessary dependencies.
4. Download the required datasets or pre-trained models, if applicable.
5. Execute the notebook cells sequentially to run the practical.

---

## Learning Outcomes

Through these practical implementations, the repository covers:

- Fundamental NLP preprocessing techniques.
- Text normalization, tokenization and linguistic analysis.
- Text vectorization and word embeddings.
- Text similarity and information retrieval.
- Text classification, sentiment analysis and opinion mining.
- Topic modeling and information extraction.
- Deep learning techniques such as RNN, LSTM and Attention.
- Transformer-based NLP applications using BERT, GPT-2 and other pre-trained models.
- Document classification and sequence modeling.

---

## Conclusion

This repository demonstrates the practical application of Natural Language Processing concepts, starting from basic text preprocessing and progressing towards advanced deep learning and transformer-based NLP applications. It serves as a collection of implementations and a learning resource for understanding different NLP techniques.
