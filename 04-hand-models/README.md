# Hand Models

[Slides](https://docs.google.com/presentation/d/1RieL21CU8o3UqbWmM0tehU8WgxqwqH9alXMbA0gZk3g/edit?usp=sharing)

## Objectives

- Learn about TensorFlow Hand Pose Detection model and how it works.
- Learn to work with ml5.handPose.
- Learn to work with 3D graphics in p5.js WEBGL mode.

## Lecture Notes

### Tools

- [ml5.handPose Reference](https://docs.ml5js.org/#/reference/handpose)
  - [ml5.handPose Souce Code](https://github.com/ml5js/ml5-next-gen/tree/main/src/HandPose)
  - [TensorFlow.js Hand Pose Detection Source Code](https://github.com/tensorflow/tfjs-models/tree/master/hand-pose-detection)
  - [Hand Detection/Tracking Model Card](https://drive.google.com/file/d/1sv4sSb9BSNVZhLzxXJ0jBv9DqD-4jnAz/)

### Related Projects

- [Keyboard](https://experiments.withgoogle.com/keyboard) by Use All Five & Google Creative Lab.
- [Fingerspelling](https://www.hellomonday.com/work/fingerspelling) by Hello Monday.
- [Projection Mapping](https://www.instagram.com/p/CrLLNzGLcoA/) by Nahuel Gerth.

#### Music
- [Melody Painter with HandPose](https://www.instagram.com/p/C4WozrtsZ4r/) by Jack B. Du. [ [Live Demo](https://editor.p5js.org/jackbdu/full/jIvzImJMb) ]

#### Playful

- [Finger Talk](https://www.media.mit.edu/projects/finger-talk/overview/) by Future Sketches.
- [Look At You](https://by.alan.ooo/Project+Portfolio/Code/Look+At+You!!!) by Alan Ren & Kyrie Yang.
- [Bubbles](https://www.instagram.com/p/C6S5BHPCGu3/) by Nahuel Gerth.
- [Finger Numerals](https://www.instagram.com/p/CsBMOvUL4CP/) by Nahuel Gerth.

### Code Examples

#### In class examples

- [HandPose - pinch painting](https://editor.p5js.org/ima_ml/sketches/v1x7MSdLW)
- Woooooow: https://editor.p5js.org/yining/sketches/uiG-8dfi8

#### Core Functionalities

- [HandPose - Single Image](https://editor.p5js.org/ml5/sketches/8VK_l3XwE)
- [HandPose - Keypoints](https://editor.p5js.org/ml5/sketches/QGH3dwJ1A)
- [HandPose - Keypoints 3D](https://editor.p5js.org/jackbdu/sketches/DZoGg02Sx)
- [HandPose - Parts](https://editor.p5js.org/ml5/sketches/DNbSiIYKB)
- [HandPose - Detect Start and Stop](https://editor.p5js.org/ml5/sketches/W9vFFT5RM)
- Training hand pose model
  - Hand pose tracking + KNN Classification, [p5 web editor code](https://editor.p5js.org/yining/sketches/uUwg0z9Z5), [demo video](https://www.loom.com/share/f81cf908e5b7404ba0071902019d67c2)
  - Hand pose tracking + Neural Network, [demo video](https://www.loom.com/share/420fa5941dea411491af817011622c86)
    - [Collect data](https://editor.p5js.org/yining/sketches/dCoPm-Opb)
    - [Train the model](https://editor.p5js.org/yining/sketches/IrBFfXbSF)
    - [Run the model](https://editor.p5js.org/yining/sketches/6cFF9-L-Z)

#### Creative Applications

- [HandPose - Particles](https://editor.p5js.org/jackbdu/sketches/4Pd5XgWtC) by Jack Du
- [HandPose - Quadrilateral](https://editor.p5js.org/jackbdu/sketches/s3uqE-9fA) by Jack Du
- [HandPose - Quadrilateral with Texture](https://editor.p5js.org/jackbdu/sketches/JwMBQyES3) by Jack Du

### Technical Blog Posts

- [On-Device, Real-Time Hand Tracking with MediaPipe](https://research.google/blog/on-device-real-time-hand-tracking-with-mediapipe/) by Valentin Bazarevsky and Fan Zhang.
- [3D Hand Pose with MediaPipe and TensorFlow.js](https://blog.tensorflow.org/2021/11/3D-handpose.html) by Valentin Bazarevsky, Ivan Grishchenko, Eduard Gabriel Bazavan, Andrei Zanfir, Mihai Zanfir, Jiuqiang Tang, Jason Mayes, Ahmed Sabie.

### Video Tutorials

## Assignment 4

1. Research and find a project (experiments, websites, art installations, games, etc) that utilizes machine learning in a creative way. Consider the following:
   - What type of machine learning models did the creator use?
   - What data might have been used to train the machine learning model?
   - Why did the creator of the project choose to use this machine learning model?
2. Using HandPose, following the examples above and the [ml5.js documentation](https://docs.ml5js.org/), experiment with controlling elements of a p5.js sketch (color, geometry, sound, text, etc) with the output of the model. Try to create an interaction that is surprising or one that is inspired by the project you find.
3. Document your research, your response, and your p5.js sketch in a blog post. Add a link to the post and your p5.js sketch on the [Assignment 4 Wiki page](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/wiki/Assignment-4). In your blog post, include visual documentation such as a recorded screen capture / video / GIFs of your sketch.
