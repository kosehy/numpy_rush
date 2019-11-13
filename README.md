# Title

### Table Of Contents
* [Introduction](#introduction)
* [Objective](#objective)
* [Instructions](#instructions)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Usage](#usage)
* [Testing](#testing) 
* [Future](#future)
* [Mechanics](#mechanics)
* [Credits](#credits)
* [Disclaimer](#disclaimer)
* [Keep In Touch](#keep-in-touch)

## Introduction  

#### About This Project
This project is official rush project in 42 school. The project is to do the simple numpy array multiplication tutorial and implement more than four instagram filters. This serves two purposes, to help us learn the numpy array and to use and implement exercise using numpy library.
#### About Me
42
#### About 42  
[42][42] is a free, non profit, project-based, peer-to-peer learning coding school. It originated in France and now has over 20 campuses all over the world. More information can be found [here][42] 

## Objective  
The assignment is broken up into a part 1 and part 2.
Part 1 is to do the simple numpy array multiplication tutorial.
Part 2 is to implement more than four instagram filters.

## Instructions
Make sure you have the needed [dependencies](#dependencies) before proceeding.
For instructions and/or greater detail refer to the project [pdf][pdf]

## Dependencies  
* numpy
* matplotlib
* jupyter

## Installation
brew install docker-machine docker

brew services start docker-machine

docker-machine create --driver virtualbox default

eval "$(docker-machine env default)"

## Usage  
download Dockerfile

docker build -t numpy_rush .

mkdir notebooks

docker run -p 8800:8888 -v $(pwd)/notebooks:/notebooks numpy_rush

- To get docker-host-ip

docker-machine ls

<docker-host-ip>:8800/?token=...

## Testing  
Most testing was done under a google colab environment.

## Future

## Mechanics  

## Credits  
[https://github.com/akiomik/pilgram][pilgram]

## Disclaimer

This project was done for learning purposes only.

### Warning For 42 Students

This is not kept up to date and I cannot guarantee that it will work on your future machines. You are welcome to use and learn from this as you want, but do not implement code that you do not understand. Copying is not the way. 

## Keep in Touch

You can find me on:
[Github][kosehy]
Enjoy!

[42]: http://42.us.org "42 USA"
[pdf]: https://github.com/kosehy/numpy_rush/blob/master/numpy.en.pdf
[pilgram]: https://github.com/akiomik/pilgram
[kosehy]: https://github.com/kosehy