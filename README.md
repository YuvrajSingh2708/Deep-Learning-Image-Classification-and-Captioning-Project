# Deep Learning Image Classification and Captioning Project

## Overview
This repository showcases a project demonstrating image classification using Convolutional Neural Networks (CNN) and image captioning using Recurrent Neural Networks (RNN). Originally developed as an assessment for the COMP5625M Practical course, this project now serves as a standalone demonstration of deep learning techniques for image analysis and understanding.

## Motivation
The project aims to provide a practical exploration of deep learning techniques for image analysis and understanding. By focusing on image classification and captioning tasks, it aims to familiarize users with fundamental concepts such as model training, evaluation, and optimization, as well as advanced strategies like handling overfitting and text preprocessing.

## Output Highlights
- **CNN vs. MLP for Image Classification**: The CNN model outperformed the MLP model with a validation accuracy of around 50% compared to 23%. The CNN model's simplicity and ability to find patterns in images through convolutional layers contributed to its superior performance.
- **CNN Model with Data Augmentation**: Data augmentation methods didn't significantly improve the CNN model's performance. Despite a slight reduction in validation loss initially, the model eventually overfit.
- **Feedback on CNN Model with Dropout**: Using dropout regularization in the CNN model proved highly effective, maintaining consistent accuracy levels for both training and validation datasets without signs of overfitting.
- **Feedback on AlexNet Model**: The AlexNet model trained on CIFAR10 achieved 78.8% accuracy on the validation set, demonstrating effective performance. Conversely, freezing some layers in the AlexNet model led to a drop in accuracy, highlighting the importance of convolutional layers for image classification.

## Usage
1. Ensure Python and necessary libraries are installed.
2. Download the dataset provided or access it from the specified source.
3. Execute the Jupyter notebook files provided in the repository.
4. Follow the instructions within the notebooks to train models, generate predictions, and evaluate performance.
5. Modify the code as needed for experimentation or adaptation to other datasets.

## Contributors
- Shrichand Bhuria 

Feel free to explore the notebooks and experiment with the provided code to understand and apply deep learning techniques for image classification and captioning tasks. If you encounter any issues or have suggestions for improvement, please feel free to contribute or reach out to the project contributors.
