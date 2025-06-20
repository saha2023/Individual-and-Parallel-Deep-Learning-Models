# Individual-and-Parallel-Deep-Learning-Models

[ArkajyotiSaha.pdf](https://github.com/user-attachments/files/20843408/ArkajyotiSaha.pdf)

This report evaluates the performance of individual
and parallel deep learning models on the MNIST and
CIFAR-10 datasets. Using pre-trained models-VGG16,
ResNet18, and GoogLeNet-we adapt them through trans-
fer learning with a two-phase approach: feature extrac-
tion followed by fine-tuning. We explore parallel archi-
tectures combining features from two models, defined
as f(x) = [f1(x),f2(x)] where f1 and f2 are fea-
ture extractors. Results indicate that parallel models,
such as ResNet18 + GoogLeNet, achieve a top accuracy
of 99.55% on MNIST, slightly outperforming individual
models (e.g., ResNet18 at 99.49%). On CIFAR-10, in-
dividual GoogLeNet excels at 95.17%, surpassing paral-
lel configurations like ResNet18 + GoogLeNet (94.94%).
These findings highlight dataset complexity’s impact on
model efficacy, with parallel models showing marginal
gains on simpler tasks.

## three Individual models
![image](https://github.com/user-attachments/assets/a443d08b-3da1-4dbf-acf0-1514f42c782b)


## Three Parallel Model Combinations
Your research evaluated three specific parallel combinations: ResNet18+GoogLeNet, VGG16+GoogLeNet, and ResNet18+VGG16. Each combination brings together different architectural philosophies and parameter counts.
![image (1)](https://github.com/user-attachments/assets/43b9cc86-31e7-4d92-8804-c9641688af80)

