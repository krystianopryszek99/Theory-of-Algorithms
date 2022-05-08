<p align="center">
  <img src="https://user-images.githubusercontent.com/57759154/162638159-53282ce7-70bf-40bf-8409-5d285f1f696d.png" width="350" height="150"/>
 </p>

# Theory of Algorithms

**Name:** Krystian Opryszek

**Student ID:** G00366895

## Table Of Content
- [Overview](#Overview)
- [How to run the notebooks](#How-to-run-the-notebooks)
- [Requirements](#Requirements)
- [Technologies used](#Technologies-used)
- [References](#References)

## Overview
This repository contains lab work and assessment for Theory of Algorithms module. There are two jupyter notebooks which are used for the assessment, `post-correspondence.ipynb` and `countdown.ipynb`.

- **post-correspondence.ipynb**

  The post-correspondence notebook contains the definition and explanation of the [Post Correspondence Problem](https://en.wikipedia.org/wiki/Post_correspondence_problem) and Bounded Post Correspondence Problem. A Python function to solve the Bounded Post Correspondence Problem. The function takes two lists of strings and returns True or False depending on if they correspond or not. This notebook also contains an explanation of what an undecidable problem is in computability theory.

- **countdown.ipynb**

  The countdown notebook contains an overview and explanation of the [Countdown Numbers Game](https://en.wikipedia.org/wiki/Countdown_(game_show)). This notebook also contains the discussion of the complexity of the Countdown Numbers Game. A python function to solve a Countdown Numbers Game, written in a [functional programming style](https://docs.python.org/3/howto/functional.html). The function takes a list of six numbers and a target number and returns a method to calculate the target from the numbers. Finally an explanation of the functional aspects of the code.
  
- **Labs**

  All lab work can be found in the `Labs` folder. It contains all the lab work throughout the course of this module.
  
## How to run the notebooks

To run the notebooks follow the below instructions:

### Quick steps

You can view notebooks in static form by clicking the following image:


| post-correspondence notebook| [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/krystianopryszek99/Theory-of-Algorithms/blob/main/post_correspondence.ipynb)| 
| --------------- | --------------- | 
| **countdown notebook** |  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/krystianopryszek99/Theory-of-Algorithms/blob/main/countdown.ipynb)|

### Run using jupyter notebook 

*You may have to install anaconda to run with jupyter notebook, look the [Requirements](#Requirements)*

1) Clone this repository onto your machine:
```
$ git clone https://github.com/krystianopryszek99/Theory-of-Algorithms
```
2) Direct to the folder: `Theory-of-Algorithms`

3) Open cmd and run:

```
$ juyter notebook 
```

## Requirements

In order to run these notebooks with jupyter notebook, you may be required to have Python and anaconda installed on your machine. Anaconda is the recommended solution for installing both Python and Jupyter. You can download the following: [Python](https://www.python.org/downloads/) and [Anaconda](https://www.anaconda.com/). You can follow installation steps from [Jupyter Documentation](https://test-jupyter.readthedocs.io/en/latest/install.html) to install Jupyter Notebook. More on running the notebook on [Jupyter Documentation](https://test-jupyter.readthedocs.io/en/latest/running.html#running).

## Technologies used

Some of the technologies used in this assessment are as follow:

- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" height="50"/> **Python**
  
  Python is a high-level, general-purpose programming language that is interpreted.
  
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width="50" height="50"/> **Jupyter Project** 
  
  Open-source software, open standards, and Interactive computing services for dozens of programming languages.
  
- <img src="https://searchvectorlogo.com/wp-content/uploads/2020/10/anaconda-inc-logo-vector.png" width="50" height="50"/> **Anaconda** 

  Anaconda is a Python and R programming language distribution for computer science that aims to make package management and deployment easier.

## References

Here is a list of references I have used to complete this assessment.

1. [*Post correspondence problem*, <br> https://en.wikipedia.org/wiki/Post_correspondence_problem](https://en.wikipedia.org/wiki/Post_correspondence_problem)
1. [*Countdown Numbers Game*, <br> https://en.wikipedia.org/wiki/Countdown_(game_show)](https://en.wikipedia.org/wiki/Countdown_(game_show))
3. [*Functional Programming HOWTO*, <br> https://docs.python.org/3/howto/functional.html](https://docs.python.org/3/howto/functional.html)
