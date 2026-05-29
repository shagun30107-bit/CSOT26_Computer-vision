# CSOT26_Computer-vision
#week1-
🔍 Neural Networks, CNNs & PyTorch Foundations

WEEK_1 ( OBJECTIVES )
Before we dive into advanced computer vision modeling, we need to master:

-The core math behind Perceptrons, activation functions, and backpropagation.(https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&si=YigXBaf3nSdXYbqL)
-PyTorch essentials (Tensors, Autograd, Layer Modules, and data pipeline setups).(https://docs.pytorch.org/tutorials/beginner/basics/intro.html)
-The spatial mechanics of Convolutions (kernels, padding, stride, and pooling).
-Training, hardware acceleration (GPU utilization), and debugging optimization loops.

🗂️ Step-by-Step Action Plan
Step 1: Environment Setup & Cloud GPU Check
-Do this first: Set up a Google Colab notebook for this week.
-Head to the settings and change your runtime type to use a T4 GPU accelerator. (PyTorch requires hardware acceleration to train these networks efficiently, and Colab provides this with zero local setup required!)

Step 2: Master the Mathematical Foundations
- Dive into the core math of deep learning by watching Videos 1-4 of the (https://surl.li/mhyejd)
  
Step 3: Get Comfortable with PyTorch
-Work through Sections 1-7 of the official https://docs.pytorch.org/tutorials/beginner/basics/intro.html

Step 4: Build a Fully Connected Network (Build 1)
-Build this first: Load up the classic Fashion MNIST dataset (a collection of 28x28 grayscale clothing images across 10 classes).
-Flatten those 2D image matrices into a 1D vector of 784 pixels, and build a standard multi-layer perceptron using linear layers and ReLU activations.
-Run your training loop and observe your baseline test metrics.

Step 5: Shift to Spatial Thinking & CNNs[
-Read this reference: Study the Stanford CS231n: Convolutional Networks Notes or watch the (https://youtu.be/LxfUGhug-iQ?si=nUAxdBrhoNhdD7KE)
-Understand why flattening images discards vital spatial relationships, and see how sliding convolutional kernels, padding, stride, and Max Pooling preserve spatial properties.

Step 6: Build a Convolutional Neural Network (Build 2)
-Build this next: Using the exact same Fashion MNIST dataset, replace your flattened linear network with a proper Convolutional Neural Network (CNN).
-Route your tensors through Conv2D and MaxPool2D layers before passing them into a final classification head.




