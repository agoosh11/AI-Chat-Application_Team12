# AI-Chat-Application_Team12
Evaluation of a Knowledge-Based AI Chat Application


## **Project Overview**

### **Objective**

The objective of this project is to build an evaluation framework, and evaluate different aspects
of an AI-powered chat application capable of answering questions based on a knowledge base
comprised of unstructured data.


### **Key Features**

- **Chat Application**: 
  - Develop a chat interface that interacts with users and answers queries using a knowledge base.
  - The knowledge base consists of unstructured data from sources like webpages, PDFs, and other text-based documents.

- **Knowledge Base Handling**:
  - Implement data extraction and preprocessing techniques to ingest unstructured data for use in the chat application.
  - Create embeddings and store them in a vector store (pgvector).

## **Parameters Influencing Response Quality**

There are identified and evaluated parameters that can impact the quality of the AI chat application’s responses. Some of these parameters include:

- **Embedding Creation Parameters**:
  - **Text Preprocessing**: Tokenization, stopword removal, stemming/lemmatization.
  - **Embedding Type**: Word2Vec, GloVe, BERT, Sentence Transformers, etc.
  - **Context Window Size**: The amount of text context considered during embedding.
  - **Dimensionality Reduction**: Techniques like PCA, t-SNE to optimize embedding space.

- **Model Variables**:
  - **Model Type**: Transformer-based models, RNNs, GPT, etc.
  - **Hyperparameters**: Learning rate, batch size, number of epochs, etc.
  - **Response Generation Method**: Greedy search, beam search, top-k sampling, etc.

- **Knowledge Base Variables**:
  - **Data Source Quality**: Relevance and reliability of data sources.
  - **Data Volume**: Quantity of data used to train and query.
  - **Data Preprocessing**: Noise removal, redundancy check, data augmentation.

- **System Performance Parameters**:
  - **Latency**: Response time of the application.
  - **Scalability**: Ability to handle multiple queries simultaneously.
  - **Storage Requirements**: Efficient storage of embeddings and model parameters.

## **Evaluation Framework**

The evaluation framework focuses on assessing different techniques and their impact on response quality. The framework includes:

- **Embedding Evaluation**:
  - Evaluate different embedding methods and configurations for their effectiveness in representing the knowledge base.
  - **Metrics**: Cosine similarity, Euclidean distance between similar queries and responses, etc.

- **Model Evaluation**:
  - Compare models based on accuracy, relevance, and coherence of responses.
  - **Metrics**: BLEU score, ROUGE score, F1 score, etc.

- **Response Quality Evaluation**:
  - Human-in-the-loop testing to evaluate the relevance and accuracy of answers.
  - **Metrics**: User satisfaction score, qualitative feedback analysis, etc.

- **System Performance Evaluation**:
  - **Primary Measure**: Latency
  - **Extended Scope**: Throughput and resource utilization.


