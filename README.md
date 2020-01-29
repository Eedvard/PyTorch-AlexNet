# PyTorch-AlexNet

This is a very basic implementation of the AlexNet convolutional neural network in PyTorch. The original research paper is available here: https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf.

## Network structure

AlexNet consists of five convolutional layers and three fully connected layers. The dropouts are right before the first two fully connected layers.

## Regularization techniques

To prevent overfitting and improve the model accuracy following regularization methods were implemented for the model:

1. Batch normalization
2. Random horizontal flip
3. Dropout
4. Changing learning rate

## Dataset

The dataset used to test the network is Fashion MNIST. Because the images are greyscale instead of RGB the network structure had to be altered slightly.

## Results

**Figure 1** Training and validation accuracies during the training process
![Accuracy](https://github.com/Eedvard/PyTorch-AlexNet/tree/master/img/accuracy.png)

**Figure 2** Training and validation losses during the training process
![Loss](https://github.com/Eedvard/PyTorch-AlexNet/tree/master/img/loss.png)

