# Week 2

# 1 Probability

- Probability of the word "happy" be categorized as Positive or Negative

<p align="center">
  <img src="../res/img/img24.png" width="500"/>
  <img src="../res/img/img25.png" width="500"/>
</p>

- Probability of the interestion

<p align="center">
  <img src="../res/img/img26.png" width="600"/>
</p>

# 2 Bayes' Rule

- Conditional probabilities: P(A|B) = P(A & B) / P(B)
  - Probability of B, given A happened
  - Looking at the elements of set A, the chance that one also belongs to set B

<p align="center">
  <img src="../res/img/img27.png" width="500"/>
  <img src="../res/img/img28.png" width="500"/>
</p>

- Bayes' rule: P(X|Y) = P(Y|X) \* P(X) / P(Y)

<p align="center">
  <img src="../res/img/img29.png" width="600"/>
</p>

# 3 Naive Bayes

## 3.1 Introduction

- Naive: features used for the classification are all independent
- Pipeline:

1. Count the pos/neg words

<p align="center">
  <img src="../res/img/img30.png" width="600"/>
</p>

2. Calculate the conditional probabilities

<p align="center">
  <img src="../res/img/img31.png" width="600"/>
</p>

3. Distinguish words:
   1. Similar prob: neutral words
   2. Pos > Neg: positive words
   3. Neg > Pos: negative words
   4. 0: cannot compare between two corpora

<p align="center">
  <img src="../res/img/img32.png" width="600"/>
</p>

4. To avoid this problem, we need to smooth the probability function.

5. Get the value for the tweet: apply Naive Bayes inference condition rule

<p align="center">
  <img src="../res/img/img33.png" width="600"/>
</p>

## 3.2 Laplcian Smoothing

- Formula

<p align="center">
  <img src="../res/img/img34.png" width="600"/>
</p>

- Calculation

<p align="center">
  <img src="../res/img/img35.png" width="500"/>
  <img src="../res/img/img36.png" width="500"/>
</p>

## 3.3 Log Likelihood

- Ratio of probabilities

<p align="center">
  <img src="../res/img/img37.png" width="600"/>
</p>

- Naive Bayes Inference
  - Simple, fast, and powerful baseline
  - A probabilistic model for classification

<p align="center">
  <img src="../res/img/img37.png" width="600"/>
</p>

- Log likelihood
  - Product may contain numerical underflow (the number is too small to be stored)

<p align="center">
  <img src="../res/img/img38.png" width="600"/>
</p>

- Calculating lambda

<p align="center">
  <img src="../res/img/img39.png" width="600"/>
</p>

## 3.4 Training Naive Bayes

- Pipeline

<p align="center">
  <img src="../res/img/img40.png" width="500"/>
  <img src="../res/img/img41.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img42.png" width="500"/>
  <img src="../res/img/img43.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img44.png" width="600"/>
</p>

## 3.5 Test Naive Bayes

<p align="center">
  <img src="../res/img/img45.png" width="500"/>
  <img src="../res/img/img46.png" width="500"/>
</p>

# 4 Applications

- Author identification
- Spam filtering

<p align="center">
  <img src="../res/img/img47.png" width="600"/>
</p>

- Information retrieval

<p align="center">
  <img src="../res/img/img48.png" width="600"/>
</p>

- Word disambiguation

<p align="center">
  <img src="../res/img/img49.png" width="600"/>
</p>

# 5 Naive Base Assumptions

- Independence
  - Assuming words are independnet
  - May give equal probabilities to each word (if Naive Bayes is used to predict the word)

<p align="center">
  <img src="../res/img/img50.png" width="500"/>
  <img src="../res/img/img51.png" width="500"/>
</p>

- Relative frequencies in your corpus

  - Relies on the distributions of the training datasets
  - Most avaliable datasets now are artificially equally distributed

# 6 Error Analysis

- Removing punctuation and stop words

<p align="center">
  <img src="../res/img/img52.png" width="500"/>
  <img src="../res/img/img53.png" width="500"/>
</p>

- Word order

<p align="center">
  <img src="../res/img/img54.png" width="600"/>
</p>

- Adversarial attacks

<p align="center">
  <img src="../res/img/img55.png" width="600"/>
</p>
