# Perceptron
* Perceptron (html & JavaScript)
* Perceptron.html

## Introduction
* Single perceptron
* No activation function
* Two inputs, two train data, bias input (optional), learning rate
* Hyperplane is shown

## Usage
* Start: generates two train data (p1 and p2, desired output (d): 1 and -1) with two featrues ranging [0, 1] , and resets weights
* Step:
  + trains by each train data, alternately
  + updates by w<sub>1</sub>(t+1) = w<sub>1</sub>(t) + η(d-y(t))x<sub>1</sub>(t), where y = w<sub>1</sub>x<sub>1</sub> + w<sub>2</sub>x<sub>2</sub> + b
* Step(1000): trains 1000 epochs
* Reset weights: resets weights to random values ranging [-0.5, 0.5]
* [View](https://nize-vision.tistory.com/1) 
<br> <img src="Perceptron.jpg"></img>  
