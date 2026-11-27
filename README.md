# Clustering and Classification with Python

Practical machine learning notebooks exploring customer segmentation and Iris species classification.

## Examples

| Notebook | Task | Method |
| --- | --- | --- |
| [Customer segmentation](Code_Mall.ipynb) | Unsupervised learning | K-means |
| [Iris classification](code_iris.ipynb) | Supervised learning | Nearest-neighbor classification |

## Getting started

Clone this repository and open the notebooks in Jupyter:

```bash
git clone https://github.com/AliRezaKhatibi/Clustering.git
cd Clustering
python -m pip install jupyter numpy pandas matplotlib scikit-learn
jupyter notebook
```

Check the notebook imports and dataset paths before executing all cells. The dependency list above is a starting point, not a tested lockfile.

## Learning objectives

- Understand the distinction between clustering and classification.
- Explore feature selection for tabular datasets.
- Compare unsupervised customer segmentation with supervised species prediction.

## Original project notes

# Clustering
Using Kmeans and Kneighbors algorithm for clustering Iris and Mall data

In the Mall_Customers dataset 
KMeans algorithm has been used for clustering by selecting the most optimal features
Code : [Code_Mall.ipynb](https://github.com/AliRezaKhatibi/Clustering/blob/3a2dac4a46d3993405f23a350cb840ceaf2df2e2/Code_Mall.ipynb)

In the iris dataset 
From Neighbors algorithm in the direction of clustering by choosing the most optimal features in order to classify this plant into three categories:
Iris-setosa, Iris-versicolor, Iris-virginica have been used.
And finally, a prediction model has been built by giving four characteristics:
SepalLengthCm, 
SepalWidthCm,
PetalLengthCm,
PetalWidthCm,
It is possible to determine the type of plant with good accuracy.
Code: [code_iris.ipynb](https://github.com/AliRezaKhatibi/Clustering/blob/3a2dac4a46d3993405f23a350cb840ceaf2df2e2/code_iris.ipynb)

