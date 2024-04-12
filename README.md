# Adaptive Set-level Metric for Few-Shot Image Classification
Few-shot image classification aims to learn a classifier from limited labeled data.  Though the existing methods have achieved significant improvement, they are still challenging to accurately differentiate image categories between the confused support and query samples.  To this end, we propose to represent each image using a set of feature embeddings instead of only one image-level feature, by which allowing the network to aggregate more rich and useful features from different views of the image.  Furthermore, we propose a set-based metric approach with a dynamic self-adapting weighting mechanism to measure the similarity between the two sets of image embeddings (the query set and the support set).  The experimental results demonstrate the effectiveness of the proposed method, achieving state-of-the-art performance in miniImageNet, tieredImageNet, and CUB dataset.
