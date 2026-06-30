# Selecting-an-Open-Source-LLM-for-eCommerce-Fine-Tuning
To build a lightweight, cost-effective, and domain-specific AI assistant for eCommerce by fine-tuning an open-source LLM on a free Google Colab T4 GPU using modern parameter-efficient fine-tuning techniques.
This project explores and evaluates multiple open-source Large Language Models (LLMs) to identify the most suitable model for fine-tuning on a Google Colab Free (Tesla T4 GPU) environment. After comparing different models based on performance, hardware requirements, licensing, and ease of fine-tuning, Qwen2.5-3B-Instruct was selected.

The project demonstrates an end-to-end fine-tuning workflow using Unsloth, QLoRA, and LoRA to adapt the model for eCommerce tasks such as customer support, product recommendations, product description generation, FAQ answering, and return policy assistance.
*Objectives
1) Research and compare open-source LLMs.
2) Select the best model for a free Google Colab T4 GPU.
3) Fine-tune the selected model using Parameter-Efficient Fine-Tuning (PEFT).
4) Build an eCommerce-focused conversational model.
5) Evaluate the fine-tuned model using sample eCommerce prompts.

Project Workflow


Research
      ↓
Model Comparison
      ↓
Model Selection
      ↓
Environment Setup
      ↓
Load Pre-trained Model
      ↓
Configure LoRA
      ↓
Prepare Dataset
      ↓
Fine-Tune Model
      ↓
Save LoRA Adapter
      ↓
Evaluate Model
