# Week3

# 1 N-Grams

## 1.1 Backgrounds

- Language models / autocompletion

<p align="center">
  <img src="../res/img/img42.png" width="500"/>
  <img src="../res/img/img43.png" width="500"/>
</p>

## 1.2 Introduction

<p align="center">
  <img src="../res/img/img44.png" width="500"/>
  <img src="../res/img/img45.png" width="500"/>
</p>

- Probability of unigram

<p align="center">
  <img src="../res/img/img46.png" width="600"/>
</p>

- Probability of bigram / trigram

<p align="center">
  <img src="../res/img/img47.png" width="500"/>
  <img src="../res/img/img48.png" width="500"/>
</p>

- Probability of ngram

<p align="center">
  <img src="../res/img/img49.png" width="600"/>
</p>

## 1.3 Sequence Probabilities

- Formula

<p align="center">
  <img src="../res/img/img50.png" width="600"/>
</p>

- Example

<p align="center">
  <img src="../res/img/img51.png" width="500"/>
  <img src="../res/img/img52.png" width="500"/>
</p>

- Approximation

<p align="center">
  <img src="../res/img/img53.png" width="600"/>
</p>

## 1.4 Starting and Ending Sentences

- Start

<p align="center">
  <img src="../res/img/img54.png" width="600"/>
</p>

- End

<p align="center">
  <img src="../res/img/img55.png" width="500"/>
  <img src="../res/img/img56.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img57.png" width="500"/>
  <img src="../res/img/img58.png" width="500"/>
</p>

- Example

<p align="center">
  <img src="../res/img/img59.png" width="600"/>
</p>

# 2 N-gram Language Model

## 2.1 Introduction

<p align="center">
  <img src="../res/img/img60.png" width="600"/>
</p>

## 2.2 Count Matrix

<p align="center">
  <img src="../res/img/img61.png" width="600"/>
</p>

## 2.3 Probability Matrix

<p align="center">
  <img src="../res/img/img62.png" width="600"/>
</p>

## 2.4 Language Model

<p align="center">
  <img src="../res/img/img63.png" width="600"/>
</p>

- Implementation

<p align="center">
  <img src="../res/img/img64.png" width="500"/>
  <img src="../res/img/img65.png" width="500"/>
</p>

## 2.5 Evaluation

- Data

<p align="center">
  <img src="../res/img/img66.png" width="500"/>
  <img src="../res/img/img67.png" width="500"/>
</p>

- Perplexity

<p align="center">
  <img src="../res/img/img68.png" width="500"/>
  <img src="../res/img/img69.png" width="500"/>
</p>

- Bigram perplexity / log perplexity: Good model -> 20~60, 4.3~5.9 (log level)

<p align="center">
  <img src="../res/img/img70.png" width="500"/>
  <img src="../res/img/img71.png" width="500"/>
</p>

## 2.6 Out of Vocabulary Words

<p align="center">
  <img src="../res/img/img72.png" width="500"/>
  <img src="../res/img/img73.png" width="500"/>
</p>

- Example

<p align="center">
  <img src="../res/img/img74.png" width="600"/>
</p>

- How to create vocabulary V

<p align="center">
  <img src="../res/img/img75.png" width="600"/>
</p>

## 2.7 Smoothing

- Motivation

<p align="center">
  <img src="../res/img/img76.png" width="600"/>
</p>

- Smoothing method

<p align="center">
  <img src="../res/img/img77.png" width="500"/>
  <img src="../res/img/img78.png" width="500"/>
</p>

<p align="center">
  <img src="../res/img/img79.png" width="600"/>
</p>
