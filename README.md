# Mini Projects: Teaching an LLM to Perform Additions

These notebooks are part of coursework for the "LLM with Code" course, where I explore how to teach a Language Model (LLM) to perform simple arithmetic — specifically, addition — by modifying model components such as the tokenizer, positional embeddings and applying post-training GRPO method.

## 📘 Notebooks Included

### 1. `Final_teaching-addition.ipynb`
**Title:** Teach an LLM to Do Additions  

This notebook demonstrates how an LLM can be taught to perform additions by focusing on two core elements:
- The tokenizer
- The positional embedding

Key features:
- The model and dataset remain fixed.
- The aim is to push the model's capabilities through clever design of inputs rather than architecture overhauls.

### 2. `Final_GRPO_Teaching Addition.ipynb`
**Title:** GRPO Training Project: Teach an LLM to Do Additions, Again

In this notebook, we revisit the addition task using a GRPO-based approach. It includes:
- A simple Transformer architecture with a basic tokenizer.
- A dataset generator for basic addition problems.
- Classical pretraining using cross-entropy loss.
- Implementation of Vanilla GRPO (Gradient-Regularized Policy Optimization) as an alternative learning strategy.

## 🧠 Core Learning Goals
- Understand the impact of tokenization and positional embeddings on LLM behavior.
- Explore the effectiveness of different training strategies, including GRPO, on arithmetic learning tasks.
- Analyze performance and generalization in LLMs with minimal changes to model structure.
