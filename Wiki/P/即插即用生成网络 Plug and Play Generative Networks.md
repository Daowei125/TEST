# 即插即用生成网络 Plug and Play Generative Networks

**即插即用生成网络**（ PPGN ）是 Nguyen 等人在 2016 年提出的一个模型。

 PPGN 是通过近似 Langevin 采样方法，使用马尔可夫链来产生图像。  Langevin 采样器的梯度通过使用一个降噪的（ denoising ） 自动编码器来估计。 这个降噪自动编码器使用几个损失函数来进行训练， 其中包含一个 GAN 的损失。

### PPGN 的特点

- PPGN 整合了对抗训练、cnn 特征匹配、降噪自编码、Langevin 采样；

- PPGN 生成的图像同类差异化大，可根据指定生成不同类别的图像、多类化，生成的图像清楚分辨率高。

- PPGN 可使用 imagenet1000 类分类网络生成特定类别的图像。


### 参考来源：

【1】  Nguyen A, Clune J, Bengio Y, et al. Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space[C]//CVPR. 2017, 2(5): 7.

【2】  https://sinpycn.github.io/2017/05/12/GAN-Tutorial-Plug-and-play-generative-networks.html