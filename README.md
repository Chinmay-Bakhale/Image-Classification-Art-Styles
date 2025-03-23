# Hybrid Zero-Shot and Fine-Tuned Image Classification System for Art Styles

A Python-based project that combines Vision Transformers (ViT) with Low-Rank Adaptation (LoRA) and OpenAI's CLIP model to classify images into known and novel art styles.

## Project Overview

This system supports hybrid classification by leveraging fine-tuned ViT-LoRA for specialized categories and CLIP's zero-shot capabilities for arbitrary user-defined categories.

## Key Features

- **Fine-tuning**: ViT model with LoRA for efficient adaptation to art styles.
- **Zero-shot Classification**: CLIP model for novel categories.
- **Hybrid Approach**: Combines predictions from both models for robust classification.
- **User Interface**: Supports image uploads and custom category inputs.

## Tech Stack

- **Programming Language**: Python
- **Deep Learning Frameworks**: PyTorch, Hugging Face Transformers
- **Model Architectures**: ViT, CLIP
- **Parameter-Efficient Fine-Tuning**: LoRA

## Getting Started

1. Clone the repository.
2. Install required packages: `!pip install transformers peft torch torchvision pillow ftfy regex tqdm`
3. Run the notebook (`Hybrid_Zero_Shot_Classification.ipynb`) in Google Colab or a similar environment.

## Contributions

Contributions are welcome! Please read the contribution guidelines before submitting pull requests.

## License

[Insert License Here]

## Last Updated

[Insert Date]
