# Visual Computing Algorithms — README

A collection of algorithms in visual computing implemented using Python and Jupyter Notebooks.

## Project overview

This repository contains a curated set of visual computing algorithms implemented in Python using Jupyter Notebooks. The goal is to demonstrate a solid understanding of core concepts in visual computing, including image processing, computer vision, and geometric transformations, while also showcasing proficiency in algorithm design and implementation.

Each notebook is self-contained and designed to present my journey in understanding the algorithms, where possible.


## Technologies used

* Python 3.x

* Jupyter Notebooks

* NumPy

* OpenCV (cv2)


## Algorithms

* Change Detection

    ![GMM Demo](<Demos/GMM Demo.gif>)

* Object Tracking

    ![Tracking Demo](<Demos/Tracking Demo.gif>)

* Depth Extraction

* Image Filtering using Fourier Transforms

## What’s included in this repo

```
/TestFiles/               <- Videos and images used during testing
/Demos/                   <- Output demos 
/Change Detection         
/Object Tracking    
/Fourier Transforms
/Depth Extraction      
/requirements.txt         <- Dependencies needed to run this project
/README.md                <- this file
```


## Limitations & what I’d improve

* Change detection algorithm is too slow to process high-resolution videos

* Tracking algorithm can't detect obscured objects

* Fast Fourier Transform algorithm is not yet fully finished

* Depth extraction algorithm is not yet finished due to slow execution time


## Installation

To run these notebooks locally, I reccomend the following steps:

* Clone this repository:

```
git clone https://github.com/SebastianBodean/visual-computing-algorithms.git
cd visual-computing-algorithms
```

* Install the required packages:

```
pip install -r requirements.txt
```

* Install [Visual Studio Code](https://code.visualstudio.com/)

* Open VS Code and install the Jupyter Notebook plugin from the Extensions tab

* Open the desired file using Visual Studio Code
