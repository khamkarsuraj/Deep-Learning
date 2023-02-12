# Deep-Learning

Homework 1 CPSC-8430\
Suraj Khamkar\

This repo consist of below files with code\

Q1-Task1 - source code for Part1.1 Simulate a Function\
Q1-Task2 - source code for Part1.2 Train on an Actual Task\
Q2-Task1 - source code for Part2.1 Visualize the Optimization Process\
Q2-Task2 - source code for Part2.2 Observe Gradient Norm during Training\
Q2-Task3 - souce code for Part2.3 Calculating minimal ratio at zero gradient\
Q3-Task1 - source code for Part3.1 Can Network fit Random Labels\
Q3-Task2 - source code for Part3.2 Number of Parameters VS.Generalization\
Q3-Task3-Subtask1 - Interpolation.ipynb - source code for Part3.3.1 Flatness VS. Generalization\
Q3-Task3-Subtask2- souce code for Part3.3.2 Flatness VS. Generalization\
HW1_Report.pdf - Assignment report with analysis of code and results\

To run these files, the following libraries are required:\
python 3.8\
Pytorch 1.7\
Tensorflow 2.4\
Matplotlib 3.2.2\
Numpy 1.19\

The dataset required to run the source code is the MNIST dataset from the torchvision datasets library in pytorch. Once the dataset is downloaded to this pathfile, it can be used by every other file and is the only file you will need to download. In every file that requires the MNIST dataset, there is a line of code that grabs the dataset.
It is provided below:
trainingSet = datasets.MNIST('', train=True, download=False, ...)
To download the dataset, change the download option to True. This is done for you in the first source code file (Part1_TrainOnActualTask.ipynb). You will need internet connect to download the dataset.
