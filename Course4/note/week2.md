# Week 2

# 1 Recap

<p align="center">
  <img src="../res/img/img13.png" width="500"/>
  <img src="../res/img/img14.png" width="500"/>
</p>

# 2 RNNs

## 2.1 Introduction

- RNNs model relationships among distinct words
- In RNNs, lots of computations share parameters

<p align="center">
  <img src="../res/img/img15.png" width="500"/>
  <img src="../res/img/img16.png" width="500"/>
</p>

## 2.2 Applications of RNN

- One-to-one (use one data to generate one outcome -> not useful)

<p align="center">
  <img src="../res/img/img17.png" width="600"/>
</p>

- One-to-many (use one picture to generate multiple results)

<p align="center">
  <img src="../res/img/img18.png" width="600"/>
</p>

- Many-to-one (a sequence of words to generate one outcome)

<p align="center">
  <img src="../res/img/img19.png" width="600"/>
</p>

- Many-to-many (a sequence of words to generate a sequence of words (machine translation))

<p align="center">
  <img src="../res/img/img20.png" width="600"/>
</p>

## 2.3 Math in RNN

- Vanilla RNN
  - Hidden states propagate information through time
  - Basic recurrent units have two inputs at each time: h^<t-1>, x^<t>

<p align="center">
  <img src="../res/img/img21.png" width="500"/>
  <img src="../res/img/img22.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img23.png" width="600"/>
</p>

## 2.4 Cost Function for RNNs

<p align="center">
  <img src="../res/img/img24.png" width="500"/>
  <img src="../res/img/img25.png" width="500"/>
</p>

## 2.5 Implementation Note

- For loop -> but framework needs this kind of abstraction
- tf.scan() mimics RNNs

<p align="center">
  <img src="../res/img/img26.png" width="600"/>
</p>

## 2.6 Gated Recurrent Units (GRU)

- Introduction

<p align="center">
  <img src="../res/img/img27.png" width="600"/>
</p>

- Comparison

<p align="center">
  <img src="../res/img/img28.png" width="500"/>
  <img src="../res/img/img29.png" width="500"/>
</p>

## 2.7 Deep and Bidirectional RNNs

- Bidirectional RNNs (starts propagation from both sides)

<p align="center">
  <img src="../res/img/img30.png" width="500"/>
  <img src="../res/img/img31.png" width="500"/>
</p>

- Deep RNNs (multiple RNNs (can be more than one))

<p align="center">
  <img src="../res/img/img32.png" width="500"/>
  <img src="../res/img/img33.png" width="500"/>
</p>
