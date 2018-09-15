# 伪标记 Pseudo-label	

**伪标记**（ PL ）：利用伪标记来对目标域数据产生伪实例级标注。

给定一个神经网络，不管是 CNN 还是 Autoencoder，他们的训练过程都包含了一个分类器，当输入的样本是一个有标记的样本的时候，我们需要最小化模型输出和样本标记的交叉熵（cross entropy ），这就是监督学习，那么没有标记的怎么办，这时候就需要一个伪标记。

使用伪标记的流程示意：

![] (伪标记.png)

### 参考来源：

【1】  http://www.atyun.com/8381.html  

【2】  https://blog.csdn.net/g8015108/article/details/70941024