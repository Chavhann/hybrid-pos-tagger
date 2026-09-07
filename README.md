# Hybrid POS Tagging System

## 📌 Overview

This project implements a Hybrid Part-of-Speech (POS) Tagging System for Natural Language Processing.

The system identifies the grammatical category of each word in a sentence, such as noun, verb, adjective, adverb, pronoun, and determiner.

It combines linguistic rule-based tagging with statistical sequence prediction and provides a comparison between different tagging approaches.

## 🎯 Objective

The main objective of this project is to improve POS tagging by combining:

- Rule-based linguistic patterns
- Context-aware statistical tagging
- Hybrid decision-making
- Model output comparison

## 💡 Innovation

The key innovation of this project is the **hybrid tagging mechanism**.

Instead of depending on a single POS tagging technique, the system combines linguistic rules and contextual prediction to select more appropriate POS tags.

This approach allows the system to handle both straightforward grammatical patterns and context-dependent words.

## ⚙️ System Workflow

User Input
    ↓
Sentence Tokenization
    ↓
Rule-Based POS Tagging
    ↓
Statistical/CRF POS Tagging
    ↓
Hybrid Decision Layer
    ↓
Comparison of Results
    ↓
Final POS Tags

## 🧠 POS Tagging Example

Input:

"She is running fast."

Output:

| Word | POS Tag |
|------|---------|
| She | PRP |
| is | VBZ |
| running | VBG |
| fast | RB |

## 🛠️ Technologies Used

- Python
- NLTK
- Machine Learning
- CRF / Statistical Sequence Tagging
- Flask (for API integration, if enabled)
- HTML, CSS and JavaScript (for the frontend, if enabled)

## ✨ Features

- Sentence-based POS tagging
- Rule-based tagging
- Statistical sequence tagging
- Hybrid tagging
- Model comparison
- Interactive user interface
- REST API support (if enabled)

## 🚀 Future Improvements

- Integrate Transformer/BERT-based POS tagging
- Add domain-specific POS models
- Improve hybrid confidence scoring
- Add accuracy and performance visualization
- Support multilingual POS tagging

## 👨‍💻 Project

This project demonstrates the evolution of POS tagging from traditional linguistic rules toward modern context-aware NLP systems.
