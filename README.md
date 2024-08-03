# 🦙 Meta Llama 3.1 (8B, 70B, and 405B) on Vertex AI with 🤗 Hugging Face

This repository contains some recipes for deploying and fine-tuning Meta Llama 3.1 models within Google Cloud on Vertex AI with 🤗 Hugging Face.

[Meta Llama 3.1](https://huggingface.co/collections/meta-llama/llama-31-669fc079a0c406a149a5738f) is the latest is the open LLM from Meta, a follow up iteration of Llama 3, released in July 2024. Meta Llama 3.1 comes in three sizes: 8B for efficient deployment and development on consumer-size GPU, 70B for large-scale AI native applications, and 405B for synthetic data, LLM as a Judge or distillation; among other use cases. Amongst Meta Llama 3.1 new features, the ones to highlight are: a large context length of 128K tokens (vs original 8K), multilingual capabilities, tool usage capabilities, and a more permissive license.

[Vertex AI](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform) is a machine learning (ML) platform that lets you train and deploy ML models and AI applications, and customize large language models (LLMs) for use in your AI-powered applications. Vertex AI combines data engineering, data science, and ML engineering workflows, enabling your teams to collaborate using a common toolset and scale your applications using the benefits of Google Cloud.

## Recipes

* [Deploy Meta Llama 3.1 405B on Vertex AI with Text Generation Inference](./notebooks/meta-llama-3-1-on-vertex-ai/vertex-notebook.ipynb)

## What's next?

* Fine-tune Meta Llama 3.1 8B on Vertex AI with TRL (single GPU)
* Fine-tune Meta Llama 3.1 70B on Vertex AI with TRL (multi GPU)
