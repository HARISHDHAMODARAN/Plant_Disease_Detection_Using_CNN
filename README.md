**🌿 Plant Disease Detection Using CNN**
This repository contains a deep learning project that utilizes a Convolutional Neural Network (CNN) for detecting and classifying plant diseases based on images. The model is trained on image datasets representing healthy and diseased plant leaves, enabling it to identify three classes: Healthy, Powdery Mildew, and Rust.

**🚀 Features**
Data Preprocessing: Augmentation techniques like rotation, width/height shifts, zooming, and horizontal flipping.
Model Architecture: Sequential CNN model with convolutional, max-pooling, dropout, and dense layers.
Real-Time Evaluation: Visualization of predictions using a confusion matrix and classification report.
Performance Metrics: Achieves up to 93.75% accuracy on test data.
Visualization: Custom data visualization for training images.

**📂 Dataset**
The project uses a custom dataset of plant leaves categorized into:
Healthy
Powdery Mildew
Rust
Each image is resized to 150x150 pixels, and data is split into training, validation, and testing sets.

**🛠️ Technologies Used**
Programming Language: Python
Deep Learning Library: TensorFlow/Keras
Visualization Tools: Matplotlib, Seaborn
Data Augmentation: Keras ImageDataGenerator

**📖 How It Works**
1.Data Preprocessing:
Rescales pixel values to [0,1].
Applies augmentations like rotation, shift, zoom, and flips to improve model robustness.

2.Model Architecture:
3 Convolutional layers with ReLU activation.
MaxPooling for feature reduction.
Dropout for regularization.
Fully connected dense layers for classification.

3.Training and Evaluation:
Trains on augmented data for up to 30 epochs with early stopping.
Evaluates using accuracy and loss on test data.

4.Visualization:
Confusion matrix and classification report for detailed performance metrics.

**📈 Results**
Accuracy: Achieved 93.75% on the test dataset.
Confusion Matrix: Helps identify true positives, false positives, and false negatives.
Classification Report: Precision, Recall, and F1-score metrics for all classes.
