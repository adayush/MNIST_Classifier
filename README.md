
# Handwritten Digit Recognition
<br>

<h2>Aim:</h2> To make a convolution neural network to recognise handwritten digits by training the model on MNIST dataset available in keras.
<br>
<h2>MNIST DATASET:</h2>The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset. It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.
<br>
<h2>CNN MODEL OVERVIEW:</h2>
<br>⚈ Model contains Conv2D, MaxPooling2D, Flatten and Dropout layers combination.
<br>⚈ Model is trained for 5 epochs.
<br>⚈ Categorical_crossentropy is loss function and adam is used for optimization.
<br>⚈ Model gives 98.90% accuracy.
<h2>For Deployment:</h2>Save model using tensorflowjs converters as json file and weight as .h5 file.Use Tensorflow.js to load model and predict in javascript file