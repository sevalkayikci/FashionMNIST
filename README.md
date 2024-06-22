👗 Fashion MNIST Project
========================

Welcome to the Fashion MNIST Project! This project leverages machine learning to classify images of clothing using the Fashion MNIST dataset. This project is part of the AYGAZ YAPAY ZEKAYA GİRİŞ BOOTCAMP.

📚 Libraries Utilized
---------------------

This project makes use of the following libraries:

*   TensorFlow
*   scikit-learn
*   matplotlib

📂 Data Loading
---------------

The Fashion MNIST dataset is loaded using TensorFlow's built-in functions. The dataset includes 60,000 training images and 10,000 test images, each with dimensions of 28x28 pixels.

📊 Data Dimensions
------------------

The shapes of the datasets are as follows:

*   `X_train`: (60,000, 28, 28)
*   `y_train`: (60,000,)
*   `X_test`: (10,000, 28, 28)
*   `y_test`: (10,000,)

🧠 K-Nearest Neighbors (KNN) Model
----------------------------------

### 📝 Data Preparation

The images are reshaped from 2D arrays into 1D arrays to be compatible with the KNN model.

### 🔧 Model Creation

A KNN model is created using `KNeighborsClassifier` with 3 nearest neighbors.

### 🏋️‍♂️ Training

The model is trained on the flattened training dataset.

### 🔍 Prediction and Evaluation

Predictions are made on the test dataset, and the following evaluation metrics are calculated:

*   **Accuracy**: 0.8541
*   **Precision**: 0.8575
*   **Recall**: 0.8541
*   **F1 Score**: 0.8539

📈 Results
----------

The KNN model demonstrates good performance on the Fashion MNIST dataset, achieving an accuracy of 85.41%.

🔚 Conclusion
-------------

The KNN model provides a robust and efficient method for classifying images in the Fashion MNIST dataset. While the accuracy is strong, further improvements could be achieved through hyperparameter tuning, using more sophisticated models, or employing data augmentation techniques.

🚀 How to Run
-------------

To install the required libraries, run:

`pip install tensorflow scikit-learn matplotlib` 

📞 Contact
----------
For any questions or further information, please contact:

- **Email**: sevalkayikci@gmail.com
- **LinkedIn**: [Seval Hatice Kayikci](https://www.linkedin.com/in/seval-hatice-kayikci-9730261b5/)
- **GitHub**: [sevalkayikci](https://github.com/sevalkayikci)
