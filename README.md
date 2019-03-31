# "Understanding Models Through The Training Data"

In this repository, we replicated some of the experiments discussed in Koh et al's paper titled "[Understanding Black-box Predictions via Influence Functions](https://arxiv.org/abs/1703.04730)". The original code can be found here: http://bit.ly/gt-influence.

We focused on two use cases of influence functions discussed in the paper:
1. Understanding model behavior
2. Debugging domain mismatch

For each task, we replicated the results presented in the paper and implemented additional experiments using other datasets or other models. For a more detailed description of our work and our findings, kindly refer to the [report](https://github.com/radaimi/Understanding-Models-Through-The-Training-Data/blob/master/Understanding%20Models%20Through%20The%20Training%20Data.pdf).

The datasets and model weights used for the first application "Understanding model behavior" can be downloaded:
1. [Inception V3 weights](https://github.com/fchollet/deep-learning-models/releases/download/v0.5/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5)
2. [Inception ResNet V2 weights](https://www.kaggle.com/keras/inceptionresnetv2)
3. [DogFish Dataset](https://worksheets.codalab.org/bundles/0x550cd344825049bdbb865b887381823c) (From Koh's replication package of the paper) 

