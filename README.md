# Linear-Transformations-and-Neural-Networks
This repository contains the Jupyter Notebook C1W3_Assignment.ipynb, which serves as the third assignment for a Linear Algebra course. This assignment is designed to deepen your understanding of linear transformations and introduce foundational concepts of neural networks, highlighting the crucial role of linear algebra in both domains.

Table of Contents
The notebook is structured into the following main sections:

1 - Introduction

1.1 - Transformations

1.2 - Linear Transformations

1.3 - Transformations Defined as a Matrix Multiplication

2 - Standard Transformations in a Plane

2.1 - Horizontal Scaling (Dilation)

2.2 - Example 2: Reflection about y-axis (the vertical axis)

2.3 - Stretching by a scalar (Exercise 1)

2.4 - Horizontal shear transformation (Exercise 2)

2.5 - Rotation (Exercises 3 & 4)

3 - Neural Networks

3.1 - Linear Regression

3.2 - Neural Network Model with a Single Perceptron and Two Input Nodes

3.3 - Parameters of the Neural Network

3.4 - Forward propagation (Exercise 5)

3.5 - Defining the cost function (Exercise 6)

3.6 - Training the neural network

4 - Make your predictions! (Exercise 7)

Assignment Overview
This assignment is divided into two core parts:

Linear Transformations: You will implement functions to generate matrices for various 2D transformations, including stretching, shearing, and rotation. This section emphasizes the practical application of linear algebra in manipulating vectors and geometric shapes.

Neural Networks: The focus shifts to building a simple neural network. You will implement the forward propagation step for a single perceptron with two input nodes, and define the cost function. This part illustrates how linear algebraic operations form the backbone of neural network computations, from basic linear regression to more complex models.

By completing this assignment, you will gain a clear understanding of how linear algebra underpins both vector transformations and the core mechanics of neural networks.

Required Packages
To run this Jupyter Notebook, you will need the following Python libraries:

numpy: For numerical operations, especially array and matrix manipulations.

matplotlib: For plotting and visualizing transformations and data.

pandas: For data manipulation and analysis (used for the neural network section).

utils (custom module): This module is expected to be provided alongside the assignment, containing helper functions.

w3_unittest (custom module): This module is expected to be provided alongside the assignment, containing unit tests for the exercises.

You can install the primary dependencies using pip:

pip install numpy matplotlib pandas

Note: utils.py and w3_unittest.py are typically provided with the course materials and should be placed in the same directory as the notebook.

How to Run the Notebook
Clone this repository (or download the C1W3_Assignment.ipynb file along with any accompanying data/ and utils.py/w3_unittest.py files):

git clone https://github.com/junaidshah2001/Linear-Transformations-and-Neural-Networks.git
cd Linear-Transformations-and-Neural-Networks

(Note: The repository name Linear-Transformations-and-Neural-Networks is a suggestion based on the assignment title.)

Ensure you have Jupyter installed. If not, you can install it via pip:

pip install jupyter

Install the required Python packages as listed above.

Launch Jupyter Notebook:

jupyter notebook

In the Jupyter interface that opens in your web browser, navigate to the directory where you saved C1W3_Assignment.ipynb and open it.

You can then run the cells sequentially to follow the explanations and complete the exercises.

Exercises
The notebook includes several exercises designed to test your understanding and practical implementation skills. These are marked within the notebook (e.g., Exercise 1, Exercise 2, etc.) and cover topics such as:

Creating transformation matrices for stretching, shearing, and rotation.

Implementing forward propagation for a single-perceptron neural network.

Defining a cost function for the neural network.

Making predictions with the trained model.

Contributing
If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
