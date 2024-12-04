# Artificial Neural Networks

An Artificial Neural Network (ANN) is a concept in artificial intelligence inspired by the structure and functioning of biological neural networks in the human brain. Similar to the human brain which consists of neurons interconnected in complex networks to communicate and learn, ANNs are made up of interconnected units called nodes that work together in various layers to process information. By mimicking the way neurons collaborate in the brain, ANNs are designed to enable computers to understand information, solve problems, and make decisions in a way that resembles human thought processes.

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Basic Programming knowledge in Python is recommended. See deployment for notes on how to deploy the project on a live system.

# Prerequisites

What things you need to install the software and how to install them

1. GIT
2. ANACONDA NAVIGATOR
3. DATASET TO RUN THE NEURAL NETWORK ALGORITHM

# Installing

A step by step series of examples that tell you how to get a development environment running

1. To download the anaconda navigator, visit the official website https://www.anaconda.com/download/success
   
![image](https://github.com/user-attachments/assets/86295b05-a337-41ec-a268-ff1f9f0d4e13)

2. Choose the installer package for your operating system (Windows, Linux, or macOS).
3. Once the download is complete, open the installer package.
4. Follow the on-screen instructions to complete the installation.
5. Launch the Anaconda Navigator and access the Jupyter Notebook to open it.

![Screenshot 2024-12-04 123028](https://github.com/user-attachments/assets/d1e1e778-7917-4687-9aba-94454b0ca46a)

# Running the tests

1. Clone the repository using the command git clone "the web URL", which can be obtained by clicking the Code dropdown button on GitHub.
2. If Git is not installed on your system, download the repository as a ZIP file by selecting the Download ZIP option from the Code dropdown menu. Extract the ZIP file after downloading.
3. Open Jupyter Notebook from your browser by launching it through Anaconda Navigator or directly searching for "Jupyter Notebook" on your machine.
4. Navigate to the folder where the repository was cloned or the ZIP file was extracted.
5. Open the NeuralNetwork.ipynb file in Jupyter Notebook.
6. Execute each code by pressing Shift + Enter.

# Break down into end to end tests

Explain what these tests test and why

## Breakdown of Neural Network Classifier

This project uses the MLPClassifier with the following configuration:

Hidden Layer Sizes: (5, 4, 5)
Activation Function: ReLU
Solver: Adam
Max Iterations: 10,000
Random State: 100

The model's performance is evaluated using a confusion matrix and a classification report.

## Decision Tree Classifier

Implements the DecisionTreeClassifier with:

Random State: 100

Evaluation is performed using a confusion matrix and a classification report.

# Authors

Aiswarya Somanath

# License
This project is licensed under the MIT License - see the LICENSE.md file for details

# Acknowledgments
Rejoy James, Prof DATA 1202 DATA ANALYSIS TOOLS
