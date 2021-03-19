# Image Classifier with PyTorch
Built a convolutional neural network using PyTorch to compare with a multi-layer perceptron for image classification on CIFAR-10. Using the CIFAR-10 dataset with the default test and train partitions.

The CIFAR-10 dataset consists of 60,000 32x32 colour images (3x32x32) in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The training set is split into 5 batches, each with 10,000 images while the testing set is one batch of 10,000 images. The classes of images are split evenly among the batches.

The CIFAR10 dataset classes include: 'airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', and 'truck'. Each class is exclusive and there is no overlap between classes

writeup.pdf: The main report of the project

## Multilayer Perceptron
Implement the model from scratch including backpropogation and the gradient descent algorithm (SGD)

Run MLP_1.ipynb to load the data and run the model

## Convoluational Neural Network
Convolutional Neural Network built with PyTorch and torchvision. The initial CNN, inspired by LeNet-5, had two convolutional layers (with max pooling) followed by 3 fully connect layers

Run Convolutional_Neural_Network.ipynb to load the data and run the model

## Results
Compared the test and train performance of the above two models as a function of training epoch. Hyper-parameters such as the number of layers, number of units, and acivation functions were adjusted to test performance

<object data="writeup.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="writeup.pdf">
        <p>Please read writeup.pdf for full results and discussion. You can download the PDF to view it: <a href="writeup.pdf">Download PDF</a>.</p>
    </embed>
</object>
