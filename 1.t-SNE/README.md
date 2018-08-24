# t-SNE on Amazon Fine Food Reviews

**t-SNE(t-distributed stochastic neighbor embedding)** is a machine learning algorithm for visualization developed by Laurens van der Maaten and Geoffey Hinton. It is a non-linear dimensionality reduction technique to embed high-dimensional data in a low-dimensions for visualization.<br>

There are other dimensionality reduction techniques like **Truncated-SVD** and **Principal Component analysis(PCA)** etc. But they are used for feature extraction or feature selection. t-SNE on the other hand is used specifically for high-dimensional data visualization in a lower-dimension(2-D or 3-D).<br>

t-SNE preserves **local structure** of the data. Here, i'm performing t-SNE on [Amazon Fine Food Reviews dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews). But, Here i will show the **crowding-problem** in t-SNE i.e sometime it is not possible to preserve local neighborhood. In such cases t-SNE is used to address the problem.

### Some useful links to learn more about t-SNE
1. [Detailed Data Visualization using t-SNE by Google](https://experiments.withgoogle.com/visualizing-high-dimensional-space)
2. [For visual Interpretation](distill.pub/2016/misread-tsne)
