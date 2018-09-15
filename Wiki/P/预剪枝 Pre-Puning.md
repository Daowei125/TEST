# 预剪枝 Pre-Puning

**预剪枝**是剪枝算法中的其中一类。是指在决策树生成之前进行剪枝操作。

在决策树生长过程中，对每个结点在分支前做预先估计，如果该结点的划分不能带来决策树泛化性能的提升，就停止划分并将此结点标记为叶结点。

预剪枝是剪枝操作的一种，对应的还有后剪枝，是指在决策树生成后进行剪枝操作。

### 预剪枝的常用方法：

1. 定义一个高度，当决策树达到该高度时就停止决策树的生长。

2. 达到某个节点的实例具有相同的特征向量，及时这些实例不属于同一类，也可以停止决策树的生长。这个方法对于处理数据的数据冲突问题比较有效。

3. 定义一个阈值，当达到某个节点的实例个数小于阈值时就可以停止决策树的生长。

4. 定义一个阈值，通过计算每次扩张对系统性能的增益，并比较增益值与该阈值大小来决定是否停止决策树的生长。

### 优缺点

预剪枝由于避免了不必要的节点展开，一定程度上减少决策树训练的时间和测试的时间，但是也存在欠拟合的风险。


##### 父级词：剪枝  
##### 同级词：后剪枝
    
### 参考来源：

【1】  Bramer M. Pre-pruning classification trees to reduce overfitting in noisy domains[C]//International Conference on Intelligent Data Engineering and Automated Learning. Springer, Berlin, Heidelberg, 2002: 7-12.

【2】  https://www.cnblogs.com/starfire86/p/5749334.html
