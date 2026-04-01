# neural-networks-generative-ai-assignment
**Course:** Introduction to Machine Learning  
**Instructor:** Becky Deitenbeck
**Student:** Luis Lopez Martinez
**Date:** 3/31/2026

## Assignment Overview

Building a simple Neural Network and experimenting with data augmentation.

1. Part A
   - Using MNIST (handwritten digits) dataset
   - Used PyTorch to define a feedforward neural network (MLP)
   - included 2 hidden layers
     
2. Part B
   - Data augmentation using Keras’ ImageDataGenerator
   - Retrained using augmented
   - compared test accuracy.
  
## Reflection
At first I had some trouble with shape of the data making sure I knew what data I had to divide by 2555 at first I accidentally just divided y_train by 255 so the model had very bad accuracy about .10 so I when went rhogut and realized I got rid of that. Next I used hands on machine learning book to train the model with 2 hidden layers the first had 300 the second had 100 using ReLU and softmax for the output layer and 30 epochs. the model had an accuracy of .92 and loss of .22 when evaluating the model the accuracy was .88 when I changed the neurons for the first layer to 110, second layer to 50 and 6 epochs the model had .86 accuracy. But when evaluated the model had an accuracy of .85 Which is not that far off from the 30 epochs with 300 neurons in the first layer. Which means the model was trying to tweak very specifically to the information when using more epochs when 6 would do the about the same. 

Real life applications
These techniques could be used in computer vision, a real-life application that I have see is charging for the amount of time you spend in a parking garage. There are cameras that can detect your license plate and charge you when you head out. With neural networks computer vision can get better at predicting the cars license plate letters and numbers.


## How to Run

1. Clone this repository or download the notebook.  
2. Install requirements:
***pip for python or conda when using anaconda***  
   - pip install seaborn 
   - pip install pandas
   - pip install numpy 
   - pip install sklearn
   - pip install matplotlib.pyplot
   - pip install tensorflow 

4. Open the notebook in Jupyter Notebook or Environment that can open a .ipynb file 

