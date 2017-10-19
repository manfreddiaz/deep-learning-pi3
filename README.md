# Pytorch Pre-trained Convolutional Neural Networks Models Benchmark on Raspberry PI 3
## Instructions
[DRAFT] Put here a link to Florian's gist for compiling PyTorch on a Raspberry PI 3.
Installation requirements.
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
