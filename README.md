# Transfer Learning–Based Image Classifier (TensorFlow)

This project implements an image classification pipeline using **transfer learning** with pretrained CNN models in TensorFlow.

##  Key Concepts
- Transfer Learning using ImageNet pretrained models
- Pretrained embeddings for feature extraction
- Freezing vs Fine-tuning of CNN layers
- GPU-accelerated training using Google Colab

##  Models Used
- EfficientNetB0 (primary)
- ResNet50 (optional comparison)

##  Workflow
1. Load dataset using TensorFlow Datasets
2. Preprocess and normalize images
3. Use pretrained CNN as a frozen feature extractor
4. Train custom classification head
5. Fine-tune higher layers with low learning rate
6. Evaluate model performance

##  Tech Stack
- TensorFlow / Keras
- Python
- Google Colab
- NumPy, Matplotlib

## Results
Fine-tuning pretrained layers improved validation accuracy compared to using frozen features alone.
