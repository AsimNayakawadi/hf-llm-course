# Hugging Face LLM Course — Notes, Practice, and Implementations

This repository documents my learning journey through the **Hugging Face LLM Course**, where I studied core concepts behind modern Large Language Models (LLMs), the Hugging Face ecosystem, tokenization, transformer workflows, and fine-tuning fundamentals.

It includes my **notes, hands-on practice, notebooks, and concept breakdowns** from the course modules I have completed so far.

## About This Repository

I created this repository to:

- document my progress while learning LLMs in a structured way,
- strengthen my practical understanding through notebooks and experiments,
- build a public portfolio of my work in **NLP, transformers, and model fine-tuning**.

This repo reflects both **conceptual learning** and **practical implementation** using Hugging Face tools.

## Course Progress

- [x] **Chapter 1** — Introduction to LLMs and Transformer Basics
- [x] **Chapter 2** — Using Hugging Face Transformers
- [x] **Chapter 3** — Fine-tuning Language Models and Understanding Learning Curves

## Key Concepts Covered

### LLM and Transformer Fundamentals
- What Large Language Models are
- Transformer architecture basics
- How tokenized text is represented before entering a model

### Tokenization
- `input_ids`
- `attention_mask`
- padding
- truncation
- subword tokenization concepts
- differences between tokenizers and model inputs

### Hugging Face Ecosystem
- `pipeline()`
- `AutoTokenizer`
- `AutoModel`
- pretrained model workflows
- loading and testing transformer models

### Dataset and Preprocessing Workflow
- dataset loading
- mapping and preprocessing
- batching
- data collators
- preparing text for training

### Fine-tuning and Evaluation
- `Trainer`
- `TrainingArguments`
- training loop basics
- understanding training loss vs validation loss
- identifying overfitting using learning curves

## Repository Structure

```bash
hf-llm-course/
├── Transformer Model/
├── Understanding Learning Curves/
└── README.md
