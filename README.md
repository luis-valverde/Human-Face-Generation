# Human Face Generation

## Table Of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Neccessary Files](#neccessary-files)
- [How to Run](#how-to-run)

## Introduction

This repository contains all my work for the Udacity's Deep Learning Nanodegree Program.

The goal in this project was to perform a Deep Generative Adversarial Network (DCGAN) to generate new images of faces
that look as realistic as possible.

To accomplish this, I implemented DCGAN model adversarial networks (discriminator and generator) with PyTorch tracking
their losses to avoid overfitting. Then, initialized hyperparameters (learning rate, epochs) and network weights to
help the model to converge. Finally, I trained the DCGAN network tracking the generator and discriminator losses to
avoid overfitting.

## Project Overview

Learn to understand Generative Adversarial Networks in this project and implement a Deep Convolutional GAN. This
DCGAN is made of a pair of multi-layer neural networks that compete against each other until one learns to generate
realistic images of faces.

In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to
generate new images of faces that look as realistic as possible.

## Requirements

This project uses the following software and Python libraries:

- [Python](https://www.python.org/downloads/release/python-364/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn (v0.17)](https://scikit-learn.org/0.17/install.html)
- [Matplotlib](https://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the
[Anaconda](https://www.anaconda.com/distribution/) distribution of Python, which already has the above packages and
more included.

## Neccessary Files

This repository contains three files needed to solve the project.

1. **dlnd_face_generation.ipynb:** This is the main file where I performed the work on the project.
2. **dlnd_face_generation.html:** This is an HTML report of the Jupyter notebook.
3. **assets/processed_face_data.png:** Example of human faces.
4. **problem_unittests.py:** Unit tests to verify correct functionality of the algorithms created.

## How to Run

In the Terminal or Command Prompt, navigate to the folder on your machine where you've put the project files, and then
use the command:

```bash
jupyter notebook dlnd_face_generation.ipynb
```

 to open up a browser window or tab to work with your notebook.
 Alternatively, you can use the command:

 ```bash
jupyter notebook
```

or

```bash
ipython notebook
```

and navigate to the notebook file (dlnd_face_generation.ipynb) in the browser window that opens.
