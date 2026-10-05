#Comparative Evaluation of Pre-Trained CNN Architectures for Pediatric Pneumonia Detection

Pneumonia remains a leading cause of mortality among children under five globally, particularly in resource-constrained environments where access to radiologists and advanced diagnostics is severely limited. While previous studies have shown that Convolutional Neural Networks (CNNs) can accurately detect pneumonia, they have predominantly focused on classification accuracy while neglecting computational efficiency a critical factor for deployment in low-resource settings.

This repository contains the code, evaluation pipeline, and experimental results for a comparative study evaluating three prominent pre-trained CNN architectures (VGG16, ResNet50, and EfficientNet) under identical hyperparameters using a public chest X-ray dataset.

**Key Findings**
-  High-Performance Workstations: ResNet50 achieves a top accuracy of 98.09%, making it ideal for high-throughput hospital workstations.

-  Edge Deployment: EfficientNet offers a lightweight solution (~29 MB), balancing robust accuracy with the constraints of edge devices in low-resource clinical
   settings.
