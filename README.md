# Brain Tumor Classification

## Overview

Binary classification of brain X-ray images of patient diagnosed with brain tumor using deep neural networks. <br>
Our results with MLP and Deep CNN models show that Deep CNN architectures are not always the solution to image classification. 

## Data
This project was carried out with data from [Kaggle's Brain Tumor Dataset](https://www.kaggle.com/preetviradiya/brian-tumor-dataset) with train-test ratio of 8:2.

**Brain Tumor**
* X-ray images of brains with tumor<br>
  ![tumor](https://github.com/Taehee-K/Brain-Tumor-Classification/blob/main/img/tumor.png)

**Healthy**
* X-ray images of brains without tumor<br>
  ![healthy](https://github.com/Taehee-K/Brain-Tumor-Classification/blob/main/img/healthy.png)

## Model

* **Multi-Layered Perceptron(MLP)**
* **LeNet** - [Gradient-Based Learning Applied to Document Recognition, 1998, (Yann LeCun Leon Bottou Yoshua Bengio and Patrick Haffner)](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf) 
* **AlexNet** - [ImageNet Classification with Deep Convolutional Neural Networks, 2012, (Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton)](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
* **ResNet16** - [Deep Residual Learning for Image Recognition, 2015, (Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun)](https://arxiv.org/pdf/1512.03385.pdf)

All of the models were trained and tested via Pytorch framework<br>
No pretrained model was used for this project


## Results

| Model | Accuracy | F1-Score |
|:-----:|:--------:|:--------:|
| MLP | 99.35% | 0.99 |
| LeNet | 97.72% | 0.98 |
| AlexNet | 94.02% | 0.94 |
| ResNet16 | 83.28% | 0.83 |
<br>

## Structure
```
Brain Tumor Classification
├── README.md
├── code
│   ├───AlexNet.ipynb
│   ├───LeNet.ipynb
│   ├───MLP.ipynb
│   └───ResNet.ipynb
│   
```