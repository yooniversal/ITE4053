## ITE4053 : 딥러닝 및 응용
### Assignment 1: 이미지 분류
Linear Layer를 사용해 **CIFAR10 dataset**을 분류합니다.<br>
- activation function : *Sigmoid*
- Optimizer : *Adam*
- *Dropout*
- [more details](https://github.com/yooniversal/ITE4053/blob/master/assignment_1/2018062733_assignment_1.pdf)

### Assignment 2: GAN - 이미지 생성
GAN 네트워크를 통해 training data 학습 후 이미지 생성하고 평가합니다.<br>
**Generator**는 fake image를 만들어내는 Generator class를 정의하고, **Discriminator**는 input이 실제 image인지 판별하는 Discriminator class를 정의합니다. 
GAN 네트워크는 이 2가지로 구성되며 서로 반대되는 특성을 가져 결과적으로 각각의 성능을 높이는 방식으로 동작합니다.
- **Generator**
  + activation function : *ReLU*
  + Optimizer : *Adam*
  + Batch Normalization
  + 2D transposed convolution
- **Discriminator**
  + activation function : *leaky ReLU*, *Sigmoid*
  + Optimizer : *Adam*
  + Batch Normalization
- [more details](https://github.com/yooniversal/ITE4053/blob/master/assignment_2/2018062733_assignment_2.pdf)
