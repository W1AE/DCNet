# DCNet: A Deconvolutional-Convolutional Neural Network for 1-Dimensional Big Data Analysis

## Abstract:
In recent years, the two dimensional convolutional neural network has beeen widely used in numerous practical applications. However, in some cases, the 1D convolutional neural networks are not wide spread as it is. The primary reason is that the existing CNN-based methods for 1D signals are expensive due to the need for human-made pre-processing, such as utilizing the preprocessing techniques like DFT to rebuild the 1D signal into the 2D array. In this paper, a novel 1D signal processing algorithm is proposed for 1D big data analysis through learning a deep network. Compared to the existing 1D signal processing algorithms, the DCNet has the advantages of fewer human-made inference and higher generalization performance. The experimental results with a varying number of training patterns (50 K to 11 M) ranging from classification and regression show that the DCNet provides better performance over most of the existing algorithms.

## Contributions:
* I. Architecture side -  In this paper, one 1D classification and regression algorithm called DCNet is proposed. Specifically, the proposed algortihm shows better generalization performance over other existing 1D classification models. 

* II. Application side - In some real-world applications, the 1D CNNs need the use of man-made pre-processing steps, which is time-consuming and expensive. In this paper, the end-to-end algorithms is developed without human inference.

## Learning Structure:

<img src="https://github.com/W1AE/DCNet/blob/main/f1_n.jpg" width="1050" height="430" />

## Downloads:
### Connect4 dataset
* Connect4 dataset: [Caltech-101 DATASET](http://www.vision.caltech.edu/Image_Datasets/Caltech101/)
* Source code for Connect4: [Connect4](https://github.com/W1AE/Retraining/blob/main/Demo_Caltech101.zip)
### Hep-OS dataset
* Hep-OS dataset: [Hep-OS (Google Drive)](https://drive.google.com/file/d/1kL3de2i6QYgFyOpmZYlnFy6_IJKeRB38/view?usp=sharing)
* Source code for Hep-OS: [Hep-OS](https://github.com/W1AE/Retraining/blob/main/Demo_MNIST.zip)

## Dependancies
* Matlab version 2020a,
* A workstation with a 256GB memory and an E5-2650 processor.

## Reproduce the Experimental Results

#The code is released in content-obscured version (p files). After acceptance of the manuscript (if decided so), the source code will be made public.
