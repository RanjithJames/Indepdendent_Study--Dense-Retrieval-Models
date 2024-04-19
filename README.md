# Project Repo: Multi-Dense Retrieval Models for MS MARCO Passage Retrieval

## Overview
This repository contains code for implementing multiple dense retrieval models aiming to achieve state-of-the-art (SOTA) results on the MS MARCO dataset for passage retrieval. The MS MARCO dataset is a large-scale dataset for machine reading comprehension and question answering, containing real-world queries sourced from Bing's search logs. The goal of this project is to develop retrieval models that can efficiently and accurately retrieve relevant passages from a large corpus given a user query.

## Models
The repository includes implementations of the following dense retrieval models:
- **Rank Zephyr**
- **Dense Passage Retrieval (DPR)**
- **Repllama**
- **Rankllama**
- **Mistral**

## Features
- **Efficient Passage Retrieval:** The models are designed to efficiently retrieve relevant passages from a large corpus, enabling fast search and retrieval for user queries.
- **Scalability:** The code is scalable and can handle large-scale datasets such as MS MARCO effectively.
- **State-of-the-Art Performance:** The models are trained and fine-tuned to achieve state-of-the-art performance on the MS MARCO dataset, measured in terms of retrieval accuracy and efficiency.

## Requirements
- Python 3.x
- PyTorch
- Hugging Face Transformers Library
- Sentence Transformers Library
- Other dependencies as specified in the individual model implementations
