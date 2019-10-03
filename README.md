# mnist-tsne
this is a repo for the visualizing MNIST dataset using TSNE and PCA methods
After the data preprocessing steps , I applied T-SNE to the dataset which was containg 784 diamensions and TSNE was capable of seperating the data(0-9) from one another which was not possible with PCA.

![](giphy.gif)

As we all know @d visualization is a challenge in itself, when we have multi diamensional data, it becomes quite difficult to visualize it(because of the complexity arsing with diamensionality reduction).

But the problem becomes worse if the diamesnssions become greater then 10.
In this dataset the data is 784D.Hence, methods like PCA will fail.

T-sne stands for t- Stocastic Neighborhood Embedding. It solves this problem by taking into account the features of data and how they all are related to one another, Which in turn makes much better cluseters than PCA.
