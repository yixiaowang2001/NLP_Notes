# Week3

# 1 Overview

<p align="center">
  <img src="../res/img/img74.png" width="600"/>
</p>

- Question answering
  - Closed book: without accessing other documents

<p align="center">
  <img src="../res/img/img75.png" width="600"/>
</p>

- Transfer learning

<p align="center">
  <img src="../res/img/img76.png" width="600"/>
</p>

- Classical training vs. transfer learning

<p align="center">
  <img src="../res/img/img77.png" width="500"/>
  <img src="../res/img/img78.png" width="500"/>
</p>

- Transfer learning: different tasks

<p align="center">
  <img src="../res/img/img79.png" width="600"/>
</p>

- BERT

<p align="center">
  <img src="../res/img/img80.png" width="600"/>
</p>

- T5: single task vs. multi task

<p align="center">
  <img src="../res/img/img81.png" width="600"/>
</p>

- Transfer learning: desirable goals

<p align="center">
  <img src="../res/img/img82.png" width="600"/>
</p>

# 2 Transfer Learning in NLP

- Process

<p align="center">
  <img src="../res/img/img83.png" width="600"/>
</p>

- General purpose learning

<p align="center">
  <img src="../res/img/img84.png" width="600"/>
</p>

- Feature-based vs. fine-tuning

<p align="center">
  <img src="../res/img/img85.png" width="600"/>
</p>

- Adding new layer
  - Freeze all parameters

<p align="center">
  <img src="../res/img/img86.png" width="600"/>
</p>

- Self-supervised task

<p align="center">
  <img src="../res/img/img87.png" width="500"/>
  <img src="../res/img/img88.png" width="500"/>
</p>

- Fine-tune a model for each donwstream task

<p align="center">
  <img src="../res/img/img89.png" width="600"/>
</p>

# 3 ELMo, GPT, BERT, T5

- Timeline

<p align="center">
  <img src="../res/img/img90.png" width="600"/>
</p>

- CBOW

<p align="center">
  <img src="../res/img/img91.png" width="500"/>
  <img src="../res/img/img92.png" width="500"/>
</p>

- BiLSTM
  - Output the embedding of the target word

<p align="center">
  <img src="../res/img/img93.png" width="600"/>
</p>

- GPT
  - Unidirectional (no peeking)!

<p align="center">
  <img src="../res/img/img94.png" width="600"/>
</p>

- BERT

<p align="center">
  <img src="../res/img/img95.png" width="500"/>
  <img src="../res/img/img96.png" width="500"/>
</p>

- BERT: Words to Sentences

<p align="center">
  <img src="../res/img/img97.png" width="500"/>
  <img src="../res/img/img98.png" width="500"/>
</p>

- T5

<p align="center">
  <img src="../res/img/img99.png" width="600"/>
</p>

- Summary

<p align="center">
  <img src="../res/img/img100.png" width="600"/>
</p>

# 4 BERT

## 4.1 Introduction

<p align="center">
  <img src="../res/img/img101.png" width="500"/>
  <img src="../res/img/img102.png" width="500"/>
</p>

- Quick summary

<p align="center">
  <img src="../res/img/img103.png" width="600"/>
</p>

## 4.2 BERT Objective

- Formalizing the input

<p align="center">
  <img src="../res/img/img104.png" width="500"/>
  <img src="../res/img/img105.png" width="500"/>
</p>

- Objective

<p align="center">
  <img src="../res/img/img106.png" width="600"/>
</p>

## 4.3 Fine-tune Pre-trained

<p align="center">
  <img src="../res/img/img107.png" width="500"/>
  <img src="../res/img/img108.png" width="500"/>
</p>

## 4.4 Transformer: T5

- Tasks

<p align="center">
  <img src="../res/img/img109.png" width="600"/>
</p>

- Data

<p align="center">
  <img src="../res/img/img110.png" width="600"/>
</p>

- Architecture

<p align="center">
  <img src="../res/img/img111.png" width="500"/>
  <img src="../res/img/img112.png" width="500"/>
</p>

## 4.5 Multi-task Training Strategy

- Performance

<p align="center">
  <img src="../res/img/img113.png" width="500"/>
  <img src="../res/img/img114.png" width="500"/>
</p>

- Data training strategies

<p align="center">
  <img src="../res/img/img115.png" width="500"/>
  <img src="../res/img/img116.png" width="500"/>
</p>

- Fine-tune
  - The main objective of the multitasking training strategy is to improve the performance of the various tasks by learning them together

<p align="center">
  <img src="../res/img/img117.png" width="600"/>
</p>

# 5 GLUE Benchmark

<p align="center">
  <img src="../res/img/img118.png" width="500"/>
  <img src="../res/img/img119.png" width="500"/>
</p>

# 6 Question Answering

- Model

<p align="center">
  <img src="../res/img/img120.png" width="600"/>
</p>

- Data

<p align="center">
  <img src="../res/img/img121.png" width="600"/>
</p>

- Implementation

<p align="center">
  <img src="../res/img/img122.png" width="600"/>
</p>

# 7 Hugging Face

## 7.1 Introduction

<p align="center">
  <img src="../res/img/img123.png" width="500"/>
  <img src="../res/img/img124.png" width="500"/>
</p>

- Fine-tune

<p align="center">
  <img src="../res/img/img125.png" width="500"/>
</p>

## 7.2 Pipeline

- Tasks

<p align="center">
  <img src="../res/img/img126.png" width="500"/>
  <img src="../res/img/img127.png" width="500"/>
</p>

- Checkpoints

<p align="center">
  <img src="../res/img/img128.png" width="500"/>
</p>

- Model hub

<p align="center">
  <img src="../res/img/img129.png" width="500"/>
</p>
