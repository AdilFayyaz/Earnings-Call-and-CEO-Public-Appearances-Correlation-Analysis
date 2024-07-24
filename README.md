# Earnings-Call-and-CEO-Public-Appearances-Correlation-Analysis

## Overview

This repository contains a notebook that explores the relationship between earnings call data and CEO public appearances, including conferences, interviews, and other events. The analysis aims to identify and evaluate correlations between earnings call metrics and CEO statements using a Retrieval-Augmented Generation (RAG) pipeline and semantic embeddings.

## Features

- **Data Preparation**: Load, clean, and preprocess earnings call and CEO appearance data.
- **RAG Pipeline**: Retrieve and process relevant transcripts to generate responses based on predefined prompts.
- **Embedding Analysis**: Transform responses into BERT embeddings and compare these with scaled financial data distributions.
- **KL Divergence Calculation**: Measure the difference between embedding distributions and financial data to assess representation effectiveness.
- **Visualization**: Plot histograms to visually compare the distributions of embeddings and financial data.

## Getting Started

### Prerequisites

Ensure you have the following Python packages installed:

- `pandas`
- `langchain_community`
- `langchain_openai`
- `openai`
- `transformers`
- `torch`
- `scipy`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:

```bash
pip install pandas langchain_community langchain_openai openai transformers torch scipy matplotlib seaborn
