# Week 2

# 1 Part of Speech

- Introduction

<p align="center">
  <img src="../res/img/img14.png" width="600"/>
</p>

- Application

<p align="center">
  <img src="../res/img/img15.png" width="600"/>
</p>

# 2 Markov Chains

## 2.1 Introduction

- Tend to depend on the previous tag of POS

<p align="center">
  <img src="../res/img/img16.png" width="500"/>
  <img src="../res/img/img17.png" width="500"/>
</p>

- Directed graph

<p align="center">
  <img src="../res/img/img18.png" width="600"/>
</p>

## 2.2 Transition Matrix

- Prob for going from NN to NN, NN to VB, NN to O

<p align="center">
  <img src="../res/img/img19.png" width="600"/>
</p>

- How to assign a POS tag to the first word in the sentence -> introduce initial state

<p align="center">
  <img src="../res/img/img20.png" width="600"/>
</p>

- Transition matrix

<p align="center">
  <img src="../res/img/img21.png" width="500"/>
  <img src="../res/img/img22.png" width="500"/>
</p>

## 2.3 Emission Matrix

- Emission probabilities

<p align="center">
  <img src="../res/img/img23.png" width="600"/>
</p>

## 2.4 Calculate Probabilities

- Process

<p align="center">
  <img src="../res/img/img24.png" width="500"/>
  <img src="../res/img/img25.png" width="500"/>
</p>

- Summary

<p align="center">
  <img src="../res/img/img26.png" width="600"/>
</p>

## 2.5 Populating Transition Matrix

<p align="center">
  <img src="../res/img/img27.png" width="500"/>
  <img src="../res/img/img28.png" width="500"/>
</p>

- Smoothing

<p align="center">
  <img src="../res/img/img29.png" width="600"/>
</p>

## 2.6 Populating Emission Matrix

<p align="center">
  <img src="../res/img/img30.png" width="500"/>
  <img src="../res/img/img31.png" width="500"/>
</p>

## 2.7 Viterbi Algorithm

- Visualization

<p align="center">
  <img src="../res/img/img32.png" width="600"/>
</p>

- Steps

<p align="center">
  <img src="../res/img/img33.png" width="600"/>
</p>

- Intialization

<p align="center">
  <img src="../res/img/img34.png" width="600"/>
</p>

- Forward pass

<p align="center">
  <img src="../res/img/img35.png" width="600"/>
</p>

- Backward pass

<p align="center">
  <img src="../res/img/img36.png" width="600"/>
</p>

- Backward pass example

<p align="center">
  <img src="../res/img/img37.png" width="500"/>
  <img src="../res/img/img38.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img39.png" width="500"/>
  <img src="../res/img/img40.png" width="500"/>
</p>

- Implement notes

<p align="center">
  <img src="../res/img/img41.png" width="600"/>
</p>
