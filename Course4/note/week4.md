# Week 4

# 1 Task with Long Sequences

## 1.1 Introduction

- Tasks (difficult for training)

<p align="center">
  <img src="../res/img/img130.png" width="600"/>
</p>

- Chatbot: context windows

<p align="center">
  <img src="../res/img/img131.png" width="600"/>
</p>

## 1.2 Transformer Issues

- Activations need to be stored for backprop
- Big models are getting bigger

<p align="center">
  <img src="../res/img/img132.png" width="500"/>
  <img src="../res/img/img133.png" width="500"/>
</p>

# 2 LSH Attention

## 2.1 Introduction

- What does attention do?
- Nearest neighbors

<p align="center">
  <img src="../res/img/img134.png" width="500"/>
  <img src="../res/img/img135.png" width="500"/>
</p>

## 2.2 LSH Attenion

<p align="center">
  <img src="../res/img/img136.png" width="500"/>
  <img src="../res/img/img137.png" width="500"/>
</p>

## 2.3 Motivations

- When total number of layers increases, emory required increases

<p align="center">
  <img src="../res/img/img138.png" width="600"/>
</p>

## 2.4 Reversible Residual Lyaers

- Euqations

<p align="center">
  <img src="../res/img/img139.png" width="500"/>
  <img src="../res/img/img140.png" width="500"/>
</p>

- Visualization

<p align="center">
  <img src="../res/img/img141.png" width="500"/>
  <img src="../res/img/img142.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img143.png" width="500"/>
  <img src="../res/img/img144.png" width="500"/>
</p>

- BLEU performance

<p align="center">
  <img src="../res/img/img145.png" width="600"/>
</p>

# 3 Reformer

- Application

<p align="center">
  <img src="../res/img/img146.png" width="600"/>
</p>

- Structure

<p align="center">
  <img src="../res/img/img147.png" width="600"/>
</p>

- Attention
  - How standard attention takes longer as sequence length increases
  - However, LSH attention taks roughly the same amout of time as sequence length increases
  - The only difference is more hashes taking slightly longer than fewer hashes regaredless of the sequence length

<p align="center">
  <img src="../res/img/img148.png" width="600"/>
</p>
