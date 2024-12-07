# Email Thread Summarization

This repository contains the implementation of an email thread summarization tool that leverages transformer-based models (e.g., T5) to generate concise, informative summaries of lengthy email conversations. By preserving the context and intent of the original messages, the tool improves information accessibility and reduces cognitive load for users.

## Features
- Hierarchical summarization using a two-layer T5 model.
- Preprocessing pipeline for cleaning and structuring raw email data.
- Fine-tuned T5 model trained on the *Email Thread Summary* dataset.
- Evaluation metrics, including ROUGE, G-Eval, and SummEval, for assessing summary quality.
- Multilingual translation of generated summaries for global accessibility.
