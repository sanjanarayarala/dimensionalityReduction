# Dimensionality Reduction

## 📌 Overview
This repository explores **dimensionality reduction techniques** applied to the **MNIST dataset**, including:
- **Principal Component Analysis (PCA)**
- **Linear Discriminant Analysis (LDA)**
- **t-Distributed Stochastic Neighbor Embedding (t-SNE)**
- **Uniform Manifold Approximation and Projection (UMAP)**

Each technique is implemented in a separate Jupyter Notebook:
- `pca.ipynb` – PCA
- `lda.ipynb` – LDA
- `t-sne.ipynb` – t-SNE
- `umap.ipynb` – UMAP

---

## 📖 About the MNIST Dataset
MNIST (**Modified National Institute of Standards and Technology**) is a dataset of **handwritten digits (0-9)**. It consists of:
- **70,000 grayscale images** (28×28 pixels each)
- **60,000 training samples** and **10,000 test samples**
- **Each image is labeled** (digits from 0 to 9)

MNIST is widely used for benchmarking **machine learning and deep learning** models.

---

## 🚀 What is Dimensionality Reduction?
Dimensionality reduction is the process of reducing the number of features in a dataset while preserving its meaningful structure. This helps in:
- **Reducing computational complexity**
- **Eliminating redundant features**
- **Improving visualization (2D/3D)**
- **Enhancing classification performance**

### 🔹 Types of Dimensionality Reduction
1. **Feature Selection** – Selecting relevant features and removing irrelevant ones.
2. **Feature Extraction** – Transforming data into a lower-dimensional space (e.g., PCA, LDA, t-SNE, UMAP).

---

## 📌 Techniques Covered in This Repository
### **1️⃣ Principal Component Analysis (PCA)**
- **Unsupervised** technique
- Maximizes variance while reducing dimensions (variance determines how much information it carries!)
- Does **not** use class labels
- Commonly used for data compression and noise reduction

📄 **Notebook**: [`pca.ipynb`](pca.ipynb)

---

### **2️⃣ Linear Discriminant Analysis (LDA)**
- **Supervised** technique
- Maximizes class separability
- Uses **labels** to improve classification performance
- Limited to at most **(C-1) components** (where C = number of classes)

📄 **Notebook**: [`lda.ipynb`](lda.ipynb)

---

### **3️⃣ t-Distributed Stochastic Neighbor Embedding (t-SNE)**
- **Unsupervised** technique
- Preserves local relationships between data points
- Non-linear method ideal for visualization
- Computationally expensive

📄 **Notebook**: [`t-sne.ipynb`](t-sne.ipynb)

---

### **4️⃣ Uniform Manifold Approximation and Projection (UMAP)**
- **Unsupervised** technique
- Preserves both local and global structure
- Faster and more scalable than t-SNE
- Effective for clustering and visualization

📄 **Notebook**: [`umap.ipynb`](umap.ipynb)

---

## ⚡ Getting Started
### **1️⃣ Install Dependencies**
Ensure you have Python and the required libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn umap-learn
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/your-repo/mnist_dim_reduction.git
cd mnist_dim_reduction
```

### **3️⃣ Run Jupyter Notebook**
```bash
jupyter notebook
```
Open the desired `.ipynb` file and run the code.

---

## 🎯 Conclusion
Dimensionality reduction is crucial for handling high-dimensional datasets like MNIST. This repository demonstrates how **PCA, LDA, t-SNE, and UMAP** can be used to reduce dimensions and visualize data effectively.

🚀 **Explore, experiment, and improve!** 🚀

---

## 🔗 References
- MNIST Dataset: [OpenML](https://www.openml.org/d/554)
- PCA: [Wikipedia](https://en.wikipedia.org/wiki/Principal_component_analysis)
- LDA: [Wikipedia](https://en.wikipedia.org/wiki/Linear_discriminant_analysis)
- t-SNE: [Laurens van der Maaten’s paper](https://lvdmaaten.github.io/publications/papers/JMLR_2008.pdf)
- UMAP: [UMAP Documentation](https://umap-learn.readthedocs.io/en/latest/)

📢 Feel free to contribute and improve this repository! 😊

