# Graph_neural_network

Graph Neural Network, as how it is called, is a neural network that can directly be applied to graphs. It provides a convenient way for node level, edge level, and graph level prediction task.

There are mainly three types of graph neural networks in the literature:

Recurrent Graph Neural Network,

Spatial Convolutional Network,

Spectral Convolutional Network

The problems that GNN solve can be broadly classified into three categories:

1.Node Classification.
2.Link Prediction.
3.Graph Classification.

#GNN in Natural Language Processing:

GNN utilized the inner relations of words or documents to predict the categories. For example, the citation network is trying to predict the label of each paper in the network given by the paper citation relationship and the words that are cited in other papers. It can also build a syntactic model by looking at different parts of a sentence instead of purely sequential as in RNN or LTSM.


#GNN in Computer Vision:

One successful employment of GNN in CV is using graphs to model the relationships between objects detected by a CNN based detector. After objects are detected from the images, they are then fed into a GNN inference for relationship prediction. The outcome of the GNN inference is a generated graph that models the relationships between different objects.


![image](https://user-images.githubusercontent.com/65480772/208359847-f0aaf929-828a-4956-bd07-368edcb5d9ad.png)

The traditional way of image generation is text-to-image generation using GAN or autoencoder. Instead of using text for image description, graph to image generation provides more information on the semantic structures of the images.

![image](https://user-images.githubusercontent.com/65480772/208361951-d1def2d9-cf0c-41df-a49e-cebbcdda54a4.png)


GNN in Other Domains
More practical applications of GNN include human behavior detection, traffic control, molecular structure study, recommender system, program verification, logical reasoning, social influence prediction, and adversarial attack prevention.


References:
F.Scarselli, M.Gori, “The graph neural network model,” IEEE Transactions on Neural Networks, 2009

T. N. Kipf and M. Welling, “Semi-supervised classification with graph convolutional networks,” in Proc. of ICLR, 2017.

Z. Wu, S. Pan, F. Chen, G. Long, C. Zhang, Philip S. Yu, “A Comprehensive Survey on Graph Neural Networks”, arXiv:1901.00596

D. Xu, Y. Zhu, C. B. Choy, and L. Fei-Fei, “Scene graph generation by iterative message passing,” in Proc. of CVPR, vol. 2, 2017

J. Johnson, A. Gupta, and L. Fei-Fei, “Image generation from scene graphs,” in Proc. of CVPR, 2018

X. Wang, Y. Ye, and A. Gupta, “Zero-shot recognition via semantic embeddings and knowledge graphs,” in CVPR 2018
