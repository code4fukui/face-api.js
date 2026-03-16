# face-api.js

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

**JavaScript face recognition API for the browser and nodejs implemented on top of tensorflow.js core ([tensorflow/tfjs-core](https://github.com/tensorflow/tfjs))**

## Demo
[Click here for Live Demos!](https://justadudewhohacks.github.io/face-api.js/)

## Features
- Face Detection
- Face Landmark Detection
- Face Expression Recognition
- Age Estimation and Gender Recognition

## Requirements
- [face-api.js](https://github.com/justadudewhohacks/face-api.js) library
- TensorFlow.js (included in the library)

## Usage

### For the Browser
Include the latest script from [dist/face-api.js](https://github.com/justadudewhohacks/face-api.js/tree/master/dist).
Or install via npm:
```
npm i face-api.js
```

### For Node.js
Install required dependencies:
```
npm i face-api.js canvas @tensorflow/tfjs-node
```
Then set up the environment:
```javascript
import '@tensorflow/tfjs-node';
import * as canvas from 'canvas';
import * as faceapi from 'face-api.js';

const { Canvas, Image, ImageData } = canvas;
faceapi.env.monkeyPatch({ Canvas, Image, ImageData });
```

## API Documentation
[View the API Documentation](https://justadudewhohacks.github.io/face-api.js/docs/globals.html)

## License
MIT License — see [LICENSE](LICENSE).