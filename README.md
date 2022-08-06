# Sign-Language-recognition-using-CNN

# Overview

- Build neural network conveniently.
- Configure with different regularization methods: Dropout, l1 or l2 regulation.
- Fine tune pre-trained model to build your own projects.

# Dataset
This dataset is provided by our current research project, which utilize 20 kHz acoustic sensing to sense ASL gestures. All the 10 ASL words perform by 5 subjects. All images are generated by using the short-time Fourier transform (STFT) to calculate a spectrogram as the feature representation of the reflected near-ultrasound waves. Based on the Doppler effect, sign language gestures, including both hands and arms, will cause phase and frequency changes of the reflected sonic wave. 

This dataset has a training set of 5,000 examples, and a test set of 1,000 examples.

## We build a Convolutional Neural Network with 2 or 3 hidden layers without regularization methods, which includes Conv2D layer, activation Layer. We calculate L1 and L2 losses to trian the network and get the accuracy on the dataset.

## Further, we took the pretrained ResNet50 model and manipulated it to create a CNN model.
