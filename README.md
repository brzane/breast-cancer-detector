# Breast Cancer Detector
## Overview
Breast cancer detector is Desktop app written in python(Jupyter Notebook) with accuracy 86%  to help boosting breast cancer detection 
and aimed to speed up the diagnosis process by assisting specialist to diagnosis and classification the breast cancer by
classifying mammogram image into normal, benign(non-cancerous abnormality) and malignant (cancerous abnormality) using convolutional neural network CNN.
## Introduction
Breast cancer is an important risk that must be concerned by everyone around the world. With almost 1.7 million new cases 
diagnosed in 2012, breast cancer is the most common form of cancer around the world [1]. In 2017, estimated 252,710 new 
invasive breast cancer cases will be developed in women, along with 63,410 of non-invasive breast cancer case, and 40,610 case 
breast cancer deaths . It is the most important reason that can cause low survival rate of breast cancer all around the world. Due to lack of breast cancer 
specialist nurse or doctor, it will cause late diagnosis of breast cancer, lack of compliance to optimal detection or treatment, 
and inequity of access to optimal treatment. Therefore breast cancer detection is developed to perform effectiveness in both 
abnormalities and classification breast detection. This is to assist and diagnose the breast cancer. 
### CNN
CNNs are regularized versions of multilayer perceptrons.
 Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. 
 The "full connectivity" of these networks make them prone to overfitting data. Typical ways of regularization, or preventing overfitting, include: penalizing parameters during training (such as weight decay)
 or trimming connectivity (skipped connections, dropout, etc.) CNNs take a different approach towards regularization: they take advantage of the hierarchical pattern in data and assemble patterns of increasing complexity using smaller and simpler patterns embossed in their filters.
 Therefore, on a scale of connectivity and complexity, CNNs are on the lower extreme.<br><br>
![CNN+Structure](https://user-images.githubusercontent.com/59266093/177186501-440557b0-2d8c-45df-8682-76eb626498a1.jpg)
## Dataset 
this project uses the Breast Histopathology Images dataset from Kaggle> <br>
you can download the dataset from this link(3 GB): https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images
## Results
### Proposed model:<br>
![image](https://user-images.githubusercontent.com/59266093/177185848-9f4ae80e-b184-4912-a239-5abb244593d5.png)
Training Results |     Model Accuracy             |  Model Loss
 :-------------------------:|:-------------------------:|:-------------------------:
 ![image](https://user-images.githubusercontent.com/59266093/177185999-4aac9f4f-cf7e-471e-82c8-36ab327917cf.png) | ![image](https://user-images.githubusercontent.com/59266093/177185699-50f478ec-566f-4720-ba08-8502239e4f3e.png)  |  ![image](https://user-images.githubusercontent.com/59266093/177186114-c8be9088-2208-4204-94f4-ac69b969a239.png)

## What the project contains
1- jupyter note book file contains code and results.<br>
2- detailed paper about the problem and the implementaion approuch and all reference papers and articles(in arabic).
## How to use this project:
this project was written in python (Jupyter notebook) , so you can clone the repo and run the code using Jupyter notebook or VSCODE or Pycharm and happy hacking :)
