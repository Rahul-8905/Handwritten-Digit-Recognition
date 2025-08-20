# Handwritten Digit Recognition
The Handwritten Digit Recognition is a CNN (Convolutional Neural Network) trained to recognize handwritten numbers, using the MNIST dataset. The network is built using Keras, which is a high-level API incorporated in Tensorflow (Google's deep learning API). I have downloaded the entire MNIST dataset (on handwritten digits) as .jpg files, so that the network can be more "prepared" to analyze our hand-drawn digits, as opposed to just trianing it straight from the compressed MNSIT dataset. 

# How does this work?
First, the program reads all images, which is classified into 10 different folders (about 37000 images in total). Then, the network trains itself. After the network is trained, you can test the network by drawing your number in a Tkinter window. When you finish drawing, Tkinter will create a temporary .jpg file, and then the network will predict your number based on that temporary .jpg file. 




