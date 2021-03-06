# 随机梯度下降 Stochastic Gradient Gescent

**随机梯度下降**（ SGD ）是梯度下降算法的一种迭代求解思路。

SGD 是为了解决批量梯度下降法的弊端而衍生出的方法。

在 SGD 中，每次迭代可以只用一个训练数据来更新参数。


### 随机梯度下降的特点

优点：训练速度快；

缺点：准确度下降，并不是全局最优；不易于并行实现。


SGD 会最小化所有训练样本的损失函数，使得最终求解的是全局的最优解，即求解的参数是使得风险函数最小。

SGD 会最小化每条样本的损失函数， 虽然不是每次迭代得到的损失函数都向着全局最优方向， 但是大的整体的方向是向全局最优解的，最终的结果往往是在全局最优解附近。


##### 父级词：梯度下降法
##### 相关词：批量梯度下降法，小批量梯度下降法。


### 参考来源

【1】  https://blog.csdn.net/lilyth_lilyth/article/details/8973972

【2】  http://www.cnblogs.com/maybe2030/p/5089753.html