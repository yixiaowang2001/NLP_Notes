# Week 4

# 1 Word Embeddings

## 1.1 Basic Word Representations

### 1.1.1 One-hot vectors

- Pro
  - Simple
  - No implied ordering
- Con
  - Huge vectors
  - No embedded meaning

<p align="center">
  <img src="../res/img/img80.png" width="500"/>
  <img src="../res/img/img81.png" width="500"/>
</p>

### 1.1.2 Word embeddings

- Pro
  - Low dimension
  - embed meaning

<p align="center">
  <img src="../res/img/img82.png" width="500"/>
  <img src="../res/img/img83.png" width="500"/>
</p>

## 1.2 Process

<p align="center">
  <img src="../res/img/img84.png" width="600"/>
</p>

## 1.3 Methods

- Basic methods

<p align="center">
  <img src="../res/img/img85.png" width="600"/>
</p>

- Advanced methods

<p align="center">
  <img src="../res/img/img86.png" width="600"/>
</p>

# 2 Continuous Bag-of-Words Model

## 2.1 Introduction

- Predict the center word

<p align="center">
  <img src="../res/img/img87.png" width="500"/>
  <img src="../res/img/img88.png" width="500"/>
</p>

## 2.2 Data Cleaning

### 2.2.1 Clean and tokenizations

- Letter case
- Punctuations
- Numbers
- Special characters
- Special words

<p align="center">
  <img src="../res/img/img89.png" width="500"/>
  <img src="../res/img/img90.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img91.png" width="500"/>
  <img src="../res/img/img92.png" width="500"/>
</p>

### 2.2.2 Get windows of words

<p align="center">
  <img src="../res/img/img93.png" width="500"/>
  <img src="../res/img/img94.png" width="500"/>
</p>

### 2.2.3 Transforming Words into Vectors

<p align="center">
  <img src="../res/img/img95.png" width="500"/>
  <img src="../res/img/img96.png" width="500"/>
</p>

- Final training set

<p align="center">
  <img src="../res/img/img97.png" width="600"/>
</p>

## 2.3 CBOW Model Architecture

### 2.3.1 Introduction

- N is the size of the hidden layer, also the word embedding size
  - 8000 (input), 400 (output), 8000 (output)
  - N = 400 in this case
- Dense neural network (layers are fully connected)

<p align="center">
  <img src="../res/img/img98.png" width="600"/>
</p>

### 2.3.2 Dimensions

- One example as input

<p align="center">
  <img src="../res/img/img99.png" width="500"/>
  <img src="../res/img/img100.png" width="500"/>
</p>

- More than one examples as input

<p align="center">
  <img src="../res/img/img101.png" width="500"/>
  <img src="../res/img/img102.png" width="500"/>
</p>

### 2.3.3 Activation functions

- ReLU

<p align="center">
  <img src="../res/img/img103.png" width="600"/>
</p>

- Softmax

<p align="center">
  <img src="../res/img/img104.png" width="500"/>
  <img src="../res/img/img105.png" width="500"/>
</p>

### 2.3.4 Cost functions

- Loss function

<p align="center">
  <img src="../res/img/img106.png" width="600"/>
</p>

- Cross-entropy loss
  - Right: correct predictions
  - Left: incorrect predictions

<p align="center">
  <img src="../res/img/img107.png" width="500"/>
  <img src="../res/img/img108.png" width="500"/>
</p>

## 2.4 Training A CBOW Model

- Training process
  - Forward propagation
  - Cost
  - Backward propagation and gradient descent

<p align="center">
  <img src="../res/img/img109.png" width="600"/>
</p>

- Minize the cost
