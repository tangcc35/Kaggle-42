# Data-2040-Midterm-Project  ![](https://img.shields.io/badge/python-3.7+-pink.svg)  
***Group Member: Shiyu Liu, Cangcheng Tang, Guanzhong Chen***

## <center>Hand-written Bengali Grapheme Classification</center>

## Introduction

As the main task of this Kaggle competition, optical character recognition requires the algorithms to take the handwritten Bengali images as input and return the constituents of the character image: grapheme root, vowel diacritics, and consonant diacritics. For the input dataset, the feature variables are 137x236 grayscale images of Bengali characters. There are 168 types of consonant diacritic roots, 11 types of vowel diacritics, and 7 types of consonant diacritics, a total of 186 classes. 

We split the input dataset into training and test sets. The training set consists of 20,0840 data points. The test set’s size is the same, but can not be fully downloaded, only a few rows are provided to ensure consistency after submission. 

Empirical cases have shown that the convolutional neural network(CNN) is the most popular deep learning method conducting image classification. We use such methods with various architectures to classify the three constituents. 


