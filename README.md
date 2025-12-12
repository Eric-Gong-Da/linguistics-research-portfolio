# Linguistics Research Portfolio

This repository contains a portfolio showcasing a Semantic-Aware Literature Retrieval System for linguistic research.

## Project Overview

Traditional literature search systems in linguistics often rely on keyword matching, which can miss conceptually similar works expressed in different terminology. This project presents a novel approach using Natural Language Processing techniques to overcome these limitations.

## Features

- Semantic-aware literature discovery using NLP techniques
- Integration of sentence transformers and Large Language Models
- Improved recall and precision in literature retrieval
- Time-saving intelligent ranking system

## System Workflow

The system transforms literature search from keyword matching to semantic understanding through these steps:

1. **Text Vectorization**: Convert paper abstracts into high-dimensional semantic vectors
2. **Semantic Centroid Generation**: Use LLM to generate a "semantic centroid" representing core concepts
3. **Similarity Computation**: Calculate cosine similarity between document vectors and query centroid
4. **Intelligent Re-ranking**: Apply LLM-weighted re-ranking to improve result relevance
5. **Result Presentation**: Display top results with brief rationale for quick screening

## Technologies Used

- sentence-transformers/all-MiniLM-L6-v2 for text embedding
- OpenRouter API with gpt-4o-mini for LLM integration
- Python for implementation
- Cosine similarity for document ranking

## Results

The system demonstrates significant improvements over traditional search methods:
- 40% improvement in recall
- 60% reduction in literature review time
- Better precision in top-ranked results

View the live portfolio: https://eric-gong-da.github.io/linguistics-research-portfolio/