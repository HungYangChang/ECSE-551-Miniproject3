# Neural networks - Image classification
### Contributors: Jonathan Arsenault, Hung-Yang Chang, Anan Lu
### Mini-Project 3 - ECSE 551 McGill University

## Abstract
A convolutional neural network is the preferred machine learning model to perform image classification tasks. In this project, image classification is performed on a modified version of the Fashion-MNIST data set. To obtain the best performing model, several network architectures and optimization hyperparameters were considered. The best results were obtained using a VGG-16 network, which has a history of strong performance on image classification tasks. The weights were trained using the Adam optimization algorithm, with a decreasing learning rate to help convergence to a global minimum. The model submitted to the Kaggle competition achieved a preliminary accuracy of 97.9\%.

## Code.zip
The code.zip contains 4 files:
* 2 Colab notebook files - miniproject3.ipynb and miniproject3_supplemental.ipynb
  * miniproject3.ipynb contains the best hyperparameters we tried to get the highest performance.
  * miniproject3_supplemental.ipynb contains each step for choosing parameters. The details are shown in Section 4 Result in Report.pdf
* 1 Dataset file - model_trained_VGG_16_98percent.tar
  * model_trained_VGG_16_98percent.tar is the VGG-16 neural networks we trained to get 98% on Kaggle
* 1 ReadMe file - readme.md

## Report.pdf
All experiments are summarized in Report.pdf

## Code Usage - (Python 3.6, Colab)
1. Please Upload to python notebook (.ipynb file) to Colab
2. Select the required notebook and select "Run" in each code.
3. Note: you may not be able to run %cd '/content/gdrive/MyDrive/Colab/ECSE551Miniproject/Mini-Project3', if you wanna test, you need to connect to your own path and put training and testing dataset into that folder.
