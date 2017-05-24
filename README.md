# Fine-tune Convolutional Neural Network in Keras with ImageNet Pretrained Models

The reason to create this repo is that there are not many online resources that provide sample codes for performing fine-tuning, and that there is not a centralized place where we can easily download ImageNet pretrained models for common ConvNet architectures such as VGG, Inception, ResNet, and DenseNet.

See [this](https://flyyufelix.github.io/2016/10/03/fine-tuning-in-keras-part1.html) for a comprehensive treatment of fine-tuning Deep Learning Models in Keras

## ImageNet Pretrained Models

Network|Theano|Tensorflow
:---:|:---:|:---:
VGG-16 | [model (553 MB)](https://drive.google.com/file/d/0Bz7KyqmuGsilT0J5dmRCM0ROVHc/view?usp=sharing)| -
VGG-19 | [model (575 MB)](https://drive.google.com/file/d/0Bz7KyqmuGsilZ2RVeVhKY0FyRmc/view?usp=sharing)| -
GoogLeNet (Inception-V1) | [model (54 MB)](https://drive.google.com/open?id=0B319laiAPjU3RE1maU9MMlh2dnc)| -
Inception-V3 | [model (95 MB)](https://github.com/fchollet/deep-learning-models/releases/download/v0.2/inception_v3_weights_th_dim_ordering_th_kernels.h5)| -
Inception-V4 | [model (172 MB)](https://github.com/kentsommer/keras-inceptionV4/releases/download/2.0/inception-v4_weights_th_dim_ordering_th_kernels.h5)| [model (172 MB)](https://github.com/kentsommer/keras-inceptionV4/releases/download/2.0/inception-v4_weights_tf_dim_ordering_tf_kernels.h5)
ResNet-50 | [model (103 MB)](https://github.com/fchollet/deep-learning-models/releases/download/v0.2/resnet50_weights_th_dim_ordering_th_kernels.h5)| [model (103 MB)](https://github.com/fchollet/deep-learning-models/releases/download/v0.2/resnet50_weights_tf_dim_ordering_tf_kernels.h5)
ResNet-101 | [model (179 MB)](https://drive.google.com/file/d/0Byy2AcGyEVxfdUV1MHJhelpnSG8/view?usp=sharing)| [model (179 MB)](https://drive.google.com/file/d/0Byy2AcGyEVxfTmRRVmpGWDczaXM/view?usp=sharing)
ResNet-152 | [model (243 MB)](https://drive.google.com/file/d/0Byy2AcGyEVxfZHhUT3lWVWxRN28/view?usp=sharing)| [model (243 MB)](https://drive.google.com/file/d/0Byy2AcGyEVxfeXExMzNNOHpEODg/view?usp=sharing)
DenseNet-121 | [model (32 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfMlRYb3YzV210VzQ)| [model (32 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfSTA4SHJVOHNuTXc)
DenseNet-169 | [model (56 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfN0d3T1F1MXg0NlU)| [model (56 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfSEc5UC1ROUFJdmM)
DenseNet-161 | [model (112 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfVnlCMlBGTDR3RGs)| [model (112 MB)](https://drive.google.com/open?id=0Byy2AcGyEVxfUDZwVjU2cFNidTA)

## Requirements

* Keras 2.0.3
* TensorFlow 1.1.0
