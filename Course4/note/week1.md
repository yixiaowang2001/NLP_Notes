# Week 1

# 1 Seq2seq

- Introduction

<p align="center">
  <img src="../res/img/img1.png" width="500"/>
  <img src="../res/img/img2.png" width="500"/>
</p>

- Encoder & decoder

<p align="center">
  <img src="../res/img/img3.png" width="500"/>
  <img src="../res/img/img4.png" width="500"/>
</p>

- Short comings

<p align="center">
  <img src="../res/img/img5.png" width="600"/>
</p>

- Time efficiency - attention
  - Model would have flaws with memory and contexts
  - Provide information specific to each input word, you can give the model a way to focus it's attention in the right place at each step of the decoding process

<p align="center">
  <img src="../res/img/img6.png" width="500"/>
  <img src="../res/img/img7.png" width="500"/>
</p>

# 2 Seq2seq Model with Attention

- Comparison

<p align="center">
  <img src="../res/img/img8.png" width="600"/>
</p>

- Motivation

<p align="center">
  <img src="../res/img/img9.png" width="500"/>
  <img src="../res/img/img10.png" width="500"/>
</p>

# 3 Queries, Keys, Values, and Attention

- Introduction

<p align="center">
  <img src="../res/img/img11.png" width="600"/>
</p>

- Scaled dot product attention

<p align="center">
  <img src="../res/img/img12.png" width="600"/>
</p>

- Alignment weights & flexible attention

<p align="center">
  <img src="../res/img/img13.png" width="600"/>
</p>

# 4 Machine Translation

## 4.1 Setup

- Data

<p align="center">
  <img src="../res/img/img14.png" width="500"/>
  <img src="../res/img/img15.png" width="500"/>
</p>

- Example

<p align="center">
  <img src="../res/img/img16.png" width="500"/>
  <img src="../res/img/img17.png" width="500"/>
</p>

## 4.2 Teach Forcing

- The model is naive during early steps of training

<p align="center">
  <img src="../res/img/img18.png" width="500"/>
  <img src="../res/img/img19.png" width="500"/>
</p>

- Correct sequence (ground truth) of words as input (shifted right)
  - It has some variations. For example, you can slowly start using decoder outputs over time, so that leads into training, your are no longer feeding in the target words (curriculum learning)

<p align="center">
  <img src="../res/img/img20.png" width="600"/>
</p>

## 4.3 NMT (Neural Machine Translation) Model with Attention

- Model structure

<p align="center">
  <img src="../res/img/img21.png" width="500"/>
  <img src="../res/img/img22.png" width="500"/>
</p>

- NMT model

<p align="center">
  <img src="../res/img/img23.png" width="600"/>
</p>

## 4.4 Evaluation

### 4.4.1 BLEU score

- Introduction

<p align="center">
  <img src="../res/img/img24.png" width="600"/>
</p>

- Basic version
  - Con: more common words, better performance

<p align="center">
  <img src="../res/img/img25.png" width="500"/>
  <img src="../res/img/img26.png" width="500"/>
</p>

- Modified version

<p align="center">
  <img src="../res/img/img27.png" width="600"/>
</p>

- Drawbacks

<p align="center">
  <img src="../res/img/img28.png" width="600"/>
</p>

### 4.4.2 ROUGE

- Introduction

<p align="center">
  <img src="../res/img/img29.png" width="600"/>
</p>

- Basic version

<p align="center">
  <img src="../res/img/img30.png" width="500"/>
  <img src="../res/img/img31.png" width="500"/>
</p>

- Combined version: ROUGE-N, BLEU, and F1 score

<p align="center">
  <img src="../res/img/img32.png" width="600"/>
</p>

- Note
  - All these evaluation metrics don't consider the sentence structure and semantics
  - Only account for matching n-grams (accuracy) between candidates and the reference translations

## 4.5 Sampling and Decoding

### 4.5.1 General method

- Greedy decoding

<p align="center">
  <img src="../res/img/img33.png" width="600"/>
</p>

- Random sampling

<p align="center">
  <img src="../res/img/img34.png" width="500"/>
  <img src="../res/img/img35.png" width="500"/>
</p>

### 4.5.2 Beam Search

- Introduction

<p align="center">
  <img src="../res/img/img36.png" width="500"/>
  <img src="../res/img/img37.png" width="500"/>
</p>

- Example

<p align="center">
  <img src="../res/img/img38.png" width="600"/>
</p>

<p align="center">
  <img src="../res/img/img39.png" width="500"/>
  <img src="../res/img/img40.png" width="500"/>
</p>

- Problem

<p align="center">
  <img src="../res/img/img41.png" width="600"/>
</p>

### 4.5.3 Minimum Bayes Risk (MBR)

- Introduction & calculation

<p align="center">
  <img src="../res/img/img42.png" width="500"/>
  <img src="../res/img/img43.png" width="500"/>
</p>

- Example
  - More contextually accurate translation than random sampling and greedy decoding

<p align="center">
  <img src="../res/img/img44.png" width="600"/>
</p>
