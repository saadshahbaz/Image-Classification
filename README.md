# Image Classification


## Objective
The goal of this project is to develop models to classify the MNSIT
- The data model can be found in the <a href="https://www.kaggle.com/c/comp-551-fall-2021/data" target="_blank">Kaggle </a>
- Making a custom CNN architecture to acheive an accuracy >90%
## Dataset
- The Dataset is comprised of 60,000 trained images, with 30,000 labelled images and 30,000 unlabelled changes. <br>
- The Dataset is comprised of 15,000 test images.<br>
- Each image has dimensions of 56 x 56 and comprises of two characters: <br>
     1. `One Digits (from numbers 0-9)`<br>
     2. `One English alphabet (26 alphabets)`<br>
- <img width="1176" alt="MNIST" src="https://user-images.githubusercontent.com/59991041/151294243-93ef0e0a-4e83-4026-93a4-14d4093213e2.png">

## CNN
Our model uses:
1. 9 convolutional <br>
2. 1 flattening <br>
3. 3 fully connected layers <br>

Each layer, except the final layer, use ReLU activation function and include batch normalization and some max pooling

## Code

The code can be found in `project/src`

## Accuracy

- Reached a training accuracy of <b> 93.8% </b> and a test accuracy of <b> 94.08% </b>. 
- Received an accuracy of <b> 94.84% </b> on Kaggle.

## Report

Here is a detailed report for the models implemented: <a href="https://github.com/saadshahbaz/Image-Classification/blob/main/Comp551_Project3.pdf" target="_blank"> Multi-label Classification of Image Data </a>



<br><br><br>

#### Please note that all the code written in the files is for an assignment, and all rights belongs to me. Copying or using the code for an assignment is not allowed and I take no responsibility for any plagiarism or any other issues that you might run into.

