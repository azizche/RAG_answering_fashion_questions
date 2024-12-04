# Fashion RAG System

This project implements a Retrieval-Augmented Generation (RAG) system for the fashion domain. It enhances the quality of responses to user queries by combining information retrieval with generative modeling using OpenAI's GPT-based model.

## Overview

The system works as follows:
1. **Query Embedding**: Calculates the embedding of the user query.
2. **Similarity Calculation**: Computes the similarity between the query embedding and the embeddings of information in the dataset.
3. **Candidate Selection**: Selects the top 3 most relevant entries from the dataset.
4. **Prompt Enrichment**: Enriches the GPT model's input prompt with the retrieved entries to generate contextually accurate answers.

## Features

- **Efficient Similarity Matching**: Leverages embedding-based similarity to identify relevant information.
- **Prompt Enhancement**: Integrates top candidates into the GPT model's prompt to improve answer quality.
- **Domain-Specific**: Tailored for the fashion industry.

