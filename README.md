# MNIST Classification Using Convolutional Neural Networks (CNN)

## Project Description
This project explores the application of Convolutional Neural Networks (CNN) for image classification tasks on the MNIST Digits and Fashion-MNIST datasets. CNN was employed to classify handwritten digits and fashion items, achieving competitive accuracy.

## Dataset
- **MNIST Digits Dataset**: 70,000 grayscale images (28x28) of handwritten digits (0–9), commonly used for computer vision benchmarks.
- **Fashion-MNIST Dataset**: 70,000 grayscale images (28x28) of clothing items in 10 categories, designed for fashion image classification.

## Model Architecture
The CNN model includes:
- **Convolutional Layers**: Two layers with 32 and 64 filters respectively, using a 3x3 kernel and ReLU activation.
- **MaxPooling Layers**: Reduces dimensionality with a 2x2 pooling size.
- **Fully Connected Layers**: Includes a dense layer with 128 neurons and a final dense layer with 10 output units using the softmax activation function.
- **Optimizer**: Adam optimizer for efficient training.
- **Loss Function**: Sparse categorical crossentropy for multi-class classification.

## Implementation
1. **Data Preprocessing**: Reshaped images to 28x28x1 and normalized pixel values.
2. **Model Training**: Implemented a CNN model with the architecture described above, trained over 5 epochs with a batch size of 64.
3. **Evaluation**: Tested the model’s accuracy on the test sets of both datasets.

## Results
- **Digits Dataset**: Achieved an accuracy of 99.23%.
- **Fashion Dataset**: Achieved an accuracy of 90.30%.
- **Confusion Matrix Analysis**: High accuracy for the digits dataset; fashion dataset shows notable misclassification in similar clothing categories (e.g., shirts and pullovers).

## Contribution
Feel free to fork this repository and submit pull requests with improvements or additional features.
