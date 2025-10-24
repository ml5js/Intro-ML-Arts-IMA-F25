# Convolutional Neural Network (CNN)

- [CNN Slides](https://docs.google.com/presentation/d/14EKV7ZIhk-3ioGCZPxp646e1264Dy0wOdFj2vhxUsWA/edit?usp=sharing)

## Session A: What is CNN?

### Objectives:

- Understand when and why you might train your own model from scratch versus use a pre-trained model or transfer learning.
- Learn about the Google "Quick, Draw!" dataset.
- Understand how ato work with image data for training your own model.

### Dataset
- [The Quick, Draw! Dataset](https://github.com/googlecreativelab/quickdraw-dataset) from Google Creative Lab.
- [The MNIST Dataset](https://yann.lecun.com/exdb/mnist/) by Yann LeCun el al.
- [Video tutorial: Replaying Drawings with node server](https://thecodingtrain.com/challenges/122-quick-draw)
- [Video tutorial: Replaying Drawings with Google Web API](https://thecodingtrain.com/challenges/122-quick-draw)
- [Preparing Data as Images for Doodle Classifer Part 1](https://youtu.be/gX7U6WA7Ffk)
- [Preparing Data as Images for Doodle Classifer Part 2](https://youtu.be/wMe6qcpD8jI)

### Examples

- [Displaying MNIST](https://editor.p5js.org/ima_ml/sketches/ndqnn8p3F)
- [Displaying Quick, Draw! 28x28 images](https://editor.p5js.org/ima_ml/sketches/wOO4nvwyw)

### Creative Quick, Draw! projects

- [Letter collages](http://frauzufall.de/en/2017/google-quick-draw/) by [Deborah Schmidt](http://frauzufall.de/)
- [Face tracking experiment](https://www.instagram.com/p/BUU8TuQD6_v/) by [Neil Mendoza](http://www.neilmendoza.com/)
- [Faces of Humanity](http://project.laboiteatortue.com/facesofhumanity/) by [Tortue](www.laboiteatortue.com)
- [Scribbling Speech](http://xinyue.de/scribbling-speech.html) by [Xinyue Yang](http://xinyue.de/)
- [How do you draw a circle?](https://qz.com/994486/the-way-you-draw-circles-says-a-lot-about-you/)

### Other Related Projects:

- [Machine Learning for Visualization by Ian Johnson](https://medium.com/@enjalot/machine-learning-for-visualization-927a9dff1cab)
- [MegaPixels: Faces](https://ahprojects.com/megapixels-glassroom/) curated by Tactical Tech, design and development by Adam Harvey
- [Watch What Neural Networks See](https://experiments.withgoogle.com/what-neural-nets-see) by Gene Kogan
- [Recognizing Human Facial Expressions With Machine Learning](https://thoughtworksarts.io/blog/recognizing-facial-expressions-machine-learning/) by Angelica Perez

## Session B: Doodle Classification

### Objectives

- Learn to train an image classifier (no convolutional layers) with ml5.js.
- Learn the distinction between different types of layers of a neural network, specifically "What is a convolutional layer?"
- Learn to feed the input of a graphics canvas into a machine learning model.

### Video Tutorials

- [ml5.js: What is Convolutional Neural Network Part 1 - Filters - video tutorial](https://youtu.be/qPKsVAI_W6M) by Daniel Shiffman.
- [ml5.js: What is Convolutional Neural Network Part 2 - Max Pooling - video tutorial](https://youtu.be/pRWq_mtuppU) by Daniel Shiffman.
- [ml5.js: Training a Neural Network with Pixels as Input - video tutorial](https://www.youtube.com/watch?v=UaKab6h9Z0I)
- [ml5.js: Training a Convolutional Neural Network for Image Classification - video tutorial](https://www.youtube.com/watch?v=hWurN0XhzLY)


### Convolutional Neural Nets

- [Original 1998 "LetNet5" paper: "Gradient-Based Learning Applied to Document Recognition"](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf) by Y. Lecun, L. Bottou, Y. Bengio, P. Haffner
- [How computers got shockingly good at recognizing images](https://arstechnica.com/science/2018/12/how-computers-got-shockingly-good-at-recognizing-images/) by Timothy B. Lee
- [Image Kernels Explained Visually](http://setosa.io/ev/image-kernels/) by Victor Powell
- [A visual and intuitive understanding of deep learning, CNNs](https://www.youtube.com/watch?v=Oqm9vsf_hvU) (0:00 - 9:40) by Octavio Good

### Examples

- [p5.js Convolution demo](https://editor.p5js.org/codingtrain/sketches/BN1lE-gyl)
- [p5.js Convolution demo -- max pooling](https://editor.p5js.org/codingtrain/sketches/GMRfsK7Wn)
- [Training a CNN model with `ml5.neuralNetwork()` and Google Quick, Draw! images](https://editor.p5js.org/yining/sketches/sMPv9-4qg)
- [Classifying Drawings with ml5's DoodleNet](https://editor.p5js.org/ima_ml/sketches/IbXlN6voN) (model trained by @yining1023)

### Demos [code](https://github.com/yining1023/machine-learning-for-the-web/tree/master/cnn)

- [Classifying Drawings with ml5's DoodleNet](https://editor.p5js.org/ima_ml/sketches/IbXlN6voN)
- [Doodle Classifier on 100 classes](https://yining1023.github.io/machine-learning-for-the-web/cnn/DoodleClassifier100/)
- [Doodle Classifier on 345 classes](https://yining1023.github.io/machine-learning-for-the-web/cnn/DoodleClassifier345/)
- [Doodle Classifier with KNN Classifier](https://yining1023.github.io/machine-learning-for-the-web/cnn/DoodleClassifier_KNN/)
- [Get Quickdraw Dataset](https://yining1023.github.io/machine-learning-for-the-web/cnn/GetQuickdrawData/)
- [Train your own Doodle Classifier](https://yining1023.github.io/machine-learning-for-the-web/cnn/TrainDoodleClassifier)
- [Train your own MNIST Classifier](https://yining1023.github.io/machine-learning-for-the-web/cnn/TrainMNIST)

### Supplemental Materials

- [An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) by Ujjwal Karn.
- [What Neural Networks See](https://experiments.withgoogle.com/what-neural-nets-see) by Gene Kogan.
- ["Gradient-Based Learning Applied to Document Recognition"](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf) by Y. LeCun, L. Bottou, Y. Bengio, P. Haffner.
- [How computers got shockingly good at recognizing images](https://arstechnica.com/science/2018/12/how-computers-got-shockingly-good-at-recognizing-images/) by Timothy B. Lee.
- [A visual and intuitive understanding of deep learning, CNNs](https://www.youtube.com/watch?v=Oqm9vsf_hvU) (0:00–9:40) by Octavio Good.
- [Recognizing Human Facial Expressions With Machine Learning](https://thoughtworksarts.io/blog/recognizing-facial-expressions-machine-learning/) by Angelica Perez.
- [Image Kernels Explained Visually](http://setosa.io/ev/image-kernels/) by Victor Powell.
- [Interactive Node-Link Visualizations of Convolutional Neural Networks](https://adamharley.com/nn_vis/) by Adam W. Harley.
- [Convolution Operation Demo](https://deeplizard.com/resource/pavq7noze2) by Deeplizard.

### Code Examples

#### Working with Datasets

- [Loading and Displaying Quick, Draw! Dataset](https://editor.p5js.org/jackbdu/sketches/UC_KqRr121)
- [Loading and Displaying MNIST Dataset](https://editor.p5js.org/jackbdu/sketches/E1Bb3KmLl)

#### Convolution Neural Network Layers

- [Convolutional Neural Network - Filter Demo](https://editor.p5js.org/codingtrain/sketches/BN1lE-gyl)
- [Convolutional Neural Network - Max Pooling Demo](https://editor.p5js.org/codingtrain/sketches/GMRfsK7Wn)

#### Training Image Classifiers

- [Training a Doodle Classifier with Convolutional Layers](https://editor.p5js.org/jackbdu/sketches/Id2cg4UQL)
- [Training a Handwritten Digit Classifier with Convolutional Layers](https://editor.p5js.org/jackbdu/sketches/ab7lfmRyH)
- [Training a Webcam Image Classifier with Convolutional Layers](https://editor.p5js.org/jackbdu/sketches/7Y6VDvUO6)
- [Doodle Classification with DoodleNet](https://editor.p5js.org/jackbdu/sketches/ts3fuRZGW)
- class: https://editor.p5js.org/yining/sketches/D0DuuxVMu

## Assignment
1. Reading: [An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) by Ujjwal Karn.
2. Coding: Reading line by line in the 4 "Training Image Classifiers" [examples](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/tree/main/08-cnn#training-image-classifiers), build on top of any of the 4 examples
3. Add a link to the post and your p5.js sketch on the [Assignment 8](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/wiki/Assignment-8) Wiki page.

