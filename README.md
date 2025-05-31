# Fine-Tuning LLM: Llama-3.2-3B-Instruct Fine-Tuning Project

This project demonstrates how to fine-tune the Llama-3.2-3B-Instruct model using QLoRA, an efficient method for adapting large language models with limited computational resources.

---

## Tech Stack & Key Libraries

### Core Framework
- Python

### Deep Learning
- PyTorch

### LLM Fine-Tuning and Optimization
- **Unsloth**: Provides accelerated supervised fine-tuning (SFT) and support for QLoRA with 4-bit quantization.
- **Transformers (Hugging Face)**: Used for accessing the base model, tokenizers, and various training utilities.
- **TRL (Transformer Reinforcement Learning)**: Supplies the `SFTTrainer` for structured training workflows.
- **Bitsandbytes**: Enables 4-bit quantization for memory-efficient model loading.
- **Xformers** (optional but recommended): Improves performance through optimized attention mechanisms.

### Data Handling
- **Datasets (Hugging Face)**: Used for loading and preprocessing training data.

---

## Base Model

- `unsloth/Llama-3.2-3B-Instruct`

## Example Dataset

- `mlabonne/FineTome-100k`

---

## Installation of Key Libraries

Install the required libraries using pip:

```bash
pip install unsloth transformers trl datasets torch bitsandbytes xformers
```

---


