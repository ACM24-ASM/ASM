#  [Adaptive Set-level Metric for Few-Shot Image Classification](https://github.com/xznuist/ASM/)
![f2](https://github.com/xznuist/ASM/assets/85595552/2d55473c-5f63-4d37-8345-8b240eb0e3fa)



Few-shot image classification aims to learn a classifier from limited labeled data.  Though the existing methods have achieved significant improvement, they are still challenging to accurately differentiate image categories between the confused support and query samples.  To this end, we propose to represent each image using a set of feature embeddings instead of only one image-level feature, by which allowing the network to aggregate more rich and useful features from different views of the image.  Furthermore, we propose a set-based metric approach with a dynamic self-adapting weighting mechanism to measure the similarity between the two sets of image embeddings (the query set and the support set).  The experimental results demonstrate the effectiveness of the proposed method, achieving state-of-the-art performance in miniImageNet, tieredImageNet, and CUB dataset.

## Dependencies
In the evaluations, we used Cuda 11.0 with the following list of dependencies:
1. Python 3.8.10; 
2. Numpy 1.21.2; 
3. PyTorch 1.9.1+cu111; 
4. Torchvision 0.10.1; 
5. PIL 7.0.0; 
6. Einops 0.3.0.

 ## explain
 Our implementation code and details will be updated after the paper is included.

 
