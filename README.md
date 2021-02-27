# Image Classifier with PyTorch
Built a convolutional neural network using PyTorch to compare with a multi-layer perceptron for image classification on CIFAR-10. Using the CIFAR-10 dataset with the default test and train partitions

writeup.pdf: The main report of the project

## Multilayer Perceptron
Implement the model from scratch including backpropogation and the gradient descent algorithm (SGD)

Run MLP_1.ipynb to load the data and run the model

## Convoluational Neural Network
Convolutional Neural Network built with PyTorch and torchvision. The initial CNN, inspired by LeNet-5, had two convolutional layers (with max pooling) followed by 3 fully connect layers

Run Convolutional_Neural_Network.ipynb to load the data and run the model

## Results
Compared the test and train performance of the above two models as a function of training epochs. Hyper-parameters such as the number of layersm number of units, and acivation functions were adjusted to test performance

<object data="writeup.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="writeup.pdf">
        <p>Please read writeup.pdf for full results and discussion. You can download the PDF to view it: <a href="writeup.pdf">Download PDF</a>.</p>
    </embed>
</object>
