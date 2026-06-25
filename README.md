# BIT4133 - Natural Language Processing with Deep Learning

## Project: SMS Spam Detection and Text Classification System

**Student:** Faith Wanja Gichure  
**Admission Number:** BSCCS/2024/31978  
**Unit:** BIT4133 - Natural Language Processing with Deep Learning  

---

## Project Description
An SMS Spam Detection system built using Python, NLTK, and Scikit-learn.
Classifies SMS messages as spam or ham using TF-IDF vectorization 
and a Multinomial Naive Bayes classifier.

## Results Achieved
- Dataset: UCI SMS Spam Collection - 5,572 messages
- True Negatives: 964 | True Positives: 118
- False Positives: 2 | False Negatives: 31

### Creative Consolidation Project: Word2Vec + Neural Language Model
A custom project combining Week 6 (Word Embeddings) and Week 7 (Neural Language Models) by feeding Word2Vec-trained embeddings into an LSTM network's Embedding layer as pre-trained weights demonstrating transfer learning, the same principle behind BERT and GPT.

---

## Repository Contents

| File | Description |
|------|-------------|
| NLP_Weekly_Practicals.ipynb | Weekly practicals - Weeks 1 to 5 |
| NLP_Practical.ipynb | Week 1 Tokenization Assignment |
| Extra_Work_NLP.ipynb | Extra work - Stemming, Lemmatization, Parsing, Word Frequency Charts |
| NLP_Project_Practical.ipynb | Full project pipeline Main SMS Spam Classifier |
| Creative_Consolidation_Project_Week 6 & 7.ipynb | Word2Vec embeddings transferred into LSTM model  |
| Week 6 to 7_Practicals.ipynb | Word Embeddings-Word2Vec, FastText, GloVe, CBOW vs Skip-Gram, PCA visualisation, Neural Language Models-TensorFlow neural networks, LSTM next-word prediction, RNN vs LSTM comparison |
| Week 6 & 7_Extra_Work.ipynb | Embedding comparisons, word analogies and RNN vs LSTM  |
| Week_8_Practicals.ipynb | Transformer models - sentiment analysis using DistilBERT, text generation using GPT-2 |
| Week_8_Extra_Work.ipynb | Extra work Week 8 Five Transformer pipelines, BERT vs GPT-2 comparison, Transformer spam detection |
| BIT4133_NLP_LOGBOOK.docx | Full practical logbook - Weeks 1 to 8 with screenshots and reflections |
| NLP_EXTRAWORK.docx | Extra work documentation - Weeks 1 to 8 with screenshots and reflections |

---

## Weekly Topics Covered

| Week | Topic |
|------|-------|
| 1 | Introduction to NLP, Tokenization, Stop Word Removal |
| 2 | N-grams, POS Tagging, Language Prediction |
| 3 | Hidden Markov Models, Sequence Labeling, Named Entity Recognition |
| 4 | Syntactic and Semantic Analysis, spaCy Dependency Parsing, Semantic Similarity |
| 5 | Complete NLP Pipeline Integration, Student Academic Assistant Chatbot |
| 6 | Word Embeddings, Word2Vec, CBOW vs Skip-Gram, FastText, GloVe |
| 7 | Neural Language Models, ANNs, LSTM Next-Word Prediction |
| 8 | Transformer Models, Attention Mechanisms, BERT, GPT-2 |

---

## Extra Work - Independent Study Beyond Classwork

- Stemming using Porter and Snowball stemmers vs Lemmatization comparison
- Word frequency analysis with bar and pie chart visualisations
- Syntax, Semantics, and Pragmatics demonstrations
- Syntactic parsing and semantic similarity scoring
- Word2Vec vs FastText vs GloVe comparison including FastText sub-word advantage for unseen words
- Word analogy reasoning using GloVe (King − Man + Woman = Queen)
- Sentiment analysis rebuilt using averaged Word2Vec embeddings instead of TF-IDF
- SimpleRNN vs LSTM hands-on training comparison
- Five Transformer pipelines. sentiment analysis, NER, extractive summarization, fill-mask, zero-shot classification
- BERT vs GPT-2 encoder vs decoder architecture comparison
- Zero-shot Transformer spam detection compared against Project 1 Naive Bayes baseline

---

## Technologies Used
Python • NLTK • spaCy • Gensim • TensorFlow • Scikit-learn • Pandas • NumPy • Matplotlib • Hugging Face Transformers • Google Colab
