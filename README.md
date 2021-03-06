# TRL: Tensor rank learning in CP decomposition via convolutional neural network
Tensor factorization is a useful technique for capturing the high-order interactions in data analysis. One assumption of tensor decompositions is that a predefined rank should be known in advance. However, the tensor rank prediction is an NP-hard problem. The CANDECOMP/PARAFAC (CP) decomposition is a typical one. In this paper, we propose two methods based on convolutional neural network (CNN) to estimate CP tensor rank from noisy measurements. One applies CNN to the CP rank estimation directly. The other one adds a pre-decomposition for feature acquisition, which inputs rank-one components to CNN. Experimental results on synthetic and real-world datasets show the proposed methods outperforms state-of-the-art methods in terms of rank estimation accuracy.

# Notes:
1. We use 50 × 50 × 50 synthetic dataset with 20dB noise level in this demo. The ranks range from 50 to 100.
2. The predefined rank bound of pre-decomposition of TRN-PD method is 110.
3. The dataset of this demo can be downloaded in https://drive.google.com/drive/folders/1Q-yjBoRHQ4N0Um1IJcIf_xMQINLfGxUg?usp=sharing

# Reference:
M. Zhou, Y. Liu, Z. Long, L. Chen, C. Zhu, Tensor rank learning in CP decomposition via convolutional neural network, Signal Processing: Image Communication, 2018, DOI: doi.org/10.1016/j.image.2018.03.017. online available at: https://www.sciencedirect.com/science/article/pii/S0923596518302741
