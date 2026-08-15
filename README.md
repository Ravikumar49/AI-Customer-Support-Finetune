# Customer Support Llama 3.2 3B LoRA

This model is a fine-tuned LoRA adapter based on **unsloth/Llama-3.2-3B-Instruct**, optimized to behave like a trained, professional customer support assistant. 

## Model Description
- **Developed by:** [Your Hugging Face Username]
- **Model Type:** LoRA Adapter (Fine-tuned)
- **Base Model:** unsloth/Llama-3.2-3B-Instruct
- **Language:** English

## Intended Uses & Limitations
This model is designed to answer customer support queries across various retail e-commerce categories, including:
- Order cancellations and status updates
- Refund policy inquiries
- Changing shipping addresses
- Account deletion requests

## Training Dataset
The model was fine-tuned on the **bitext/Bitext-customer-support-llm-chatbot-training-dataset**, which includes 26,872 real-world customer support instruction-response pairs spanning 27 intents.

## Training Configuration
The adapter was trained using the following parameters:
- **r (rank):** 16
- **lora_alpha:** 16
- **Training Steps:** 60
- **Learning Rate:** 2e-4
- **Optimizer:** adamw_8bit
- **Hardware:** Google Colab T4 GPU

Link: https://huggingface.co/Jack217/customer-support-llama-3.2-3b-lora
