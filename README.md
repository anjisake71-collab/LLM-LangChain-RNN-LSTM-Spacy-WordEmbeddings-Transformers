# 🧠 NLP, RNN, LSTM, Transformers & LLM Projects

Welcome to my **Natural Language Processing (NLP) and Generative AI Projects** repository!

This repository is a practical collection of notebooks and interactive projects covering the journey from **fundamental NLP techniques and word representations to RNNs, LSTMs, Seq2Seq models, Transformers, Large Language Models (LLMs), and LangChain**.

The projects focus on understanding concepts through hands-on implementation, experimentation, and practical examples using Python and modern AI libraries.

---

## 📁 Project Overview

### 1. Bag of Words (BoW)

**File:** `1.Bow_vectors.ipynb`

- **Objective:** Understand how text can be converted into numerical vectors using the Bag of Words representation.
- **Techniques:** CountVectorizer, vocabulary creation, document-term matrices.
- **Libraries:** `Scikit-learn`
- **Highlights:**
  - Demonstrates basic Bag of Words representation.
  - Shows the effect of synonyms on vocabulary.
  - Explores morphological variations.
  - Demonstrates vocabulary growth with larger text collections.
  - Highlights limitations of simple word-count representations.

---

### 2. Word Embeddings with Word2Vec

**File:** `WordEmbeddings_1.ipynb`

- **Objective:** Explore how words can be represented as dense numerical vectors and how semantic relationships can be captured.
- **Techniques:** Word2Vec, word similarity, word analogies, vector relationships.
- **Libraries:** `Gensim`
- **Highlights:**
  - Explore individual word vectors.
  - Find similar words.
  - Perform word analogies.
  - Calculate word similarity.
  - Find odd words out.
  - Explore semantic relationships between groups of words.
  - Investigate word neighborhoods.

---

### 3. NLP Text Preprocessing with spaCy

**File:** `Spacy_Exercises.ipynb`

- **Objective:** Learn essential NLP preprocessing and linguistic analysis techniques using spaCy.
- **Techniques:** Tokenization, normalization, stop-word removal, lemmatization, POS tagging, NER, dependency parsing.
- **Libraries:** `spaCy`
- **Highlights:**
  - Tokenization
  - Lowercasing
  - Punctuation removal
  - Stop-word removal
  - Lemmatization
  - Number filtering
  - Part-of-Speech tagging
  - Named Entity Recognition
  - Sentence segmentation
  - Dependency parsing
  - Complete text preprocessing pipeline

---

### 4. Byte Pair Encoding (BPE)

**File:** `bpe_animation.html`

- **Objective:** Understand subword tokenization through an interactive visualization.
- **Techniques:** Character-level tokenization, pair-frequency calculation, iterative merging, vocabulary construction.
- **Highlights:**
  - Starts with individual characters.
  - Counts adjacent token pairs.
  - Merges frequent pairs.
  - Builds a subword vocabulary step by step.
  - Demonstrates how words can be represented using reusable subword units.

The animation demonstrates the process using examples such as `low`, `lower`, and `lowest`. :contentReference[oaicite:3]{index=3}

---

### 5. SentencePiece Tokenization

**File:** `sentencepiece_animation.html`

- **Objective:** Understand language-independent subword tokenization using SentencePiece.
- **Techniques:** Character-level processing, subword merging, space markers, vocabulary learning.
- **Highlights:**
  - Processes raw text directly.
  - Represents spaces using the `▁` marker.
  - Demonstrates vocabulary construction.
  - Shows how subword units are learned.
  - Illustrates language-agnostic tokenization.

The project specifically demonstrates how SentencePiece treats spaces as part of the tokenization process. :contentReference[oaicite:4]{index=4}

---

### 6. WordPiece Tokenization

**File:** `wordpiece_animation.html`

- **Objective:** Understand WordPiece tokenization and how subword vocabularies are constructed.
- **Techniques:** Likelihood-based merging, continuation tokens, subword vocabulary.
- **Highlights:**
  - Demonstrates vocabulary initialization.
  - Shows iterative token merging.
  - Explains continuation tokens using the `##` prefix.
  - Demonstrates root and continuation subwords.
  - Provides an interactive visualization of the tokenization process.

The animation demonstrates examples such as `playing → play + ##ing`, `player → play + ##er`, and `played → play + ##ed`. :contentReference[oaicite:5]{index=5}

---

## 🔄 RNN & LSTM Projects

### 7. First RNN Project – IMDB & BBC News

**File:** `FirstProject_RNN (1).ipynb`

- **Objective:** Build Recurrent Neural Networks for text classification.
- **Techniques:** RNN, Embedding, sequence padding, sentiment classification, text preprocessing.
- **Datasets:** IMDB Movie Reviews and BBC News.
- **Libraries:** `TensorFlow`, `Keras`, `Pandas`, `NumPy`, `NLTK`
- **Highlights:**
  - IMDB sentiment classification.
  - Text tokenization and sequence padding.
  - SimpleRNN model construction.
  - Custom review predictions.
  - Experimentation with real-world text classification.

---

### 8. Understanding RNN vs LSTM

**File:** `Differentiating_LSTM_and_RNN (1).ipynb`

- **Objective:** Compare Simple RNN and LSTM models for handling sequential information.
- **Techniques:** SimpleRNN, LSTM, Embedding, sequence modeling, long-range dependencies.
- **Libraries:** `TensorFlow`, `Keras`, `NumPy`
- **Highlights:**
  - Compares RNN and LSTM architectures.
  - Uses synthetic movie-review style datasets.
  - Experiments with long-range dependencies.
  - Explores sentiment classification.
  - Tests model behavior with increasingly challenging sequences.

---

### 9. LSTM Movie Sentiment Project

**File:** `LSTM_Movie_started_terribly.ipynb`

- **Objective:** Use an LSTM network to learn sentiment patterns from movie-related sentences.
- **Techniques:** Text tokenization, sequence padding, Embedding, LSTM, classification.
- **Libraries:** `TensorFlow`, `Keras`, `NumPy`
- **Highlights:**
  - Movie sentiment examples.
  - Text-to-sequence conversion.
  - Embedding representation.
  - LSTM-based sequence learning.
  - Sentiment prediction.

---

### 10. LSTM Seq2Seq – Shakespeare Text Generation

**File:** `LSTM_Project_Seq2Seq (1).ipynb`

- **Objective:** Generate new text in a Shakespeare-like style using an LSTM language model.
- **Techniques:** Character-level tokenization, LSTM, sequence modeling, text generation.
- **Dataset:** Tiny Shakespeare.
- **Libraries:** `TensorFlow`, `TensorFlow Datasets`, `Keras`, `NumPy`, `Matplotlib`
- **Highlights:**
  - Character-level text modeling.
  - LSTM-based sequence generation.
  - Shakespeare text generation.
  - Experimentation with deeper model architectures.
  - Dropout and training callbacks.
  - Generates new text based on learned patterns.

> The model generates new text based on patterns learned from the training corpus rather than retrieving the original Shakespeare text.

---

## 🤗 Transformers & Modern NLP

### 11. Transformers Exercises

**File:** `Transformers_Exercises.ipynb`

- **Objective:** Explore practical NLP and generative AI tasks using Hugging Face Transformers.
- **Techniques:** Transformer pipelines, masked language modeling, text generation, translation, summarization, question answering, speech processing, classification.
- **Libraries:** `Transformers`, `PyTorch`
- **Highlights:**
  - Masked Language Modeling
  - Text Generation
  - Text Translation
  - Text Summarization
  - Question Answering
  - Text-to-Speech
  - Speech-to-Text
  - Text Classification
  - Direct model and tokenizer usage

---

## 🤖 LLM & Generative AI Projects

### 12. LLM Inference Parameters

**File:** `LLM_Inference_Parameters (1).ipynb`

- **Objective:** Understand how inference parameters influence LLM output.
- **Techniques:** Temperature, Top-p, Maximum Tokens, Frequency Penalty.
- **Libraries:** `OpenAI`
- **Highlights:**
  - Experiment with temperature.
  - Explore Top-p / nucleus sampling.
  - Understand token limits.
  - Experiment with frequency penalties.
  - Compare controlled and more diverse generations.

---

### 13. LangChain Components

**File:** `Langchain_Components (1).ipynb`

- **Objective:** Explore the core building blocks of LangChain and learn how LLM applications can be structured into reusable components.
- **Techniques:** Prompt Templates, Chat Models, Output Parsers, Memory, Chains.
- **Libraries:** `LangChain`, `OpenAI`
- **Highlights:**
  - PromptTemplate
  - ChatPromptTemplate
  - Few-shot prompting
  - Chat models
  - Output parsing
  - Conversation memory
  - Summary memory
  - Token-based memory
  - LLM chains
  - Sequential chains
  - Conversation chains
  - Multiple LLM providers

---



## 🛠️ Technologies Used

### Programming

- Python

### NLP & Machine Learning

- Scikit-learn
- NLTK
- spaCy
- Gensim

### Deep Learning

- TensorFlow
- Keras
- PyTorch

### Transformers & LLMs

- Hugging Face Transformers
- OpenAI
- LangChain

### Data & Visualization

- NumPy
- Pandas
- Matplotlib

### Development

- Jupyter Notebook
- Google Colab
- HTML / CSS / JavaScript

---

🚀 Getting Started
1. Clone the repository
git clone https://github.com/anjsake71-collab/LLM-LangChain-RNN-LSTM-Spacy-WordEmbeddings-Transformers.git
cd LLM-LangChain-RNN-LSTM-Spacy-WordEmbeddings-Transformers

2. Create a virtual environment
python -m venv .venv
3. Activate the environment

Windows:

.venv\Scripts\activate

4. Install the required libraries
pip install numpy pandas matplotlib scikit-learn nltk spacy gensim tensorflow torch transformers langchain langchain-openai openai jupyter

 5. Start Jupyter Notebook
jupyter notebook

🤝 Contributing

Contributions and suggestions are welcome.

If you would like to improve an example, add a new NLP project, or introduce another LLM technique:

Fork the repository.
Create a new branch.
Add your project or improvement.
Commit your changes.
Open a Pull Request.
👨‍💻 Author

Anjisake71

GitHub: @anjsake71-collab

⭐ If you find this repository useful, consider giving it a star!

7. 

