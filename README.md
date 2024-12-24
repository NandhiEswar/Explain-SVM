Support Vector Machine (SVM) Kernels Demonstration

This project demonstrates the usage of Support Vector Machines (SVM) with various kernels (Linear, Polynomial, RBF, and Sigmoid) to perform binary classification. The MNIST dataset is used for practical demonstration, where the task is to classify the digit '0' versus all other digits.

Overview

Support Vector Machines (SVM) are powerful machine learning algorithms used for classification tasks. By using different kernels, SVM can create complex decision boundaries that allow it to classify data that is not linearly separable.

In this project, we explore the following kernels:

Linear Kernel: Used when data is linearly separable.
Polynomial Kernel: Maps data to higher dimensions, useful for non-linear data.
RBF (Radial Basis Function) Kernel: Transforms data into a higher-dimensional space, allowing for more complex decision boundaries.
Sigmoid Kernel: Often used in neural networks, mimics the behavior of certain activation functions.
Installation

To run this project, you'll need the following Python libraries:

pip install numpy pandas scikit-learn matplotlib
Project Structure

SVM-Kernels-Demo/
│
├── data/                   # Data files (MNIST dataset)
├── main.py                 # Main script for training SVM models
├── README.md               # Project description
└── requirements.txt        # List of dependencies
Usage

1. Clone the Repository
git clone https://github.com/your-username/SVM-Kernels-Demo.git
cd SVM-Kernels-Demo
2. Run the Main Script
Run the script to see the demonstration of different SVM kernels:

python main.py
This script will:

Load the MNIST dataset.
Preprocess it for binary classification (digit '0' vs. others).
Train SVM models using each kernel (Linear, Polynomial, RBF, and Sigmoid).
Evaluate and print the accuracy of each model.
3. Results
The script will output the classification accuracy for each SVM model using different kernels, providing insight into how each kernel performs on the MNIST dataset.

Example Output

Accuracy with Linear Kernel: 0.89
Accuracy with Polynomial Kernel: 0.91
Accuracy with RBF Kernel: 0.94
Accuracy with Sigmoid Kernel: 0.87
Contributing

Feel free to fork the repository and contribute by opening issues or submitting pull requests. If you have suggestions for additional kernels or improvements to the project, I welcome your contributions!

License

This project is licensed under the MIT License.

Learn More

For more on SVM and kernels, check out the following resources:

Scikit-learn SVM documentation
Understanding SVM Kernels
