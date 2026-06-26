## Machine Learning Lab 8 : Custom CNN for Image Classification

Overview:
This repository contains the implementation of Lab 8, where a custom Convolutional Neural Network (CNN) is designed, trained, and evaluated for image classification using a corn leaf disease dataset.

### Author
* Uzair-ur-Rehman  
* Registration No: 22JZELE0471  
* Department: Electrical Engineering

Repository Contents:

Lab_8_22jzele0471.ipynb`

Objectives:

* Design a custom CNN architecture.
* Train the CNN using image datasets.
* Apply Batch Normalization and Dropout to improve performance.
* Evaluate the trained model on test data.
* Visualize training and validation accuracy.

 CNN Architecture:

Conv2D (64 Filters, 3×3, ReLU)
Batch Normalization
MaxPooling2D
Conv2D (128 Filters, 3×3, ReLU)
Batch Normalization
MaxPooling2D
Conv2D (256 Filters, 3×3, ReLU)
Dropout (0.3)
MaxPooling2D
Flatten
Dense (256, ReLU)
Dropout (0.5)
Dense (1, Sigmoid)

Technologies Used:

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

Dataset:

The model is trained using two classes from the Corn Leaf Disease dataset.

How to Run:

1. Clone the repository.
2. Install the required libraries:
3. Open Jupyter Notebook:
4. Run: Lab_8_22jzele0471.ipynb

Learning Outcomes:

* Build custom CNN architectures.
* Train deep learning models.
* Apply Batch Normalization and Dropout.
* Evaluate image classification models.
* Analyze CNN performance.

License:

This project is submitted for academic and educational purposes.
