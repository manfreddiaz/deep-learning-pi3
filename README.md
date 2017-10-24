# Pytorch Pre-trained Convolutional Neural Networks Models Benchmark on Raspberry PI 3
## Instructions
[DRAFT] Put here a link to Florian's gist for compiling PyTorch on a Raspberry PI 3.
Installation requirements.
## Settings (from pytorch documentation)
* All pre-trained models expect input images normalized in the same way: 3-channel RGB images of shape (3 x H x W), where H and W are expected to be at least 224.
* The images have to be loaded in to a range of [0, 1] and then normalized using mean=[0.485, 0.456, 0.406] and std=[0.229, 0.224, 0.225]
## Results
Average (over 10 iterations) inference time of some pre-trained CNN models on a Raspberry Pi 3 Model B.

| Model  | Inference (ms) | Memory Footprint |
| ------------- | :-------------: | :---------------: |
| [Squeezenet v1.1](https://arxiv.org/abs/1602.07360)  | 546  |
| [Resnet18](https://arxiv.org/abs/1512.03385)  | 1622 |
| [AlexNet](https://arxiv.org/abs/1404.5997) | 847 |   |
| [VGG11](https://arxiv.org/abs/1409.1556)\* | NR |  |
| [Inception v3]() \*| NR | |

\* DON'T RISK YOUR PI: do not run 10 iterations of these models.
