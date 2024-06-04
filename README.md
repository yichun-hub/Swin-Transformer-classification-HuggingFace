# Swin-Transformer-classification-HuggingFace

This project demonstrates how to use pre-trained models from the Hugging Face Transformers library to classify images. The model used in this project can identify various types of animals from images.
The types of animals including scoiattolo, pecora, mucca, gatto, gallina, farfalla, elefante, cavallo and cane.

## Description

The project is structured into three main sections:

1. **Data Loading**: This part deals with loading and preprocessing the images necessary for training and evaluating the model.
2. **Model Training**: In this section, we fine-tune a pre-trained Swin Transformer model on our specific dataset of animal images.
3. **Model Evaluation and Testing**: The final section involves assessing the model's performance on unseen data and ensuring that it generalizes well outside of the training dataset.

This setup not only showcases the integration of cutting-edge machine learning models with practical applications but also provides an accessible way for beginners and intermediate developers to understand and deploy image classification models.

For more details, please see my Medium.

## Getting Started

### Dependencies

- PyTorch 2.1.2 or higher
- Hugging Face Transformers library 4.38.1
- PIL for image processing

Ensure all dependencies are installed using Python's pip package installer:

```bash
pip install torch torchvision transformers pillow

Or

Executing the code in Google Colab. The original version: Fine-tuning for Image Classification with 🤗 Transformers [!https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/image_classification_albumentations.ipynb]
