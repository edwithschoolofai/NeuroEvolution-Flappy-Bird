# Flappy Bird: 인간 vs NEAT vs 다층 퍼셉트론(MLP)
The goal of the project is to apply NEAT to evolve the network architecture of Deep Neural Networks for improving their performance on a given classification task, in this case the game Flappy Bird, the goal is to determine if for a given input the bird must jump or no to avoid hitting the pipes.
이 프로젝트의 목표는 NEAT를 적용하여 주어진 분류 작업의 성능 향상을 위한 딥 신경망 네트워크 구조를 발달하는 것입니다. Flappy Bird 게임의 주 목적은 주어진 입력값에 대해서 새가 배관에 부딪히는 것을 피하기 위해 뛰어야할지를 결정하는 것입니다.     
This repository contains a Jupyter Notebook where is possible to compare a Human, a Neat implementation and a multilayer perceptron playing Flappy Bird. 
이 레포지토리는 인간, NEAT 구현, 그리고 다층 퍼셉트론이 Flappy Bird 게임하는 것을 비교할 수 있는 주피터 노트북이 포함되어 있습니다. 

<p align="center">
 <img src="https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/ComparisonPlaying.gif?raw=true" alt="INPUT" />

</p>

## 입력값

신경 진화 알고리즘과 다층 퍼셉트론을 위한 입력값은 동일합니다. 
 
    1) Distance in the X axis from the bird to the next pipe.
    2) Distance in the Y axis form the bird to the lowest point of the pipe in the top.
    3) Distance in the Y axis from the bird to the highest point of the pipe in the top
    4) Distance in the Y axis from the bird to the top of the map.
    5) Distance in the Y axis from the bird to the bottom of the map.
    
<p align="center">

<img src="https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/Input.png?raw=true" alt="INPUT" width="350" height="680" />

</p>


## 결과

In this project we probe that NEAT can improve the performance of a DNN. We found that NEAT can be useful to reduce the complexity of our models. NEAT is able to produce networks that produce similar results to the MLP but much less complex. We have been able to use NEAT to reduce the complexity of our model. We went from 20 neurons and 98 weights in the MLP to 7-8 neurons and 6-10 weights, with is a huge complexity reduction. 이 프로젝트에서 우리는 NEAT가 딥 신경망의 성능을 향상시킬 수 있는지 조사합니다. NEAT는 모델의 복잡도을 줄이는 데 유용하다는 것을 찾았습니다. NEAT로 MLP와 비슷한 결과를 주지만 훨씬 덜 복잡한 네트워크를 생성할 수 있습니다. 우리는 NEAT를 사용해 모델의 복잡성을 줄일 수 있었습니다. MLP에서 20개의 뉴런과 98개의 가중치를 사용했던 것을 NEAT로 7-8개의 뉴런과 6-10개의 가중치를 사용하여 복잡성이 크게 줄였습니다. 


더 많은 정보는 [문서화 자료](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/)에서 찾을 수 있습니다 

![INPUT](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/blob/master/DemoImages/comp.png?raw=true)


## 저자
```
Iker García Ferrero - ikergarcia1996
Gonzalo Pierola - Guamedo
```
## 실행하는 법
이 프로젝트를 실행하기 위해서는 [파이썬](https://www.python.org/)과 [주피터 노트북](http://jupyter.org/)이 필요합니다.
그리고 "README.md"에 명시되어 있는 파이썬 라이브러리를 "Jupyter Notebook" 폴더에 설치해야 합니다. 

## 문서화 자료
Documentation is available in the [releases section](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/) with the corresponding release. [releases section](https://github.com/ikergarcia1996/Flappy-Bird-NEAT-vs-DEEP/releases/)에 각 릴리즈에 대한 문서화 자료를 찾을 수 있습니다. 

## Flappy Bird 게임
이 프로젝트의 Flappy Bird 게임은 다음 코드를 바탕으로 구현되었습니다. 
[Gamedevlapse: 파이썬으로 Flappy Bird 구현하기 \[Time Lapse\] (유투브 영상)](https://youtu.be/h2Uhla6nLDU)
