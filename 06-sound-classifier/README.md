# Sound Classifiers

## Objectives
- Learn to use sound classifiers in ml5.js
- Understand sound classification models and their applications
- Build interactive projects with real-time sound recognition

## Resources
- [ml5.js SoundClassifier Reference](https://docs.ml5js.org/#/reference/sound-classifier)
- [p5.js Sound Library](https://p5js.org/reference/#/libraries/p5.sound)
- [The Coding Train - Sound Classification](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/sound-classification)

## Sound Classification with ml5.js

Sound classification is the process of analyzing audio input and categorizing it into predefined classes. ml5.js provides pre-trained models that can recognize various sounds in real-time.

### Available Models

#### 1. SpeechCommands18w
A model trained to recognize 18 different spoken words:
- "zero", "one", "two", "three", "four", "five", "six", "seven", "eight", "nine"
- "up", "down", "left", "right"
- "go", "stop", "yes", "no"

#### 2. Custom Models
You can also train and use your own sound classification models using Teachable Machine.

## Basic Example

### HTML Setup
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sound Classification</title>
  <script src="https://cdn.jsdelivr.net/npm/p5@1.9.2/lib/p5.min.js"></script>
  <script src="https://unpkg.com/ml5@latest/dist/ml5.min.js"></script>
</head>
<body>
  <script src="sketch.js"></script>
</body>
</html>
```

### JavaScript (sketch.js)
```javascript
let classifier;
let label = 'Listening...';
let confidence = 0;

function preload() {
  // Load the SpeechCommands18w model
  classifier = ml5.soundClassifier('SpeechCommands18w');
}

function setup() {
  createCanvas(640, 480);
  // Start classifying
  classifier.classify(gotResult);
}

function draw() {
  background(0);
  
  // Display the current label
  fill(255);
  textSize(32);
  textAlign(CENTER, CENTER);
  text(label, width / 2, height / 2);
  
  // Display confidence
  textSize(16);
  text('Confidence: ' + nf(confidence, 0, 2), width / 2, height / 2 + 50);
}

function gotResult(error, results) {
  if (error) {
    console.error(error);
    return;
  }
  
  // The results are in an array ordered by confidence
  label = results[0].label;
  confidence = results[0].confidence;
}
```

## Key Concepts

### 1. Model Loading
```javascript
// Load a pre-trained model
classifier = ml5.soundClassifier('SpeechCommands18w');

// Or load a custom model from Teachable Machine
classifier = ml5.soundClassifier('path/to/model/model.json');
```

### 2. Classification Options
```javascript
const options = {
  probabilityThreshold: 0.8  // Only return results above 80% confidence
};
classifier = ml5.soundClassifier('SpeechCommands18w', options);
```

### 3. Getting Results
```javascript
// Continuous classification
classifier.classify(gotResult);

// Single classification
classifier.classify((error, results) => {
  // Handle results
});
```

## Project Ideas

### Beginner
1. **Voice-Controlled Game**: Create a simple game controlled by voice commands (up, down, left, right)
2. **Number Recognizer**: Display the spoken number visually on canvas
3. **Sound Visualizer**: Create different visual effects based on recognized sounds

### Intermediate
4. **Voice-Controlled Drawing**: Draw different shapes or colors based on voice commands
5. **Musical Instrument Classifier**: Identify different instrument sounds
6. **Ambient Sound Monitor**: Classify environmental sounds (traffic, nature, etc.)

### Advanced
7. **Multi-Modal Interface**: Combine sound, gesture, and face detection
8. **Sound-Based Accessibility Tool**: Create interfaces for users with mobility limitations
9. **Custom Sound Trainer**: Build an interface to train custom sound models

## Using Teachable Machine

You can train custom sound models using [Teachable Machine](https://teachablemachine.withgoogle.com/):

1. Go to Teachable Machine and select "Audio Project"
2. Record samples for each class you want to recognize
3. Train your model
4. Export as "TensorFlow.js"
5. Upload the model files and use in ml5.js:

```javascript
const modelURL = 'https://your-domain.com/model/';
classifier = ml5.soundClassifier(modelURL + 'model.json', modelReady);
```

## Tips & Best Practices

1. **Microphone Permissions**: Always request microphone access and handle permission errors gracefully
2. **Background Noise**: Consider the environment - background noise can affect accuracy
3. **Confidence Threshold**: Set an appropriate confidence threshold to filter out uncertain predictions
4. **User Feedback**: Provide clear visual/audio feedback when sounds are recognized
5. **Testing**: Test your application in different acoustic environments

## Common Issues

### Microphone Not Working
- Check browser permissions for microphone access
- Ensure you're running on HTTPS or localhost
- Test with the browser's built-in audio recorder first

### Low Accuracy
- Increase the `probabilityThreshold` to only show high-confidence results
- Train a custom model with more examples
- Reduce background noise
- Speak/make sounds more clearly and consistently

## Exercises

1. **Basic Classification**: Display all 18 commands from SpeechCommands18w
2. **Voice Game**: Create a simple game controlled entirely by voice
3. **Sound Visualizer**: Map different sounds to different visual effects
4. **Custom Classifier**: Train your own model to recognize 3-5 custom sounds
5. **Multi-Class**: Combine sound classification with other ml5 models (pose, face, etc.)

## Assignment Ideas

- Create an interactive art piece that responds to voice or sound
- Build an accessibility tool using voice commands
- Design a sound-based game or music application
- Train a custom model to classify sounds relevant to your interests

## Additional Resources

- [Web Audio API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [Teachable Machine](https://teachablemachine.withgoogle.com/)
- [ml5.js Examples](https://examples.ml5js.org/)
- [The Coding Train Tutorials](https://thecodingtrain.com/)

## Next Steps

After completing this module, you'll be ready to:
- Combine sound classification with other ML models
- Create multi-modal interactive experiences
- Build accessible interfaces using voice control
- Train and deploy custom sound classification models

