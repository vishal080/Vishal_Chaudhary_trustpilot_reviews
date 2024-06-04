
# Customer Feedback Intent Classification

This repository contains the code and data for building an intent classification model for Novo's customer feedback. The goal is to develop a system that labels multiple intents in customer tickets to build an intelligent routing engine.



## Overview

This project uses Natural Language Processing (NLP) techniques to analyze and classify customer feedback. The main steps involve:

1. **Data Preprocessing:** Cleaning and preparing the data for analysis.
2. **Topic Modeling:** Using Latent Dirichlet Allocation (LDA) to identify topics in the feedback.
3. **Intent Classification:** Training a BERT-based model to classify feedback into predefined intents.

## Data

The dataset used in this project is Novo's customer feedback collected from TrustPilot. The data includes customer reviews along with intent labels.

## Installation

To run this project, you need to install the required packages. The primary libraries used are `transformers`, `torch`, `scikit-learn`, and `pandas`.

```bash
pip install pandas scikit-learn transformers[torch] accelerate torch
