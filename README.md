# Convolutional Neural Network to Classify Images of Forest and Mountains

In this project, we will apply three different CNN models to a binary image classification problem using Keras. We will need to classify images of mountains and images of forests, treating mountains as the positive class (1) and the forest images as the negative class (0).

The problem is relatively difficult given the small sample size, with only about 350 observations per class. However, this sample size might be something that we can expect when prototyping an image classification problem/solution at work.

## Part 1: Pre-Trained Model
In this part, we will use a pre-trained model to classify the images. We will use transfer learning to use a pre-trained model and apply it to our problem. We will use the ResNet50 model for the binary classification task at hand.

## Part 2: Custom CNN Model
In this section, we will define a custom CNN model to classify the images. We will define and train a convolutional neural network using Keras and any architecture that has at least one convolutional and one pooling layer at the beginning of the network.

## Part 3: CNN with Data Augmentation
In this part, we will use data augmentation to improve the performance of our model. We will use the same custom CNN model from part 2, but we will apply data augmentation to the training set to improve the model's generalization.

## Part 4: Compare Model Results
In this last section, we will use TensorBoard to visualize the different possible models and compare their performance, as well as answer some questions about the different models' curves.

### Instructions
We can find the necessary data in the `./data` directory. The `./data/train` directory contains the training set, and the `./data/validation` directory contains the validation set.

