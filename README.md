# Multilabel Classification for Remote Sensing Images

Author : Cheng Huang, Haoyu Guo, Zhiwei Zeng

## Abstract

Deep Neural network(DNN) has already shown us the great ability to do the classification task. In this paper, we investigate the use of transfer learning on a multi-labeled remote sensing images dataset by using the pre-trained deep convolutional neural network VGG16 model. A typical problem with the multi-label classification task that we often encountered is the imbalance of the positive and negative labels. To handle this problem, we use three different loss functions on our multi-label classification task, which are binary cross-entropy loss, focal loss, and asymmetric loss respectively. We show that using the focal loss and the asymmetric loss can help us better solve the multi-label classification task by improving the micro F1 score 24.2% and 22.7% separately compared with the baseline model with the binary cross-entropy loss. The source code and the output are available at https://github.com/kouteisang/ImageMultilabelClassification

## Example

<img width="504" alt="image" src="https://user-images.githubusercontent.com/80028318/205495091-d39b35bd-6370-47d3-a79e-ebd22e3cacd9.png">

