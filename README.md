# DogCatBird-KaggleChallenge CSE669 Deep Learning

# **Overview**
This repository contains the implementation of  image classification task  differentiate between three classes: Dog, Cat, and Bird. In this i used CNN architectures, including Baseline CNN, Transfer Learning Models (ResNet-18, VGG-16) and an Ensemble Model to achieve optimal performance on the dataset sourced from a Kaggle competition (https://www.kaggle.com/t/571920ea0e2f4c9b99b725b667afdd69)

##  **Dataset Details**

- **Training Set:** 40,000 labeled images (32x32 PNG format)  
- **Test Set:** 20,000 unlabeled images  
- **Balanced Dataset:** Equal representation across all three classes  
- **Evaluation Metric:** Accuracy

## Insights
The results showed that a learning rate of 0.001 consistently outperformed ensuring efficient convergence and increasing the number of epochs improved accuracy especially for deeper models like VGG-16. A dropout rate of 0.5 effectively minimized overfitting, enhancing generalization. ResNet-18 performed better than VGG-16 due to its residual connections, enabling stable training. Combining both architectures in an ensemble model delivered balanced and good accuracy but I achieved highest accuracy with ResNet-18 that is 88%.

### This repository includes all necessary implementation details for data preprocessing, model training, evaluation and visualization making it a comprehensive resource for this image classification tasks. Further I write a detailed report using LateX and i added it as well
