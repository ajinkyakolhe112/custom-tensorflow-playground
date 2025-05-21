# TensorFlow Neural Network Playground

This is a web-based neural network playground that allows you to experiment with neural networks directly in your browser. It's a fork of the original [TensorFlow Playground](https://github.com/tensorflow/playground) with some modifications.

## Features

- Interactive neural network visualization
- Multiple datasets for classification and regression
- Adjustable network architecture
- Real-time training visualization
- Various activation functions and regularization options

## Live Demo

Visit the live demo at: https://ajinkyak.github.io/custom-tensorflow-playground

## Local Development

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/ajinkyak/custom-tensorflow-playground.git
cd custom-tensorflow-playground
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Building from Source

If you want to modify the code:

1. Install dependencies:
```bash
npm install
```

2. Build the project:
```bash
npm run build
```

## GitHub Pages Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. The deployment process:

1. Builds the project using `npm run build`
2. Deploys the contents of the `dist` directory to the `gh-pages` branch
3. The site is then available at https://ajinkyak.github.io/custom-tensorflow-playground

To trigger a new deployment, simply push your changes to the main branch.

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Acknowledgments

- Original work by Daniel Smilkov and Shan Carter
- Based on Andrej Karpathy's convnet.js demo
- Inspired by Chris Olah's articles about neural networks
