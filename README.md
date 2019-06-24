# Flappy Bird: Human vs NEAT vs MLP
The goal of the project is to apply NEAT to evolve the network architecture of Deep Neural Networks for improving their performance on a given classification task, in this case the game Flappy Bird, the goal is to determine if for a given input the bird must jump or no to avoid hitting the pipes.
This repository contains a Jupyter Notebook where is possible to compare a Human, a Neat implementation and a multilayer perceptron playing Flappy Bird. 

<p align="center">
 <img src="https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/ComparisonPlaying.gif?raw=true" alt="INPUT" />

</p>

## Input 입력값

For both, neuroevolution algorithm and multilayer perceptron the input is the same:
 
    1) Distance in the X axis from the bird to the next pipe.
    2) Distance in the Y axis form the bird to the lowest point of the pipe in the top.
    3) Distance in the Y axis from the bird to the highest point of the pipe in the top
    4) Distance in the Y axis from the bird to the top of the map.
    5) Distance in the Y axis from the bird to the bottom of the map.
    
<p align="center">

<img src="https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/Input.png?raw=true" alt="INPUT" width="350" height="680" />

</p>


## Results 결과

In this project we probe that NEAT can improve the performance of a DNN. We found that NEAT can be useful to reduce the complexity of our models. NEAT is able to produce networks that produce similar results to the MLP but much less complex. We have been able to use NEAT to reduce the complexity of our model. We went from 20 neurons and 98 weights in the MLP to 7-8 neurons and 6-10 weights, with is a huge complexity reduction.

More information available in the [documentation](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/).
더 많은 정보는 [documentation](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/)에서 찾을 수 있습니다 

![INPUT](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/comp.png?raw=true)


## 저자
```
Iker García Ferrero - ikergarcia1996
Gonzalo Pierola - Guamedo
```
## 실행하는 법
To run this project you need [Python](https://www.python.org/) and [Jupyter Notebook](http://jupyter.org/).
이 프로젝트를 실행하기 위해서는 [파이썬](https://www.python.org/)과 [주피터 노트북](http://jupyter.org/)이 필요합니다.
Also you will need to install all the python libraries specified in the "README.md" inside the "Jupyter Notebook" folder.
그리고 "README.md"에 명시되어 있는 파이썬 라이브러리를 "Jupyter Notebook" 폴더에 설치해야 합니다. 

## Documentation
Documentation is available in the [releases section](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/) with the corresponding release.

## Flappy Bird 게임
이 프로젝트에서 사용한 Flappy Bird 게임 구현은 다음 코드를 바탕으로 하였습니다. 
The implementation of the Flappy Bird Game that we used for this project is based on this code:
[Gamedevlapse: Create Flappy Bird in Python \[Time Lapse\] (youtube)](https://youtu.be/h2Uhla6nLDU)
