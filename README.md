# Churn Classification Modelling

![](https://raw.githubusercontent.com/Mohitkr95/Churn-Classification-Modelling/master/Images/1_Xap6OxaZvD7C7eMQKkaHYQ.jpeg)

Customer attrition, customer turnover, or customer defection — they all refer to the loss of clients or customers, ie, churn. This can be due to voluntary reasons (by choice) or involuntary reasons (for example relocation).
In this project I have predicted whether the customer will leave the bank or not based on the dataset provided by the bank This dataset is taken from [Deep Learning A-Z™: Hands-On Artificial Neural Networks](https://www.udemy.com/course/deeplearning/#instructor-1) and the project is inspired from **Kirill Eremenko**.

## Installation Instructions

### How to install Theano, TensorFlow and Keras

**For Mac users:**

Open your main terminal or the Anaconda Prompt and enter the following commands:
pip install theano
pip install tensorflow
pip install keras
conda update --all

**For Windows and Linux users:**
In Spyder, go to Tools and Open Anaconda Prompt. Then enter the following commands:
1. Create a new environment with Anaconda and Python 3.5:
conda create -n tensorflow python=3.5 anaconda
2. Activate the environment:
activate tensorflow
3. After this you can install Theano, TensorFlow and Keras:
conda install theano
conda install mingw libpython
pip install tensorflow
pip install keras
4. Update the packages:
conda update --all
5. Run Spyder:
spyder

To install TensorFlow on your GPU (optional):
pip install tensorflow-gpu

I have used ANN for this project with 2 hidden layers (each with 6 nodes) and the detailed description about Artificial Neural Network is as follows:

## Artificial Neural Networks

![](https://raw.githubusercontent.com/Mohitkr95/Churn-Classification-Modelling/master/Images/Artificial-neural-network-architecture-ANN-i-h-1-h-2-h-n-o.png)

Artificial neural networks (ANN) or connectionist systems are computing systems vaguely inspired by the biological neural networks that constitute animal brains. Such systems "learn" to perform tasks by considering examples, generally without being programmed with task-specific rules. For example, in image recognition, they might learn to identify images that contain cats by analyzing example images that have been manually labeled as "cat" or "no cat" and using the results to identify cats in other images. They do this without any prior knowledge of cats, for example, that they have fur, tails, whiskers and cat-like faces. Instead, they automatically generate identifying characteristics from the examples that they process.
