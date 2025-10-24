# Training a Neural Network

[Slides](https://docs.google.com/presentation/d/1VfD-AfsOtljmxXpR_1hj_M7yOC0zwSRRb-9HfYj4oNs/edit?usp=sharing)

## Objectives

- Learn steps to construct a "vanilla" neural network and train a classification model with ml5.js.
- Understand Neural Network architecture.
  - What is a perceptron?
  - What is a multi-layered perceptron?
  - What are activation functions?
- Understand the terminology of the training process.
  - Training
  - Learning rate
  - [Epochs](https://docs.ml5js.org/#/learn/ml5-glossary?id=epochs)
  - [Batch size](https://docs.ml5js.org/#/learn/ml5-glossary?id=batch-size)
  - Loss
- Understand the difference between training and inference.
- Understand the distinction between different types of layers in a neural network.
  - What is a convolutional layer?
  - What is a pooling layer?
- Learn to train an image classifier with ml5.js, with and without convolutional layers.
- Revisit and examine the concepts of classification and regression as applied to real-time interaction.

## Tools

- [ml5.neuralNetwork Reference](https://docs.ml5js.org/#/reference/neural-network)
  - [ml5.neuralNetwork Source Code](https://github.com/ml5js/ml5-next-gen/tree/main/src/NeuralNetwork)
  - [TensorFlow.js Source Code](https://github.com/tensorflow/tfjs)

## Artificial Neural Networks

### Code Examples

- [NeuralNetwork - Color Classifier](https://editor.p5js.org/ml5/sketches/eGHBdmCLe)
- [NeuralNetwork - Mouse Gesture](https://editor.p5js.org/ml5/sketches/FdXAgrA3N)
- [NeuralNetwork - Train and Save](https://editor.p5js.org/ml5/sketches/rR51vvi-u)
- [NeuralNetwork - Load Model](https://editor.p5js.org/yining/sketches/XHGgqSLNu)
- Class: https://editor.p5js.org/yining/sketches/GjbZopuEZ

### Supplemental Materials

- [Chapter 10: Neural Network, Nature of Code](https://natureofcode.com/book/chapter-10-neural-networks/) by Daniel Shiffman.
- [But what _is_ a Neural Network?](https://youtu.be/aircAruvnKk?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by 3Blue1Brown.
- [The 7 steps of machine learning](https://www.youtube.com/watch?v=nKW8Ndu7Mjw) from Google Cloud Tech.

### Video Tutorials

🚨 _Note: ml5.js tutorials below were taught using an older version of ml5.js, refer to the [ml5.js Resources Wiki page](https://github.com/jackbdu/Intro-ML-Arts-IMA-Summer24/wiki/ml5.js-Resources) for more information._ 🚨

#### Neural Network Concepts

- [Neural Networks: Perceptron (2 parts) - video tutorial](https://thecodingtrain.com/tracks/neural-networks/neural-networks/2-perceptron-part-1)
- [Neural Networks: Multilayer Perceptron (2 parts) - video tutorial](https://thecodingtrain.com/tracks/neural-networks/neural-networks/4-multilayer-perceptron-part-1).
- [Neural Networks: Matrix Math](https://thecodingtrain.com/tracks/neural-networks/neural-networks/6-matrix-math-basics) by Daniel Shiffman.

#### ml5.js Neural Network

- [ml5.js: Train Your Own Neural Network - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/1-train-the-model)
- [ml5.js: Save Neural Network Training Data - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/2-save-data)
- [ml5.js: Save Neural Network Model - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/3-save-model)
- [ml5: Neural Network Regression - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/4-regression)
- [ml5.js: Pose Classification with PoseNet and ml5.neuralNetwork() - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-posenet/2-pose-classifier)
- [ml5.js: Pose Regression with PoseNet and ml5.neuralNetwork() - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-posenet/3-pose-regression)

## Assignment 7
1. Reading:
   - [Chapter 10: Neural Network, Nature of Code](https://natureofcode.com/book/chapter-10-neural-networks/) by Daniel Shiffman.
   - [But what _is_ a Neural Network?](https://youtu.be/aircAruvnKk?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by 3Blue1Brown.
2. Create your own p5+ml5 sketch that trains a Neural Network with real-time interactive data.
   This can be a prototype of the aforementioned idea or a simple exercise where you run this week's code examples with your own data. Here are some exercise suggestions:

   Try to invent more elegant and intuitive interaction for collecting real-time data beyond clicking buttons?
   What other real-time inputs might you consider beyond mouse position, image pixels, or face/pose/hand tracking? Could you use real-time sensor data?
   What other real-time outputs might you consider beyond color or sound modulation? Could the output be a physical computing device? Multiple outputs like R,G,B values? [Code examples](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/tree/main/07-neural-networks#code-examples)
    - Can you add more keypoints from the hand to the data collection? (All the keypoints?)
    - Can you add more classification categories?
    - Can you create an interface for training and showing the results of model's prediction?
    - Can you turn this into a regression model?
3. Add a link to the post and your p5.js sketch on the [Assignment 7](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/wiki/Assignment-7) Wiki page. 
