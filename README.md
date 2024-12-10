# Aerospace_Chatbot
Repository of Aerospace Chatbot for Technical Documents Retrieval and Querying
# CS_7650_Project: Developing an NLP-Based Chatbot for Efficient Retrieval of Aerospace
Technical Documents

This repository contains a project developed for CS 7650 NLP, focusing on the implementation of a Retrieval-Augmented Generation (RAG) model for efficiently retrieving and summarizing information from technical documents.

## **Features**
- Preprocessing large datasets from PDF documents.
- Extracting, tokenizing, and cleaning text using NLP tools like SpaCy and NLTK.
- Generating text embeddings using OpenAI's `text-embedding-ada-002`.
- Deduplicating and filtering data with Bloom Filters.
- Clustering and analyzing topics using TF-IDF and NMF.
- Visualizing similarity scores using heatmaps.

---

## **Installation**
To set up the environment and run the project, follow these steps:

### **Prerequisites**
- Python 3.8 or above
- [pip](https://pip.pypa.io/en/stable/installation/)
- Install the following libraries:
  ```bash
  pip install pdfminer.six PyPDF2 openai python-dotenv bloom-filter2 streamlit
  pip install matplotlib seaborn nltk spacy tensorflow-hub
  pip install transformers scikit-learn wordcloud

-If using preprocessed data please closely watch for cells that are indicated to skip if loading data from folder. 
-The drive location is set up to local machine and must be adjusted for each user. 
