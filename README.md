# Applied Machine Learning in Python (UIUC — MCS-DS)

Graduate ML coursework spanning classical methods, probabilistic graphical models, EM algorithms, and deep learning. All notebooks render directly in GitHub — click any link to read without downloading or running Jupyter.

---

## Assignments

| Week | Topic | Key Techniques | View |
|---|---|---|---|
| W01 | NumPy Foundations | Vectorized operations, broadcasting, array manipulation | [notebook](Assignments/W01_Practice%20Programming%201B%20Numpy.ipynb) |
| W02 | Basic Classification | Nearest neighbor, Naive Bayes, decision boundaries | [notebook](Assignments/BasicClassification.ipynb) · [pdf](Assignments/W02BasicClassification.pdf) |
| W03 | Image Classification | Naive Bayes + Random Forests on image data | [notebook](Assignments/W03ClassifyingImages.ipynb) · [pdf](Assignments/W03-ClassifyingImages.pdf) |
| W04 | SVM with SGD | Stochastic gradient descent SVM, large-scale classification | [notebook](Assignments/W04-SGDSVM.ipynb) |
| W05 | Regression | Multiple linear regression, OLS, residual diagnostics | [notebook](Assignments/W05Regression.ipynb) · [pdf](Assignments/W05Regression.pdf) |
| W06 | Regularized Regression | GLMnet — Lasso, Ridge, Elastic Net, cross-validated λ selection | [notebook](Assignments/GLMnet.ipynb) · [pdf](Assignments/W06-GLMnet.pdf) |
| W07 | Dimensionality Reduction | PCA, SVD, NIPALS, PCoA, Canonical Correlation Analysis | [notebook](Assignments/PCA.ipynb) · [pdf](Assignments/W07-PCA.pdf) |
| W08 | Clustering | k-means variants, vector quantization, cluster validation | [notebook](Assignments/Clustering.ipynb) · [pdf](Assignments/W08-Clustering.pdf) |
| W09 | High-Dimensional Classification | Multivariate Normal, Multinomial density classifiers, LDA/QDA | [notebook](Assignments/HiDimClassification.ipynb) · [pdf](Assignments/W09-HiDimClassification.pdf) |
| W10 | EM — Topic Modeling | Expectation-Maximization for latent topic models (LDA-style) | [notebook](Assignments/EMTopicModel.ipynb) · [pdf](Assignments/W10-EMTopicModel.pdf) |
| W11 | EM — Image Segmentation | EM for Gaussian Mixture Models, image segmentation | [notebook](Assignments/EMSegmentation.ipynb) · [pdf](Assignments/W11-EMSegmentation.pdf) |
| W12 | Mean Field Inference | Variational inference, Boltzmann Machines, Discrete Markov Random Fields | [notebook](Assignments/MeanField.ipynb) · [pdf](Assignments/W12-MeanField.pdf) |
| W13 | Convolutional Neural Networks | CNN architecture, backprop, image classification in PyTorch | [notebook](Assignments/CNN.ipynb) · [pdf](Assignments/W13-CNN.pdf) |

---

## What this course covers

This course goes substantially beyond classical supervised ML. The full scope:

**Supervised learning** (W02–W06): classification baselines (KNN, Naive Bayes, Random Forests), large-scale SVM via SGD, regression, and regularized regression (Lasso/Ridge/Elastic Net with cross-validated hyperparameter selection).

**Dimensionality reduction** (W07): PCA via both eigendecomposition and NIPALS iterative method, SVD, Principal Coordinate Analysis, and Canonical Correlation Analysis — relevant for high-dimensional claims and EHR feature spaces.

**Unsupervised learning** (W08): k-means and variants, vector quantization, cluster evaluation.

**Probabilistic and high-dimensional classifiers** (W09): density-based classification using multivariate Normal and Multinomial distributions; Linear and Quadratic Discriminant Analysis.

**Expectation-Maximization** (W10–W11): EM algorithm derived from first principles and applied to two domains — latent topic modeling over text/code data (W10) and Gaussian Mixture Model image segmentation (W11). EM topic modeling directly connects to the CONTENT readmission model in [DL4Health](https://github.com/mohassan99/DL4Health).

**Variational inference and graphical models** (W12): Mean Field inference, Boltzmann Machines, Discrete Markov Random Fields — the probabilistic graphical model foundations underlying modern generative models.

**Deep learning** (W13): CNN architecture, loss gradient derivation, backpropagation, and image classification in PyTorch — extended further in [DL4Health](https://github.com/mohassan99/DL4Health) with RETAIN, attention mechanisms, and autoencoders applied to clinical data.

---

## Stack
Python · scikit-learn · PyTorch · NumPy · Pandas · Matplotlib · Jupyter

## Course
Applied Machine Learning · University of Illinois Urbana-Champaign · MCS-DS (School of Engineering)
