# Snake Game AI
- Author: Quoc "Tim" Huynh
- Language: Python (version 3.7.7)
- A snake game that can be played traditionally or by ML algorithm
- Last updated: August 9th, 2020.

## Project Overview
- Learn the basics of Artificial Intelligence

## Demo 

![](snake_gif3.gif)

## Input and Output
### Input
- Automatically generated ~ 37,500 training data
- train_X.shape = [14500, 7]
- train_y.shape = [14500, 3]

### Output
- The model dynamically works with different grid dimensions (50x50, 30x30, 20x20)
- Train Accuracy: ~ 98%
- Train Loss: ~ 2%
- Grid size 50x50: High score = 89; average score = 51.
- Grid size 30x30: High score = 57; average score = 35.
- Grid size 20x20: High score = 46; average score = 22.

## Reproduction Steps (macOS/ Linux)
### Prerequisites

```
pygame==1.9.6
keras==2.3.1
numpy==1.18.1
tqdm==4.42.1
```
### Installing

Note: Ideally, you would want to create a virtual environment first and then begin the installation process inside this environment.

- Download this repository on your local machine 

- Install all the dependencies listed in the requirements.txt file:
```
$ pip install -r requirements.txt
```

### Running the program
- In your terminal, locate your project folder and run the following files in order:

```
$ cd /path/to/your/project/folder
$ python neuralNetwork.py (optional)
$ python main.py
```


















