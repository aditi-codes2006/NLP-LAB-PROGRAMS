# NLP Unit 1 Programs

This repository contains the practical programs covered in **Unit 1 of Natural Language Processing (NLP)**.

## Student Details

- **Name:** Aditi Mishra
- **Roll Number:** 2401331520016
- **Course:** B.Tech CSE (Artificial Intelligence)
- **Subject:** Natural Language Processing
- **Unit:** Unit 1

---

## Programs Included

| S. No. | Program | CO |
|--------|---------|----|
| 1 | Tokenization of Sentences and Words using NLTK and spaCy | CO1 |
| 2 | Stemming and Lemmatization on Sample Text | CO1 |
| 3 | Stop-word Removal from a Document | CO1 |
| 4 | Part-of-Speech (POS) Tagging of a Given Sentence | CO1 |
| 5 | Parsing and Chunking using RegEx and spaCy | CO1 |
| 6 | Named Entity Recognition (NER) using spaCy | CO1 |

---

## 1. Tokenization

Tokenization is the process of breaking text into smaller units called tokens. These tokens can be sentences or individual words.

This program performs:
- Sentence tokenization
- Word tokenization
- Tokenization using NLTK
- Tokenization using spaCy

**File:** `Program1_Tokenization.ipynb`

---

## 2. Stemming and Lemmatization

Stemming and lemmatization are text normalization techniques.

- **Stemming** reduces words to their root-like form.
- **Lemmatization** converts words into their meaningful dictionary form.

**File:** `Program2_Stemming_Lemmatization.ipynb`

---

## 3. Stop-word Removal

Stop-word removal removes frequently occurring words that may not provide significant information for certain NLP tasks.

Examples include:

`is`, `the`, `a`, `an`, `and`, `of`, `to`

The program demonstrates stop-word removal:
- Without NLTK
- Using NLTK

**File:** `Program3_Stopword_Removal.ipynb`

---

## 4. Part-of-Speech Tagging

Part-of-Speech (POS) tagging assigns a grammatical category to each word in a sentence.

Examples:

- Noun
- Verb
- Adjective
- Adverb
- Pronoun
- Preposition

This program uses NLTK for POS tagging.

**File:** `Program4_POS_Tagging.ipynb`

---

## 5. Parsing and Chunking

Parsing analyzes the grammatical structure of a sentence, while chunking groups related words into meaningful phrases.

This program demonstrates:
- Chunking using RegEx
- Dependency parsing using spaCy
- Noun phrase chunking using spaCy

**File:** `Program5_Parsing_Chunking.ipynb`

---

## 6. Named Entity Recognition

Named Entity Recognition (NER) identifies important entities in text, such as:

- PERSON – Person names
- ORG – Organizations
- GPE – Countries, cities, states, etc.
- LOC – Locations
- DATE – Dates
- MONEY – Monetary values

This program uses the spaCy English language model for NER.

**File:** `Program6_Named_Entity_Recognition.ipynb`

---

## Technologies Used

- Python
- NLTK
- spaCy
- Regular Expressions (RegEx)
- Google Colab
- GitHub

---

## Installation

Install the required libraries using:

```bash
pip install nltk spacy
