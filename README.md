# Principal Component Analysis (PCA) on 3D Clustered Data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MaksymilianSzymczak/ML24/blob/master/nazwa_notebooka.ipynb)

## Task Description
The task involves performing PCA on a 3D dataset containing three distinct clusters. We visualize the data in 2D after dimensionality reduction and compare it with the original feature spaces.

## Results
- PCA visualization shows better separation of clusters compared to the original features.
- Standardization is necessary to avoid dominance of features with larger scales.

## Answers to Questions
### Primary Question
Perform PCA on the provided dataset to find the two principal components and visualize the data in a 2D plot using these components.

Compare this PCA plot with the following 2D plots of the original data:
- x vs. y
- x vs. z
- y vs. z

Does PCA improve the separation of data points from different clusters compared to the original feature spaces? Explain why.

**Odpowiedź:**
PCA może poprawić separację klastrów, ponieważ skupia się na kierunkach w danych, które maksymalizują wariancję. Jeśli różnice między klastrami są związane z tymi kierunkami, PCA może lepiej uwidocznić grupowanie. W porównaniu z oryginalnymi cechami, PCA eliminuje redundancję i redukuje szum, co może prowadzić do lepszej separacji.

### Secondary Question
Remember: before applying PCA, standardize the data so that each feature has a mean of 0 and a variance of 1.

Why is standardization necessary before applying PCA?

Reflect on how differences in scale among features can impact the principal component directions.

**Odpowiedź:**
Standaryzacja jest konieczna, ponieważ PCA jest wrażliwe na skalę danych. Jeśli cechy mają różne jednostki lub zakresy wartości, cechy o większej skali będą dominować w obliczeniach wariancji, co może zniekształcić kierunki głównych składowych. Standaryzacja zapewnia, że każda cecha ma równy wpływ na analizę.

---

## How to Run the Notebook?
1. Click the **"Open in Colab"** button above to open the notebook in Google Colab.
2. Run all cells to see the results.
