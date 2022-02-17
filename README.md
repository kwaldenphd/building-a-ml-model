# Building Your Own Machine Learning Model in Python

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

## Lab Goals

This lab provides a framework for building a basic machine learning model in Python. It covers the basic steps of a machine learning workflow and provides additional resources for building a model.

# Table of Contents

- [Overview](#overview)
- [Option #1](#option-1)
  * [Resources](#resources)
- [Option #2](#option-2)
- [Option #3](#option-3)
- [Option #4](#option-4)
- [Lab Notebook Components](#lab-notebook-components)

# Overview

The previous lab included a brief discussion of the fundamentals of a machine learning workflow.

  * Step 1- identify the problem or question, think about options for answering or solving, and decide if machine learning will be a useful tool.

  * Step 2- identify and analyze available datasets to see if sufficient data is available to build a model

  * Step 3- transform the data into a tabular structure so it can be the input for a machine learning model

  * Step 4- train the model (or more accurately engage in an iterative process of training the model)

  * Step 5- evaluate the model to see if (and how effectively) it solves the original question/problem

  * Step 6- deploy the model

Our goal in this lab is for you to come up with a problem or question that can be answered via machine learning and build a model that responds to that question/problem.

Simple, right?

As you can imagine, this is an iterative process that takes TIME.

  * Time to determine the central problem or question, and figure out if machine learning is a good fit.

  * Time to figure out what data is needed to build a model, identify or collect that data, and wrangle it into a tabular structure.

  * Time to figure out what type of model is the best fit for the question/problem AS WELL AS the input data.

  * Time to train the model and evaluate the effectiveness of the model.

  * Time to figure out what the model has to say about your original question or problem.

  * In short, TIME.


Which is why we're spending two weeks on this lab and working collaboratively.

# Lab Options

There are a few different options for how you can approach this lab.

Lab notebook templates:
- [Jupyter Notebook](https://colab.research.google.com/drive/1Uen-hrgBbOLyGNYg0sjgeH-TFOUekqBk?usp=sharing)
- [Google Doc](https://docs.google.com/document/d/1-mG_8WLzM7cK8rjnsSOYJ-xbs0MoL-uxzXDWKD8cn6U/copy)

## Option #1

Use the steps outlined above and resources provided below to identify a problem/topic, relevant dataset, and build your own machine learning model.

This is the most open-ended and technically complex option.

### Resources

Starting with a method or concept's Wikipedia page can give you the broad strokes as well as links or citatations for additional resources.

Andreas C. Müller and Sarah Guide's accessible *Introduction to Machine learning With Python: A Guide for Data Scientists* (O'Reilly, 2017) is where I would start with additional research. 
- [Publisher website](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
- [Link to access via Google Drive](https://drive.google.com/file/d/1VHBuayX6PoZZrFaps-HLs3exXoLPSlSM/view?usp=sharing) (ND users only)
- [Code repository](https://github.com/amueller/introduction_to_ml_with_python)

Package documentation:
- [`NumPy`](https://numpy.org/install/)
- [`SciPy`](https://www.scipy.org/install.html)
- [`matplotlib`](https://matplotlib.org/3.3.3/users/installing.html)
- [`pandas`](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)

The [`scikit-learn` documentation](https://scikit-learn.org/stable/index.html) also has useful algorithm overviews, examples, and tutorials.

Another resource that includes Python machine learning tutorials:
- Lisa Tagliaferri and Brian Boucheron, [*Python Machine Learning Projects*](https://www.digitalocean.com/community/books/python-machine-learning-projects-a-digitalocean-ebook) (Digital Ocean, May 2019)

## Option #2

Read pages 94-114 from Meredith Broussard's 2018 book [*Artificial Unintelligence: How Computers Misunderstand the World*](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph004791189) (MIT Press). 

In this section of Chapter 7 "Machine Learning: The DL on the ML," Broussard outlines a machine learning workflow using data about Titanic passengers.

Follow the steps outlined in the chapter excerpt to build a machine learning classifier.

Chapter excerpt:
- [Access via Google Drive](https://drive.google.com/file/d/1sXJPcvk84SDB3QXCNWiKwL7AQ-gKcgh7/view?usp=sharing) (ND users only)
- [Link to electronic access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph004791189)

Jupyter notebook:
- [Link to Jupyter Notebook](https://colab.research.google.com/drive/1dJLBUyDvQZ7qGzsUxiVbegxZkDiDRMr4?usp=sharing)
  * SOURCE: Adapted from [Lauren F. Klein](https://lklein.com/)'s  [implementation of Broussard's exercise](https://github.com/laurenfklein/feminist-data-science/blob/master/notebooks/lab2-survival/lab2-survival-inclass.ipynb), developed for the Spring 2020 Emory University course [QTM 490 "Feminist Data Science"](https://github.com/laurenfklein/feminist-data-science).

You'll also need two data files for  this option: `text.csv` and `train.csv`
- GitHub
  * Test: https://raw.githubusercontent.com/kwaldenphd/building-a-ml-model/main/data/test.csv
  * Train: https://raw.githubusercontent.com/kwaldenphd/building-a-ml-model/main/data/train.csv
- Google Drive
  * [Test](https://drive.google.com/file/d/1YIKOH2upzQQUAiIqLwIqk5xdddetDsfR/view?usp=sharing)
  * [Train](https://drive.google.com/file/d/1CcHmC4hvVrLeM8AeSHmxCJSUvdXofGN_/view?usp=sharing)

This is a guided (i.e. not open-ended), moderately complex option.

## Option #3

Work through the *Digital Ocean* "How to Build a Machine Learning Classifier in Python With Scikit-learn" tutorial.

Michelle Morales, "[How to Build a Machine Learning Classifier in Python With Scikit-learn](https://www.digitalocean.com/community/tutorials/how-to-build-a-machine-learning-classifier-in-python-with-scikit-learn)" *Digital Ocean* (24 March 2019).
- [Link to Jupyter Notebook](https://colab.research.google.com/drive/1W0Onsdkmu_s3rGuXnm5PEWtPLlsONsXP?usp=sharing)

This is a guided (i.e. not open-ended), moderately complex option.

## Option #4

Use Google's "[Teachable Machine](https://teachablemachine.withgoogle.com/)" project website to assemble a collection of objects/data and build a machine learning model.

The Teachable Machine website provides tutorials and a workflow overview, so there is structure, but the type of model and content used to build the model is open-ended. 

This option does not involve any programming and runs entirely through the web-based interface.

# Lab Notebook Components

Lab notebook templates:
- [Jupyter Notebook](https://colab.research.google.com/drive/1Uen-hrgBbOLyGNYg0sjgeH-TFOUekqBk?usp=sharing)
- [Google Doc](https://docs.google.com/document/d/1-mG_8WLzM7cK8rjnsSOYJ-xbs0MoL-uxzXDWKD8cn6U/copy)

For all of these options, the lab notebook consists of a narrative that documents and describes your experience working through this lab. 
- What option did you select?
- What challenges did you face, and how did you solve them? 
- What did you learn about machine learning through this lab? 
- How are you thinking about machine learning differently after this lab?
- Other comments/questions/observations

I encourage folks to include code + screenshots as part of that narrative.
- You are welcome (but not required) to include Python code as part of that narrative.

This reflection should include comments from each member of the group. These can be combined in a single notebook or submitted individually along with work completed collaboratively.
