# Handwritten-Digits-Classification-using-SVM


In this notebook, my objective is to explore the popular MNIST dataset and build an SVM model to classify handwritten digits. Here is a detailed description of the dataset.

Objective

We will develop a model using Support Vector Machine which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem.

We'll divide the analysis into the following parts:

* Data importing and understanding
* Data preparation for model building
* Building an SVM model - hyperparameter tuning, model evaluation etc.

Data Import

The data file digit_svm.csv contains gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The digits data set, (digit_svm.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

