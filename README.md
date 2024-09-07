# Food-classification-with-deeplearnig-method

This project aims to develop a lightweight and efficient deep learning model for food image classification. The primary objective is to achieve fast and accurate classification by leveraging MobileNet V2, a pre-trained image classification model, in combination with a Support Vector Machine (SVM) classifier. This hybrid approach is designed to optimize the balance between speed and accuracy, making it well-suited for real-time food classification applications.

## Model using performance
1.MobileNet V2 with Linear Layers: Standard deep learning approach using linear layers for classification.
2.MobileNet V2 with SVM Classifier: A hybrid model combining MobileNet V2 features with an SVM classifier for potentially improved classification performance.
3.MobileNet V2 with Transfer Learning and SVM Classifier: Enhancing the MobileNet V2 model with transfer learning for fine-tuning, paired with an SVM classifier for better accuracy.
4.CNN (Custom Model) with Linear Layers: A convolutional neural network built from scratch, using linear layers for classification.

## Summery
Unfreezing the last 10 layers of MobileNetV2 and using an SVM classifier provided the best performance for food image classification. This combination improved accuracy and efficiency, making it ideal for real-time or resource-constrained environments. The SVM consistently outperformed the CNN classifier, particularly when paired with transfer learning. Despite some misclassifications among visually similar food items, this approach offers the best balance of accuracy, efficiency, and computational demand.
