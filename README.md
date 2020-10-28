# LeNet-5
Reference：
LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998). Gradient-based learning applied to document recognition. Proceedings of the IEEE, 86(11), 2278-2324.

CIFAR10 (at least 60% test accuracy) and MNIST(at least 99% test accuracy)

Stochastic gradient descent method applies in this model. 

* Pytorch
* Running on GPU
* Codes contain dataloader 

For CIFAR10:
* 30 epochs
* Learning rate schedule by 10 every 10 epochs
* Weight decay
* Data normalization

For MNIST:
* 20 epochs
* Learning rate schedule by 10 every 10 epochs
* Weight decay

