# LLaMA Factory Script

This repository contains a script for fine-tuning and inferring LLaMA-Factory models with LoRA configurations. The script leverages Hugging Face's `transformers`, `datasets`, and `peft` libraries to achieve fine-tuning and inference.

## Description

- Fine-tunes a GPT-2 model on a subset of Stable Diffusion prompts.
- Utilizes LoRA (Low-Rank Adaptation) for efficient training.
- Provides a Gradio interface for generating prompts.
- Includes a CLI application for interactive use.

## Usage

1. **Install the required libraries:**

```bash
pip install transformers torch gradio datasets huggingface_hub peft
