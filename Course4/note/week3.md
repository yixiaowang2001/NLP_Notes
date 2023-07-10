# Week3

# 1 RNNs and Vanishing Gradients

## 1.1 Recap for RNNs

- Advantages
  - Captures dependencies within a short range
  - Takes up less RAM than other n-gram models
- Disadvantages
  - Struggles to capture long term dependencies
  - Prone to vanishing or exploding gradients

## 1.2 Vanishing Gradients & Exploding Gradients

- Gradient is proportional to a sum of partial derivative products
- Vanishing gradients: let RNN ignore the parameters computed from early steps
- Exploding gradients: lead to convergence problems during training

<p align="center">
  <img src="../res/img/img34.png" width="500"/>
  <img src="../res/img/img35.png" width="500"/>
</p>

- Solving for vanishing or exploding graidents

<p align="center">
  <img src="../res/img/img36.png" width="600"/>
</p>

# 2 LSTMs

## 2.1 Introduction

1. Forget gate
2. Input gate
3. Output gate

<p align="center">
  <img src="../res/img/img37.png" width="600"/>
</p>

- Applications

<p align="center">
  <img src="../res/img/img38.png" width="600"/>
</p>

## 2.2 Architecture

- Candidate cell state
- New cell state

<p align="center">
  <img src="../res/img/img39.png" width="500"/>
  <img src="../res/img/img40.png" width="500"/>
</p>

# 3 NER

## 3.1 Introduction

- Types of entities

<p align="center">
  <img src="../res/img/img41.png" width="500"/>
  <img src="../res/img/img42.png" width="500"/>
</p>

- Example of a sentence

<p align="center">
  <img src="../res/img/img43.png" width="600"/>
</p>

- Applications

<p align="center">
  <img src="../res/img/img44.png" width="600"/>
</p>

## 3.2 Data Processing

- Word to number & label to number

<p align="center">
  <img src="../res/img/img45.png" width="600"/>
</p>

- Token padding

<p align="center">
  <img src="../res/img/img46.png" width="600"/>
</p>

## 3.3 Training the NER

- Pipeline

<p align="center">
  <img src="../res/img/img47.png" width="500"/>
  <img src="../res/img/img48.png" width="500"/>
</p>

- Trax implementation

<p align="center">
  <img src="../res/img/img49.png" width="600"/>
</p>

## 3.4 Evaluation

- Computing accuracy

<p align="center">
  <img src="../res/img/img50.png" width="500"/>
  <img src="../res/img/img51.png" width="500"/>
</p>
