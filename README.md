## PyTorch_CIFAR10_Training
CIFAR10 dataset training, val. and testing with different Models and evaluating them. Use CNN, Resnet ...


## The CIFAR-10 dataset

The `CIFAR-10` dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.  
  
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


<img
  src="![image](https://github.com/zero-suger/PyTorch_CIFAR10-MNIST-datasets_Training_Testing/assets/63332872/c4295b21-110e-4746-88d3-93b339476885)
"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">



NN LR (custom model) --> 11 Epoches  --> 16 ~ 18%

CNN (VGG custom) --> 11 Epoches  --> 61 ~ 64%

ResNet (resnet18) --> 11 Epoches  --> 91~97,8%
