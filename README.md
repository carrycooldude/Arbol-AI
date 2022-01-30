![Cover Image](media/cover.png)

# Arbol-AI🌱 


This is a web application🌐 which could help easily diagnose diseases in plants
🌱 using Machine Learning all on the web, powered by TensorFlow JS. 

***You can use and test the latest web app from below 👇***

[![Launch Example](https://img.shields.io/badge/launch-example-red?style=for-the-badge&logo=google-chrome)](http://www.plant-ai.tech/)

## About 🔮

- Creates a TensorFlow Model for identifying plant diseases
- Creates optimized TensorFlow JS Models
- Uses TensorFlow JS to perform inferences on-device
- Creates a fully functional web app using React
- Exposes a hosted API built with TensorFlow Serving for inferences from the TensorFlow Model

## About the Notebooks

### [`plant-diseases-training.ipynb`](notebooks/plant-diseases-training.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xc0vTKL1sYSAmMO0yRyif6tlKOfF-5qx?usp=sharing)

This notebook contains the code to train a model on the [PlantVillage dataset](http://arxiv.org/abs/1511.08060)
to identify diseases from plant images. Here we provide a subset of our 
experiments on working with this data. Finally we export our model as a 
TensorFlow `SavedModel`.

## Run Locally

To get up and running with this web-app, run the following commands, make sure 
you have [Node.js](http://nodejs.org/) installed. This runs the app in 
development mode:

```sh
git clone https://github.com/carrycooldude/Arbol-AI.git # or clone your own fork
cd Arbol-AI
npm install
npm start
```

<!-- markdown-link-check-disable-next-line -->
Your app should now be running on [localhost:3000](http://localhost:3000) :rocket:.

## Lint ✅
This project uses [***GitHub Super Linter***](https://github.com/github/super-linter) which is Combination of multiple linters to install as a GitHub Action.

Following Linters are used internally by super linter (enabled for this project):
- JavaScript: [eslint](https://eslint.org/)
- CSS: [stylelint](https://stylelint.io/)
- HTML: [HTMLHint](https://github.com/htmlhint/HTMLHint)
- JSON: [jsonlint](https://github.com/zaach/jsonlint)
- YAML: [YamlLint](https://github.com/adrienverge/yamllint)

## Contributors

- [Kartikey Rawat](https://github.com/carrycooldude)
- [Abhishek Agrawal](https://github.com/fazer1929)
- [Abhay Chaudhary](https://github.com/abhayac15)


