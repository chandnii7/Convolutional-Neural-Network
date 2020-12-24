# Convolutional Neural Network

Program implements a basic convolutional neural network for classifying images of numbers in the MNIST dataset as either even or odd using GPU framework.
1. Contructing CNN: MNIST dataset is split into training, validation, and testing subsets with 55000, 10000, and 5000 examples, respectively. Digit labels are converted to even or odd using 0 and 1. Also plotting training and validation loss and accuracy as a function of epochs.
2. Hyper-parameters Tuning: Evaluating different variations of basic network by changing:
  * network architecture
  * receptive field
  * stride
  * optimizer
  * loss function
  * dropout
  * learning rate
  * number of epochs
  * weight initializers
  * batch normalization
  * layer normalization
3. Inference: Taking images with handwritten digits as input and performing image preprocessing like resizing, converting to grayscale and then to binary image using threshold. Classifying input images into odd/even labels.
<br/>

Program was implemented using Python, TensorFlow, Keras, and OpenCV. Refer the report for further implementation details and instructions to run the code:
<a href="https://github.com/chandnii7/ConvolutionalNeuralNetwork/blob/main/doc/Report_A3_Chandni_Patel.pdf">View Report</a>
<br/><br/>

### Results:
1. Contructed CNN for training:
<img src="https://github.com/chandnii7/ConvolutionalNeuralNetwork/blob/main/data/out1.jpg" height="400" width="500"/>
<br/>

2. After Hyper-parameter Tuning:
<img src="https://github.com/chandnii7/ConvolutionalNeuralNetwork/blob/main/data/out2.jpg" height="150" width="500"/>
<br/>

3. Inference with handwritten images:
<img src="https://github.com/chandnii7/ConvolutionalNeuralNetwork/blob/main/data/out3.jpg" height="700" width="500"/>
<br/>
