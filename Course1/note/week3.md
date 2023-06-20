# Week3

# 1 Vector Space Models

<p align="center">
  "You shall know a word by the compay it keeps" -- Firth 1957
</p>

## 1.1 Word by Word / Word by Document

- Word by word design

<p align="center">
  <img src="../res/img/img56.png" width="600"/>
</p>

- Word by document design

<p align="center">
  <img src="../res/img/img57.png" width="500"/>
  <img src="../res/img/img58.png" width="500"/>
</p>

# 2 Distance Formula

## 2.1 Euclidean Distance

- Biased by the size difference between the representations

<p align="center">
  <img src="../res/img/img59.png" width="500"/>
  <img src="../res/img/img60.png" width="500"/>
</p>

## 2.2 Cosine Similarities

- **ISN'T** biased by the size difference between the representations

```Python
cosine_similarity = np.dot(a, b) / (np.linalg.norm(a) * np.linalg.norm(b))
```

<p align="center">
  <img src="../res/img/img61.png" width="500"/>
  <img src="../res/img/img62.png" width="500"/>
</p>

## 2.3 Manipulating Words in Vector Space

<p align="center">
  <img src="../res/img/img63.png" width="600"/>
</p>

## 2.4 Visualization and PCA

### 2.4.1 Visualization

<p align="center">
  <img src="../res/img/img64.png" width="500"/>
  <img src="../res/img/img65.png" width="500"/>
</p>

### 2.4.2 PCA

- Get uncorrelated features
- Reduce dimensions while retaining as much information as possible

<p align="center">
  <img src="../res/img/img66.png" width="600"/>
</p>

- Eigenvector: uncorrelated features for your data
- Eigenvalue: the amount of information retained by each feature
- Dot product gives the projection on uncorrelated features

<p align="center">
  <img src="../res/img/img67.png" width="500"/>
  <img src="../res/img/img68.png" width="500"/>
</p>
