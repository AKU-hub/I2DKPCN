# Incremental Two-dimensional Kernel PCA-based Convolutional Network (APIN 2022)
This is the official implementation of the paper ["I2DKPCN: an unsupervised deep learning network"](https://link.springer.com/article/10.1007/s10489-021-03007-9).

Code is under preparation, please be patient.

> **Abstract:** *In this paper, we proposed an incremental two-dimensional kernel PCA-based convolutional network (I2DKPCN) which 
is a novel unsupervised deep learning network. In our architecture, I2DKPCN consists of several feature extraction stages and
one output stage, and each feature extraction stage includes a convolutional layer, a feature pooling layer and a feature fusion
layer. In the output stage, binary hashing and blockwise histograms are exploited for the generation of the final features. In
particular, the filters of the convolutional layer are learned by using incremental two-dimensional kernel principal component
analysis(I2DKPCA) rather than the gradient-based optimization. Due to the fact that the back propagation is not used to
learn the parameters of the filter, the calculation speed of I2DKPCN is much faster than that of the existing deep network. We
have extensively tested I2DKPCN on multiple data sets for three challenging tasks, including hand-written digit recognition,
texture classification and face recognition. It can be seen from the results that I2DKPCN performs competitively or even
better compared with other networks in all tests. Because the filters are learned by I2DKPCA, which combined the 2DPCA
with kernel method and incremental learning, the non-linear problem was solved and the computational time was reduced.*  

## Network Architecture
![framework](https://github.com/AKU-hub/I2DKPCN/blob/master/%20figs/framework.png)
## Training and Inference
![framework](https://github.com/AKU-hub/I2DKPCN/blob/master/%20figs/train.png)
