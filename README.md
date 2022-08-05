# Classification of technical papers using Graph Convolutional Neural Networks

- Classified 2708 research papers into 7 classes, based on their research areas.
- I have build Graph Convolution Networks (GCN) with Spektral API, a Python toolkit for graph deep learning based on Tensorflow 2. Using the CORA dataset, I performed Semi-Supervised Node Classification.
- A comparison of its implementation with CNN showed that GNN outperformed CNN.

### Dataset
The cora dataset consists of two files:
Cora.content: In this file in each row:
	First element is the paper ID followed by the 0 or one representing whether the node contains the particular feature or not.
	Last element is the class label.
Cora.cites:
In each row first element is the paperID that is source and second element is the paperID that cites the first element. We are going to form an edge between these two.

https://relational.fit.cvut.cz/dataset/CORA

### Result with GCNN

![image](https://user-images.githubusercontent.com/103813206/182972736-bc082f17-541b-4702-bf24-8eb16768fe3f.png)

### Result with CNN

![image](https://user-images.githubusercontent.com/103813206/182972902-e9f80085-b91e-4763-afee-0d275ba82fe7.png)



