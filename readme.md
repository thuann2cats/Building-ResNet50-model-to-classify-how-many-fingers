In this [experiment](G_Residual_Networks.ipynb), I built a deep convolutional network with residual blocks as introduced by [He et al.](https://arxiv.org/pdf/1512.03385.pdf), using the starting code, hints, dataset and utility functions from the [Convolutional Neural Networks](https://coursera.org/learn/convolutional-neural-networks) course (offered by DeepLearning.AI on Coursera).

I built a ResNet-50 model with TensorFlow to classify how many fingers in an image, as described in this figure (from Coursera), which is comprised of identity blocks and convolutional blocks:
![resnet_kiank.png](images%2Fresnet_kiank.png)

The identity blocks and residual blocks have skip connections to prevent the vanishing/exploding gradient problems:

Identity block:
![idblock2_kiank.png](images%2Fidblock2_kiank.png)

Convolutional block:
![convblock_kiank.png](images%2Fconvblock_kiank.png)


