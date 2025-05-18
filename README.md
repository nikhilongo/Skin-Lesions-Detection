# Skin Lesion Classification with Deep Learning

## Project Overview

This project focuses on the classification of seven types of skin lesions using the HAM10000 dataset, which contains 10,000 dermatoscopic images. The primary objective was to leverage advanced deep learning techniques to achieve high classification accuracy.

## Key Features

* **Deep Learning Model:** Developed a model for classifying skin lesions using DCNNs (Deep Convolutional Neural Networks).
* **Pre-trained Models Used:** Fine-tuned state-of-the-art DCNNs, including VGG16, Inception V3, Inception ResNet V2, and DenseNet 201.
* **High Accuracy:** Achieved a top test accuracy of 88.52% using an ensemble of Inception V3 and DenseNet 201.
* **Transfer and Ensemble Learning:** Employed transfer learning to leverage pre-trained models and combined them using ensemble learning for superior performance.
* **Comparative Analysis:** Conducted a detailed comparison of different DCNN architectures, identifying DenseNet 201 as the best-performing model for this task.

## Results

* Highest Accuracy: 88.52% on the test set using an ensemble of Inception V3 and DenseNet 201.
* Comparative Model Performance:

  * VGG16: 79.64% test accuracy.
  * Inception V3: 79.94% test accuracy.
  * Inception ResNet V2: 82.53% test accuracy.
  * DenseNet 201: 83.93% test accuracy.

## License

This project is open-source and available under the MIT License.
