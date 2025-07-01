# Gene Expression Prediction via Deep Learning Regression

This repository demonstrates the application of deep learning techniques for predicting gene expression levels from high-dimensional transcriptomic data, following the methodology presented in the [D-GEX study](https://academic.oup.com/bioinformatics/article/32/12/1832/1743989).

## 🔗 Data Download

To get started, please download the preprocessed dataset from the following link and place it in this directory:

👉 [Download Dataset](https://gocuhk-my.sharepoint.com/:u:/g/personal/yuli_cuhk_edu_hk/EfRg6fmt3lNPlTvPS9tz7fsBRp_aOPn9wHQQRkO1MecBYw?e=qLYigj)

This dataset is derived from the **Gene Expression Omnibus (GEO)** repository and has undergone standardized normalization procedures, consistent with the processing pipeline described in the original D-GEX publication.

## 🔬 Overview

In this example, we apply **deep learning regression models** to predict gene expression values using transcriptomic profiles. Inspired by the [D-GEX framework](https://academic.oup.com/bioinformatics/article/32/12/1832/1743989), our objective is to infer the expression levels of unmeasured target genes from a subset of landmark genes.

We implement a **deep, fully connected neural network** using [Keras](https://keras.io/), demonstrating how modern deep learning tools can be effectively leveraged for high-dimensional biological data analysis.

## 🧠 Model Architecture

- **Input**: Normalized expression levels of landmark genes  
- **Output**: Continuous values corresponding to target gene expressions  
- **Architecture**: Deep feedforward neural network  
- **Activation Functions**:  
  - Hidden layers: ReLU  
  - Output layer: TanH (used instead of Softmax for regression)  
- **Loss Function**: Mean Squared Error (MSE), appropriate for continuous-valued prediction tasks

The network is concise and computationally efficient—requiring just **10 lines of Keras code** to define and train.

## ⚙️ Performance

- **Training Environment**: NVIDIA Titan X GPU  
- **Training Time**: Approximately 2 minutes  
- **Performance Benchmark**:  
  The deep learning model achieves a **4.5% improvement** in predictive accuracy over traditional linear regression approaches, evaluated on a randomly selected target gene.

## 📚 References

- Chen, Y. et al. (2016). [Gene expression inference with deep learning](https://academic.oup.com/bioinformatics/article/32/12/1832/1743989), *Bioinformatics*, 32(12), 1832–1839.  
- D-GEX GitHub Repository: [https://github.com/uci-cbcl/D-GEX](https://github.com/uci-cbcl/D-GEX)

---

This project serves as a practical introduction to using deep learning for regression tasks in genomics, highlighting the potential of data-driven approaches in computational biology and transcriptomic analysis.
