# Neural Network Scratch

	Implement a feed-forward neural network with back-propagation from scratch. Using numpy and scikit-learn low-level functionality, but not their pre-built implementations of grad descent etc.

## Testing on a simple dataset

	Build and train a neural net with one hidden layer, and see how well you can perform on a held-out portion of it

## Testing on a challenging dataset

1. Image recognition is a task now tackled with ML, that was considered “very hard” not long ago
2. We will use the CIFAR-10 dataset of 10 images: https://www.cs.toronto.edu/~kriz/cifar.html
3. Each image is of size 32x32, with 3 colour channels (Red, Green, Blue): 
4. To make it suitable for your shallow neural net, use just 1 of the colour channels or average all three to convert the images to greyscale; then convert it to vector of 1024 floats
5. There are 50,000 training images and 10,000 testing images: you can select smaller random subsets of these, to speed up training/testing (e.g use just 1 of the 6 batches, or part of a batch)
6. Our architecture will have 1 hidden layer (larger than the one for the simple dataset) and 1 output node
7. We will distinguish between 2 images only.

## Deep Learning

1. In the part 4 must be done on your own.
2. Initially, we developed a standard feed-forward neural net with 1 hidden layer
3. We will pick some enhancement that is characteristic of deep learning and implement the enhancement; 
5. Test how well it works relative to previous NN.