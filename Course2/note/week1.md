# Week 1

# 1 Autocorrect

## 1.1 Introduction

- Workflow

<p align="center">
  <img src="../res/img/img1.png" width="500"/>
  <img src="../res/img/img2.png" width="500"/>
</p>

## 1.2 Building The Model

1. Identify a misspelled word

<p align="center">
  <img src="../res/img/img3.png" width="600"/>
</p>

2. Find strings n edit distance away (n usually be 1~3 in autocorrect)

<p align="center">
  <img src="../res/img/img4.png" width="500"/>
  <img src="../res/img/img5.png" width="500"/>
</p>

3. Filter candidates (if candidates are not in the dictionary, drop them and finally we will get a list of avaliable candidates)

<p align="center">
  <img src="../res/img/img6.png" width="600"/>
</p>

4.
