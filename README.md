# Bird Classifier
A fine-tuned MobileNetV2 model achieving **95% accuracy** on the CUB_200_2011 bird species dataset.

## Overview
This project involves fine-tuning the MobileNetV2 convolutional neural network on the **CUB_200_2011** dataset for bird species classification. After training, the model achieves an impressive accuracy of **95%**.
Model was trained on both personal laptop CPU and google colab T4 GPU.

## Dataset
### About the Dataset
The **CUB_200_2011** (Caltech-UCSD Birds) dataset is a widely used benchmark in fine-grained image classification. It contains 11,788 images across 200 bird species. Each image is annotated with:
- Bird species label
- Part location annotations
- Bounding boxes

📥 You can access the dataset from [Kaggle](https://www.kaggle.com/datasets/veeralakrishna/200-bird-species-with-11788-images).

## MobileNetV2 
My choice for using MobileNetV2 is due to its balance of efficiency and performance. Since the model is lightweight, it is well-suited for deployment on mobile devices, making it an ideal choice for applications where computational resources are limited. Additionally, MobileNetV2's streamlined architecture reduces memory usage and inference time, ensuring faster and more responsive applications. This scalability makes it particularly advantageous for integrating AI-powered features into mobile apps, providing users with seamless and real-time experiences.<br>

## Evaluation
Evaluation is done using accuracy as the primary metric. The model achieved:
- **Training Accuracy:** 94.96%
- **Validation Accuracy:** 95%

Additionally, loss, validation accuracy and training accuracy were used to monitor training progress and detect overfitting.

## Results
- **Final Model Accuracy:** 95.15%
- **Loss:** 0.4066

  
