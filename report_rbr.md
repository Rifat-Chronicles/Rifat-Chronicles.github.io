# Introduction to Deep Learning - Homework 1
**Student Name:** Rifat  
**Date:** Feb 16, 2026

---

## Problem 1: Manual Calculation
*(My manual calculations are attached on the following page)*

1. **For K=1:** The class is ...
2. **For K=2:** The class is ...
3. **For K=3:** The class is ...

---

## Problem 2: Simple KNN (miniknn.py)

### Description
In this problem, I implemented a KNN classifier for 2D data points. The algorithm calculates the Euclidean distance between test points and training data, sorts them, and uses majority voting to classify.

### Source Code
@import "miniknn_1.py" {class="line-numbers"}

### Execution Output
@import "Output_1.txt"

### Visualization
![Generated Graph](miniknn.png)

---

## Problem 3: MNIST Digit Recognition (knn.py)

### Description
For this problem, I extended the logic to 28x28 pixel images. I flattened the images into vectors and calculated L2 distance to find the nearest handwritten digits.

### Source Code
@import "knn.py" {class="line-numbers"}

### Execution Output
@import "knn_output.txt"