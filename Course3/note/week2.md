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
