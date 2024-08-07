# Fine-Tuning Phi-3 Model for Natural Text-to-SQL Query Generation Based on Database Schema
![alt text](image.png)
## Overview

This guide details the process of fine-tuning the Microsoft Phi-3-mini-4k model on custom data to generate SQL queries from natural language text. The fine-tuning process allows the model to interpret and transform natural language input into SQL queries based on a provided database schema.

## Model Description

The Phi-3-mini-4k is a compact yet powerful variant of the Phi-3 series of small language models (SLMs) developed by Microsoft. With 3.8 billion parameters and the ability to handle context lengths of up to 4,000 tokens, this model provides a balance between computational efficiency and the capability to process substantial amounts of text.

## Advantages of Phi-3 Models

- **High Efficiency**: The Phi-3 models, including the Phi-3-mini-4k, offer competitive performance in language understanding and generation despite their smaller size compared to larger models like GPT-3 or GPT-4.
- **Cost-Effectiveness**: Lower computational power requirements translate to reduced operational costs.
- **Flexibility**: The models can be deployed across various platforms, including cloud environments, edge devices, and personal computers.
- **Fine-Tuning Capability**: Phi-3 models are well-suited for fine-tuning, making them ideal for adapting to specific domains or tasks.


## What is Finetuning?

Finetuning is the process of training a pre-trained language model on a new dataset to learn specific skills, languages, or tasks not covered during its initial training. This process updates the model's parameters through a method known as back-propagation.

## Why Finetune?

Language models like ChatGPT are initially trained on vast and diverse datasets to handle a wide range of topics and interactions. However, to adapt these models to specific applications—such as understanding a new programming language, adhering to particular conversation styles, or excelling in specialized tasks—finetuning becomes essential. It allows the model to become more proficient in areas relevant to the users' needs.

However, finetuning can be resource-intensive and time-consuming due to the complexity of the models and the depth of learning required.

## why unsloth for finetuning?
Unsloth makes finetuning large language models like Llama-3, Mistral, Phi-3 and Gemma 2x faster, use 70% less memory, and with no degradation in accuracy!

