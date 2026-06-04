# Applied Machine Learning in Python
**University of Illinois Urbana-Champaign · Master of Computer Science (Data Science)**

Thirteen programming assignments spanning the full arc of machine learning — from building classifiers from scratch using only NumPy, through probabilistic models and clustering, to training neural networks in PyTorch. Each entry links directly to the rendered notebook (HTML) and the source code (ipynb).

---

## W13 — Teaching a Computer to Recognize Images with Neural Networks
A convolutional neural network (CNN) is a type of AI modeled loosely on how the human visual system works — it learns to detect edges, shapes, and patterns in images automatically. Here, CNNs were built and trained from scratch in PyTorch to classify photos from two benchmark datasets: CIFAR-10 (10 categories of objects) and MNIST (handwritten digits). The architecture was tuned to push classification accuracy as high as possible.

[📓 Notebook](CNN.ipynb) · [🌐 HTML](W13-CNN.html)

---

## W12 — Cleaning Up Noisy Images Using Probabilistic Reasoning
Mean Field inference is a technique for making educated guesses about missing or corrupted information by looking at the surrounding context — similar to how you can often read a word even if one letter is smudged. Here it was applied to restore MNIST digit images that had been randomly flipped to noise, using a probabilistic graphical model that considers each pixel's neighbors when deciding what value it should have.

[📓 Notebook](MeanField.ipynb) · [🌐 HTML](W12-MeanField.html)

---

## W11 — Segmenting Images by Color Using the EM Algorithm
Image segmentation is the process of dividing an image into regions that belong together — for example, separating the sky from the ground in a photo. Here the Expectation-Maximization (EM) algorithm was implemented from scratch to group pixels by their color into clusters, producing segmented versions of test images at 10, 20, and 50 segments. Five different random starting points were tested on a sunset image to study how sensitive the results are to initialization.

[📓 Notebook](EMSegmentation.ipynb) · [🌐 HTML](W11-EMSegmentation.html)

---

## W10 — Discovering Hidden Themes in Text Using the EM Algorithm
Topic modeling is a technique for automatically discovering the underlying themes in a collection of documents — without being told what those themes are in advance. The EM algorithm was implemented from scratch to find latent topics across a text corpus, learning which words tend to appear together and what each topic is "about." This is the same probabilistic framework used in the CONTENT clinical readmission model in [DL4Health](https://github.com/mohassan99/DL4Health-CONTENT).

[📓 Notebook](EMTopicModel.ipynb) · [🌐 HTML](W10-EMTopicModel.html)

---

## W09 — Classifying Data When There Are Thousands of Variables
When data has hundreds or thousands of features — like gene expression data or medical records — standard classifiers break down. This assignment implemented density-based classifiers that model the full statistical distribution of each class using multivariate probability distributions, then assign new observations to the class whose distribution they fit best. Scored 100% on the autograder.

[📓 Notebook](HiDimClassification.ipynb) · [🌐 HTML](W09-HiDimClassification.html)

---

## W08 — Grouping Data Without Labels (Clustering)
Clustering finds natural groupings in data without any predefined categories — useful for customer segmentation, anomaly detection, or exploratory analysis. The k-means algorithm and several of its variants were implemented, along with vector quantization, a technique used in data compression. Scored 100% on the autograder.

[📓 Notebook](Clustering.ipynb) · [🌐 HTML](W08-Clustering.html)

---

## W07 — Reducing Complexity: Finding the Signal in High-Dimensional Data
When data has too many variables, it becomes hard to visualize, analyze, or model. Principal Component Analysis (PCA) finds the directions in the data that capture the most variation, allowing you to represent the data in far fewer dimensions without losing much information. Multiple approaches were implemented including SVD, NIPALS (an iterative method used in chemometrics), and Principal Coordinate Analysis. Scored 100% on the autograder.

[📓 Notebook](PCA.ipynb) · [🌐 HTML](W07-PCA.html)

---

## W06 — Smarter Regression: Automatically Selecting the Most Useful Variables
Standard regression uses all available variables equally, which can lead to overfitting — a model that memorizes the training data but fails on new data. GLMnet (Lasso, Ridge, and Elastic Net) adds a penalty for complexity, automatically shrinking unimportant variables toward zero and selecting the most predictive ones. The optimal penalty strength was chosen using cross-validation. Scored 100% on the autograder.

[📓 Notebook](GLMnet.ipynb) · [🌐 HTML](W06-GLMnet.html)

---

## W05 — Predicting a Number: Linear Regression
Regression is the task of predicting a continuous outcome — like a price, a score, or a measurement — from a set of input variables. Multiple linear regression was implemented from scratch, including ordinary least squares fitting, residual diagnostics, and model evaluation. Scored 96% on the autograder.

[📓 Notebook](W05Regression.ipynb) · [🌐 HTML](W05Regression.html)

---

## W04 — Teaching a Computer to Draw a Boundary: SVM with Gradient Descent
A Support Vector Machine (SVM) finds the best dividing line (or boundary) between two categories in data — for example, spam vs. not spam. Training a standard SVM on large datasets is slow, so this assignment implemented it using Stochastic Gradient Descent (SGD), which updates the model incrementally on one example at a time, making it practical at scale. Scored 82% on the autograder.

[📓 Notebook](W04-SGDSVM.ipynb) · [🌐 HTML](W04-SGDSVM.html)

---

## W03 — Recognizing What's in a Photo
Image classification is the task of teaching a computer to look at a photo and say what's in it. Two approaches were compared: Naive Bayes (a probabilistic model that treats each pixel independently) and Random Forests (an ensemble of decision trees that vote on the answer). The tradeoffs in accuracy, speed, and interpretability between the two were explored.

[📓 Notebook](W03-ClassifyingImages.ipynb) · [🌐 HTML](W03-ClassifyingImages.html)

---

## W02 — The Basics of Classification: Teaching a Computer to Tell Things Apart
Classification is one of the most fundamental tasks in machine learning — given a set of inputs, predict which category they belong to. Three foundational approaches were implemented from scratch: K-Nearest Neighbors (which classifies by looking at similar examples), Naive Bayes (a probabilistic classifier), and decision boundary visualization to understand what each model is actually learning.

[📓 Notebook](NaiveBayesClassification.ipynb) · [🌐 HTML](W02BasicClassification.html)

---

## W01 — The Engine Under the Hood: NumPy and Vectorized Computing
Before building any machine learning model, you need to be able to work with data efficiently. NumPy is Python's core library for numerical computation — it allows operations on entire arrays of numbers at once instead of looping through them one by one, making code orders of magnitude faster. This assignment covered vectorization, broadcasting, matrix operations, and the mathematical foundations that underlie all subsequent work.

[📓 Notebook](W01_Practice%20Programming%201B%20Numpy.ipynb)

---

## Tech Stack
Python · NumPy · PyTorch · scikit-learn · Pandas · Matplotlib · Jupyter
