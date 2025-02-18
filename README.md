# **Fine-Tuning Language Models for NLP Tasks**  
## *Advanced Natural Language Processing Course*  
**Academic Year:** 2024/2025  

---

## Project Objectives  

### Enhancing Model Adaptation  
- Fine-tune a **pre-trained BERT model** for sentiment analysis on the **Arabic Sentiment Tweets** dataset.  
- Evaluate model performance using metrics from **TorchMetrics**.  

### Implementing Multi-Head Differential Attention  
- Develop a **custom multi-head attention** mechanism leveraging **differential attention** principles.  
- Integrate this approach seamlessly into the fine-tuned BERT model.  

### Investigating Hybrid Attention Strategies  
- Replace **25%-50%** of the encoder and/or decoder layers’ multi-head attention with the differential attention mechanism.  
- Train multiple configurations and compare their effectiveness.  

---

## Dataset  
**Dataset Name:** Arabic Sentiment Tweets Dataset  
- **Task:** Sentiment Classification  
- **Source:** [Mendeley Data](https://data.mendeley.com/datasets/57zpx667y9/2)  

---

## Pre-trained Model  
**Base Model:** BERT  
- **Version Used:** [BERT-Base-ArabertV2](https://huggingface.co/aubmindlab/bert-base-arabertv2)  

---

## Setup Guide  

### Requirements  
Ensure you have the following dependencies installed:  

- Python 3.x  
- PyTorch (version 1.10+ recommended)  
- Hugging Face **Transformers** library  
- **TorchMetrics** for evaluation  
- **Datasets** library for handling data sources  

---
